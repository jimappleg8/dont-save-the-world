---
layout: default
title: Open Artifacts 11ty Starter
eleventyNavigation:
  key: home
permalink: /index.html
---
{% from "macros/hero-book.njk" import hero %}
{% set options = {
  dark: true,
  topText: "The world needs people who can help it evolve.",
  titleText: "The World Needs<br><span id=\"typed-text\" class=\"text-secondary-600\"></span>",
  subtitleText: "Learn how to become part of the <span class=\"text-primary-300\">Great Collaboration</span> where millions of <span class=\"text-primary-300\">Cultural Creators</span> like you are building a world that works for everyone.",
  buttonText: "Read The Introduction",
  buttonLink: "/book/0-introduction/",
  imageSrc: "/assets/images/DSTW-Front-Cover-Art.png",
  imageAlt: "Book Cover"
} %}
{{ hero(options) }}

{% section %}

## A new, old kind of activism

We don't need more heroes trying to save the world.
We need more creators helping build a world that works for everyone.

In my book _Don't Save the World!_, I offer a practical guide for people who want to contribute to a better future—but don't want to wait for permission, perfection, or a five-year plan. Drawing on the work of Buckminster Fuller, Joanna Macy, and the open-source movement, this book invites readers to engage in a powerful creative practice: one that transforms both the world and the self.

Whether you're an artist, activist, educator, designer, or simply someone who cares, this book will help you:
→ Discover work that needs doing
→ Choose the creative contributions that are yours to make
→ Strengthen your ability to act with clarity, courage, and purpose
→ Participate in a global movement of cultural creators shaping a life-sustaining future

Through vivid storytelling, practical tools, and visionary frameworks, I lay out a new model of change—one rooted not in crisis response, but in collaborative design, personal growth, and radical imagination. If you've ever asked yourself, What can I actually do to help?—this book is your answer.

## About the book

I’m old enough to remember a time when people were excited about the future. The National Geographic magazine had stories about how we’d all be living on the Moon or in orbiting farms that would help feed the people on our planet. There was hope that we’d solve the problems we faced and we’d come out OK.

The feeling today is much bleaker. We’re faced with climate change and a whole slew of other problems and the future has become scary. My goal is to help you get excited about where we’re going as a species, and that’s what this book is about… in a way.

It’s not all about hope and inspiration, though that is certainly needed. It’s a practical guide. It offers actionable steps that we can all take. And you’re not going to hear me recommend that you plant a tree or start recycling. We all have much more to offer than that. Together we have immense power to create change and this book is about how we can harness that power to bring about the world that we want to live in.

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