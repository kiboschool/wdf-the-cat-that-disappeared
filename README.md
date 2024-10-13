# The Cat that Disappears

Make the image of the cat disappear from the page after some time, using JavaScript.

## Instructions

1. First, run the code, open the page, and Inspect the cat image.
2. Open the console, and in the console, select the cat image using `document.querySelector`. _Hint: how would you select the img in CSS?_
3. When you have the code to select the cat image in the console, make the image disappear by adding the `hidden` class to the element.
4. Now that you've hidden the cat from the console, copy that JavaScript code and add it the top of `script.js`. When you run the site again, the cat disappears instantly -- you never see it show up!
5. Next, move the code down into the `setTimeout` block below, where the comment is. Run the site again, and see that the cat disappears after 3 seconds.

**Notes**
* You can see the CSS for the `hidden` class in `style.css`. It sets `display: none`.
* `setTimeout` waits for some amount of time, then runs the code inside the `{}`.

Once you have the cat disappearing after 3 seconds, you have finished the exercise. Feel free to explore more of how the code works. Change things, run the code, and see what happens.

## Hints

* Remember to use quotes around the selector and class names, like `document.querySelector('div')` and `add('retro')`.
* You can use `classList.add('hidden')` to add the 'hidden' class.

Tip: Pressing the up arrow on the keyboard brings back the last command you entered in the console. Press it again to scroll backwards through the commands you've entered.