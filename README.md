# Simba
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FSaitoWu%2Fsimba.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FSaitoWu%2Fsimba?ref=badge_shield)


Simba is a generator for Sinatra applications.

Simba chooses slim + sinatra + activerecord to build your awesome apps.

Simba's aim is to help you to use best practices when not using ruby on rails.

## Installation

    $ gem install simba

## Usage

    $ simba new appname

    $ # development
    $ bundle exec rackup

    $ # production
    $ rake asset:precompile
    $ bundle exec rackup -E production

## More

Simba uses [Linner](https://github.com/SaitoWu/linner) as its asset packaging system,
You can star it on the github page.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am "Added some feature"`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FSaitoWu%2Fsimba.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FSaitoWu%2Fsimba?ref=badge_large)