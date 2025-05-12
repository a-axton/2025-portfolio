---
title: 'Astro: The Unexpected Hero of My Portfolio (Sorry, Next.js)'
description: 'When starting a new project, selecting the right tools to use is an important step. Many times we just reach for the most familiar tools.'
pubDate: 'April 23 2025'
heroImage: '/blog/astro-logo-light-gradient.png'
heroObjectFit: 'contain'
---
As a front-end engineer, I’ve worked with a variety of frameworks over the years (shout out to Backbone.js as my first framework). One of the first decisions when you start a new project is which framework to use. When I'm starting a new project I usually reach for Next.js but I've had my eye on Astro for some time. While both are great frameworks, Astro stands out as the better choice for many projects—especially if you prioritize simplicity, ease of setup, and optimal performance. Let’s dive into why Astro might be the best framework for your next website.

## Simplicity at it's Core

One of Astro’s biggest advantages over Next.js is its simplicity. With Next.js, developers have to manage server-side rendering (SSR), API routes, middleware, and complex configurations to get started. While this is great for full-fledged web applications, it can be overwhelming for developers who just want to build a fast and lightweight website.

Astro, on the other hand, focuses on making the development process as straightforward as possible. Its component-based architecture is familiar to those coming from React, Vue, or Svelte, yet it strips away unnecessary complexity. The learning curve is significantly lower, making it easier for beginners and experienced developers alike to get up and running quickly.

## Zero JavaScript by Default

Next.js is built on React, which means it ships JavaScript by default, even if you’re just building a simple content-driven site. This can lead to unnecessary client-side bloat, slowing down page loads and hurting performance. React server components are a step in the right direction but there is still going to be a framework javascript bundle included even if your site is fully static.

Astro takes a different approach with its "zero JavaScript by default" philosophy. Static pages are built with no JavaScript overhead unless explicitly needed. You can still use interactive components when necessary, but Astro ensures that only the required JavaScript is sent to the browser, resulting in dramatically better performance.

## Faster Setup and Easier Deployment

Setting up a Next.js project requires configuring API routes, selecting a rendering strategy (SSG, ISR, SSR, CSR), and often wrestling with Vercel-specific optimizations. While these features are powerful, they add layers of decision-making that can slow down the development process.

Astro, on the other hand, is designed for rapid setup. A basic project can be scaffolded in minutes without worrying about complex configurations. Deployment is seamless, whether you’re using Netlify, Vercel, or traditional static hosting providers.

## Adding Client-Side Interactivity

While Astro is optimized for static content, it provides an elegant way to add client-side interactivity when needed. With its "partial hydration" approach, developers can load JavaScript components only when necessary, preventing unnecessary performance hits.

Astro allows developers to import React, Vue, Svelte, or other frameworks for interactive elements and control their behavior using directives like client:load, client:idle, and client:visible. This fine-grained control ensures that interactive components are only loaded when they are actually needed, maintaining fast page speeds.

For example, if you have a dynamic search bar or a carousel, you can selectively hydrate just that component instead of loading JavaScript for the entire page.

## Superior Performance Out of the Box

Speed is critical for modern websites, and Astro is designed from the ground up to be performance-first. By sending zero JavaScript unless necessary, Astro sites consistently achieve better Lighthouse scores compared to Next.js sites, which often require additional optimization efforts to minimize JavaScript payloads and improve performance.

While Next.js does offer static site generation (SSG) for performance benefits, Astro inherently builds for the static web, making it the better choice for blogs, marketing sites, documentation hubs, and content-driven applications.

## When Should You Still Choose Next.js?

While Astro excels at building static and hybrid websites, Next.js remains a great choice for dynamic applications that require server-side rendering, API routes, or extensive backend integration. If you’re developing a large-scale SaaS platform or need complex user authentication and real-time data fetching, Next.js might be a more suitable option.

## Wrap-up

If your goal is to build a fast, easy-to-maintain, and high-performance website, Astro is the clear winner over Next.js. Its simplicity, zero JavaScript-by-default philosophy, flexible client-side interactivity, and superior performance make it the ideal framework for content-driven websites. While Next.js is still a fantastic tool for application development, Astro’s approach makes it the smarter choice for many web projects today.

