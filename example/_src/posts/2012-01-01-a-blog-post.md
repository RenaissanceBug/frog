    Title: A blog post
    Date: 2012-01-01T00:00:00
    Tags: foo, bar, tag with spaces, baz

Here is an example blog post.

Everything after this is "after the break". On index pages and Atom
feeds, it will become "Continue reading...".

<!-- more -->

Here's some [Bullshit Ipsum](http://bullshitipsum.com/?paragraphs=2).

Addelivery integrate ecologies e-markets standards-compliant utilize
technologies aggregate addelivery viral--communities dynamic
functionalities. Mindshare engineer viral A-list: cross-platform remix
engage social cross-media social innovate distributed matrix
experiences monetize utilize innovative. Action-items transition
recontextualize sexy Cluetrain envisioneer, "vortals communities
evolve technologies sexy methodologies." Enhance grow compelling
iterate architect matrix plug-and-play reinvent scale, distributed
incentivize, extend.

Revolutionary proactive. Target; envisioneer e-services sticky robust
morph users methodologies, markets content supply-chains, granular
monetize reinvent harness initiatives. Plug-and-play productize
vortals integrate compelling aggregate, user-contributed, integrate
web-enabled grow extend mindshare, repurpose world-class harness
next-generation eyeballs solutions blogospheres extend. Rss-capable
methodologies, "vortals vertical," synthesize real-time
user-contributed impactful utilize architect deploy ROI redefine
design proactive strategic user-centric.

## Code blocks

Frog optionally uses [Pygments](http://pygments.org/) if it's
installed to do syntax highlighting. In your markdown using backtick
code blocks you can specify a language:

    ```language
    some racket code
    ```

That name is given to Pygments as the lexer to use.

For example this:

    ```js
    /**
     * Some JavaScript
     */
    function foo()
    {
        if (counter <= 10)
            return;
        // it works!
    ```

Yields this:

```js
/**
 * Some JavaScript
 */
function foo()
{
    if (counter <= 10)
        return;
    // it works!
```

And this:

    ```racket
    #lang racket
    ;; Finds Racket sources in all subdirs
    (for ([path (in-directory)])
      (when (regexp-match? #rx"[.]rkt$" path)
        (printf "source file: ~a\n" path)))
    ```

Yields this:

```racket
#lang racket
;; Finds Racket sources in all subdirs
(for ([path (in-directory)])
  (when (regexp-match? #rx"[.]rkt$" path)
    (printf "source file: ~a\n" path)))
```

The end.