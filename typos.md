I've created this document in an effort to give you all more pracical expereince with git. Git is an important and powerful tool that you need to know how to use beyond simply pushing commits to your own repos.


Follow the instructions [here](https://github.com/firstcontributions/first-contributions) to make your first git pull request, if you haven't already done so. You'll basically follow the same process for this exercise, but we'll do more of a back and forth.

# Instructions
Now, go into my git repo and find the repository called *gittraining*. Inside of this repo is a document titled **typos.md**. The document contains a section for each of you with a snippet of javascript code that I want you to modify according to the instructions in your section. 

You can take the code and work with it in the browser or node, it doesn't matter which. Once you have a solution, working or not, replace the malfunctioning code snippet in your section with your code and submit a pull request.

It really doesn't matter if you modify your snippet correctly. Try to do it correctly, but in the end the point is that you see how code collaboration works. It is an iterative process, so this is a great time to make mistakes and just submit something to get a feel for how code collaboration works in git.


# Tasks
## David
Edit the code below to output *1 2* to the console instead of *2 2*.

```javascript
function editMe() {
    var x = 1;
    if (true) {
        var x = 2;
        console.log(x);
    }
    console.log(x);
}
```

## Gerald
Create an IIFE that will print 3 parameters passed to it to the console.
```javascript

```

## Mitch
Fix the code below so that *1 2 3* is logged to the console instead of *1 undefined undefined*

```javascript
  function hoistMe() {
    var foo = 1;
    console.log(`${foo} ${bar} ${baz}`);
    var bar = 2;
    var baz = 3;
  }
```

## Sarah
Rewrite the following using a switch statement:

```javascript
if(browser == 'Edge') {
    alert("Desperate attempt at staying relevant much?");
} else if (browser == 'Chrome'
    || browser == 'Firefox'
    || browser == 'Safari'
    || browser == 'Opera') {
    alert( 'That\'s better' );
} else {
    alert( 'We hope that this page looks ok!' );
}
```