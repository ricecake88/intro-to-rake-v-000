namespace :db do
  task :environment do
    require_relative './config/environment'
  end  
    desc 'migrating database that alters database'
    task :migrate => :environment do
      Student.create_table
     end

  
end

