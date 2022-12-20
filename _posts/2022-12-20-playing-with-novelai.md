---
title: Playing with NovelAI
excerpt: Musings on AI art.
published: true
categories:
  - General
tags:
  - general
  - musing
safira:
  - url: /assets/images/2022/12/safira3.png
    image_path: /assets/images/2022/12/safira3.png
    alt: AI image of Safira, stepping forward.
  - url: /assets/images/2022/12/safira2.png
    image_path: /assets/images/2022/12/safira2.png
    alt: AI image of Safira, clutching her arm.
  - url: /assets/images/2022/12/safira4.png
    image_path: /assets/images/2022/12/safira4.png
    alt: AI image of Safira, sitting down.
safira2:
  - url: /assets/images/2022/12/safira5.png
    image_path: /assets/images/2022/12/safira5.png
    alt: AI image of Safira, wearing a shorter dress.
    title: That golen hem on the bottom really restricts her legs, doesn't it?
  - url: /assets/images/2022/12/safira6.png
    image_path: /assets/images/2022/12/safira6.png
    alt: AI image of Safira, clutching her hands over her chest.
    title: The tights aren't black, and what the fuck is wrong with her hands?
  - url: /assets/images/2022/12/safira7.png
    image_path: /assets/images/2022/12/safira7.png
    alt: AI image of Safira, with three legs.
    title: I have no fucking idea how NovelAI came up with three legs.
---
**NovelAI art is not a replacement for real artistic effort. Please support artists through commissioning them and boosting them when you can.**

This is a bit of a popular topic these days, and one that until today, I didn't look into much apart from vague distaste. I decided to play around with [NovelAI's image generation](https://novelai.net/image) this morning to get to know more about it. I have some thoughts. My usual instinct favors a Twitter/Mastodon thread, but I think I should give this blog some love. I also don't want to imply this is going to cover every possible talking point or moral stance, it's just an off-the-cuff post based on a couple hours of experience.

First and foremost, I side with artists on this. I *deeply* respect and admire those who put hours, months, years of their lives onto their craft, constantly improving and expressing themselves. I do not for a moment think AI art could, or *should* replace them. I've been grateful to know many artists in my life, my girlfriend is one, and I've tried my hand at learning a couple times. It requires dedication, discipline, and a degree of earnestness common to any creative endeavor.

That we have AI art this detailed and clean is an achievement of design and programming. I'm not denying that. The final pieces look pretty good! But these images are based off innumerable pieces of anime art harvested across the internet, and I imagine they weren't given with the artist's consent. That's fucked up, and I don't want to support continued development of these AI tools with these ethical considerations. I've thrown $10 into NovelAI to see how it worked. I don't anticipate giving them more.

A friend of mine discussed this in a Discord server, and she talked about how smugly malicious people can be toward artists, and how AI art should put them out of work. *Fuck no*. The pieces I generated, which I'll show off throughout this post, look fine for my limited purposes, but they *categorically* pale in comparison to human effort. I want to continue commissioning artists to draw my characters, and all I want to use AI art for, all I think it *should* be used for, is **to help spark inspiration for human artists**. That's it. They aren't real work in and of themselves. They don't replace years of effort.

That out of the way, let me talk about my experience.

---

I decided to generate art of an elven self-insert of mine, Safira. I've semi-jokingly called her my elfsona to a couple people, but that's essentially what she is: an idealized fantasy of myself.

On a related note, I've recently come out as a transwoman. Go figure.

(I can do a whole separate post about her, but I don't have a backstory or personality. She exists in a high fantasy setting of mine as a crystal/stellar mage. I've statted her up as an Astral Elf Abjuration Wizard in D&D 5E, if that helps)

I originally came up with a design in 2021, with an artist friend of mine I've known for over a decade (please [check her work out](https://karla-talisayan.com/), she's one of the best artists I know). This took place over a few sessions, as I tried to come up with a design in real time, based off a few vague ideas. It came out pretty well! I wanted to use it as a base for further commissions (and also for vtubing, which I lost interest in, thankfully *before* I bought any expensive equipment/a Live2D avatar). But, I haven't done much with it, and figured it'd be a good experiment to use for NovelAI.

(I don't intend to post it here, as I certainly don't want it to be used as AI art fodder if this blog ends up getting scraped)

{% include figure image_path="assets/images/2022/12/safira1.png" alt="Waist-up picture of the elven character Safira." caption="One of the first images I generated of Safira, before I though to add the `full body` tag." %}

If you haven't used it before, they first have you pay a monthly sub (the lowest is US$10 a month), which gives you 1000 credits (called 'Anlas' because of course it is). Each piece of AI art costs about 5 credits, with the price increasing depending on the complexity of the image. I set the AI to generate a tall portrait (512 x 1024), which cost 6 Anlas.

You then fill out a query string of comma-separated tags, which inform the AI as to the kind of character you want. There are other settings you can tweak, as well as tweaking the final image, but I didn't bother with those. You can also spend ~24 Anlas to generate variants of an image, which yielded some interesting results. I didn't keep examples, however.

The query string took a few tries to get right, but I found it was best to be as specific as possible. Every little thing I could think to put into the query helped with the final image. This is what I ended up with (in no particular order):

```csv
blue dress,gradient hair,purple hair,elf,dark skin,halter top,purple eyes,long hair,full body,over knee tights,long dress,mary janes,gold trim
```

And here's how it turned out:

{% include gallery id="safira" caption="Examples of Safira generated by NovelAI." %}

I think they look pretty good for something generated in a few seconds. I don't think these constitute the 'real' version of the character. They're variations on a theme, put together by a blind, dumb machine. I could probably get even more granular, but I don't much see the point.

You'll note the lack of backgrounds (save one image, further down). I'm sure I could try to have NovelAI generate them, but again, I don't see the point. The more tags I add, the muddier the end result become. There's definitely a sweet spot I think I've hit with Safira where I can reliably generate usable images. I'll mention this again later, but sometimes NovelAI ignores some tags. I imagine Safira wearing tights on her arms (there's a name for these, I don't recall it), but I wasn't able to get images with those.

There's a few clear traits here (long blue dress with gold trim, elf ears, purple hair and eyes, dark skin, tights, Mary Janes), but they're just basic, without personality or flair. Sure, I can have the AI generate images of her in different clothes or a different hairstyle, but it's essentially a novelty.

{% include figure image_path="assets/images/2022/12/safiramaid.png" alt="AI image of Safira, wearing a maid dress." caption="You know I had to do it (maid cosplay) to 'em (her)." %}

There isn't a unified look to these; none have a noticable style. They're about as bland and vapid as character art can be. There isn't any soul in these, whereas my favorite artists have a strong sense of style. I can identify their work at a glance. Each one brims with effort and personality.

To use my friend Karla as an example, her art is lush and complex, with lovely shadows and detailing. I've seen her work improve over the 14 years I've known her, and I can that progression clearly with older pieces I have from when we first met.

Another example is my favorite Japanese artist, [lansane](https://www.pixiv.net/en/users/4007933). The work they put into designing so-called monstergirls is fascinating, and each one overflows with personality, particularly their poses and facial expressions. I'm excited to see each new work, all expressions of their creativity.

I don't think this is something AI art could ever accomplish. It can't make those human decisions into lines, character details, poses. It can only copy what already exists.

Maybe we'll get to a point where an AI can make more original work, but after a certain point, I feel as if it'd become another artist, having become self-aware through increasingly complex programming and thought processes. Its creativity is increasingly indistinguishable from a human's, but should exist alongside them, not replacing them.

That's an entirely different discussion, however.

---

{% include gallery id="safira2" caption="Other examples of Safira generated by NovelAI." %}

What AI art does, what I think it's best for, is provide examples of what Safira *could* look like. It's a jumping off point, like a writing prompt. Something quick to give the artist an idea of how to draw her hair, her dress, her pose.

Eventually, I'd like to build up a body of commissions to fully nail her design down. I want to support as many artist as I can, while also feeling the affirmation of seeing this idealized self depicted in a variety of artistic styles. AI art can help, but eventually I think I'd like to fill my Imgur reference folder with other commissions. Other examples of what this character looks like, with a finalized design (and maybe even a reference sheet).

Obviously, every artist is going to want to put their own spin on the character, and I think AI art can help inspire little touches like that. But they're too bland to be representative of how I think of the character.

I'm pleased with these results, but I more look forward to using them to help craft a better-realized character. They aren't a complete solution, merely a tool.

Safira, however, is a pretty simple character design. I tried another character with a more complex design (one I don't have art of, just a relatively detailed list of traits), and NovelAI didn't generate anything I liked. I tried to be relatively granular, but I found it ignored a number of tags: the character has a red dress with a brown vest over it, but NovelAI kept ignoring the vest and only did a red dress. So, like I've said before, it's good for very broad strokes of character design based of a few simple traits, but is no replacement for human creativity.

A final note: I haven't used NovelAI's other main focus, AI-generated writing. There's maybe a use-case there, but I don't see myself needing it and aren't interested in playing around with it.
