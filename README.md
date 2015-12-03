# `$ joapp` [![Support this project][donate-now]][paypal-donations]

A collection of small scripts that help you a lot when you create a new web application.

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

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## License

[MIT][license] © [Ionică Bizău][website]

[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2014#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md