require "bundler/gem_tasks"
require "rake/testtask"

Rake::TestTask.new do |t|
  t.test_files = FileList['test/**/*_test.rb']
  t.libs << 'test'
end

task :default => :test
