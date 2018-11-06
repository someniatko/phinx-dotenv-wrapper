# phinx-dotenv-wrapper
Wrapper over phinx binary (`robmorgan/phinx`) with added support for .env file.


## Installation
Run `composer require someniatko/phinx-dotenv-wrapper`.


## Usage
Add .env file to the root of your project. Then, instead of running
`./vendor/bin/phinx`, use `./vendor/bin/phinx-dotenv-wrapper`. Commands and their arguments stay the same.
