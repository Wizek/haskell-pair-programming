[![Come chat on Gitter](https://badges.gitter.im/haskell-pair-programming/Lobby.svg)](https://gitter.im/haskell-pair-programming/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Rules

0. Tell everyone about the club.
1. Join [the chat](https://gitter.im/haskell-pair-programming/Lobby). You will
   obtain collaborator rights to edit this file. Or someone will help you to
   edit the file.
2. Add short contact info into the summary table and verbose info as a separate
   section below. Keep alphabetical order.
3. There are two chats for find partners:
   + **[quick connections](https://gitter.im/haskell-pair-programming/QuickConnections)**
     to find a partner withing 30 minutes time window
   + **[the main chat](https://gitter.im/haskell-pair-programming/Lobby)** to
     find someone for a longer partnership or for general discussions.
4. Nicknames in chat rooms and should match to names in this list.

## Summary table

|                                           | Level                 | Preference                  | Time                                       | Language |
| ----------------------------------------- | --------------------- | --------------------------- | ------------------------------------------ | -------- |
| [aggie0](#Aggie0)                         | begginer-intermidiate | cat theory, dependent types | US, flexible                               | en       |
| [attilah](#attilah)                       | beginner-intermidiate | -                           | ? flexible                                 | en       |
| [echatav](#echatav)                       | intermediate-advanced | reflex, ghc, squel          | Pacific time, flexible, better 4pm Mondays | en       |
| [kevroletin](#kevroletin)                 | beginner-intermidiate | -                           | UTC+10 flexible                            | en,ru    |
| [kmett](#kmett)                           | expert                | own projects                | EDT (UTC-4) weekends, and some evenings    | en       |
| [sh4rk1z](#sh4rk1z)                       | beginner              | GMT+3                       | Learning a book                            | en       |
| [tech-learner-maker](#tech-learner-maker) | begginer-intermidiate | hledger                     | GMT+5.30, 5-8pm or 12-2pm                  | en       |
| [therealjohnfreeman](#therealjohnfreeman) | beginner              | book exercises              | Texas, evenings and weekends               | en       |
| [wizek](#Wizek)                           | intermidiate          | reflex, hs-di               | UTC+2 flexible                             | en       |

## aggie0

1. Availability

   I'm in grad school in the US, so most times work for me (as long as it's not
   in the middle of the night in the US).

2. Experience

   A year-ish, don't know much about most language extensions, but I've written
   a ~1k LOC library for doing some category theory calculations.

3. Interests

   Anything can work, maybe we can alternate. I'm really interested in
   dependently typed stuff (Idris, Agda). I also have an open source library for
   some math stuff we can hack on.

## attilah

1. Availability

   I'm available at any time this week. We can even schedule a session right
   now.

2. Experience

   I started learning Haskell since about 2012. But it's been more of a on/off
   kinda thing.

3. Interests

   I'm open to pairing on any project/codebase.

## echatav

I enjoy pair programming.

1. Availability

   Flexible but say 4pm Mondays Pacific time to choose something specific.

2. Experience

   4.5 years, intermediate to advanced

3. Interests

   Definitely interested in learning Reflex. Interested to learn GHC's codebase.
   Or we can hack on Squeal.

## kevroletin

1. Availability

   UTC+10 VLAT 9am - 12pm

   I have a very flexible schedule and generally, I am available at any time
   during my day. From time to time I have activities which can't be rescheduled
   but most of the time it's easy for me to be available. But due to my time
   zone, it can be hard to connect with people from Europe or America.
   Australia, Japan, China, and India are much easier.

2. Haskell level of experience

   I am a (advanced?) beginner haskeller who is trying to pass "mythical middle
   level" which every Haskell programmer somehow passes without speaking much
   about it :) Before that, I've been programming with different popular
   languages including C++ and Java.

   I am quite comfortable with basic everyday constructs (i.e. Monoid .. Monad,
   typeclasses, ADT, basic lenses, basics of streaming libraries and I had
   several chances to apply profiling tools). I didn't touch type-level
   programming (including GADT).

3. Interests

   Anything goes. As long as it's Haskell, I'm in :)

   But I don't have experience with pair programming. I mean at my previous job
   we did short "uni-directional" sessions when you come to help a newbie, or
   you are a newbie and someone helps you. But we were never meant to actually
   develop stuff together.

   Also, I have thoughts about tasks planning and knowledge organizing using
   plain text files (emacs ord-mode, etc...). So if someone wants to start a
   small silly project, or want to work with existing tools, that will be
   interesting for me.

## kmett

I've had good success with using pair programming as a sort of "forcing
function" to drive me to complete a bunch of tasks that would otherwise sit in
my back burner for a long time. I'm opening to trying the experiment on the
internet at broad. I've been debating about that or doing live streams or
something to serve the same purpose, as it'd force me to set aside a fixed time
window to work on these things.

1. Availability

   I have pretty good availability on the weekends, and some evenings EDT
   (UTC-4) and I'm usually on irc.freenode.net as edwardk, so ping me and talk.
   If I have time I'll often dive right in. Too much structure takes time to
   manage, and I don't have time for that. =)

2. Experience

   I know Haskell, uh.. reasonably well.

3. Interests

   There's a pretty broad cross-section of projects I have in the air, so he's
   what I have that seems to make sense to pair on off the top of my head,
   ranked in terms of immediacy:

   In the short term I'm interested in releasing a bunch of packages for
   unpacked containers abusing backpack. That stuff I could probably pair with
   anybody who is interested in backpack and knows the general cut of
   containers, unordered-containers, etc. It is mostly syntactic work and
   packaging. This would be of fairly general applicability because most of the
   time when somebody imports Set or HashSet or Map in a module they go to use
   it at one type anyways. Getting an across-the-board improvement in memory
   locality and footprint seems like a no-brainer. -- [Edit: I just wrote this
   one.]

   I'm also interested in chewing down the backlog of issues in my current
   package set. If you have an issue you'd like to get fixed in something I
   maintain, feel free to reach out.

   I'm also interested in sitting down and playing with QuantifiedConstraints,
   but for that I'd probably want to pair with someone already well acquainted
   with some of my previous projects for encoding more category theory in
   haskell like hask, etc. This has a bit of a higher level of activation
   because it means I'd have to actually build the appropriate ghc branch,
   myself, so it'd have a fairly slow start.

   I also have a bunch of more formative work I'm doing on a toy compiler
   project. This may involve a lot more flailing. If you're familiar with
   bidirectional typechecking, dependent types and what not this may be a place
   where pairing makes sense.

   I'll admit my list is a bit me-centric.

## sh4rk1z

1. Availability

   I could make time for this everyday until 11 April (anytime) but after that I
   would only have time from 5pm to 9pm GMT+3.

2. Experience

   I'm not at a level where I could complete a basic application from start to
   finish using haskell (not even close I think) but who wants to pair learn (is
   that a word?) with me?

3. Interests

   I'm currently going through functors, applicative and monoids but I don't
   have any problem even starting from the start to stabilize my base.

   What we would do: Having an immediate communication
   link(skype/telegram/anything goes) so we could ask each other questions and
   solve code problems alone then share answers and think of a better way to
   code it.

## tech-learner-maker

1. Availability

   Anytime between 5pm to 8 pm [GMT+ 5.30] or 12 pm to 2 pm [GMT + 5.30]

2. Experience

   One year working out of self interest. need more experience.

3. Interests

   Projects - Interested to work on hledger project as I use it a lot. Also GTK+
   binding of haskell to make a fun pomodoro. Or can hack on anything fun.

## therealjohnfreeman

1. Availability

   Evenings and weekends in Central Time (Texas, USA).

2. Experience

   I think I'm your typical Haskell beginner: several false starts across 7+
   years. I wrote some Advent of Code solutions in Haskell, but I'm not sure I
   could write them again today. Writing Haskell feels like tying knots: if you
   don't use it, you lose it.

3. Interests

   I'd really like to start with good tooling from the beginning: stack, hlint
   (is that still a thing?), syntax highlighting in Vim, errors marked in Vim
   without blocking the UI, an auto-formatter. I don't know what the gold
   standard tools are these days, and I abhor solutions that consist of dumping
   a bunch of Vim plugins in my configuration because they inevitably fail to
   play well with the others I already have. This is not a must have, but it's a
   nice to have.

   I was part of a study group in NYC that worked through the Learn Haskell book
   (now titled Haskell Programming: From First Principles), but I couldn't keep
   up with the schedule and fell behind and out. I'd like to restart that and
   get through the book. There are some exercises in there. I'd like to write
   solutions to put on Github as evidence that I finished the book.

   After I get a baseline understanding, I want to work through some problem
   sets, specifically Exercism and each year of Advent of Code.

   After that, I think I can branch off on my own. My first real project is
   resurrecting my dead blog in Hakyll.

## wizek

1. Availability 

   Time is quite flexible for me. E.g. even now for the next few hours I could
   start and try a session with one of you. I live in UTC+2, CEST, but that
   doesn't mean much because my sleep cycle is often shifted. Even now the local
   time here is 4:43 AM. I suspect your schedule might be a narrower bottleneck
   here.

2. Haskell level of experience

   I've started learning Haskell about 5 years ago IIRC, and about 3 years ago
   I've made it one of my primary languages. I've written a few webservers with
   yesod, a few GUIs with reflex-frp/reflex-dom, and written a few open source
   libraries as well like https://hackage.haskell.org/package/hs-di and
   https://hackage.haskell.org/package/dump

3. Interests

   Two main interests jump to mind at first that I'd quite like to pair on:
   + I'd like to spend a bit of time trying to write a POC solution to this
     issue that I've had with reflex-dom:
     https://github.com/reflex-frp/reflex-dom/issues/175 I have an idea how we
     could begin, but so far I've found it a bit daunting to start working on it
     without a pair.
   + I'd like to find a solution together with someone to this issue with hs-di:
     https://gist.github.com/Wizek/396b0a608fa93d7d458a78dbf7c88870 Maybe with
     someone who has a deeper understanding than I currently possess about GHC
     and similar type errors.
