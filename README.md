![build-master](https://travis-ci.org/mikaturunen/poly-blog.svg?branch=master)

# Proof-of-concept of a Polymer based Github pages compatible blog

I started toying around with an idea of building an completely Github pages compatible Polymer based blog and here it is. Essentially you are just serving the static content (Polymer components and application itself) from Github pages and the dynamic content, which is the blog posts are coming in from Firebase.

## Travis CI

Once a PR / commit is merged into `/master` the Travis CI will take over and handle the github pages bundling and publishing. The process if fairly simple. Thought it does involve some highly experimental Travis CI magic that works wonders.

### Builds

* Master: ![build-master](https://travis-ci.org/mikaturunen/poly-blog.svg?branch=master)
* Overall build process: https://travis-ci.org/mikaturunen/poly-blog

# FAQ

## Can I use this as a blog?

Short: No.

Longer: Yes and no. It's a proof of concept of how one can essentially abuse GitHub's ability to serve static content and host the actual blog posts in a separate location, such as Firebase that is extremely easy to use from frontend.
