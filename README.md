# Homework-1-Code-Refactor
For this assignment I was tasked with altering this HTML file so that it follows the given accesability guidelines. 

# To do list
Continue making alt attributes starting on social-media-marketing

# Semantic HTML elements

# Logical structure and ordering of elements
The div with class hero was used to display the image digital-marketing-meeting. To a screen reader this would only appear to be a div with no extra importance. I replaced this div with img tags and applied the hero class. This resulted with no visual changes, but now will be more accessable. 


# Descriptive and concise alt attributes for each image
I will name the image and then list the alt added.

digital-marketing-meeting: Group collaborating on a shared project.

search-engine-optimization: Notebook drawing of acronym SEO surrounded by the words Content, Headings, Mobile Compatibility, Social Media, Link Building, and Backlink.

online-reputation-management: Laptop with bar graph on the screen titled Reputation.





# Heading attributes are in sequential order
The heading elements already appear in order of semantic importance in the given file. No changes were made.

# Title is concise and descriptive
Original title was "website".
New title is "Horiseon Social Solution Services"
This was chosen as it was short and described what the website was focused on displaying. This is the same description as was found in the copyright liscense at the bottom of the page.

# Other changes/bug fixes
Link at top of page to "Search Engine Optimization" did not lead anywhere. The link pointed toward an element with an id of "search-engine-optimization". I added this id to the div containing the class "search-engine-optimization". this resolved the issue.

In the div of class benefit-cost there was an unnecessary closing img tag which I removed.
