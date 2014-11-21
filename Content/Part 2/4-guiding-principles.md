## 4. Guiding Principles

It’s no surprise that the developers that founded WordPress had so much in common. b2 was simple, hackable, usable. It was these aspects of b2 that attracted them to the software. WordPress needed to be simple, hackable, and usable too. When they forked b2, the founders didn’t just inherit code, they also inherited b2’s ideals. These were enriched by the ideas about software and software development that each of the founders brought with them. These founding philosophies informed much of WordPress’ early development, became underpinning philosophies for the project, and today still inform decision making about software development and community building.

From b2, they inherited a focus on usability. On cafelog.com, Michel kept a development log on which he recorded his thoughts about developing b2. It’s often just a list of things that he’s done that day, but some of the things he mentions provide insight into who he saw as b2’s user base. For example, when he [talks about creating a templating system](http://cafelog.com/?p=30&tb=1), he says that he wants to “make templates customizable by Joe Newbie,” a templating system that any user could customize. A user shouldn’t have to be a CSS genius just to customize their site. 

 Another feature of b2 was the install script, written by a b2 contributor, which made installing the software easy. This was in contrast to the most popular blog platform around, Movable Type, which was notoriously difficult to install. A simple install script meant that people without much technical knowledge could install the software. By the time b2 ceased development, it hadn’t reached the point of a seamless install, but the code and the intent provided the groundwork for WordPress’ “famous 5-minute install.”

Even before WordPress was WordPress, in its nascent state as b2, the focus was on making things as easy as possible for all users, and particularly for those who were new to the platform. 

Allied to a this focus on usability, was a commitment to simplicity. Creating simple software means focus on providing users with only exactly what they need to get the job done. Software is a tool and, like any tool, the simpler it is the easier it is to use. By keeping things simple, a user can figure out the software from the interface itself, with as little external instruction as possible. The way to use software should be self-evident from the interface.

When Michel started development of b2 he made the decision to focus solely on blogging functionality. He didn’t want to create a CMS, he wanted to create a blogging platform. This meant that all of his early enhancements were centred on simple tools for getting content on the screen. This focus on blogging ensured that, particularly in the early days of development, the platform remained simple.  


Matt’s early focus was on web standards. He wanted to ensure his own website's forward compatibility, to ensure that it worked in future browsers and devices. A major influence was [Jeffrey Zeldman’s](http://www.digital-web.com/articles/999_of_websites_are_obsolete/) _Forward Compatibility: Designing and Building with Standards_ . Zeldman's book covers how to create standards-compliant websites that work across browsers and devices. Even prior to forking b2, Matt had converted most of his site to XHTML 1.1. 

This meant that many of Matt’s first commits to WordPress were focused on HTML semantics and web standards. After setting up the CVS repository (the version control system the project used at that time), and uploading the files, Matt made basic semantic changes to the `index.php` file, fixed whitespace issues, and converted `<div>` tags into heading tags. Using the correct tags to generate proper headings reinforces the content's semantic meaning on the page. 

In a post just after the launch of WordPress 0.7, Matt outlined his thoughts on the future of WordPress on [WordPress.org](http://WordPress.org). He wrote, (http://web.archive.org/web/20031002112415/http://wordpress.org/about/future/) "one thing that will never change is our commitment to web standards and an unmatched user experience.” 


Simplicity, usability, and web standards - these are principles that guide WordPress development to the present day. Over time and as new people join the project, new axioms become a part of the community, augmenting and strengthening these guiding principles. Taken together, these are guiding principles for a user-first focus. The software was developed with the user in mind. Perhaps this came about because the software’s developers started out as users themselves. Mike and Matt were users of b2 - they started to blog before they started developing blogging software. They started developing blogging software only because they were interested in making improvements to their own blogs. And as they made these improvements they got more drawn in to the development community. But they remained, particularly in the beginning, software users, which meant that while they were developing software they retained an empathy for others. This was also the case for other developers who became involved with the project. Developers didn’t get involved with the project just because they felt like working on blogging software. They got involved with the project because they used blogging software. They had installed the software for their own blog, found that they wanted to change or improve something, and contributed those changes back. 

What ensures the continuation of this user-first approach is a decision that was made prior to even the fork of WordPress, a legacy that the community is either sustained by or stuck with, depending on your perspective. That legacy is the GPL, the software license that Michel distributed b2 with, and that remains WordPress’ license to this day.