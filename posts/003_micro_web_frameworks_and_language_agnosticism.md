# Micro Web Frameworks and Language Agnosticism

[Back to the List](https://github.com/rziehl/from_the_terminal)

* * *

I am about to begin a side project that will be my most non-trivial personal
endeavour to date but there is still one question in my mind:

*Ruby's Sinatra or Python's Flask?*

I have used Sinatra on and off for a few years and I've been a Rubyist
for quite some time but I'm weary about labeling myself as a specific type
of developer. To me, developers should be able to adapt and continue to solve
problems whether their tools or environment change. Not to say that if you
do C your entire life and write tons of low-level utilities and servers in
that one language that you are a bad developer, that's not the case at all.
I think that for the majority of developers (especially in tech today),
flexibility is a key skill for success given how volatile the industry seems
to be.

So which language and micro web framework combination would it be for this
project?

First, I started by making a list of the Ruby gems and other tools that I use
often that I would not want to particularly abandon or could not live without.
I then split that list into language specific utilities and
language agnostic tools (some of which could be Ruby gems too). My list looked
like this:

<table>
  <tr>
    <th>Language specific</th>
    <th>Language agnostic</th>
  </tr>
  <tr>
    <td><code>gem</code></td>
    <td><code>git</code></td>
  </tr>
  <tr>
    <td>minitest</td>
    <td><code>foreman</code></td>
  </tr>
  <tr>
    <td>Bundler + Gemfile</td>
    <td>SCSS</td>
  </tr>
  <tr>
    <td><code>irb</code></td>
    <td><code>compass</code></td>
  </tr>
  <tr>
    <td>mocha</td>
    <td>Bourbon</td>
  </tr>
  <tr>
    <td>ActiveRecord</td>
    <td>ZURB Foundation</td>
  </tr>
  <tr>
    <td>Sinatra</td>
    <td>Memcached</td>
  </tr>
  <tr>
    <td>ERB</td>
    <td></td>
  </tr>
  <tr>
    <td><code>rbenv</code> + <code>rubybuild</code></td>
    <td></td>
  </tr>
</table>

As you can see the split is close to fifty-fifty which is pretty good.
Now with the list of gems that are specific to my language, what are their Python
equivalents? I researched for a while and found some suitable alternatives,
whilst doing so I also kept track of any doubts I had in my mind about
whether the alternative supported a certain feature (like ActiveRecord migrations
for example). Anything else I wasn't sure about with regards to Python I also
tracked on this same list. Here's the list of alternatives:

<table>
  <tr>
    <th>Ruby</th>
    <th>Python</th>
  </tr>
  <tr>
    <td>Sinatra</td>
    <td>Flask</td>
  </tr>
  <tr>
    <td>minitest</td>
    <td>unittest</td>
  </tr>
  <tr>
    <td>Bundler</td>
    <td>virtualenv</td>
  </tr>
  <tr>
    <td><code>irb</code></td>
    <td><code>python</code></td>
  </tr>
  <tr>
    <td><code>rdoc</code></td>
    <td><code>pydoc</code></td>
  </tr>
  <tr>
    <td><code>rdb</code></td>
    <td><code>pdb</code></td>
  </tr>
  <tr>
    <td>ActiveRecord</td>
    <td>SQLAlchemy</td>
  </tr>
  <tr>
    <td>ActiveRecord::Migration</td>
    <td>SQLAlchemy-Migrate</td>
  </tr>
  <tr>
    <td>Rakefile</td>
    <td>A python script?</td>
  </tr>
  <tr>
    <td><code>gem</code></td>
    <td><code>pip</code></td>
  </tr>
  <tr>
    <td>Gemfile</td>
    <td>requirements.txt</td>
  </tr>
  <tr>
    <td>mocha</td>
    <td>Mock</td>
  </tr>
  <tr>
    <td>ERB</td>
    <td>Jinja2</td>
  </tr>
  <tr>
    <td>Rack</td>
    <td>WSGI</td>
  </tr>
  <tr>
    <td>sinatra <code>configure</code> block</td>
    <td>Flask doesn't run code outside of routes on every request</td>
  </tr>
  <tr>
    <td>rbenv</td>
    <td>virtualenvwrapper</td>
  </tr>
</table>

Monday past was a statutory holiday so I decided to dedicate a full eight hours
to starting my project with Flask to satisfy my curiousity. All in all, I didn't
find too many noticeable differences. Sure things were new in Python somewhat
which slowed me down initially a bit but my process stayed the same. I found that
Flask "seems" to have a lot more extensions than Sinatra as listed [here](http://flask.pocoo.org/extensions/)
however at times I felt that Ruby's Standard Library documentation was easier to
navigate and a bit more useful than Python's. I like that the Python community
seems more diverse and their efforts have traction in more places than just the
web, not saying that Ruby is a one-trick pony but Ruby is very Rails dominated
still. I'm interested to see whether Python is less magical than Ruby and how close
to English I can make the code look compared to Ruby.

If I do switch over to Python for this project though, that doesn't mean Ruby is dead
to me. As I mentioned above, some of the gems that are part of my toolbelt can
be used for non-Ruby projects too. It's an interesting exercise to do as a
developer every now and then, even if you don't construct anything useful you
will still see how language dependent you have potentially become and if this
is the case, I urge you to pursue becoming a bit more flexible.

* * *

© Robert Ziehl 2013 | [Twitter](https://twitter.com/robziehl)
