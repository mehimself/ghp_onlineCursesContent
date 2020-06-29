A course is the largest semantic unit. They bundle [__episodes__](https://github.com/mehimself/onlineCourses_content/blob/master/episodes/README.md) together and connect the learning content of [__episodes__](https://github.com/mehimself/onlineCourses_content/blob/master/episodes/README.md) with high level [__materials__](https://github.com/mehimself/onlineCourses_content/blob/master/material/README.md). 

## Course Files
Courses manifest in two files; the course file and the `list.md` file.

__The course file__  
Course contents reside in a dedicated course file named with a unique alias. Course file names are of the following format: `alias.md` where the extension `.md` specifies [markdown](https://markdown-it.github.io/)
                                                                   content and `alias` is the appropriate alias for the course.  

Aliases must fulfil the following criteria:

 - be unique (amongst courses)
 - can only use alphanumeric letters and _
 - they describe their contents to lay people 

Finding a good alias is important, because references to it should be as intelligible to any visitor as possible. Optimally a learner looking at a course reference should be able to understand what the course is about.

__Examples__ 

a bad alias: `courseAboutProgramming`

a good alias: `gitShell`

__The `list.md` file__

Each course file must be listed in `list.md` by alias or file name on its own line. Courses that are not listed here do not available to the application

## Embedding a Course

```markdown
_course(alias)
```

## Referencing a Course

```markdown
_c(alias)
```
