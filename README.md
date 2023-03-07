### The Console
<p> The following are some helpful commands that can be used in the terminal:</p>
<li><code>rmdir</code> - Remove a directory</li>
<li><code>curl</code> - Command line client URL browser</li>
<li><code>grep</code> - Regular expression search</li>
<li><code>find</code> - Find files</li>
<li><code>top</code> - View running processes with CPU and memory usage</li>
<li><code>df</code> - View disk statistics</li>
<li><code>less</code> - Interactively output the contents of a file</li>
<li><code>ps</code> - View the currently running processes</li>
<li><code>kill</code> - Kill a currently running process</li>
<li><code>history</code> - Show the history of commands</li>
<li><code>ping</code> - Check if a website is up</li>
<li><code>traceroute</code> - Trace the connections to a website</li>
<li><code>dig</code> - Show the DNS information for a domain</li>
<li><code>man</code> - Look up a command in the manual</li>
<p></p>
<p>Some other helpful special characters and commands are also as follows:</p>
<li><code>|</code> - Take the output from the command on the left and pipe, or pass, it to the command on the right</li>
<li><code>></code> - Redirect output into a file, overwrites if the file already exists</li>
<li><code>>></code> - Redirect output into a file, appends to the file if it already exits</li>
<li><code>CTRL-R</code> - use type ahead to find previous commands</li>

### VIM
<p>Here are a few commands that are helpful in VIM, which you can open by typing <code>vi filename.txt</code> into the console</p>
<li><code>:h</code> - Help</li>
<li><code>i</code> - Enter insert mode</li>
<li><code>u</code> - Undo</li>
<li><code>CTRL-R</code> - Redo</li>
<li><code>gg</code> - Go to the beginning of the file</li>
<li><code>G</code> - Go to end of file</li>
<li><code>/</code> - Search for text that you type after /</li>
<li><code>n</code> - Next search match</li>
<li><code>N</code> - Previous search match</li>
<li><code>v</code> - Visually select text</li>
<li><code>y</code> - Yank or copy selected text to clipboard</li>
<li><code>p</code> - Paste clipboard</li>
<li><code>CTRL-W</code> - Split window vertically</li>
<li><code>CTRL-ww</code> - Toggle windows</li>
<li><code>CTRL-wq</code> - Close current window</li>
<li><code>:e</code> - Open a file. Type ahead available. If you open a directory you can navigate it in the window.</li>
<li><code>:w</code> - Write/save file</li>
<li><code>:q</code> - Quite, exit file</li>
<li><code>:q!</code> - Exit file without saving</li>

### Git
<li><code>git init</code> - This initializes a directory as a Git repository</li>
<li><code>git status</code> - Tells you what is happening in Git</li>
<li><code>git add .</code> - Adds git tracking for the versions of all files in the cwd</li>
<li><code>git commit -am "comment here"</code> - Add a file to the Git, and commit a version with a message</li>
<li><code>git log</code> - Shows commits with associated comments as well</li>
<li><code>git checkout</code> - Allows you to switch back to a previous version (or back to the master branch) with the use of a SHA (unique identifier for each commit)</li>
<li><code>git diff HEAD HEAD~(number of commits back you wish to reference)</code> - Lets you look at the differences between two different versions of a file.</li>
<li><code>git branch (name of the branch)</code> - Creates a new branch</li>
<li><code>git checkout (name of the branch)</code> - Allows you to begin working on the branch specified</li>
<li><code>git merch (name of the branch)</code> - Mergest the branch you are currently on with the branch named in the command</li>

### GitHub
<p> What I learned with the GitHub assignment is that it can be really annoying to deal with merge conflicts. The best way to get around this is clear communication with team members and consistency in the way that you are editing something in your repository.</p> 
<p> The following are also some useful commands to know with GitHub:</p>
<li><code>git clone (url)</code> - Will clone a copy of the GitHub repo to your device</li>
<li><code>git push</code></li>
<li><code>git pull</code></li>
<li><code>git fetch</code> - Get the latest information about the changes on GitHub without changing the local repo</li>
<li><code>git status</code> - See the difference between the clones</li>
<p></p>
<p>As a side note, forking is similar to cloning a repo, but it copies to your GitHub instead of to your local machine</p>

### AWS
<p>With a little help from someone with a lot more money than I have, it is actually fairly simple to launch a nice webserver.</p>
<p>This is my server's IP address: <b>3.132.231.194</b>. And this is the command to ssh in: <b>ssh -i [key pair file] ubuntu@3.132.231.194</b>. </p>

### DNS
<p>DNS stands for Domain Name System. The A record (Address) is a mapping from a domain name to an IP address. The CNAME record (canonical name) maps one domain name to another domain name. It acts as an alias.</p>
<p>My domain name is <b>https://chickenlittle.click</b>. I do not wish to justify myself in this decision. I learned that renting a domain name can be fairly simply but the set up is complicated if you don't know what you are doing. </p>

### HTTPS
<p>HTTPS stands for Hypertext Transport Protocol.</p>
<p>With this assignment I learned how to request a certificate so that your website can be secure. Secure websites are super important in order to protect information of visitors and of the owners as well. Now in order to go to a subdomain of my website I have to actually have created one. </p>

### HTML
<p>I learned about the basic structure of HTML documents and how to add tables and images. It was fairly simple, although I do want to remember that as class is a classification and not the same as a class in object oriented programming at all. </p> 
<p>The terminal command to deploy the main page of my website is: <b>./deployWebsite.sh -k {path to key} -h {domainname}</b></p>
<p>The following are some common elements in HTML.</p>
<li><code>meta</code> - Metadata for the page such as character set or viewport settings</li>
<li><code>include</code> - External content reference</li>
<li><code>nav</code> - Navigational inputs</li>
<li><code>section</code> - A section of the main content</li>
<li><code>aside</code> - Aside content from the main content</li>
<li><code>h1-9</code> - Text heading, h1 is the biggest/highest and h9 is the smallest/lowest</li>
<li><code>b</code> - Bring attention</li>
<li><code>table</code></li>
<li><code>tr</code> - Table row</li>
<li><code>th</code> - Table header</li>
<li><code>td</code> - Table data</li>
<li><code>ol</code> - Ordered list</li>
<li><code>ul</code> - Unordered list</li>
<li><code>li</code> - List item</li>
<li><code>a href=""</code> - Anchor the text to a hyperlink</li>
<li><code>img src=""</code> - Graphical image reference</li>
<li><code>dialog</code> - Interactive component such as a confirmation</li>
<li><code>form</code> - A collection of user input</li>
<li><code>input</code> - User input field</li>
<li><code>audio</code> - Audio content</li>
<li><code>video</code> - Video content</li>
<li><code>svg</code> - Scalable vector graphic content</li>
<li><code>iframe</code> - Inline frame of another HTML page</li>
<li><code>&lt;!-- --&gt;</code> - Comment</li>
<p></p>
<p>The following are special characters in HTML that require escape syntax to display, they aren't supposed to have spaces in them but I don't know how to escape the escapes HA:</p>
<li><code>& amp;</code> - &amp;</li>
<li><code>& lt;</code> - &lt;</li>
<li><code>& gt;</code> - &gt;</li>
<li><code>& quot;</code> - &quot;</li>
<li><code>& apos;</code> - &apos;</li>
<li><code>& #128512;</code> - &#128512;</li>

#### Simon HTML
<p>I learned a lot about how the structure of HTML actually works. I think that I am finally starting to get the basic ideas down. By studying the deployment script for this project I also learned a few things about how writing scripts actually works, although this did raise some questions for me as well. I learned about the importance of pushing to GitHub often as well. </p>
<p> The terminal command to deploy is: <b>./deployFiles.sh -k {path to key} -h {domainname} -s {which service}</b></p>

#### StartUp HTML
<p> I learned the importance of flexibility in changing previous plans. I also learned the importance of creating visuals in helping to streamline and improve your coding process. The great thing about HTML is how easy it is to change things around and create the skeleton of what you want your work to be. This skeleton is also helpful for visualizing and implementing better code and design. </p>

### CSS
<p> I learned that sometimes the best teacher is trial and error. There are a lot of ways you can manipulate the structure of HTML with CSS to make visually interesting animations. However, this takes practice and ultimately is a skill to develop over time. </p>
<p> The link to the most helpful reference guide I used in this assignment was: <b> https://developer.mozilla.org/en-US/docs/Web/CSS/animation </b> </p>
<p>This is how to link a CSS(cascading style sheets) sheet into your HTML: <code>&lt; link rel="stylesheet" href="styles.css"&gt;</code></p>
<p>Pals Before Marriage</p>
<p>The following is a table of how combinators in CSS work:</p>
<table>
  <tr><th>Combinator</th><th>Meaning</th><th>Example</th><th>Description</th></tr>
  <tr><td>Descendant</td><td>A list of descendants</td><td><code>body section</code></td><td>Any section that is a descendant of a body</td></tr>
  <tr><td>Child</td><td>A list of direct children</td><td><code>section > p</code></td><td>Any p that is a direct child of a section.</td></tr>
  <tr><td>General sibling</td><td>A list of siblings</td><td><code>p ~ div</code></td><td>Any p that has a div sibling</td></tr>
  <tr><td>Adjacent sibling</td><td>A list of adjacent siblings</td><td><code>p + div</code></td><td>Any p that has an adjacent div sibling</td></tr>
</table>
<p>Classes are selected by having a <code>.</code> directly in front and IDs are selected by having a <code>#</code> directly in front. You can select elements based on their attributes by saying <code>a[href]</code>. Sudo selectors can be added as well, such as <code>section:hover</code>, which adds CSS when the user hovers over a certain element.</p>
<p>The following are some helpful properties in CSS:</p>
<li><code>background-color:color</code> - Fill the background color</li>
<li><code>border:color width style</code> - Sets the border using shorthand where any or all of the values may be provided</li>
<li><code>border-radius:unit</code> - EX)50%, sets the size of the border radius </li>
<li><code>box-shadow:x-offset y-offset blu-radius color</code> - Creates a shadow</li>
<li><code>columns:number</code> - Number of textual columns</li>
<li><code>column-rule:color width style</code> - Sets the border used between columns using border shorthand</li>
<li><code>color:color</code> - Sets the text color</li>
<li><code>cursor:type</code> - Sets the cursor to display when hovering over the element</li>
<li><code>display:type</code> - Defines how to display the element and its children</li>
<li><code>filter:filter-function</code> - EX)grayscale(30%), applies a visual filter</li>
<li><code>float:direction</code> - Places the element to the right or left in the flow</li>
<li><code>flex</code> - Flex layout, used for responsive design</li>
<li><code>font: family size style</code> - Defines the text font using shorthand</li>
<li><code>grid</code> - Grid layout, used for responsive design</li>
<li><code>height:unit</code> - Sets the height of the box</li>
<li><code>margin:unit</code> - Sets the margin spacing</li>
<li><code>max-[width/height]:unit</code> - EX)20%, Restricts the width or height to no more than the unit</li>
<li><code>min-[width/height]:unit</code> - EX)10vh, restricts the width or height to no less than the unit</li>
<li><code>opacity:number(0-1)</code> - Sets how opaque the element is</li>
<li><code>overflow:[visible/hidden/scroll/auto]</code> - Defines what happens when the content does not fix in its box</li>
<li><code>position:[static/relative/absolute/sticky]</code> - Defines how the element is positioned in the document</li>
<li><code>padding:unit</code> - Sets the padding spacing</li>
<li><code>left:unit</code> - The horizontal value of a positioned element</li>
<li><code>text-align[start/end/center/justify]</code> - Defines how the text is aligned in the element</li>
<li><code>top:unit</code> - The vertical value of a positioned element</li>
<li><code>transform:transform-function</code> - EX)rotate(0.5turn), applies a transformation to the element</li>
<li><code>width:unit</code> - Sets the width of the box</li>
<li><code>z-index:number</code> - Controls the positioning of the element on the z-axis</li>
<p></p>
<p>You can add fonts to CSS by either doing the following code: <code>@import url(" ");</code> or 
  
  ```css
  
  @font-face { 
    font-family: "Name";
    src: url("");
  }
  
  ```
</p>

#### Animation
<p> the following is the basic syntax of creating animations in CSS:
  
  ```css
  
  p {
    animation-name:nameOfAnimation;
    animation-duration: 10s;
    animation-direction: alternate;
  }
  
  @keyframs nameOfAnimation {
    from {
      some css delarations
    }
    95% {
      some more css declarations
    }
    to {
      final state of animation
    }
  }
  
  ```
  
</p>
  

#### CSS: Responsive Display
<p> I learned that there are several rather difficult elements to making CSS responsive to display size. Of course a very important part is the metadata head that can be included in the HTML, <coode>&lt;meta name="viewport" content="width=device-width,initial-scale=1"&gt;</cpde> Additionally, the display in CSS can be changed to grid or flex or float to accomplish all sort of different things. </p>
<p> Possible values for <code>display:</code> are <code>none</code>, <code>block</code>, <code>inline</code>,<code>flex</code>, and <code>grid</code>. Block displays the element with a width that fills its parent element. Inline will display the element with a width that is only as big as it's content.</p>
<p> Media queries can look something like the following:
  
  ```css
  
  @media (orientation: portrait) {
    body {
      transform: rotate(270deg);
    }
  }
  
  ```
  
  or
  
  ```css
  
  @media (max-height: 600px) { } 
  
  ```
  
</p>

#### Simon CSS
<p> I learned that Bootstrap can make your CSS life so easy. Also adding <code>!important</code> to a line of CSS will make it override the parent.</p>

### JS
<p> I learned how to create functions, especially arrow functions which look something like <code>(a) => a + 1</code>. I also learned how to create classes and object easily. It looks like the following: <code>class Hats {}</code> and inheritance looks like <code>class Ballcap extends Hats{}</code>.</p> 
<p><code>for (const name in obk)</code> will iterate over an object's propery names while <code>for (const val of arr)</code> will iterate over an iterable's (such as a Map, Array, Set) property values</p>
<p>The following are some important array features:
  <table>
    <tr><th>Function</th><th>Meaning</th><th>Example</th></tr>
    <tr><td>push</td><td>Add an item to the end of the array</td><td><code>a.push(4)</code></td></tr>
    <tr><td>pop</td><td>Remove an item from the end of the array</td><td><code>x = a.pop</code></td></tr>
    <tr><td>slice</td><td>Return a sub-array</td><td><code>a.slice(1,-1)</code></td></tr>
    <tr><td>sort</td><td>Run a function sort an array in place</td><td><code>a.sort((a,b) => b-a)</code></td></tr>
    <tr><td>values</td><td>Creates an iterator for use with a for of loop</td><td><code>for (i of a.values()) {...}</code></td></tr>
    <tr><td>find</td><td>Find the first item satisfied by a test function</td><td><code>a.find(i => i < 2)</code></td></tr>
    <tr><td>forEach</td><td>Run a function on each array item</td><td><code>a.forEach(console.log)</code></td></tr>
    <tr><td>reduce</td><td>Run a function to reduce each array item to a single item</td><td><code>a.reduce((a, c) => a + c)</code></td></tr>
    <tr><td>map</td><td>Run a function to map an array to a new array</td><td><code>a.map(i => i+i)</code></td></tr>
    <tr><td>filter</td><td>Run a function to remove items</td><td><code>a.filter(i => i%2)</code></td></tr>
    <tr><td>every</td><td>Run a function to test if all items match</td><td><code>a.every(i => i < 3)</code></td></tr>
    <tr><td>some</td><td>Run a function to test if any items match</td><td><code>a.some(i => 1 < 1)</code></td><tr>
</table>
    </p>

#### RegEx
<p> in order to creat a RegEx object you can use the following syntax <code> const regObj = new RegExp("expression", "flags") </code>. Some of the more useful flags are i (which makes the expression not case sensitive) and g (which performs a global search). Additionally in order to use a regular expression character, such as \b (which represents a break between words etc.) you need to represent it in the string as <code> \\b </code>. Finally, there are functions such as <code>text.match(regObj)</code>, <code>text.replace(regObj ,"replacement String")</code>, <code>text.replaceAll(regObj, "replacement Stirng")</code>, and <code>text.test(regObj)</code> which will return a boolean if the regular expression appears in the text string. </p>
<p>A literal RegEx looks something like this: <code>/ab*/i</code>.</p>


#### Rest & Spread 
<p> Rest allows a function to have an uncertain number of perameters, and you add the <code>...</code> in the function definition. Spread is found in function calls and allows you to split up the parts of an iterable object (like a string or array) into multiple parameters of the function.

#### DOM
<p> It is shockingly uncomplicated to change the DOM around but the methods are so strangely named that it is a little difficult to remember them. Some good ones include: 
  <li><code>.getElementById("#id")</code></li>
  <li><code>.querySelectorAll("element")</code></li>
  <li><code>.textContent = "some text";</code></li>
  <li><code>.createElement("element")</code></li>
</p>

#### Simon JS
<p> It is important to put the <code><script src="scriptName.js"></script></code> at the bottom of the HTML document. You can also use JS to change the CSS of HTML elements through <code>elName.style.backgroundColor</code> etc. </p>
