# **Basic structure of an HTML document**

![img1](https://stuyhsdesign.files.wordpress.com/2015/09/basic-structure.png)


The basic structure of an HTML document consists of 5 elements:

<!DOCTYPE>
 1. **< html >**
 2. **< head >**
 3. **< title >**
 4. **< body >**

# **The DOCTYPE**

A DOCTYPE declaration must be specified on the first line of each web document:

![img2](https://stuyhsdesign.files.wordpress.com/2015/09/doctype.png?w=768&h=76)

*The DOCTYPE tells the web browser which version of HTML the page is written in.  In this class, we will be using ‘XHTML Transitional’, which allows us a little flexibility.*

**The < html > Element**

Immediately following the DOCTYPE declaration is the < html > element:

![img3](https://stuyhsdesign.files.wordpress.com/2015/09/html-element.png?w=768&h=169)

The **< html >** element tells the browser that the page will be formatted in HTML and, optionally, which world language the page content is in.

**The < head > and < body > Elements**

![img4](https://stuyhsdesign.files.wordpress.com/2015/09/head-body.png?w=768&h=185)

The **< head >** element surrounds all the special “behind the scenes” elements of a web document.  Most of these elements do not get displayed directly on the web page.
The **< body >** element surrounds all the actual content (text, images, videos, links, etc.) that will be displayed on our web page.

**The < meta > Element**

Immediately after the **< head >** line, we place this **< meta >** element:

![img5](https://stuyhsdesign.files.wordpress.com/2015/09/meta-element.png?w=768&h=225)

This line declares that the document is encoded in the UTF-8 (Unicode) character set.

There can be multiple **< meta >** lines in the same web page.  The **< meta >** element is often used to provide additional information such as page keywords, a page description, and the author(s) of a web document.

**The < title > Element**

The **< title >** element defines what text will show in the web browser’s title bar:

![img6](https://stuyhsdesign.files.wordpress.com/2015/09/title-element.png?w=768&h=323)