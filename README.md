# Send to Publish Queue plugin for Movable Type

This plugin provides administrators with the ability to republish a blog through the Publish Queue. Send to Publish Queue can be used to republish one or many blogs:

* Visit System Overview > Blogs, select the blogs you'd like republished, and choose "Send to Publish Queue" from the List Actions.
* Visit Design > Templates and choose the Action "Send to Publish Queue."

The plugin will send every template to the Publish Queue to be published later.
Once the publishing job is complete, another cleanup task will go through and email the specified parties.

[Learn more](http://www.movabletype.org/documentation/administrator/publishing/publish-queue.html) about the Publish Queue.

# Prerequisites

* Movable Type 4.x or 5.x
* `run-periodic-tasks` must be set up ([instructions](http://www.movabletype.org/documentation/administrator/setting-up-run-periodic-taskspl.html))

# Installation

To install this plugin follow the instructions found here:

http://tinyurl.com/easy-plugin-install

# License

This plugin is licensed under the same terms as Perl itself.
