source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.1'
gem 'sqlite3'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jquery-ui-rails', '~> 4.2.1'

gem 'jbuilder', '~> 2.5'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.6'
gem 'font-awesome-sass'
gem 'devise', '~> 4.2'
gem 'activeadmin', '~> 1.0.0.pre4'
gem 'inherited_resources', git: 'https://github.com/activeadmin/inherited_resources'
gem 'active_skin'
gem 'paperclip', '~> 4.3', '>= 4.3.6'

group :development, :test do

  gem 'byebug', platform: :mri
end

group :development do

  gem 'web-console', '>= 3.3.0'
end


gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
