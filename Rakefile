require 'rake'
require 'rake/testtask'
task :default => :test

desc "Run tests"
Rake::TestTask.new(:test) do |t|
  t.test_files = FileList['*_test.rb']
  t.verbose = true
end
