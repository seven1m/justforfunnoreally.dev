task :deploy do
  sh "rsync -avz --exclude='.git' --delete ./ deploy@justforfunnoreally.dev:/var/www/statics/justforfunnoreally.dev/"
end
