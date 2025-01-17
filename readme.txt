=== Manual Completions for LearnDash ===
Contributors: liveaspankaj
Donate link:
Tags: learndash, grassblade, manual, completion, mark complete, bulk
Requires at least: 4.0
Tested up to: 6.5.3
Stable tag: trunk
Requires PHP: 5.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Manual Completions for LearnDash lets you check completion as well as manually mark courses, lessons, topics and quizzes as complete. Individuals as well as in bulk.

== Description ==

Manual Completions for LearnDash provides a very simple interface to check completion as well as manually mark courses, lessons, topics and quizzes as complete.

You can use it for single completions as well as for **bulk completions** of hundreds of users. In one click, get all the enrolled users in the course.

You can also upload a CSV files with user_id, course_id, lesson_id, topic_id, quiz_id. To quickly list all the completions, and then process them in bulk in any order you want.

You can also bypass completions blocked by GrassBlade xAPI Companion for xAPI Contents.

**Tracking:**
- If you have an LRS, you can see tracking data, including the user id and name of the admin who marked the lesson complete.

**Requirements to use this plugin:**
To use this plugin you need these two plugins:
1. [LearnDash LMS](https://www.nextsoftwaresolutions.com/r/learndash/wp_mcl_plugin_page)
2. [GrassBlade xAPI Companion](https://www.nextsoftwaresolutions.com/grassblade-lrs-experience-api/)

**Other Manual Completion Plugins:**
[Manual Completions for LifterLMS](https://www.nextsoftwaresolutions.com/manual-completions-for-lifterlms/)
[Manual Completions for TutorLMS](https://www.nextsoftwaresolutions.com/manual-completions-for-tutorlms/)
[Manual Completions for LearnPress](https://www.nextsoftwaresolutions.com/manual-completions-for-learnpress/)

**Related Plugins for LearnDash LMS:**
[Manage Enrollments for LearnDash LMS](https://www.nextsoftwaresolutions.com/manage-enrollment-for-learndash/)
[Autocomplete LearnDash Lessons and Topics](https://www.nextsoftwaresolutions.com/autocomplete-learndash-lessons-and-topics/)
[Visibility Control for LearnDash LMS](https://www.nextsoftwaresolutions.com/learndash-visibility-control/)

== Installation ==

This section describes how to install the plugin and get it working.


1. Upload the plugin files to the `/wp-content/plugins/manual-completions-learndash` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Go to WP ADMIN > GrassBlade > Manual Completions for LearnDash or (WP ADMIN > LearnDash > Manual Completions)


== Frequently Asked Questions ==


== Screenshots ==

1. Manual Completions page
2. Checking Completion status
3. Marking Completions
4. Status Reported in the LRS (if you have an LRS)
5. CSV Upload Format
6. Get all enrolled users

== Changelog ==

= 1.9 =
* Fixed: GrassBlade Icon not displaying on multisite.

= 1.8 =
* Improvement: CSV Upload. Allow uploading user_email or user_login instead of user_id.
* Improvement: Store quiz completion data in LearnDash Activity/ActivityMeta table. Default Quiz Completion data: score = 100, percentage = 100%, points and total points = 1, 1 out of 1 questions.

= 1.7 =
* Improvement: User search is changed for select2 to own code to improve performance for large websites.
* Feature: Added Total count

= 1.6 =
* Fixed: issues related to addons page specially on network website.

= 1.5 =
* Feature: Added ability to pull list of all enrolled users.

= 1.4 =
* Feature: Added ability to mark complete entire Course or entire Lesson.

= 1.3 =
* Fixed: Styling to work with v4.0 of GrassBlade xAPI Companion


= 1.2 =
* Fixed: Completion with CSV upload showing Unknown Error.
* Fixed: Topic and Quiz selection causing issues

= 1.1 =
* Fixed CSS issue on GrassBlade page
* Added Addons page

= 1.0 =
* Initial Commit


