# The Node.js community on IRC

**Hit a problem using Node.js?**<br>
**Confused about how to use a module?**<br>
**Maybe you just want to profess your love for Node.js?**

The Node.js IRC channels are vibrant gatherings of *volunteers* that want to make 
Node.js and its friends the best platform available on ALL operating systems!
<br>
<br>
**Are you a rookie?**<br>
**Just getting starting?**<br>
**A bit nervous to ask a question that might be silly?**

Don't worry- most people feel that way initially. To make Node.js even more 
super awesome, it requires new people come on board. And we all understand 
that they *may* have silly questions. It isn't a big deal- but there are a 
few things you should know before you jump in. Here we go...

## World Wide!
The Node.js community is global. It is very important to realize that your mid 
afternoon crisis is happening at 3AM for others! There is no time-of-day that is 
"best" to seek help.

## What to expect
The channels are open to all. That includes experts, novices, noobies, and... of 
course the occasional smart ass, jerk, hater, troll ...etc. The channels 
are moderated by several volunteers living all around the world. In the inevitable 
case of a misbehaving member, they will step in and resolve the issue to ensure 
the community keeps a positive vibe.

Everyone in a channel is there on his or her own free will. No one is *required* to 
help you. Most people just have the channel open, are mostly silent, but enjoy 
multi tasking and helping whenever they can.

Many module authors are connected but have their IRC client running in the 
background. If you have a question about a specific module, it is better to ask 
your question to everyone and not directly to the author. Module authors are 
volunteers too! They may be busy at the moment.

> TIP!: A question asked directly to someone will be ignored by everyone else!

> TIP!: NEVER ASSUME A NON-RESPONSE IS VICIOUS!


## Asking for help
I'm going to unofficially declare *RULE #1:* Ask Google first.

If your answer is easily found on Google do not ask in IRC. If you haven't put 
in a reasonable effort to resolve the issue on your own- you'll just irritate 
people. Volunteers want to *help* you- not *work* for you.

### Help everyone help you!
The more detailed and well prepared your question is the more likely 
you are to get help.

The more complicated your scenario is, the more detailed you should be.
(example: https://gist.github.com/williamwicks/6477189)

#### Isolate your problem first
The example above was something I experienced in a large application of mine. 
It took me several hours to create that whittled down use case that removed 
all unnecessary code possible. I focused on making it as easy as possible 
for others to follow and work with. The result: some gracious folks *did* 
run the code and ultimately surfaced [a confirmed bug](https://github.com/joyent/node/issues/6203).

#### What not to do
Here are some common questions that will generally will go ignored:
* "Can someone help me?"
* "Can I ask a question?"
* "Hey, does anyone here have experience with Express?" (or other thing)
* "What's wrong with this code: &lt;big blob pasted in&gt;"

#### A good example
> I'm having a problem with socket.io. I've searched google for the error 
and cannot find anything. When I call this.emit('foo') I getting the error 
'<Object> does not have a function emit()'. You can see my code here: 
http://pastebin.com/asdf1234"

*(That is a completely made up example. Send me a PR to suggest a better one!)*

Here, a simplistic high-level overview starts the question and then ends 
with a way for a volunteer to click a link to a well-know service to examine 
the details.


### Be on topic
It's very very OK to be a rookie! Often when you're getting started, you're 
confused about what-is-what and don't know where to start. We've all been there!

If you are told to "Go ask in channel X!"... do not get offended often you'll 
discover that the channel you're referred to will do a much better job.

For example: People often ask C/C++ questions in the #Node.js channel. Although
it may be related to #Node.js the channel doesn't discuss it often or in great 
detail. You may get more love in `#libuv` or `#v8`.

####The #Node.js channel has a few cousins:
##### #libuv
Node.js strives to run on all platforms. Node.js provides a platform agnostic API 
to Operating System functions. To accomplish this, Node.js delegates things to the 
`libuv` library. If you are having low-level operating system issues, this may be 
the place you want to ask.

The members here frequently need to work with v8 and are often very knowledgeable 
about v8 (in the context of Node.js) also.

##### #v8
Node.js uses the v8 Javasript engine. This means we rely on them to bring new 
Javascript features to Node.js. It also means bugs/quirks trickle into Node.js.

*Very important to know:*
V8 is a google backed product that is primarily focused on Google products. You 
may not get love if you ask about a specific Node.js issue. DO NOT HATE THEM 
(Google) FOR THIS! They are doing amazing things that Node.js is able to leverage. 
Be grateful for this gift. They have no obligation to cater to the Node.js 
community. (And that's OK!)

You should probably have a decent knowledge of v8 if asking here.


