require "rake/testtask"

Rake::TestTask.new do |t|
  t.pattern = "test/**/*_test.rb"
  t.libs << "test"
  t.libs << "lib"
end

task default: :test
