---
---

# Session Transcript:<br>Visualization as a Civil Right

### Session facilitator(s): Thomas Wilburn, Joanna Kao

### Day & Time: Friday, 2:30-3:45pm

### Room: Johnson
 
THOMAS: Okay.  I guess we do have microphones here.  But I can just stand here.  That's fine too. I'm also probably loud enough.  So, this is probably fine.  Thank you all for coming to visualization as a civil right.  Before we get started, I just wanted to note Amanda here is transcribing this session which is great.  We're thrilled, especially as an accessibility session to have someone transcribing it.

A couple things to keep in mind.  We will report back sometimes.  If you can, make sure to speak loudly enough that she can hear so that that can get captured for people who aren't in the room or who can't hear.  And if you need to say something sensitive or that you don't want to be associated with you publicly, that's fine.  Be sure to say that it's "Off the record" and then she will stop transcribing and you can go back on the record as soon as you've gotten whatever juicy details out that you need to let the rest of us know about.

In any case, thank you for coming to our session on creating accessible graphics.  My name is Thomas Wilburn.  I am the news developer on the interactive team at the Seattle Times.  I have been working on trying to become better at accessibility for about the last year to year and a half.  So, I want to be clear that I'm not coming to you as an expert on all of this stuff.  But I, you know, I'm working on it.  And I hope that you all will join me in that.  And   

JOANNA:  I'm Joanna.  I work on the graphics team.  I'm also not an expert.  I like thinking about it, but there's a lot of aspects of accessible graphics that we have not thought about.  We hope you will help us come up with things to take home.  We are hear for 75 minutes.  We know there's a lot of really interesting sessions going on at the same time.  If at any point you find that the session isn't useful or there is something else to go to, feel free to leave.  We won't take it personally.  Unless you tell us we should.

THOMAS: Take that off the record.

JOANNA If you are here, we are going to talk you through how to set the tone.  And we will use a screenreader, you can download the one you have on your phone or download one.  And if you don't want to work on your own project, we can give you links to look at.  And we're going talk about things we could do to improve the projects we have worked on and talk about those a bit.

This is the definition of accessibility that we're using.  So, the way that we like to think about it is disability is a mismatch between a person and their environment.  And accessibility is the correction of this mismatch.  The reason why we really like this definition is because this is a definition that looks at how society is designed and that accessibility    that disability and accessibility are related to the design of society and not necessarily something that you're necessarily born with or something that can be diagnosed.

And before we started we wanted to try to bust some common misconceptions about disabilities.  These are not in any particular order.  But things we would like you to think about as you are looking through the projects that you're going to work on today.  The first is that disabilities are visible.  A lot of them are not visible.  The second thing is disabilities are permanent.  Often disabilities can come and go.  They can be really temporary, last for a couple months or hours.  The third is that people are born with disabilities.  That's definitely not true, you can develop them over time.  As we get older, almost everyone in the room will have one.

The fourth is a disability in one place is a disabilities everywhere.  Going back to the definition of disabilities and accessibility.  We really see that disability is related to how things are designed.  So, disability one place might not necessarily be a disability somewhere else.

The fifth thing is designing for accessibility takes more time and resources.  And hopefully what we'll see in this session is that this is not necessarily true.  And the last one is accessible design only benefits people with disabilities.  And hopefully also by the end of the session you'll see that's definitely not true as well.

THOMAS: So, we're going to spend some time in this session, the practical focus, at least, for a little while, we're going to be working with a screenreader and talking about that.  We're going to be focusing on visual impairment a little bit.  But we want to remember that disability comes in all kinds of forms.  That it's not just necessarily about like an on/off state.  And that it's not necessarily about just one form of having difficulty interacting with a design, right?  It can be come down to situations or cases where there's low vision, blindness, degrees of blindness, color blindness, motor impairment to various degrees and at various parts of the body.  Cognitive impairment in different ways.  Vestibular disorders.  So, people who have vertigo or who are made dizzy by large kind of like moving objects near them.

And degrees of hearing impairment which can take a lot of forms.  You can actually be deaf, you can have difficulty hearing certain frequencies.  You can have difficulty distinguishing voices.  So, there's lots of different ways that this can be defined.  And it's also not necessarily, as Joanna mentioned, a permanent thing.  We can think of a scale of accessibility as being perhaps I don't have access to a hand.  That might be because there's something physically keeping me from using that hand.  It might be because I just have a broken arm.  It might be because I just had a kid and so I'm carrying a child and so I can't use the hand.  I'm doing everything one handed.

So, we want to not think of this narrowly.  And that brings us to the idea of inclusive design.  And so, inclusive design is kind of this thought process that everybody falls into this as a spectrum throughout our lives.  But more than that, it's the idea that creating a design that is inclusive for people who have disability actually also makes the experience better for people who do not suffer or encounter that disability in that scenario.

So, for example, a really good case that this would be is closed captioning.  Right?  Closed captioning is introduced in theory for people who can't hear the screen.  But it turns out closed captioning is also really useful if you work in a noisy environment.  If you are trying to teach a child how to read.  If you are somebody who struggles with a language and so it helps to see something that's both written and, you know, listening available to you.

So, that design of creating something that may have been meant for people who are hearing impaired actually makes the experience better when it's available for everyone.  And that's the principle that we want to work on when we're designing stuff for the web.  One way that I think of for this in particular is alt text, right?  Like alt text is a thing that we add to images so that they're accessible to screenreaders.  But if you were on a slow connection and images don't load, the browser shows the alt text.  Now the experience is better for people who have poor connectivity or might have images turned off to save bandwidth.  We're creating a better experience by targeting disability and that's inclusive.

So, just as there are    thank you, I keep forgetting to advance the one that's not mine.  Just as there are different kinds of disabilities, there are a lot of different ways that people get to and consume your content.  The one that I have on the top is for me kind of is a good lead-in.  We don't tend to think of this, I think, under accessibility.  But for me the point of mobile versus desktop is in the year of our Lord 2018, we typically have to design a responsive side, right?  Like the days of MDOT are gone.  You're already thinking about site design in terms of a client that is not a single standard 960 grid, right?

You're already thinking of it as something that can reflow and have great points and change in fidelity.  So, by already thinking of it that way, it's a lot easier step to say that I'm also thinking about things in terms of screenreaders or braille readers.  We have some pictures here.  So, the top left is eye tracking.  Someone who is interacting with the screen and there's a keyboard up and it's tracking their eyesight so they can interact with the computer.  Switch devices.  Two of which are shown here.  The one on the left is for phones, and the one on the right is a foot switch for using with a computer.

And this is a way that people are going to actually interact.  But, of course, like inclusive design, the same design that's good for switch devices is good for people who might only use a keyboard.  I had really bad carpal tunnel when I was in college and it was really useful to have keyboard accessibility because the mouse would hurt me.  That was a good case where it comes in handy.  Closed captioning, audio description, they are all things that your content may be consumed or browsed and it's what we need to think about to be more inclusive in our design.

So, how does this apply to journalism?  I wrote up a post that originally was kind of the thought process for starting this talk for source about using a mobile screenreader.  And it had been inspired    and one of the things that Lindsay, who was editing the piece asked me was, how does this apply to journalists?  It applies to everyone.  Don't be a jerk.  Like, accessibility is important for anyone.  But I thought it was actually a really    it was kind of an interesting question because as an industry that has trouble getting and keeping readers in the first place, like, why would we put barriers in front of stuff?  Like, why would you give people an excuse not to necessarily read your stuff?

And there are other reasons that we worry about this.  There is possible legal liability.  You can have an ADA action filed against you if you are a public company that is supposed to be providing service.  And I think more importantly it really helps us think about what are the story choices that we're making?  How are we presenting those things and who are we interviewing and how are we report something who are we asking to speak to us?  Are we being inclusive with how we're talking and interacting with them?  Are we respectful of their needs at the same time?  I think that could really be useful for us as journalists who are thinking about our communities.

Okay.  So, now we're going to get into, real quick I want to start by doing a little bit Joanna is going to go around while we're doing this so that in case we need help    although she has warned me she's much more experienced with the iOS version than the Android.  The idea is that everyone in here, if you have a smartphone, you have a screenreader.  Back in the bad old days you had to go out and you had to get a screenreader.  And before NVDA was a thing, you had to pay a lot of money for JAWS if you were on Windows.  They weren't common.  It wasn't easy to test.  But if you have a smartphone, it ships with a screenreader.  There's no excuse not to know how to use it.  We're going to two through real quick and we are going to set one up and teach you how to use one if you don't know already.

One thing I wanted to ask.  Does anyone here actually already know how to use a mobile screenreader?  A few of you.  Okay.  What I would like to do, especially in a few minutes after we've gone through the basics we're going to break into pairs to kind of do an exercise.  And if you all could make sure that you are spread around the room or available to help people out who might be struggling because it's the first time, that would actually be really, really great.

JOANNA:  And if you need help while we're doing this, just raise your hand and I'll come over.

THOMAS: Yes.  The first thing we're going to do as you're setting up is we need to make it really easy to turn the screenreader off and on.  Because once these are turned on on a mobile device, the screen will stop acting as like a direct manipulation.  You'll no longer be able to just touch an item or scroll a list.  Instead, it's all gestural.  You can get into an immediate panic of I've turned this on and it's yelling at me and how do I get it to shut up?  The first thing we're going to do is you're going into your settings.

We have two paths here.  IOS, general settings, there's an accessibility menu and there's an option for an accessibility shortcut and you're going to check VoiceOver on that.  And in Android, in settings and accessibility, as far as I know that should be fairly standard, it may depend on your phone, there should be an option for the volume key shortcut and that's TalkBack.

And you will use a single button combination without going through settings to turn it off and on.  On an iOS, that's triple tapping the home button is going to turn off or on any accessibility services that you have enabled.  And on Android, it's going to be holding the volume keys up and down for three seconds.  So, for example, on my phone, if I hold the volume keys up and down for three seconds    yeah.  Sorry.

[screenreader talking]

THOMAS: And then when I'm done, it's shouting at me, please make it stop.  I'll hold the buttons down again.  Or on iOS, triple tap and it will turn it back off.  It will announce it, but that's the last time it will talk to you.  It has to announce in case you can't see it.  This is the part where putting in one ear plug is going to be really handy.  Otherwise we're going to get a lot of shouting phones here.

Okay.  So, once we have that set up, we need to do some simple navigation.  The idea of a screenreader both on mobile and on desktop is that it basically treats where you would normally have like a whole screen, it's going to treat it as a list, basically.  That you can move up and down through the list.  So, everything becomes a linear experience.  That's another reason why for me the idea of like responsive design is really useful for this.  Because you're already used to thinking about a single column of content a lot of the times.  That's what a screenreader basically experiences.

So, on both operating systems, once this is enabled, you're going to be able to swipe left and right and you should be able to see a high litigate move on the screen as it will read something to you.  So, you should be able to see that to navigate up and down the screen.  There's another thing    once you have something selected, obviously like you can't touch that thing to activate it, but if you double tap anywhere on the screen, whatever has the highlight around it, that will now be    it's as though you tapped that item.  So, that should give you the basics of being able to move up and down.  David, if you have a question?

AUDIENCE: Yeah.  How did the standard for those interactions come about?

THOMAS: This was really first kinds of launched as I think it was iOS3 rolled out VoiceOver.  The standard for this is going to be a little bit different.  And the reason for that is you'll notice that iOS has a lot of multi finger gestures because they support multi touch screens.  There's thing like two fingers and rotating.  Android did not.  Apple would have a two finger motion, Android maps it to a shape that you'll use for a single swipe.  But the back and forth and the double tap seems to be really natural so they're both going to share that.

The other thing is if you're on screen and need to jump to something quickly and you can see the screen or you can't, you can touch and either hold or just touch and move the focus.  You can use that to explore the screen.  If you're sitting there with a screen that you want to find things on, you can touch and then move your finger and it will announce what's under your finger.  So, that's another way, instead of having to move linearly by swiping left and right, you can actually just kind of jump around.  This is for me really useful for skipping ads on websites.  Which will almost    you are going to see will almost immediately trap you.  So, it's useful to be able to, like, kind of spatially move past them as opposed to trying to get through whatever weird hierarchy the ad company has put into place.

All right.  Next thing that we want to be able to do is    so, navigating up and down by kind of like one item at a time is fine, but it's not terribly efficient and in a lot of cases like if you get stuck in a deep menu.  The Seattle Times use to have a menu at the top of our page that was like every section front and every sub section front and it was like 400 items long.  It was in there twice, they had a mobile and desktop version.  It was a nightmare.  Luckily we don't have that anymore.  But what you want to do is jump to a landmark.  On iOS, there's a thing called landmark.  And you want to jump to headers and landmarks.  H1s, article tags, this is why the semantic markup is important.  It gives people landmarks to get to.

The other options are move by word, move by character so you can have the phone manually spell something out.  You can have options for that.  And you can swipe up and down and move by landmark.  Left and right moves one item, but you can use up or down to jump on iOS.  On Android, because they don't have the rotor, they don't have the two finger turn, the left and right always moves by something, but not always a single item.  And you swipe up and down to change the granularity.  You can be in headers mode.  To get back to normal, you switch back to default.  You keep swiping up or down until that changes.

And that could let you jump to like headlines or lists or out of lists, for example.  The next thing that you're going find is so when you move to something    when you move the focus manually, either by touching it on screen or swiping left or right, what's going to happen is it's going to pause and wait for input.  It wants to know, maybe you want to tap on that thing.  When that happens, you need to tell it, no, I want you continue from this point.  I want you to keep reading.  So, on iOS you can then pull down with two fingers and that's the gesture saying, okay, just continue from this point.  On Android this gets weird.

I have    I'm going to grab this mic.  Hello?  Hello?  Okay.  So, I drew up here kind of these crappy diagrams to help you remember visually.  Like Android is on the left, iOS is on the right.  If you need to move up closer, that's totally cool.

Android, instead of having the rotor has a local context menu that you can open.  So, you draw an upside-down L.  You go up and to the right.  And if you do that, it should open up a menu that you can then choose to read from next item.  This is a huge pain.  It's really obnoxious because you often need to navigate to something and then continue reading and having to jump into the context and it's really painful.  One of the things I recommend if you have more time, don't necessarily worry about it now, if you go into the TalkBack settings, you can assign gestures.

So, for example, I have mine set up so the fingerprint sensor on the back, if I swipe up or down, that changes my jump mode to like headlines or default.  And in swiping up or down, continues reading because I do that a lot more often.  So, Android gives you a lot of opportunities to customize the gestures to make them less awkward and I would highly recommend doing that if you get a chance. 

Okay.  So, at this point that's your crash course.  You should now be able to load a page that you've worked on and listen to it.  And it'll be eye opening for you.  Or ear opening, so to speak.  Because it's a lot different than you might think it is.  And some things that you're going think of as being clear turns out they're divorced from visual content, they're not.  What we would like you to do is to start by opening up something that you've worked on.  If you don't have something that you've worked on personally or that you wanted to kind of use as an example, in the Etherpad I have put three examples of visualizations that I think are both good and bad.  Two I have worked on.  One is a pudding visualization that I actually thought was very good but has some accessibility problems.  And you can use those as an example.

So, take a few minutes now, load that up and, and just kind of take a test drive, right?  We'll take a couple minutes and then come back and split into pairs and talk about it. 

JOANNA:  And if you need help, just raise your hand and we'll come over. 

[Setting up screenreaders]

THOMAS: So, one thing that Dana just noticed that is notable, when you first turn this on, it may make you walk through a tutorial just so you're aware.  It may make you walk through it.  That's good because it will refresh your memory.

If you're having trouble on iOS and you're using Chrome, try switching to Safari.

[Setting up screenreaders]

I had a mistake in my slides on Android.  The local context menu shows you the items for landmarks readings.  You actually want to do an actual L shape to open the global menu to read from the next item.  So, that is on me and I'm deeply sorry about that.

Yeah, so, now that you've gotten started, like this should be enough for you to kind of start seeing what it's like.  What we want to do is a pair exercise.

JOANNA:  Yeah, so, if you could try to find someone near you.  Raise your hand if you've used a screenreader before today.  Okay, you guys are basically already spread out.  Okay.  I think we're good, then.  So, what we would like you to do is before you get into your pairs, we would like you to write down two questions that someone who has consumes whatever the thing    the project that you're looking at is should be able to answer after having looked at your project.  So, like come up with two questions and have them in mind or write them down somewhere.  We'll give you like maybe a minute to come up with that.  And then after that try to find a partner near you who you can work with.

[Group work]

I'll give you another 30 seconds to write down two questions.

THOMAS: They don't have to be like amazing questions.  Just basic comprehension. 

AUDIENCE: Can you give an example question?

THOMAS: Sure, so, like an example question might be if I were    so, one of the pieces that's the example in there that's my bad example.  And it's actually a recent project so it's a little embarrassing.  But we did a burger bracket.  So the questions would be like, can you vote in the burger bracket?  Are you capable of understanding that this is a voting participation thing and then can you actually vote on the page?

Because if not, then it's not doing its job.  So, what we kind of want to know is, like, can you get it?  Like if you're accessing this from a screenreader, is the basic information delivered to you?  Can you understand the point of the graph?  Are the numbers clear?

JOANNA:  Yeah, so, if this is like a written traditional text story, what was the main point of the story?  What is the lead of your story?  If it's a graphic, it could be like what was the peak of whatever thing you're graphing, for example, if that's the point you're trying to make to get across.  Okay.  So, we're going to hope you guys have two questions in mind.  What we would like you to do now is pair up with somebody.  And what we would like you to do is to show the project that you're working on to your partner only using VoiceOver.  They're not seeing it, but they're going to hear your project.  I know.  We're hearing some scary sounds around the room.

So, we're going to give you guys a little bit of time to do that.  And what we would like you to be thinking about as you do it, do you understand what it is?  Can they describe it back to you and can they answer the questions that you just wrote down?  And if you're the person doing it, think about what made sense, what didn't make sense, what could have been better.  And write them down as you're thinking about them.  And we will come back at the end and talk about them as a group.

[Group work]

THOMAS: So, it's been a little bit more than five minutes.  Can the person driving be now listening and the other person is the driver?  That way you can each try an example.  If you have been switching off, that's great too.

[Group work]

JOANNA:  We're going give you guys one more minute.  Try to wrap up what you guys are working on.

THOMAS: Okay.  So, at this point you should    you've each got an chance to listen.  You've each had a chance to drive.  And hopefully you've had a chance to see some places where stuff went right, hopefully, and also some places where it fell over.  So, what I would like to do, Joanna is over here.  She's going take it down on the board.  If you want to raise your hand, what went right and what were the things that you noticed were immediately accessibility problems?  Yeah?

AUDIENCE: For my stuff, going right, you know, more prosy content around it seemed to read just fine.  But things like, you know    any depiction of like the rise and fall of a line, there's no way to convey that.  It was reading the access labels, but there's like no context as to like what these numbers are that are being read aloud.

THOMAS: So, one of the things that I find myself doing, and I think it depends.  Like I know Joanna has often put like a table hidden behind that graphic so that people can get access to the numbers.  One thing that I actually do is for a lot of graphics that are just trying to make a point, I actually just use the alt text to be like, it's a downward trend.  Because to me it's also about like they're reading it for the story.  Honestly, like a lot of visual readers are not exactly plotting their numbers.  They're looking for, well, what's the point of this graphic?  But, yes, that's definitely one.  Especially SVG or HTML graphics will immediately start spitting out things with no context.

AUDIENCE: Is there a way to get it to ignore the access labels?

THOMAS: If you take the containing div    there's a thing called ARIA, the accessibility rich application standard    let's go with that.  So, ARIA specifies a number of attributes that you can add to elements.  One of them you can add is role.  Role will tell you, this is not a div, this is a button  or an image.  When I have SVG graphics, I wrap them in role and image and set the context.  And it will treat them like an image tag.  That's good for leaflet maps.  Because if it goes into a leaflet map it will start reading all like 100 tile images and it's a nightmare.  But if you mark it at role image, I can't dive into an image.  I'm just going to read the alt text and keep going.  That's super useful.  David?

AUDIENCE: Leaflet being open source software.  Is there a reason that's not in leaflet?

THOMAS: You would have to talk to them about it.

AUDIENCE: Because it's open source.  Someone could make a pull request.

THOMAS: We often embed leaflet through a custom element.  I have my element automatically add that role to it.  I don't know why it's not standard in the library.  I honestly couldn't tell you.  Yeah.  What else?

AUDIENCE: We found something very weird.  Here is Denver.  And Denver is in bold.  And then it treats it as if it's two different paragraphs.

THOMAS: That can happen.  Especially if you used a block level element and then overrode it with style, the screenreader may not know.  So, this is one of those cases where it's really important to use like a bold tag.  But it will also often pause between words with emphasis so that a difference in formatting will sometimes trigger.  It's not a perfect    it's an automated reader.  Sometimes it has hiccups like that too.  Yeah, what else?

AUDIENCE: I got a bad and then a good, maybe.  But bad was it was a questionnaire and it doesn't reset after each question to the top.  It got stuck on the action bar so you weren't able to read them.  The good ish was that I used native slider and so it was able to understand that to be a slider.  The ish part is I don't know how to interact with that slider using a screenreader.  I'm going to assume there's some interaction that may have worked.  It registered as here is something you can do something with.  I just didn't know how.

THOMAS: Yes, actually I remember there was some guidance about sliders because it's not entirely always clear at the OS level.  Like those things would be supported in an application.  But on the web it can be a little bit more difficult.  Anyone else here have issues where like something might have changed higher up on the screen but the screenreader wouldn't have known about it?  I see a couple of people.  Does anyone how to fix that?  How do we tell a screenreader that something happened higher up?

The way that I will typically do this it in JavaScript you will have the abilities to focus an element.  And when you focus something, it moves the screenreader to that point.  And so, if, for example, in your quiz you press the question button and then using like JavaScript you're replacing the contents and you need to let the screenreader know, you can set the focus to the top of the question and it will cause it to move up there and start again from the top.

AUDIENCE: But on the flipside, wouldn't that be impacting    if someone wanted to go through the questionnaire that was reading it visually and they want to stay on yes, no.

THOMAS: This is one of the few cases you would turn off the focus ring in your styles.  Because it's    there's a style for focus, right?  And usually that    and you see that as the ring that's around things.  Like, if you design websites a lot of times you'll unset that for buttons, do not do that.  Do not unset focus styles.  People use that with keyboard navigation otherwise they don't know what it is that they have selected to hit enter on.  But what you can do, if it's not an interactive element.  So, like the top of your question is not a thing you can tap or click on, you can turn off focus styles for that.  But you can still focus that element to move the screenreader up without visually indicating for people who are reading it that it's actually moved the focus up.

So, the only thing that would happen would be form controls would be blurred, but that's okay.

JOANNA:  There's an ARIA attribute for a state that's changing and something in the page changed for something later.  I think it's ARIA live.

THOMAS: ARIA live and role equals alert.

JOANNA:  When something changes later in the page and causes something earlier to change, it can read out the change.  There's two different modes.  One is called polite and the other one is something else.  I don't remember what it's called.  Polite is the screenreader continues to read what it's reading.  When there's a pause, it will go back and tell you something changed.  The other one yells at you right away.

THOMAS: It should be rude, but it's not.  I think it's    anything else?  Good or bad that you noticed?

AUDIENCE: So, today it was scrolling.  And it's so bad because like everything you do as positive equals zero is now supposed to speak out.  It does speak out.

THOMAS: So, passing a zero to the screenreader doesn't affect it.  There is a link in the Etherpad.  One of the places I go once a week, a blog post by an accessibility consultant is a way to hide things in a modern browser.  There are ways to hide it so that it's visible but not accessible to screenreaders.  And then there are ways to do the reverse where    and I actually really like using opacity.  The example that I have in there for my good example, which is fine, is a stepper.  And so, it has like next and previous buttons.  And the previous isn't shown on the first slide visually.  But I set it to be invisible using opacity because I want screenreaders to let you know there is a previous button available.  Because it's not going to go back up and tell them when I change that style.

So, it's kind of like those disappearing mint news in Microsoft Word a few years back.  Where did the edit command go?  It got rid of it because you didn't use it and you had to hunt for it.  Don't make people do that with the screenreader.  It can be good to say this is invisible with Opacity zero and that blog post walks through the options.  It's great.

AUDIENCE: And the other thing is I think screenreader reads from top to down.  I think and the HTML sequence.

THOMAS: Yes.  Source order is important.

AUDIENCE: And so scrolling is    you have the background layer and then you have the layer on top.  And the layer on up to never speaks up until you finish the background layer which is   

THOMAS: Yes.  Yep.  That's definitely a thing.  And we do a lot of scrolling stuff.  And for me it's really    yeah.  Finding a way to make it so that those things can be ordered internally so that it's sourced.  Because it will pay attention.  And if you use something like Flex or Grid and you rearrange using those orders, the screenreader still ignores it.  Which can actually be really helpful because it does mean that you can rearrange things visually but show them to a screenreader in an accessible way.  But it can also mean that you thought you were able to arrange this thing and you were like, yes, I have order and you do not.  For a chunk of your readers.

AUDIENCE: With regard to that, some of our publications at Conde Nast we definitely had a heading H1s inside of our body text.  Causing the screenreader to read the H1 and skip all of the body text between there and the next H1.

THOMAS: Oh.  Were you in headings and landmarks mode?  It shouldn't do that.

AUDIENCE: No.  It just jumps to the H1 to start.

THOMAS: Okay.  That's behavior I haven't seen.  That sounds terrifying.  That makes sense.  I never understood the point of using the section tag.  I don't understand.  And what I noticed    I went through before this session, like I was going through different sites in a screenreader to try to find good and bad examples.  And I'm actually really surprised, sites have gotten a lot better.  But one of the things is like when you hit an ad or something like that and sections are really great because they act as landmarks.  So, you can use those to skip down without having to worry that if I go to the next header, is it going to take me all the way to like social at the bottom of the page because that's the next H1.  Yeah.  David?

AUDIENCE: I was going to say, the piece that I brought up with was a multi faceted interactive graph.  And there was in it    there was a list of 99 items that had    99 items that more than one word labels.  Add multi word labels.  And then each of them also had an image with them.  So, the first    when we were going through it and I was trying to skip past them all it was just reading out 99 things.  And then you type on the 100th that 100th swipe and it starts reading out 01.eng, 02.eng.  That was an unfortunate   

THOMAS: That can be frustrating.  One thing   

[ Laughter ]

One thing that can    so, you should always specify.  Like, this is a good lesson.  You should also specify alt text for your images because otherwise it will read the file name.  If it's 00 dot    or leaflet tiles.  It will start announcing all of the six digit numbers and it's not useful to you.  Two things that you can do.  One, you should always use alt text.  But sometimes we have images where they would not be really useful.  Like a classic example for me would be like a really designed like pull quote in a page that doesn't serve any purpose if you can't see it.  So, if you have an image and you set alt equals and then empty quotes, that will signal to the screenreader that this image is simply decorational and it will skip it.

And if you have images    and I do this a lot    if I have a list and I suppress the bullets and provide my own bullet as an image, the screenreader doesn't need to know that.  Like, I can just say this image was decorational and it will know it's a list item and handle it correctly.  But, yeah, that's definitely a problem that I have run into.  Anything else?  Yeah?

AUDIENCE: Do screenreaders for desktop computers function differently than mobile?  Are there different design principles?

THOMAS: So, the screenreader for Mac is also VoiceOver.  It doesn't use gestures, but it is the same kind of like speech and accessibility engine.  The behavior is really similar.  It's still going to effectively flatten your site into a single list.  It's not going to tell you that things are side by side.  And that behavior will remain the same.  The way you interact with it, you can use the mouse.  And some of those things can be a little bit easier.  On Windows NVDA is the free and open source screenreader.  And it behaves fairly similar to VoiceOver in that like if I use the mouse and I move around the screen it will describe where it's kinds of like exploring by touch.  So, it'll tell me what my pointer is over.  And then if I activate a window, it will try to read the window to me.  That kind of thing.

It's different.  I have been daring myself to code through a screenreader and I can never work up the nerve to do it.  We have like fairly few good things.  Does anyone want to like    which is fine.  Like, this is a learning experience and there's no shame.

AUDIENCE: This is something very, very small.  Like a lot of the text things in a table were read like the down arrow and an asterisk.  But there was like a number with commas, a million number, and I was afraid it was going to be like 1, comma, 6    but it read it as   

AUDIENCE: It was really easy to understand the numbers.

THOMAS: One of the other nice things about tables actually is if they are labeled with like a table header, many when it says a value, and especially exploring by touch, it will say the value and it will actually say which column or row it's in.  So, that way people don't have to remember like the rows.  Because I was looking at something and it would be like 1 million and then it would read lying the header was percent or something.  Obviously 1 million percent was not right.  But it'll do something like that.  So, using tables for what they're meant for really is the right thing to do for a lot of this stuff.  I feel like that reminded me.

The flipside of that, if you ever land on an embedded Tweet it will try to read the Tweet ID and interpret it as a number.  1 trillion, 398 billion.  Oh, my god.  That's in there like four times.  You listen to this number a lot.  It's really, really awful.

AUDIENCE: I have a question.  Is there a way    if we want in a table, there's not a lot of space and have percent as PCT, is there a way to have the screenreader read it as a full   

THOMAS: Yes, you could have the physical label but use the group to set that as invisible to screenreaders.  You have two labels, but only one shows up.

AUDIENCE: We have this at the FT because the letters get read F and T as featured.  We have an invisible label that has the F and then a space and then the T.  So whenever you're seeing the word FT on the screenreader, it reads it as two separate letters rather than featured.

THOMAS: Yeah?

AUDIENCE: Yeah, as much as I hate making AMP passage, I found AMP was easier on screenreaders.  Because they are pre built in.  And it was easier to navigate.

THOMAS: Yes.  That's very true.  If it's done well and especially if it comes from the big software companies, they're going to invest in that.  And you feel bad because you're encouraging AMP, but on the other hand, it is built in.

AUDIENCE: That's the most positive thing I have ever said about AMP.

THOMAS: Anyone else, and then group discussion?

AUDIENCE: One more thing, there was a section of the same graphic that came down and had isolated elements that had blurb test about what was in it.  And some of those were pretty successful in describing what was above it.  They said that you didn't actually see it.  And in using    I can imagine it would be even better if you combined the strategies to hide certain things that would be just taken for granted.

THOMAS: Yeah.  Yeah.  I think that's a good point.  I actually    I often think that this is a good cut the mustard text.  If your graphic could be read in the screenreader without needing images, are they adding value?  Or are you feeling better?  Maybe work on it to add value.  I'm to the saying that for you, I'm saying that for me sometimes.  Okay.  Great.  Cool.

JOANNA:  Oh, yeah, now that we've talked about what we like and didn't like, at your tables, join a table with people at it, what are common visualizations that you have been able to makes accessible?  What are some kinds of graphics that have been difficult to adapt?  What are some easy strategies that you've used to educate your teams after that activity?  We're going to give you about ten minutes to do this and we're going to come back as a group and talk about it.  Yeah, if you can get into groups and we'll keep this up.

THOMAS: The kinds of things your newsroom does a lot, are those things accessible?  How could you fix them? 

[Group work]

THOMAS: Hey, everybody.  So, we're just about out of time.  We would like to ask you for two things, one, if there's been good information or good questions that up, could you put them in the Etherpad for the session.  We hope to get information on what newsrooms are struggling with and, B, how they're approaching the problems.  And second, for each table, could we get kind of like thing you were discussing or problem you were solving that the whole group might be interested to hear about.  We can just go counterclockwise starting over here.

AUDIENCE: Speaking for myself, we were talking about how it would be difficult to kind    might be with this starting off from all of the work for all of our organizations.  But there is just maybe templates that we work with or best practices that we could at least get sort of like some baseline accessibility standards implemented so it's a little bit better and work from there.

THOMAS: Yeah.  Cool.  Over here.

AUDIENCE: So, we talked about how the    we were talking internal tools.  Some very easy to do.  Like think about accessibility when you design these tools.  Like we have the Apple charts at work.  And I don't think that when they design the charts that they're thinking about adding these accessibility.  And that can be easy.  And that can impact all the charts in our stories.  And like you can have that added there.  And then also like using them across all of these newsrooms.  So, like a map on all the levels, so, like, how you can add one line to say you don't speak them out.  That would be very helpful.

THOMAS: Yeah.  Sure.

AUDIENCE: So, we were looking at a branded content piece that I did for Canon cameras and we didn't have any alt text on the images.  On the very minimum, it's a visual story.  Probably do some alt text.  That would help get the point across.

AUDIENCE: We ended up having an interesting conversation around    I had the question of, for pieces that have an audio feature where, you know, there's a player that has just a produced version of that piece or on NPR when there's an audio clip, you know, for the main piece but then there's also a transcript on the bottom, are folks building for ATP and audio first experience?  So that the player just plays and the voice reader reading that transcript?  Or reading the piece when there is a produced piece that you could be listening to.  So, curious if anyone has answers to that.  And if not, think about it.

THOMAS: Sure.

AUDIENCE: We don't have solutions.  But we were discussing how to work with them if you're doing stories where you're using visualizations.  How you would explain them.  Like having a table for visualization is also not that useful.  Or, like, doesn't make sense.  So, we just discussed that.

AUDIENCE: I just had a question which was if there are any useful guides to best practices for writing alt text.  There probably are, but I've not been able to find one.

THOMAS: Fair enough.  I don't know that I have one either.  So, if anyone has one    Joanna has got one.

JOANNA:  I'll drop one into the Etherpad.

AUDIENCE: We talked also about whether or not there is any possibilities of using audio as a means of describing graphics.  Like whether or not a graphic artist could record a description of what a map is showing.  Which oftentimes would be helpful for readers visually saying something on the page too.  But another thing was looking at input features and whether or not you could use voice as a means of inputting an address to a map.  Or some kind of calculator.  We like calculators.  That's something we could possibly use.

THOMAS: Just out of curiosity, raise your hands if you have used voice control on the computer?  Only like    again, like I had really bad carpal tunnel.  It is worth loading up on Windows which comes built in with voice control these days it's really interesting to use one just completely by voice.  You feel like you're in Bladerunner.  It's cool.

AUDIENCE MEMBER: We talked about the workloads at our organization.  It's just not embedded right now when we develop interactives or whatever content we have.  So, the question comes to how do we get the resources?  Do we need a copy editor or do we test it the responsiveness of the design?  Yeah.

THOMAS: That's okay.  All right.  Yeah.  Thank you so much for coming to our session.  Please keep this going.  I would really love for the industry to just have like more of a conversation around accessibility.  I know we have been talking about this a little.  But I want to bring all of you into that.  And hopefully see you at the table.  So, thank you.

[ Applause ]