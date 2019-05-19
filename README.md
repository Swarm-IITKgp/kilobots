# Kilobots
All the work related to kilobots.
# Getting started with kilobots
* Latest official kilobots [documentation](https://www.k-team.com/mobile-robotics-products/kilobot).

* [Paper](http://csl-ep.mech.ntua.gr/pdf_ps/ICRA206.pdf) on how kilobots move using vibrational motors.

* [Harvard website](https://ssr.seas.harvard.edu/kilobots) for kilobots. [Mirror link](http://www.eecs.harvard.edu/ssr/projects/progSA/kilobot.html).

Kilobot hardware and software [details](https://projects.iq.harvard.edu/files/ssr/files/kilobot_documents.zip).  

[More insight into design of kilobots](https://github.com/Swarm-IITKgp/kilobots/blob/master/maker-a-kilobot-swarm.pdf)

[Good Resource of Kilobotics](http://home.iitb.ac.in/~anuragg/files/kilobotics.pdf).

[Simple tutorials to get started with programming](https://www.kilobotics.com/labs#lab4-orbit).

[Here You can Download V-Rep for simulating kilobots.](http://www.coppeliarobotics.com/downloads.html)

After Downloading, execute any .ttt file in terminal like this:
`./vrep.sh Kilobots_around.ttt`

[This](https://www.kilobotics.com/docs/index.html) provides details about all the different functions and data structures present in kilolib library.

Some common tips while using V-Rep Simulator for Kilobots:

1 :- The script is in Lua Language so while using it. Refer to [This](https://www.lua.org/docs.html) Lua documentation.

2 :- Before running you have to ensure that you have the models of controller and kilobots i.e. their .ttm files. added to the system.
Their files may be located in something like /home/username/V-REP_PRO_EDU_V3_6_1_Ubuntu16_04/models/robots/mobile

3 :- After editing the script, you have to ensure that you have clicked the Download like button on the top left most area which ensure that your changes have been added to the scene. 
