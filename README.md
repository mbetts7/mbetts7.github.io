## What is Octopress?

Octopress is [Jekyll](https://github.com/mojombo/jekyll) blogging at its finest.

1. **Octopress sports a clean responsive theme** written in semantic HTML5, focused on readability and friendliness toward mobile devices.
2. **Code blogging is easy and beautiful.** Embed code (with [Solarized](http://ethanschoonover.com/solarized) styling) in your posts from gists, jsFiddle or from your filesystem.
3. **Third party integration is simple** with built-in support for Pinboard, Delicious, GitHub Repositories, Disqus Comments and Google Analytics.
4. **It's easy to use.** A collection of rake tasks simplifies development and makes deploying a cinch.
5. **Ships with great plug-ins** some original and others from the Jekyll community &mdash; tested and improved.

**Note**: Octopress requires a minimum Ruby version of `1.9.3-p0`.

## Command Line:

### Deploying to production
`rake generate   # Generates posts and pages into the public directory`
`rake deploy     # deploys and pushes commit on master branch in github`
### Development:
`rake watch      # Watches source/ and sass/ for changes and regenerates`
`rake preview    # Watches, and mounts a webserver at http://localhost:4000`
### new posts and pages
`rake new_post["title"]`
`rake new_page[super-awesome] # creates /source/super-awesome/index.markdown`
`rake new_page[super-awesome/page.html] # creates /source/super-awesome/page.html`
### Commiting regularly to source branch
`git push origin source`

## Useful guides and sources

* [Best 3rd party resource for setting up Octopress](http://webdesign.tutsplus.com/tutorials/getting-started-with-octopress--webdesign-11442)<br>
* [Definitely going to want to integrate some plugins](http://octopress.org/docs/blogging/plugins/)
* [Octopress.org documentation](http://octopress.org/docs)
* [getting custom domain up and running](http://haikus-in-c.com/posts/github-pages-custom-domain/)
* [custom domain setting up](https://help.github.com/articles/setting-up-a-custom-domain-with-pages)



old points to a name 184.168.221.50