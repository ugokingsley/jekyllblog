---
layout: post
title:  "Welcome to Jekyll on Now!"
date:   2019-03-26 03:28:01 +0000
categories: jekyll now deployment example
---

Welcome to this deployment example of Jekyll, built and deployed in the cloud with [ZEIT Now](https://zeit.co/now)!

To find the source code of this deployment and many more deployed application examples, see our [Now Examples repository](https://github.com/zeit/now-examples).

## Usage
You’ll find this post in the `_posts` directory. Go ahead and edit it then re-build the site to see your changes. You can rebuild the site in many different ways, the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

## Deployment
First, download [Now](https://zeit.co/docs/v2/getting-started/installation), then run the following in your terminal:

```shell
now init jekyll
```

When the command is complete, you will have a new directory named `jekyll` in the [current working directory](https://en.wikipedia.org/wiki/Working_directory). Move into that directory using `cd jekyll` in your terminal, then deploy your new jekyll application using the following:

```shell
now
```

Once deployed, you will see a deployment URL, like the one you are currently accessing this site from.

## Resources
For more information on ZEIT Now, see the following resources:
- [Introduction to Now](https://zeit.co/docs)
- [Deployment Basics](https://zeit.co/docs/v2/deployments/basics)

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
