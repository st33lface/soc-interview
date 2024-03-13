# Security Operation Control Interview - CRDC
##### Your goal will be to protect our company while we empower our customers.
&nbsp;
![CRDC](/images/logo-rodape.png "CRDC - Central de Registro de Direitos Creditórios")

## About the test 


- First of all, remember that you can use any technology to help you solve the problems. We're here just to challenge you to think.
- Don't be afraid of finishing the test on time. Take care to explain your mindset and ask us anytime you want. 
- We won't give you the answers, but we'll help you through the path.
- Anytime you want, take a deep breath and drink a couple of sips of water
- At the end of the test, you must commit your changes and push it to our repository.

 
# Requirements
- Install Git and Github CLI
 
Linux (Ubuntu based)
```sh
sudo apt update && sudo apt install git
```
```sh
sudo apt install gh
```
Windows
```sh
winget install -e --id Git.Git
```
```sh
winget install github.cli
```
- Configure Github CLI to be able to clone our repository
```sh
gh auth login
```
select github.com and hit enter 
```sh
What account do you want to log into? GitHub.com
```
select SSH and hit enter 
```sh
What is your preferred protocol for Git operations on this host? SSH
```
hit enter
```sh
Generate a new SSH key to add to your GitHub account? Yes
```
hit enter
```sh
Enter a passphrase for your new SSH key (Optional)
```
hit enter
```sh
Title for your SSH key: GitHub CLI
```
select Login with a web browser and login to your account 
```sh
How would you like to authenticate GitHub CLI? Login with a web browser
```

- Clone the following repository

```sh
git clone https://github.com/claytonpiccinin/soc-interview && cd soc-interview
```

# Challenge 

Let's start thinking about the problem. We suffered an attack 😧, and we're trying to understand step by step what happened.
Your goal here, is to help us to understand. 

Read carefully and analyze these events: 

```sh
A - Open the Archive1 json file and analyze:
 1 - Find the malicious sample family.
 2 - Find the hostname.
 3 - Find the username.
 4 - Find the date (mm/dd/year).
 5 - What should you do to perform containment?
 6 - What do you think about this event behavior? Is it True or False?
```
```sh
B - Open the Archive2 json file and analyze:
 1 - Find the user involved in this event.
 2 - Find all IPs and write about there are. 
 3 - What could a hacker do inside this network?
 4 - What do you think about this event behavior? What could've happened here? Is it True or False?
```
```sh
C - Incident Response
    1 - What do you understand by Incident Response?
    2 - Which are the Incident Response phases?
    3 - What do you understand by CSIRT (Computer Security Incident Response Team)?
    4 - Which are the differeces between personal data and sensitive data?
```
GOOD LUCKY :)
