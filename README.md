# goldcoinbalance


Frontend website for <a href="https://goldcoinbalance.com">Gold Coin Balance</a>

### Devlopment environment setup

Install node and npm from https://nodejs.org/en/

Install bower:

    npm install -g bower

Check out the project from version control:

    git clone git@github.com:alleyway/goldcoinbalance.git
    cd goldcoinbalance

Install project dependencies:

    bower install


### Publishing changes

Github pages uses jekyll on their server to build the site, so for small changes, you can generally just edit the files and do a git push

    git add .
    git commit
    git push origin

### Running site locally for development

Handy for instantly seeing your changes in the browser by running a server on your local computer.


#### Install prerequisites
    
Install Homebrew from https://brew.sh/

Use Homebrew to install ruby:    
    
    brew install ruby

Update rubygems:

    gem update --system

Install bundler:
        
    gem install bundler
    
#### Start local server        
        
    bundle exec jekyll serve


### Maintenance


    bundle update


##

Google AdWords is linked with Google Analytics

PayPal is configured to provide transaction information (Paypal PDT)

A script on the Order Confirmation (thank-you.html) page sends ecommerce data back to Google Analytics which
also feeds AdWords in order to get best ROI for ad spend

http://tools.seobook.com/keyword-list/generator.php
