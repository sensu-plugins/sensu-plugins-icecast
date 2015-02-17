## Sensu-Plugins-icecast

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-icecast.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-icecast)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-icecast.svg)](http://badge.fury.io/rb/sensu-plugins-icecast)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-icecast/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-icecast)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-icecast/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-icecast)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-icecast.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-icecast)

## Functionality

## Files
 * bin/check-icecast2-alive
 * bin/metrics-icecast2

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-icecast -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-icecast`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-icecast' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-icecast' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
