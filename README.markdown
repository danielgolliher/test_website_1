# My Simple Test Website

A Pen created on CodePen.io. Original URL: [https://codepen.io/dgolliher/pen/KKyMZOz](https://codepen.io/dgolliher/pen/KKyMZOz).

Created via a guided practice exercise from Bloomtech: [Free Coding Course: Intro to HTML and CSS](https://learnworlds.bloomtech.com/course/beginning-your-coding-journey-html).

# Notes on the project:

If you want a great walkthrough of HTML and CSS (the foundational technologies needed to build websites!), then this course is great. I had a patchwork understanding of both, but this course knitted everything together wonderfully. From what I can tell, it would be a great intro for people without any prior exposure to HTML/CSS as well. And it's free! Take it!

# Glossary of terms
## From the course above

**<a> (anchor) tag** — The <a> tag is what defines the beginning and the end of a hypertext link. This is what we use to link from one page to another. Users click on the anchor text to reach the link target. The most important attribute of the <a> element is the href attribute, that’s what indicates the link's destination. (Without an href attribute, the <a> tag is just a placeholder for a hyperlink.)

**align-items** — In CSS Flexbox, align-items controls the alignment of items on the cross axis: which, by default, is the vertical axis. Align-items is to the vertical (or cross) axis what "justify-content" is to the horizontal (or main) axis — these sub-properties control your axes in Flexbox layout (bear in mind that when the main axis changes the cross axis changes with it). The align-items property accepts 5 different values: flex-start, flex-end, center, baseline, and stretch (default).

**alt** — When you embed an image in your web page, you’ll use this attribute to include alternate text for when the image can’t be displayed (due to a slow connection or an error in the src attribute) or for people who may not be able to see it (the visually impaired use screen readers). For example, <img src="where the image is" alt=“descriptive text about the image” />

**Angle brackets** — You’ve noticed that HTML contains little pieces enclosed in angle brackets (< >), though before now you may have known them better as “less-than” and “greater-than” symbols. These angle-bracket-enclosed pieces (called tags) aren’t visible to the user, but rather convey to the browser information about the page's structure. These brackets let the browser know where our tags start, and where they end.

**App** — Short for application. We have apps on our phones and mobile devices, but our desktops and laptops are full of apps too (though we may just call them applications). Software applications, web applications, mobile applications — all can be called apps.

**Assignment operator (=)** — You may hear developers refer to the equals sign as an “assignment operator.” This just means that they’re using the equals sign to assign a value to something — like an attribute. So by typing, <img src="where the image is"...> you're simply assigning the value (the link or path to your image) of the image location, to the src attribute.  

**Box model** — In CSS, we use the term "box model" when talking about design and layout. Not to blow your mind or anything, but virtually every element in web design is a rectangular box. The CSS box model is just a box that wraps around every HTML element. (Broadly speaking, CSS has two types of boxes: block boxes and inline boxes). 
Understanding these boxes is key to being able to create layouts with CSS or to align items on a page. CSS determines the size, position, and properties (color, background, border size) of these boxes. Every box is composed of four parts (or areas): the content area, padding area, border area, and margin area:
- Content - The content of the box: text and images.
- Padding - Clears an area around the content. The padding is transparent.
- Border - A border that goes around the padding and content.
- Margin - Clears an area outside the border. The margin is transparent.

**Browser** — Web browsers (like Google, Firefox, or Safari) are such a ubiquitous part of our modern lives that we may not even stop to think about what they are anymore, but a browser is really just a software application that we use to access the internet (someone just like you has to develop and maintain them).

**Chrome DevTools** — A set of web developer tools built directly into the Google Chrome browser. DevTools allows you to edit web pages and diagnose problems quickly. DevTools also serves as an excellent learning tool for developers in training, making it easy to "look under the hood" and experiment with the functions and mechanics of professional web development. Simply right-click anywhere on a web page and select "Inspect."

**Closing tag (or "end tag")** — Closing tags tell the browser that this particular piece of HTML content, this element, is done. You can tell most closing tags by the backslash </tagname>. Not all tags have closing tags that look like this, and some are self-closing, but this is by far the most common way to encounter them.

**Cloud-hosted** — When people say "the cloud" they really just mean "the internet." When you hear about something being hosted in the cloud, that means the data or program they're referring to is stored on internet servers rather than your personal computer's hard drive (a server is just a computer that serves information to other computers). So cloud hosting means someone else is giving you access to their computing, data, or storage resources via the internet.

**Code** — What even is code? Simply put, code is program instructions that tell a computer what to do. Just as we’ve developed a “code” for understanding each other in life (the English language in this particular case), we’ve also developed code to communicate with computers. Once you learn to the speak the language, you can tell each other almost anything!

**CodePen** — CodePen is an online code editor that lets you test out your HTML, CSS, and JavaScript code. As a testing environment (sometimes called a sandbox environment) it’s an excellent learning tool that allows you to see your HTML content render on the screen in real-time: much faster than saving your file and reloading it in the browser every time you make a change.

**Comment <!-- --> tag** — This tag allows you to leave comments in your HTML that won’t show up for the user. This is useful for planning ahead or leaving yourself reminders/placeholders for where you need to tweak or add content. You can also use it to leave notes to other developers about your code and it’s functionality. (Comments are also great for debugging in HTML because you can “comment out” HTML lines of code one at a time to search for errors.)

**CSS** — (stands for Cascading Style Sheets) is a computer language for laying out and structuring web pages. CSS is the language that tells the computer how to present all that HTML (including colors, layouts, fonts, and instructions for display on different devices). It gives the HTML some personality. Like HTML and JavaScript, it’s a cornerstone of the internet.

**CSS border** — Guess what borders in CSS do? Put borders around your content! (I love it when it means just what you think.) Borders show you where your elements begin and end. The CSS border properties allow you to specify the style, width, color, and radius of an element's border. The "border" property itself is a shorthand property that incorporates border-width, border-style, and border-color.

**CSS .class selector (.)** — In CSS, a class selector is formatted as a period (.) character followed by the name of the class. It selects all elements with that class attribute so that unique CSS styles can be applied to those specific elements.

**CSS code/rules **— CSS is a different computer language than HTML, so its look and syntax are different. A segment of CSS code is referred to as a CSS rule (similar to how a piece of HTML code is called an HTML element). A CSS rule consists of a selector, and a declaration block. The selector (like "h1") points to the HTML element you want to style. The declaration block contains one or more declarations separated by semicolons (see image below). Each declaration includes a CSS property and a value, separated by a colon. Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces. As you're writing a CSS rule, remember to frame it using three things:
- _What HTML element(s) the code applies to_ — Also known as the selector. This will be the first part your CSS code. 
- _Curly braces { } _— The opening curly brace comes right after you declare the HTML element you want this CSS to apply to. The stuff in these curly braces specifies the style you want that HTML element to have.
- _The code inside the curly braces_ — which consists of properties and values (each property/value pair makes up a declaration).

**CSS comment (/* */) **— Just like comments in HTML, the browser will not display any comments you leave in your CSS code. In CSS, comments start with /* and end with */. For example, /* This is a comment */ would only be visible to you, not the user. You can add comments wherever you want in the code (for explanatory notes or to "comment out" specific lines of code).

**CSS declarations** — In CSS, a property and value pair is called a declaration. In the example "color: red;" the property is "color" and the value is "red." The property and value are separated by a colon, and each declaration is closed by a semi-colon. Your CSS will pay attention to which declarations apply to every single element on a page to know how to lay it out and style it correctly.

**CSS display property (display type)** — The display property sets the element's display type. That is, it defines how the components (like divs, hyperlinks, headings, etc.) are arranged on the web page. Every HTML element has a default display value depending on what type of element it is. The default display value for most elements is block or inline. This property is the most important CSS property for controlling layout because it specifies if and how an element is displayed. Every HTML element is represented by a box that contains something and has space around it. The display property specifies how this box appears on the web page relative to other elements, as well as the behavior of its child elements (the elements inside it).

**CSS margin** — The "white space" around the outside of the box. Margins are used to create space around elements. To help keep them straight, remember that the border is what separates the padding (on the inside of the box) from the margin (which is the space around the outside of the box). You can add margin to specific sides (margin-left, margin-bottom, etc.) or around all four sides with the shorthand property "margin." 

**CSS padding** — The "packing paper" around your content. Padding is the space between an element's content and its border (padding creates extra space within an element, while margin creates extra space around an element). While you can add padding to each side of your content individually (padding-top, padding-right, etc.), the CSS shorthand property "padding" lets you set the padding area on all four sides of an element at once.

**CSS properties** — determine which aspect of the selector you want to change (visually). Properties are defined within selectors (see image below). In the video, we saw an example of this property/value pair: "color: red;". The word "color" is the property. It's the piece of the declaration that determines which aspect of the selector will be changed visually. You can choose to have as many properties as you like.

**CSS selectors** — A CSS selector is what selects the HTML element(s) you want to style. It's also the first part of a CSS rule. Writing "h1" before you use your opening curly brace means that you want whatever code follows to apply to the h1 HTML element and to style it accordingly.

**CSS values** — The value is what the chosen CSS property will be changed to. So if the value of a property/value pair is "red," then it would look like this: "color: red;". It would change whatever HTML element you selected (with your selector) to the color red. Every time you use a property (like "color"), you must give it a value (in this case "red") — and certain properties can only accept certain values.

**Curly braces { } **— Also known as "curly brackets" or just "braces," come right after whatever HTML element you've said you want to apply style to. Braces mark the beginning and end of the CSS code that's specifying your style. You need both an opening curly brace and a closing curly brace to write valid CSS (remember — syntax matters!)

**Deploy** — In programming, deploy means moving a system from the testing phase to the production phase. In development, “production” means — real people are using it to do real work. So deploying a website means doing everything you need to do to make your website available for use — getting it up and running. You know it’s been deployed when it’s been delivered from developers to users.

**Developer** — In our industry, developer is usually short for software developer or web developer, that is, someone who creates software or builds websites. You’ll hear developer used interchangeably with terms like computer programmer, coder, and software engineer, to name a few.

**display: block **— In CSS, this means that the element is displayed as a block, starting on a new line and taking up the whole line (stretching as far to the left and right as it can). Block-level elements span the entire width of the page unless another width is specified; this means that a block will have some whitespace above and below it and won't allow other HTML elements next to it (except when ordered otherwise — by adding a float declaration to another element, for instance). Some examples of block-level elements include <div>, <p>, <form>, <h1> (or any header), <footer>, and <section>.

**display: flex **— The flex property in CSS is the combination of (or shorthand for) the flex-grow, flex-shrink, and flex-basis properties. The flex property is responsive and mobile friendly. "display: flex" is used to set the length of flexible items (if the element is not a flexible item the flex property has no effect) and makes it is easy to position child elements in the main container. 

**display: inline** — In CSS, this means the element can be displayed with floating content on its left and right side (a block element fills the entire line — nothing can be displayed on its left or right). Inline elements don't start on a new line and only take up as much width as necessary. They don't break the flow of content — multiple inline elements can exist on the same line if there's space. Some examples of inline elements include <span>, <a>, and <img>.

**<div> tag **— A <div> is a generic container. It defines a division or a section (and was one of the only ways to do so before the <section> tag was introduced) which can then be styled with CSS or manipulated with JavaScript. It can help us group or separate out our data — any sort of content can be put inside a <div>. By default, browsers will insert a line break before and after a <div> element. The <div> tag can be useful for styling purposes or as a scripting convenience. (A general rule is that the <section> element is appropriate only if the element's contents would be listed explicitly in the document's outline.)

**DRY principle** — The DRY principle (“don't repeat yourself”) is a development concept aimed at reducing repetition and redundancy in coding patterns. Can you make your code less cumbersome? How often are you copying and pasting chunks of your own code? When you have to update duplicate snippets of code in multiple locations it makes your code much harder to maintain. Duplication bloats your codebase —   resulting in more opportunities for bugs and adding unintended complexity to the system. Simpler, cleaner code is easier to reproduce and easier to parse — not just by others, but by future you as well. Clarity should be a constant goal.

**Flexbox** — The Flexible Box Layout Module helps provide a more efficient way to lay out, align, and distribute space among items in a container, even when the size is unknown and/or dynamic (thus the word “flex”). The main idea behind the flex layout is to give the container the ability to alter its items’ width/height (and order) to best fill the available space, mostly to accommodate all kinds of display devices and screen sizes. A flex container expands items to fill available free space or shrinks them to prevent overflow. The flexbox layout is direction-agnostic as opposed to the regular layouts (block which is vertically-based and inline which is horizontally-based). While those work well for pages, they lack flexibility (pun intended) to support large or complex applications (especially when it comes to orientation changing, resizing, stretching, shrinking, etc.).

**Font-family** — The font-family property in CSS specifies the font for an element. You can add multiple font name values for each font-family property — alternatives the browser can use if it doesn't support your first choice. Because of this, you generally start with the name of the specific font you want, then end with a generic font-family name. Be sure to separate each font value with a comma (font-family: Arial, sans-serif;). There are two types of font family names: a specific family name like "times," "courier," or "arial"; and a generic family name like "serif," "sans-serif," "cursive," or "monospace."

**Gutter** — The grey margin on the left of a code editor (these gutters can also be disabled) that displays line numbers and tags lines of code with different markers. Gutters can also refer to the alleys or spacing between content tracks — the margins, padding, or gaps between content.

**<h1> tag** — This is the tag for the top-level heading in HTML. Guess what the 2nd level heading is? Yup, <h2>. And header 3 would be <h3>, and so on through <h6>. <h1> defines the most important heading — the main heading/subject for the whole page — and <h6> would define the least important heading. You should only use one <h1> per page.

**Hex color codes** — or "hexadecimal colors," are color values supported in all browsers. A hexadecimal color is specified with: #RRGGBB. RR (red), GG (green) and BB (blue) are hexadecimal integers between 00 and FF specifying the intensity of the color. For example, #0000FF is displayed as blue, because the blue component is set to its highest value (FF) and the others are set to 00.

**href (hypertext reference)** — href is an attribute of the <a> (anchor) tag; it’s what specifies your link’s destination. You need it to link to another page. If there’s no href attribute, then it’s not a hyperlink. (It goes inside the opening tag of your <a> element.)

**HTML** — the fundamental building block of every web page and web application on the internet. HTML stands for “hypertext markup language.” So what’s hypertext? And what’s a markup language? Glad you asked. Hypertext is the text displayed on a computer that links you to somewhere else when you click on it (“link” is just short for hyperlink). A “markup language” is a language you use to annotate a document so it displays a certain way on your computer. Unlike a “programming” language, which is used to execute tasks, a markup language is simply designed to format or graphically display your content. Your web browser reads the HTML on a web page to know what information it’s supposed to display and how.

**HTML attribute** — An attribute helps describe an element: provides additional information about it. They’re like special words that control the element’s behavior. You’ll always specify your attributes in your opening tag. Attributes usually come in name/value pairs like: name="value" (for example, while the <img> tag is used to embed the image, the src attribute in the <img> element specifies the path to the image — tells us where to find it).

**HTML classes** — Classes are used to group things together. Specifically, grouping elements that you want to apply the same style properties to. The class attribute can be used on any HTML element. The most common use for HTML classes is CSS styling. Create a specific style, assign it to a particular class in HTML, then simply add that class name to any elements you want to inherit that style. Syntax-wise you'd write it like this: <div class="bigger">Wash your hands!</tag>.

**HTML element **— Elements are the building blocks of HTML. An HTML element is simply a start tag, whatever content you have, and an end tag. Everything that falls between the start tag and end tag (including the start tag and end tag) is the element.

**Hypertext** — Hypertext is the text displayed on a computer that links you to somewhere else when you click on it. It’s the text that’s been turned into a link. As you click those links, you’re jumping between “hypertext documents” that are interconnected by “hyperlinks” (link is short for hyperlink).

**<img> tag **— This is the tag you use to add an image to your HTML page. Fun fact, images aren’t technically inserted into a web page — they’re linked to web pages; the <img> tag just creates a sort of holding space for the referenced image. The <img> tag has two required attributes: src — this specifies the path to the image, and alt — this specifies “alternate” text that describes the image, in case the image can’t be displayed for some reason.

**JavaScript (JS)** - JavaScript is a programming language used in web development that helps make web pages interactive. Where HTML and CSS are languages that give a web page structure and style, JavaScript gives a web page engaging and dynamic interactive elements. Web pages would be pretty boring if they just sat there displaying static information all the time.

**justify-content** — The CSS justify-content property is a sub-property of the Flexible Box Layout module (flexbox). It defines how the browser distributes space between and around content items along the main-axis of a flex container. It helps distribute extra free space leftover when either all the flex items on a line are inflexible, or are flexible but have reached their maximum size. Flexbox makes it easy to vertically align a box. The justify-content property accepts five different values: flex-start, flex-end, space-between, space-around, and space-evenly.

**margin: auto **— In CSS, "margin: auto" instructs the browser to adjust the horizontal margin automatically based on the viewable area (remember, margins are used to create space around elements). This is often used to center an element.

**Markup language** — A computer language you use to annotate a document so it displays a certain way on your computer. Unlike a programming language, which is used to execute tasks, a markup language is simply designed to format or graphically display your content. Your web browser reads the HTML on a web page to know what information it’s supposed to display and how.

**Nesting** — Nesting is when we put one element inside of another. Nested elements are referred to as “children” and their top-level elements as “parents.” If HTML elements are the boxes that hold your content, then it stands to reason that you could put one box inside of another.

**Normal flow** — Normal flow (or flow layout) is simply the standard way in which elements are positioned on a web browser (before you've made changes to the layout with CSS). Generally, the elements are positioned from top to bottom and left to right. The elements in CSS are either block-level elements or inline elements. In the normal flow, block-level elements stack on top of one another and inline elements fill the available space (multiple inline elements can occupy the same line, but each block-level element takes up its own line). When the browsing window is resized, the block elements expand or contract to the new width, and the inline content reflows to fit. Objects in the normal flow influence the position of the surrounding content (sibling elements).

**Opening tag** — (or "start tag") goes at the beginning of your HTML element. It’s what get’s your element started. The basic structure of an HTML document includes tags, which surround content and apply meaning to it. The opening tag is what kicks things off and tells the browser that everything between this opening point, and the </html> closing tag, is an HTML element to interpret.

**<p> tag **— The p stands for paragraph. Paragraphs are usually blocks of text, but they can be any group of related content, like images or form fields. When you surround a chunk of content with <p> tags, your browser will automatically add a blank line before and after it to give it a little space from the other stuff — since you said it was its own paragraph.

**Path** — Path just means 'where a computer searches for a file or a program.' A “file path” for example could describe the location of a file in a web site's folder structure. So when we talk about a “source path” for our src attribute in the <img> element, we’re just talking about the “path” the browser takes to get us to the source (the external link).

**Pixels** — A pixel is the smallest unit of a digital image that can be displayed, represented by a dot or square on a monitor/screen. We combine a bunch of pixels to form a complete image, video, text — really any visible thing on a computer display. It’s also known as a picture element (pix = picture, el = element). Pixels are the basic building blocks of a digital image and are created using geometric coordinates. Depending on the graphics card and display monitor, the quantity, size, and color combination of pixels varies and is measured in terms of the display resolution. For example, a computer with a display resolution of 1280 x 768 will produce a maximum of 98,3040 pixels on a display screen.

**Responsive web design (responsive units)** — Responsive web design (RWD) refers to the use of HTML and CSS to ensure your web page looks good on any device. As more diverse screen sizes became available, a set of practices developed to allow web pages to alter their layout and appearance to suit different screen widths, resolutions, etc. (on a phone users might see content in a single column, whereas a tablet might show the same content in two columns). Ideally, your web page should be able to resize, hide, shrink, enlarge, or move content in its layout so it displays well regardless of the device being used to view it — automatically adjusting for everything from device specifications to viewports. Ultimately, it's about anticipating and responding to the needs of your users.

**<section> tag** — Guess what the <section> tag does? Defines sections! Don’t you love that? The content on your web page may contain chapters, headers, footers, or other sections that could benefit from a more organized <section> tag. In terms of its difference from a <div> tag, <section> means that the content inside is grouped (i.e. relates to a single theme), and would appear as an entry in an outline of the page. <div>, on the other hand, does not convey any meaning in itself.

**Semantic HTML/tags** — Semantic HTML just means HTML whose function or content is obvious by its name. The term "semantic" refers to how we draw meaning from words, so "semantic elements" are elements that clearly describe their meaning to the developer and the browser. <div> and <span> would be examples of "non-semantic elements," as their names tell us nothing about their content. Whereas, <h1>, <section>, and <form> all make it clear what they're for, what purpose they serve in the document.

**Serifs** — Serifs are details or small decorative flourishes on the ends of certain strokes that make up letters and symbols. Some notable examples of serif fonts include Georgia, Garamond, Times New Roman, and Baskerville. Sans-serif fonts (like the Arial font) do not have these details or flourishes.

**src (source) **— The src attribute in the <img> element tells us where the image is coming from. Remember, web pages don’t literally contain the images, they link to them. The src attribute specifies the path to the image you’re trying to embed (points you to the external file or resource).

**Syntactic sugar** — Syntactic sugar is syntax in a programming language that makes the code easier to read, express, or understand. Anything that makes it "sweeter": expressed more clearly, more concisely, or in a preferred style.

**Syntax** — the rules we follow to accurately express ourselves in a language. Unlike human language (which we often still understand despite poor syntax) computer languages require precisely accurate syntax in order to understand. If we don’t write our code according to the rules, the computer or browser won’t know how to interpret it. 

**Target attribute **— The <a> target attribute specifies WHERE to open the link. Depending on what you tell it to do, it can open your link in the same window, a new window, a new tab, etc. It will look something like this: <a target="_blank"> (this particular value will open the link in a new window or tab).

**Typography** — When we talk about typography in CSS, we’re talking about how your text looks on screen. Typography encompasses a lot — and not just which font you use or whether it’s italic or not. It’s also about the space around and between letters, words, and lines, the size difference between blocks of text in relation to one another, even the history behind various font families.

**Unicode** — A computing standard for consistently encoding symbols (used to display any symbol or character). It’s a universal standard that assigns a code to every character and symbol in every language in the world. You can take this unicode, drop it into your HTML, and your browser will render the image. Pretty useful.

**URL** - A URL is just the address of web page. Just like you need an address to find a physical location in the world, you’ll need an address to access a digital location on the internet.

**Viewport **— The viewport is the area of the web page that is viewable to the user. The viewport varies based on a number of things, including the size of the device (it will obviously be smaller on a cellphone than on a computer screen), whether the browser's in fullscreen mode, whether the user's zoomed in or not, etc. The viewport is generally the same as the browser window, excluding the UI, menu bar, and anything's that's not the web page itself. Simply put, it's the section of the web page that's currently visible.
