require_relative './config/environment'
require 'sinatra/activerecord/rake'
require_relative './artist.rb'

task :console do
  require 'irb'
  ARGV.clear
  IRB.start
end

task :create_database do
  Artist.create_table(:artists)
end
