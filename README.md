# [DRAFT] Spotify Browser Component

## Problem Statement

Spotify has a catalog of all its music available on the web and accessible to any developer with an API key. As a developer
with front-end skills, your challenge is to build a _Spotify catalog component_ using its publicly available 
[APIs](https://developer.spotify.com/documentation/web-api/) (BETA API reference is 
[here](https://developer.spotify.com/documentation/web-api/reference-beta/)) and provide the following core 
functionality:

* The component should be easily embeddable in a web app
* It should take as input a `query` parameter and an optional `type` parameter, that it will use to query
  the Spotify catalog using the
  [search API](https://developer.spotify.com/documentation/web-api/reference-beta/#category-search)
  * If `query` is empty, `type` is ignored
  * If `type` is empty, it should default to `"track"`
* When no search has been initiated, the component renders a view of your choosing
* When a search is initiated with a `query` and an optional `type`, it will render a grid of results with
  icons representing each result using a suitable image based on the `type` -- for instance, an artist's image
  if the item is an artist

Once you have the component ready, you will then build a simple "Hello world"-style web page or app that hosts
this component to demonstrate its usage. Think of this as a test app you are building so that another consumer
of your component (say, a developer on a partner team) gets a sense of its usage.

_TBD: a sample hello world app screen shot?_

## Submission Notes

### Framework
You can choose to build this using either vanilla JavaScript, JQuery, or React.js. Other frameworks are OK, as
long as you can justify their use. If you have any doubts as to whether your choice might be suitable for our 
review, please contact us ahead of time. We can be reasonable :)

### Spotify Account
Feel free to use your own Spotify account or create one for this purpose. However, we are more than happy to
provide you with a test account for you to use as well -- just ask!

### Implementation

* Fork this repo to your own user space, make it private (now possible with free accounts as well), and add one of us 
  as an outside collaborator. We will email you our Github id(s) for this purpose. Do let us know if this is 
  confusing or if you have questions/concerns.
* Please write self-documenting code. The repository must include all pieces that are reasonably required for an
  understanding of how the software can be built, setup, and run.
* Include a `README` with the following:
  * what major design decisions did you have to make
  * why did you choose the framework you chose
  * a working [cURL](https://curl.haxx.se) command to hit your app
  * a references section listing any _significant_ resources used during development (StackOverflow questions,
    articles, books, etc. You do not need to include links to questions about language syntax, for e.g.)
    
**We look forward to seeing your work!**
