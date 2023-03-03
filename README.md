### GitHub
<p> What I learned with the GitHub assignment is that it can be really annoying to deal with merge conflicts. The best way to get around this is clear communication with team members and consistency in the way that you are editing something in your repository.</p> 

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
