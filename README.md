# [HugoStrap]

Hugo theme with Bootstrap 4 boilerplate with Gulp.js, browsersync and multiple-language support.

Combine the power of [Hugo](http://hugo.spf13.com/), [bootstrap](http://getbootstrap.com/) and [gulp.js](http://gulpjs.com/),
it becomes incredibly easy & fast to generate a static site of your own.

Write posts in Markdown, polish UI in stylus/less/sass/coffee,
build the entire site in seconds.

## Usage

1. [Install hugo](http://hugo.spf13.com/overview/installing) //
   Long story short: `brew install hugo`
2. Create a site: `hugo new site /path/to/site`
3. `cd /path/to/site`
4. `git clone https://github.com/alkymst/hugostrap.git themes/hugostrap`
5. `hugo server -ws -t=hugostrap .`

### Grunt

1. `cd hugostrap && make init`
2. `cd hugostrap && make watch`

### Start building

1. `hugo new post/first-article.md`
2. `hugo server -ws -t=hugostrap .`


## License

MIT
