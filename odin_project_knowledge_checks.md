# How does the web work

- What is a network?
    A collection of connected computers.

- What is the internet?
    The hardware that physically connects various networks.

- What is an IP address?
    An address made up of 4 numbers seperated by `.` to denote a location on a network.

- What is a router?
    A special computer that directs data among various networks.

- What is an ISP?
    A company that manages many routers to connect many networks. Even those of other ISPs.

- What are packets and how are they used to transfer data?
    Packets are data that has been broken into smaller chunks to be routed through the internet to their destination.

- What is a client?
    A client is a machine that accesses the internet via an ISP and makes requests to servers.

- What is a server?
    A server is a machine that hosts websites or other applications.

- What is a web browser?
    A web browser is an application used by a client to access the web.

- What is a search engine?
    A search engine is a website that helps users find other websites.

- What is a DNS request?
    During a DNS request a domain name is resolved to an IP address.

- What browser are you currently using?
    Brave

- In your own words, explain what happens when you run search on google.com.
    During a google search the google search engine service looks through all of the pages it has indexed and returns what it believes are the best matches for your request.


----

# Command line basics

- What is the command line?
    A way to directly interactive with the computer.

- How do you open the command line on your computer?
    With super key and t. `<S-t>`
    
- How can you navigate to a particular directory?
    By using the `cd` command. `cd /some/path`
    
- Where will `cd` on its own navigate to?
    To your home directory.
    
- Where will `cd ..` navigate you to?
    It will take you one directory up.
    
- How do you display the name of the directory you are currently in?
    With the `pwd` command.
    
- How do you display the contents of the directory you are currently in?
    With the `ls` command.
    
- How do you create a new directory?
    With the `mkdir` command. `mkdir something`
    
- How do you create a new file?
    With the `touch` command. `touch something`

- How do you destroy a directory or file?
    With the `rm` command. `rm target`
    
- How do you rename a directory or file?
    With the `mv` command. `mv something somethingnew`
    
----

# Intro to Git

- What kind of program is Git?
    Git is a versioning program. You can look back at how a file has changed over a series of commits.

- What are the differences between Git and a text editor in terms of what they save and their record keeping?
    A text editor will overwrite the file that is being worked on so changes are lost. Git adds changes so even if something is changed it will show you when and where the change was made.

- Does Git work at a local or remote level?
    Git works at the local level.

- Does GitHub work at a local or remote level?
    GitHub works at the remote level.

- Why is Git useful for an individual developer?
    Git is great for individuals as they can see their work over time and revert to previous versions if need be.

- Why are Git and GitHub useful for a team of developers?
    Git is great for teams for the same reasons as individuals but also the merge feature allowing a group to divide work then pull all of those changes together in a coherent manner.

----

# Git Basics

- What is the Git command used to get a full copy of an existing Git repository from GitHub?
    `clone`

- What is the Git command used to check the status of your files?
    `status`

- What is the Git command used to track files with Git?
    `add`

- What is the Git command used to remove tracked files with Git?
    `remove`

- What is the Git command used to commit files?
    `commit`

- What is the Git command used to view your commit history?
    `history`

- What is the Git command used to upload projects onto GitHub?
    `push`

- Explain the two-stage system that Git uses to save files.
    With the two-stage system you can commit files as they are ready and progressively add more.
    
- Explain what `origin` is in `git push origin main`.
    The `origin` parameter refers to where the repository.
    
- Explain what `main` is in `git push origin main`.
    The `main` paramter is the remote branch to be commited to.

----

# Practicing Git Basics

- How do you create a new repository on GitHub?
    To create a new repository on GitHub you first sign into you account. Find where it says `Repositories` and new, then click new and follow the wizard.

- How do you copy a repository onto your machine?
    By using `git clone /the/url`

- What is the default name of you remote connection?
   `git@github.com:cvissing/git_test` 

- How to you check the status of your current repository?
    `git status`

- How do you add files to the staging area an add a descriptive message?
    `git add FILE`
    `git commit -m "Message"`

- How do you push your changes to your repository on GitHub?
    `git push origin main`

- How do you look at the history of your previous commits?
    `git log`

----

# Intro to Front End

- Which language is responsible for the semantic structure of a document?
    HTML

- Which language can change the font, text-size, or background-color of an element?
    CSS

- Name a few behaviors that javascript can be responsible for on a a website.
   APIs, dynamic elements, and graphics 

- What is the purpose of an opening tag and closing tag in an HTML element?
    The purpose of the open and closing tags in HTML is to tell the browser how interpret the content enclosed by the tags.

- What is the selector in a CSS ruleset?
    The selector identifies the element to be styled.

- What is the property and property value in a CSS ruleset?
    The property is a style of the element to be effected such as the color of text. The property value in this example would be the chosen color.

- What is the declaration in a CSS ruleset?
    The declaration is the combined property and property value.

- How do you reference a file in the same directory as your HTML file?
    `file`
- How do you reference a file in a directory below your HTML file?
    `below/file`
- How do you reference a file in the directory above your HTML file?
    `../file`
    
----

# HTML and CSS basics

- What is the difference between HTML and CSS
    HTML is the scaffolding of the webpage where as CSS handles the styling of webpage.

- For accessibility in HTML, what is the attribute used to describe an image (on screen for readers or if it fails to load)?
    `alt`

- What is the difference between CSS Grid and Flexbox?
    Grid is a newer method based on a grid system and handles larger scale layouts. Flexbox works till fill allotted space and handles smaller scale layouts well.

- For a responsive website, should it be designed mobile-first or desktop-first?
    mobile-first

- Describe the components of the CSS Box Model.
    The different parts of the CSS box model are content, padding, border and margin.

- In CSS, what is a breakpoint?

- What is a div and how are they used?
    `<div>` tags represent divisions/segments of the page are easily styled with CSS.

- What are the two main groups of CSS properties that control typography style?
    Font sizing and font stacks.

- What is the "query string" in a URL and what does it do?
    A query string is part of a URL that assigns values to specified parameters.

- What is the difference between "pixels" and "em"?
    Pixels are and absolute unit, where as em is a relative unit.

- How does inheritance work for CSS styles, i.e. how does an element get its "default" styles?
    When no value is specified the element inherits the value from the parent element.

- What are two CSS attributes you can change to push an element around on the page?
    Flex and Grid

- What are the three different ways to include a CSS stylesheet in your project or use CSS to style a particular element?
    The three ways to include CSS in your webpage is by linking a CSS file, creating a `<style></style>` tag the top and writing all of the CSS within that tag, or to use inline CSS.

- What is the "default stylesheet" or "user agent stylesheet"?
    A default stylesheet is used as a fall back for older browsers.

- What is the purpose of a CSS reset file?
    A CSS reset file is used to override a browsers default CSS settings.

----

# Developer tools

- How do you open developer tools in your browser?
    Right click then select inspect. 

- How do you select a specific element on your page with your browser's developer tools?
    Hover over the element and the code will be highlighted.

- How do you change CSS in real time on specific elements of a web page with your browser's developer tools?
    Double click the code to edit then make the desired change.

- What does a strikethrough in a CSS element mean in your browser's developer tools?
    Strikethroughs indicate that there is a more specific rule that is overriding the stuckthrough code.

- How do you check every inherited style for an element in your browser's developer tools?
    The computed tab in the CSS window of Div Tools lists all applied rules to the current element.

- How do you edit HTML in real time in your browser's developer tools?
    Double click the code to edit then make the desired change.

- How do you toggle responsive design mode in your browser's developer tools?
    Select the mobile device icon to enter responsive design mode.

- Are changes made in your browser's developer tools permanent?
    No

- How do you open the console in your browser's developer tools?
    Select the console tab to open the console.

- What is the best resource for learning about your browser's developer tools?
    The official documentation.

----

# Fundamentals Part 1

- Name the three ways to declare a variable?
    `var`, `let`, and `const`

- Which of the three variable declarations whould you avoid and why?
    `var` should be avoided. It is an outdated method that breaks due to unexpected behavior due to not having block-scoping behavior which `let` does have.

- What rules should you follow when naming variables?
    Variables should have meaningful unabiguous names. Camelcasing can also help to make the variable more meaningful.
    
- What should you look out for when using the `+` operator with numbers and strings?
    The `+` operator is used for addition and concatination but a number can not be added to a string.
    
- How does the `%` operator work?
    The `%` operator returns the remainder of division.
    
- Explain the difference between `==` and `===`.
    `==` is equal to where as `===` is strict equal too. The strict equal to tests value and datatype to the is equal only testing the value.
    
- When would you receive a `NaN` result?
    The `NaN` result is received when trying to do math operations on numbers and non-numeric strings.
    
- How do you increment and decrement a number?
    `--` to decrement and `++` to increment
    
- Explain the difference between prefixing and post-fixing increment/decrement operators.
    The difference is based on return values. Prefix returns new value where postfix returns old value.
    
- What is operator precedence and how is it handled in JS?
    Operator precedence is handled the same in JS as it is in math.
    
- How do you access developer tools and the console?
    From the right click menu select inspect and then the console tab from the newly opened dev tools.
    
- How do you log information to the console?
    `console.log()`

----

# Fundamentals Part 2

- What are the eight data types in JavaScript?
- Which data type is NOT primitive?
- What is the relationship between null and undefined?
- What is the difference between single, double, and backtick quotes for strings?
- What is the term for embedding variables/expressions in a string?
- How do you embed variables/expressions in a string?
- What are methods?
- What is the difference between slice/substring/substr?
- What are the three logical operators and what do they stand for?
- What are the comparison operators?
- What are truthy and falsy values?
- What are the falsy values in JavaScript?
- What are conditionals?
- What is the syntax for an if/else conditional?
- What is the syntax for a switch statement?
- What is the syntax for a ternary operator?
- What is nesting?

----
