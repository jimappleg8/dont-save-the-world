---
layout: default
title: Don't Save The World Book
eleventyNavigation:
  key: home
permalink: /index.html
---
{% from "macros/hero-book.njk" import hero %}
{% set options = {
  dark: true,
  topText: "The world needs people who can help it evolve.",
  titleText: "The World Needs<br><span id=\"typed-text\" class=\"text-secondary-600\"></span>&nbsp;",
  subtitleText: "Learn how to become part of the <span class=\"text-primary-300\">Great Collaboration</span> where millions of <span class=\"text-primary-300\">Cultural Creators</span> like you are building a world that works for everyone.",
  buttonText: "Read The Introduction",
  buttonLink: "/book/0-introduction/",
  imageSrc: "/assets/images/DSTW-Front-Cover-Art.png",
  imageAlt: "Book Cover"
} %}
{{ hero(options) }}

{% section %}

## Help build a better world

Our human world is a mess. The world's purpose is to help humanity survive and thrive, but it's doing that for only a small percentage of us and at the expense of the planet. We don’t need to save it, we need to evolve it, fix it, make it better than it is now.

That's not to say that we want to tear down or destroy anything. Our world is a gift from thousands of generations of our ancestors, passed to us for safe keeping and further development. It's a mess, yes, but much of it is beautiful and invaluable.

So, how do we peacefully reshape the world? Buckminster Fuller called it a design revolution, and it's already underway. Cultural creators like you and me are pooling our creative energies and working together to reimagine our world. We're designing and building life-sustaining alternatives to the life-destroying parts of the world we seek to make irrelevant.

*Don't Save The World* gives you step-by-step instructions on how to participate in this revolution. It doesn't tell you what to think, but it does advocate for the common good. It doesn't promote specific solutions; it shows you how you can tap into your life experience, knowledge and skills and find your own way to contribute. It shows you a path along which you can improve yourself while also improving the world.

Sound good? {% externalLink "Get your copy of <i>Don't Save the World</i> today!", "https://a.co/d/0j7BB2zj" %}

## A new, old kind of activism

We hear a lot about the well-worn ways of creating change: protesting in its many forms, trying to convince politicians and businesses to do the right thing, or giving money to those trying to patch over the cracks in the system.

We're so caught up trying to create change from within the system that we forget that the system was created by and for people, just like us. We are both part of the system and separate from it. That means we can step outside of the system and look at it objectively.

It's that outside perspective that allows us to imagine how our world might be better. It also allows us to see past all the problems we face and start to see the new solutions that people are growing between the cracks in the old system. There is a whole different world of life-sustaining ideas developing all around us that I call Eternia. It's being built by people just like you in the same ways that our ancestors reshaped their worlds.

Building Eternia is the most powerful form of activism that no one talks about, and it's available to you. {% externalLink "Get your copy of <i>Don't Save the World</i> today!", "https://a.co/d/0j7BB2zj" %} and come meet us in Eternia.


## A hopeful future

I’m old enough to remember a time when people were excited about the future. The *National Geographic* magazine had stories about how we’d all be living on the Moon or in orbiting farms that would help feed the people on our planet. There was hope that we’d solve the problems we faced and we’d come out OK.

The feeling today is much bleaker. We’re faced with climate change and a whole slew of other problems and the future has become scary. I think what makes it scary is that we don't really know what to do about the problems we face. 

One of the guiding principles on *Don't Save The World* is that individuals drive real change. There isn't anything more powerful than a person with a good idea, except perhaps millions of people with good ideas supporting each other to realize them. The ability to take meaningful action brings with it hope for the future, and this book is all about taking meaningful action.

It doesn't matter if you are feeling a little low on ideas at the moment; there are other creators looking for people with your skills to help them develop their ideas. It doesn't matter if you have only a tiny amount of time to contribute; you get to decide what you work on, when you do it, and for how long. And it doesn't matter if you don't think you have any usable skills; part of goal is for you to grow, so there's plenty of opportunity to learn on the job.

If you've been looking for a way to stop worrying about the future and start making a difference using the best of your experience, knowledge and skills with infinitely flexible hours, {% externalLink "get your copy of <i>Don't Save the World</i> today!", "https://a.co/d/0j7BB2zj" %}.

## A practical guide

Whatever else *Don't Save The World* is, it is first and foremost a practical guide. I've been frustrated by calls to action that fall short on specifics. Calls to "Stop Racism" and "End Inequality" are worthy goals but how, exactly, do we do that?

On the other end of the spectrum are the overly simplistic solutions like "plant a tree" or "recycle." Again, these are worthy actions, but they may not be possible for everyone, and even if you do them, what comes next?

*Don't Save The World* offers actionable steps that we can all take. It teaches you a skill set that can be applied to building solutions to any intractable problem you want to address. Your actions are completely self-directed, but you're not left alone to figure it all out by yourself. We all have a lot to offer the world and together we have immense power to create change.

If you want to learn practical skills around how we can harness our collective power and bring about the world that we want to live in, {% externalLink "get your copy of <i>Don't Save the World</i> today!", "https://a.co/d/0j7BB2zj" %}.

## Available now

Currently, you can only order the book from Amazon. I’m working to make it available from different vendors and in different formats, but the paperback is available now:

{% externalLink "Order now on Amazon.com", "https://a.co/d/0j7BB2zj" %}

I hope you'll join us in the design revolution as a cultural creator. We need the unique experience, knowledge and skills that you have.

{% endsection %}

{# From https://github.com/mattboldt/typed.js #}
<script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
<script>
  document.addEventListener("DOMContentLoaded", function() {
    var options = {
      strings: [
        "Your Perspective.",
        "Your Experience.",
        "Your Knowledge.",
        "Your Skills.",
        "Your Creativity.",
        "You.^3000"
      ],
      typeSpeed: 100,
      backSpeed: 25,
      loop: true
    };

    var typed = new Typed("#typed-text", options);
  });
</script>