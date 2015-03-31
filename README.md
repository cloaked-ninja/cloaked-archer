# cloaked-archer
jQuery Menu insertion for SharePoint 2013, using structural navigation menu and bootstrap V5 masterpage.

Ever put in a situation where you need to add extra submenus to SharePoint top structural navigation but you don't have the experience/access to use Visual Studios to do so? This menu insertion should work for you! 

Dependencies: Bootstrap V5 masterpage (links to jQuery are built into the V5 masterpage).

More information: The first line of code runs the menu, inserts either the menu part with a flyout navigation arrow, or it can
be adjusted to insert only a normal menu link if you want a normal menu option.  SharePoint doesn't have an option to create submenus in structural navigation unless it automatically creates them when a subsite is created.

Example SharePoint structural navigation menu:

(the zzXX_ numbers are dynamic, so a solution needs to ignore these)

<div id="zz12_TopNavigationMenu" class="nav noindex ms-core-listMenu-horizontalBox">zz12_TopNavigationMenu
  <ul id="zz23_RootAspMenu" class="root ms-core-listMenu-root static">              zz23_RootAspMenu
      <li> First Menu Item
      <li> Second Menu Item
      <li> Third Menu Item
        <ul>
          <li> First Submenu Item
          <li> Second Submenu Item
       
       
