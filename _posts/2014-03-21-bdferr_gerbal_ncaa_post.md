---
layout : post
author : 
 - grant
 - bdferr
title : Grant and Brendan's collaboration
---

Brendan was at first confused about the placement of the NCAA repo; he had cloned it as ncaa inside of the spring2014 directory. Grant explained that “git repos do not live happily inside of each other,” so Brendan employed rm –rf ncaa. This one command removed all of the files in the ncaa directory, including all of the files in its subdirectories, then removed each subdirectory once it was empty, then removed the folder “ncaa” once it was empty. Brendan then respawned the ncaa directory outside of the spring2014 folder, so that it could have more Lebensraum.

After cloning the NCAA github repo in nitrous, Brendan made a branch called “wisconsin” inside it. He added the requested labels and pushed the file to the master branch for Grant to pull down to his own fork and edit, and Grant similarly entered the labels for the Arizona team on a newly created "Arizona" branch and pushed the Arizona file to the origin.

Brendan then pulled the Arizona file to his own fork and entered data about the Arizona Wildcats basketball team. Grant did the same for the Wisconsin Badgers.
 
Brendan did not know anything about basketball, but after searching Wikipedia and an ESPN [page](http://espn.go.com/mens-college-basketball/tournament/history/_/team1/5229) which Google (through Startpage.com) brought him to, he was able to find the relevant data.

Grant merged Brendan’s pull request [here](https://github.com/silshack/NCAA/pull/37), while Brendan merged Grant’s pull request [here](https://github.com/silshack/NCAA/pull/38).