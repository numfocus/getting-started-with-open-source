# How to Organize an Open Source Sprint
By Julia Meinwald

I work at Two Sigma as an open source coordinator, so part of my job is getting more people at the company to try contributing to open source.  An event like this is referred to as a sprint or hackathon.  To this end, we host an annual sprint, TS Open.  Today, as I sit at the NumFOCUS Unconference on Diversity and Inclusion, I learned that open source sprints like this happen all the time.  These sprints are a great way to widen the pool of open source contributors.  Below are a few quick guidelines for setting up your own!

### What is an Open Source Sprint?
An Open Source Sprint is a short event, typically lasting 1-2 days, where groups of people get together to work on one open source project.  The people will generally use this time to add content and fix bugs for the project.  There will typically be TAs from the project community to help out, answer questions, and facilitate the acceptance of the contributions in a timely manner.

### Who can organize an Open Source Sprint?
Anyone!  This is something that can be done within your own organization, at a Meetup group, at a Hackathon, or at a college computing club.  Anyone that has a group of technologists can organize an event of this type.  It will be a great resource to both the Open Source community as well as all of the participants.

#### Step 1: Select Your Topic/Project

When we set up our annual hack day, the first thing we think about is  what we want to hack on.  Since the events I plan are for Two Sigma employees, we think about what projects are widely used at Two Sigma.  We assume people will be more motivated to hack on something they actively use. What languages does one need to know to contribute to these projects? We also take a look at open issues in the project.  Are there issues that a beginner could easily tackle? Pull requests that could be submitted after a single day of work? Our hope is that the sprint will build momentum for continued contribution, but we also like the satisfaction of being able to complete a pull request at the event itself.  Does the project have good documentation? This can be important, too, in selecting a project that will be fun and accessible to work on. At Two Sigma, given the considerations above, we picked [Pandas](https://github.com/pandas-dev/pandas) for our 2016 sprint and [Jupyter](https://github.com/jupyter) for our 2017 event.  

#### Step 2: Reach out to Core Contributors

Once we know what project we want to work on, we reach out to core contributors on the project.  This might sound scary, but in my experience has been super easy.  I’ve just googled who the core contributors on the projects were, and cold emailed them explaining what we were planning.  In both cases, I got enthusiastic responses back! We were lucky enough to have a small budget for our event, so we could invite a few people to fly out for our event.  If this isn’t the case for you, I’d ask the core contributors if they can recommend anyone in your area who contributes to the project.  Having an expert there for the event itself was Super helpful for us -- people could ask them questions as they arose mid-hack, and it showed that participants’ contributions were being seen and valued, which was great for morale. 

We collaborated with core contributors on the project to put together a list of suggested issues for our sprint.  As I mentioned above, we were looking for issues that could be tackled in a single day, with a special focus on beginner-friendly issues.  It’s helpful if the project you pick already has some sort of system for tagging issues with difficulty levels. If the project you’ve chosen is a large one, you might also have decisions to make about the scope of your event. (Are there projects related to the one you chose that people might also want to hack on?)   A narrower scope can give a greater sense of purpose and make prepping for the event easier, but broadening the scope can make the event more accessible/interesting to a wide group of people.  

#### Step 3: Set-Up Talks and Trainings

In the weeks leading up to our hackathon, we host a talk and a workshop.  For the talk, we invite a core contributor to visit and give a presentation on the project’s history, features, future road map, etc.  It’s basically meant to inspire people to become users and contributors.  Ideally, this speaker might be the same person who acts as a facilitator for your hackathon, and this is a chance for that person to get to know participants in advance. We also host workshops in which we walk people through the open source contribution workflow.  During these workshops we also help people install and get setup with anything they will need to hack on the project, so when the day of the hackathon comes they can start hacking right away, and don’t need to sink time into setting up their environment.  You can consider other programming leading up to your event, too.  For example, this year, we’re considering hacking on a project written in Scala, so we’re thinking about running a Scala study group starting a couple of months before the hackathon.  

#### Step 4: Logistics and Fun

Secure a place and a date for your event.  Think about whether you want attendees to attend in person, or if you want people to attend virtually.  Since we held our events with everyone in the same place at the same time, these are some of the issues we thought about: Where will the event be?  If you work at a company, perhaps they have a meeting space you can use. You can also check whether other companies routinely open their spaces up for events like this. (Two Sigma, for example, sometimes hosts open source meetups in our space for no cost to the meetup organizer) You want to make sure that you have table space, chairs, power outlets, and adequate wifi for your participants, and to make a plan for breakfast, lunch, and dinner.  

##### Step 5: Communicate

I recommend setting up some sort of wiki or Google doc announcing your event with links to the project you’ll be hacking on, the issue list you’ve curated, and a place for people to sign up in advance to work on certain issues. Clearly set out any pre-requisites for participating.  If possible, link these with ways to meet the prerequisite (i.e., if you need to know Python to contribute, you might link to an intro Python course on Coursera.) Don’t forget about material prerequisites. For example, if everyone will be hacking on their personal laptops (as is the case for our events), make that clear.  Also provide clear instructions for anything people will need to do to set up their computing environment and encourage them to do this prior to the event.    

Publicize your event! Again, if you’re planning this within a company, internal forums are a great place to start.  If you’re planning a wider community event, you can spread the word at places like meetup.org, Facebook, or LinkedIn.  Set up some way to count RSVPs so you know how many to prepare for wrt food and space.  

Finally, you’ll want a way to share your progress after the event. Think about writing up a blog post -- maybe you can even do a co-post with the project core-contributor(s) you worked with! If people encountered interesting problems while hacking, perhaps you want to hold lightning talks where people present their pull requests.  Keep track of how many participants you had and how many accepted pull requests the event generated -- these metrics will be great for talking about the event after the fact.  (At our Jupyter sprint we had about 30 participants and 31 accepted pull requests.)  

#### Step 6: Keep the Momentum Going

Look for ways to keep the momentum going after the sprint.  At Two Sigma, we host a weekly hack night, with in-house experts there to help people get started or answer questions.  We’re still wrestling with ways to keep people involved once they’ve started at a sprint -- any ideas you have would be appreciated! 

I hope these guidelines were helpful -- we’d love to hear about what events you host and anything you learn from the process! 


### Experiences

Here’s a link by first time contributor Noemi Derzsy at a [scikit sprint](http://wimlds.org/noemi-derzsy-scikit-learn-sprint/) in New York City.  

Bloomberg annually hosts an open source day.  Here’s a link to [Bloomberg and Open Source:  Collaborating on Better Developer Tools]( 
https://www.bloomberg.com/company/announcements/bloomberg-open-source-collaborating-better-solutions-code-management/).  Over 30 employees participated in the Git sprint. 


