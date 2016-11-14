## Pjax + React [Back](./../react.md)

As we all known, Pjax was a jQuery plugin before, and now it has been a well known technology to easily enable fast Ajax navigation on any website (using **pushState** and **XMLHttpRequest**). It exactly allows us to build standard websites with complicated user experience, which make users feel like browsing an app.

Under the hood, it actually uses **Ajax** to load resources from server sides, and re-renders them in the same page, by replacing some elements we want without breaking down the whole structure. After that, Pjax will update the browser's current url using **pushState**. With the process of re-rendering, we can easily implement any animation between sites' switching.

For some reasons, I have written this document to talk about how to use **Pjax** combined with **React**. However, as we mentioned above, **Pjax** was originally a jQuery plugin, but what if I don't want to import the library jQuery in React?

Thanks to [MoOx](https://github.com/MoOx), he has provided another projects for us to complete it without using jQuery.