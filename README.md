#Skrifa

Don't read this.

I hate literally every single KB layout/website/system I've ever met and I wanted to make my own. After several empty threats of "I'm going to make my own damn KB", I finally decided to get drunk and do it. Some of it works, some of it doesn't -- I have no idea what I'm doing, so it may take a while.

Do whatever you want with it, but don't be a jerk.
Pull requests are totally welcome.

##Using This theme

These instructions assume you have a basic working knowledge of how to operate Jekyll. If you don't, read through their [documentation](http://jekyllrb.com/docs/home/).

1. Make sure you have Ruby, RubyGems, Node.js, and some non-Windows machine (Jekyll doesn't run on Windows without hacky stuff).
2. Get [Jekyll](http://jekyllrb.com/docs/installation/).
3. Fork this repo and then clone to your machine.
4. ```cd``` to your clone's directory.
5. Open up the project folder in your fav text editor and play away.
6. When you're ready to preview your site, enter ```jekyll serve``` in the command line from inside your project directory. It'll spit out the site some localhost port for you to look at.

Warning: If you make changes to config.yml, you'll need to restart the jekyll server to see the changes.

##Deploying
There are probably a million ways to deploy a Jekyll site, so you're on your own there. I wasn't able to get this theme to work on GitHub pages (there's some Ruby floating around in here, and I kept getting build errors so I gave up), but you can use other options, like your own web server, [divshot](https://divshot.com/), and I've heard rumors that you can deploy to [Force.com](https://developer.salesforce.com/page/Sites) sites.

## To do:

- Write Tag logic and display.
- Make search work better and not bork out when it's on article pages.
- Look in to ways to streamline breadcrumb nav. It's a bit cumbersome to set up. 
- ~~Add disqus feature.~~
- ~~Generate and add linked "Category List" to index.~~~
- ~~Figure out Breadcrumb nav. It'll be cool.~~
- Document _everything_
- ~~figure out how in the hell i ended up with two page.html files, and get rid of the _includes_ one.~~
- ~~make the CSS not suck.~~ it's never gonna not suck.
