---
layout: sidebar-page
title: Recommended Reading
eleventyNavigation:
  key: Recommended Reading
  parent: chapters
  order: 20
tags: book
navKey: book
---
{% section %}

# Recommended Reading

### _Operating Manual for Spaceship Earth_

By Buckminster Fuller

### _Thinking in Systems: A Primer_

By Donella H. Meadows

### _The Men's Group Manual_

By Clyde Henry

### _The Practice: Shipping Creative Work_

By Seth Godin

### _Active Hope_

By Joanna Macy and Chris Johnston

### _The Evolving Self_

By Mihaly Csikszentmihalyi

### _The Infinite Game_

By Simon Sinek

### _The Permaculture City: Regenerative Design for Urban, Suburban, and Town Resilience_

By Toby Hemenway

### _Be a Changemaker: How to Start Something That Matters_

By Laurie Ann Thompson

### _A Pattern Language: Towns, Buildings, Construction_

By Christopher Alexander, Sara Ishikawa, and Murray Silverstein

### _The Timeless Way of Building_

By Christopher Alexander

### _Finite and Infinite Games: A Vision of Life as Play and Possibility_

By James P. Carse

### _The Beginning of Infinity: Explanations that Transform the World_

By David Deutsch

## Resources

Each chapter in the book introduces ideas designed to help you take action toward building a world that works for all life. Here, you’ll find books, websites, and tools that can help you go deeper into those ideas—curated to support your creative practice and your journey into the Great Collaboration.

### 📘 How This Page Works

Resources are organized by chapter so you can easily explore what interests you most.

We include books, articles, videos, websites, and tools aligned with the principles of evolutionary design, creative practice, systems thinking, and cultural regeneration.

This page will continue to grow as we discover new materials and receive recommendations from the community.

### Chapter-by-Chapter Resources

<ul>
  {% for resource in collections.allResources %}
    <li><a href="{{ resource.url }}">{{ resource.data.title }}</a></li>
  {% endfor %}
</ul>

### Suggest a Resource

If you know of a book, tool, or article that aligns with the principles in Don’t Save the World, you can suggest it using this form so we can continue building a rich, evolving library for cultural creators everywhere.

### Get Updates

Want to know when we add new resources? Join our newsletter here.

{% endsection %}