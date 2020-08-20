# dwm
dynamic window manager (by suckless) [customized]
Original: https://dwm.suckless.org/

## Patches/Customizations in use

## Keyboard Customizations
Meta Key (⊞) is reset to the CTRL key

Function | Keybinding
------------ | -------------
focusonce(?) | [⊞]+[Alt]+[Return]
swawn(?) | [⊞]+[Alt]+[Return]
Next Tab | [⊞]+[Tab]
Previous Tab | [⊞]+[Alt]+[Tab]
Next Tab | [⊞]+[Alt]+[l]
Previous Tab | [⊞]+[Alt]+[h]
Move Tab Forward | [⊞]+[Alt]+[j]
Move Tab Backward | [⊞]+[Alt]+[k]
Select_Tab(?) | [⊞]+[`]
Select Tab 1 | [⊞]+[1]
Select Tab 2 | [⊞]+[2]
Select Tab 3 | [⊞]+[3]
Select Tab 4 | [⊞]+[4]
Select Tab 5 | [⊞]+[5]
Select Tab 6 | [⊞]+[6]
Select Tab 7 | [⊞]+[7]
Select Tab 8 | [⊞]+[8]
Select Tab 9 | [⊞]+[9]
Select Tab 10 | [⊞]+[10]
Quit Tabbed | [⊞]+[q]
Focus Urgent(?) | [⊞]+[u]
Toggle Urgent(?) | [⊞]+[u]
Fullscreen | [⊞]+[F11]


## Patching process
My patching strategy:
* `suckess` origin is upstream source
* `master` branch is live version

To apply a new patch:
* checkout `suckless/0.6` to new branch
* apply patch to new branch
* compile and test patch in isolation
* commit and push new branch
* merge new branch into master
* resolve any conflicts
* compile and test tabbed with all patches
* commit and push master branch
