---
layout: post
title:  "Wie Hab ichs gemacht"
date:   2023-02-14 23:04:57 +0100
categories: github page
---


* [Following the instructions from github](https://docs.github.com/de/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll)
* [Add the Jekyll workflow Github](https://github.com/GfSE/SAF-Test-Pages/actions/new)
* clone the repo
* [Download Ruby](https://rubyinstaller.org/downloads/)
* [Install Jekyll](https://jekyllrb.com/docs/installation/windows/)

*From the a vscode terminal*
{% highlight sh %}
gem install jekyll bundler
jekyll -v
{% endhighlight %}

*make new jekyll site*
{% highlight sh %}
mkdir docs
cd docs 
jekyll new --skip-bundle .
{% endhighlight %}

*site lokal testen*
{% highlight sh %}
bundle exec jekyll serve
{% endhighlight %}
