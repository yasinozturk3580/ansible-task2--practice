# ansible-task2--practice
# Task- install static web site :
  - create 2 VMs, centos 7 and ubuntu 20.04
  - create playbooks which will automatically run below tasks based on centos or ubuntu
       1- Install Apache
       2- Download a template from https://www.free-css.com/free-css-templates
  - Run playbooks and test,make sure web sites are accessible over public IP
    Createa new github Repository
    once the playbooks are raedy push them to the Github Repository
    And share screenshot of the web site -----------

    1-create  new repository on GitHub account.
    2- clone the repository to ansible vm machine on droplet.
       git clone ( repository IP address SSH )
    3- go to vsc and open the folder

    # create 2  folders
     1-solution #1
      create files = 1-redhat.yml 2- main.yml 3- debian.yml 4-hosts 

     2-solution #2
      create file = 1-main.yml  2- hosts 


    # ansible-playbook -i hosts  main.yml



