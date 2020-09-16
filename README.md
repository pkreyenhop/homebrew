How to clone PK's Homebrew Setup for Common Lisp
=================================================
This install contains all the software to get started with Common Lisp.
The setup is based on SBCL and emacs. Part 2 will get emacs configured and part 3 will configure SBCL.


1. install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```
2. install git 

```
brew install git
```

3. clone this repo to new box

``` 
git clone https://github.com/pkreyenhop/homebrew.git
```

4. install everything

```
cd homebrew
brew bundle
``` 
