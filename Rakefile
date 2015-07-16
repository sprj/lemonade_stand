require "bundler/gem_tasks"

require 'rake/testtask'

task :default do
  	Rake::TestTask.new do |t|
  		t.test_files = FileList['spec/lemonade_stand/*_spec.rb']
	end
end

