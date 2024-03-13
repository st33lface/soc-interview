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

- Clone the following repository

```sh
git clone https://github.com/claytonpiccinin/soc-interview && cd soc-interview
```

# Challenge 

Let's start thinking about the problem. We suffered an attack 😧, and we're trying to understand step by step what happened.
Your goal here, is to help us to understand. 

Read carefully and analyze these events: 

A - Open the Archive1 json file and analyze.
 1 - Find the malicous sample family.
 2 - Find the hostname.
 3 - Find the username.
 4 - Find the date (mm/dd/year).
 5 - What should you do to perform eradication?.
 6 - What you think about this event behavior? It's True or False?.

B - Open the Archive2 json file and analyze:
 1 - Find the user involved in this event.
 2 - Find all IP's and write about there are. 
 3 - What could a hacker do inside this network?
 4 - What you think about this event behavior? What could have happened here? It's True or False?
 
 
```sh
 ```

As [John Gruber] writes on the [Markdown site][df1]

> The overriding design goal for Markdown's
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [Gulp] - the streaming build system
- [Breakdance](https://breakdance.github.io/breakdance/) - HTML
to Markdown converter
- [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
