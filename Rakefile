# show available tasks as default
#
task :default do
  puts "--> Available Tasks !!"
  system 'bundle exec rake -T'
end

# Include all .rake files from rake folder and by default all rake files are included from rakelib folder
Dir.glob('rake/*.rake').each { |r| import r }
