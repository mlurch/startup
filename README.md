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
<p>With a little help from someone with a lot more money than I have, it is actually fairly simple to launch a nice webserver. </p>
<p>This is my server's IP address: <b>3.132.231.194</b>. And this is the command to ssh in: <b>ssh -i [key pair file] ubuntu@3.132.231.194</b>. </p>

### DNS
<p>My domain name is <b>https://chickenlittle.click</b>. I do not wish to justify myself in this decision. I learned that renting a domain name can be fairly simply but the set up is complicated if you don't know what you are doing. </p>

### HTTPS
<p>With this assignment I learned how to request a certificate so that your website can be secure. Secure websites are super important in order to protect information of visitors and of the owners as well. Now in order to go to a subdomain of my website I have to actually have created one. </p>

### HTML Intro
<p>I learned about the basic structure of HTML documents and how to add tables and images. It was fairly simple, although I do want to remember that as class is a classification and not the same as a class in object oriented programming at all. </p> 
<p>The terminal command to deploy the main page of my website is: <b>./deployWebsite.sh -k {path to key} -h {domainname}</b></p>

### Simon HTML
<p>I learned a lot about how the structure of HTML actually works. I think that I am finally starting to get the basic ideas down. By studying the deployment script for this project I also learned a few things about how writing scripts actually works, although this did raise some questions for me as well. I learned about the importance of pushing to GitHub often as well. </p>
<p> The terminal command to deploy is: <b>./deployFiles.sh -k {path to key} -h {domainname} -s {which service}</b></p>

### CSS
<p> I learned that sometimes the best teacher is trial and error. There are a lot of ways you can manipulate the structure of HTML with CSS to make visually interesting animations. However, this takes practice and ultimately is a skill to develop over time. </p>
<p> The link to the most helpful reference guide I used in this assignment was: <b> https://developer.mozilla.org/en-US/docs/Web/CSS/animation </b> </p>


### CSS: Responsive Display
<p> I learned that there are several rather difficult elements to making CSS responsive to display size. Of course a very important part is the metadata head that can be included in the HTML, <b> meta name="viewport" content="width=device-width,initial-scale=1" </b> Additionally, the display in CSS can be changed to grid or flex or float to accomplish all sort of different things. </p>

### StartUp HTML
<p> I learned the importance of flexibility in changing previous plans. I also learned the importance of creating visuals in helping to streamline and improve your coding process. The great thing about HTML is how easy it is to change things around and create the skeleton of what you want your work to be. This skeleton is also helpful for visualizing and implementing better code and design. </p>

### Simon CSS
<p> I learned that Bootstrap can make your CSS life so easy. Also adding <code>!important</code> to a line of CSS will make it override the parent.</p>

### JS
<p> I learned how to create functions, especially arrow functions which look something like <code>(a) => a + 1</code>. I also learned how to create classes and object easily. It looks like the following: <code>class Hats {}</code> and inheritance looks like <code>class Ballcap extends Hats{}</code>.</p> 

#### RegEx
<p> in order to creat a RegEx object you can use the following syntax <code> const regObj = new RegExp("expression", "flags") </code>. Some of the more useful flags are i (which makes the expression not case sensitive) and g (which performs a global search). Additionally in order to use a regular expression character, such as \b (which represents a break between words etc.) you need to represent it in the string as <code> \\b </code>. Finally, there are functions such as <code>text.match(regObj)</code>, <code>text.replace(regObj ,"replacement String")</code>, <code>text.replaceAll(regObj, "replacement Stirng")</code>, and <code>text.test(regObj)</code> which will return a boolean if the regular expression appears in the text string. </p>


#### Rest & Spread 
<p> Rest allows a function to have an uncertain number of perameters, and you add the <code>...</code> in the function definition. Spread is found in function calls and allows you to split up the parts of an iterable object (like a string or array) into multiple parameters of the function.

#### DOM
<p> It is shockingly uncomplicated to change the DOM around but the methods are so strangely named that it is a little difficult to remember them. Some good ones include: 
  <li><code>.getElementById("#id")</code></li>
  <li><code>.querySelectorAll("element")</code></li>
  <li><code>.textContent = "some text";</code></li>
  <li><code>.createElement("element")</code></li>
</p>

### Simon JS
<p> It is important to put the <code><script src="scriptName.js"></script></code> at the bottom of the HTML document. You can also use JS to change the CSS of HTML elements through <code>elName.style.backgroundColor</code> etc. </p>
