

  
namespace :db do
    desc 'migrating database that alters database'
    task :migrate => :environment do
      Student.create_table
  end
  task :environment do
    require_relative
    './config/environment.'
  end
end

