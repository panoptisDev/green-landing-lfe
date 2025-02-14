+++
title = "Learn"
in_search_index = true

[extra]
long_title = "Resources for Learning LFE"
long_description = "Learning LFE must be taken in two tracks: learning the syntax particular to a Lisp on the Erlang VM, with all its support for pattern matching, Erlang-style arities, etc., and then learning the ins-and-outs of BEAM languages and OTP. This two-pronged approach is the path to success."

+++

# LFE

## [Quick Start Guides](#quick-start-guides)

[Quick Start with rebar3](https://lfe.io/books/rebar3-quick-start/) - This will get you up and running with LFE, requiring _only_ that you have a modern Erlang installed (version 21+) and `rebar3`.

## In-Depth

[The LFE Tutorial](https://lfe.io/books/tutorial/) - The Erlang "Getting Started" translated into LFE!

[Casting SPELs in LFE](https://lfe.io/books/casting-spels/) - The famous "Casting SPELs in Lisp" translated into LFE, but taking things further than the original with state management via `defrecord`, creating a custom game server, and then dipping the toes into OTP with a conversion of the custom game server to a `gen_server`.

[LFE Examples](https://github.com/lfe/lfe/tree/develop/examples) - For those that learn by watching and playing, the `./examples` directory in the LFE repo may be quite useful.

LFE on [Rosetta Code](https://rosettacode.org/wiki/Category:LFE) - If those examples aren't enough for you, there are 99 others to choose from on Rosetta Code!

[Structure and Interpretation of Computer Programs](https://lfe.io/books/sicp/) - The LFE edition of SICP is still a work in progress, but two chapters have been completed and offer an excellent introduction to core concepts in computer programming, or a refresher for those wishing to get back in the game. This text in its original form was used as the basis for the computer science introductory courses taught at MIT for over a decade (from the early 1980s into the 90s). SICP is widely regarded as one of the most important texts for programming, clearly explaining core principals of the art and science, and helping to shape the minds of the first few generations of early Internet innovators. The _LFE Edition_  converts the Lips-1 of the original (Scheme) into the Lisp-2+ variant of LFE.

## More LFE

Once you've learned the syntax and the underlying principles of the Erlang VM, you're going to want to actually _use_ this beautiful Lisp! Be sure to check out our [reference materials, how-tows, etc.](/use).

[The community](/community) will be an invaluable resource in your journey of learning, to be sure to stop in whatever medium makes you happy, say "hi" and ask us lots of questions!

# Erlang

There are some phenomenal materials available for a self-paced Erlang/OTP education. Some of the classics are given below. For those with bigger budgets, remember that formal training is also an option! (In fact, there are not only classes offered for Erlang, but also LFE ...)

## The Language

[Learn You Some Erlang for Great Good!](https://learnyousomeerlang.com/) - Probably one of the best (and _definitely_ the most fun) books available for learning Erlang. (Also available [in print](https://nostarch.com/erlang).)

## OTP

[Designing for Scalability with Erlang/OTP](https://www.oreilly.com/library/view/designing-for-scalability/9781449361556/) - The thinking person's OTP book: where to go when you really want to understand OTP.

[Erlang and OTP in Action](https://www.manning.com/books/erlang-and-otp-in-action) - This book is another fantastic resource, building up an OTP application piece at a time as you move through the chapters.

## In Production

Once you've learned how to write Erlang/LFE/OTP applications, is time to get them into production, and you'll find the following invaluable references for that:

* [Adopting Erlang](https://adoptingerlang.org/) - _"Adopting Erlang is an ongoing effort to gather all the resources that will help you use Erlang in a business. The booksite is divided in three sections focusing particularly on Erlang/OTP’s higher level concepts in the current open source ecosystem, how to use it in production (while setting up a pipeline for continuous development and delivery), and how to build a team when you’re starting from scratch."_
* [Stuff Goes Bad - Erlang in Anger](https://erlang-in-anger.com/) - _"This book intends to be a little guide about how to be the Erlang medic in a time of war. It is first and foremost a collection of tips and tricks to help understand where failures come from, and a dictionary of different code snippets and practices that helped developers debug production systems that were built in Erlang."_

# Lisp Arcana

In the event that you want to dive deeper into the world of Lisp itself, there are several excellent texts to explore.

## Lisp Internals

* [Lisp in Small Pieces](https://www.cambridge.org/core/books/lisp-in-small-pieces/66FD2BE3EDDDC68CA87D652C82CF849E) - _"This is a comprehensive account of the semantics and the implementation of the whole Lisp family of languages, namely Lisp, Scheme and related dialects. It describes 11 interpreters and 2 compilers, including very recent techniques of interpretation and compilation."_

* [Let Over Lambda—50 Years of Lisp](https://letoverlambda.com/) - _"Starting with the fundamentals, it describes the most advanced features of the most advanced language: COMMON LISP. The point of this book is to expose you to ideas that you might otherwise never be exposed to. This book is about macros, that is programs that write programs. Macros are what make lisp the greatest programming language in the world. When used properly, macros enable amazing feats of abstraction, programmer productivity, and code efficiency and security that are unheard of elsewhere. Macros let you do things you simply cannot do in other languages."_

## Lisp Reference

* [Common Lisp HyperSpec](http://www.lispworks.com/documentation/HyperSpec/Front/Contents.htm) - This is the definitive reference manual for the Common Lisp standard. The LFE core contributors have made nearly constant reference (and deference) to this document in the course of implementing features in LFE.

* [The Moonual](http://www.softwarepreservation.org/projects/LISP/MIT/Moon-MACLISP_Reference_Manual-Apr_08_1974.pdf) - This is a bit of computing history that not many are aware of: the manual for [MACLISP](https://en.wikipedia.org/wiki/Maclisp) written by David Moon. This is of interest to LFE developers due to the influence it has had upon the design and development of LFE. LFE actually derives most of it Lisp nature due to the experiences Robert Virding had as a physics PhD student who programmed in MACLISP on university machines. Even since then, we have constantly referenced the Moonual, almost as much as the Common Lisp HyperSpec (and in some cases, more!). It is of particular interest that the MAC project at MIT not only gave birth to MACLISP, but also [MACSYMA](https://en.wikipedia.org/wiki/Macsyma) (originally written in MACLISP, since ported to Common Lisp) which significantly influenced the development of Mathematica.
