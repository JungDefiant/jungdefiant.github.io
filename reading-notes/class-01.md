# Class 01 Notes
## HTML & CSS
### HTML: Introduction
- **Web Browser:** Software used to view web pages. 
- **Web Server:** Computers that host websites.
- **Web Hosting Company:** Companies that host webpages for other companies.
- **Screen Readers:** Software used by people who are visually impaired to read the content on a screen.
- **Languages Used to Create Webpages:** HTML, CSS, PHP, ASP.NET, Java, Ruby
- **DNS:** Domain Name Resolution. This is how computers translate URL's to servers that they can connect with. On the internet, ISP's connect your computer to a wider network. You find websites through DNS servers that translate readable website addresses to one that is readable to computers. The web server than returns pages requested to your browser.

### Chapter 1: 'Structure'
- **Elements:** Content that resides in an HTML document.
- **Tags:** Indicators that enclose elements and communicates certain information to the browser. They are like 'containers' for content on the page.
- **Basic HTML Elements**
  - *html:* Indicates that the content is HTML code.
  - *body:* Indicates information inside the browser page.
  - *head:* Indicates information about the page, which is not displayed.
  - *title:* Indicates what the page displays as the name of the page in browsers.
  - *h1:* Indicates the main heading of the page.
  - *h2 or h3:* Indicates a sub-heading.
  - *p:* Indicates a paragraph of text.
- **Attributes:** Modifiers for tags that provide additional information about an element. They have a name and a value.
- **Code Management System:** These are tools, such as blogging platforms, that allow you to edit the content of the page without knowledge of coding. They often follow a specific template and have restrictions on how a page can be customized.
- **View Source:** This command lets you see the HTML code of a webpage.

### Chapter 8: 'Extra Markup'
- **HTML Elements/Attributes**
  - *!DOCTYPE:* This element tells the webpage what version of HTML is being run.
  - *!--:* This element is how comments are written in HTML.
  - *id:* This attribute distinguishes elements with a unique identity.
  - *class:* This attribute identifies one or more elements under the same identity.
  - *block:* These type of elements block out text line-by-line with specific formatting, including *p*, *h1*, *ul*, and *li*.
  - *inline:* These type of elements format text on a single line, including *a*, *b*, *em*, and *img*.
  - *div:* This element organizes several elements into a single section and blocks them together.
  - *span:* This element organizes several elements into a single action, except it's on a single line.
  - *iframe:* This element cuts out a window inside the page.
    - *src:* This attribute determines the webpage that the iframe is displaying.
    - *height:* This attribute determines the height of the iframe.
    - *width:* This attribute determines the width of the iframe.
    - *scrolling:* This attribute determines if there is scrolling inside an iframe.
    - *frameborder:* This attribute determines whether the iframe has a border.
    - *seamless:* This attribute makes the iframe look as though it's part of the document that it's embedded.
  - *meta:* This element contains information that is used by search engines.
    - *description:* This attribute describes what can be found on this page. 
    - *keywords:* This attribute describes specific words suggesting what kind of content is on this page.
    - *robots:* This attribute determines whether this page should be on search engines.
    - *author:* This attribute indicates the webpage's author.
    - *pragma:* This attribute determines whether this page is cached.
    - *xpires:* This attribute determines the date that this page expires after caching.
- **Escape Characters:** These are characters that are used by HTML, so they have special codes for using them.

### Chapter 17: 'HTML5 Layout'
- **Traditional VS HTML5:** In traditional HTML, authors would manually denote headers, pages, content, etc. using *div*, *id*, and *class*. In HTML5, standard sections became keywords, such as *header*, *nav*, and *article*.
- **HTML Elements/Attributes**
  - *header:* This element appears at the top of each page.
  - *footer:* This element appears at the bottom of each page.
  - *nav:* This element blocks off the main site navigation.
  - *article:* This element sections off individual articles, blog entries, forum posts, etc.
  - *aside:* This element has two purposes; information related to an article (but not important overall) and a container for information related to the whole page.
  - *section:* This element sections off a page or parts of an article.
  - *hgroup:* This element groups together several headings.
  - *figure/figcaption:* This element contains content that is not essential to the flow of the page, but contains a reference to information on the page. *figcaption* specifically provides a description of the content.
- **Linking Blocks:** Entire blocks of a page can be linked using *a*. This is a new feature in HTML5.
- **Older Browser Compatibility:** Older browsers may not be able to run HTML5. The use of specifying specific headers to use blocking via CSS can fix this problem for some browsers. JS use of HTML5 shiv or shim can also be used, but they require enabling of JS on browsers.

### Chapter 18: 'Process & Design'
- **Target Audience:** It's important when designing a website to ask questions related to the demographic of your site. Some characteristics to consider in your audience include age range, marital status, average income, education level, etc. For companies, considerations include position of people using the site, size of the company, company's budget, and whether the site is used for the people visiting the site or others.
- **Reasons To Visit Site:** Reasons for visiting a website include *motivations* and *goals*. Motivations determine why someone would decide to go to the site. Goals determine why someone is on the site once they visit it. You should create a list of reasons why someone would visit your site when designing it.
- **Information Needed:** You should also consider what information visitors need when visiting your site. Visitors consider your site to be more relevant when you can design it to provide the information they need. They don't need all of the information possible, only what is important and helpful to their needs.
- **Frequency of Site Visits:** Another consideration of site design is considering how often people are expected to visit your website. Websites can take a lot of resources to actively support and update. You should organize when you update your website, but this is based on how often the website is visited. Considerations include how often a product you offer is purchased or how often the information provided changes.
- **site map:** A diagram used to help organize the design of a website. They typically begin with a homepage and then break down into smaller categories that are grouped by pages on the site.
- **card sorting:** A method of designing a site map. The designer groups information that visitors would look for onto different cards, then organizes them into groups with larger categories. 
- **wireframe:** A diagram showing a visualization of a page's information flow and hierarchy of elements. This is a barebones diagram simply indicating what goes where.
- **Communicating Through Design:** The goal of a designer is to communicate information clearly through the design of visuals. They prioritize information by organizing the layout of a page's visual elements. They do this using *visual hierarchy* and grouping together elements into blocks/chunks. Visitors should be able to look at blocks or chunks and understand why the grouping is there.
- **visual hierarchy:** The order in which visual elements are organized. Contrasting elements on a page through size, color, and style allows users to skim a page and quickly find the information they need. 
- **Grouping Elements**
  - *Proximity:* Elements placed closer together are seen as being related to each other.
  - *Closure:* Elements placed in complicated arrangements are difficult to interpret, so people usually attempt to find an order.
  - *Continuance:* Elements placed in a line or curve are seen as being related to each other.
  - *White Space:* Elements placed with spacing between each other are interpreted as being unrelated to each other.
  - *Color:* Elements placed with similarly colored backgrounds are interpreted as being related to each other.
  - *Borders:* Elements placed inside a border together are interpreted as being related to each other.
  - *Consistency:* How a document is navigated can depend on the consistency of sizing, coloring, and style between groups.
  - *Headings:* These can clearly indicate how sections of informations are grouped together.
- **Site Navigation Principles**
  - *Concise:* Quick and easy to read. Not cluttered.
  - *Clear:* Prefer single descriptive words. Easy to predict where link will lead.
  - *Selective:* Navigation should be separate from other functions of site.
  - *Context:* Indicates where user is located in the site at any given time.
  - *Interactive:* Different states of interaction should be distinct and clear.
  - *Consistent:* Don't change methods of navigation from page-to-page.

## JAVASCRIPT & JQUERY
### JS: Introduction
- **Javascript & Interactivity:** JS makes page more interactive through accessing HTML/CSS content, modifying HTML/CSS content, setting rules for how the browser interacts with the webpage, and reacting to specific events on the webpage.
- **Javascript Examples:** Examples of JS include slideshows, interactive/validation forms, reloading parts of a page, and filtering data rendered to a page.

### Chapter 1: 'The ABC's Of Programming'
- **ABC of Programming**
  - *A:* What is a script and how do I create one?
  - *B:* How do computers fit in with the world around them?
  - *C:* How do I write a script for a web page?
- **Scripts:** Instructions for a computer. Computers execute scripts step-by-step.
  - *Writing a Script:* When you write a script, you need to define what you want to achieve, write down the steps needed to execute the script, and finally code the program.
- **Vocabulary:** Words understood by a computer.
- **Syntax:** The way words are constructed into instructions for the computer.
- **'Programmatically':** Refers to solving problems step-by-step.
- **Objects:** How a program models things, such as cars, houses, or people.
  - *Window Object:* An object representing a browser window.
  - *Document Object:* An object representing the content, or document, in a page.
- **Properties:** Named values that make up the data of an object.
- **Events:** Reactions coded into a program when a specific trigger occurs.
- **Methods:** Code that either returns a value (accessor) or changes a value (mutator).
- **Three Layers of Webpages**
  - *Content Layer:* HTML files are the content of a webpage.
  - *Presentation Layer:* CSS files provide rules for how HTML files are presented.
  - *Behavior Layer:* JS files define the behaviors of a webpage.
