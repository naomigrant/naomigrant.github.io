
desc 'deploy latest changes'
task :deploy do |commit_message|
  `bundle exec middleman build && git commit -a -m #{commit_message} && git subtree push --prefix build origin master`
end