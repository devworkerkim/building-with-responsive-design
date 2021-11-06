# Building With Responsive Design

This is the repo for the Building With Responsive Design project in the HTML And CSS course of The Odin Project.  The project is the recreate The Next Web webpage and include a responsrive design such that the page's look changes as the size of the window changes.

## What I Learned

### Mobile First

I thought I would give mobile first design a try since I usually start my responsive design with desktop first.  The video [Are you writing responsive CSS the wrong way?](https://www.youtube.com/watch?v=0ohtVzCSHqs) from the lesson brought up some good points about doing mobile first instead of desktop first.  I thought I would give it a try and see how the CSS turned out.

### `::before` And `::after`

There is a numbered list on the page that didn't have the decimal point in the marker.  Trying to mimic the page as close as possible, I went searching for answers on how to remove the decimal point.  Essentially, I was learning how to customize the look of the numbered list.  I found this post on [Remove decimal from ordered <ol> list via CSS?](https://stackoverflow.com/questions/3153019/remove-decimal-from-ordered-ol-list-via-css) and the answer was only a few lines of CSS.  Part of the answer had the `::before` pseudo-element which I had seen before but didn't know what it was.

I found this article on [::before / ::after](https://css-tricks.com/almanac/selectors/a/after-and-before/) that had a really great explanation of these pseudo-elements right from the beginning.  After seeing the example and how the `::before` and `::after` elements were placed, it made complete sense.  This makes for a very clever way of adding visual content, and for good or bad it is not included in the DOM.