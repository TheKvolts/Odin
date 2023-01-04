Need a <!DOCTYPE html> at to begin.

<meta charset = "UTF" prevents bugs.>

<title> , <p> <h1-6>, 

bold: <strong>
italics: <em>
<!--- This is a comment. -->
Remember, everything basically can be nested. 
ex. <title> Hey my <strong> NAME </strong> is Kalen. </title>
Unordered Lists: <ul>
Ordered list: <ol>
bullet points: <li>

Add a link (anchor tag): <a>
HTML attribute: name and value. (two parts)
    Need to give a hyperlink reference (href) to the anchor tag.
ex. <a href= "https://www.google.com">
click me</a> 
<!--- This will redirect the button to google -->

Absolute (external) vs Relative (internal) links 
Absolute links: will always have protocol and domain.
Relative links: only include the file path.

Put ./ before links to prevent unexpected issues.

images: <img>
ex. <img src= "https://www.theodinproject.com/mstile-310x310.png">

This puts image in the main page. How do we put it in one of our tabs?
Use "../" to access a folder(directory) inside the main folder.
ex. if we want the pic to be in images, 
in a file in "images", <img src="../images/dog.jpg">

include alt attribute (alt) to describe an iamge.

