namespace :sass do
  desc "Will Build Sass/SCSS files"
  task :build do
    puts "Building grid.scss into grid.css"
    `bundle exec sass --style expanded --no-cache grid.scss:grid.css`
  end

  desc "Will Build Sass/SCSS files on change"
  task :watch do
    puts "Watching grid.scss changes"
    `bundle exec sass --style expanded --no-cache --watch grid.scss:grid.css`
  end
end