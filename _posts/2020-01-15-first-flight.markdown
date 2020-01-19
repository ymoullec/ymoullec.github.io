---
layout: post
title:  "First flight!"
date:   2020-01-15 23:57:41 +0100
categories: assignment
---

This post deals with the first assignment called First Flight for which we were asked to create a few accounts, install software, and more broadly get accustomed to a few HFOSS tools.

The first thing was to connect to an IRC channel, which gives you the opportunity to chat with the other people that joined the same channel. This is a useful tool for communicating informally with other developers. This tool can can used via command line, web client or desktop client. In class, I'll use the [freenode web client][freenode-webclient] and I've chosen to install [HexChat][hexchat] on my laptop. Just like on this blog, my IRC nickname is *ymoullec*.

The second thing to do was to subscribe to a RIT mailing list, and to introduce yourself to the other subscribers. This list will be dedicated to more formal ways of communicating between people participating to HFOSS.

Then comes the HFOSS journal. This journal is an informal way to put my thoughts on paper (or almost paper), thoughts which are shared with the instructor, but which aren't not available to the public. It requires a daily entry and provides the content used to fill these blog posts. From a technical point of view, this journal is a simple git repository containing a README.md file which itself contains all entries in descending chronological order.

Then onto what you're currently reading : a blog. This is more of a challenge as it's not something I've already done in the past. To create my blog, I first tried to use [WordPress][wordpress]. I created an account and started customizing my blog's look. But my I got to choosing a domain name, it seemed that none of the options available was free of charge. Thus, I deleted my account and went for the [GitHub Pages][github-pages] option. A GitHub page consists in turning a GitHub repository into a website. Also, [Jekyll][jelyll] offers a very simple way to turn markdown files into a blog using GitHub Pages. It still might still need some customizing but this blog is now online and ready to be used.

Finally, it was time to share this blog with the class using GitHub. That meant cloning the class's repository, adding a YAML file that references tis blog, pushing it to GitHub and issuing a pull request. As I'm not yet super familiar with the *pull request* mechanism, I first looked at some tutorials on how exactly all this is supposed to be done.

And that's it for the first flight.

[freenode-webclient]: https://webchat.freenode.net/
[hexchat]: https://hexchat.github.io/
[wordpress]: WordPress.com
[github-pages]: https://pages.github.com/
[jekyll]: https://jekyllrb.com/

<!--
rebuild the site : run `jekyll serve` or `bundle exec jekyll serve`

posts file formats : `YEAR-MONTH-DAY-title.MARKUP`
- `YEAR` is a four-digit number, 
- `MONTH` and `DAY` are both two-digit numbers,
- `MARKUP` is the file extension representing the format used in the file

Code snippets:
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

[Jekyll docs][jekyll-docs] for more info
[Jekyll’s GitHub repo][jekyll-gh] file all bugs/feature requests
[Jekyll Talk][jekyll-talk] for questions

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
-->