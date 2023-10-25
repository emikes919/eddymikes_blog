---
layout: post
title: Man learns to code at tender age of 31
excerpt: (or how I turned two hours into three seconds)
---
<p class="sub-section">In this article:</p>

- [The Why](#the-why)
- [The How](#the-how)
- [Reflections](#reflections)
- [Resources](#resources)

My hand trembled with anticipation as it hovered over the enter key. Six weeks of hard work had led to this moment.

Sickened by months of manual Excel work, I had finally cobbled together a bloated code file that <em>might</em> be smart enough to do all of that mind-numbing work for me.

Emerging from hundreds of lines of code and countless squashed bugs, I found myself playing chicken with the enter key.

I'd come too far to back down, too far to cower back into the depths of manual data crunching. There was only one thing left to do:

*Smash that enter key and hope for the best.*

I was fairly sure this would work. But if I was wrong, back to code review hell I'd go to comb through my monstrosity in hope of finding and fixing yet another error.

Here goes nothing.

...*cocks gun noise*... **ENTER**.

There was a split second of utter stillness.

Then, the terminal sprang to life.

Progress statements ran down the screen like rapid fire, making me feel like a bona fide NSA hacker. Pretty baller.

About three seconds later, `done` printed to the screen.

Stillness.

The moment of truth was upon me. Did two hours of my life just collapse into three seconds?

All I had to do was open one Excel file to find out...

---

This is the story of how I <s>learned</s> <em>am learning</em> how to code.

Much like starting a blog, learning to code has long lingered in the back of my mind.

I finally pulled the trigger in earnest in late 2021, and one game of chicken with my enter key has left me more energized than ever almost two years later. 

Maybe this post will serve as inspiration to some of you who have been thinking about programming, but just need a little nudge to get started.

<p id="thanks-text"><em>Quick note on the title of this post: It always amazes me how often people don’t try something new because they’re “too old”. Life expectancies are rising, people. It’s never too late to start.</em></p>

<p class="main-section"><a name="the-why">The Why</a></p>

I finally pulled the trigger for several reasons:

1. I wanted to throw rocket fuel on my creative fire.
2. I wanted to challenge my 🧠.
3. I wanted to automate work.

<p class="sub-section">Creativity & Entrepreneurship</p>

As a recently [self-proclaimed wantrepreneur](https://eddymikes.me/2022/08/07/quitter.html){:target="_blank"}, I've quickly learned that entrepreneurship is difficult. Really difficult. 

The ability to keep stepping up to the plate is critical to success. 

There is no shortage of ideas that do not require software, but if I'm able to take on problems that can be solved with even the simplest technology-based* products, the universe of ideas explodes.

Programming skills at the prototyping level will put the raw power of creation my hands.

<p id="thanks-text"><em>*Note: “Technology-based”, for the purposes of this post, means any business where the product or service is software, or where the core value proposition is driven or enabled by software.</em></p>

<p class="sub-section">Problem solving</p>

Programming is very intellectually demanding and, at its core, is about problem solving. 

It's a way to push myself intellectually and become a better problem solver.

Programming is especially appealing because progress is not dependent on anyone or anything. I don’t need a teacher to schedule time with, waves to surf, or a team to play against. All the resources to learn are freely available, and I don’t need anyone’s permission to start writing code.

All I need is a computer and an internet connection.

<p class="sub-section">Automating work</p>

Having started my career in investment banking, I became quite the little Excel monkey.

An unintended side effect of my unnecessary level of Excel mastery was massive impatience for manual work and things taking longer than they should.

Like absurd impatience. Like <em>"relax bro, you're weirdly too impatient about this"</em> impatience.

Not really an issue when the entire job consisted of pumping out simple spreadsheets and charts for PowerPoint presentations.

But years later, when I found myself at a job that required much more manual data crunching than I was accustomed to, that impatience began to rear its ugly head.

To pile it on, my company had a large technology department, so I was constantly forced to watch in a potent cocktail of awe and agony as my developer colleagues automated away their manual work. All while I bitterly trudged through mine.

Spend enough time watching other people do something in a fraction of the time it takes you, and well… 

**Impatient guy sees better way to get things done, decides to learn how.**

<p class="main-section"><a name="the-how">Projects, baby! Projects!</a></p>

With most things, the most effective way to learn is through practical application. In programming land, that means building stuff.

What kind of stuff? Whatever floats your boat.

I’ve found the best projects a) pique your interest and/or b) can be implemented immediately with your current skillset or after learning a bite-sized amount of something new. 

That means start small.

<p class="sub-section">Project 1: Employ the robots</p>

Remember the heart-pounding opener to this post? Enter [Python](https://en.wikipedia.org/wiki/Python_(programming_language)){:target="_blank"}. 

Python is a popular programming language for automating Excel work and is the golden child in finance. Naturally, learning enough to automate some of my manual misery became my first bogie. 

I used [automatetheboringstuff.com](http://automatetheboringstuff.com){:target="_blank"} and was up and running with live Python scripts inside six weeks. These scripts migrated the responsibility of managing several manual processes from me…

…to my computer.

I know, I know. The suspense has been killing you. How did that game of chicken with my enter key play out?

I did indeed check that Excel file, and by what feels like some miracle, my enter key lost!

Two hours of my life did, in fact, collapse into ***three seconds***.

I cannot understate how good this feels.

Over the course of a few weeks, I automated several daily and monthly manual processes that previously consumed about eight hours of my time each month.

Think about that.

Approximately ninety hours of upfront investment (three hours of coding/day, five days/week, for about six weeks) to save eight hours of work per month. Payback in one year, and I’ve picked up a new skill that I can use forever. Seems like a good trade to me.

<p class="sub-section">Project 2: Roast the fellas</p>

My friends and I use [Groupme](https://groupme.com/en-US/){:target="_blank"} as our chat group. Luck would have it that Groupme has an open [API](https://dev.groupme.com/){:target="_blank"}, giving the programmatically inclined access to all of their own personal messaging data. 

My group chat has been in use for seven years, averaging 30 messages per day…

…methinks a closer look at the data is in order 🤔.

Enter my next project.

I used Python to gather our group chat’s entire messaging history from Groupme’s API, slice and dice it, and put it into a silly but illuminating presentation for the boys. The result was a twenty page deck pumped full of cute stats on my friends’ proclivity to absolutely roast each other.

They liked it, to say the least. 

Here’s a little taste of what is now an annual production:

![groupme-presentation-slide](/assets/images/groupme-presentation-slide.png "groupme-presentation-slide")

This project only required a minor extension of my Python knowledge into a few [new](https://pandas.pydata.org/){:target="_blank"} [libraries](https://pypi.org/project/requests/){:target="_blank"}* and functionalities that are handy for working with large datasets and APIs, and it was a logical next step following my Excel automation work.

Success working with Groupme’s simple API inspired me to see what other laughs I could generate at my friends’ expense… 

<p id="thanks-text"><em>*Note: A library is just a set of pre-written code that you can leverage to get common stuff done instead of reinventing the wheel.</em></p>

<p class="sub-section">Project 3: Roast one particular fella</p>

As it turns out, Groupme also offers chatbot functionality.

What if I created a bot in our chat group that singled out one friend of the chattier variety and programmatically roasted him every time he opened his digital mouth?

<div style="width:100%;height:0;padding-bottom:55%;position:relative;"><iframe src="https://giphy.com/embed/26BRBKqUiq586bRVm" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/americasgottalent-agt-americas-got-talent-26BRBKqUiq586bRVm"></a></p>

And off I went.

I used Python and learned just enough [Flask](https://flask.palletsprojects.com/en/2.2.x/){:target="_blank"}* to build and host a simple Groupme chatbot app that publicly roasted my friend with one of several snappy comebacks every time he sent a message over a certain length. 

Funny, it was. Pleased, he was not.

<p class="blue-box">These projects have two important traits that are worth harping upon for a moment. They <strong>1) brought me joy once completed and 2) brought me absolutely nothing until they were completed</strong>. Said differently, I was working toward something I wanted, and I didn’t get what I wanted until I saw it through to the end. It kept me motivated. Something to think about if you decide to pick up coding.</p>

Good progress so far, but at this point, I’m but a humble noob. These little projects were fun and undeniably advanced my Python skills, but my ultimate goal is to prototype web-based software.

<p id="thanks-text"><em>*Note: Flask is a web framework for Python. Similar to a library, a framework is bunch of pre-written code that helps you build web-based apps quickly, from as simple as a Groupme bot to the much more complex.</em></p>

<p class="sub-section">Project 4: You’re reading it</p>

I wanted to start with an easy first website project, and I wanted to start writing more for aforementioned [reasons](https://eddymikes.me/2022/08/06/why-i-started-this-blog.html){:target="_blank"}.

…incoming message from Captain Obvious…

<br>

*Dear Ed,*

*You should build and launch your own blog.*

*You’re welcome,*

*Captain Obvious*

<br>

A blog it is then.

The blog you’re currently reading was surprisingly easy to get up and running and involved the following:

1. Picked a domain
2. Sketched out a simple design
3. Learned just enough [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML){:target="_blank"} & [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS){:target="_blank"} (see the [Odin Project](https://www.theodinproject.com/){:target="_blank"} below) 
4. Learned just enough [Jekyll](https://jekyllrb.com/){:target="_blank"} (a popular blog site generator)
5. Built the site using HTML, CSS, and Jekyll
6. Hooked up my domain to [Github Pages](https://pages.github.com/){:target="_blank"}, and hosted the site
7. Started writing (hardest part)

It was a great project because it hit all of my criteria:

<ul class="no-bullet-list">
    <li>✅ Piqued my interest</li>
    <li>✅ Required me to reach slightly beyond my grasp</li>
    <li>✅ Generated zero payoff until completed</li>
</ul>

The whole exercise took about six weeks. Not bad.

<p class="sub-section">What’s next?</p>

With a solid understanding of the fundamentals in place, I felt comfortable advancing to the next level of difficulty. To do anything remotely advanced on a website, another programming language is required: [JavaScript](https://en.wikipedia.org/wiki/JavaScript){:target="_blank"}, the third core technology of the internet. It makes things come alive on a webpage and is a critical component of all web applications.

So, my programming journey thus far can be summarized as follows:

**Python → HTML → CSS → JavaScript**

I’ve learned a tremendous amount, but the material I have yet to cover is immense. The plan is to stay on theme and take on projects that hit all of my criteria.

I have an app idea in mind. It’s a daunting project, but it will act as a guiding North Star as I navigate the never ending universe of programming. 

<p id="thanks-text"><em>Note: All of the above probably seems like a lot, and it is. Programming is a huge time commitment. But I'm not programming every single day. It ebbs and flows with my work load. There have been month-plus long periods where I haven’t been able to think about coding. No deadlines. Learning is a lifelong journey.</em></p>

<p class="main-section"><a name="reflections">Reflections</a></p>

So that’s where I’ve been, how I got there, and where I’m going. Here are the big things that come to mind when reflecting on my journey so far. Worth considering before you decide to take it on!

<p class="sub-section">Programming is satisfying</p>

Code gives you the power to sit in front of your computer and create something useful in the real world, no welding skills required. If you can dream it up, you can probably build it.

That power of creation in your fingertips is intoxicating. The more you learn, the more enjoyable the process of learning becomes, and the faster the idea flywheel spins.

<p class="sub-section">Programming is difficult, frustrating, and time consuming…</p>

Make no mistake, programming is not easy.

This is largely because it’s completely digital and pretty abstract. Also, the scope and complexity of material necessary to be dangerous as a programmer is massive. It takes a long time and a lot of effort learning seemingly rudimentary concepts just to get to the beginner level. I’d venture to guess this is a common reason people don’t even start.

Expect to get stuck on things constantly, sometimes for days or weeks at a time, feeling like you’re making no progress (in reality though, you’re learning).

The ability to succeed is highly dependent on one’s ability to stay motivated when it gets dark. This is why your reasons for learning to program and whether it naturally energizes you are so important.

There’s much more to why and how programming is difficult, which you can read about [here](https://www.thinkful.com/blog/why-learning-to-code-is-so-damn-hard/){:target="_blank"}. 

<p class="sub-section">…but not as hard as people tend to assume</p>

Having said all that, putting one foot in front of the other will get you there, and at least through the intermediate level, it’s mostly a matter of dedication and consistency. 

A lot of programming’s difficulty can be overcome by the simple act of chipping away at it.

There's nothing holding you back. It’s just you, your computer, and your desire to learn.

<p class="main-section"><a name="resources">Free resources I used to get going fast</a></p>

I've explored **a lot** of coding content. If you do decide to jump into programming, I recommend checking out these resources.

<p class="sub-section"><a href="http://automatetheboringstuff.com/" target="_blank">Automatetheboringstuff.com</a></p>

I cannot recommend this highly enough for beginners. It is an EXCELLENT starting place for learning Python.

Nothing but a free online textbook that explains concepts well.

It’s worth reiterating the point about my game of chicken: <strong>*from nothing, I was up and running with value-adding scripts in six weeks using this resource alone.*</strong>

Python is a great starting language because it’s modern, intuitive, and widely used with endless resources and community support. It’s also a very powerful language that can do a whole universe of things beyond automating some of your busy work, including build very scalable web applications.

However, if you aren’t particularly interested in learning Python but want to learn to build web apps, an equally good place to start is The Odin Project. 

<p class="sub-section"><a href="https://www.theodinproject.com/" target="_blank">The Odin Project</a></p>

If you want to learn web development as a beginner, The Odin Project is the 🐐. Full stop.

The creators assume you have zero programming knowledge and take you through everything you need to know to build a [full stack](https://www.geeksforgeeks.org/what-is-full-stack-development/){:target="_blank"} web application from square one. 

That means it is an extremely comprehensive resource that requires months of investment to understand and complete (I still have a ways to go).

Having said that, you start seeing results almost immediately. The speed at which I was able to spin up some basic, but decent-looking websites was shocking (here’s a [fun one](https://emikes919-battleship.netlify.app/){:target="_blank"}). You are constantly building a portfolio of work as you advance which serves as a nice reward and motivation to keep going.

They give you just enough to keep you going while still forcing you to struggle a bit and figure out a lot on your own (a huge part of programming).

And yes, it’s free.

<p class="sub-section">YouTube</p>

I don’t think enough people realize what a goldmine of knowledge exists on YouTube.

If you want to learn it, there’s someone on YouTube waiting to explain it to you like you’re a small child. Over and over again to your little heart’s content.

This is especially true for programming. YouTube videos have been the sole reason I’ve gotten “unstuck” on many occasions.

Some favorite channels I’ve used include [Fun Fun Function](https://www.youtube.com/@funfunfunction){:target="_blank"}, [Wes Bos](https://www.youtube.com/@WesBos){:target="_blank"}, [Kevin Powell](https://www.youtube.com/@KevinPowell){:target="_blank"}, [Web Dev Simplified](https://www.youtube.com/@WebDevSimplified){:target="_blank"}.

<p class="sub-section">Google</p>

Anyone who picks up coding will come to find that 90% of your time is spent on Google, not in your code editor. 

As a beginner, there is a 100% chance that whatever problem you’re facing has been solved before. Google will take you to the solution.

That solution usually exists on [stackoverflow.com](https://stackoverflow.com/){:target="_blank"}, the Mecca of coding discourse, but can also be found on a long list of great programming websites and forums that Google will find for you.

A lot of becoming good at programming is a function of how good you become at Googling stuff. The specifics of what you search for can result in huge differences in the time spent solving your problem.

<p class="sub-section">My Fiancée</p>

Sarah is a self-taught former integrations engineer and now product manager, having cut her teeth on [Java](https://en.wikipedia.org/wiki/Java_(programming_language)){:target="_blank"}, [Node.js](https://nodejs.org/en){:target="_blank"}, and Python. She is an absolute machine. 

Having her around to graciously get me “unstuck” countless times has really sped things up. I question the judgement of anyone who wouldn’t hire her.

Yes, this is a huge leg up on anyone learning to code in a vacuum, but hey, I’ll take it.

<p class="sub-section">⚠️ Avoid: Codecademy</p>

Those seriously contemplating the programming journey will have no doubt stumbled upon [Codecademy.com](https://www.codecademy.com/){:target="_blank"}.

I must recommend against it.

Set aside that fact that it isn’t free (I have used the paid version), it falls short in one critical area: **Codecademy forces you to write code in their online environment which is not transferable to the real world.** 

As frustrating as it can be, the payoff of struggling to figure out the day one fundamentals on your own computer is huge. I think Codecademy robs students of this opportunity to “figure it out”.

You aren’t required to do any of the dirty work of installing various dependency software and navigating the underbelly of your operating system that’s required at every level of programming in the real world.

I understand why this may be appealing to some people, but I believe it is a sub-optimal way to learn.

---


And voilà. Now you know how one game of chicken with my enter key led to an eighteen month (and counting) hobby. Those months feel like years when I think about the ground I’ve covered. 

Nevertheless, it’s a little scary to re-anchor my perspective back to how much of a beginner I still am and to think about what I’ll have to conquer to get where I want to go.

A long road ahead, indeed.

Looking down that road may be intimidating, but that fear seems nonexistent next to how excited I am to walk down it.

And that, dear reader, is a good sign if I’ve ever seen one.

<p id="thanks-text"><em>Thanks to Sarah and Julian for reading a draft of this post.