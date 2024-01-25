GitHub-Actions Project 
-----------------------------

GitHub Hosted Runners
----------------------

Launch an EC2 instance and edit the inbound and outbound rules to allow only http and https from anywhere IPV4.<br>
addition.py is python file.<br>
create an .yml file which runs on: ubuntu-latest inside .github/workflows/ folder which describes jobs to be done by the GitHub-Actions.<br>
Click on the Actions that is present under repository name.<br>
Click the name of the run from the list of workflow runs.<br>
Under jobs, select which u want to see.<br>
The log presents how each step is proceeded.<br>

Self Hosted Runners
---------------------------
Launch an EC2 instance and edit the inbound and outbound rules to allow only http and https from anywhere IPV4.<br> 
addition.py is python file.<br>
create an .yml file which runs on: self-hosted inside .github/workflows/ folder which describes jobs to be done.<br>
Click on settings.<br>
On the left pane click on Actions then Runners.<br>
Click on New self-hosted runner.<br>
Select the Operating system and architecture of your self host machine.<br>
Follow the instructions for downloading and installing the runner application.<br>
Open terminal, login into EC2 instance and excute each command in order.<br>

