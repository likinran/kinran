source 'https://rubygems.org'

# base
gem 'rails',        '5.1.6'

# database
gem 'mysql2'

# server
gem 'puma',         '3.9.1'

# view
gem 'sass-rails',   '5.0.6'
gem 'bootstrap-sass', '3.3.7'
gem 'uglifier',     '3.2.0'
gem 'coffee-rails', '4.2.2'
gem 'jquery-rails', '4.3.1'
gem 'turbolinks',   '5.0.1'
gem 'jbuilder',     '2.7.0'

# login
gem 'bcrypt',         '3.1.12'

group :development, :test do
  gem 'byebug',  '9.0.6', platform: :mri
  gem 'faker',          '1.7.3' #実際にいそうなユーザー名を作成するgem
end

group :development do
  gem 'web-console',           '3.5.1'
  gem 'listen',                '3.1.5'
  gem 'spring',                '2.0.2'
  gem 'spring-watcher-listen', '2.0.1'
end

group :test do
  gem 'rails-controller-testing', '1.0.2'
  gem 'minitest',                 '5.10.3'
  gem 'minitest-reporters',       '1.1.14'
  gem 'guard',                    '2.13.0'
  gem 'guard-minitest',           '2.4.4'
end

# Windows環境ではtzinfo-dataというgemを含める必要があります
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
