# HTML+Javascript 101: Tuesday

### 10:00 (first instructor)

Open by asking folks how the class is going. Anything need changing?

Goals for today: edit other people's code, feel dangerous. Students
won't understand the difference between a Function or a String but they
will be able to edit a jQuery selector to point to the right DOM id.

### 10:10

Restore yesterday's editing environment. Make sure they can edit a file
and preview it in Chrome.

Direct students to download the html file here:
<pre>
<a
href="http://jackdanger.github.com/faces101/tuesday/1_jquery_demo.html"
>http://jackdanger.github.com/faces101/tuesday/1_jquery_demo.html</a>
</pre>

Open it in Chrome and play with the effects. Ask students to see if they
can figure out which parts of the page cause changes when clicked and
which don't.

Have them open the Web Inspector and take a closer look at the DOM near
where the effects seem to be happening. Demonstrate the link between the
DOM id and jQuery selector.


10:30

Have the students edit the file to change the DOM ids of the elements
and watch that the effects no longer happen. Then get them to update the
jQuery selectors to use the new DOM ids.
Goal: get the effects working the same as before but with brand new dom
ids.

Likely problems: students will pick the same id for multiple elements.

### 11:00 (switch instructors)

Download http://squareup.com to a local file (save with all assets)

Open it in both the text editor and Chrome

Instruct students to copy the &lt;script&gt;&lt;script&gt; tag from the
previous example and paste it at the extreme bottom of the saved Square
home page HTML.

Have students change one of the jQuery selectors to bind to
"#user-password" (the PW element of signup form).
Have students change the target to ".register-fg"

Goal: Clicking the password field should trigger slideToggle (or some
other effect) on the floating hand image.

### 11:40

### 12:00 (exercises begin, folks can leave at will)

### Exercise 1
