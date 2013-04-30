---
layout: post
title: "secrets of the software conference pros"
description: ""
category: 
tags: []
---
{% include JB/setup %}



Have you ever been at a development conference and been struck by the
developers command of the command line. Not to say that they are all
snake oil and high equity mortgage salesman but most of them use a bit
of linnix illusion. 

The trick to pulling this of is to record your bash session with something like the script or ttyrec commands. If your on debian or ubuntu you likely still have scriptreplay available to you. 

record your session

    script -t 2> tutorial.timing -a tutorial.session

execute what you you want to show off
exit the session 
replay

    scriptreplay tutorial.timing tutorial.session

if your not on debian you need to build ttyrec

    git clone git@github.com:mjording/ttyrec.git
    cd ttyrec
    make

If you don't have the  directory setup (from macports or another unix add on)
 
    sudo /bin/mkdir -p /usr/local/bin
    sudo /usr/sbin/chown root:wheel /usr/local /usr/local/bin
    sudo /bin/chmod 0755 /usr/local /usr/local/bin 

Otherwise copy the binary in and make some shortcuts

copy ttyrec, ttyplay and ttytime to /usr/local/bin

    sudo /bin/cp -i ~/Desktop/ttyrec-1.0.8/ttyrec /usr/local/bin
    sudo /bin/cp -i ~/Desktop/ttyrec-1.0.8/ttyplay /usr/local/bin
    sudo /bin/cp -i ~/Desktop/ttyrec-1.0.8/ttytime /usr/local/bin

Now you can record your session to a file via

    ttyrec -a tutorial.session

and play it back with 

    ttyplay tutorial.session

ttyrec also has advanced features that allow you to adjust playback speed. 

