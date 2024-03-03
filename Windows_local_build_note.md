# Note for local-run jekyll for academicpages

## Prerequisite

1. [Github Desktop](https://desktop.github.com/ "Github Desktop"), git clone the project to local drive
2. [Ruby](https://rubyinstaller.org/downloads/ "Ruby Installer") + DevKit install
   1. ```
      ridk install
      ```
   2. MSYS2 and MINGW development tool chain
   3. ```ruby
      gem install jekyll bundler
      ```
   4. ```
      jekyll -v
      ```

      (https://jekyllrb.com/docs/installation/windows/)
   5. ```ruby
      bundle install
      ```

      in site folder
   6. ```ruby
      bundle exec jekyll serve -l -H localhost
      ```
   7. localhost:4000 in browser
3. [Node.js](https://nodejs.org/en/download/)

## Fix for TZinfo error

add in Gemfile:

```ruby
gem 'jekyll-octicons'
```

```ruby
platforms :mingw, :x64_mingw, :mswin, :jruby do  
	gem 'tzinfo', '>= 1', '< 3'  
	gem 'tzinfo-data'
end
```
