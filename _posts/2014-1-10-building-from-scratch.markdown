---
layout: post
title: "Building From Scratch Then Scratching That Build"
---

Over the past couple of weeks I've been working hard on building my own website. I actually began this work last summer, in the midst of a code camp for humanities graduate students being run at U.Va. with the great help of [Scholars' Lab][1] staff. There, I had gotten an intro to git, found out about [Github Pages][2] and [Jekyll][3], and had learned enough PHP to build a couple different WordPress themes throughout July and August. But, I was never happy with what I had produced and when school started back, my priorities shifted. When the holiday break began, I knew I needed to go ahead and get something up and running. 

I decided to host the site with Github Pages using Jekyll for a couple of different reasons. One, it's free and I'm a humanities graduate student. Two, I wanted my site to be focused around blog content, and Jekyll will auto-build a blog from your markdown files. I have written nearly everything over the past six months in markdown, so this fits well with my current habits and preferences. And three, hosting through Github Pages has made using git and the terminal a comfortable habit, all to the betterment of my future.  

This still left the question of what to build and how to build it. Throughout the year, I had spent time looking at different frameworks and boilerplates. I checked out the [HTML5 Boilerplate][4], browsed through [Bootstrap][5], and looked at a number of different grid systems, such as [Skeleton][6]. A number of these different frameworks and systems fit the design aesthetic I like - minimal clutter, clear navigation, focus on text and typography and the like. As I said in [my previous blog post][7], I decided to build it from scratch, thinking that the design I had in mind and had sketched out was pretty simple to code. And it was, mostly. I built a blog site with a left sidebar navigation menu taking roughly 2/5 of the page with the rest displaying the blog content. I used [Adobe Kuler][8] to help generate a color scheme I liked. I spent quite a bit of time looking at typography. Wanting to keep up with the times, I made the whole thing responsive and wrote media queries to shift the navigation menu to the top at an appropriate breakpoint, and though I still needed to iron out some positioning and spacing kinks, it all worked. But there was something missing, some bit of polish and clarity that you find in great websites today. That's when I realized that minimalism isn't necessarily easier to code. The basics of the layout and style were straightforward, but when there is less on the page, every detail matters, and to code those details, those little bits of spaces, calculating the proper ems and such, that would take time. 

Unfortunately, time is not necessarily what I have in abundance. With the spring semester starting, my dissertation looms especially large, as does planning for the course I'm TAing and preparing for our work in [Praxis][9] on Ivanhoe. In the interest of pragmatism, I decided several days ago to scratch my built from scratch build. I want my site to show a bit of my coding ability, but I also want it to meet a certain standard. My own build isn't quite there, though given some time I'll have it there one day. I decided, though, to rebuild using the [PureCSS Framework][10]. It's a set of CSS modules that can be used all together or pulled apart. To get the layout and appearance I wanted, and still be responsive, I decided to use one of their layouts similar to my own. I worked off of the framework and adapted it to the templates that Jekyll needs, done with the [Liquid][11] templating language, to get content to display where and how I wanted it. I then started changing things a bit with my own CSS, using the color scheme I had decided on to style the links, to change a bit in the menu, to change spacing, and then put in my own font choices. I hooked in [Font Awesome][12] to get icons for links to my Github and Twitter pages. The whole time, I used git to track the changes I was making  (as my [commit history][13] on Github shows) and ran Jekyll locally to know what was going on.

There are still things here and there I want to tweak, such as spacing, but the website is up and running at [csbailey.org][14]. 

And I learned this lesson, which I think has been dwelling in the back of my head for some months. The website that is up and running is better than the built from scratch website that sits on your computer, never to be seen by anyone else. 



[1]:	http://www.scholarslab.org/
[2]:	http://pages.github.com/
[3]:	http://jekyllrb.com/
[4]:	http://html5boilerplate.com/
[5]:	http://getbootstrap.com/
[6]:	http://www.getskeleton.com/
[7]:	http://www.scholarslab.org/grad-student-research/building-a-website-and-pulling-apart-wordpress-plugins/
[8]:	https://kuler.adobe.com/create/color-wheel/
[9]:	http://praxis.scholarslab.org/
[10]:	http://purecss.io/
[11]:	http://docs.shopify.com/themes/liquid-basics
[12]:	http://fontawesome.io/
[13]:	https://github.com/csbailey5t/csbailey5t.github.com/commits/master
[14]:	http://csbailey.org/