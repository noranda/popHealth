# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)
require 'rake'
require 'rspec/core/rake_task'

PopHealth::Application.load_tasks

ENV['DB_NAME'] = "pophealth-#{Rails.env}"

