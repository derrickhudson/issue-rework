# issue-rework
Love the [*Issue* Tumblr theme](https://www.tumblr.com/theme/38861)!

It uses up more screen real-estate than most grid layout themes and has great customization options built-in. Really great for minimalist image grid blogs. 

However, I found a couple of areas that could be improved upon:

- The theme limits image post `height` to `600px` with a set `400px width`. This squishes any images that turn out taller than `600px` when their `width` is set to `400px`. It would be better to support images with `height: auto` up to any size (not limit it to `600px`).
- In my opinion, infinite-scrolling is a big plus for image blogs. The drawback is that if the user reloads the page, they will lose their place. It would be better if the infinite-scrolling tracked the page number so that the user could keep their place.
