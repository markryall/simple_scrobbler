require "rake/testtask"
require 'bundler/gem_tasks'

task :default => :test

Rake::TestTask.new do |t|
  t.test_files = FileList["test/*_test.rb"]
  t.verbose = true
end
