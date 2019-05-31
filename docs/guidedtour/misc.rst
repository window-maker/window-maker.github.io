<!DOCTYPE html>
<html>
  <head>
    <title>Window Maker: Guided Tour - Miscellaneous</title>
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
        Miscellaneous
=============

.. contents::
   :backlinks: none


Localization
------------

As soon as Window Maker is compiled with some options and gettext installed, it
is fully localizable. Check the INSTALL file.

However, localization of menus can be used without the LANG environment
variable set. Using pl menu allows to get menus in any available language
without setting this variable.

Why do such a "thing" instead of setting the localization the "right" way?

For some reasons users may want to keep the system default language instead of
defining a new localization. One of the main reason is that most software
doesn't exist in all languages.

Fonts
-----

It's possible to change the fonts in Window Maker, editing the WindowMaker file
or the WMGLOBAL file in ``~/GNUstep/Defaults``.

Once again the INSTALL file gives instructions on how to do it.

The specific file to edit varies according to the fonts to be changed.

The script *wsetfont* is provided to do the job.

Utilities
---------

Window Maker provides the user with some useful utilities.

There is a README file concerning these scripts in the util directory.

Almost each script has it's own man page recommended reading.

These utilities mainly concern the GUI: icons, styles, fonts, menus,
backgrounds.

A few of them deserve special interest as many users don't seem to know about
them.

The *wdwrite* script, for instance, writes data into the configuration files.

The *setstyle* (or *getstyle*) scripts are used to manage themes.

*Wxcopy* and *wxpaste* allows copying and pasting using the X cutbuffer.

The first one makes part of the default applications menu, in the selection
item.

For KDE users, wkdemenu.pl is worth using.

From version 0.63.0 on, a new utility is available : *wmagnify*. It allows
magnification of the area under the mouse pointer.

      </article>
      <div id="titlebar">
        <div id="minimize"></div>
        <div id="titlebar-inner">Window Maker: Guided Tour - Miscellaneous</div>
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
