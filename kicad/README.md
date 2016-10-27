## Introduction

Original **Pixhawk 2.1** FMC project has been implemented using Altium under OSH license.
**Altium** is a great EDA tool but still unavailable for most of OSH community people due
to expensive licenses.

This directory (will) contain **Pixhawk 2.1** project artifacts converted to **KiCAD** format.
Also it contains **altium2kicad** tool as a submodule.

Everyone are welcome to participate in this effort. The workflow that would be good to
follow is proposed below.
 
## Workflow

1.  Fork this repository to make your personal work repository
1.  Make local clone of your work repository using *git clone*
1.  *cd pixhawk2.1/*
1.  *git checkout transition-to-kicad*
1.  *git checkout -b name-of-your-branch*
    It is good to use meaningful branch names like: *fix-description-text-aligned* or *feature-esd-protection-added*
1.  *git submodule update --init --recursive*
1.  Perform your changes
1.  Add them with *git add* and commit the with *git commit -m "some meaningful changes description"*
1. *git push origin name-of-your-branch*
1.  Open your github repository in browser
1. Create new pull request from *name-of-your-branch* branch in your repository to *transition-to-kicad*
    branch of this repository
    
Feel free to submit issues here.