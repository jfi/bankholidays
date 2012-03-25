# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  gem.name = "bankholidays"
  gem.homepage = "http://github.com/jfi/bankholidays"
  gem.license = "MIT"
  gem.summary = %Q{Get UK bank holidays from www.gov.uk}
  gem.description = %Q{Library to parse UK bank holidays from https://www.gov.uk/bank-holidays/}
  gem.email = "james@jamesinman.co.uk"
  gem.authors = ["James Inman"]
  gem.files = ["lib/bankholidays.rb", "README.*", "LICENSE.*"]
end

Jeweler::RubygemsDotOrgTasks.new