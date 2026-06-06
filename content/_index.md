---
title: "gem.coop"
---

**gem.coop** is a next-generation gem server, created by the former maintainers and operators of rubygems.org.

To follow along as we build, [read our blog](/updates), or [subscribe to email updates](#subscribe).

## namespaces

Have you ever come up with a really good gem name, only to discover that name has already been taken and you can't push your gem? Ever been confused about if the gem `aws-sdk-malware` was really published by AWS?

Namespaces solve this problem, by creating a separate gem source for each user or organization. With namespaces, our gems live at [`gem.coop/@gem-coop`](/@gem-coop), and you can publish your own gems at `gem.coop/@yourname`. 

[Sign up and reserve your namespace today!](/sign_up)

## rubygems.org mirror

All gems published to rubygems.org are available from gem.coop, updated in real time. Get started right now with a simple change to your [Gemfile](https://bundler.io/guides/gemfile.html):

```diff
- source "https://rubygems.org"
+ source "https://gem.coop"
```

## cooldown (beta)

[We should all be using dependency cooldowns](https://blog.yossarian.net/2025/11/21/We-should-all-be-using-dependency-cooldowns). The gem.coop beta cooldown server hides mirrored gems until they have been published for 48 hours.

To use the cooldown beta, change your gem source URL like this:

```diff
- source "https://gem.coop"
+ source "https://beta.gem.coop/cooldown"
```

For more about the cooldowns beta test, check out [the cooldown docs](/docs/cooldowns).
