# HTML+Javascript 101: Tuesday

### 10:00 (first instructor)

Open by asking folks how the class is going. Anything need changing?
Consider having students work in pairs.

Goals for today: Understand basic CSS concepts, edit existing code, feel dangerous.
Stretch goals: CSS selectors

### 10:10

Restore yesterday's editing environment. Make sure they can edit a file
and preview it in Chrome.

Direct students to open the html file here:
<pre>
<a
href="http://jackdanger.github.com/faces101/1_css_demo.html"
>http://jackdanger.github.com/faces101/1_css_demo.html</a>
</pre>

Open it in Chrome and talk through the various effects.
Have them open the Web Inspector and take a closer look at the the
connection between DOM ids and styles.

### 10:30

Have the students download and edit the file to play with the various
CSS styles. Have them make a div as ugly as possible by applying all
6 styles to one of the &lt;div&gt; tags.

### 10:45

Put the students in pairs and have them inline the styles. The result
should be that they can delete the STYLE tag and it still looks the same.

### 11:00 (switch instructors)

Direct students to open
<pre>
<a
href="https://squareup.com/news"
>https://squareup.com/news</a>
</pre>
And look at it with Web Inspector. Have them do all of the following:

* uncheck the margin-top on the 'Square News' h1
* uncheck the color on 'In The News' h3
* selec the '.hero-section p', double-click the style list and add a
  color.

Have the students download the page and save it for editing.

Talk them, step by step, through the steps necessary to turn the page
they just downloaded into this one:
<pre>
<a
href="http://jackdanger.github.com/faces101/1_css_demo.html"
>http://jackdanger.github.com/faces101/1_css_demo.html</a>
</pre>

Steps they'll need to perform:

* create a &lt;style&gt;&lt;/style&gt; tag
* add a rule for something they want to override (tell them to just copy
  what they see as the rule in Web Inspector)
* write a new style between the curly braces

Note: tell them it's okay to use !important freely.

Likely problems: quieter students might be lost. Take ten minutes for
the students to take turns explaining what you've said so far today.

### 11:35

Direct students back to this page:
<pre>
<a
href="http://jackdanger.github.com/faces101/1_css_demo.html"
>http://jackdanger.github.com/faces101/1_css_demo.html</a>
</pre>

Have them delete and re-download it if they need to.

Talk about the process of using Web Inspector to find selectors
and play with changes. Have them use Web Inspector to invent new changes
to this page.

They should copy the changes they come up with to the page's
&lt;style&gt; tag so they changes persist.

Ideas:

* Set small widths on all P tags
* Set a different color for the H1
* Set a different background-color for the .hero-unit


### 12:00 (exercises begin, folks can leave at will)

### Exercise 1

Change each section of the CSS demo page to have a different font-size.

### Exercise 2

Change each section of the CSS demo page to have a different color.

### Exercise 3

Change each section of the CSS demo page to have a different
background-color.

### Exercise 4

Download https://squareup.com/legal/ua and make it look as different as
possible.
