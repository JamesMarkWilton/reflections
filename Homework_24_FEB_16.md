============================================== Git and Pairing ==================================================

  To start you need to pick someone to Host the git repo on github
Once you have that all other memebers should be added as contributers and they
should clone the repo to a their computers. With this all people have copies and the branching can begin.
When you're working on your computer you should start by doing a git pull so you have the most up to date
version of the project. Then you set up a seperate branch with git checkout -b "BRANCH NAME" This is so you
can make changes to your copy but keep the Master branch seperate so you always have a working copy that is
the same as your partners. Once you are ready to commit a change. (Which you should do often) one that adds
to the project but doesn't have to be perfect. you should do a git status to see the changes and files you want
to commit. git add those files that are worth it. Then status to make sure it is all set to commit. Then
git commit them with comments about what you have done. Then you git push the Branch you have created to origin
or github. Then you go to the project git page and do a pull request to the master branch. After you have made the
request. One of oyur other team members should review the changes you want to add and merge the branch to the master.
Now they master has to changes and you can delete the old branch and git pull the new updated Master to your computers.
This keeps the project organized and makes sure that all tema members are aware of changes and what is going on in the
project.

=================================================== Gitloc ==============================================================

  Gitloc is a Ruby Gem that we created that takes a git repo either on your local system or from github and looks at all
the files puting to the commandline the file names and the number of lines of code in those files. It gives you an overview
of a repo and what it contains without getting into too much crazy detail about what is inside. The main idea behind the project
wasn't just to show us how many lines of code were in a repo though. It was to give us a way to look at developing and building
an executable program or something that could be used by many different people to do something pretty cool. It teaches you about
Gems too! Which are pretty cool. They're ways to package ruby code and make available to many different people. When used properly
they can be a valuable tool to take parts of your code that you use often but never touch and place it in a file that can be accessed
by many other programs and used but no need to mess with the inner working. although you can. The project helps us to see this and set
it up so that things are organized but seperate. Each part of the git loc program knows aout itself and it's fuctions but doesn't have
to deal with things outside of it's scope. The executable file is in bin and just deals with running the code which is housed in the
lib folder. This has the nuts and bolts the working parts of the program and handles the work load. The other idea introduced was the
gemspec file which tells the gem installer about the program and it's creator it also allows us to install and create the gem. This
sepration is important because it doesn't clutter files with stuff they don't need. And it clearly breaks up the work flow of the
program. The project also touched on things that we had worked on before like LOAD_PATH, where ruby looks to find your files to run
code. And it Gave us the idea of name spacing or making a program not conflict with other programs on a system by palcing it in it's
own set of dirs and clearly marked folders.

======================================= A trick I have picked up or something useful ===============================================

  I think this is a tricky question.....I have learned a lot of habits for better learning and different ways of looking at or tackling
this wild crazy big world that I have decided to dive into. I have been a student for well ost of my life and I have doubts that this will
ever change. I think someone once said that when you stop learning you start dying....and I am in no rush to die. So I think that the new
insites I have gained into the ever present passion of curiosity are what is helping me the most in the class and just in learning in general.
Being able to think about the task of taking on a strange world of 1's and 0's by breaking down the skills in front of me into usuauble small
tasks to tackle and hone. Thinking about the abstract as having a tangable element that I can pratice and build upon while also knowing that
parts are there to think through and ponder. Imporves the experince. Knowing that there are parts of it that I can gain a foothold in while
I work on understanding others helps me to place goals on my process and see that I am learning not just banging my head trying to remmeber
what a regex is or how a module talks to an object, which a class can be be also create....It's I think the idea that no matter how much I learn
I will always have skills to work on and other things to learn. Start out small and build and build and then take that knowledge and style of
learning and go find other stuff to tackle or play with to expand upon my job and me future and my knowledge of computer. Science!

  Ok so if you wanted a more concerte thing that I have found useful while I am on this learning escaped. I have found pry to be a tool I could not
live without. I still don't know everything there is to do with it or even how to navigate what I do use it for perfectly. But placing it in some
code where I am stuck trying to find a way to deal with some data. Methods I can call on it or what it is actually doing while it passes through my
code. What state it is sitting in. What my code is actually returning. These are the questions I bring with me into pry. I place the binding with \p
I then start by seeing what state a variable is in. Jsut call the variable a see what pry returns. Or I put in a small blaock and see what comes back.
Most cases this allows mw to see what i then can do with that return value. Call ls -v and start playing with these methods. Seeing what they will do
with show-doc (plus the code) or I just run it and see what it returms. This ability to not have to guess what is comming out of a method call or what
trying to remember that sutpid method that does that thing that I need all the time both helps me to remember oh yeah that was the method I called to
make it do that thing. Plus it shows me new stuff I can do to data all the time. I spend more time playing with code and testing ideas rather then
trying to figure out where thimgs are going in my head before writing it out. Just do it!

I also found that adding NERDtree to your vim is super helpful. It is a directory handler that lets you see you PWD or any directory and file then just open
that file in bim to edit rather then jumping out of vim and pulling it up on the command line. The commands are the same as vim and super simple like o opens
the dir or file and s splits the screen w/ the current file and the new one. That way I can look into a couple files at once which is nice if you have four files
talking to each other. I don't have to jump out and break my train of thought to find info I need quick. Ok now that i am doen with my sales pitch I will leave you
with another thought about learnoing. "There is nothing new under the sun, but there are lots of old things that we don't know!"
