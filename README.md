# Project: Scenario 2: 2D Sidescroller
## Secondary Genre: Roguelike

### **Meetings on Discord weekly.**

## Level Elements:
### Required (all):
- Starting Location: This is where the player will spawn at the beginning.
- Level Goal: This is the “finish line” or “goal” of the level.

### Additional Elements:
- Player Pickups (Health, power-ups, etc.) (at least 3 unique types, can be placed scattered around
level)
- Collectables (These are collectables for a power-up. For example, the player may…llect 10 keys before exiting the level.)
- Enemies (Moving) (2 types, can be moving on platforms or jumping around)
- Obstacles (Stationary) (4 unique types; scattered about the level. Will harm player or cause an
effect)

## Task Board
### [Kanban Using Taiga](https://tree.taiga.io/project/chamomilecelebi-gam-305-project/kanban)

## Module Three Project Log - Team Development: QA and Testing Plan
- Makes use of the "Ready for Test" status in the Kanban.
- Discuss testing during weekly meetings to ensure testing is done in a timely manner.
- Bugs reported on the comments for the associated task on the Kanban.
- Overall, all tracking and pass/fail will be done through the Kanban workflow.

## Module Four Project Log - Team Reflection
- Reviewing PRs went really well; reviews ensured that changes were made in a way that was sane, and the process remained consistent throughout the project.
- Bugs were identified through reviews. After discussing with the PR owner, the bug was either fixed by them or by the reviewer if it was simple enough, which helped maintain momentum.
- In terms of the QA and testing process, the approach was effective overall, though more structured test cases could have been introduced earlier to streamline verification.
- Kanbans were especially useful for keeping track of tasks. This is due to their visual nature and the way they made workload distribution and bottlenecks immediately clear to the whole team.
- The team’s initial analysis of the game design document helped clarify the scope and complexity of the project, which in turn guided the selection of tools and techniques that best supported organized development and communication.

## Module Five Project Log - Team Reflection
- Using the Kanban worked really well for organizing who was working on what and what stage of the process the task was in.
- We had a lot of problems with git conflicts.
- To mitigate the issues with collboration using git, we setup a channel in our Discord server called #lock-files where we let everyone know what files we were working on. This made sure that we could still work async while not touching the same files twice and causing conflicts.
- The biggest thing we would do different if we were to start on this project again is to not use git. Based on online research, things like svn and perforce are much more suited for Unreal Engine 5's binary files.
- As mentioned prior, using git was a huge headache.

## Module Six Project Log - Team Reflection
- The team found that using Kanban for tracking tasks and workload distribution worked very well, and reviewing pull requests helped identify bugs while maintaining momentum.
- Using Git caused major headaches due to frequent conflicts with Unreal Engine 5’s binary files, despite trying to mitigate issues with a file-locking system in Discord.
- The team carried forward the effective Kanban workflow from earlier stages but added a Discord #lock-files channel to address Git collaboration problems identified in the previous evaluation.
- Instead of Git, the team would use a version control system better suited for Unreal Engine’s binary files, such as Perforce or SVN.
- Git was not helpful because its design for text-based files led to constant merge conflicts with Unreal Engine’s binary assets, slowing down development significantly.

## Contributers
- Jordan Marine
- Joshua Scarpa
- Johnny Hernandez
- Chris Morano
