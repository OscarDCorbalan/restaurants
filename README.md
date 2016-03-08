# Restaurants (Python + SQLite)

_This project is part of Udacity's Full Stack Developer Nanodegree._

This project consists in implementing **Python** modules that use **SQLAlchemy** with **SQLite** databases.

![screenshot](/vagrant/restaurants/screenshot.jpg?raw=true "Project as of 29 February 2016")

**TODO**

## Note: problem-set-1 folder

You can safely ignore it when running the project, as it's just a problem set to practice, where students need to rely on the SQLAlchemy documentation and Python documentation heavily, with freedom to use any other outside resources like StackOverflow or Flask blogs.



# How to run the project

To run the project tests, follow these steps:

1. Install [Vagrant](https://docs.vagrantup.com/v2/installation/)  if you don't have it already.
2. Grab a copy of the project. You can either:
  * Clone the repo with git: `git clone https://github.com/OscarDoc/fullstack-nanodegree-vm.git`.
  * [Clone with GitHub Desktop](github-windows://openRepo/https://github.com/OscarDoc/fullstack-nanodegree-vm).
  * [Download the latest release](https://github.com/OscarDoc/fullstack-nanodegree-vm/archive/master.zip)
3. Open a command-line window and go to the /vagrant folder of the project.
4. Once in it, run `vagrant up`. That will load the Virtual Machine, which has Python and PostgreSQL installed.
5. SSH into the machine with the username `vagrant`. Depending on your OS:
  * **NOT** Windows: just run `vagrant ssh`.
  * Windows: Running `vagrant ssh` will mourn that it's not possible and provide you an IP/port to log in. So, to log in, download [PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html) and follow the instructions [found here](https://github.com/Varying-Vagrant-Vagrants/VVV/wiki/Connect-to-Your-Vagrant-Virtual-Machine-with-PuTTY), which basically explain how to use the Vagrant VM certificate in PuTTY.
6. Once inside the VM, run `cd /vagrant/tournament`.
7. Once inside the folder:
  **TODO**


# What's included

**TODO**

Within the download you'll find the following directories and files, logically grouping common assets. You'll see something like this:
```
├── vagrant/  
│   ├── restaurants/            Tournament Planner
│   │   ├──README.md            --> THIS FILE <--
│   │   ├──X                    Automated tests  
│   │   ├──X                    Code  
│   │   └──X                    Definition of the DB  
│   ├── Vagrantfile             Virtual machine configuration  
│   └── pg_config.sh  
└── README.md                   Repository readme file  
```

# Test cases (strikethrough means implemented)

**TODO**