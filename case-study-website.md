# Case Study: Building theleannesummers.com with AI

**The honest version: what took weeks, what took half a day, and why it still took six months to launch.**

---

## The starting point

I already had a website. An old WordPress site from my copywriter days. I'd paid someone to build it — a proper designer, a proper build. I also paid for a brand stylist to create my brand guide: the colours, the type choices, the visual logic that made the whole thing feel considered and cohesive. It felt like me.

It had a look I liked. A tone of voice I'd spent years earning.

When I started positioning myself as an AI Workflow Designer, I needed a new site. I had a different story to tell and different humans to speak to.

What I didn't need was to pay someone again.

What I definitely didn't need was to dive into WordPress and start again.

So one night on the couch, I asked Claude how I could build a new website knowing that I already had a domain name and a hosting site. We had a plan and off we went.

---

## Step one: capture the brand before it disappears

The new site wasn't going to be WordPress. But I wanted all the architecture. I wanted the new site to look like the old one, without having to redo it all again.

Problem: the colours, the type scale, the spacing decisions that made it feel like *me* — all of it lived entirely in the platform. Not in a document. Not anywhere I owned. Of course I had the brand guide and the assets, but not the look and feel of my "paid for" website.

So before touching anything else, I asked Claude to read the old site and reverse-engineer a brand style guide from it.

The result is a document called `design-guide.md`. It captures everything: the exact colour hex codes (Coral `#FE7061`, Teal `#03A6A6`, Ink `#272525`), the typeface pairing (Playfair Display for headings, Source Sans Pro for body), the spacing scale, the component rules, the things not to do. It even documents the logo usage rules and the mobile breakpoints.

That document is mine now. Not locked inside a platform. Not dependent on a subscription. Sitting in a folder I own, readable by any tool, transferable to any build.

---

## Step two: write the brand voice guide

The design was one half. The other half was the words.

I've been writing professionally for a long time. I know how I sound. But "how I sound" isn't something most people can hand to an AI and get back intact. You have to make it explicit.

So I wrote a brand voice guide — the real one, not the watered-down version. Five pillars. The words I use. The words I never use. The difference between earned authority and empty claims. The reason dry wit works when it's quiet and fails when it's performed.

That guide became the filter for every sentence on the new site. When copy drifted into marketing language — *transform*, *seamless*, *unlock* — the guide caught it. When a sentence got vague where it should have been specific, the guide fixed it.

The result is copy that sounds like me. Because it was written using the rules I set.

---

## Step three: build the site

With a style guide and a voice guide in place, the actual build was fast.

Claude wrote the HTML and CSS. Not "generated a template and hoped for the best" — wrote it against the design guide specs. Correct type scale. Correct colours. Correct spacing tokens. Correct mobile behaviour.

I reviewed. I changed words. I made decisions about what to keep and what to cut. The formatting, the layout, the structural decisions — those were mine in the sense that I'd defined them in the guide. The execution was AI's.

Three pages built and styled in an afternoon: Home, About, Contact. Plus Privacy and Terms based on the existing legal pages from the old site, edited down to what actually applied.

---

## Step four: ship it

The site lives in a GitHub repository. Plain HTML and CSS files — no build step, no CMS, no dependencies.

(Github sounds incredibly scary, and it took me a good year to build up the courage to create an account, but it's one of the best decisions I've ever made — and it's not scary at all. It's simply a file system that keeps every version of documents you've made.)

GitHub Pages serves it. The custom domain (`theleannesummers.com`) points to GitHub's servers. Deploying a change is: edit the file, commit, push. Done. Live in under two minutes.

If I want to change a word today, I change the word. If GitHub Pages shuts down, I move the files somewhere else and point the domain there. Nothing is locked in. Nothing has a monthly fee attached to it. The whole thing is mine in a way that a Squarespace site never quite is.

---

## What it actually took

The brand capture, voice guide, copy, and build: one working day. Maybe a bit over.

The courage to launch it: six months.

That part isn't a workflow problem. The assets were ready in April. The site sat in a GitHub repo, built, styled, polished — and I didn't push the button.

Because putting yourself out there in a new way, with a new title and a new offer, is harder than building the thing. The building is the easy part, once you know what you're building.

I finally pushed it live in June 2026.

---

## What this means if you're doing the same thing

If you have a brand that lives somewhere you don't own — a platform, a designer's head, an old folder with files you can't read — capture it now. Turn it into a document you can hand to any tool, any designer, any future version of yourself.

If you have a voice but you've never made it explicit — write it down. Not "friendly, professional, approachable." Voice pillars. Anti-examples that are just as specific as the examples. The exact words you reach for and the ones that make you cringe. If you don't know where to start, tell your preferred AI that you want to make a brand voice guide and ask it to interview you. You can make one together. Once it's written, it's repeatable.

And if the thing you're waiting for is the perfect moment to launch: it doesn't come. You push the button on a Tuesday morning when you've run out of reasons not to.

That's the actual workflow.

This case study, and the website it lives on, is one of those workflows. What used to take days of manual effort is now done. Which means the time is mine: for coffee, for a walk, for the decisions that actually need me rather than the tasks that just needed someone.

So hello. Welcome to my little corner of small-business-owner get-my-time-back land.

---

*Built: April–June 2026. Stack: plain HTML/CSS, GitHub Pages, Formspree. Tools used: Claude Code CLI.*
