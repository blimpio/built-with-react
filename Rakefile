# frozen_string_literal: true

require 'html-proofer'

task :test do
  sh 'bundle exec jekyll build'
  options = { :assume_extension => true }
  HTMLProofer.check_directory('./_gh_pages/', options).run
end