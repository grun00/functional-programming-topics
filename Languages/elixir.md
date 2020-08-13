
## Oficial Documentation of Elixir

https://elixir-lang.org/

## Installation

#### macOS

* Using Homebrew:
```
brew update
brew install elixir
```
* Using Macports:
 ```
sudo port install elixir
 ```
#### GNU/Linux

* Arch Linux (Community repository)
```
pacman -S elixir
```

* Ubuntu 14.04/16.04/17.04/18.04/19.04 or Debian 7/8/9/10

    Add Erlang Solutions repository:
```
wget https://packages.erlang-solutions.com/erlang-solutions_2.0_all.deb
sudo dpkg -i erlang-solutions_2.0_all.deb
sudo apt-get update
sudo apt-get install esl-erlang
sudo apt-get install elixir
```

## Variables Names

In Elixir, a variable name always starts with a lowercase alphabetic character or an
underscore. After that, any combination of alphanumerics and underscores is allowed.
The prevalent convention is to use only lowercase ASCII letters, digits, and underscores:
* valid_variable_name
* also_valid_1
* validButNotRecommended
* NotValid

Variable names can also end with the question mark (?) or exclamation mark (!)
characters:
* valid_name?
* also_ok!
