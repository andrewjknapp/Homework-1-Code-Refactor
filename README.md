# Homework-1-Code-Refactor
For this assignment I was tasked with altering this HTML file so that it follows the given accesability guidelines. 

## Semantic HTML elements
Changed div of class header to a header element along with all header class selectors in style.css
Changed div of class footer to a footer element along with all footer class selectors in style.css
Changed div of class contents to the main element along with the corresponding contents class selectors
Changed div of class benefits to an aside element along with the corresponding class selectors in style.css
Changed div containing navigational ul to a nav element along with corresponging class selectors in style.css
Replaced each div element within the main element and aside element with section element tags
Changed name of class hero to banner-image to match what it is applied to.


## Logical structure and ordering of elements
The div with class hero was used to display the image digital-marketing-meeting. To a screen reader this would only appear to be a div with no extra importance. I replaced this div with img tags and applied the hero class. This resulted with no visual changes, but now will be more accessable. 

Reorganized the css to group selectors pertaining to the header, main, aside, and footer in that order.


## Descriptive and concise alt attributes for each image
* digital-marketing-meeting.jpg: Group collaborating on a shared project.

* search-engine-optimization.jpg: Notebook drawing of acronym SEO surrounded by the words Content, Headings, Mobile Compatibility, Social Media, Link Building, and Backlink.

* online-reputation-management.jpg: Laptop with bar graph on the screen titled Reputation.

* social-media-marketing.jpg: A table covered with captions which say tweet, media, like, and share.

* lead-generation.png: Icon of gear pointing toward a dollar sign signifying the automation of generating website traffic.

* brand-awareness.png: Icon of buisnessman with a lightbulb for a head.

* cost-management.png: Icon of a gear surrounded by dollar signs.


## Heading attributes are in sequential order
The heading elements already appear in order of semantic importance in the given file. The title/logo was given the h1, section titles within the main content were given the next rung of importance h2, and the section titles in the aside were given h3. No changes were made.


## Title is concise and descriptive
Original title was "website".
New title is "Horiseon Social Solution Services"
This was chosen as it was short and described what the website was focused on displaying. This is the same description as was found in the copyright liscense at the bottom of the page.


## Other changes/bug fixes
* Link at top of page to "Search Engine Optimization" did not lead anywhere. The link pointed toward an element with an id of "search-engine-optimization". I added this id to the div containing the class "search-engine-optimization". this resolved the issue.

* In the div of class benefit-cost there was an unnecessary closing img tag which I removed.

* Added whitespace between some of the large blocks of code for better readability.

* Reduced css selector "header h1 .seo" to ".seo" as a class selector is specific enough on its own.

* Changed css selector "nav ul" to ".nav-list" and added the class where necessary to reduce dependency

* Condensed benefit-lead, benefit-brand, and benefit-cost into the class aside-section

* Condensed search-engine-optimization, online-reputation-management, and social-media-marketing into the class main-section

