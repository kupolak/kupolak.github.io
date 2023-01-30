---
layout: post
title:  "Sentiment analysis in Elixir - afinn has been released"
date:   2023-01-30 18:15:00 +0100
categories: jekyll update
---
Last week, I released the first version of [afinn][afinn-url] library for Elixir.
It's a very simple library for sentiment analysis.

Just add it to `mix.exs`:

{% highlight elixir %}
def deps do
[
  {:afinn, "~> 0.1.0"}
]
end
{% endhighlight %}

And then we can use it like this:

{% highlight elixir %}
text = 'I love this!'

Afinn.score(text)
#=> 3

Afinn.score_to_words(text)
#=> :positive

{% endhighlight %}



Some ideas for further development:
* Improve documentation
* Add more languages
* Add emoticons/emoji support
* Add support for multi-word expressions ("bad luck", "no fun" etc.)


[afinn-url]: https://github.com/kupolak/afinn