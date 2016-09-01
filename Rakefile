desc 'regenerate static HTML, JS, other files'
task :build do |t|
  `bundle exec middleman build`
end

desc 'deploy latest changes'
task :deploy do |t|
  `git subtree push --prefix build origin master`
end
