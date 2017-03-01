# Empty Rails 5 app

Generate new app:

```
$ rails new . -T -B -p postgresql
```

Add `rspec-rails` into `Gemfile`

```ruby
group :development, :test do
  gem 'rspec-rails', '~> 3.5'
end
```

And run `bundle install`
