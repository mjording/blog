---
layout: post
title: "One of Ruby's strongest traits as a language is its community."
description: ""
category: 
tags: []
---
{% include JB/setup %}

One of Ruby’s strongest traits as a language is its community.

 [Nick Fitzgerald](http://fitzgeraldnick.com), posted a [nice piece](http://fitzgeraldnick.com/weblog/39/ ) on object oriented code on new years eve 2010. Yes he was blogging about programming on NYE. Whats perhaps more telling is I tweeted and read it as it came out. 

One of the reasons I was happy to see a OO post on Ruby is the rarity. In our [weekly meetup](http://meetup.com/nycruby/ ) we don’t cover it enough. I think this is because seasoned Rubyists assume to have a working knowledge of the Ruby’s Object structure and new Rubyists tend to be facilitated by Ruby’s meta-programming side. Ignoring OO discussion can be a huge problem. As Yahuda Katz ( the man who saved Rails )  pointed out in a few rants as he walked through the shadow of active record that [Ruby’s strength is in the Object](http://yehudakatz.com/2010/02/21/ruby-is-not-a-callable-oriented-language/ ). 

Ruby is a wonderfully accommodating language to code in. This helps coders get things done. It also allows the Active Record version 2.3.x codebase to exist. To the credit of AR it was and still is a nearly painless data persistance experience for both newbie and old web beard. The initial key to being approachable and friendly to the libraries consumers was a fairly heavy handed use of meta-programming. I wont go to far into it here but essentially AR attempted to work around a variety of potential issues with a fairly elegant leveraging of method_missing and a labyrinth of mix-ins. 

AR gave us callbacks and gave developers power over the transaction to the chagrin of DBA’s system wide.  All this seems great until it needs maintenance, refactoring or an extension via plugin/gem. It is at this point that the Ruby daredevils were separated from the faint of heart.  Meta programming on this scale forces a developer to be brilliant to a level superseding function of a ORM or in many cases forces one to create create maps. We should not have to make maps of code. 

I was fortunate to have done nearly all my Ruby work outside of Rails
until the past couple of years, thanks to successful consulting
practice, a fat Java resume and Merb I escaped what would have driven me
to contribute all my family time to making Rails as elegant a codebase
as it is for web developers as a web dev Domain Specific Language (DSL).
Thank you Yehuda ( @wycats](http://twitter.com/#!/wycats ) ) , Engine Yard et all for allowing me to take on Rails projects and participate more fully in the Ruby community. 

[@wycats](http://twitter.com/#!/wycats ) has also been one of the few ROR devs to both [despair](http://yehudakatz.com/2009/03/06/alias_method_chain-in-models/ ) when we fool ourselves into thinking we are clever watching him [tend the gardens](http://yehudakatz.com/2009/01/16/status-update-a-fresh-look-at-callbacks/ ) of ruby web frameworks saved me hours and frustration. This is not to mention the tremendous innovative contributions [directly](http://yehudakatz.com/2010/04/12/some-of-the-problems-bundler-solves/ ) gave the community nor the [indirect](http://weblog.rubyonrails.org/2010/2/13/jos-e-valim-and-carl-lerche-joins-rails-core) [contributions](https://github.com/josevalim) [his guidance](http://yehudakatz.com/2010/08/14/threads-in-ruby-enough-already/ ), [solid public engineering](http://yehudakatz.com/2010/08/14/threads-in-ruby-enough-already/ ), and [passion](http://yehudakatz.com/2009/08/24/my-10-favorite-things-about-the-ruby-language/ ) for [the craft](http://yehudakatz.com/2010/02/07/the-building-blocks-of-ruby/ ) that leaves any RoR dev indebted . 

Really what I’m saying is I have a man crush on Yehuda Katz. I am going to right now thank him on twitter and follow his example by attempting to in a minor way find best practices and discuss them publicly. Sure it can be a bit intimidating to work publicly, where others are given the opportunity to ridicule. I know that I stand in the shadow of some amazing talent. One of the things that keeps me happy to be among Rubyists and part of the community is that the ridicule if it comes is good spirited and humorous and more often then not everyone is given an opportunity to participate in a discussion and learn from each other. 

Shortly after my gushing thanks of @wycats I’ll be posting my screencast on Object Composition in Ruby 

