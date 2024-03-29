================
Wordpress plugin
================

Misinformation is a very complex phenomenon.
Media’s credibility has lessened because of questionable practices like stealth editions.
This plug-in would help media outlets to be accountable to their audiences.
We believe that using the plug-in could be seen as a commitment to open the newsrooms to public scrutiny, by using something that could be easily installed by everyone.

Besides, misinformation is an alarming situation in Latin America, where media companies are not used to follow nor enforce rigorous editorial policies.
By using technology to open the process of news publishing, we can also improve it.
News making should be a public discussion, in order to strengthen reliability and credibility.

Since the goal is to create a Wordpress plug-in, the tool would be available for practically 20% of all self-hosted websites in the world.
Also we would like to draft a protocol RFC to publish newsdiffs to subscribed peers.
The plug-in could also be integrated with other tools and potentially implemented other CMS platforms by following the standard.


Design
**************************************************
The plugin is designed to leverage the use of Wordpress revisions.
The plugin adds the capability to expose the revisions of `post_types` when revisions are enabled.

We have enabled four different endpoints:

#. **{{site}}/wp-json/wp/v2/glassbox** - Enables to see the revisions of posts edited in the last 72 hours.
#. **{{site}}/wp-json/wp/v2/posts/{{post_id}}/glassbox** - Enables to see all the stored revisions of a given post.
#. **{{site}}/glassbox** - Enables to see the revisions of posts edited in the last 72 hours in Json format.
#. **{{site}}/PERMALINK/glassbox** - Enables REDIRECT TO see all the stored revisions of a given post into the wp-json API.


Compatibility
**************************************************
Wordpress 4.7 > and up.


Installation
**************************************************
1. Download the (plugin zip)[https://github.com/GlassboxNews/wordpress-plugin/releases/tag/v0.1.0-beta.1].
2. Install the zip as a plugin by uploading the file.
3. Activate the plugin.
4. (Optional) You should enable the use of wordpress Json API if disabled.


Demo
**************************************************

.. raw:: html
   :file: media/wordpress-glassbox-demo.html


Acknowledgements
**************************************************

* @sterndata - Member of the Wordpress community
* @Clorith - Member of the Wordpress community
