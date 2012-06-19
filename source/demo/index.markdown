---
layout: page
title: "Demo"
date: 2012-06-19 20:42
comments: true
sharing: true
footer: true
---
1. Begin with a quick explanation of [Jekyll][] and [Octopress][]
2. Discuss the specific configuration, fire up local to demonstrate
    * Initial setup involves installing ruby and a few gems
    * `git checkout demo-1-config`
3. Deployment to [Heroku][]
    * `git checkout demo-2-heroku`
    * [Deploying Octopress to Heroku With a Custom Buildpack](http://jasongarber.com/blog/2012/01/10/deploying-octopress-to-heroku-with-a-custom-buildpack/)
    * `$ heroku create --stack cedar --buildpack git://github.com/jeffora/heroku-buildpack-ruby-octopress.git jeffburndemo`
    * `$ git remote`
    * `$ git checkout -B master`
    * `$ git push heroku master`
4. Creating content (MOD story)
    * `git checkout demo-3-mod`
    * Branch and create new page / new post
    * push to heroku
5. Switch to bootstrap layout
    * `git checkout demo-4-bootstrap`
    * Demonstrate ZenCoding in Sublime Text 2 

[Jekyll]: https://github.com/mojombo/jekyll
[Octopress]: http://octopress.org/
[Heroku]: http://www.heroku.com/