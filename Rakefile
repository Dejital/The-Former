task :default => :sass

desc "Convert the primary stylesheet from Sass CSS format to standard CSS."
task :sass do
  `sass --scss --no-cache --style compressed src/css/main.scss public/css/main.css`
  `haml src/index.haml public/index.html`
end
