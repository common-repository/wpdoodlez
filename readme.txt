=== Plugin Name ===
Contributors: robert_kolatzek
Donate link: https://www.paypal.me/RobertKolatzek/
Tags: doodle, poll, question, meeting
Requires at least: 4.4
Tested up to: 4.9.6
Stable tag: 1.0.10
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html


== Description ==

Everyone knows [doodle](https://doodle.com) It's a cute plattform to poll, to find the best meeting date or place, to make a decision with many people.

With this plugin you can create very simple doodles in your wordpress installation.

WPdoodlez are own post type and very similar to a post. A WPdoodle extends a post and uses custom fields to set possible answers.

* A link to WPdoodle ist public but not published everywhere
* A WPdoodle can be in a review and be published at given time
* A WPdoodle can have own URL 
* Poll users must not be valid logged in wordpress users
* Users with "delete published post" rights can delete votes
* Users name will be stored in a cookie for 30 days (user can change only his own vote, but on the same computer)
* Every custom field set in a WPdoodle is a possible answer
* The first value of the custom field will be displayed in the row as users answer
* The last row in the table contains total votes count

== Installation ==

After install this plugin you will see "WPDoodle" item in the menu on the left site. 

== Screenshots ==

1.  View in the **frontend**
2.  View in the **backend**

== Changelog ==

= 1.0.1 =
Fix for plugin activation. Sorry for the mess!

= 1.0.2 =
Fix registering rewrite rule in activation

= 1.0.3 = 
Translate word "Doodle" as "WPdoodle" because of trade mark collision

= 1.0.4 =
Bugfix: Load and execute javascript after loading jQuery -> external file

New: Load css from a file 

New: Overwrite plugins css with own css definistions in user.css (loading only if exists)

= 1.0.5 =
Bugfix: Loading js file

New: highlight your vote by using css class "myvote"

= 1.0.6 =
Error message by second voting try. (After deleting a vote cookies are still
in the browser of the person, which vote was deleted. She/he can not vote any more
and doesn't know why. The message in a javascrip alert fix this bad behaviour.)

= 1.0.7 =
= 1.0.8 =
Update latest installable version to 4.7 without changing anything but documentation

= 1.0.9 =
= 1.0.10 =
Update latest tag to 4.9.6
