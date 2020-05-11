---
date: 2020-05-11
title: Setup a Custom Domain
description: How to setup a custom domain
categories:
  -custom-domain
type: Document
---

Under the heading “Dashboard” there are three tab options. Click on the tab reading “Domains” to brand your links with a custom domain.

There are two main ways of setting up your custom domain through LinkSplit.  

### A) Dedicated Domain

A dedicated domain is a custom domain that will be used solely for link redirection via LinkSplit. This domain will not host a website. The base domain will be used for link redirection (e.g customdomain.com/mylink). 

The benefit of using a dedicated domain is the ability to have a very short link without the need of a subdomain. If you have purchased a domain with the sole intention of hosting short links, then a dedicated domain is likely for you.

#### To set up a dedicated domain:

 1) Add your domain into LinkSplit via the “Domains” tab (e.g customdomain.com).

 2) In your DNS configuration provided by your domain provider, set a CNAME record pointing @ to cname.linksplit.io

 3) Allow for up to 48 hours for the DNS to propagate. This time will vary case by case.


### B) Subdomain

Subdomain custom domains allow you to continue to use your domain to host your website while allowing a subdomain to handle the redirection of LinkSplit links (e.g links.customdomain.com/mylink)

If you have an existing website on your domain name then using a subdomain is probably right for you. 

#### To set up a subdomain custom domain through LinkSplit.

1) Add your domain, including the subdomain portion, into LinkSplit via the “Domains” tab (e.g links.customdomain.com).  Note: “links” is just an example, you may choose any subdomain you wish.

2) In your DNS configuration provided by your domain provider, set a CNAME entry pointing “links” to cname.linksplit.io.

3) Allow for up to 48 hours for the DNS to propagate. This time will vary case by case.