---
layout: post
title: Long live the web
date: 2013-07-07
---

Web browsers are a dated technology.

Today, most of the time we spend on a desktop computer is spent in a web
browser. It’s not even unreasonable to spend **all** of one’s time in a web
browser, hence the success of chrome os.

The web is great, but web browsers aren’t a great way to experience it.

The modern web is no longer a collection of static documents cross-referenced
with hyperlinks. Today’s web is a collection of interconnected web services. The
web pages that we use to access them are nothing more than web-based clients for
those web-based services.

We still access those clients as we accessed the static documents of yesterday.

---

When I click on an email (mailto) link, it opens in the gmail web client because
I’ve set that web-based interface to be my default email client. When I click on
an http link in some other application, say a twitter client, it opens in my
default web browser.

When I click on a link to a blog post, it opens in whatever client the person
who posted the link was using. Maybe they were reading it on the blog’s native
client (what we usually think of as the blog itself), but I want to view it in
my favorite RSS reader. My browser should show me the content the way _I_ want
to see it.

Hyperlinks were designed to link static pages, but we rarely see static pages
today. Instead we have web clients, which are technically the same thing but
semantically very different. I don’t want a link to a client, I want a link to
the resource itself; something that any client for the protocol can understand.
I want blog://adrusi.com/post/5, not http://adrusi.com/post/5.

Browsers need to know how to handle links for foreign protocols. If I’ve set my
preferred blog client, then when I open a blog URI, it should use my preference.
Maybe if I haven’t set one, it could check whether the server hosting the blog
service also hosts a blog client, and use that.

There is no _browsing_ involved in what such a browser is doing. It’s not a web
_browser_, it’s a web _terminal_.
