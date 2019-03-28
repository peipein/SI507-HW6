# JavaScript assignment

## Some useful resources
* Some [JavaScript tutorials](https://www.htmldog.com/guides/javascript/)
* The complicated [resources in the You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) series, including [your reading last week](https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch2.md)
* [A resource for CSS/style/colors](https://htmlcolorcodes.com/)  
* [An excerpt from a specific workshop site](https://witny-summer-guild-2018.github.io/day_4_exercise_2.html) (for a different audience than yourselves) which addresses some common questions about jQuery
* [The simple JSFiddle example from class](https://jsfiddle.net/2of65j8q/)
* A [W3Schools resource on JavaScript output](https://www.w3schools.com/js/js_output.asp)
* Google, Piazza, your classmates, office hours, lab time!

## Included files
* This `README.md`, which you should edit with answers to the questions
* `jsPracticeLab.html`, which you'll need to edit and try out
* `jquerylib_submit_example.html`, which you'll need to edit and try out

## Your goals for this lab

### Broadly
The aim for this lab is to practice adapting to and understanding code in a new-to-you (or not) language and its own libraries/packages -- JavaScript, in this case.

The programming skills you have built up till now are useful for *Python programming*, but, more than that, they extend to fundamentals of many kinds of programming.

This experience is *not in any way* about becoming an expert JavaScript programmer. Instead, it is about using what you *do* have experience with -- and your skills in *learning new things* that relate to programming -- in order to make educated judgments about some brand new-to-you code, even if you haven't learned in detail about it yet. That's part of what being in technology -- or even technology-adjacent -- will often mean.

### Specifically

Below are a bunch of questions and indications of things to do. For each indication of something to do with code, there is also an accompanying question to answer or brief explanation to give.

**To complete and submit this assignment, you should:**

* Fork (and clone) this repository
* Add our instructional team as a collaborator to your fork (see instructions for adding collaborators on Canvas)
* Edit this `README.md` file with answers to the questions/prompts, briefly, using Markdown formatting so that the questions appear in bulletpoints and the answers appear clearly below each respective question, *not* as bulletpoints.
* Add all names of those who worked on this (as indicated below)
* Make the changes that are indicated below to each of the `.html` files with JavaScript programs provided. (You'll probably do this concurrently with answering questions)
* Commit (as you go) and push your changes to all three files to your GitHub forked repository.
* Submit a link to your repository on Canvas. (This HW doesn't have an autograder -- it will be graded by hand/by humans this time.)

### Important notes
* You are *more than* welcome to work together on this, but **you must <u>each</u> submit a repo to be graded on it**, so if you do work together, you should do the following:
	* Make sure each one of you understands all the work -- YOU are responsible for using and knowing this information
	* Write each person's name & uniqname who worked on the assignment together on your submitted `README.md` file (you'll see a space for this below)

* In answering questions, please make sure the formatting is clear to read and that you have updated the names of everyone who worked with you, with your name first (see below).

* In answering questions, assume all of the questions include a *explain briefly* note -- you do NOT have to, and should not, write extended paragraphs. Be as concise as you can and explain in your own words. Don't worry about "whether it's enough" -- just worry about conveying your understanding so you can read it later, or even give it to someone else, and the answers will help/make sense.

* It is not acceptable to copy and paste answers from the internet and submit them as your own. If you cite things, make sure you provide a citation, including to links. If you get information from a resource and rephrase it so you're basically explaining an idea, that's just fine for an explanatory purpose in this assignment, but you *must* cite any quotes or examples that aren't yours.

* **For grading:** we are grading on...
	* Following the instructions
	* Approximate correctness of the code edits
	* Careful & clear answers to the questions
	* Correct answers to the questions
	* Slightly more than half the 1000 points will come from answering the questions. The rest will come from your edits to the code.

### Names of people you have worked with on this assignment
* List everyone's names and uniqnames who have worked on this assignment with you, **including your own name, but make sure YOUR name is first and bold**
* Peipei Nie (niep)

## Questions & code instructions

### The first questions address the `jsPracticeLab.html` file.

* **This is just an example question.**

This is what an example answer should look like. If you want to include some code, which you probably don't have to do, you can, like this:

```js
Some JavaScript code
```

* **What does a code comment look like in JavaScript? What character/s do you have to put before a comment?**

An example of a code comment looks like this: // Comment should be put here.

Two slash // should be put before a comment.

* **Explain what needs to happen to get a JavaScript program to "run", given the JavaScript you've seen in this assignment.**

Save the source code as a .html file, and open it in a web browser.

* **What functions in JavaScript seem to be similar in function to the `print` function in Python? (There are two.) Why might you use one and not the other? Explain briefly.**

alert() and console.log()

The alert() function pops up an alert box with a specified message and an OK button. It is intended to make sure a user sees the message.

The console.log() function displays a message in the console, for the purpose of testing.

* **What code would have to comment out to get rid of the pop-up box when you load the page? (Related to the last question.) Do that in the code file, and then, add code so that a text box will appear that contains the current date and time! *HINT:* Look through the rest of the code first...**

alert("hello") would have to be commented out.

* **How can you put your own name at the top where it currently says "A name"? Explain very briefly how to do so, and replace `A name` in the web page with your own name.**

Change the string value "A name" in the
```js
document.querySelector('h1').innerHTML = "A name";
```
to my own name.

* **What does the word `document` represent in this code? Explain briefly.**

The 'document' represents the HTML content of the file which stores a group of selectors that allows .querySelector() to match with.

* **What is happening in line 12 (
		`document.querySelector('#items').innerHTML = document.getElementsByTagName('li').length`
)? Explain, briefly (<= 2 sentences).**

The left side of the assignment returns the first element within the document that matches the specified selector '#items'. The right side returns all the elements in the document with the specified tag name "li", counts its length, and assigns the value back to the left side.

* **What color would the background of this page be <u>if there were no JavaScript in this page</u>?**

White.

* **Why are there a couple of gray boxes on the screen with a different colored border? How could you edit this code to make them a different color? Explain briefly. Then edit the code to make those boxes some shade of blue, of your choosing.**

Because the color code for the boxes within the
```js
background-color: #b3b3b3;
```
represents gray, and the color code for the border of the boxes

```js
border: 3px solid #FFFFFF;
```
represents white.

To make those boxes a different color, simply change the color code. Here is the website where you can find color code: https://www.w3schools.com/colors/colors_picker.asp

* **Edit the code so that, if you highlight `McGill University` and copy it, you see the text `O Canada` near the bottom of the page. Briefly explain why you made the edits that you did -- how did you know/figure out what to do?**

The function and property relevant to "copy" are the copyFunction() and the oncopy property of the HTMLElement interface, which would process copying event. To highlight one of the universities, I need to find the section of the document which contains universities. The method that would return the first element within the document that matches the specified selector is querySelector. Then I found that universities is within a section of the document with the id="cheer", so I assigned the words to it, then added oncopy="copyFunction()>" before the McGill University because oncopy would execute the copyFunction() when the user copies the content of the element.

I figured it out because Jackie showed us in lecture that when she highlighted and copied the "University of Michigan", "Go Blue" will appear on the bottom, so I went to find out how she did it in the code, trying to understand and mimic it.

* **In the original code, when you click the button that says `Wow`, you see a text box! Wow. Explain briefly in your own words why the following code causes that to happen:**

```js
function handleClick(){
	alert("hello");
}
```
**and**

```js
<button onclick=handleClick() id="wow-button">Wow</button>
```

The alert("hello") pops up an alert box with the specified message and an OK button, which in this case, is the definition of the function handleClick(). Then, handleClick() is passed to onclick, which means when the button is clicked, something will appear. id is bind to the button name. "Wow" is the text displaying on the button. </button> is an element type.

* **Knowing what you learned from the previous question, add code/markup to the `jsPracticeLab.html` file *so that* there is a button with the text `Spring Equinox 2019` on it somewhere on the page, and when that button is clicked, a text box containing the text `March 20, 2019` appears. (There's no function -- that I am aware of -- to automatically get this info, you've got to type it yourself.)**



### The next few questions address the `jquerylib_submit_example.html` file.

* **Check out the file `jquerylib_submit_example.html`. This is an example of code that uses a package called `jQuery` (and this will need you to have an internet connection to run it properly, although the other file does not). Check out resources above for more on jQuery!**

* **When you enter input that isn't valid, you see an error that is red. Why is the error in red? Why is the response for valid inputs blue?**

It is because of this block of code:

```js
<style type="text/css">
    .error{
        color: red;
    }
    .good {
        color: blue;
    }
```
CSS determines visuals applied to structure, which includes color. .error block means when the input isn't valid, the output should be in red; .good block means when the input is valid, the output should be in blue.

* **What is this line `var regex = /^[a-zA-Z]+$/;` helping with? And if you googled something to figure that out, what did you google, and what, briefly, did you learn? (If you didn't need to google, you can leave that out, but explain briefly what that line is helping the program do, anyway.)**

It creates a regular expression that will check if the line starts with and ends with one or more occurrences of the characters that match a-z or A-Z.

I googled "regex" in jQuery, and it led me to Regular Expression, which contains all the explanations for the special Regex characters on the right side of the expression.

I learned that ^ represents the start-of-line and $ represents the end-of-line. The +, known as occurrence indicator (or repetition operator), indicates one or more occurrences (1+) of the previous sub-expression. In this case, [a-zA-Z]+ matches one or more characters.

* **What's different about the syntax of conditional statements in JavaScript, compared to Python?**

JS uses curly brackets to enclose the statements and specify the scope of the condition, whereas Python uses colon and indentation to do so. JS uses brackets to enclose conditional statements followed by if/else, whereas conditional statements are directly followed by the if/else in Python.

* **What do you think the `10000` refers to in the code `.fadeOut(10000)`?**

The number determined how long the animation will run.

* **What do you think is going on with the following code at the beginning of the program? Note that the most important thing to do for answering this question is to be thoughtful and clear, not to be absolutely correct:**

The special $ character is used to point to parts of the HTML structure and change them. So the first line points to the HTML document and the second line points to the section enclosed by </form>. .ready() specifies a function to execute when the DOM is fully loaded. .submit() binds an event handler to the "submit" JavaScript event, or trigger that event on an element.

version added: 1.0

```js
$(document).ready(function(){
    $("form").submit(function(event){
```



* **Add some code to the `jquerylib_submit_example.html` file so that, if the input is valid and is specifically the text `hello`, rather than the visible output being `Nice!` in blue, the visible output should be `Hello to you too!`, also in blue, just like `Nice!` is.**
	* *HINT:* You'll have to make some changes to the conditional statement, and possibly look up some JavaScript conditional syntax. You'll also need to look carefully at what generates visible output right now.
