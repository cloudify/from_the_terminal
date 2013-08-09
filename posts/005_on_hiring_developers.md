# On Hiring Developers

[Back to the List](https://github.com/rziehl/from_the_terminal)

* * *

It seems all developer positions these days require the following:

* A link to your Github account
* A link to your LinkedIn profile

I'm going to address each of these individually.

My Github page is fairly sparse compared to some people but I am not
about to upload every side project I have ever worked on just for the
sake of increasing my repository count. It surprises me how many
developers I have spoken to who have never even heard of Bitbucket,
which offers free unlimited private repositories. This is actually
where the majority of my code sits. Some of it I have spent weeks on
and would probably look pretty good on my Github profile but I am
not about to give it away because some of it could be turned into an
actual product one day.

I'm not against open source by any means but
if you subscribe to the Church of Stallman and believe everything
should be free (as in speech) and you insist that others do the same,
then understand that you are no different from a religious missionary
visiting Africa indoctrinating the locals there with your beliefs
and stripping away their culture whilst masking your intents
with this wonderful idea that what you are doing is for their best
interests. Now I am not saying all charitable efforts are like this,
but the ones that are like that make me sick to the stomach. Free
software fanatics who close-mindedly try to bludgeon others into their
beliefs are no different. They have decorated their harmful intentions
to strip people of their freedom to choose how they should license or
source their software with these beautiful ideals like freedom. Many
of them do not actually realize that are being so hypocritical and
truly believe that they are doing others a favour.

Here is my view on the matter: if you did not put in the time and you
did not pay that person for their time, you have no say in the matter.
It is as simple as that. Time is a valuable resource and I find it
very arrogant that people dictate how people should distribute their
software having not spent any time writing that code. You gave no time.
The common rebuttal is that Stallman gave a lot to the community,
therefore he can dictate to others how they should release their projects.
No, he spent lots of time on his projects and licensed them as he wanted,
now let others do the same, that is freedom. Yet now the whole industry
is sold on Github profiles as the best way to determine good candidates.

I agree that it holds some merit, but in the same sense that hours worked,
lines of code typed, commits pushed and bugs solved all have some merit.
If you think they are perfect metrics to rank people on you clearly do not
see the flaws in the system. Look at Julython, a month long Python
hackathon. It is a cool idea but the winner is determined based on number of
commits. It's not about winning but still.

I know why companies have bought into the idea of Github profiles. It is a
neat way to filter out poor candidates. Understand though that Github does
not differentiate between developers on it's platform therefore your filter
does not guarantee good candidates, your filter guarantees candidates that
are on Github. This does not mean you will see a user's best work or even
a user's own work for that matter. I have seen Github profiles that have
eighty or more forks of various other projects purely for the sake of backing
them up, no contributions and maybe a Github Pages site or a dotfiles repo
and that's it. Now at a far glance, their profile would look better than mine
but your recruiting staff still has to sift through that data and actually
find out how much work that person has done of their own. Oh wait, not all
of that user's work is on Github necessarily, so even after you have analyzed
their repositories you still have no definite metric for success yet. But
you can't take a bet on someone if you haven't seen their work? I will address
that in a moment but I want to touch on LinkedIn for a bit before providing
some of my own advice.

LinkedIn honestly does not feel like a welcoming platform and I think it's a
very poor way to showcase yourself. Immediately at the top of the page, they like to list
equally redundant statistics like number of connections. Understand that the
number of connections is like your Twitter follower count, it actually means
very little in the grand scheme of things, how many recommendations do you
have on LinkedIn? What's that ratio between recommendations and connections?
How many of your connections are actually connections who you can rely on and
how many of those recommendations are reliable enough to fall back on in times
of need? I started tweeting this year and set myself a goal of one hundred
followers by the end of the year. A few weeks ago I realized how ignorant that
was. The catalyst? I met with a friend of mine who I have worked with before
and we caught up. Last year was filled with highs and lows for me, more so than
most other years and I began to question if what I was doing was right anymore.
My friend who I had a lot of respect for, as a developer, a thinker and a person
said that he had a lot of respect for me. It isn't often that someone you have
a lot of respect for says that to you and that really hit home for me. I knew
I must have been doing something right if he was saying that. That made that
whole night and that to me was what a true connection is. Not some number on a
website that everyone uses just because everyone else uses it. You will not
get that kind of experience, this is interaction with real people in person.
These are real connections but yet again you have put up another filter, which does
not necessarily filter out good or bad candidates but it filters out people
without LinkedIn.

Another turn off is the job description itself. I started off my
[last post](https://github.com/rziehl/from_the_terminal/blob/master/posts/004_true_startup_culture.md)
taking a stab at those hip startups in the Valley and I think they are doing it
wrong. I also think companies that list every possible technology ever invented
are doing it wrong too. If you want to see what a good job listing looks like,
check out [Hashrocket's careers page](http://hashrocket.com/contact-us/jobs/developer).
They are looking for people who are
[language agnostic](https://github.com/rziehl/from_the_terminal/blob/master/posts/003_micro_web_frameworks_and_language_agnosticism.md)
and who value principles and qualities over the names of technologies. Also, take a look
at the positions listed, there are three. No meaningless and overly superfluously long
titles that make a position's role hard to understand. Simple and straightforward plus
that has already shown me a lot about their company values.

Now onto the interview process which normally starts off with someone asking me
to tell my story mostly because they did not bother to read my resume (some more
obviously than others). For some of them, I wonder if that LinkedIn work experience
section even got scrolled through. Why did you want a cover letter again?

Anyway, onto the technical interviews, the part that developers have been waiting
for. What do you actually do during your technical interview? Do you quiz candidates
with impractical brainteasers or do you actually look for the one thing you
should actually care about at this stage? Their work process. Understand that their
Github and LinkedIn will not show you how they truly work. They are in your offices
now and you have a valuable window of opportunity to see how this candidate actually works.

So ask them to do this in an hour or two, code something. No, not code this specific
thing just give them those two words "code something". Provide a list of fun ideas
as well (say a dozen or so just in case). Let them bring their own laptop with them
into this part of the interview and if they have a desktop at home use TeamViewer
to watch them work remotely if you have to. But I will tell you right now that with
this exercise you will not need a full two hours to see if this candidate is right
for your company or not. Observe their development environment, are they a GUI guy
or do they favour the command-line? What customizations have they done to their
terminal? What Vim or Emacs plugins are they using to improve their process? Are
they using source control? Are they thinking ahead as they code? And also watch what
happens when they get stuck. Do they Google the answer? Do they immediately check
the Standard Library Documentation? Do they pop out of their text editor and type
`rdoc` or `pydoc` into their shell? Do they fire up an interactive REPL with `irb`
or `python`? Like I said, you will quickly see how mature this developer is and how
they function instead of asking them to write a binary sort on a piece of paper or
asking them how many windows there are in San Francisco. Don't waste their time
and don't waste yours.

Good developers will maintain their process as their tools change, they will find
equivalents and the process they demonstrated during that coding session is what
you probably will get whilst they work for you.

* * *

© Robert Ziehl 2013 | [Twitter](https://twitter.com/robziehl)
