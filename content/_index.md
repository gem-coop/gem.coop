---
title: "gem.coop"
---

We’re excited to introduce **gem.coop** -- a new server for gems in the [Ruby](https://ruby-lang.org/) ecosystem.

We aim for fast, simple hosting, that is compatible with [Bundler](https://bundler.io/) but optimized for the next generation. It’s built for the community by the former maintainers and operators of [RubyGems.org](https://rubygems.org/).

All gems published to [RubyGems.org](https://rubygems.org/) are available, updated in real time. Get started right now with a simple change to your [Gemfile](https://bundler.io/guides/gemfile.html):

```diff
-source "https://rubygems.org"
+source "https://gem.coop"
```

To use gem.coop directly from the `gem` command you can either specify it for a single `gem install`.

```shell
gem install --clear-sources --source https://gem.coop <gem>
```

Or you can add it to your `gem sources` (and remove [RubyGems.org](https://rubygems.org/) if you wish).

```shell
gem sources --add https://gem.coop

# if you want to fetch from gem.coop only
gem sources --remove https://rubygems.org/

# to verify
gem sources list
```

Governance for this project is modeled on [Homebrew](https://brew.sh/), with setup assistance from [Mike McQuaid](https://github.com/MikeMcQuaid). The documents describing the proposed governance structure and the process we're following to adopt it [can be found on GitHub](https://github.com/gem-coop/governance/#readme). Everyone from the Ruby community is welcome to contribute and participate.

If you want to follow along with our progress, subscribe to the gem.coop newsletter for monthly updates.

Our goal is to provide fast, community-owned, transparent, sustainable, and secure gem hosting for everyone. We’re launching with support for bundling and installing all public gems, and we’re excited to keep improving.

— The Gem Cooperative ([@deivid-rodriguez](https://github.com/deivid-rodriguez), [@duckinator](https://github.com/duckinator), [@indirect](https://github.com/indirect), [@martinemde](https://github.com/martinemde), [@segiddins](https://github.com/segiddins), [@simi](https://github.com/simi))
