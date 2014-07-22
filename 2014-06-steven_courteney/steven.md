# Reflections on Teacher Swap

## Travel Policy

The funding model behind long-term stays is completely broken. It lead me and
has lead / will continue to lead other teachers to be in dangerous situations.

1. The budget is designed for short day-long visits and should be revised to
have a phase-long model
2. It is unreasonable and a misuse of DBC time and resources for teachers to be
in charge of the discovery and evaluation of their accommodation. In the same
way that i would expect no New Yorker to know *which* intersections on Folsom
are good or bad, it's ridiculous to think someone from another site could know
the same thing about New York.
3. The policy effectively communicates to me that cross-site interaction is not
a priority

## Performances versus Culture and Learning

I felt that NYC put a much stronger emphasis on culture and learning aspects of
the DBC experience. Students there seemed to be more vocal about the role of
culture ("ex-Fiddler Crab members are being silo'd away from Spring Peepers").
The daily midday announcements seemed to put a stronger emphasis on the primacy
of these tentpole ideas.

Contrawise, in SF, we tend to focus on the work primarily with discussion about
culture, "discoveries" being largely forgotten after phase 1.

## Continuity of Cultural Experience

Ancillary to the culture and learning emphases, NYC makes a more continued,
sustained investment in providing a consistent cultural experience, their
"culture steward" role.

## Less emphasis on space ownership in SF vs NYC

Due to the continued connection within the school, there are levers wherewith
the school is able to impress a sense of investment onto the students.

## Space

* The space is dark and spartan. Reham should visit! I can't imagine what that
  place is going to be like in the winter
* Proximity of students is nice, we're so much more spread out in SF
* Lunchtime interactions are more social and more friendly than in SF

### Professional Coding

I was rather surprised that the submissions for one of the challenges from
Phase 2 was not in a runnable state based on checkout.

Consider (chosen since it was the first in the drop-down list)

https://github.com/spring-peepers-2014/recent-tweets-2-challenge/tree/Alex_Isabel

Specifically, tpo get things working I had to perform:

https://github.com/spring-peepers-2014/recent-tweets-2-challenge/commit/b8d93524a8ee212f198a2fd2bf3a8d77e5013c13

It may be because of the incessant focus on success, clarity, and runnability
that I have a different (SF) expectation.

## Performance of Spring Peepers 2014

### Surprise about Being Cut Off

The Spring Peepers cohort reacted strongly, negatively to the "pushing out of
the nest" begun by Nikola at the beginning of the phase. In SF the "pushing
out" process, in our most successful cohorts, has begun strongly with Rao and
has been followed up (to date) by myself or Shadi in the Phase 3 kick-off.

While they might have felt that to be "unkind," forebearance of the shoddy code
delivered was even crueler.

### Less Responsiveness to Teacher Direction

Before the first day I assigned reading that was not done ([Everyday Rails:
Testing with RSpec][edr]). I was surprised by this as the explanation was, in
the words of Reid Covington: "In an ideal world, man."  This would not be the
typical response in SF.

Also, during final projects the team delivering "Smart SOS," a very
conventional Rails application, ignored teacher input on their MVP that their
data model was misconceived and preferred to plow ahead with their
implementation.  Ultimately they were hamstrung and unable to implement key
features.  This necessitated a Tuesday-night rewrite.  While the teachers in SF
do not serve to dictate direction, their advice is generally acted on.

[edr]: https://github.com/Devbootcamp/Experiments/blob/master/sf-experiments/04-reading-everyday-rails-rspec.md

### Surprise about Being Reviewed Critically

On day 1, I dropped a pop quiz on the group as I have occasionally done for
Phase 3's in SF.  Responses were generally weak and indicated particular
weakness in the following categories:

#### RSpec and Testing

A perennial pain point. Despite mailing the students a coupon code with a link
to a [book covering RSpec](), I was surprised that many students did not take the
initiative to read the material and benefit from it.

* [Isabel](https://github.com/spring-peepers-2014/phase-3-guide/pull/1/files#diff-ca23c37a821f99b7c3385f55b00ce1b2R50)
* [Ryan](https://github.com/spring-peepers-2014/phase-3-guide/pull/9/files#diff-7bf11952f311e5add6d7923b7027ce94R70)
* [Reid](https://github.com/spring-peepers-2014/phase-3-guide/pull/5/files#diff-ca23c37a821f99b7c3385f55b00ce1b2R40)
* [Zach](https://github.com/spring-peepers-2014/phase-3-guide/pull/11/files#diff-ca23c37a821f99b7c3385f55b00ce1b2R62)

This is a drift from SF. I need more time with this experiment but I believe it
will be getting better in SF in the very near future.  What was expressly
galling is that I received a number of complaints about how they spent all day
setting up RSpec when the formula on how to build and deploy RSpec in Rails
was literally in the text I told them how to read before showing up.

#### Advanced ActiveRecord

Another perennial weakness.  Two major smells here:

* `post.comments.create params[:comment]`
* `accum = []; collection.each{ |x| accum << x + 2 }`

* [Alex](https://github.com/spring-peepers-2014/phase-3-guide/pull/3/files#diff-c42616d74a53b8e91bed161b85ccc209R155)
* [Kenneth](https://github.com/spring-peepers-2014/phase-3-guide/pull/12/files#diff-ca23c37a821f99b7c3385f55b00ce1b2R19)
* [Beverly](https://github.com/spring-peepers-2014/phase-3-guide/pull/7/files#diff-ca23c37a821f99b7c3385f55b00ce1b2R6)

This has been called out to SF Phase II.

#### OOJS

The group seemed well prepared here and definitely understood the point of
function constructors and creating objects in their preliminary
self-assessment.  However, the final projects showed that their understanding
of OO JS was largely academic.  The application that used the _most_
JavaScript was still using an unsophisticated approach.

This file from Smartipants is reflective:

https://github.com/spring-peepers-2014/smartipants/blob/5cbeb3f315f62921bc824a7a8e11859c382fa675/app/assets/javascripts/application.js

Here we have view, data, templating concerns conflated.

#### Basic Ruby Debugging

I was surprised by how many students showed little facility in debugging a
stack trace.  I saw and participated in, and saw Nikola do the same, several
help requests where the students could not formulate a question nor could they
locate, via the stack trace, the locus of the error.

I saw a number of students getting lost and frustrated for want of the ability to
start looking at the problem in a fruitful spot.


#### AJAX

Good.  A few were using the non-promises interface to jQuery but by and large
this was in a good place.

## School &amp; Staff

I really enjoyed working with Nikola, he absolutely brings the weight of
real-world experience to the cohort and does a great job providing real world
support. Lloyd facilitates a great atmosphere and I cannot say enough positive
things about how Tanner backstops, supports, and helps the teaching staff.

Lastly, LaTeesha is great.  I love her attitude, focus, and drive.

Lamentably I wasn't able to hang out as much with the school because of home
obligations and housing shuffle.  I would really like the time to have a more
leisurely (but shorter) visit with them. Nate, Alex, and Sam all made my stay
welcome and fun.  And I mean, how are you going to top the just-married Sam and
Imogene coming in on demo day?  Hard to top! :)

Lastly: I love New York and am charmed by this team.

## Conclusion

This was an incredibly informative trip for me.  My biggest regrets are not
having had the opportunity to socialize more / working with RMW, but I hope that
the opportunity to visit again will happen again soon.

Insofar as it is incredibly difficult to inject the DBC culture and desirable
performance characteristics via text, these personality injections, to my mind,
are essential for creating and facilitating a vibrant culture that is more
**convergent** than **divergent**.

Finally, while we didn't spend much time together I really liked working with
Courtney to discuss our observations and experiences.
