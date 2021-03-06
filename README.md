Comet.js
=======

Comet.js, help you in your development with Meteor.js creating what we
understand what should be a directory structure and files to Meteor.js
that himself recognizes. Following the organization:

```sh
  ├── mobile-config.js
  ├── LICENSE
  ├── README.md
  ├── .gitignore
  ├── client
  │   ├── helpers
  │   ├── i18n
  │   ├── styles
  │       ├── includes
  │           ├── _breakpoints.styl
  │           ├── _mixins.styl
  │           ├── _palette.styl
  │           ├── _settings.styl
  │           ├── _typography.styl
  │           ├── _variables.styl
  │       ├── main.styl
  │   └── views
  │       ├── main.html
  │       ├── main.js
  ├── lib
  │   └── routers 
  │       └── router.js
  ├── collections
  ├── packages
  ├── private
  ├── public
  │   ├── fonts
  │   ├── icons
  │   └── images
  ├── server
  └── tests
```

## TOC
  1. [Requirements](#requirements)
  2. [Installation](#installation)
  3. [Configuration](#configuration)
  4. [Usage](#usage)
  5. [Generator](#generator)
  5. [roadmap](#roadmap)
  6. [How to help](#contributing)
  7. [License](#license)

## Requirements
Coming soon

## Installation
```sh
  npm install -g cometjs
```

## Configuration
No need configuration

## Usage

CLI Usage:
```
Usage: comet [command]

  new [name]  Make a subdirectory called <name> and create a new Meteor app,
	based in our skeleton, there.
```

Generate a new skeleton meteor stack with:

```sh
  comet new [name]
```

and after
```sh
	cd [name]
	meteor
```

## Generator
Coming soon

## Roadmap
Follow the CometJs Roadmap on Trello:
[https://trello.com/b/Wn2wCDCu/cometjs](https://trello.com/b/Wn2wCDCu/cometjs)

## Contributing
Coming soon

### TODOS ###

* Support scaffold
* Create new themes with codebases in git repositories

## License
Comet.js is available under the MIT license.
