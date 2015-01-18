
desc 'deploy latest changes'
task :deploy do
  `bundle exec middleman build && git commit -a -m "Generate latest version" && git subtree push --prefix build origin master`
end