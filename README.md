## The Not So Secret Life of Rachel Flynn


<!DOCTYPE html>
<html>
<head>
	<title>Instafeed on Your Website</title>
	<style type="text/css">
		a img{ 
			width: 25%;
		}
	</style>
</head>
<body>
	<h1 style="text-align: center">Show Instagram Feed on your Website</h1>
    	<div id="instafeed-container"></div>



	<script src="https://cdn.jsdelivr.net/gh/stevenschobert/instafeed.js@2.0.0rc1/src/instafeed.min.js"></script>
	<script type="text/javascript">
	var userFeed = new Instafeed({
		get: 'user',
		target: "instafeed-container",
    	resolution: 'low_resolution',
		accessToken: 'IGQVJWWXpZAMWtMRk9iNWlhbXZAibE96MjcyajVZAWjJrX0ZAOMW5oQkQ4NEJwc2lUR3ZAqeUd1ZAE1zd0RGVElMTUc5MlJnRTl2ZADlUWmlSNkxSZAU5ja0ctWXREQkFnTFJQUDZAFM1ktemtxM2ZAOR1dJSVdObwZDZD'
	});
	userFeed.run();
	</script>
</body>
</html>


You can use the [editor on GitHub](https://github.com/rachelflynn/blog/edit/gh-pages/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/rachelflynn/blog/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
