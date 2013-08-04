# A Simple Git Powered Blog

[Index](https://github.com/rziehl/from_the_terminal) | [Twitter](https://twitter.com/robziehl)

I have three main needs for a blogging system:

* I write my posts in Vim
* My posts are formatted in Markdown
* I update my blog by pushing my posts to a Git repository

Basically I want to blog from my terminal using the tools I
already use daily. I know solutions like Octopress exist but
currently I just want something simpler.

In the past, I have written two blogging solutions powered by
Git: BitBlog and Hubnode. One used Bitbucket and the other used
Github. They would receive webhooks whenever I pushed to a
remote repository and then I would use their API to retrieve the
content of new and updated posts as well as delete posts that no
longer exist. BitBlog was a Sinatra application and Hubnode
initially used Rails (complete overkill but it was for the purpose
of learning).

I recently refactored Hubnode to use Sinatra and
completely overengineered it (again for the sake of learning).
It would receive webhooks with a SHA key as one of the params
to verify that my Github repository was sending the webhook.
After authenticating, it would spawn a background job with Sidekiq
that would make the API calls to Github to update my blog content.
It would also clear any cache (both cached views as well as cached
database query results in Memcached) and then precache those so the
very first request to those posts would be fast. Complete overkill,
but fun.

This is not a new concept by any means, in fact, I remember one
of my coworkers at my first job mentioning the idea of a Git
powered blog. However, after implementing my own versions I thought
up a simpler alternative:

* Create a Github repo
* Write some Markdown pages
* Push them

That's it. Github already renders Markdown nicely in my opinion, I
get code highlighting built in, I don't have to worry about a post
getting too popular and then a Heroku dyno gets overwhelmed by requests
because of a sudden increase in traffic. None of those concerns.
Oh did I mention no configuration? (Well apart from adding a remote and
an SSH key). This is the setup process:

* git init
* git remote add
* git add .
* git commmit
* git push

Sure, Github Pages exists and I will probably go down that road later
when I feel like getting more involved in frontend development but right
now I just want to write and share my thoughts.
