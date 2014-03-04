joapp
=====

A collection of small scripts that help you a lot when you create a new web application.

## Installation
Run the following command in the terminal:

```sh
$ sudo npm install -g joapp
```

## Help
```sh
$ joapp help

  JohnnyApp
  A collection of small scripts that help you a lot when you create
  a new web application.

  usage: joapp [actions] [options]

  actions:
    init           inits a new web application
    help           display this help content

  options:
      No options in this version.

  Documentation can be found at https://github.com/IonicaBizau/joapp/

```

## Utility
To create a "Hello World" web application, run:

```sh
$ joapp init
```

## Example
```sh
$ ls
hello-world
$ joapp init
Enter the project name:
The project name cannot be empty.
Enter the project name: hello-world2
Full Path hello-world2
Creating /home/username/Documents/test/hello-world2 directory ...
Copying hello world web application ...
Initializing git repository ...
Initialized empty Git repository in /home/username/Documents/test/hello-world2/.git/
Finished.
$ ls
hello-world  hello-world2
```

## Changelog

 - `0.1.0`
    Initial release

## License
See the LICENSE file.
