# 100 Days Of Code - Log

### Day 1: 03JAN16

**Today's Progress**: Got feedback on pull request to AgileVentures.  Responded with thoughts about the code.  Made a small change and pushed it to get code climate to re-run since there was an error the first time.  That error was resolved, but a test failed seemingly unrelated to the code I changed in CI.  The test failed locally once.  Re-ran 3 times after that and it passed.  Pushed an empty commit this time to see if the build would pass and it did.  Mentioned intermittent failure issue in slack and in the pull request.  Looking back, the same test did fail on at least one previous build.

Worked on some of issue https://github.com/AgileVentures/WebsiteOne/issues/1475 .  The functionality I want is working, but there are some other tests that have started to fail. 

**Thoughts:** Happy to recieve feedback on the pull request and am interested in the conversation and best way to move forward with the desired feature.  Curious what is going on with the intermittently failing test.  Wondering why using activerecord callbacks is a bad idea.

**Link to work:** (https://github.com/AgileVentures/WebsiteOne/pull/1474) https://github.com/c1505/WebsiteOne/commit/8f30616f04d1016771771db0a96700bacf79ed09

### Day 2: 04JAN16
**Today's Progress**: Work on previous pull request to understand what is desired testing-wise.  Submitted a new pull request for agileventures.org to make live events visible when they aren't started from an event.  Reviewed a bit of SOLID principles from an edx agile development course.  

**Thoughts:** I think actually opening a pull request and getting feedback will speed up my learning and it will be better working on projects with other people that are used.  There are real users affected.  

**Link to work:** https://github.com/AgileVentures/WebsiteOne/pull/1478 

### Day 3: 05JAN16
**Today's Progress**: Got further direction on automatic event creation and live events pull requests.  Spent some time trying to figure out the cause behind bug where the 'start a hangout' button won't show up.  Was able to replicate it.

**Thoughts:** Most of programming is not the typing of the characters on a keyboard.  

**Link to work:** https://github.com/AgileVentures/WebsiteOne/issues/1477

### Day 4: 06JAN16
**Today's Progress**: Added some tests for upcoming and live events pull request for agileventures.org.  Investigated a bit more into the 'start hangout' button bug.  

**Thoughts:** It can be dangerous to rely on an external API for business critical things.

**Link to work:** https://github.com/AgileVentures/WebsiteOne/pull/1474

### Day 5: 07JAN16
**Today's Progress**: Added more tests for upcoming and live events pull request.  Squashed commits and rebased with develop and updated the pull request for later review.  

**Thoughts:** Git in how it allows collaberation, but could use better naming and error messages.

**Link to work:** https://github.com/AgileVentures/WebsiteOne/pull/1474
