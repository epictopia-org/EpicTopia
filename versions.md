# What's New

This page shows the detailed updates of each app version.
Please get in touch with us at [hello@epictopia.com](hello@epictopia.com) if you have any issues, feedback, or thoughts.



# 1.4.2: Enhanced UI Consistency

Version 1.4.2 delivers updates focused on UI enhancements and resolving technical issues for a smoother app experience.

## Enhancements
- Unified UI Style: Standardized pop-up windows for a more consistent and intuitive user interface.
- 3-Party Swift Library Updates: Updated third-party libraries to improve app compatibility and performance.

## Bug Fixes
- Fixed conflicts between NavigationStack and NavigationLink to ensure fluid navigation.
- Addressed issues with setting recurring times, enhancing reliability for scheduled events.



# 1.4.1: Unified Date Settings

Version 1.4.1 introduces thoughtful refinements across the board, aimed at streamlining operations and enriching the user experience.

## New Features
We've consolidated the time setting, repeat, and reminder options into a single window when creating a post, simplifying the process and enhancing user convenience.

## Enhancements
- Revamped Onboarding Experience: We've enhanced the onboarding process to better introduce new users to key features such as the timeline, entry creation, icon functionalities, and tracker usage, ensuring a comprehensive understanding from the start.
- Faster Main Tab Navigation: Improved the switch speed between main tabs, significantly enhancing user interaction.
Bug Fixes

## Bug Fixes
- Fixed a bug that affected the daily recommendation feature.


# 1.4.0: Unified Planning and Timeline

Version 1.4.0 marks a significant evolution in our app's functionality, incorporating major updates that streamline planning and timeline management with advanced AI integration.

## New Features
- We integrated the planning function directly into the timeline, which now accommodates future dates. Phases have been transitioned to milestones. This eliminates the separate planning module, consolidating past phases into milestones for a more cohesive view of your journey.
- AI-generated plans are now fully editable and customizable, allowing you to tailor them to better fit your needs and objectives. 
- New indicators have been added to milestones to reflect their completion status, accompanied by updated icons to enhance visual differentiation.

## Enhancements
- Refined the logic and performance of recurring entries to minimize bugs and improve overall system efficiency.
- In AI-created Epics, AI now assigns dates to all entries and milestones in its suggested timeline.
- Enhanced language detection based on Entry titles instead of Epic names when generating AI guidance or tasks,

## Bug Fixes
- Fixed a critical bug that prevented users from logging out, enhancing system reliability and user control.
- Fixed issues related to missing user IDs upon registration.


# 1.3.9: Streamlined Editing and Enhanced Stability
`May 9, 2024`

Version 1.3.9 delivers focused enhancements and bug fixes to improve the editing experience, making entry and task management smoother and more intuitive.

## Enhancements
- Task Entry Improvements: Updated task entry to insert a new line between tasks when hitting enter, facilitating easier additions.
- Timeline Scrolling Enhancement: Resolved stuttering issues during timeline scrolling caused by lazy loading and repeated refresh calculations.
- Long Text Editing Stability: Enhanced long text editing experience for stable cursor behavior.
- Consistent Loading Indicator: Standardized the spinning circle effect after editing trackers for uniformity.
- Tracker Display Enhancement: Resolved issues with tracker units not fully displaying during edits, ensuring complete visibility and editability.

## Bug Fixes
- Tracker Details Persistence: Fixed bugs preventing the saving of edited tracker details.
- Keyboard Dismissal on Commenting: Improved keyboard management, ensuring it dismisses correctly after commenting on a post.
- Blank Task Handling: Resolved issues with entering blank or empty lines not creating new tasks, and fixed related crashes.

# 1.3.8
`Apr 30, 2024`

Version 1.3.8 addresses a specific yet critical issue for iOS users.

## Bug Fixes
Date & Time Setting Compatibility: We've fixed a bug affecting iOS users where the 12-hour date and time setting prevented access to backend services. This update ensures that both 24-hour and 12-hour settings work flawlessly with our app, enhancing compatibility and user experience.


# 1.3.7
`Apr 20, 2024`

Version 1.3.7 delivers focused improvements aimed at enhancing user interaction and comprehension, alongside critical stability fixes.

## Enhancements
- Increased Clicking Area of Comment Button: To improve user experience, we've enlarged the clicking area for the comment button, making it easier and more intuitive to engage with posts.
- Full Renaming of "Backlog" to "Unscheduled": We've completed the renaming process across the platform to "Unscheduled" to further enhance clarity and user understanding.

## Bug Fixes
- Fixed Crash Bug in Entry Rescheduling: Addressed and resolved a crash that occurred when dragging entries to a different date, ensuring a smoother and more reliable content management experience.

# 1.3.6
Version 1.3.6 introduces user-centric updates and bug fixes to enhance overall app functionality and user comprehension.

## Enhancements
- Renaming "Idea Backlog" to "Unscheduled": To improve clarity and user understanding, we've renamed the "Idea Backlog" section to "Unscheduled," making it easier to organize and prioritize your plans and ideas.
- Updated the configuration file in the program to streamline system operations.

## Bug Fixes
- Addressed and fixed an issue where liking an entry was not functioning correctly, ensuring your interactions are reflected accurately across the platform.
- Resolved a request timeout issue regarding `getS3Info`, enhancing the reliability of accessing S3 resources.


# 1.3.5
In Version 1.3.5, our focus shifts towards internal improvements, fine-tuning our systems to deliver an even smoother and more reliable app experience.

## Enhancements
- Reduced False Alarm Exceptions: We've refined our error detection mechanisms to reduce false alarms in exception error email notifications, ensuring our team can respond more effectively to genuine issues.
- Elastic IP for EC2 Services: By integrating Elastic IP with our EC2 services, we enhance the reliability and scalability of our infrastructure, ensuring seamless access and performance for our users.

# 1.3.4
We're thrilled to roll out Version 1.3.4, bringing a highly requested feature to set entry reminders.

## New Feature
Entry Reminders with Time-Sensitive Notifications: Set reminders on any entry and opt-in for time-sensitive notifications. This ensures you’re alerted at the exact moment you need to be, making it easier than ever to stay on top of your commitments.


# 1.3.2
Welcome to Version 1.3.2, where we introduce exciting new functionality and enhancements to improve your app journey.

## New Feature
Epic Sharing via Web Link: Elevate your storytelling by sharing your public Epics with others through a convenient web page link, broadening the reach of your journey and insights.

## Bug Fixes
- Post UI Alignment Fix: Corrected a UI alignment issue within posts, particularly in the tasks displayed in the explore view, for a cleaner and more cohesive visual experience.
- AI Weekly Summary UI Improvements: We've refined the UI of the AI Weekly Summary, addressing minor issues to enhance your review experience and interaction with insightful analytics.


# 1.3.1
We're proud to present Version 1.3.1, a step forward in refining user interactions and bolstering backend robustness.

## Enhancements
- Clicking on system push notifications now takes you directly to the intended page, enhancing your navigation experience for efficiency and ease.
- Error Monitoring Improvement: Optimized error monitoring by eliminating filtering conditions on frontend error alerts, providing a more comprehensive oversight.

## Bug Fixes
- Fixed a glitch where timelines could be inaccessible due to an empty Epic ID parameter, ensuring smooth and continuous access.
- Addressed a bug hindering new entries post-deletion of an Epic, streamlining content creation without interruptions.
- Refined error handling within AI epic planning features for premium users, boosting overall stability and reliability.

# 1.3.0
In this update, we've focused exclusively on refining user experience.

## Enhancements
We focused on enhancing the reliability and performance of our app through critical bug fixes affecting epic notifications and Entry detailed view.

# 1.2.9

We're excited to roll out Version 1.2.9, which brings a host of improvements and enhances the VIP experience for our users.

## New Features
VIP for Weekly Summaries: Unlock advanced insights with our new VIP features in the weekly summaries. Get deeper analysis, personalized feedback, and more to supercharge your growth journey.

## Enhancements
- Push Notifications: Ensure you're always up to date with our latest features, insights, and updates with new message push notifications.
- Updated SwiftUI Components: Experience a more seamless and responsive UI as we transition from NavigationView to NavigationStack in our latest SwiftUI update.
- Ongoing Bug Fixes: Our commitment to providing a smooth and reliable user experience continues with further bug fixes in this version.

# 1.2.8
In our latest update, we are excited to unveil a new transformative AI feature designed to enrich your growth journey.

## New Features
AI Weekly Summaries: Elevate your personal growth with AI-curated weekly insights, including Weekly Keywords, Data & Charts, Weekly Highlights, Life's Moments, AI Tailored Feedback, and Self-Reflection.

## Enhancements
We've reduced loading times and resolved profile-related bugs for a smoother, more responsive app interaction.


# 1.2.7
In this update, we've focused exclusively on refining user experience:
- Upgraded email services
- Significantly improved the app's stability and performance with bug fixes

# 1.2.4
In this update, we've focused exclusively on refining user experience:
- Enhanced the user experience of creating entries
- Significantly improved the app's stability and performance with bug fixes

# 1.2.3
In this update, we've focused exclusively on refining user experience:

## Enhancements
In this update, we've focused exclusively on refining user experience:
- Enhanced the user experience of recurring entries
- Significantly improved the app's stability and performance with bug fixes

# 1.2.2
In this update, we've focused exclusively on refining user experience:

## Enhancements
- Significantly improved the app's stability and performance with bug fixes.
- Enhanced logging capabilities for better backend performance and diagnostics.
- Addressed a major issue that prevented server access, ensuring consistent and reliable connectivity.

# 1.2.0
In this update, we've focused exclusively on refining user experience:

## Enhancements
- Significantly improved the app's stability and performance with crucial bug fixes.

# 1.1.8
In our latest update, we've taken a monumental step forward:

## Enhancements
- Significantly improved AI understanding of users' pursuits to craft more personalized and effective paths for your life goals or life journeys.
- Enhanced stability and performance with crucial bug fixes.

# 1.1.7
We're excited to announce Version 1.1.7, a significant leap forward in our app's evolution with groundbreaking features and enhancements.
## New Features 
- AI-Powered Personalized Planning: Unleash the power of AI to craft a personalized path for your life goals and provide detailed guidance.
- Integrated Task Management: Stay organized with our new calendar and to-do task features, all seamlessly integrated into your daily workflow.
## Enhancements
- Improved Onboarding Process: Experience a smoother, clearer introduction to our app, making it easier for new users to get started.
- Streamlined User Interface: Enjoy a simplified and refined UI, focusing on core functionalities for an enhanced user experience.

# 1.1.3
## New Features 
- 2 main sections - Today's Section, Profile Section
- Recurring tasks
- AI features to generate a personalized path and advice
## Enhancements
- Improved onboarding process


# 0.51.0
## New Features 
- Revamped the onboarding process for a smoother and more intuitive experience for newly registered users
- Guide users to fill in the invitation code earlier in the process before entering personal information
- Simplified the process of entering birthday
- Pre-provide some example Epics during the onboarding process
- Provide a user guide epic for users to get started
- Introduced a helpful banner that prompts users to create Epics when content is sparse
## Enhancements
- Revamped the homepage for clarity and ease of use
- Removed the Activities Board to streamline content
- Introduced a convenient "+" button under each Epic for quick additions
- Added an entry point to access the full Timeline with ease
- Simplified our headers for a cleaner, more intuitive interface
## Bug Fixes
- Resolved an issue that occurred while re-editing photos in memos

# 0.50.1
## New Features 
- Increased the max number of photo attachments in one memo from 3 to 9
- Daily post recommendation
- Timeline for all epics
## Enhancements
- Enhanced the memo editing view and task editing view
- Simplified the process to create a new epic
- Replaced the transition animation when entering timeline
## Bug Fixes
- Fixed the timeout bug when entering the app

# 0.48.0
## Enhancements
- Improved the process of handling internal emails
- Enhanced photo slicing when uploading an epic cover or profile photo
- Improved memo UI and tracker UI for a more user-friendly and intuitive experience
- Enhanced the experience of tasks
- Improved the smoothness of entering the timeline from an epic in the home page

# 0.47.0
## New features
- Support photo editing when creating a memo
## Enhancements
- Enhanced the photo uploading procedure for memo, profile, and epic cover
- Enhanced scrolling experience in the explore section and timeline section
- Enhanced the onboarding animation
- Improved data loading speed when re-entering the app
## Bug Fixes
- Fixed issues of the explore section (wrongly positioned photo and content not showing up)
- Fixed issues of the guest mode
- Fixed bugs that caused incomplete epic loading

# 0.46.5
## Enhancements
- Updated screenshots on the Apple Store
## Bug Fixes
- Fixed bugs that caused the explore page to be empty for new users and the banner animation to be abnormal after registration

# 0.46.2
## Bug Fixes
- Fixed UI issues when replying to the author
- Fixed crash issues when subscribing to others' epics in the post detail view

# 0.46.1
## Bug Fixes
- Fixed UI issues in the summary section
- Fixed issues when editing trackers

# 0.46.0
## New features
- Discover epics recommendations in the explore section
- Gain better understanding of trackers with new explanations
## Enhancements
- Improved the epic summary section for a better user experience
- Enhanced the process of adding and editing trackers
## Bug Fixes
- Fixed UI issues related to memo editing (font style, bold, photo)

# 0.45.0
## New features
- Add covers for epics
- New memo editing structure (collapse irrelevant buttons when editing content)
## Enhancements & Bug Fixes
- Enhanced richtext editing UX (bold, bullet points, ordered list)
- Restructured onboarding process (removed beginners' tasks and guide users to timeline first)
- Fixed the logic of Day # in timeline
- Fixed the UI issues of user profile (following & follower)


# 0.44.0
## New features
- Enable type selection (memo, task, milestone, epic) when tapping the bottom "+" button
## Bug Fixes
- Fixed the issues of uploading duplicate photos and editing entries
- Fixed default profile image for new users
- Fixed the logic of Day # in timeline

# 0.43.0
## Bug Fixes
- Fixed google login issues
- Fixed memo editing error (photo)
- Wrong categories in Explore section

# 0.42.0
## New features
- Mood on tasks or memos 

# 0.41.1
## Bug Fixes
- Wrong categories when creating epics

# 0.41.0
## New features
- To-do tasks
- Categories in the Explore section
- User display name
- Markdown editor for memos supporting bullet points, list, bold, and link
## Enhancements & Bug Fixes
- Enhanced UI for timeline, onboarding process, font style, epic summary, tracker, and badges
- Added sound when completing a to-do task
- Enhanced beginners' tasks
- Fixed most exception errors and timeout errors


# 0.40.0
## New features
- Edit past memos and milestones
- Notify users when their followers and subscriptions have updates
- Long press posts to copy the content
## Enhancements & Bug Fixes
- Trackers not showing up when creating a new memo
- Enhanced visualizations of trackers in epic summary 
  - Adjusted UI
  - Corrected height calculation for bar charts
  - The tracker preview does not reflect the actual graph in the detailed view
- Crash issues for signup and login
- Fixed issues of the guest mode
  - Error message for onboarding process of guest mode
  - Profile image uploading issue
  - Crash issues
- Error message when entering the post detailed view

# 0.39.0
## New features
- Visualizations for trackers 
  - Line charts for Number trackers
  - Bar charts for Category and Duration trackers
- Reminders for upgrading the app
## Enhancements
- Enhanced image uploading process
  - If an image is not uploaded successfully, automatically try another time
  - Before successfully uploading an image, use the local image as a temporary placeholder
  - Display a "failure" icon if an image is not uploaded successfully
- Improved the drag-to-refresh experience on the home page
- Enhanced image preview
## Bug Fixes
- Fixed the image reloading issue when returning to the home page
- Fixed the image uploading error

# v0.38.0
`Sep 1, 2022`

## Enhancements
- Select more than one picture at a time when uploading photos from the album
- Direct the users to the detailed views of the post when clicking the system notification regarding a post

## Bug Fixes
- Fixed the issue that the notifications for epic reminders make no sound
- Fixed the animation issue of the time picker when setting epic reminders

# v0.37.4
`Aug 29, 2022`

## Bug Fixes
- Fixed the "show more" issue on the posts in the explore section and collection view
- Fixed the bugs of bio placeholder, profile image setting, and signing up procedure

# v0.37.3
`Aug 27, 2022`

## New features
- Add reminders to the epics in the epic setting section
- Notification center
  - One click to clear all notifications
  - One click to mark all notifications as read

## Enhancements
- Redesign the epic setting page 


# v0.36.2
`Aug 12, 2022`

## Bug Fixes 
- Corrected the order of notification list
- Solved the conflict between the tracker information page and keyboard
- Fixed a typo on the tracker information page
- Fixed the "show more" on the post detail page
- Fixed the navigation issue of the invitation banner (invisible background)
- Fixed the navigation issue of the collection view (mistakenly adding an epic when clicking a blank space)

## Enhancements
- Show up the onboarding process when deleting and re-signing up the account

# v0.35.3
`Aug 10, 2022`

## Bug Fixes & Enhancements
- Improved the UI quality of the information page for Activities Board and Trackers
- Enhanced the smoothness and refreshing experience of the collection view by replacing ScrollView with List
- Updated What's New section
- Reduced the loading time for the Notification section by restructuring the Message module in Swift
- Enhanced the loading logic of tracker info on the post by restructuring the PostTracker module to directly contain the tracker meta data

# v0.35.2
`Aug 5, 2022`

## Bug Fixes & Enhancements
- Negative like numbers
- The top status bar does not show up on the premium member page (golden card)
- Trackers issue
  - The app crashes when creating multiple trackers quickly at the same time
  - The trackers got duplicated when selecting and un-selecting trackers quickly when creating the post

# v0.35.1
`Aug 5, 2022`
## Bug Fixes & Enhancements
- Updated the invitation link to download the app
- Fixed the login issue through Gmail
- Fixed the crash issue caused by loading the epics

# v0.34.6
`Aug 4, 2022`

## Welcome to EpicTopia!

We help users record and share their long-term journeys or goals, which we call "epics".
EpicTopia helps you keep a record of your precious memories, connect with people who shared similar experiences, and find solutions that matter to you.


## Create your epics

What is epic? Epic is your long-term journeys, stories, or goals.
You can create your epics with specific categories, start dates, and end dates.
You can create multiple epics and manage them on the `Epics` board in the collection section.



## Add content to your epics


A post can contain
- Title (optional text)
- Description (optional text, up to 2500 characters)
- Up to 3 images

You can also add milestones to record your significant progress. In your timeline, the posts and milestones are ordered in time sequence.

## Epic Settings

You can set the following properties for a given epic:

- Epic name
- Epic category
- Start date
- End date

## You can update the epic status:

- In progress (default)
- Accomplished
- Discontinued for other reasons

## Activities Board

You can check how active you are in the past half-year on our activities board.
We display your daily activity level on each grid. The darker the color of the grid, the more active you were on that particular day.
We calculate your streak if you are consecutively active on multiple days.

## Social Section

You can interact with other users:
- Search other users and epics
- Explore other users' posts
- Subscribe to other users' epics and receive updates in the Subscription section
- Follow other users and see the following and follower list in Profile
- Comment on posts
- Like post

## Support

- If anything happens, you can go to `Contact Us` to provide any feedback or ask for help.
- If you have an issue logging into the app, you can click `ask for help` to contact us.
- Whenever you register into the app or reset your password, we will send you emails for notification.
- You can check the app version, our website, the registered email, privacy policy, and terms of use in the app.
