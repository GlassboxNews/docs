============
Wordpress plugin
============

Misinformation is a very complex phenomenon.
Media’s credibility has lessened because of questionable practices like stealth editions.
This plug-in would help media outlets to be accountable to their audiences.
We believe that using the plug-in could be seen as a commitment to open the newsrooms to public scrutiny, by using something that could be easily installed by everyone.

Besides, misinformation is an alarming situation in Latin America, where media companies are not used to follow nor enforce rigorous editorial policies.
By using technology to open the process of news publishing, we can also improve it.
News making should be a public discussion, in order to strengthen reliability and credibility.

Since the goal is to create a Wordpress plug-in, the tool would be available for practically 20% of all self-hosted websites in the world.
We want to create a protocol description to publish newsdiffs to suscribed peers.
The plug-in could also be integrated with other tools and potentially be used with other CMS platforms by following the protocol.


Design
**************************************************
The plugin is designed to leverage the use of Wordpress revisions.
The plugin adds the capability to expose the revisions of `post_types` with revisions enabled.

We have enabled two different endpoints:

#. **{{site}}/wp-json/wp/v2/glassbox** - Enables to see the revisions of posts edited in the last 72 hours.
#. **{{site}}/wp-json/wp/v2/posts/{{post_id}}/glassbox** - Enables to see all the stored revisions of a given post.


Compatibility
**************************************************
Wordpress 4.7 > and up.


Installation
**************************************************
1. Download the plugin zip.
2. Install the zip as a plugin by uploading the file.
3. Activate the plugin.
4. (Optional) You should enable the use of wordpress Json API if you have disabled it.


Acknowledgements
**************************************************

* @sterndata - Member of the Wordpress community
* @Clorith - Member of the Wordpress community
