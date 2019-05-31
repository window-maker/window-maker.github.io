<!DOCTYPE html>
<html>
  <head>
    <title>Window Maker: Guided Tour - Clip</title>
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
        CLIP
====

By default, The clip is represented by the icon on the top left of the screen
containing a paperclip image.

.. figure:: images/clip.png
   :alt: Clip icon
   :figclass: borderless

The clip's primary function is to serve as a workspace-specific dock. In other
words, applications may be attached to the clip just as they are to the dock,
but the clip and its associated applications are specific to each individual
workspace - not available on all workspaces as they are on the dock.

The clip's secondary function is to act as a "pager" - a utility for changing
from one workspace to another (paging). The arrows at the top right and bottom
left corners of the clip icon allow you to switch from one workspace to the
next workspace (top right) or previous workspace (bottom left).

The current workspace name (if any) and number are displayed on the
clip.

The clip also has a number of menu-driven features.

Clip Menu
---------

Right-clicking the clip displays a menu.

.. figure:: images/menu_clip.png
   :alt: Clip menu
   :figclass: borderless

   Clip menu

Clip Options
------------

The first menu item allows you to select clip options. The following options
are available:

- *Keep on top* - do not allow windows to cover the clip.
- *Collapsed* - icons attached to the clip are hidden until you left-click the
  clip, which unhides them.
- *Autocollapse* - same as the previous option, except that mouseing over the
  clip unhides application icons.
- *Autoraise* - clicking an icon representing a window hidden under a larger
  window brings that window to the front.
- *Autoattract icons* - selecting this option attracts the icon of any
  application launched on the current workspace. Closing the application
  removes the icon from the clip.

Rename Workspace
----------------

This item gives you to ability to name (or rename) the current workspace.

Some users tend to group certain applications by workspace and like to name the
workspace to indicate the nature of the applications on the clip. For example,
a user might have a browser, an IRC client, and a file transfer application
clipped on a workspace, and might name that workspace "internet" to indicate
the workspace's primary function. The user might have a seperate workspace with
a vector graphics application, an image manipulation application, and an image
viewer on the clip, and might name that workspace "graphics."

Other Options
-------------

Right-clicking a clipped application's icon gives options specific to that
application.

- You may make the application's icon *omnipresent* (clipped on all
  workspaces).

- You may *select* one or all clipped icons.

- You may *move* one or all icons to a different workspace.

- You may *remove* the icon.

- You may instruct Window Maker to have all icons *attracted* to the clip as
  soon as each application is launched, rather than placing them initially in
  the defined location on the display.

The remaining clip menu items are similar to those of the `Dock application
icon menu <dock.html#conf>`_. As with the dock, clipped applications may be
launched, hidden, or killed and their settings (icon used, application launch
path/arguments, middle-click launch) may be modified.

From version 0.80.0 on, the clip can "steal" appicons. This feature has nothing
to do with autoattracting icons. When you start an application from somewhere
other than either the clip or the dock (i.e., from the menu or a terminal), and
the application is already either docked or clipped, a new application icon
does not appear at the bottom of your screen. The icon that is already docked
or clipped "steals" the icon function. As a result, the icon for the
newly-launched application is the icon already on the clip or the dock.

      </article>
      <div id="titlebar">
        <div id="minimize"></div>
        <div id="titlebar-inner">Window Maker: Guided Tour - Clip</div>
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
