---
author: "hypowork"
title: "Makerwork 005"
date: "Mon, 22 Feb 2021 12:00:06 +0800"
description: ""
draft: false
hideToc: false
enableToc: true
enableTocContent: true
authorEmoji: 👨
tags: 
- clojure
- music
- rust
series:
- makerwork
image: images/feature/makerwork005.png
mustache: ./pandoc.yaml
---

{{< img src="/images/header/375x200makerwork-code-block-purple-green.png" title="" alt="Makerwork" height="199px" position="center" >}}

## Hey Makers! 👋

Welcome to **Digest {{num}}** of the newsletter. {{intro}} 🏆

{{body}}

{{star}} ⭐️

## What I've Been Reading 📖

* ⭐️ GUIs are useful if you're an amateur composer, but sometimes [to achieve greatness you need to go back to basics and start with a blank canvas](https://blog.djy.io/alda-a-manifesto-and-gentle-introduction). Now you can even have a version history using music as code.

* Stories of people losing their Google accounts for practically no reason scare me. Maybe it's time to [de-Google my mission critical and sensitive stuff](https://kn100.me/declouding-replacing-google-photos-part-1).

---

## Maker Focus 🏆

*Featuring one or more makers per digest. Want to be featured as a maker? Fill in this [form](https://yourls.fxgit.work/010jotsh). ✍️*

### {{name}}

{{< featuredImage alt="featured image" width=200 height=200 >}}

| [Twitter]https://{{twitter}} | [LinkedIn]https://{{linkedin}} | [GitHub]https://{{github}} | [Keybase]https://{{keybase}} | [Blog]https://{{blog}} |
| ------- | ------- | ------- | ------- | ------- |

{{skill}} 🍸

He is currently learning {{learning}} 📚

---

## Product Focus 📦

### [{{pname}}]https://{{purl}} ⭐️
*{{pshort}}*

{{< img src="/images/makerwork{{num}}/{{pimage}}" title="{{pname}}" alt="*{{pname}}*" width="{{pwidth}}px" position="center" >}}

| Language | Stars | Forks | Issues |
| ------- | ------- | ------- | ------- |
| {{planguage}}  | {{pstars}} | {{pforks}} | {{pissues}}  |

| Last commit | First commit |
| ------- | ------- |
| {{plast}} | {{pfirst}} |

### [{{qname}}]https://{{qurl}}
*{{qshort}}*

{{< img src="/images/makerwork{{num}}/{{qimage}}" title="{{qname}}" alt="*{{qname}}*" width="{{qwidth}}px" position="center" >}}

| Language | Stars | Forks | Issues |
| ------- | ------- | ------- | ------- |
| {{qlanguage}}  | {{qstars}} | {{qforks}} | {{qissues}}  |

| Last commit | First commit |
| ------- | ------- |
| {{qlast}} | {{qfirst}} |

**Bloom** is an open source and privacy-focused productivity suite: Inbox, Calendar, Files, Contacts & much more. It's literally the easiest way to de-Google your life and business. 

### [{{rname}}]https://{{rurl}}
*{{rshort}}*

{{< img src="/images/makerwork{{num}}/{{rimage}}" title="{{rname}}" alt="*{{rname}}*" width="{{rwidth}}px" position="center" >}}

| Language | Stars | Forks | Issues |
| ------- | ------- | ------- | ------- |
| {{rlanguage}}  | {{rstars}} | {{rforks}} | {{rissues}}  |

| Last commit | First commit |
| ------- | ------- |
| {{rlast}} | {{rfirst}} |

---

## Tweet Focus 

{{< img src="/images/makerwork{{num}}/{{timage}}" title="{{tname}}" alt="*{{tname}}*" width="{{twidth}}px" position="center" >}}

---

## Education 📚 & Resources 🧩

* [Building in Public Definite Guide](https://kevoncheung.com/building-in-public): *You're now reading the Building in Public eBook and guide that comes from months of studying, understanding, and implementing how Building in Public works for founders and creators.*
* [Litic](https://litic.techseo.blog): *Analyze your website and get insights about SEO, accessibility, security, and best practices in less than a minute.*

---

## An Interview with {{fname}} of {{pname}}

**Hey {{fname}}! Let's start out with your background and how did you get into coding? 📝**

> I'm a software engineer at [Kevel](kevel.co), and a life-long musician, composer and self-taught programmer. 
> 
> After studying Music Composition in college and beginning to get more into software development, I started to become really interested in the idea of composing music the same way that software developers create software. This is what led me to develop Alda, a music composition programming language.

**What is the purpose of your blog, and what resources do you use to get your ideas, if any? 🧩**

> I write about all kinds of things in my blog. I've probably written the most about Alda, but I've also written about my various music projects, productivity tools, the Clojure programming language, and a bunch of other random stuff.
> 
> I keep a file where I jot down quick ideas for blog posts whenever they occur to me. I try to keep my blog post ideas small, although I often end up having a lot more to say than I anticipated! 
> 
> Every couple weeks or so I try to start working on a new blog post, and I refer to my list of blog post ideas for inspiration.

**What is an opinion you have that most people don't agree with? ✒️**

> I strongly prefer lines of code to be shorter than 80 characters. I feel like if you get much longer than that, the code ends up being difficult to navigate on smaller screens, harder to read, and poorly written. 
> 
> Granted, it isn't always technically possible to get below 80 characters (for example, there could be a really long URL that you can't chop up), and it doesn't bother me when teammates or contributors go over 80 characters for whatever reason. But in the code that I write, you'll typically see a lot of short lines instead of a few long ones.

**Why was {{pname}} started and is there a roadmap? 🎯**

> When I studied music composition, I used graphical score editing programs extensively, and I learned that if you use those types of GUI applications to assist you with composition, it becomes severely artistically limiting, because you end up composing music that is easier to notate in the GUI, but much less interesting and imaginative than it could be.
> 
> As I got more into software development, I grew to love the autonomy and creative freedom that came from working with a simple text editor and the command line. Because this type of environment doesn't guide you in any particular direction, you are free from influence and you can create whatever comes to mind. 
> 
> At one point, I started to wonder what it would be like to apply this sort of philosophy to music composition. In 2012, I started to experiment with creating a text-based language for music composition, and that experiment became Alda.
>
> In the years since then, I have been focused on implementing the basic features of the language, making the compiler performant, and providing a quality CLI experience. That work is still ongoing, but I do have some exciting ideas for the future of Alda, including collaborative live-coding features, waveform synthesis, and flexible import/export with a variety of formats including MIDI and MusicXML.

**What is the most challenging problem that's been solved in {{pname}} so far? 🚧**

> MIDI export was tricky to implement. Alda's model of time differs significantly from the typical one that you see in MIDI files. 
> 
> They are compatible, but I had to implement some complex logic in order to get to the point where you can export an Alda score to a MIDI file that's usable in other programs.

**What is one feature, which you're most proud of, that differentiates {{pname}} from other products? 🦄**

> I think Alda's killer feature is that it treads the line between an easy-to-use, beginner-friendly music programming language and a flexible, all-powerful environment for Turing-complete music programming. 
> 
> Whether you're a musician looking to get more into programming, or a programmer looking to learn how to write music, I think you'll enjoy what Alda has to offer.

**What is one product that you can't live without that you think others should know about? 💡**

> I use tmux extensively to organize and persist all of my terminal sessions. It's really nice to be able to start something in one shell and then close the terminal and pick it right back up later, without having to remember the last command I run and the output.

**If I gave you $1 million to invest in one thing right now, where would you put it? 🚀**

> I would invest in research and development into affordable, sustainable transportation that won't contribute to climate change.

**Thank you {{fname}}.**

---

Like what you saw here? Why not share it?

<p>
<span class="badge-buymeacoffee"><a href="https://ko-fi.com/dennislwm" title="Donate to this project using Buy Me A Coffee"><img src="https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg" alt="Buy Me A Coffee donate button" /></a></span>
</p>