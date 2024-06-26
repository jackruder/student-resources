# README #

In this repo, we provide resources for new students in cs, math,
and stat.  These are the resources that we have found
helpful for our students, and we hope will help you as well.

## Git ##

To clone this repo:
```
$ git clone https://<username>@bitbucket.org/tda-at-msu/student-templates.git
```

When collaborating, we usually commit directly to master and do not go through
issuing pull requests.  As such, the workflow is typically the following:
```
$ git pull [[to make sure you're up-to-date]]
$ [[edit]]
$ git status [[make sure the files edited match what you expect!]]
$ git add [[list files to stage]]
$ git commit -m "[[good commit message here, see resources below]]
$ git pull [[just in case someone else snuck in]]
$ git push [[now, you're done!]]
```
Of course, the words in the brackets are comments and not part of the commands.

For additional resources on git, take a look at:

- [Git Udacity
  Course](https://www.udacity.com/course/how-to-use-git-and-github--ud775)
- [Forking in Git](https://help.github.com/articles/fork-a-repo/)

When working in a group, commit messages are very important.  Your collaborators
(and even your future self) will be very thankful for well crafted messages.
Typically, the messages will start with a verb (with first letter capitalized)
in the present tense and will finish the sentence "Pulling this commit will ..."
For more on how to write good commit messages, see blogs from:

- [Erlang project](https://github.com/erlang/otp/wiki/writing-good-commit-messages)
- [Tim Pope](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
- [Chris Beams](https://chris.beams.io/posts/git-commit/)

## Academic Writing ##

Academic writing is mastered in one way: practice and learn from your mistakes.  The following resources we find helpful:

- [Shewchuk's 3 Sins](https://www.cs.cmu.edu/~jrs/sins.html)
- [Ott's 10 Tips](http://www.ms.uky.edu/~kott/proof_help.pdf)
- [Communicating Statistical Results](https://www.math.ttu.edu/~atrindad/stat5302-5303/Materials/Hoeting-Givens.pdf):
  Written for statisticians, but applicable for all scientific articles.
- [Bibtex Cheatsheet](https://en.wikibooks.org/wiki/LaTeX/Bibliography_Management)
- Pseudocode resources:
  [Pseudocode
  1](https://onlinelibrary.wiley.com/doi/pdf/10.1002/0470029757.app1)
  [Pseudocode 2](https://www.cs.oberlin.edu/~asharp/cs383/2007fa/handouts/pseudocode.pdf)
- [Journal Abbreviations](https://mathscinet.ams.org/msnhtml/serials.pdf) lists
  standard abbreviations for most journals.
- [That vs. Which](https://www.quickanddirtytips.com/education/grammar/which-versus-that-0) explains when to use the word 'that' versus 'which', and how to properly punctuate both.
- [Graphical
  Abstracts](https://www.animateyour.science/post/how-to-design-an-effective-graphical-abstract-the-ultimate-guide)
  are a great way to give a visual summary of your papers that help readers
  digest the technical stuff.

## Posters and Figures ##

Presenting posters at academic conferences is a great way to practice talking
about your research.  We recommend using Inkscape to create posters, and provide
a template in the poster folder.

- [Poster Tips](https://www.makesigns.com/tutorials/poster-design-layout.aspx):
  a great resource for knowing what font size to use, etc.
- [Inkscape Soup Can Tutorial](http://tavmjong.free.fr/INKSCAPE/MANUAL/html/SoupCan.html): this tutorial gives you a jump start on using Inkscape (basically, the free version of illustrator).  Some keyboard shortcuts are given.
- [Advanced Inkscape](https://inkscape.org/en/doc/tutorials/advanced/tutorial-advanced.en.html)
- [textext](https://textext.github.io/textext/install/windows.html).  There is a bug with textext in Mac, see [wiki](https://github.com/compTAG/student-resources/wiki/Inkscape-&-Mac-Errors-with-textext) for how to fix.
- [Figure
  Captions](http://www.biosciencewriters.com/Tips-for-Writing-Outstanding-Scientific-Figure-Legends.aspx) in papers:
  This website is a great resource for how to write a figure caption. If you
  want a concrete example, take a look at [this
  paper](http://pub.ist.ac.at/~edels/Papers/2012-P-11-PHTheoryPractice.pdf) as
  well.

## File Naming ##

When naming files (and directories), be sure to follow common practices.
[Google](https://developers.google.com/style/filenames) has nice documentation
that explains how to properly name files.  Some things to consider:

- Do not use spaces in filenames.
- Make filenames informative, yet concise.
- Use dashes between words in long filenames.
- Each repo should be self-consistent.

Following these guidelines makes it easy for you and your collaborators to find
what you need!

## Introductory Readings for Topics ##

### Persistent Homology
- [Dey/Wang Book](http://yusu.belkin-wang.org/CTDAbook-DeyWang.pdf) (can start with chapter 2)
- [Edelsbrunner/Harer Book](https://bookstore.ams.org/mbk-69/): Covers
  persistent homology, comparison of diagrams, and more.
- [Persistent Homology: a Survey - HE,
  JH](https://www.researchgate.net/publication/228629885_Persistent_homology-a_survey):
  A concise survey of persistent homology.
- [What is Persistent Homology -
  SW](http://www.ams.org/notices/201101/rtx110100036p.pdf): AMS survey article.

### Computational Geometry
- [Dutch/Marks Book](https://www.springer.com/us/book/9783540779735)
- [David Mount's lecture notes](http://www.cs.umd.edu/class/fall2014/cmsc754/Lects/cmsc754-fall14-lects.pdf)
- [Devadoss and O'Rourke](https://press.princeton.edu/titles/9489.html)
- [Computational Geometry in C](https://cs.smith.edu/~jorourke/books/compgeom.html)

## Who to Contact with Questions and Suggestions ##

- [Brendan](https://brendanmumey.wordpress.com/)
- [Brittany](http://www.fasy.us)
- [Carola](http://www.cs.tulane.edu/~carola/)
- [David](http://www.millman.us)
- [Stacey](http://www.math.montana.edu/shancock/)
