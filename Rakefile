require "bundler/gem_tasks"
require "rake/testtask"

Rake::TestTask.new do |t|
  # To run test for only one file (or file path pattern)
  #  $ bundle exec rake test TEST=test/test_specified_path.rb
  t.description = 'Run yao-oj\'s test suite'
  t.libs.concat ["test"]
  t.test_files = Dir["test/**/test_*.rb"]
  t.verbose = true
  t.ruby_opts = ["-r config"]
end
