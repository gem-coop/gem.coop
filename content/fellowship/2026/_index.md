---
title: "Announcing the 2026 Gem Fellowship"
date: 2026-01-19T09:44:46-08:00
publishdate: 2026-01-19
lastmod: 2026-01-19
tags: []
draft: true
---

Last month I announced my latest venture to support the Ruby open source community: the [Gem Fellowship](https://gem.coop/fellowship).
I want this grant program to support and fund existing Ruby-related open source project maintainers and their ongoing efforts: fixing bugs and adding features for those libraries we know and love.

## The Class of 2026

We announced $100,000 in available funds, took applications in the month of December and received 40 applications for a total of $439,000 in requested funds.
I've been working with [gem.coop](https://gem.coop) to select the highest value projects for the community; we settled on these eight projects.

<style>
  .fellow-headshots {
    margin: 20px auto;
  }
  .fellow-headshots li {
    display: inline;
  }
  .fellow-headshots img {
    width: 150px;
    display: inline;
  }
</style>

<ul class="fellow-headshots">
  <li><img src="/img/fellows/2026-jneen.png">
  <li><img src="/img/fellows/2026-emil.png">
  <li><img src="/img/fellows/2026-james.jpg">
  <li><img src="/img/fellows/2026-piotr.jpg">
  <li><img src="/img/fellows/2026-chris.png">
  <li><img src="/img/fellows/2026-marco.jpg">
  <li><img src="/img/fellows/2026-dmitry.jpg">
  <li><img src="/img/fellows/2026-jared.jpg">
</ul>

1. **Jeanine Adkisson**	[https://github.com/rouge-ruby/rouge](https://github.com/rouge-ruby/rouge/milestone/3)

Rouge was created in a fit of rage by jneen in an attic somewhere in south England when her personal website broke due to a libpython linking error in pygments.rb, which was the gold standard of syntax highlighting at the time.
It has since grown into a formidable project, supporting over 200 languages and powering the syntax highlighting of Jekyll, middleman, and Gitlab among others.

2. **Emiliano Della Casa** [https://github.com/emilianodellacasa/ruby-asterisk](https://github.com/emilianodellacasa/ruby-asterisk/milestone/1)

Ruby-Asterisk is a Ruby client for the Asterisk Manager Interface (AMI) that relies on synchronous telnet connections.
We are transforming it into a comprehensive toolkit for the Asterisk PBX ecosystem by adding native support for the REST Interface (ARI) and FastAGI.
The project is undergoing a major architectural overhaul to leverage modern Ruby concurrency features like Ractors and Async, ensuring thread-safety and compatibility with Ruby 3 and the newest Ruby 4.

3. **James Couball** [https://github.com/ruby-git/ruby-git](https://github.com/ruby-git/ruby-git)

`ruby-git` provides a Ruby interface to the git command line.
The current codebase, while functional, has several design issues that have accrued over time, making it difficult to extend and maintain.
The goal of this project is to refactor the codebase so it can better evolve with the git command itself.
See our [Architecture Redesign Implementation Plan](https://github.com/ruby-git/ruby-git/blob/main/redesign/3_architecture_implementation.md).

4. **Piotr Murach** [https://github.com/piotrmurach/tty-markdown](https://github.com/piotrmurach/tty-markdown)

TTY::Markdown transforms Markdown content into an easy-to-read format for display in terminal emulators. The grant will contribute to improving this experience through more robust content rendering with native hyperlinks, expanded theme configuration, greater recognition of HTML tags, and support for new elements such as emoji shortcodes or task lists.

5. **Christoph Olszowka** [https://www.ruby-toolbox.com/](https://www.ruby-toolbox.com/)

Christoph is the long-time author and maintainer of SimpleCov and Ruby Toolbox.
This grant will support [ongoing maintenance](https://github.com/orgs/rubytoolbox/projects/3/views/1?pane=info) for his projects.

6. **Marco Roth**	[https://herb-tools.dev](https://herb-tools.dev)

Herb is an HTML-aware ERB parser and tooling foundation that treats HTML+ERB as a structured language rather than plain text.
It provides a lossless syntax tree that enables reliable formatters, linters, language servers, and more advanced rendering and developer tooling in the Ruby ecosystem.

This grant will be used to stabilize Herb towards a [1.0-ready tooling and language foundation](https://github.com/marcoroth/herb/milestone/1) for Ruby, with a focus on backwards compatibility.
It will also lay the groundwork for exploring reactivity support in the rendering engine.

7. **Dmitry Vorotilin**	[Cuprite](https://github.com/rubycdp/cuprite/issues/307), [Ferrum](https://github.com/rubycdp/ferrum/issues/557)

Ferrum and Cuprite provide a Ruby bridge to modern headless Chrome and the Capybara driver powering reliable browser-based testing.
With this grant, Dmitry aims to ship Ferrum 1.0 with a stable, clean API and make Cuprite fully compatible so every Capybara test suite runs green on a fast, modern browser stack.

8. **Jared White** [https://www.bridgetownrb.com](https://www.bridgetownrb.com)

Bridgetown is a content-focused, "hybrid" web framework supporting both static deploys and full-stack applications.
We're ready to take things to the next level with two initiatives: an official plugin program called [Bridgetown Center](https://github.com/bridgetownrb/bridgetown/issues/1076) inspired by GNOME Circle, and a high-quality customizable theme called [Willamette](https://codeberg.org/bridgetownrb/willamette/issues/1) suitable for documentation, publishing, and portfolios.

Congratulations to our 2026 Gem Fellowship winners!

<div style="float: right; padding: 20px;">
  <a href="https://gem.coop">
    <img src="/img/2026.png" width="240" alt="Winners" license="Creative Commons Attribution-ShareAlike 2.5">
  </a>
</div>

Finally, we want to thank all Fellowship applicants for their time and ongoing effort to build and improve Ruby software.
We can't fund everyone but we hope you will continue to help Ruby's open source community thrive!

## Background 

Early in my Ruby days, I took over maintenance on the [`memcache-client`](https://rubygems.org/gems/memcache-client) gem.
A year later Couchbase asked me if I would be interested in adding support for memcache's new binary protocol; they would be willing to pay me to do the work.
I accepted their offer and that work turned into the `dalli` gem which has benefited the entire Ruby community.
The amount was $3,000, a laughably small amount IMO considering the actual amount of time I spent working on it. 500-1000 hours over the next two years?
But the expertise I developed from that small stipend was absolutely critical to making Sidekiq into the high performance Rubygem which has been so valuable to the Ruby community.
Everybody wins.

That's the spirit in which I've created the Gem Fellowship.

Mike Perham, mike@contribsys.com