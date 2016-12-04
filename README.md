![CF](https://i.imgur.com/7v5ASc8.png)  Lab 05: New Article Creation
=======
[![Build Status](https://travis-ci.org/codefellows-seattle-301d9/05-new-article-creation.svg?branch=master)](https://travis-ci.org/codefellows-seattle-301d9/05-new-article-creation) [![GitHub issues](https://img.shields.io/badge/Issues%3F-Ask%20for%20Help!-orange.svg)](https://github.com/codefellows/seattle-301d4/issues/new)

Now's a good time to recap what we've covered so far. Then, we'll build an article creation form for the blog, so authors have a nice way to write new posts.

Follow along with the in-class workshop. When you are done, you should be able to add new articles to the blog.

##  Notes (Key Terms)

## Class Videos

- [Python Lecture with Cris Ewing](https://www.youtube.com/watch?v=wgnG-F6PBHI&index=17&list=PLVngfM2hsbi8gIVLWmnvSc975LAPYInrA)
- [Forms Lecture (Coming Soon)]()


Ashley's notes:
() are the invocation operator
in a function, it invokes the function
Order of the call stack form bottom to top (see article.js):
.sort --> anonymous function --> new Date function
(the anonymous func?? is removed from the stack)

pushed to stack when called
removed from stack when (completed) return
array.push gives length of array
array.pop removes the last item in the array which reduces the length of the array

you can put "debugger;" into a function and the application will pause at that spot so you can review it.

$('#new-form').on('change' , articleView.create);
...if we had done this articleView.create()
immediately when the interpreter reads it (not when the event -inthis case change, actually fires)


opts is an Object from the info the user has entered

publishedOn: $('#article-published:checked').length ? new Date : null
The ? means...
if true, goes to new Date
if false, goes to null

hljs is the library we added to the html file to highlight


<!-- ```

function sayHi() {
console.log('Woohoo!');
}

``` -->
