#Installation

## Get Growl and Growl Notify

  - Download and install [Growl](http://itunes.apple.com/us/app/growl/id467939042?mt=12&ign-mpt=uo%3D4)
  - [Growl Notify](http://growl.info/downloads#generaldownloads). 

## Setup your Rails gemfile

Configure your dev environment with rspec and autotest. 

````ruby
group :test do
  gem "rspec", "~> 1.3.2"
  gem "rspec-rails", "~> 1.3.4"
  gem "autotest"
  gem "autotest-rails"
end
````

- cd into your Rails build and bundle install

## Configure autotest files

- Put the .autotest file in your home ~/ directory. 
- Stick the Growl Images folder in ~/Documents. 
- Start spork and autotest, receive sweet growl notifications! This has been tested on OSX 10.7.