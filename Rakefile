#desc 'outputs hello to the terminal'
#task :hello do
#  puts "hello from Rake!"
#end

namespace :db do
  desc 'require files to migrate'
  task:environment do 
    require_relative './config/enviornment'
  desc 'migrate changes to your database'
  task :migrate => :environment do
    Student.create_table
  desc 'seed the database with some dummy data'
  task :seed do
    require_relative './db/seeds.rb'
  end
end
