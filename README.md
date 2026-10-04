# CART470---Journal
Journal done by Alexandre Godfroy for the CART 470 class surrounding the project in collaboration with AbTeC Gallery, in collaboration with Nadia, Jeremy, Bea and Ryan. Project directory [here](https://github.com/hardtrip-jpg/cart470-abtec/tree/main)
- Week 1 - Introduction to the course, no entry
- [Week 2](#week-2--sept-16-to-sept-23)
- [Week 3](#week-3--sept-23-to-sept-30)
- [Week 4](#week-4--sept-30-to-oct-7th)


## Week 2 : Sept 16 to Sept 23

During the in-class meeting of September 16th, our group explored different approaches and solutions on how to approach the development of a new AbTeC Virtual Gallery. This meeting allowed us to create an [ideation board](https://www.figma.com/board/Kd9f3aCugF4gmAMH3zHQTT/AbTec). Through this ideation board, we established a [few questions](https://github.com/hardtrip-jpg/cart470-abtec/blob/main/abtec-vault/research/First%20Meeting%20Questions.md), which we sent to the AbTeC Gallery Coordinator Thursday September 17th. 

In the afternoon of Wednesday September 16th, Nadia and I also went to the AbTeC lab to speak with Skawennati and her team to coordinate our first meeting and also inquire about getting a "guided" tour of the existing Second Life AbTeC Gallery. We also met briefly with Arijit and Nancy, as well as got their contact information, which lead to us sending them our questions the following day, as mentionned above. 

Overall, our approach is very collaborative, and we hope to find out how much liberty we have with the project during our meeting on Septemebr 23rd. The goal is also to determine a few elements that will help us understand the direction of the projects. Those elements are mainly:
- The platform/game engine to be used
- If this is exclusively VR or cross-platform
- if it is multiplayer
- if the goal is to create a specific exhibit or a base for future exhibits to be built off of.

There is also a few concerns that we have about how to approach the project in an anti-colonialism context, as most of the team is composed from caucsian people, with at most external experience of indigenous communities. We want to make sure we are fully aware of all elements, to make sure we aren't overstepping on anything. 

After we determine these elements, we will be able to start moving forward and come up with a mock-up and plan of what exactly we want to build, and focus a bit more on how the tasks will be distributed. 

[Back to Top](https://github.com/Tigrr18/CART470---Journal/blob/main/README.md#cart470---journal)

## Week 3 : Sept 23 to Sept 30

During class, we had a meeting with Nancy and Arijit from the AbTeC Gallery. After voicing our concerns about the choice of a platform, we established that we would be making small test builds in each possible engine (Unreal, Unity and Godot), to compare the pros and cons of each workflow. Each engine had its own interesting aspect, so we wanted to have a better idea at how they balance against each other.

### Meeting Goals
We determined that we would be meeting approximately every 3 week, meaning that we would have three more meetings during the session, with some goals for each.
###3 First meeting goal
- Present the different prototypes
  - VR (engine TBD)
  - Unreal PC build
  - Unity PC build
  - Unity web build
  - Godot PC build
  - Godot web build
- Determine the engine & platform to be used for the project
- Clarify Goals for second meeting

*The scope of the build is currently to import the gallery building and the tree, adjust the lighting and place a static camera. In the case of the VR, the camera will need to be able to turn around, but the player will be static. We will implement a movement system if time allows, but we will probably only implement it in 1-2 platforms at most, depending on our favorites before the meeting.*
#### Second meeting goal
- Movement system implemented
- Determining artwork import workflow
- Test of different interaction mechanics
- Test of different text pop-up/interaction systems
#### Third and final meeting goal
- Final project (ish)
- Small changes if necessary
- Discussion of where the project may go outside of the scope of the CART470 class

### Work Distribution
In terms of the work load, we have decided of the following roles for now:
- **Communications**
  - Alex (me), Nadia if I'm unavailable
- **Unreal Engine**
  - Main: Nadia
  - Helper: Bea, Alex
- **Unity**
  - Main: Alex, Ryan
- **Godot**
  - Main: Jeremy, Bea

These roles will definitely change as we reorganize after choosing the engine in which we will be doing the final prototype. 

### Other Precisions
The main repository and its forks have been confirmed to being private on Github, to preserve copyrights and limit distribution of the 3D models provided by AbTeC. 

### Timeline
Here is a timeline of the tasks I have completed this week:
#### Communication
- **Sept 23**:
  - Email to Nancy and Arijit concerning getting the 3D models
  - establishing a meeting date for the first check-in meeting
  - discussing copyright issues of a public GitHub repository
- **Sept 24**:
  - Email to Nancy about a solution of using a private repository, and giving access individually
- **Sept 24**:
  - Email to Sabine concerning using a private repository for the main files, offering to directly add her to the GitHub to make sure no copyrighted material is made public
- **Sept 29**:
  - Back and forth & calendar invite for the client meeting of Thursday Oct. 8th at 10 AM

#### Unity project
- **Sept 24**: Creation of the Unity fork from the main repository

[Back to Top](https://github.com/Tigrr18/CART470---Journal/blob/main/README.md#cart470---journal)

## Week 4 : Sept 30 to Oct 7th

### Weekly Meeting Recap
During the class, we had a brief meeting with Sabine, in which we discussed where we were so far, and what direction the project was taking. We established the following:
- We were completing, as agreed with AbTeC, 6 prototypes within 3 engines, each engine having a .exe build and a web or VR build depending on the platform
- We explored the main aspect we are worrying about for the project, accessibility
- We have a communications manager
- We have established contact with external resources (Marc-André Hamelin from Elektra Virtual Museum0

Due to having a meeting with the AbTeC staff Thursday October 8th, we decided that we would not be meeting with Mac or Sabine on Oct. 7th, as we agreed that having input the day before the client meeting might not be benefitial as it will make us want to change things with less than 24h before the client meeting. Sabine also offered to meet thursday or friday after the client meeting, with the totality or part of the team, as needed. 

### Work done this week

I had quite a bit of trouble setting up the Unity project in the GitHub fork. I had issues with the .gitignore that would not cover enough files and not load properly when pulled, and the project files just being too big to push to the branch. I tried a few times, deleting the project and redoing it, but the issue is that the project would take 5-10 minutes to delete from the GitHub changes in the GitHub Desktop window. Ryan ended up creating the project instead, but I was still having issues pulling the project into my laptop due to the previous attempts at creating a project.

After deleting all prior files and clearing the folder, there was still some issues with pulling the data in, with github giving the following error message:
```
error: cannot stat 'Abtec_UnityProject/Library/PackageCache/com.unity.render-pipelines.high-definition@390b04b9db7c/Samples~/VolumetricSamples/Fog Volume Shadergraph/Procedural Noises/Tiling Gradient Noise 3D.shadersubgraph.meta': Filename too long
Updating 9cec6a20..2cd4ce7d
```

### Timeline

#### Unity Project
- **Oct 1**:
  - deletion and recreation of the Unity fork to make sure that it was private, following the agreement on creating private repositories.
  - 2 attempts of creating the Unity Project and failing to push to the GitHub
- **Oct 3**:
  - Attempt to pull the Unity project created by Ryan, which took quite a bit of time due to the size of the project (and my internet being incredibly slow)
  - Blockage to pull the project once data was downloaded due to previous attempt not being fully removed from the local disk
- **Oct 4**:
  - Deletion of previous attempt on local disk

[Back to Top](https://github.com/Tigrr18/CART470---Journal/blob/main/README.md#cart470---journal)

