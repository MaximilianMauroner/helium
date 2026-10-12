# Compact layout and window grab area

Use the exact Compact grab-area candidate from its existing owner, not default
main when that candidate is unmerged. Record the candidate and platform build.

1. In the owned developer profile, select Compact layout and open six synthetic
   local tabs. Pin four already-owned test extensions only if separately allowed.
   Check the enabled grab-area setting and available horizontal space.
2. Drag the real browser window by the displayed grab area. The window moves;
   tabs and extension controls remain reachable and are not mistaken for drag
   targets. Check a narrow and a normal desktop window.
3. Disable the setting, reopen settings and restart the developer browser.
   The choice persists and the layout follows it. Restore the owned preference.
4. Inspect Classic layout after returning from Compact. Existing tab, toolbar
   and caption interactions retain their expected behavior.

Native dragging and hit testing need a platform operator. A screenshot, patch
check or browser-tab DOM inspection does not prove them. Use local pages; no
account login, normal profile, extension installation or upstream submission is
part of routine maintenance. Close the developer process and owned profile.
