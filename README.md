# Cyber Burger King

## Introduction

In order to get our work public for the project "Instructing Robots with Fundation Models", we transport the codes we've worked on since May, 2023 from gitlab to here. 
In our project, we tested the potential ability of a Large Language Model ChatGPT to interact with users for controlling the movable manipulating robot PR2 [makeareadme.com](https://robotsguide.com/robots/pr2) to make a burger, through proper prompting and flexible text commands. 

To get hands on experience by your own, you can follow the following steps to enter the world of our mini restaurant "Cyber Burger King". 

First in the main branch, you will find our main contribution and merged version of sections enviroment, arm, wheels and promptng workflow along with GUI design for ChatGPT in our own branches. The controller file "pr2.py" in the folder "controllers/pr2" and the world file "pr2.wbt" in the folder "worlds" are the executable file in the simulator Webots, you can download Webots through this official website [makeareadme.com](https://cyberbotics.com/) at first and open the world "pr2.wbt" along with its controller "pr2.py" that we created. After successfully openning the simulation enviroment, you will find the robot is making a cheese burger. If you scoll down to the executable codes generated by ChatGPT from line 758 to line 790, you will understand what instructions the robot are following right now. 

Next, in order to train ChatGPT to generate executable commands for making a burger, we designed a GUI and put it in the folder "controllers/pr2". The ChatGPT will follow the prompting steps shows in "initial_prompt_for_chatGPT.pyinitial_prompt_for_chatGPT.py". If the user finds problem in the results, he/she can further train ChatGPT to understand the task in GUI in a open-loop way. 

Finally, six test results of ChatGPT's responds of the command "make me a personalized-defined burger" are available in the file "Testing_more_complex_tasks.txt" in the folder "results". Since they are performed in a format that only GUI can directly transport it to the simulated robot, you will need to manually add a class "pr2." to each of the command if you want to transport the commands from ChatGPT to robot in a copy-paste mode.


## Gallery
![After prompting and training, ChatGPT is outputting its response for the request "make me a burger"](https://github.com/Supersolofly/Cyber_burger_king/blob/wheels/chatgpt1.png)
![In the simulated restaurant, the robot is making a burger based on the commands generated by ChatGPT](https://github.com/Supersolofly/Cyber_burger_king/blob/wheels/robot1.png)


## Support
If you have any question, you can contact us per email ge57nud@mytum.de.


## Authors and acknowledgment
As a team of five, we thanks the contribution that are made by all our team members, they are: Zihan, Xin, Fatma, Christopher, Yifei.

## License
not defined yet.

## Project status
There is a considerable potential for our project to try ChatGPT part into more creative ways and define the task-based API library part to be more diverse. Besides, the size of the restaurant can be expanded as well. More options of the foods can be invited to test waht is ChatGPT's limit in dealing with more complex tasks. 

Therefore, although the project status for our course is closed, as we finished the final smart goal in a nice way, we are looking forward to invite any team members of us or any of you who are watching right now to be the maintainer for the exciting future development.






