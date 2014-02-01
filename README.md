[![Build Status](http://img.shields.io/travis/pikesley/badger.svg)](https://travis-ci.org/pikesley/badger)
[![Dependency Status](http://img.shields.io/gemnasium/pikesley/badger.svg)](https://gemnasium.com/pikesley/badger)
[![Coverage Status](http://img.shields.io/coveralls/pikesley/badger.svg)](https://coveralls.io/r/pikesley/badger)
[![Code Climate](http://img.shields.io/codeclimate/github/pikesley/badger.svg)](https://codeclimate.com/github/pikesley/badger)
[![Gem Version](http://img.shields.io/gem/v/badgerbadgerbadger.svg)](https://rubygems.org/gems/badgerbadgerbadger)
[![License](http://img.shields.io/:license-mit-blue.svg)](http://pikesley.mit-license.org)
[![Badges](http://img.shields.io/:badges-7/7-ff6799.svg)](http://img.shields.io)

#Badger

Because I grow weary of copy-n-pasting the badge URLs into the README of every project, and the [img.shields.io](http://img.shields.io) API now supports all of the services I use 

##Usage

Install it

    gem install badgerbadgerbadger

or add it to your Gemfile

    gem 'badgerbadgerbadger'
    bundle
    
Then
 
    badger badge
    [![Build Status](http://img.shields.io/travis/doge/wow.svg)](https://travis-ci.org/doge/wow)
    [![Dependency Status](http://img.shields.io/gemnasium/doge/wow.svg)](https://gemnasium.com/doge/wow)
    [![Coverage Status](http://img.shields.io/coveralls/doge/wow.svg)](https://coveralls.io/r/doge/wow)
    [![Code Climate](http://img.shields.io/codeclimate/github/doge/wow.svg)](https://codeclimate.com/github/doge/wow)
    [![Gem Version](http://img.shields.io/gem/v/suchgem.svg)](https://rubygems.org/gems/suchgem)
    [![License](http://img.shields.io/:license-mit-blue.svg)](http://doge.mit-license.org)
    [![Badges](http://img.shields.io/:badges-7/7-ff6799.svg)](http://img.shields.io) 

ready to paste into the top of your README (with the correct URLs for your repo)

Try

    badger help badge

to read about Badger's Opinions 

If you're on a Mac, pipe the output into `pbcopy` to add the stuff directly to your clipboard:

    badger badge | pbcopy

##Help me make it better

    git clone https://github.com/pikesley/badger
    cd badger
    bundle
    rake