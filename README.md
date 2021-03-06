# alchemy-news-api

**BETA**

This is a Ruby SDK for the IBM Alchemy News API.  It is fairly simple at the moment, as it is just in its infancy.

## Supported Ruby Versions
This library aims to support and is tested against the following Ruby implementations:

* Ruby 2.x

## Installation

### Ruby
```    
		gem  install 'alchemy-news-sdk'
```


### Rails
```    
		gem 'alchemy-news-sdk'
```


## Use
```
api = AlchemyNews::Client.new(key)
    search = api.search("Trudeau")
    search.each do |news_item|
      puts news_item.title
    end
```
## To Do

* Better error handling
* More options for search

## Bugs

* Please post bugs here (in the issues area of github)
* Or Fix them and send me a pull request.  


## Contributing to alchemy-news-api
 
* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

### Copyright

Copyright (c) 2015 Propellerhead Interactive. See LICENSE.txt for
further details.

