# The Fifth Degree of Package Management

[Back to the List](https://github.com/rziehl/from_the_terminal)

* * *

I'm a huge proponent of package management tools. I would not consider
working without the rbenv/rubybuild combo for any of my development
machines if I was doing Ruby development. Every project I write that has
third party dependencies gets a Gemfile. Even my rake command is aliased
to ```bundle exec rake``` to enforce this, no exceptions. Dependencies 
listed in my Gemfile are always hard locked to specific versions too and 
that's what I really love about all of this. I could leave a project for
a decade, come back to them and as long as RubyGems is still online by
that time then I don't have to resolve the dependencies manually at all,
I could have my old project up and running in minutes if not seconds.

New developers often skip installing tools like this which I consider
fairly crucial. We remove the Ruby that came preinstalled with our operating
system, install an updated version for all users on our system, learn the
hard way when we try to upgrade again later and eventually get introduced
to a tool like RVM or rbenv.

I think we have seen an increase in the number of package managers over the
last few years which I fully appreciate. I dabbled with some Objective C a
few weeks ago and was presently surprised to stumble across Cocoapods, a
blatant Bundler clone for iOS/OSX project dependencies. Cool I thought, this
is just what I wanted. I had FlatUI up and running in my iOS project quickly.
In my spare time, I still actively do a lot of web development despite being
a full time mobile developer. I recently found out that package managers were
making their way to frontend web development in the form of a utility called
Bower. Again, awesome!

However, I keep having mixed feelings each time I install a new package
manager. This diagram will explain where I'm coming from:

![Package Manager Installation Tree](https://github.com/rziehl/from_the_terminal/blob/master/images/002_package_managers.png?raw=true)

This is the order in which I installed various package managers to get to
where I am now on my development machine. As you can see, I recently got to
the fifth level of these tools, isn't this getting a bit ridiculous?

1. I started with rbenv to manage Ruby versions
2. I then installed Bundler (with ```gem install```, which arguably makes this two steps not one)
3. With Bundler I then installed Homebrew
4. To get Bower, I needed to installed the Node Package Manager (```npm```)
5. Now I can finally install Bower

I know these steps could be skipped to get to Bower faster but this shows
the evolution of my development environment and I'm sure I'm not the only
one to traverse this path. I understand the process of bundling code is
different for each programming language but package management and dependency
resolution seems like a problem that should be generic enough to abstract
away into a standard format. I'm sure there are plenty of challenges and
edge cases as always but I can't help but think we keep reinventing the wheel
here.

* * *

© Robert Ziehl 2013 | [Twitter](https://twitter.com/robziehl)
