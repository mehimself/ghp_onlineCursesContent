# Images Directory

## Markdown Image Notation
 
The [markdown](https://markdown-it.github.io/) convention to embed images is

```markdown
![placeholder text](link to image file)
```

The Url to this directory is 

`https://raw.githubusercontent.com/centre-for-humanities-computing/HOPE_website_content/master/images/` 

To embed files in this directory append the name of the image file. Avoid any special characters in the file name (even spaces) since these have to be [transformed into URL-save notations](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/encodeURI).

The full url for the image in the directory is `path_to_dir/image_name.suffix` where suffix can be jpg, gif, png, or [any other supported image file suffix](https://en.wikipedia.org/wiki/Comparison_of_web_browsers#Image_format_support)

### Example

For `testImage.jpg` the notation thus becomes:

```markdown
![missing image](https://raw.githubusercontent.com/centre-for-humanities-computing/HOPE_website_content/master/images/testImage.jpg)
```

## Image Subtitles
If you want to add a subtitle to the image leave no more than a single whitespace character between the image and the title text.
