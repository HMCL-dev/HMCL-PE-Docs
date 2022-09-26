# HMCL-PE-Docs

Documentations for HMCL-PE

You can submit a Pull Request to this repository to contribute.

## How to contribute

Please place your markdown file at
```
_<category>/<article>.md
```
If your doc contains images, please place your images at
```
assets/img/docs/<article>/<image>.img
```

<category> means your article category, such as **launcher**, **modpack**.

<article> is your article name.

<image> is the image you are using in your article.

### Add new article

Please ensure that the content is stored in the above format.

Not to modify the content of other articles in a PR that adds a new article.

### Modify an existing article

Please make sure that your PR modifies only one article, and attribute in that article.

### Update index.json

Add an object to target category item like this:
```
{
    "title": "Example", // Whole title of the passage.
    "subtitle": "Example", // Subtitle of the passage.
    "path": "/_<category>/<title>.md" // Path of the passage.
}
```
So we can display the passage on our website.