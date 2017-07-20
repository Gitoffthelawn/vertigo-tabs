# Vertigo tabs
This WebExtension is a vertical tab list using the new Sidebar API in Firefox.
It has not been tested on other browsers.

# Goals
From Firefox 57 onwards, only WebExtensions will work. Conversion of legacy
add-ons isn't usually desirable, a re-write from scratch gets you closer to
having an extension ready. This is an attempt to have functional vertical tabs,
with these additional goals in mind:
- respect the user's system theme if possible (use system colors,
  system font sizes).
- shortest/cleanest code wins. Legacy Addons based on XUL and non-standard APIs
  aren't usually either short or pleasurable to read, so let's try to not repeat
  the past.
- have sane defaults, and if possible no configuration at all.
  It should just work.

## To Do
- Drag and drop support in-window and between windows. Pull requests welcome :)

## To Not Do (yet)
- Tab tree. Having a tab tree is not currently possible
  (missing [openerTabId support in firefox](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/API/tabs/Tab#Browser_compatibility)), however it might be a desirable feature in the future


# License
Released under the GNU Public License v3
