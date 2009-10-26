Flash Project Template
======================

Just a simple layout of folders/ files that I use for
all flash/ flex projects. Clone when creating a new
project then add a different remote branch to push to
as you start working on a specific project.

Usage
-----

 * Create a project in FDT (or other editor/ IDE?)
 * Open a commandline to the project directory and run:
<pre>
git init
git remote add template git://github.com/vitch/flash-template.git
git pull template master
git remote rm template
git rm README.md
git commit -m "Removed README file from template"
</pre>
 * Continue with your project committing normally to git and
   other remotes to push your work to...