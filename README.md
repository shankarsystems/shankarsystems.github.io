# jithinbp.github.io
Repository is for my GSoC-2017 github page http://jithinbp.github.io

For GSoC-17, I worked on several aspects of the Pocket Science Lab Project:

+ [Firmware development of the PSLab](https://github.com/fossasia/pslab-firmware) : Code for PIC24E processor written with MPLab IDE and compiled with XC16 compiler.
+ [Hardware design](https://github.com/fossasia/pslab-hardware) : Made with [KiCAD](http://kicad-pcb.org/)
+ [Desktop Applications](https://github.com/fossasia/pslab-desktop-apps) : My contributions were towards documenting the various apps and using Jekyll to render markdown files via templates . I cross checked a range of experiments in order to create screenshots, made several schematics, and fixed bugs in a few. I also added applications to calibrate the pslab using ADS1115 16-bit ADC module
+ [Python Communication Library](https://github.com/fossasia/pslab-python) : Made bug fixes in capture calls. Helped the android team to understand the various function calls during the porting process. Added support for several new add-on modules such as ADS1115, SX1278 LoRa module, MPU925x 10-DOF IMU sensor among others.
+ [remote laboratory](https://github.com/fossasia/pslab-remote) : Made a framework for accessing the PSLab remotely. This involves a backend designed with python flask, and a webapp made with ember-cli. A demo of the webapp hosted on [Surge.sh](pslab-remote.surge.sh), and the backend is hosted on [Heroku](pslab-stage.herokuapp.com)

A list of blog posts I wrote elaborating my journey :

+ [The Pocket Science Lab: Who Needs it, and Why](http://blog.fossasia.org/the-pocket-science-lab-who-needs-it-and-why-2/)
+ [Understanding PN Junctions with the Pocket Science Lab](http://blog.fossasia.org/understanding-pn-junctions-with-the-pocket-science-lab/)
+ [Calibrating the PSLab’s Analog Features for Maximum Accuracy](http://blog.fossasia.org/calibrating-the-pslabs-analog-features-for-maximum-accuracy/)
+ [Characteristization of Transistors Using PSLab](http://blog.fossasia.org/characteristization-of-transistors-using-pslab/)
+ [Designing a remote access framework with PSLab](http://blog.fossasia.org/designing-a-virtual-laboratory-with-pslab/)
+ [Creating backend API methods suing Python Flask](http://blog.fossasia.org/designing-a-remote-laboratory-with-pslab-using-python-flask-framework/)
+ [Execute python function calls remotely](http://blog.fossasia.org/designing-a-remote-laboratory-with-pslab-execution-of-function-strings/)
+ [Deploying the API server and Webapp to separate domains automaticaly ](http://blog.fossasia.org/pslab-remote-lab-automatically-deploying-the-emberjs-webapp-and-flask-api-server-to-different-domains/)
+ [Creating better structured apps from user submitted scripts](http://blog.fossasia.org/enhancing-the-functionality-of-user-submitted-scripts-in-the-pslab-remote-framework/)
+ [Adding a graph component to the frontend](http://blog.fossasia.org/including-a-graph-component-in-the-remote-access-framework-for-pslab/)

----

+ The PSLab project is inspired from ExpEYES  <http://expeyes.in>
+ FOSSASIA is supporting development and promotion of ExpEYES project since 2014 mainly through Google Summer of Code

Chat: [Pocket Science Slack Channel](http://fossasia.slack.com/messages/pocketscience/) | [Get an Invite](http://fossasia-slack.herokuapp.com/)
