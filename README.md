# Madlibs

We've learned how to prompt the visitor for information. Today, we talked about how to write that information to the screen. `document.write` is not the best way to present information, but it will work for our purposes today.

Your mission is to create a Madlibs app. The premise is simple. It should ask the visitor some questions (e.g. "Give me a verb.") and then put together a story based on those questions.

The trick is to store all of the responses into variables that you can use later on when you're ready to tell your story.

Here is an example:

	var name = prompt("What is your name?");
	
Whatever the visitor enters will be stored in the variable called `name`. When you are ready to use that variable, you can write it onto the HTML document.

	document.write("Hello, " + name + "!");
	
The catch is that you have to put your text in quotes and add in the variable. **This can be a little tricky at first, but you will get the hang of it**, I promise. That said, I can almost guarantee that you will make a mistake at least once. Luckily, it's fairly easy to fix your mistakes!

You'll notice that when you download this repository, you have three files.

* `README.md` (this file)
* `index.html` (an HTML document that the user visits to interact with your app)
* `madlibs.js` (a JavaScript file with your code)

The only file you need to edit is `madlibs.js`. That's the only file that you are going to submit to me. Anything you put in your `index.html` file is just for your own amusement. I put some starter code in your `madlibs.js` so that you can get a feel for how it works.