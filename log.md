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

### Day 6: 08JAN16
**Today's Progress**: Realized hangouts on air is not working for me.  Added that too the issue about the button.  Learned more about the hangouts on air vs. youtube live.  Started writing more tests for the automatic event creation issue.

**Thoughts:** Spent too much time trying to digg in to something I don't have much control over.

**Link to work:** https://github.com/AgileVentures/WebsiteOne/pull/1478
### Day 7: 09JAN16
**Today's Progress**: Matt responded to my issue about hangouts on air and it led me to a fix on the youtube live channel.  The hangouts error message doesn't give you any clue what to do, says "try again later".  That instruction of what to do should probably be on AgileVentures.org since google is not supplying a good error message.  Made some progress in highlighting live events.  I am not well versed in CSS so this will be good practice to refresh on some basic things.    

**Thoughts:** This 100 day committment does motivate me to be more focused and make some progress, but I also wonder if some days I would have gone longer than an hour if that wasn't my goal to hit.  

**Link to work:** https://github.com/c1505/WebsiteOne/tree/1468_highlight_live_events

### Day 8: 11JAN16
**Today's Progress**: Made a simple amazon alexa skill for fun.  Made some small tweaks to a sample app.  I guess officially the time learning doesn't count for this since it was mostly a tutorial.  I also spent some time working on agileventures.org .  Creating an event with the creation of google hangout.  Not a lot of code got done, but learned a bit about why and how to avoid activerecord callbacks.  

**Thoughts:** It is hard to strictly focus on projects especially if you are approaching something new.  In the desire to create a project, sometimes it is useful to start with a tutorial.  Then when you are working on a project, sometimes it is best to take an hour to learn about a best practice before writing code. 

**Link to work:** https://github.com/c1505/WebsiteOne/tree/SPIKE_1475_auto_create_event
