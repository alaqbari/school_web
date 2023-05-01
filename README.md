# school_web
this is school registration system. 

Peace, mercy, and blessings of God be upon you. Today,
 I finished my project, 
which I had been writing for a long time. It is not a big, 
huge project. Rather, 
it is a small project that I wanted to hand over to my dear teacher. After that, 
this project is a project built in three languages or one language, 
three things, and two other things like html, css, and java. Script As for that, 
my project is called Kool Web. It is a project that tells about or is built about to register students, 
and the one who records students finds all the information in an arranged table and can delete or renew it. Therefore, 
he uses many things and simplifies many things for the business owner, 
God willing. I hope it will be useful. This project and to receive the certificate after sending this project, 
God willing, the Most Gracious, may God’s prayers and blessings be upon him

I categorize my project in five the first one is the home page the home page is where the person comes and to look at what the system looks like it's in the logo and the name of the organization and when you click on the contact in the contact is money links like registration and data when you are clear that registration you see The form that the person puts is and the bad name and phone number and education level and then you click on the data link you can see the data boot into where you are. To delete personally and you can update the data personally, well, I finish the home page, contact, receive registration, data, and the last one talks about who creates this system or what this system looks like or what the system does well and this system is half of the footer footer writes the time of writing the system and the name of the system The difference is thank you good life

I'm a beginner I understand something in the course I don't have a team to do with me the project and I do the project visually I thank all the teachers and students
This is an HTML file that contains the structure of a website. The code uses the HTML5 doctype declaration, indicating the HTML version used. The `<html>` tag starts the HTML document, with the "lang" attribute set to "en" to specify the document's language. The `<head>` element follows the `<html>` tag and contains metadata for the document. It includes a `<meta>` element with "charset" attribute set to "UTF-8" which declares the character encoding for the document.[[1](https://www.w3.org/International/questions/qa-html-encoding-declarations)][[3](https://stackoverflow.com/questions/4696499/meta-charset-utf-8-vs-meta-http-equiv-content-type)]

The head section also includes a viewport meta tag that specifies how the website should be displayed on different devices. It sets the width of the viewport to the device's width, scales the page to fit the device's screen size, and sets the initial zoom level to 1.0.[[2](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)]

The code also contains links to an icon image and a stylesheet, respectively, to be used by the webpage. The icon image will appear on the browser tab when the webpage is loaded, and the stylesheet controls the webpage's visual presentation. The `<title>` tag specifies the title of the webpage, which appears on the browser's title bar.[[2](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)]

The body section of the webpage contains the main content of the webpage. It starts with a header section containing the webpage's logo, navigation bar, and horizontal line. The navigation links will take the user to different pages within the website. The main section contains a `<section>` element, which consists of a `<div>` element and an `<aside>` element, followed by a footer section containing a `<p>` element that displays the copyright.

In summary, this HTML file is a basic structure for a website, with a header, main, and footer sections containing different elements, including links to images and stylesheets, navigation links, and content sections.[[1](https://www.w3.org/International/questions/qa-html-encoding-declarations)][[2](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)][[3](https://stackoverflow.com/questions/4696499/meta-charset-utf-8-vs-meta-http-equiv-content-type)]



The provided code represents an HTML page with basic structure, including a header, a main section, and links to other pages. The `meta` tags in the `head` section specify important information about the document, such as the character encoding and the viewport size. The `link` tag refers to an external CSS stylesheet that styles the document, while the `title` tag sets the title of the page. The `body` tag contains the main content of the document, divided into `section` elements with `h1` headers. 

The first `meta` tag specifies the character encoding of the document as UTF-8. This ensures that the browser can correctly render non-ASCII characters entered by the user in forms and URLs generated by scripts [[1](https://www.w3.org/International/questions/qa-html-encoding-declarations)]. The second `meta` tag sets the `X-UA-Compatible` value to `IE=edge`, which instructs Internet Explorer to render the page using the latest version available. The `viewport` meta tag sets the width and initial scale of the viewport, which affects how the document is displayed on different devices. The `link` tag specifies the location of an external CSS stylesheet that styles the document. The `title` tag sets the title of the page, which appears in the browser's title bar and bookmarks.

The document body contains a `header` element that includes a logo image and a navigation bar with links to other pages. The navigation bar is styled using CSS classes defined in an external stylesheet. The `main` section contains two `section` elements with `h1` headers. The first `section` element contains a block of text with information about the system. The second `section` element contains a registration form with several input fields and a submit button.

In summary, the provided code is a basic HTML page that sets important metadata about the document using `meta` and `link` tags in the `head` section. The `body` section contains the main content of the document, including a header with a navigation bar and two sections of content. The document is styled using an external CSS stylesheet.


The provided code is an HTML document with a basic structure that includes the necessary elements for creating a webpage. 

The `<!DOCTYPE html>` declaration defines the document type and version of HTML being used. 

The `<html>` element encloses the entire HTML document and contains two main sections, the `<head>` and `<body>` elements. 

The `<head>` element contains metadata about the HTML document, including the page title, links to external resources, and information about the character encoding used. The character encoding is specified using the `<meta>` element with the attribute `charset="UTF-8"`. This ensures that the document can handle non-ASCII characters entered by the user and displayed on the webpage [[1](https://www.w3.org/International/questions/qa-html-encoding-declarations)]. 

The `<body>` element contains the visible content of the webpage, including headings, paragraphs, images, and links. In this code, the content is structured using semantic HTML elements such as `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>`. 

The code also includes references to external resources using the `<link>` element to link to a CSS file and the `<img>` element to display images. 

Finally, the code includes comments within the HTML code using the `<!-- -->` syntax to provide additional information or clarify the purpose of specific elements or sections. 

Overall, this code provides a basic template for creating a webpage and includes essential elements required to create a functional and accessible website.

The provided code is a JavaScript program that allows users to create, read, update, and delete student data in a table format. The program uses the document object model (DOM) to access and manipulate HTML elements on a web page. 

The code begins by defining variables for various form elements such as the name, phone, age, and parent name fields using the `getElementById` method [[1](https://www.tutorialspoint.com/How-to-work-with-document-forms-in-JavaScript)]. It also creates a variable to track the current mood, which is initially set to "create". 

The code then creates an object to store the student data using a loop to parse data from the local storage. When the user clicks the "create" button, the code creates a new object with the entered data and adds it to the student data array. If the mood is set to "update", the code updates the object at the specified index. The student data is saved to local storage using the `setItem` method. 

The code also includes functions to clear data, display data in a table format, delete individual or all student data, and update existing data. These functions manipulate the HTML table and local storage based on user interactions.

The code has some commented-out functions that appear to be intended to implement search functionality based on name or phone number. However, these functions are not currently being used.

Overall, the provided code is a simple student data management system that demonstrates the use of DOM manipulation, local storage, and basic JavaScript programming concepts.

The provided code appears to be a basic template for a web page. The code sets various styles for different elements in the page. Here's a breakdown of the styles applied in the code:

1. `*` selector sets the margin and padding to 0 for all elements on the page.
2. `font-family` is set to Arial, sans-serif for all elements.
3. `text-decoration` is set to none for all elements.
4. `box-sizing` is set to border-box for all elements. [[1](https://stackoverflow.com/questions/46923610/css-resetting-margin-and-padding)]
5. `:root` selector sets custom CSS variables for font color, background color, and another color.
6. `body` selector sets the width to 80% and centers the element using auto margin. It also sets the background color and list style to none.
7. `header` selector centers the text.
8. `.head-section` class sets the styles for a section in the header including flex display, font family, font size, font weight, and color.
9. `.logo img` and `.logo h1` classes set the styles for the logo image and its heading respectively.
10. `ul` selector sets the styles for an unordered list including flex display, color, and list style.
11. `ul li` selector sets the styles for list items in the unordered list.
12. `li a` selector sets the styles for anchor tags within list items.
13. `li a:hover` selector sets the styles for anchor tags within list items on hover.
14. `hr` selector sets the styles for the horizontal line.
15. `section` selector sets the styles for the main section including padding, background color, margin-top, overflow, border, border-radius, and height.
16. `.div-section` class sets the styles for a section in the main section including width, height, background color, position, animation-name, animation-duration, animation-delay, animation-timing-function, animation-iteration-count, and animation.
17. `.h-a-o h2` and `h2 span` selectors set the styles for a heading and its span within the main section.
18. `.h-a-o h3` selector sets the styles for another heading within the main section.
19. `.footer` class sets the styles for the footer element.

Sources:
- [1] https://stackoverflow.com/questions/46923610/css-resetting-margin-and-padding
