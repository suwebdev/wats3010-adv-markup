WATS 3010: Advanced Markup Project
===================

This is the source repository for the WATS3010 Introduction to Web Development
Advanced Markup project.

The purpose of this assignment is to practice additional markup techniques,
including presentation of tabular data in an accessible format, and the
HTML/CSS interaction required to make page layouts work to elegantly organize
and contain information.

Requirements
------------

In order to complete this assignment, you must fulfill the following requirements:

1. Pay attention to the TODOs in the HTML files. They tell you what enhancements
   you must make.
2. Add proper HREF values so navigational links allow you to click between all
   three pages of the site.
3. Style navigational lists so those links display horizontally on the page in
   the header and footer.
4. Add internal links to the in-text citations (denoted with a numnber in
   brackets like this: ``[1]``) so users can click the links and scroll directly
   to the citation.
5. Use the ``<sup>`` tag around the in-text citations to make them pop up on
   the line (so they look like footnote indicators).
6. In the ``about-poe.html`` file, add an accessible HTML table listing the
   Selected Works provided in the ``poe_selected_works.pdf`` file. (Note: This
   is the same information contained in the ``poe_selected_works.csv`` file,
   which you are also free to use as a resource.)
7. In the ``about-poe.html`` file, add a definition list (``<dl>``) to structure
   the biographical summary in the ``<aside>``.
8. In the ``about-poe.html`` page float the image and caption to the left and
   use visual styling to make it apparent that the image and caption go
   together.

Stretch Goals
-------------

If you feel like all of the above has been too easy, try to complete these
stretch goals:

* Make the social links in the ``<aside>`` element have icons. You can find
  social media icons in many places. Here's a link to get you started:
  http://designyoutrust.com/2013/08/flat-icons-super-minimalist-social-media-icons/
* Add an email share link and use a ``mailto`` link to open an email message
  dialogue for the user. Try using querystring parameters to set the
  subject line. Here's an info link to get you going:
  http://en.wikipedia.org/wiki/Mailto
* Use ``background`` and ``border`` attributes to make a "navbar" look for your
  navigation, and use the ``:hover`` pseudoselector to make the navbar react
  when a user puts their mouse over a menu item.

Tips
----

* Once again, find/replace is a useful tool in your development editor. Use
  the find/replace feature to make sure you don't miss any TODOs.
* As you complete TODOs, remove the comments containing the TODO message so
  you can more effectively use find/replace to keep track of your work.
* As you link to pages and images in the page, or via styles, remember to keep
  in mind absolute vs. relative paths. Absolute paths start with "http" and "/".
  Absolute paths will usually not work on Github Pages.
