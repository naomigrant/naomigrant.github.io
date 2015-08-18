
desc 'deploy latest changes (accepts "commit message")'
task :deploy do |commit_message|
  `bundle exec middleman build && git commit -a -m "Generate latest version" && git subtree push --prefix build origin master`
end
