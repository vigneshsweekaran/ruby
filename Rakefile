# show available tasks as default
#
task :default do
  system 'bundle exec rake -T'
end

# Include all .rake files from rake folder
Dir.glob('rake/*.rake').each { |r| import r }
