task :server do
  sh "open 'http://127.0.0.1:4000/blog/' && bundle exec jekyll serve --host 0.0.0.0 -c config/jekyll_config.yml --watch --drafts"
end

task :publish do
  ARGV.shift

  sh "bundle exec jekyll publish -c config/jekyll_config.yml #{ARGV.first}"
end