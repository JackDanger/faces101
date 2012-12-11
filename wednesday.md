# HTML+Javascript 101: Tuesday

### 10:00 (first instructor)

Open by asking folks how the class is going. Anything need changing?

Goals for today: Students may not understand the difference between a Function or a String but they
will be able to edit a jQuery selector to point to the right DOM id.

### 10:10

Restore yesterday's editing environment. Make sure they can edit a file
and preview it in Chrome.

Direct students to download the html file here:
<pre>
<a
href="http://jackdanger.github.com/faces101/2_jquery_demo.html"
>http://jackdanger.github.com/faces101/2_jquery_demo.html</a>
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

### 11:30

Have the students reopen <a href="http://jackdanger.github.com/faces101/2_jquery_demo.html">http://jackdanger.github.com/faces101/2\_jquery\_demo.html</a> and add
their own CSS effects, using styles from the CSS demo if they get
stuck.

### 12:00 (exercises begin, folks can leave at will)

### Exercise 1

Swap the green square logo image on the jQuery demo page with another
image from the internet (no need to download, just paste in the URL!)

### Exercise 2

Swap the kitty image with a different kitty image from the internet.

### Exercise 3

Make it so when you click the 1st section it runs 'slideUp' instead of
'fadeOout'

### Exercise 4

Make it so when you click the 1st section it does all of the effects all
at once, as if you'd clicked every section simultaneously (hint: copy
and paste the javascript commands that are inside the function(){} blocks)

### Exercise 5

Make it so when you click anywhere on the page the entire page slides
up. Hint: you'll want to use $("body").slideToggle()
