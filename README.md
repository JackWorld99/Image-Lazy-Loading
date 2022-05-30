## Image Lazy Loading 🖼️

> _Lazy loading is a strategy to identify resources as non-blocking (non-critical) and load these only when needed. It's a way to shorten the length of the critical rendering path, which translates into reduced page load times. Lazy loading can occur on different moments in the application, but it typically happens on some user interactions such as scrolling and navigation._

---

### Intersection 🔭 Observer 👀

> _In today’s world, a significant amount of transferred bytes can be accounted for images. This means that wecan gain the most on performance by optimizing them. Yet, most of the time these resources are kept hidden and not even seen by visitors. Offscreen images are requested, but before they are scrolled into view, users bounce off. This is where lazy loading can help us. It defers the loading of offscreen images that are only requested once they are in the viewport. This way, we can save precious bytes, reduce page load times, and potentially save money for the visitor if they have a limited data plan. For this, we will use the Intersection Observer API, which provides a way for us to detect if our target element is intersecting with either other elements or the viewport._

---

### 👉 [Demo](https://jackworld99.github.io/ImageLazyLoading/index.html "Show index.html")
