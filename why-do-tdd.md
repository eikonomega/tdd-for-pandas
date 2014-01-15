# Why Should I Use TDD?
The most strident proponents of TDD can make you feel like you 
cannot make good software without it.  In this, I disagree with
them.  

That said, utilizing the techniques of TDD does make it *more 
likely* that you will make good software.

## Tests Give You Confidence

    Good software is easy to change.
    
Let's pretend for a minute that you're working with a 
project that's been around for while but doesn't have
thorough test coverage.

Now... let's also suppose that you've just finished working on an 
awesome new feature and you publish that baby into production
only to find out that you just crashed the billing system 
and your company is losing thousands/millions/gazillions of 
dollars because of it. And the CEO is calling with some choice 
words for you.

Fast-forward to your next assignment.  Now all you do is 
stare at the screen in fear when you've completed a new feature.
**You have no way of really knowing if your change is going to 
have unintented consequences.**

Spread these experiences across the team and you've got software
that develops at a painfully slow pace and breaks whenever
some new is published. **AH SNAP.**

    Solid test coverage makes software easy to change.
    
If you have solid test coverage, you can drastically reduce
bugs getting into your billing system and increase your 
development speed.  This is because your test suites 
will immediately alert you to unintended consequences 
introduced by new code.

This allow you to make your change and immediately see
if it breaks something else within the system.  *That is,
as long as your had good tests in the first place.*

## Tests Help You See Blind Spots
    
    Good software throughly exercises logical code execution pathways.
    
    Writing unit tests helps you see which pathways you haven't account for.
    


