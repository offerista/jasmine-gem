source 'https://rubygems.org'

gemspec

gem 'anchorman', :platform => :mri

gem 'jasmine-core', :git => 'http://github.com/jasmine/jasmine.git', :tag => 'v1.3.1'

if ENV['RAILS_VERSION'] == "rails4"
  gem 'rack', '~> 1.6.0'
elsif ENV['RAILS_VERSION'] == "pojs"
  gem 'rack', '< 2.0'
else
  gem 'rack', '>= 2.0'
end

gem 'mime-types', '< 3.0', platform: [:jruby]

platform :rbx do
  gem 'json'
  gem 'rubysl'
  gem 'racc'
end
