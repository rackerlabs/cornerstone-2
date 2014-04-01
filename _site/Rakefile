desc "Install dependencies"
task :install do
  sh 'bundle install'
end

namespace :sass do
  desc "Build Sass file"
  task :build do
    sh 'bundle exec sass ./sass/cornerstone.scss ./site/css/cornerstone.css'
  end
  
  desc "Watch Sass changes"
  task :watch do
    sh 'bundle exec sass --watch ./sass/cornerstone.scss:./site/css/cornerstone.css'
  end
end

namespace :site do
  desc "Serve Jekyll site"
  task :serve do
    sh 'bundle exec jekyll serve --watch --source ./site --destination ./site/_site --baseurl ""'
  end
  
  desc "Deploy Jekyll site to gh-pages branch"
  task :deploy do
    sh "git subtree push --prefix site origin gh-pages"
  end
end
