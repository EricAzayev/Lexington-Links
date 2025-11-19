# Milestone 4

This document should be completed and submitted during **Unit 8** of this course. You **must** check off all completed tasks in this document in order to receive credit for your work.

## Checklist

This unit, be sure to complete all tasks listed below. To complete a task, place an `x` between the brackets.

- [✅] Update the completion percentage of each GitHub Milestone. The milestone for this unit (Milestone 4 - Unit 8) should be 100% completed when you submit for full points.
- [✅] In `readme.md`, check off the features you have completed in this unit by adding a ✅ emoji in front of the feature's name.
  - [✅] Under each feature you have completed, include a GIF showing feature functionality.
- [✅] In this document, complete all five questions in the **Reflection** section below.

## Reflection

### 1. What went well during this unit?

Our team successfully completed the core foundational infrastructure, which typically consumes the most development time. Specifically, we implemented database integration across the entire application, including user registration, profile creation, and post creation. Connecting the frontend with the backend required extensive work on authentication flows, RLS policies, and file storage implementation. This strong foundation unblocks all remaining feature development.

### 2. What were some challenges your group faced in this unit?

The primary challenge was managing the heavy workload inherent in the tasks with limited time. Integrating complex features across multiple tables (profiles, posts, and eventually groups) and implementing signup logic required significant debugging and iterative testing. Additionally, the need to design the initial schema (i.e. activities, profiles, users) added complexity and time, leaving less bandwidth for other tasks.

### Did you finish all of your tasks in your sprint plan for this week? If you did not finish all of the planned tasks, how would you prioritize the remaining tasks on your list?

No, we did not finish all planned tasks. We were unable to complete the Group formation feature (User Stories 5, 6, and 10).

The remaining tasks would be prioritized as follows:
Group Organizer: Create a new hangout group with a title and purpose (User Story 5) — This is the core functionality that enables all other group features.
Group Organizer: Send invitations to other students (User Story 6) — This is important for populating the groups created in the first step.
Peer: Voluntarily leave a hangout group (User Story 10) — This is important for user experience and managing active chats.

### Which features and user stories would you consider “at risk”? How will you change your plan if those items remain “at risk”?

Swipe Functionality (User Stories 3, 4) - This feature requires complex backend algorithms to filter and match users based on courses and interests and manage the swipe state (like/skip) for every user pair. If the full matching algorithm is too complex to finish on time, we will reduce the scope to a basic filter.

Group Formation (User Stories 5, 6) - This relies on creating an entirely new database table structure (groups) and associated logic (invitations, membership tracking). If the core group formation (Story 5) cannot be completed, we will defer the "Messages" feature to only support one on one chats.

### 5. What additional support will you need in upcoming units as you continue to work on your final project?

Given the large scope of the social networking features (especially messaging and group coordination), we need support in prioritizing minimum viable product features to ensure a complete, stable final demo. This includes setting clear time constraints for the "at risk" swipe functionality.
