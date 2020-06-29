# Didactic Structure and How to Use Them

## Didactic containers and representations
The onlineCourses application breaks online learning material into [markdown](https://markdown-it.github.io/) files that implement didactic units. The three main units are:
[__courses__](https://github.com/mehimself/onlineCourses_content/blob/master/courses/README.md) and [__episodes__](https://github.com/mehimself/onlineCourses_content/blob/master/episodes/README.md).

[__Courses__](https://github.com/mehimself/onlineCourses_content/blob/master/courses/README.md) bundle [__episodes__](https://github.com/mehimself/onlineCourses_content/blob/master/episodes/README.md) together and connect the learning content of [__episodes__](https://github.com/mehimself/onlineCourses_content/blob/master/episodes/README.md) with high level [__materials__](https://github.com/mehimself/onlineCourses_content/blob/master/material/README.md). 

[__Episodes__](https://github.com/mehimself/onlineCourses_content/blob/master/episodes/README.md) treat topics in more depth. They break down learning content into four didactic representations: [__material__](https://github.com/mehimself/onlineCourses_content/blob/master/material/README.md), [__example__](https://github.com/mehimself/onlineCourses_content/blob/master/examples/README.md), [__summary__](https://github.com/mehimself/onlineCourses_content/blob/master/summaries/README.md), and [__point__](https://github.com/mehimself/onlineCourses_content/blob/master/points/README.md).

[__Material__](https://github.com/mehimself/onlineCourses_content/blob/master/material/README.md)  holds verbose [markdown](https://markdown-it.github.io/) content to explore a concise aspect of a topic. It should aim to cover a handful of [__points__](https://github.com/mehimself/onlineCourses_content/blob/master/points/README.md) with informative descriptions and [__examples__](https://github.com/mehimself/onlineCourses_content/blob/master/examples/README.md) and end with a [__summary__](https://github.com/mehimself/onlineCourses_content/blob/master/summaries/README.md). 

[__Examples__](https://github.com/mehimself/onlineCourses_content/blob/master/examples/README.md) should allow learners to recognize patterns and use cases. 

[__Summaries__](https://github.com/mehimself/onlineCourses_content/blob/master/summaries/README.md) should be as brief as possible. When a learner returns to the learning material for refreshing his skills on a topic. The [__summary__](https://github.com/mehimself/onlineCourses_content/blob/master/summaries/README.md) should allow him to quickly recollect the essential points of  the [__material__](https://github.com/mehimself/onlineCourses_content/blob/master/material/README.md) viewed.

[__A Point__](https://github.com/mehimself/onlineCourses_content/blob/master/points/README.md) is the smallest unit of a learning goal. It can be a single fact, analogy, or phrase that is an essential detail of a topic.
 
## Nesting normalized learning content
For best efficiency didactic content should be defined in a single place. Thus contributions can heighten the quality of assembled content.  
 
### Example
the shell command `cd ..` is relevant across a wide variety of course material. For best results and to share the load of teaching, the material explaining the context and specifics of the `cd` command should be in a central place only. This is why course components (namely: [__courses__](https://github.com/mehimself/onlineCourses_content/blob/master/courses/README.md), [__episodes__](https://github.com/mehimself/onlineCourses_content/blob/master/episodes/README.md), [__material__](https://github.com/mehimself/onlineCourses_content/blob/master/material/README.md), [__summaries__](https://github.com/mehimself/onlineCourses_content/blob/master/summaries/README.md), and [__points__](https://github.com/mehimself/onlineCourses_content/blob/master/points/README.md)) can be __embedded__ into each other. 

#### Reference Notations

To embed a didactic unit

Embedding           | Reference
--- | ---
 _course(alias)     | _c(alias)
 _episode(alias)    | _e(alias)
 _material(alias)   | _m(alias)
 _summary(alias)    | _s(alias)
 _example(alias)    | _x(alias)
 _point(alias)      | _p(alias)

## How to contribute
 - fork this repository
 - clone your forked repository onto your computer
 - edit relevant content files 
 - commit your changes with a concise commit message stating the purpose of your changes
 - push your changes to your forked repository
 - create a pull request with this repository again stating the purpose of your changes

todo: offer [convenient versioning scripts](https://github.com/npm-scripts/scripts) 

## Trouble Shooting
### Editing Markdown files

markdown is rather forgiving, but its layout depends on whitespace

[Markdown convention used](https://markdown-it.github.io/)

caveats: too few or too many whitespace characters?
 - text that trails an image with less than two whitespace characters between them will be recognized as the image's subtitle.
  
### Editing JSON files

json files use the JSON standard.

[JSON standard](https://www.json.org/json-en.html)

caveats: 
  - comma after the last item in an array?
  - single quotes instead of double quotes?
  - forgot to quote string value?
  - typos?
  
You can use this [JSON linter](https://jsonlint.com/) to fix errors

