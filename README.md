#MiddlemanStarter

My starting Middleman blog configuration based on a [Thoughtbot article](http://robots.thoughtbot.com/middleman-bourbon-walkthrough) as well as some of my own preferences. An ever-changing work in progress.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/andrewjkerr/middleman_starter)

##Current Defaults

- Ruby 2.2.0
- Middleman 3.3.8
- Slim for templates
- Sass for stylesheets
- Coffeescript for javascript-y type things
- Bourbon, Bitters, and Neat for styling
- GitHub Pages for deployment

##Dependencies

- Ruby

##Configuration

1. Clone this repo:

```
git clone https://github.com/andrewjkerr/middleman_starter.git
```

2. Change the values in `config.rb` as you wish.

3. Run `bundle install`.

4. Run `middleman`!

##Deployment

1. If you cloned this repo, remove the current remote origin:

```
git remote rm origin
```

2. Add in your own repository:

```
git remote add origin https://github.com/user/repo.git
```

3. `middleman build`

4. `middleman deploy`
