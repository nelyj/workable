require 'rspec/core/rake_task'
require 'bundler/gem_tasks'

RSpec::Core::RakeTask.new('spec')
task default: :spec

task :console do
  sh 'irb -r ./lib/workable.rb'
end

task c: :console
