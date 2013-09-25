---
layout: default
title: Your New Jekyll Site
---

# All your front–end dependencies via one script tag. Minified, concatenated and cached.</h1>

```html
<script src="//js.pldn.io/html5shiv/jquery@1.9.1/underscore"></script>
```

**js.pldn.io** is [pulldown](https://github.com/jackfranklin/pulldown) for the client side. That means you get:

1. All your front–end dependencies in in one script tag.
2. They're minified, concatenated and cached (we Do The Right Thing™ so you don't have to worry)
3. New libraries at your finger-tips (you just need to know the name)

Sweet, huh?

## Usage

It's mind-blowingly simple. Just add a `script` tag to your page, pointing to `js.pldn.io`:

```html
<script src="//js.pldn.io/"></script>
```

Then add library names. We get these for you from [CDNjs](http://cdnjs.com/).

```html
<script src="//js.pldn.io/jquery/underscore/backbone"></script>
```

You can even specify a specific version!


```html
<script src="//js.pldn.io/jquery@1.9.1"></script>
```

### Who should use this?

People who's sites have a small set of dependencies, and who don't have the resources or specialist knowledge, or time, to do the right thing with concatenation, minification, caching and delivery.

  <!-- <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul> -->
