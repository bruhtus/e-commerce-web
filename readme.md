## Build Simple E-commerce Site with Hugo, Snipcart, and Forestry.io

Inpired by this [article](https://snipcart.com/blog/hugo-tutorial-static-site-ecommerce#comment-5331722223) to build a simple e-commerce site using hugo, snipcart, and forestry.io.

Here's the breakdown of each component that used in this project:
- Hugo: to generate static website.
- Snipcart: to handle order from customer.
- Forestry.io: to input entry for e-commerce site.
- Netlify: to deploy e-commerce site.

> There's still a problem with snipcart while processing the final checkout, the message is along this line "there's a change in the price while you place the order" or something like that. Other than that, it works.

Fix that by adding `default website domain` in [snipcart dashboard](https://app.snipcart.com/dashboard/account/domains).

### References

- [Original article](https://snipcart.com/blog/hugo-tutorial-static-site-ecommerce#comment-5331722223)
- [Setup google analytics](http://cloudywithachanceofdevops.com/posts/2018/05/17/setting-up-google-analytics-on-hugo/)
