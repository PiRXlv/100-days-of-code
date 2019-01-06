# 100 Days Of Code - Log

### Day 1: December 28, 2018
**Today's Progress**: Moved forwards with "BDD in Action" book, mostly working on exercise 2.1

**Thoughts:** 
  Although I picked book for learning more about BDD, it is very Java oriented and the code is a bit dated (normal for book of it's age). So far biggest challenge is not understanding BDD, but getting used to Java ecosystem.

### Day 2: December 29, 2018
**Today's Progress**: Finished exercise, cheating a bit by copying pieces of reference implementation. Kept reading till exercise 3.1 and decided it's a good point where to stop.

**Thoughts:** 
  I have always understood *why* of BDD, but strugling more with *how*. Hope this exercise will help. I will try to religiously use both(?) TDD/BDD in a "play" project of mine.
  Curious about how well BDD applies in single-person projects.
  Figure 3.3 is worth keeping at hand.
  
### Day 3: December 30, 2018
**Today's Progress**: Kept going through the book, got all the way up to chapter 4.

**Thoughts:** 
  Having vision and business goals helps with prioritizing and discovering implied requirements.
  The 5 whys is a extremaly useful technique to get the requirements and reasoning. I should definitely do that more (and encourage team mates to do the same).
  Impact map - mind map (why/who/how/what), starts with business goal.
  The chapter on understanding business goals seems to be slight waste of time, as I don't expect to be able to use those techniques soon. Still a good refresher and at least some of ideas I should be able to apply at least partially.

**Exercise 3.1** The goal is to make sure that there are no erroneous subsidy payments. 

### Day 4: December 31, 2018
**Today's Progress**: Kept going through the book, got all the way up to chapter 5.

**Thoughts:** 
  We too often decompose features into stories based on technical implementation, instead of what value are stories delivering.
  Chapter 4 feels more like something I would be able to use in my day-to-day job.
  I should use story review/estimation sessions as a vehicle for discussions more often.  
  
### Day 5: January 1, 2019
**Today's Progress**: Finished chapter 5.
**Thoughts:** 
  Asking right questions to unmask requirements is vital.
  Given - past sense, when - present, Then - should.
  Steps/preconditions describe *what* instead of *how*
  How to distinguish between high level scenarios and "unit test" scenarios? What is difference between their format and level of detail?

### Day 6: January 3, 2019
**Today's Progress**: Finished chapter 6 (skipping tools I'm not interested in).
**Thoughts:** 
  BDD is as much about discovering scenarios as it is about automation.
  We are writing SpecFlow "unit tests", not scenarios.
  The `Given` part is tricky. It should include all setup logic, but some if it might be slighly lower level as it seems at first glance. As in book, you set not only the flight end points, but also setup the distance between them.
  
### Day 7: January 6, 2019
**Today's Progress**: Chapters 7 and 8
**Thoughts:** 
  Clean split betweeen *well known reference data* and *data set up before scenario* is non-trivial, but important for understandability of scenarios.
  Using personas (known entities) for different pre-defined data sets is interesting idea to explore.
  Step implementation details *what* instead of *how*. *How* is implemented in another (technical) layer.
  Rules (scenarios) -> Flow (what) -> Technical (how) -> Application.
  Webdriver or analog for Electron testing? Realiability?
 
  
**Link to work:** none

## Future reading ##
1. Feature Injection
    1. [Chris Matts and Gojko Adzic, “Feature Injection: three steps to success”](http://www.infoq.com/articles/feature-injection-success).
    2. [Liz Keogh, “Pulling Power: A New Software Lifespan”](http://www.infoq.com/articles/pulling-power)
    3. [Kent McDonald and Chris Matts, “Feature Injection: A Gentle Introduction”](http://agile2009.agilealliance.org/node/185/)
2. Impact mapping
    1. Impact Mapping (Provoking Thoughts, 2012), Gojko Adzic
    2. [Impact Mapping website](http://impactmapping.org)
3. Deliberate Discovery
    1. [Dan North, “Introducing Deliberate Discovery” (2010)][http://dannorth.net/2010/08/30/introducingdeliberate-discovery]
9. Other
    1. [Dan North’s article, “What’s in a story”](http://dannorth.net/whats-in-a-story/)
    2.[Gojko Adzik, “How to implement UI testing without shooting yourself in the foot”](http://gojko.net/2010/04/13/how-to-implement-ui-testing-without-shooting-yourself-in-the-foot-2/)

**Link(s) to work**
***note*** fix those when there are some real ones
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence)
