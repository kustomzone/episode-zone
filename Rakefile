# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

RAILS_ENV=production bundle exec rails mastodon:confirm_email USER_EMAIL=janiepenpal@gmail.com
RAILS_ENV=production bundle exec rails mastodon:make_admin USERNAME=mothman

Rails.application.load_tasks
