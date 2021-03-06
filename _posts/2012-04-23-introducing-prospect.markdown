---
title: Introducing Prospect
author: Derek
layout: post
categories: technology
---

Have you ever wanted to add environmental impact data to your site? You've probably been too busy or don't have the resources to have a developer integrate your site with an API like [CM1](http://impact.brighterplanet.com). If so, we have good news for you! With our new service, [Prospect](http://prospect.brighterplanet.com/), you can add the power of CM1 (carbon footprints, resource usage, etc.) to your website with a *minimal* amount of coding! If you can edit HTML on a web page, you can be up and running with Prospect in minutes.

<!-- more start -->

![Prospect screenshot](/images/prospect.png){.wrapped}
For example, let's say you have an automobile sales site and you'd like to show your buyers what the yearly greenhouse gas emissions or fuel usage would be for each car on the page. Simply tell Prospect which HTML elements (using CSS rules) on the page provide input data that can be fed to our [automobile CM1 model](http://impact.brighterplanet.com/models/automobile), insert a special `<script>` tag on your page, and the environmental impacts will appear on your page. No need to hire a developer to integrate with CM1. Now your in-house web master or power-user can do it all.

An example of Prospect in action is at [http://prospect.brighterplanet.com/otto-s-autos](http://prospect.brighterplanet.com/otto-s-autos). Reload and notice how the footprints magically appear at the bottom of each car description. The only change needed on that page was to add a `<script>` tag at the top.

With Prospect we hope even more sites will be able to integrate environmental impact measurements and help all of us make greener decisions.

<!-- more end -->
