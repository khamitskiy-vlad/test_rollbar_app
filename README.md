# README

Copy rollbar.rb from config/initializers to config/ to raise the initialize error in app.rollbar.com

```zsh
vladislav@vladislavs-mbp test_rollbar_app % bin/rails s
=> Booting Puma
=> Rails 7.1.3.3 application starting in development 
=> Run `bin/rails server --help` for more startup options
Exiting
/Users/vladislav/.rvm/gems/ruby-3.3.1/gems/railties-7.1.3.3/lib/rails/application.rb:425:in `initialize!': Application has been already initialized. (RuntimeError)
```
