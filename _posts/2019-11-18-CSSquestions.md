---
layout: post
title:  "CSS Questions"
date:   2019-12-08 16:48:13 -0600
categories: Roxanne Update
---


**What do you think of pre-compiling your CSS?**

I didnt notice that much of a difference, but maybe because I am just a beginner. I guess it is good to have nav, li, and a in a more compressed version. I can imagine larger sites getting too tricky with multiple css pages, so being able to compile with scss will come in handy.

**Compare to regular CSSWhich techniques did you use?Pros and cons?**

I compiled more elements to have similar qualities. The cons for me is compiling makes it harder to seperate things like font and color for certain parts of the site. The overall theme overrides the ability to have tact and be specific in a way.

**What do you think of static site generators?**

I think they are tricky. My Windows Pro had a hard time with Docker and Jekyll. Jekyll update did not work which annoyed me. I think SSGs are something I have to learn to master more. Also I kept wanting to update to the newer version of Jekyll 3.o and was annoyed we were stuck on an earlier version. I did a git --force to force something on Jekyll boilerplate to work and it ruined the whole site. It feels like solitions are invisible on SSG's Im lost when it comes to finding where the issue is when one arrises.

**What type of projects are they suitable for?**

Large scale websites for businesses, organizations, or just being able to put up a website quickly. It is useful if one is working in the tech department of an organization, because we would definitley be the ones testing on localhost before it gets published or goes live.

**What is robots.txt and how have you configure it for your site?**

Robots.txt is something every website has to control how bots and crawlers crawl through info and configure the info on search engines like google for example. Facebook.com for example has several bot configurations, because they prioritize being found by bing, google and the like. But my old company has disabled most bots from crawling on the page, and I think the priority for them is to prevent spam/auto bots from finding their number and calling the HR department non stop. It has multifaceted reasons for why a bot is allowed to go through a site or not. I configured it by essentially disabling all bots because I dont want my email to be too searchable on web search engines as the site will be going live and public.

**What is humans.txt and how have you configure it for your site?**

I added a humans.txt in the root folder where I put my author information. Humans.txt is like a personal stamp on websites to show that a human was there that created it. It is kind of like when humans landed on the moon and put a flag there, or a cat peeing on a bike to mark its territory. It is more just to have an official human stamp on the website.

**How did you implements comments to blog posts**

I used disqus which was quite a smooth implementation. I first configured settings on the disqus website, then embedded the comment coding in posts.html as well as in the individual posts.

**What is Open Graph and how do you make use of it?**




<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://roxacho-github-io-2.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>