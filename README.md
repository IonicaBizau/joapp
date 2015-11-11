# `$ joapp` [![Support this project][donate-now]][paypal-donations]

A collection of small scripts that help you a lot when you create a new web application.

## Installation

You can install the package globally and use it as command line tool:

```sh
$ npm i -g joapp
```

Then, run `joapp --help` and see what the CLI tool can do.

```sh
$ joapp --help
  
  JoApp
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
$ tree ./
./
├── hello-world
│   ├── css
│   │   └── style.css
│   ├── index.html
│   └── js
│       ├── functions.js
│       └── jquery.min.js
└── hello-world2
├── css
│   └── style.css
├── index.html
└── js
├── functions.js
└── jquery.min.js

6 directories, 8 files
```

## Documentation

To create a *Hello World* web application, run:

```sh
$ joapp init
```

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:

## License

[KINDLY][license] © [Ionică Bizău][website]

[license]: http://ionicabizau.github.io/kindly-license/?author=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica@gmail.com%3E&year=2014

[website]: http://ionicabizau.net
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md