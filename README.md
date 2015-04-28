## Backend Developers
---

Install Brew:

    $ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Install Ruby:

    $ brew install/upgrade rbenv
    $ brew install/upgrade ruby-build
    $ rbenv install 2.1.5

Install bundler:

    $ gem install bundler

Install middleman:

    $ gem install middleman

Clone and bundle install

    $ git clone git@github.com:nepalidevelopers/nepalidevelopers.github.io.git
    $ cd nepalidevelopers.github.io
    $ bundle install

Available commands:

    $ middleman               # Run the preview server at http://localhost:4567
    $ middleman deploy        # Deploy to gh-pages (http://nepalidevelopers.github.io)
