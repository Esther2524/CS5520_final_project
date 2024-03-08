# StudySphere: Focus & Friends

## Focus tasks & Standby
### 1. FocusList 
This tab is the **central hub** for the user's focuses. It lists all the pomodoros (focuses) the user has added, providing an overview of their study plan. It is initially empty. When a user selects **a focus task** (represented by a card), it initiates a **focused study period** with a **countdown timer**, reflecting the user's commitment to study for a specified duration without distractions.
  * **(1) AddFocus**: It is implemented as a modal, allowing users to create new focus tasks without navigating away from their current screen FocusList. (Note: Modals are a popular UI pattern used to display content in a temporary window that overlays the main content of the app.)
  * 点击左边 -》 修改focus
  * **(2) Standby**: A personalized screen activated when a user selects a focus task from the FocusList. This screen is more than just a timer; it's a custom space designed to enhance the user's focus and motivation during a study session. The Standby screen includes:
    * **Countdown Timer**: The core feature, tracking the remaining time the user has committed to focus on a specific task.
    * **Start/Stop Functionality**: Allow users to start, pause, or stop the countdown at their discretion.
    * **Visual Feedback**: Provide a visual representation of time remaining, which can help keep users informed and motivated.
    * **Automatic Return**: Once the countdown is over, automatically navigate back to the FocusList screen, possibly with a transition animation that smoothly moves the user from the focused study back to their overall list of tasks.
    * **Customizable Background**: Allows users to personalize their Standby screen with images that inspire or relax them, making each study session unique.
    * **Motivational Quotes**: Dynamically fetched from external APIs, these quotes provide additional motivation and encouragement to the user during a focused study period.
   
## Friends & Study Groups (fostering both community engagement and discovery)
### 2. StudyGroup
This tab can be a social hub where users join study groups, compare progress, and "like" or commend friends' achievements. It fosters a sense of community and mutual motivation among peers. This screen is a social hub, designed to enhance the sense of community among users by enabling them to connect with their existing study groups, track collective progress, and engage in motivational activities. 
  * **My Groups Overview**: A list or grid view of the study groups the user is currently a member of. Each group could be represented by a card or thumbnail, displaying the group's name, a brief description, and possibly a group avatar or image.
  * **Group Activity Feed**: A feed within each group showing recent activities, such as members completing study sessions, posting updates, or sharing resources. This keeps the group members informed and encourages active participation.
  * **Progress Comparison**: Tools or widgets that allow group members to compare their study progress with one another. This could be implemented through charts, leaderboards, or simple progress bars, providing a friendly competitive edge to motivate users.
  * **Achievements and Likes**: A feature that allows users to "like" or commend achievements or contributions made by group members. This could be tied to specific milestones, such as completing a challenging study session or reaching a study goal.
  * **Group Communication**: Integrated messaging or discussion forums where group members can communicate, plan study sessions, share resources, or offer support and advice.
### 3. FindGroup
This screen is designed to help users discover and join new study groups, particularly focusing on groups that are geographically close to them or share similar study interests. Key features include:
  * **Location-Based Discovery**: Utilizing the user's geographical location to suggest study groups nearby. This encourages real-world meetups or finding groups within the same school, university, or community.
  * **Search and Filters**: Providing users with the ability to search for groups by keywords, study topics, or other criteria such as group size, activity level, or meeting frequency. Filters can help users refine their search to find the most relevant groups.
  * **Group Previews**: Offering previews or snippets of information about each group in the search results, such as the group's focus area, number of members, and a short description. This helps users make informed decisions about which groups might be a good fit for them.
  * **Join Requests**: Allowing users to send requests to join groups that interest them. Some groups may be open for anyone to join, while others might require approval from a group admin or moderator.
  * **Recommendations**: An algorithmic or curated list of recommended study groups based on the user's study habits, interests, and existing group memberships. This personalized approach can help users discover new groups that match their study goals and preferences.

## Achievements
### 4. DataAnalysis
It is a personal dashboard for users to reflect on their study habits, achievements, and overall progress. Key features here could include:
  * **Milestone Overview**: Display the milestones users have reached, such as total study hours logged, specific goals completed, or a series of consistent study days.
  * **Badges and Rewards**: Show badges or rewards earned for meeting various study thresholds, challenges, or participation in community events.
  * **Progress Graphs**: Visualize study progress over time through graphs or charts, allowing users to see trends in their study habits, focus durations, and breaks.
  * **Goal Setting and Tracking**: Let users set personal study goals and track their progress towards these goals, providing motivational feedback and suggestions for improvement.
  * **Comparative Analysis**: Optionally, include a feature to compare the user's study habits and achievements with anonymized data from similar users, offering insights and motivation to improve.

### 5. Profile
