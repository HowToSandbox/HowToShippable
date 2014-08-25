require 'rake/testtask'

task :default => [:HelloWorld]

    Rake::TestTask.new do |t|
      t.libs = ["support"]
      t.name = :HelloWorld
      t.warning = false
      t.verbose = false
      puts "Hello World"
    end

namespace :spec do

    Rake::TestTask.new do |t|
      t.libs = ["support"]
      t.name = :sandbox
      t.warning = false
      t.verbose = false
      t.test_files = FileList['spec/sandbox/*_spec.rb']
    end



end
