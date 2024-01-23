GitHub-Actions Project 
-----------------------------

GitHub Hosted Runners
----------------------

Launch an EC2 instance and edit the inbound and outbound rules to allow only http and https from anywhere IPV4. 
addition.py is python file.
create an .yml file which runs on: ubuntu-latest inside .github/workflows/ folder which describes jobs to be done by the GitHub-Actions.
Click on the Actions that is present under repository name.
Click the name of the run from the lsit of workflow runs.
Under jobs, select which u want to see.
The log presents how each step is proceeded.

Self Hosted Runners
---------------------------
Launch an EC2 instance and edit the inbound and outbound rules to allow only http and https from anywhere IPV4. 
addition.py is python file.
create an .yml file which runs on: self-hosted inside .github/workflows/ folder which describes jobs to be done.
Click on settings
On the left pane click on Actions then Runners
Click on New self-hosted runner
Select the Operating system and architecture of your self host machine.
Follow the instructions for downloading and installing the runner application.
Open terminal and excute each command in order.

