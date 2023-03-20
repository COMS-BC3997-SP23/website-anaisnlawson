---
layout: default
---
## Refined Figma
I wanted to refine my figma design even further to try to get feedback from my client so this is another walkthrough

![test](assets/website-run.mov)
## Working with React (Plot twist -- Not through gatsby)
Like I mentioned last week I'm not too familair with gatsy so I decided to make it more simple to make it easier to address errors 
For creating the website I had to reconsidered utuilizing gatsby and decided to go more barebones after discussing with my partners. 
Instead I decided to install react from scratch and start my editing that why following a Youtube tutorial that I found 
[Tutorial](https://www.youtube.com/watch?v=LMagNcngvcU).

As I followed the video I realized they were utilizing the `npx` command instead of `npm` command which initialize a new react app so I had to do some research into what the difference between them was.
After some research and utilizing the explanation from this website 
[FreeCodeCamp](https://www.freecodecamp.org/news/npm-vs-npx-whats-the-difference/).
It states that: 
“npx helps us avoid versioning, dependency issues and installing unnecessary packages that we just want to try out.

It also provides a clear and easy way of executing packages, commands, modules and even GitHub gists and repositories.”

So I first started with the command

    $ npx create-react-app ./ 

Afterwards I was able to pull up the files create in the visual studio code

One other hack that was shown was being able to use an extension 
ES7+ React/Redux/React-Native snippets to make coding more efficient

To get run the website locally I had to use the command

    $ npm state

I used this website called 
[AngryTools](https://angrytools.com/gradient/)
Great for getting the css code for the gradient!

Conveniently Figma also gives has an inspect feature that could give me exactly what I had for my mockup so I used that instead:

    background: linear-gradient(180deg, rgba(155, 38, 38, 0.76) 0%, rgba(155, 129, 38, 0.76) 51.04%, rgba(69, 155, 38, 0.76) 90.1%);

It did create an issue where the gradient was repeating instead of spanning the whole body so I had to use this code additionally

    height: 100%;
    margin: 0;
    background-repeat: no-repeat;
    background-attachment: fixed;

*note: In the video they just focus on the navbar but I didn’t what that for our page*

Next step for me is adjusting the NavBar, creating multiple pages for each section, adding content, as well as researching more into web hosting (which was actually what the first thing the guy in the video did)




[< Back](./)
