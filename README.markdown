Shutup
======

**shutup.css** is a custom user stylesheet that can be applied to your browser to hide comments on many popular web sites without user intervention.

To install:

1. Download the auto-updating [shutup.css](http://stevenf.com/pages/shutup/shutup.css) file to your system.
	
	*If you don't trust a remotely-imported CSS file, or want to make customizations, you can download the source directly instead.*

2. In your browser's preferences, configure your browser to use shutup.css as a custom user stylesheet. In Safari for Mac OS X, it looks like this:

	![Safari Preferences](http://stevenf.com/pages/shutup/safariprefs.png)

3. Enjoy a less comment-y web.

4. If you make changes, or download a new version of **shutup.css**, quit and restart your browser to make sure it takes effect.

A list of known-to-be-affected sites is contained within the stylesheet itself.

**Warning:** The stylesheet blindly hides blocks with IDs like "comments", which could have unexpected side effects. (I'm told it hides the "discussion" section of Bugzilla installations, for example.) Disable **shutup.css** if you think you might be missing important page content.

Firefox users may wish to try the [Stylish](http://userstyles.org/) plug-in. Charles Stuart provided a Chrome [extension](http://userstyles.org/).

Note on Patches/Pull Requests
-----------------------------
- Fork the project.
- Make your feature addition or bug fix.
- Commit.
- Send us a pull request. Bonus points for topic branches.