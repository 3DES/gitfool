git-fool (c) 2014 Manfred Hauser - git (at) 74th (dot) de
=========================================================

a lightweight distributed multi-user bug and issue tracker for git


LICENSE
-------
This program is free software; you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation; either version 2 of the License, or (at your option) any later version.



INSTALL
-------
- install perl 5 (any newer version should work)
- load some modules from CPAN (run git-fool to check)
- set your $PATH variable so that git-fool can be found by git



FIRST STEPS
-----------
- change into git repository
- run "git fool init"
- run "git fool new this is my first issue"
- run "git fool ls"
- run "git fool cp 1", when asked for input choose "Bug", change milestone and enter comments
- run "git fool ls -l"



COMMNENTS
---------
- yes, I know that some stuff in git-fool isn't perl-ish but I don't want
  it perl-ish I want it maintainable and readable ;)

- there is another lightweighted bug tracker git-li what was the reason
  for me making git-fool. The idea is brilliant but the problem with git-li
  is that it's just a "single player game". So you could ask why not
  expanding git-li, but git-li is written in python and IMHO python is like
  a pain in the ass.
  If you don't believe read the following, I couldn't say it better:
    https://coosoft.wordpress.com/2013/02/24/the-perl-vs-python-debate/
    Thanks a lot to Tony Cooper for writing this blog entry!

- there is no "autorepair" function in the case one of the git-fool files
  is going to be damaged, same with "undo" function. In both cases git
  should be used because it's made for this job!
  On the other hand all the files are pure text files and in worst case they
  can be repaired manually with every text editor. Like Linthagorax once said,
  "everything is text" ;)


