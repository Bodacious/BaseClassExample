# frozen_string_literal: true

require 'bundler'
Bundler.setup

require 'rake/testtask'

Rake::TestTask.new(:test) do |t|
  t.libs << 'test'
  t.libs << 'stripe'
  t.test_files = FileList['test/**/*_test.rb']
end

task default: %i[test]
