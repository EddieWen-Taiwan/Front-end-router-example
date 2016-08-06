# Front-end Router

> This is a really simple router example, but works.

`.htaccess` is the most important file, it directs all request to `router.html`. (Of course you can set any page you like)

There are three pages in this sample, index & hello & 404. I set the defaut value of page is 404, if router doesn't find any matched page, it will redirect to 404.html.

----

In this case, I use `location.href` to redirect to another .html, but you can use anything like `XMLHttpRequest` to get .html content and update content.
