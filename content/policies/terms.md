+++
title = "gem.coop terms of service"
linktitle = "terms of service"
date = "2026-06-04"
+++

Last Updated {{% date %}}

These terms of service govern access to and use of the gem.coop Ruby programming language package repository and website at <https://gem.coop>.  To use gem.coop, you have to agree to these terms.

We've done our best to write these terms in plain English that everyone can understand.  We strongly encourage you to read through yourself, and to let us know if we could make something more clear.

## In Brief

Thanks to generous sponsors and volunteers, we offer the core functions of gem.coop, publishing and downloading packages of Ruby programming language code, or "gems", completely free of charge.

Like contributors to open source projects, we stake our reputation on keeping gem.coop reliable, efficient, and secure.  Where open source contributors use license terms to limit legal risk for what they give away, we use these terms of service to protect our ability to keep gem.coop functional and free.

From the legal point of view, terms in ***bold italics*** below are particularly important, like the `SHOUT CAPS` parts of open source licenses.  We encourage you to give those parts special attention: [Disclaimers](#disclaimers), [No Liability](#no-liability),[Arbitration](#arbitration), [Deadline to Sue](#deadline-to-sue).

## Provider

gem.coop is currently a project of [Spinel Cooperative Corporation](https://spinel.coop), a California general cooperative.  When these terms speak from the first person, they speak on behalf of Spinel.  Your agreement to use gem.coop on these terms is an agreement with Spinel. We intend to create a dedicated legal entity for gem.coop in the future. We can't make any promises about the timing, but we will update these terms and let you know when we do.

## Acceptable Use

Having agreed to these terms with us, you may search for, download, publish, and manage gems, sign up for and manage an account, and otherwise interact with the repository and the website.

You'll most likely use the repo through free programs like [`rv`](https://github.com/spinel-coop/rv), [Ruby Butler](https://github.com/RubyElders/ruby-butler), [Bundler](https://bundler.io/), or [`gem`](https://github.com/ruby/rubygems).  You may also use other client software, or generic Web clients like `wget` or `curl`, but only through application programming interfaces that we describe for public use in documentation we publish.

You may perform security research on systems we use to provide gem.coop so long as you follow our security policy at <https://gem.coop/security>.

## Unacceptable Use

You agree not to:

- use gem.coop in any way that violates any law that applies to you or to us
- use anyone else's account but your own
- impersonate anyone else or falsely claim to be affiliated with organizations
- use gem.coop to send ads, job offers, service pitches, research recruitment messages, or other unsolicited messages to others
- crawl, scrape, or otherwise automate access to our website with programs other than manually operated web browsers and related assistive technologies
- disable, avoid, or circumvent any security or access restrictions, or access parts of our systems not intended for public access by users, other than as part of security research under our security policy
- strain the technical infrastructure of our repository or website with an unreasonable volume of requests, or requests designed to impose an unreasonable load on our systems
- automate repetition of needlessly duplicative requests, such as by configuring a build server to download all dependencies of a project every five minutes, rather than when your codebase is updated, especially without caching
- encourage or help anyone else to violate these terms

## Acceptable Content

gem.coop is for Ruby programming language libraries, frameworks, tools, programs, and other software useful to other users as Ruby gems.  It's also for `README` files, documentation, metadata, and other content about your gems that express and explain your code, your collaborators, your communities, and your goals or motivations.

## Unacceptable Content

You agree not to submit gem or other content that:

- is illegal, offensive, abusive, harassing, inappropriate, or otherwise harmful

- infringes intellectual property rights, violates privacy rights, or breaches legal agreements with others

- uses gem.coop as general data storage, such as gems containing database backups, scanned documents, images, audio recordings, or video clips

- uses gem.coop as a pastebin, file sharing node, or general-purpose database

- is meaningless, duplicative, or automatically generated, used only to "reserve" or "squat" a gem name, namespace, publisher name or other identifier

- is named to invite confusion with or typo misdirection from any existing, similarly named gem, namespace, publisher name, or other identifier

- falsely implies that we, our suppliers, sponsors, or volunteers sponsor, endorse, or otherwise approve of you, your affiliations, or your work

## Security Software

If you would like to publish gems including potentially malicious software, such as software exploits, vulnerability scanners, rootkits, viruses, trojans, worms, or spyware, e-mail [support@gem<!-- don't spam us -->.coop](mailto:support%40%67%65%6d%2e%63%6f%6f%70) a description of your gem and how it works first.  If our support team replies approving your gem, you're free to publish it.  Otherwise, you agree not to publish such gems to gem.coop.

We support computer security research and defense.  We use plenty of arguably "dual-use" tools ourselves.  Alas, hosting even highly reputed tools like [Metasploit](https://www.metasploit.com/) inevitably leads to automatic red-flagging, uninformed complaints, and even policy changes affecting entire repositories and websites.  We want to host the next great security tool, but it really helps to see these problems coming and act ahead of time to prevent misunderstandings.

## Commercial Content

All kinds of gems are welcome on gem.coop, from your first helper library as a hobby programmer to "enterprise"-grade commercial products and works of coding art.  However, gems and your content about them must respect that we remain neutral.  Express yourself, promote your projects, and advance your career, but don't abuse content conventions for gems or our website to put self-promotion before code.

More concretely, feel free to include all the following commercial info in `README` files and other documentation:

- credits, acknowledgments, attributions, and other recognition of contributions to gems
- information on how to hire, donate to, and otherwise support gem developers and steward organizations
- acknowledgments, including links and logos, for organizations developing, maintaining, or funding gems
- information on paid products and services related to gems, such as enhanced versions, add-ons, commercial licenses, training, integration, or support

On the other hand, these kinds of commercial content are _not_ allowed:

- advertisements in `README`s, other documentation, code comments, or metadata
- gems that are really just ads, with little if any original code, data, or other useful content
- gems that display ads at install time, runtime, or at other stages of the software development lifecycle, as distinct from gems coders use to help display ads of their own in other software

## Your Content

Nothing in these terms gives us ownership of any gems or other content you submit to gem.coop.  Your content belongs to you, and you decide whether and how to license it.  You do not need to license gems under any particular kind of license, such as a "free" or "open source" license, to publish them to gem.coop.

However, at a minimum, you license us to provide your content to other users of gem.coop and to operate gem.coop as a reliable, efficient, and secure public service.  That special license lets us copy, compress and decompress, distribute, and analyze your content, and to share our analyses with others.

We may run computer code on content you submit to analyze it, but our special license alone does not give us the right to run your gems for their functionality.  If you publish a gem containing proprietary software that requires buying a separate license to use, our special license lets us distribute that gem, back it up, cache it, and so on, but the fact that you've published it to gem.coop doesn't give us the right to use it ourselves for free.

When your content gets removed from gem.coop, by you or by us, our special license for it ends when the last copy disappears from our backups, caches, and other systems.  Other licenses, like licenses on open source terms that you may apply to your work, might continue even after your gems get removed from gem.coop.  You acknowledge that those licenses might give others, including us, the right to share your content with gem.coop again.

## Code of Conduct

You agree to abide by our [Code of Conduct](/code-of-conduct) in your interactions with our personnel, volunteers, and other gem.coop users.

## Privacy

Information about personal data we collect and how we use those data can be found in our privacy policy at <https://gem.coop/privacy>.  You grant us consent to collect and process personal data about you as described in our privacy policy.

## Moderation

Earlier sections set out your obligations in using gem.coop.  They don't limit our ability to remove gems and other content from gem.coop.  As far as the law allows, we reserve the right to remove any content at any time.  We similarly reserve the right to ban any gem, namespace, publisher, and other identifier we don't want used on gem.coop.

We can't promise or guarantee that we will notice and remove all the content that might violate the law, these terms, or our interpretations of them, quickly or at all.  If we do notice potentially unacceptable content, but don't take it down immediately, that doesn't mean it's allowed, or that we agree to leave it up.

When we take down gems or other content published with your account, we will send you an e-mail letting you know what we've taken down and why.  You can appeal those decisions, as required by the EU Digital Services Act, by e-mailing [support@gem<!-- don't spam us -->.coop](mailto:support%40%67%65%6d%2e%63%6f%6f%70).

If you find something on gem.coop that you believe breaks the law or these terms of service, please e-mail us at [support@gem<!-- don't spam us -->.coop](mailto:support%40%67%65%6d%2e%63%6f%6f%70).

## Name Disputes

You agree to abide by our name disputes policy at <https://gem.coop/name-disputes> to resolve any conflicts about who controls or uses particular gem names, namespaces, publisher names, or other identifiers on gem.coop.

You agree not to buy, sell, or trade user names, namespaces, gem names, or any other kinds of identifiers on the repository or website.

## Termination

You can end your agreement with us by sending us notice.  See [Correspondence](#correspondence) below.

We can also end this agreement anytime.  If you have an account, we will notify you by e-mailing the address given for your account.  If you do not have an account, you agree that we search publicly for some way to reach you, such as an e-mail address, mailing address, or phone number, and notify you that way.

As soon as our agreement ends, your permission to use gem.coop ends with it.  We may take technical steps to block your access to gem.coop immediately, and you may not agree to these terms again, or continue using gem.coop, without our specific, written permission.

The following sections continue in effect, or "survive", the end of our agreement under these terms: [Your Content](#your-content), [Indemnity](#indemnity), [Release](#relelase), [Disclaimers](#disclaimers), [No Liability](#no-liability), and [General Contract Terms](#general-contract-terms).

## Indemnity

If someone else makes legal claims against us related to your use or abuse of gem.coop, or your breach of your agreement with us, you agree to cover our costs and liability---or _indemnify_ us---for those claims.  This goes for claims against our members, volunteers, suppliers, and sponsors, too.  It covers reasonable lawyer fees.

This is a serious obligation, though one you'll find in terms for other free repositories, as well.  We've put it here in plain English, rather than legalese, so it's clear.

For our part, we agree to notify you promptly of any legal claims for which you might have to cover us.  We agree to let you control legal defense and any settlement, but you may not agree to any settlement that fails to release us from all liability without our specific, written approval.  We agree to give you any reasonable help you ask for your defense, but if doing so involves significant expenses, you agree to pay them where possible and to reimburse us otherwise.

## Release

You agree to leave us completely out of any legal disputes between you and other users of gem.coop related to use of gem.coop, such as lawsuits about gems you or others publish to gem.coop.  As far as the law allows, you agree to release us from all legal claims, demands, and liability related to those kinds of disputes.

## Disclaimers

***You use gem.coop entirely at your own risk.  We disclaim any and all guarantees about our service---_warranties_---that the law otherwise implies by default.***

***You use gems, data, and other content you access through gem.coop at your own risk, too.  All that content comes "as is" from us, without any warranties.***

## No Liability

***As far as the law allows, we will not be liable to you for any money a court could order us to pay---_legal damages_---related to your use of gem.coop, content you access through gem.coop, or our agreement under these terms.  This limit applies to all kinds of legal claims, not just claims for breaking our agreement.***

California law doesn't allow caps like this in certain situations, such as fraud, willful injury, and other situations set out in section 1668 of the California Civil Code.

## Changes to Service

We may change, suspend, or discontinue gem.coop, or any particular features of it, at any time.  We may announce these kinds of changes through the website or otherwise, but we don't promise to.

## Changes to Terms

We may change these terms over time.  When we do, we'll update this page with a new last-updated date at the top.  To keep using gem.coop, you have to agree to our latest terms.

If you have an account, we'll e-mail you about changes at the address given for your account.  If you don't have an account, you may see a general announcement about the change on the website, or when you access our service through a program like [`rv`](https://github.com/spinel-coop/rv), [Bundler](https://bundler.io/), or [`gem`](https://github.com/ruby/rubygems).  Either way, it's up to you to check for changes to these terms over time.

## General Contract Terms

### California Law

The law of the State of California will govern our agreement under these terms and any legal proceedings related to your use of our services.

### Court Orders

Both sides agree to ask for court orders related to your use of gem.coop or how we provide it only in state or federal courts in San Francisco, California.  Neither side will object to courts there having the right to hear the case---_jurisdiction_---being the right court within the state or federal court system---_venue_---or being an inconvenient place to hear the case---legal _forum_.

### Arbitration

***Apart from seeking orders in court, both sides agree to resolve all disputes related to your use of gem.coop or how we provide it by binding American Arbitration Association arbitration.***

Arbitration will follow the AAA's Consumer Arbitration Rules.  So that all involved can participate remotely, all documents related to the arbitration will be exchanged by e-mail, and all hearings will be held by phone or video conference call.  Any arbitration award will include costs of the arbitration, reasonable attorneys' fees, and reasonable costs for witnesses.  Either side can enter arbitration awards in any court with jurisdiction.

### One on One

With the following exception, you will resolve any legal dispute as an individual, and not as part of a class action or other kind of proceeding where one or a few represent a larger group.  No arbitrator will combine your dispute with any another without our permission.

A few years back, some clever lawyers discovered that while terms like this prevent them from bringing class actions, they can inflict great costs and try to force settlements by recruiting lots of people to bring individual claims all at once, running up a potentially huge bill of per-arbitration fees on the other side.  If you bring claims against us that are similar to claims by at least 25 other people, using the same lawyer or law firm, or lawyers and firms that are coordinating, an arbitrator will combine all relevant claims and apply the AAA's supplementary rules for mass arbitration.

A court, not an arbitrator, will decide when this exception applies and issue any orders against arbitrations begun in violation of it.

### Deadline to Sue

***You agree to bring any legal claims related to your use of gem.coop or our agreement to court or to arbitration no later than one year after the event that you think gives you the right to sue.***

We intend this specifically to shorten the deadline for bringing lawsuits---the _statute of limitations_---under California law.

### Who Can Enforce

These terms include some sections that benefit others beyond you or Spinel, such as our personnel, volunteers, suppliers, and sponsors.  Where these terms benefit them, they can enforce these terms, too.

### Assignment

You may not transfer---or _assign_---your agreement with us to anyone else.  If you try to do so, that's not a breach of our agreement that we have to sue you for.  It'll simply have no legal effect at all.

We can assign our agreement with you to other legal entities related to Spinel, any new legal entity set up to reorganize or take over operating gem.coop from Spinel, or any other organization that buys or otherwise ends up with ownership of our assets related to gem.coop.  We'll notify you of any assignments by updating these terms to identify who we're assigning to, following the process in [Changes to Terms](#changes-to-terms).

### Waivers

We may waive obligations under these terms of service, but only waivers we send you in writing will count.

### Unenforceable Terms

If a part of these terms of service can't be legally enforced as written, but could be changed to make it enforceable, we both agree that the arbitrator or judge should modify it to the minimum extent necessary to make it enforceable.  Otherwise, the provision should be left out and the rest of the terms enforced, consistent with the overall goal of protecting us from as much liability as possible for offering a valuable, technically complex service free of charge.

### Whole Agreement

These terms of service spell out all the terms of our agreement about your use of gem.coop.

### Correspondence

You agree to send all notices and other messages about our agreement under these terms to us by e-mail to [legal@gem<!-- don't spam us -->.coop](mailto:legal%40%67%65%6d%2e%63%6f%6f%70).  Messages sent elsewhere or otherwise do not count.
