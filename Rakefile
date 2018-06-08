namespace :greeting do
desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

desc 'outputs hola to the terminal'
task :hola do
  puts "hola de Rake!"
end
end


  
namespace :db do
    desc 'migrating database that alters database'
    task :migrate => :environment do
      Student.create_table
  end
  task :environment do
    require_relative
    './config/environment.rb'
  end
end
  task :environment do
    require_relative
    './config/environment.rb'
  end
