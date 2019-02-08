# Jorge Aranda's Personal Website

This is the repository for Jorge Aranda's website and blog.

It is built with [Jekyll](http://jekyllrb.com), using [Lanyon](http://lanyon.getpoole.com/) as its theme.


## Requirements

```
bundle install
```

One of the gems, `s3_website`, will also require having a JDK installed, version 8 or *lower*.


## To build and serve:

```
jekyll serve
```


## To push to S3:

```
s3_website push
```

(But `s3_website.yml` needs to be configured with the right secret `s3` credentials.)
