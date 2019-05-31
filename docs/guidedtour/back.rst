<!DOCTYPE html>
<html>
  <head>
    <title>Window Maker: Guided Tour - Backgrounds and Themes</title>
    <meta charset="utf-8">
    <link rel="stylesheet" href="/style.css" media="screen">
    <meta name="HandheldFriendly" content="True">
    <meta name="MobileOptimized" content="320">
    <meta name="viewport"
      content="width=device-width, minimumscale=1.0, maximum-scale=1.0">
  </head>
  <body>
    <div id="wrapper">
      <header>
        <h1>
          <a href="/">
            <span class="first">Window</span><span class="second">Maker</span>
          </a>
        </h1>
      </header>
      <aside>
        <nav class="menu">
          <ul>
            <li id="dock">
            <a href="#"></a>
            </li>
            <li id="home" title="Home">
              <a href="/">Home</a>
            </li>
            <li id="news" title="News">
              <a href="/news">News</a>
            </li>
            <li id="docs" title="Documentation">
              <a href="/docs">Documentation</a>
            </li>
            <li id="mail" title="Mailing lists">
              <a href="/lists">Mailing</a>
            </li>
            <li id="devel" title="Development">
              <a href="/dev">Development</a>
            </li>
            <li id="screenshots" title="Screenshots">
              <a href="/screenshots">Screenshots</a>
            </li>
            <li id="themes" title="Themes">
              <a href="/themes">Themes</a>
            </li>
            <li id="links" title="Links">
              <a href="/links">Links</a>
            </li>
          </ul>
        </nav>
      </aside>
      <article>
        .. TODO: check for the dead links

Backgrounds and Themes
======================

.. contents::
   :backlinks: none

For the purposes of this guided tour, only those appearance options that are
built-in to Window Maker will be considered. Crafting custom styles and themes
is not terribly difficult, nor do you need any special knowledge of programming
languages or other specialized skills, but this is outside the intended scope
of the guided tour.

The appearance of the Window Maker GUI can easily be customized from the
applications menu item "Appearance".

Themes, styles, icon sets, and backgrounds can be selected as soon as they are
installed in the right directory.

Themes should be installed in the directory
``~/GNUstep/Library/WindowMaker/Themes/``

Styles should be installed in the directory
``~/GNUstep/Library/WindowMaker/Styles/``

Backgrounds should be installed in the directory
``~/GNUstep/Library/WindowMaker/Backgrounds/``

If you are working within a freshly-installed instance of Window Maker, your
Linux distribution probably provided some default themes, styles and
backgrounds. Rarely, a distribution provides no additional themes, styles or
backgrounds - expecting users to provide these on their own.

Here is the "Appearance" menu and some of its associated sub-menus,
including themes, styles and backgrounds:

.. figure:: images/appearancemenu.png
   :alt: Appearance menu items
   :figclass: borderless

In the screenshot above, most of the styles are default to the Debian GNU/Linux
distribution, while most of the themes were user-installed. Many themes are
available for download on the internet.

Backgrounds
-----------

Backgrounds may be system-generated solid or gradient colors, or they may be
images from user or distribution-supplied image files. The easiest way to
change a system-generated background color or color gradient is to select one
from the "Appearance -> Background -> <Solid | Gradient>" menu. In most default
configurations there will be six to eight selections in each category.

Likewise, the easiest way to change to a background image is to select one from
the "Appearance -&gt; Background -&gt; Images" menu. If you wish to install
your own images for use as backgrounds, place the image file in your
``~/GNUstep/Library/WindowMaker/Backgrounds/`` directory and they will be
available from the menu immediately.

Styles
------

A style defines the look of the key components of the Window Maker desktop.
These components include the window titlebar and resizebar, the menu title and
text field, and the icon background.

The characteristics defined in a style (or theme) are the color and "texture"
of key GUI elements. Texture in this context means using multiple colors in
various color gradients - you are not limited to solid colors only.

The easiest method for changing the style is to select a style from the
"Appearance -> Style" menu.

A style may also be created using the *Appearance Preferences* tool in
*WPrefs.app*.  From this tool, you may configure the color and texture of
window elements (titlebars, resizebars), menu elements (menu titlebar, menu
item text colors, menu "style") and the color and texture of icon backgrounds.
The location of titlebar text and the font and text color for window and menu
text may also be configured here.


.. figure:: images/prefs13.png
   :figclass: borderless
   :alt: Appearance preferences tool

   Appearance preferences tool

More information on creating a style "from scratch" may be found `in the Window
Maker User's Guide </docs/chap4.html>`_. (Scroll down to the
section on "Appearance Options.")

A step-by-step guide to crafting a custom style is available `HERE
<http://windowmakerandi.blogspot.com/search?updated-min=2011-01-01T00:00:00-06:00&amp;updated-max=2012-01-01T00:00:00-06:00&amp;max-results=4
target="_blank">`__.

Themes
------

In its most basic form, a theme is simply a style that also includes a
background. Some Linux distributions provide one or more default themes for use
system-wide. You may install your own themes in the
``~/GNUstep/Library/WindowMaker/Themes/`` directory. Themes installed in the
correct directory will be available for selection in the "Appearance -&gt;
Themes" menu.  Selecting Themes from the Appearance menu runs the *setstyle*
program to install the theme and record it in the
``~/GNUstep/Defaults/WindowMaker`` file.

Two sites providing preconfigured themes are `HERE
<http://lonelymachines.org/windowmaker-themes/>`__ and `HERE
<http://www.jessanderson.org/wmthemes/>`__.  An internet search for "Window
Maker themes" will generate additional results, and you should also check your
Linux distribution's repositories - some provide themes for installation using
your distribution's package management system.

Themes may include images in png, jpg, xpm, and other supported image file
formats for key elements of the GUI such as titlebars, icon backgrounds, and
the workspace background. Themes that include images cannot be stored as a
single text file, and therefore must be stored in a directory. A theme
directory must contain all of the image files needed for the theme along with a
file named "style." The style file in a theme directory will specify all of the
GUI elements including any image files used for those elements in lieu of rgb
color specifications. A theme directory must use the suffix ".themed" after the
theme name.

      </article>
      <div id="titlebar">
        <div id="minimize"></div>
        <div id="titlebar-inner">Window Maker: Guided Tour - Backgrounds and Themes</div>
        <div id="close"></div>
      </div>
      <div id="resizebar">
        <div id="resizel"></div>
        <div id="resizebar-inner">
        </div>
        <div id="resizer"></div>
      </div>
    </div>
  </body>
</html>
