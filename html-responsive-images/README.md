# Responsive image with only HTML

In this article, we'll learn about the concept of responsive images — images that work well on devices with widely differing screen sizes, resolutions, and other such features — and look at what tools HTML provides to help implement them. This helps to improve performance across different devices. Responsive images are just one part of  responsive design, a future CSS topic for you to learn.


Check full article [here](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

![responsive image with html](https://raw.githubusercontent.com/shayanypn/roaming-in-technology/master/html-responsive-images/preview.png)

![responsive image with html](https://raw.githubusercontent.com/shayanypn/roaming-in-technology/master/html-responsive-images/preview.gif)


Sample code

    <picture>
        <source media="(max-width: 400px)" srcset="mobile-version.jpg">
        <source media="(max-width: 799px)" srcset="tablet-version.jpg">
        <source media="(min-width: 800px)" srcset="desktop-version.jpg">
        <img
             class="rounded-3xl" src="desktop-version.jpg"
             alt="my html response image"
        />
    </picture>

