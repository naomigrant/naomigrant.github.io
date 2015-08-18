desc 'deploy latest changes'
task :deploy, [:commit_message] do |t, args|
   commit_message = args[:commit_message] || 'Generate latest version'
  `bundle exec middleman build && git commit -m "#{commit_message}" && git subtree push --prefix build origin master`
end
