# Hangover Games' Memory Matching Game

Welcome to the GitHub repository for our memory matching game!

1. ***Want to play it?*** The game is at [https://memory.hangover.games/](https://memory.hangover.games/)

2. ***Want to follow the development?*** See [the index issue](https://github.com/hangovergames/project-memory/issues/1)

3. ***Want to join the community?*** Join our [Discord](https://discord.com/invite/tKKMczp)!

This repository contains the frontend source code and is the central hub for tracking issues and 
developments related to the game.

## Rules of the Game

1. **Combo Points**: Earn points for consecutive matching pairs. More points 
   are awarded for longer combos, with a maximum of eight consecutive pairs.

2. **Memory Bonus**: Gain extra points for recalling a card’s position for a 
   longer time, up to a set limit based on the number of cards on the board. This 
   bonus applies only when you successfully match a card on the second attempt 
   after its first reveal and when more than two cards are open (the time bonus 
   stops when only two cards are visible).

3. **First Reveal Points**: Points are awarded the first time you reveal a 
   card. However, you will lose points each subsequent time you reveal the same 
   card without making a match.

4. **Visibility Penalty**: Points are reduced the longer a card remains 
   revealed without being paired. This penalty increases exponentially over time. 
   
   **Note**: No need to rush if all cards are paired — take this moment for a quick 
   coffee break as this penalty pauses when there are no unpaired cards open on 
   the board.

5. **Mismatch Penalty**: Points are deducted each time you incorrectly attempt 
   to pair a revealed card with another.

## Releases

Notice: Our releases in this repository contain the game server as encrypted 
self-installing release. You need to have the private key to use them. Contact 
us, if you want to host your own server.

## IFrame

You can share our game on your website using an iframe:

```
<iframe src="https://memory.hangover.games/" width="960" height="540" scrolling="none"
 frameborder="0" marginwidth="0" marginheight="0" hspace="0" vspace="0"
 webkitallowfullscreen="true" mozallowfullscreen="true" msallowfullscreen="true"
 allowfullscreen="true"></iframe>
```

## Contribution and Issue Tracking

We encourage you to participate in our development process. You can find and 
contribute to our discussions on software development through our [Issues 
page](https://github.com/hangovergames/project-memory/issues). Here, you will 
encounter three main types of issues that guide our work:

1. **Development Overview Issue:** Tracks the overall development progress of 
   the game.

2. **Next Release Issue:** Pinned to track the forthcoming iteration of 
   development.

3. **Backlog Issue:** Contains all tasks and developments pending allocation to 
   a release.

### Community Engagement

Join our community on [Discord](https://discord.com/invite/tKKMczp)!

Additionally, we contribute to 
[the HyperifyIO project](https://github.com/hyperifyio), which maintains its own 
[Discord Server](https://discord.com/invite/UBTrHxA78f).

### Issue Hierarchy

Our product management is streamlined into four levels of issues, ensuring 
clarity and focus in our development efforts:

- **Index Issue (`index`):** Serves as the master tracker for all development 
  activities, including project and backlog issues.

- **Project Issues (`project`):** Represent a development iteration or release, 
  encompassing various tasks and bugs.

- **Task Issues (`task` or `bug`):** The primary unit of work, ideally broken 
  down into manageable steps achievable within a single release.

- **Subtask Issues (`subtask`):** Detailed components of a task or bug, either 
  tracked as separate GitHub issues or as checklist items within a task issue.

### Work Estimates

We adopt a straightforward approach to estimating development progress through 
[ticket 
counting](https://info.thoughtworks.com/rs/thoughtworks2/images/twebook-perspectives-estimation_1.pdf). 
Experience shows that detailed time estimates are often unnecessary. By 
splitting tasks into the smallest feasible units, we find that the average 
completion time becomes a constant. Assuming an average of one (1) story point 
per item, we standardize all tasks to this value, simplifying our estimation 
process to merely counting tasks/subtasks. This method has proven effective and 
efficient, allowing us to focus more on actual development work.

### Source Code

While the complete source code for the game is not publicly 
available, we and our parent company [Heusala Group Ltd](https://heusalagroup.fi) are 
open to crafting similar websites for interested customers under a commercial 
agreement.

Our development stack is rooted in modern technologies such as ReactJS, NodeJS, 
and Golang, which enables us to deliver highly responsive and scalable 
websites. 

For those interested in leveraging our expertise for their own projects, we 
invite you to [contact our sales team](https://www.heusalagroup.fi/contact) for 
a detailed discussion and to request a quote. Our team is dedicated to 
providing you with a solution that not only meets your needs but also surpasses 
your expectations in terms of quality and security.
