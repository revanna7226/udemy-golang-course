# Udemy-golang-course

Checkout Tech docs: https://revs-tech-docs.netlify.app

### How to Get Help

One quick item before we dive into Go...

There are three ways to get help if anything goes wrong with the course:

Post in the QA discussion here on Udemy. I usually only answer questions once a day during week days only.
Email me at ste.grider@gmail.com. I will usually get you a response back within 24 hours
Message me on Udemy. Like email, I'll usually get you a response back within 24 hours
Now enough with the administrative stuff, let's get to coding!

### Course Resources

#### Finished Code

Finished code is attached to each applicable lecture throughout the course. If you get stuck at any point you can download the code and compare it against yours with a diff tool like Diffchecker or VSCode's built-in comparison tool.

#### Diagrams

The diagrams shown in the course are attached to this lecture note as a zip file.

Download the file and extract it somewhere on your computer.

Visit [diagrams.net](https://app.diagrams.net) (formerly draw.io).

Select Open Existing Diagram and use the file explorer to select the diagram file from your computer.

or

Click on File from the diagrams.net menu.

Select Open From Device and use the file explorer to select the diagram file from your computer.

Note - Please understand, if a diagram or group of diagrams is missing, this means that we no longer have them to share. You'll need to use a good screenshot browser extension to make a copy from the video lecture.

## Gopls, undeclared name, type and module errors in VSCode

As you progress through this course, you may notice some red underlining, undeclared name, or, type errors in your VSCode editor along with the following:

## gopls was not able to find modules in your workspace.

This can happen if you have loaded a directory that contains multiple Go projects into your editor workspace. The simplest solution to resolve these errors would be to instead open only the single Go project directory you are currently working on in the editor. None of our projects are dependencies of another project or module, so, setting up a multi-module workspace would not be necessary.

You will notice that in the video lectures, we purposefully only open a single project at a time in our editor to avoid this issue.
