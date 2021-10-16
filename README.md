# 1.3 software requirements
 - Chrome Browser
 - VSCode(>IDE)
 - GitHub Desktop(>Git cli)
 
# 1.5 Understanding HTML
  - Website is just text of code
  - Browser read the text of code and configure it
  - Website is consist of two(or three) kind of language: HTML, CSS, JavaScript
  - HTML: tells the browser how the content is structured
  - CSS: tells the borwser what the content should look like
  - JavaScript: enables interactivity
  
# 2.0 Trivial Convention
  - keep HTML filename as 'lowercase'
  - when doublequote(`"`) finish with doublequote
  - specific attribute are only used in specific tags
  - make sure to use semantic tag to make the meaning of code more clear
  - Search HTML Tag on MDN(Mozillia Developer Network)

# 2.2 introduction to HTML Tag
  - Basic Syntax: `<[TAGNAME] [ATTRIBUTE]="[VALUE]"> ~ </[TAGNAME]>`
  - HTML Tag looks like: <~>
  - 'Content' should be position in between tags
  	`<~> ~ </~>`
  - Attribute: add additional information to tag
  - Attribute position next to tagname and seperated with whitespace
  	`<[TAGNAME] [ATTRIBUTE]>`
  - Attribute has boolean value can omit value(because it always has default enabled)
  	`~~`
  - Tag doesn't require text could be 'self-closing tag'
  	`<img ~ />`

# Structure of HTML file
  1. Every HTML start with `<!DOCTYPE html>`
  2. Open HTML `<html>~</html>`
  3. `<html>` is consist of two parts:
  	- `<head>`: configures the website from backstage
	- `<body>`: content which the user will see

# Common `<head>` HTML Tag Example
   - `<title>`: Name Website Name appeared on TabName
   - `<meta content="~" name="~" />`: describe extra information about website
   - `<meta charset="~" />`: default "utf-8"
   - `<meta lang="~" />`: default "kr"
   - set tab icon image
   		- `<link rel="shortcut icon" href="~" />`
   - set coverimage when share link on kakaotalk
		- `<meta property="og:image" content="~" />`

# Common `<body>` HTML Tag Example
 - text
 	- title: `<h1> ~ <h6>`
	- paragraph: `<p>`
	- style
		- `<strong>`
		- `<sup>` or `<sub>`
 - list
 	- there are two kind of list:
		- unordered list(`<ul>`)
		- ordered list(`<ol>`)
 	- for item, `<li>`
 - hyperlink
 	- `a` stands for anchor
	- a requires href(hyperlink reference) attribute
	- `<a href="~">~</a>`
	- a can have optional attribute: target
	  - `_self`: default. replace the originial one
	  = `_blank`: appear on new tab
  - image
  	- `<img src="~"/>`
	- attribute
		- src(source): image source as link
  - forms
  	- input: `<input type="~" />`
		- attrib: type
			- type="text"(default)
			- type="color"
			- type="file"
				- accept="[FILE_EXTENSION]"
				- For all image: "image/*"
			- type="url"
			- type="email"
			- type="date"
		- textbox
			- type="text"
			- type="password"
			- placeholder="~"
		- button
			- type="submit"
			- value="~"
		- other attribs
			- required
			- disabled
			- minlength
			- maxlength
	- label: `<label for="~">`
		- `<label>` works with `<input>`
		- make sure 'for' and 'id' value should be same
		- <label for=> & <input=id=>
		
# 2.9 class and id attrib
  - class
  - id
	- id's value should be unique in whole document
	- one id per one element

# 2.10 
  - `<div>`
  	- it's just a container
  - `<span>`
    - div can be semantic tag to make precise what usage has
  - `<header>`
  - `<main>`
  - `<footer>`
  - `<nav>`
  - `<section>`

## Path Notation
	- ..
	- /
	