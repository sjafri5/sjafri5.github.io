---
layout: post
title: The Software Process 
cover: cover.jpg
date:   2015-10-09 12:00:00
categories: posts
---

## --- 

The process to add a new feature is usually the byproduct of necessity. Josh, Dan, and Millie will express a need in terms of the software's capabilities. This is only the conception, however. David, will push back with quite a bit of effort to find ways around this issue or to outright dismiss them. He will always tell them to wait until they ask for it. I think this is a very important thing I've learned about software. Clients and the business side are whimsical in requesting new features. If one does not fight back then it is only a matter of time until the dev team is inundated with requests that end up not even being used.

When the needs are articulated with both persistence and a clear explanation on its importance this will get the ball rolling. Typically this is the stage were a design of the potential outcome is manifested. It involves working closely with the business side to determine what is the least they can make do with. In other words, we must define MVP. 

From here it would be smart to begin incorporating wireframes that reflect the MVP that was outlined in the previous step. Currently we do not do this. This is mostly because most of our requests have been features for the architecture of the app (i.e. modularity, multi-tenancy). In that case, David and I will sit and discuss the number of things that need to be accomplished to finish the task. We will sit and outline everything that needs to be done to deploy. I would call this the transition from idea to a concrete list of steps to take.

Once this list is created, there are many bureaucratic tasks that need to be addressed. All the necessary steps must be transferred over to Asana. They must be estimated and assigned. It is at this point that the developers can pick out a challenge and take ownership of it up to completion.

Let us assume the developer has finished creating her/his part of the task. Their next step is to create a pull request. The code will be reviewed by the manager. Typically they will give some advice in comments and wait until the issues are addressed. When the pull request is ready it will be accepted and merged into staging. This is where my understanding of the flow is a bit more foggy.
I believe there is an autobuild that will run and check for passing specs. Once the specs pass it will push to staging. This is where QA will take place and the business side can check up on the feature. If everything looks good then the features get manually pushed to Master.

What I think is important if I choose to take on the Front end of this application, is to create a process. What has improved our software team's efficiency is the creation of a process. This allows us to minimize the time spent in a grey area of unknown objectives and responsibilities. 
