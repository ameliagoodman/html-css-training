# html-css-training
Build your own website with this HTML, CSS and Bootstrap intro tutorial.


##What's In Here
* CSS folder (where your CSS goes)
* font-awesome folder (for cute and easy icons)
* img folder (where you keep any images)
* js folder (for javascript & jquery)
* favicon.ico (that little picture on the tab)
* index.html (where your HTML goes)
* README.md (that's what this is)


##What's what
CSS stands for Cascading Style Sheets. Basically, it's what takes the text, images, links, etc. you put in your HTML code and makes it look hot.

HTML stands for Hyper Text Markup Language, and is essentially the content of your website.

CSS and HTML work together to make a well-designed website.

##HTML: The Basics
First, you need to have what's called a "boiler plate." It's not that important TBH. But every HTML document has this, and so yours must too. It goes like this:
`<!DOCTYPE html>
<html>
<head>
<title>PUT YOUR TITLE HERE</title>
</head>
<body>
<h1> THIS IS WHERE YOUR CONTENT GOES</h1>
</body>
</html>`

The things in <> are called "tags." It lets the computer know what to expect and how to interpret it. Each tag needs to have an opening tag <> and a closing tag </> with the content in between.

The important tags (besides the ones listed above) are:
*Headers, marked by <h1> through <h6>. These make different sized headers, h1 being the largest and h6 being the smallest.
*Paragraph, marked by <p>. This is just for plain old text.
*Line break, marked by <br />. This is like pressing enter.
*Italics, marked by <i>.
*Bold, marked by <b>.
*Underline, marked by <u>.

##HTML: Adding more content
You can add images, links, lists and more.
To add an image, you use: <img src="img/path"/>. This only needs the one tag, as opposed to the opening and closing tags with everything else. The "src" stands for source, and you can put the path of the image in there.
To add a link, you use: <a href="www.google.com">Link Text</a>. 
To create a bulleted list, you can use:
<ul>UL stands for Unordered List
	<li>LI stands for list item</li>
	<li>Second item
		<ul> <li> sub-item </li> </ul>
	</li>
</ul>
To create a numbered list, you can use <ol> instead of <ul>. OL stands for ordered list.


##CSS: The Basics
CSS works by selecting specific tags written in HTML and adding design attributes to them. So you can set your every h1 header to the color white by saying:
h1 {
	color: white;
}
Like magic!