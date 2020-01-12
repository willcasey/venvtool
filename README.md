## A Minimilalist Approach to Managing Python Virtual Environments 
The venvtool is a simple, minimalistic tool to help you manage your 
python virtual environments.

You will easily be able to 
create, list, activate, deactivate and remove your virtual environments.

## Prereqs
1. You will need to install pip if you don't already have it.
Instructions to do that can be found here:
2. you need to install virtualenv using pip
```
pip install virtualenv
```

## Installation
1. Download or clone this repo
2. In your terminal, run the following command in the same directory that you downloaded the files to
```
sh setup
```
The venvtool setup script will add the vnv command line tool to your executable path
as well as create a default directory for your virtual environments in your systems'
home directory.
You may be required to type in your password.

## Sample Usage
1. First you need to create a virtual environment
```
vnv -c <test_env>
```

You will be able to see your virtual environments using this command:
```
vnv -ls
```

2. Then you can activate your virtual environment.
```
vnv -a <test_env>
```

3. Do awesome python work

4. When you are done with your work you can deactivate your virtual environment 
```
vnv -d
```


## Commands
```
-c <virtual_env>, --create <virtual_env>		Creates a virtual environment. 
-a <virtual_env>, --activate <virtual_env>		Activates a virtual environment. 
-rm <virtual_env>, --remove <virtual_env>		Removes a virtual environment from the directory.
-ls 							List all available virtual environments.
-d, --deactivate					Deactivates the current virtual environment.
-h, --help						Shows help for commands.
```

