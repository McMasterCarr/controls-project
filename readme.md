Controls Project
Steps:
1. Connect to netgear wifi
2. open command prompt and ssh into raspberry pi
    command: "ssh pi@raspberrypi.local"
3. say "yes" to question about connecting.
4. type "cd controls-project"
5. command "git pull"
6. to run the program type "python3 main.py"

To update code from laptop to repository:
1. open command prompt 
2. type "cd Documents"
3. type "cd command-project"
4. type "git push"

Now the code on your computer is up on the repository and ready to pull from the raspberry pi

To update code from repository to raspberry pi:
1. Connect to netgear wifi
2. open command prompt and ssh into raspberry pi
    command: "ssh pi@raspberrypi.local"
3. say "yes" to question about connecting.
4. type "cd controls-project"
5. command "git pull"