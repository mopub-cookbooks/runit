source 'https://rubygems.org'

group :test do
  gem 'chef'
  gem 'rake'
  gem 'rspec'
  gem 'foodcritic'
  gem 'vagrant-wrapper'
end

group :integration do
  gem 'test-kitchen', :git => "git://github.com/opscode/test-kitchen.git"
  gem 'berkshelf'
  gem 'rake'
  gem 'kitchen-vagrant', :git => "git://github.com/opscode/kitchen-vagrant.git"
  gem 'kitchen-ec2', :git => "git://github.com/opscode/kitchen-ec2.git"
  gem 'kitchen-lxc', :git => "https://github.com/portertech/kitchen-lxc.git", :tag => 'v0.0.1.beta2'
end
