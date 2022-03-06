# Install command line tools
If command line tools are installed, error will be displayed
```angular2html
xcode-select --install
```

# Install Homebrew
Check if homebrew is installed. 
```angular2html
brew
```
To install homebrew:
```angular2html
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

To list the packages we can install: 
```angular2html
brew search
```

To check the total number of packages: 
```angular2html
brew search | wc -l
```

To narrow down the results: 
Formula: command line software
Casks: extension of macos
```angular2html
brew search <package_name>
```

# Uninstall Packages
```angular2html
uninstall <package_name>
```


# Tree
Install
```angular2html
brew install tree
```
Check tree of a folder
```angular2html
tree <directory>
```

Information about package
```
brew info tree
```

# Check Packages

Update all packages
```angular2html
brew update
```

List outdate packages
```angular2html
brew outdated
```

Upgrade packages
```angular2html
brew upgrade
```

Remove old versions of packages
```angular2html
brew cleanup
```


# Cask
Install application
```angular2html
brew cask install <application_name>
```

Search command
```angular2html
brew search pycharm
```

Home page of software
```angular2html
brew cask home
```


# Locate Packages

Tap the repository
```angular2html
brew tap heroku/brew
```

Search repository results
```angular2html
brew search heroku
```

Install heroku
```angular2html
brew install heroku
```

