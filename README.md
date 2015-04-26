== README

Gemfile
  require 'bourbon'
  bundle install

stylesheets/application.css
  rename to application.css.scss
  delete 'require_tree'
  @import 'bourbon';  (must be before all other @imports)

index.html.erb
  <button>"Hello world!"</button>

custom.css.scss
  button  {
    @include button;
  }
