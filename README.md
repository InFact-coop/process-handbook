# Process Handbook

This guide is borrowed and built on the guide created by our friends [@dwyl](https://github.com/dwyl), thanks so much for open-sourcing your processes for the betterment of tech projects everywhere! :)

Contains our processes, questions and journey to creating ateam.

This is very much a work in progress. Please [add an issue](https://github.com/dwyl/ateam-master-reference/issues) for anything you would like to see discussed here!

All of this is predicated on the assumption that **you care about your clients** and you **care about delivering quality code**. Go into this with a positive attitude!

## Contents
- [Introduction](#introduction)
- [Responsibilities](#responsibilities)
- [Ceremonies](#ceremonies)
   - [Stand-ups](#stand-ups)
   - [Sprint demo](#sprint-demo)
      - [Sprint demo prep](#sprint-demo-prep)
   - [Retrospective](#retrospective)
   - [Sprint planning](#sprint-planning)
      - [Sprint planning prep](#sprint-planning-prep)

## Introduction
This README covers the **responsibilities** and **ceremonies** of a scrum master.

### Time needed to Scrum Master a project

Depending on the size of the team, scrum master work is likely to occupy **2-3 days per 10 day sprint**.

**This may consist of:**

- **30mins - 1 hour a day** (stand-up, backlog grooming, lifting blockers, scheduling next meetings etc.)
- **30 mins - 1 hour per sprint** doing sprint demo and sprint planning prep
- **1/2 day per sprint** in sprint demo/ retrospectives/ sprint planning

## Responsibilities
So what is a scrum master responsible for?

- **Total understanding of the problem (that the product is trying to solve)**
- **Lifting blockers** aka making sure the team has everything they need to progress with their work. For example, ensuring there are:
   - no outstanding external dependencies
   - all the designs, copy, login/card details needed
   - decisions made on issues that are in discussion

**Why?** Developers may not know the status/details of all issues at all times.
You must ensure that issues are ready to be worked on, whenever they come to them.
This prevents time being wasted chasing or clarifying things when the team come to work on them.
- **Enabling the team to focus on coding rather than project management**
   - Ie. the SM should be responsible for stopping scope creep or liaising with the client over wider project issues so that the team can focus on executing issues that they know are ready to go.
- **Enforcing good gitflow across both teams**
   - Ie. making sure the client is using github as dwyl sets out and that the team are too (correct labelling, good commit messages etc.)
- **Full knowledge of the product backlog to enable them to efficiently do backlog grooming, sprint planning and time estimating.**
- **Backlog grooming**
   - Ie. making sure the backlog doesn't have duplicates, issues are correctly labelled (prioritised, time estimated etc) and have clear and full descriptions with wireframes, designs or assets where appropriate, that new issues are created rather than tagged on to old issues, asking any outstanding questions.
- **Setting up project meetings**
   - Ie. when/ where sprint demos/planning or other client meetings, stand-ups take place.
- **Agrees sprint scope during sprint planning**
- **Client communication, on hand to answer questions that may arise**

A SM does not have 'authority' over the team, they work collaboratively with them. When the team needs direction to keep on track with the sprint milestone or with good gitflow practices they should be guided not forced! 😊

## Ceremonies
**Ceremonies** are the events that the team take part in every sprint. _Note:_ whilst valuable, ceremonies are just a portion of what it takes to run an agile project.
Following the ceremonies in isolation does not mean you work in an _agile_ way.

## Stand ups

### What is the aim of a stand up?
Stand ups are simple beasts, though often misunderstood. The aim of a stand up is a **quick update for the whole team
to ensure everyone is aware of what the team is working on, can understand where support is needed
and ensure priorities are aligned**.

Remember that 15 minutes of 4 people's time is actually an hour of time the client has to pay for.

> A swift and focussed stand up is the key to a team's effective collaboration.

They should quickly cover what each team member has worked on since the last stand up, what they plan to be working on until the next one and crucially, whether there are any blockers.

#### A stand up is _not_:
+ For the scrum master (or product owner) - a scrum master already knows what the team is working on because it's their role to stay ontop of the backlog; **this is an update _for the whole team_ to ensure everyone is on the same page**
+ A planning meeting - if new [`priority 1`](https://github.com/dwyl/labels#labels) requirements have surfaced or a feature absolutely _must_ be discussed in detail, a **short call or conversation should be organised for _after_ the stand up with the relevant developer(s)** rather than being discussed on this call
+ An opportunity for **micromanagement** - a scrum master is not a 'project manager' and our teams do not need to be 'told what to do'.
A scrum master clarifies priorities, helps the team think through
potential risks and solutions and ensures they are making progress towards removing blockers that keep the team from working
+ The time or place to ask lots of questions about a feature - **questions should be captured in the relevant issue and discussed with the relevant developer**
rather than when the whole team is on the call; if there is a particularly complex issue that requires more conversation,
a separate call should be set up with the relevant parties after the stand up

### Running stand ups
- Scheduling stand ups is the SM's responsibility
- To be held daily at the beginning or end of the day
- Should last approximately **2 - 4 minutes per team member**
- Can be done remotely via a remote conferencing tool, such as google hangouts, for which screensharing is recommended so people can see what everyone's been working on
- Should be done with the scrum backlog open and referring to issue numbers

**Each team member briefly summarises:**
  - The issues they've been working on that day
  - What issues they intend to work on the following day
  - Whether they experienced any blockers, know of any _risks_ with the issue they are working on or have any questions for the team

**The scrum master should:**
  - Update the team on their progress lifting any blockers e.g. progress getting an outstanding external dependency from the client.
  - Ask questions as the team show the work they've done that day where relevant (ie. Does that change therefore impact the timelines/effort for this other feature in the sprint? What is the result if the user chooses not to fill in all the fields of that form? This seems like a big change that would be useful to future developers on the project, should we add that to the documentation for the project?) - notice this is *not* about 'managing people and tasks' but about helping the team to work together
  - Ensure the team is on track and tackling the priorities set out in the sprint milestone on github and redirect them if they're going off track. E.g. there are 2 days of the sprint left, have we made sure that all the `priority-2` issues have been covered before we move to the `priority-3` ones?
  - Check whether the team has any new blockers or questions
  - Ensure the team stay calm and be pragmatic in times of stress or changes.

## Sprint Demo

At the end of every sprint there is a **sprint demo** with the client. During the demo the client is shown the completed user stories for the milestone.

### Sprint Demo Prep
+ **Time Boxing** :clock3:
Before the demo, set the expectation of how long you think the demo will be through a calendar invite. A typical demo might last 30 minutes. The demo duration includes the demo itself + any questions following it. Time boxing shows that you’re organised and prevents any inadvertent time wasting. It gives you a reference point that you can point to if you notice that you’re running over time (_a passionate client can talk for hours if you let them!_)
+ **Location** :house:
Ensure that you're holding your sprint demo somewhere where you and everyone involved has good access to a screen displaying your milestone / issues on GitHub.
Unless you are *constantly* referring to the project board (*in our case the GitHub issues list*) it's *very* easy for people to get side-tracked. We/You need to ***constantly re-enforce*** the team looking at the project management ***system*** to ensure it gets used appropriately, otherwise chaos ensues rapidly.
+ **Decide who will be driving the demo** :blue_car:
The demo will usually be introduced by the scrum master or the product owner (_the person with the most demo experience on the team_). The demo will then be handed over to the developers who have been working on it as they begin to go through the user flow. At any given time, the person with the most experience on a certain aspect of the application should be talking about it.

  We recommend that the person who is talking is a different person to the one driving (performing the actions in the application). When using the application it can be easy to stop interacting with the people you are demo-ing to and speed up the pace of the demo as you click through an application you personally know well. This will need to be prepared and practiced in advance.
+ **Do a run-through of the demo** :loop:
Once you've decided who is driving/ speaking you should do a run-through. This is where you'll pick up all of your problems around flow and most importantly, unexpected bugs that you don't want showing up in the actual demo. Make sure you think about including mobile/responsive views into your walkthrough.
+ **Recap on lessons learnt from previous demos** :rewind:
It's always good to reflect on what worked well in the past and also what didn't. This can help you avoid mistakes you may have made before and also leverage the things that went particularly smoothly. Make sure you have someone taking notes for you during the demo so that you can focus on delivering it at the time, and then you can review your performance afterwards.
+ **Remind yourself of the project status**
Review your backlog and take note of all the work you have done in the sprint.
+ **Have all changes merged into `master` at least half a day before the demo**
The rushed changes you make in the last half a day are usually the changes that break everything and cause stress during the demo. Your last day/half a day should be for polish and bug fixing from the merges, not for functionality.
+ **Know your audience!** :busts_in_silhouette:
Be sympathetic to who you're delivering your demo to. If they aren't technical then they won't appreciate any of the technical detail that you could go into. Your job is to be prepared for any technical questions that may be asked but it shouldn't be the focus of the demo. Don't describe what it is, describe how what you've done adds value to their application.
+ **Have prepared notes/script** :page_facing_up:
Prepare notes/ a script which details what you're going to cover during the demo to help you feel prepared and calm during the demo and to ensure that nothing is left out.
+ **Determine who'll take notes** :clipboard:
Determine who, how and where your team will be taking notes throughout the demo so there is no confusion at the time as to where feedback you receive should be captured (we recommend GitHub issues).  

### Guidelines during the Demo:
+ **Link your scope**    
In your walkthrough try and tie all of the work you've done to the proposed scope (milestone). If you haven't completed all of the deliverables that you've agreed upon make sure that you have a think beforehand about what needs doing, and how you're going to solve this moving forward.
+ **Breathe, be calm and deliberate**  
This can be nerve wracking and taking some deep breaths will help slow you down! You're likely to have lots of nervous energy and excitement (particularly when a project has incurred a problem). If you're calm, you will calm down your client and portray confidence that you can handle the issues. A great way to help you remain calm is to ensure you're well prepared (see the guidelines above) for the demo.

## The Demo
1. Begin **screen & audio recording**
2. **Context** of the sprint/demo
3. **Walkthrough** of the product
4. **Review** the stories completed in the sprint (*let the person who did the* ***work*** *do the talking*)
5. **Close** the sprint **milestone** on GitHub (once all of the stories on the milestone are marked as complete)
6. **Wrap up** the demo
7. **Invoice** the client (*ASAP*)

#### Step 1 - Screen & Audio Recording
Before you start the demo start a screen & audio recording. It's useful in case you don't get the chance to write notes or if you need to share the session with an absent team member. Recordings can also help you review and improve your sprint demos for future instances.

#### Step 2 - Context
Start the demo by providing some introductory context such as what the aim of the sprint was and what you'll be demonstrating. The purpose here is two-fold; it sets up the demo but ***more importantly*** it allows attendees time to gently switch their attention away from their previous tasks (or meeting they have just come from), slow down and focus on the task at hand. If the demo isn't going to look like what the client was expecting (minimal styling for example), ensure that you explain this before you start so that they have a bit of time to digest why this is the case (***reduce the shock factor***) and what you're going to do about it.

#### Step 3 - Walkthrough
Walk through the proposed demo, paying close attention to:
+ Picking up on any small niggles the client may notice, can you pre-empt the client bringing it up by proposing a solution as you're doing the demo?
+ Are there things you're actually still not 100% sure are working the way the client intends? Ask the questions during the demo so they know you're looking out for their needs
+ Mention all of the work that has been done (especially if additional work has been done that wasn't originally expected)

#### Step 4 - Review the Stories
This part of the process will be repeated for each of the stories listed under the sprint milestone. Start with one story. For each story you have a couple of possible actions to take:
- **If the issue is already closed:** quickly talk through how the delivering the story has gone and
confirm whether the original time estimates were met (*or why the task took more time than originally predicted*).

Estimating and tracking time is the ***single*** most important factor to manage in a software project, it's how we show the Product Owner / client that we are providing value-for-money and helps us to plan future sprints with *any* degree of accuracy. This is where other teams fall down.

Don't spend too long on each issue, whilst it's important to let the client know what progress has been made, make sure there's enough time left to cover the things that need their input and discussion.

- **If the issue is still open:** discuss why it is still open, how long it's been taking to complete and what still needs to be done (and how long that will take). If the issue is still relevant and in need of imminent completion remove it from the current sprint milestone and label it for the next sprint milestone. When you move the issue make sure you leave a comment within it which explains the current progress on the issue and why it's being moved to the next sprint. If the issue is now no longer a priority or something is blocking it and will be for a considerable period consider placing it in the backlog milestone.

In both instances ensure you mention what was learnt along the way.

#### Step 5 - Close the Sprint Milestone on GitHub

Once the previous sprint's stories have been reviewed and moved to the relevant places your milestone should now be 100% complete. At this point you should **close** the **milestone** on GitHub:
![please-close-completed-sprints](https://cloud.githubusercontent.com/assets/194400/11141396/dd7dcafa-89dc-11e5-9b08-014af837a38a.png)

#### Step 6 - Wrap Up the Demo
Once you've completed your run-through of the demo, recap on what you've talked about and then ask if there are any questions (_from either side_). Discuss your plans for the next sprint in terms of deciding on a date to confirm a new scope of work. When you're finished don't forget to stop your screen & audio recording session.

#### Step 7 - Invoice the Client
As soon as the Product Owner (client) is satisfied that the agreed stories for the sprint have been delivered, prepare and send the ***invoice before anything else***. NB. This may not fall as the responsibility of the SM.

## Retrospective

- A retrospective is held after the sprint demo
- Can be held either all-in-one with the client or in two parts, one with the client, one without depending on the client/team's preferences.
- They should last between **10 - 30 mins**.
The duration varies according to the size of the team and often may be longer earlier on in a project when the team is settling in.
- During the retrospective each team member should have the opportunity to share things that they felt **went well**, **not very well** or things that could be **improved** based on the last sprint.

## Sprint Planning
Spring planning is when you review the backlog and client's priorities to outline what will be put into the next sprint milestone. This may be done immediately after a sprint demo and retrospective or otherwise on a time/date agreed at the end of the sprint demo.

### Sprint Planning Prep
- _Prior to sprint planning_ you should **ask your Product Owner to prepare and prioritise the backlog** with user stories and acceptance criteria for each issue
  + This is **crucial** to increase the efficiency of the sprint planning session - it allows a team to come into that session fully prepared with questions and having already put some thought into the most complex issues
  + Remember that **these priorities may change during sprint planning itself** as you discuss the issues with the PO and incorporate technical expertise into prioritisation - _sprint priorities should never be decided unilaterally, they need to be discussed as a team_
- To aid the time estimating process, we recommend spending 30 mins the day before the sprint planning to familiarise yourself with the issues that will need time estimates so that you can discuss more complex with the team in advance.

### During Sprint Planning
- Time block **1 - 1.5 hours** for the sprint planning session.
- Discuss upcoming deadlines and **agree on the next sprint duration**. Generally we work in 2 week sprints however from time to time if a deadline dictates that this is no possible, we may work in a shorter sprint ie. a week. Be cautious when considering running longer sprints, sprints are called sprints for a reason and are not designed to be extremely long periods!
- The **aim** of sprint planning is to **recognise the highest priority issues and how long it would take to complete them**.
- Review how many / any **issues** you may already have added to the milestone that were **unfinished from the previous sprint**.
- Review your repo's **issues** paying attention to the **priority labels**. Alter the priority labels so that last sprint's `priority-3` are now this sprint's `priority-2` (and so on). Only assign a realistic number of issues to the sprint (according to your team size/ sprint length). If there are too many of the same priority to assign to the next sprint, discuss what can be delivered and ask the client to clarify in order to dictate what goes ahead.
- **Assign time estimate labels** to the issues. Estimates should be given by both developers in a team to account for potential differences in experience and for the fact that either of them may be tackling that issue. Timings are calculated as pairing hours.
- Once your highest priority issues have time estimates assigned, 8 days worth of highest priority issues (to forecast for a 10 day sprint) will be added to the new sprint milestone on github.
- 2 days in every sprint are reserved for refactoring, bug fixing and the sprint demo/ next sprint planning.
- On larger issues where estimating may prove difficult, help the developers estimate better by asking them to think about breaking the issue down into smaller chunks. Then estimate for each of those chunks and combine them.
- Remind your team that estimates should always account for testing, documentation and fulfilling project specific accessibility / browser or device requirements.
- Ensure that sprint planning is kept on track and runs to the allocated time.
- Use the opportunity to ask the client any questions that the team would need to know in order to implement the various issues.
- Ensure that issues are clearly defined so that time estimates reflect the implementation of the issue clearly. Ie. add a checkbox to user sign up so people can subscribe to the newsletter. Does this mean just add the checkbox or does this mean implement an admin dashboard to manage newsletter signs up and enable users to sign up by adding a checkbox on sign up?
- Try to bring back product conversations that may not be relevant or may not require everyone present at the meeting to help keep to time.
- Make note of the issues and time estimates for your reference (the Product Owner should create/update the issues on github but you may need the notes before they've had a chance to do this).
- Record any bugs/ enhancements that were discussed during the sprint demo to suggest as new issues during sprint planning. If it takes your Product Owner time to update github after your sprint planning the team can start working on these small issues that should be relatively straightforward to complete.
