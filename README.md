# sidefox

Some simple css to seamlessly integrate [tree style tab](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/) into firefox. 
These tweaks were inspired by [flyingfox](https://github.com/akshat46/FlyingFox) which sadly is no longer active.

- Hides firefox's tab row
- Converts window controls into macos style circles and moves them into the navbar
- Hides tree style tab sidebar header
- Collapses sidebar to only show tab icons and expand on hover
- Makes tree style tab spacing more consistent

![image](https://user-images.githubusercontent.com/34758569/215915268-8b9c7456-e096-4e65-8b9a-226743ad1157.png)

## usage

1. Clone/download the repository
2. Go to about:support in firefox (type it into the urlbar)
3. You should see a field called "Profile Folder", click the "Open Folder" button next to it
4. Create a new folder called `chrome` (if it doesn't exist already) inside the profile folder
5. Put the `circle.svg` and `userChrome.css` files into the `chrome` folder
6. Install [Tree Style Tab](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/) and open the options
7. Scroll down to the "Advanced" section, you should see a box where you can paste text
8. Click the "Load from File" button and load the `treestyletab.css` file from this repository

In order to remove mismatched colors, you can use the [Firefox Color](https://addons.mozilla.org/en-US/firefox/addon/firefox-color/) extension to theme Firefox.

You can start by modifying my theme: https://color.firefox.com/?theme=XQAAAAJnAgAAAAAAAABBqYhm849SCicxcUF-LXcGHf3p79EhVPXPtB1ibTLiQvLY1QylemTgx7ijSrcvWl_HVAmwvnKIJnESUiSA8WGCMfXU1SYZrivWJhOlLowTJB1L-VRPMYNnF_r80lHdEBe3JLDrssxSYl6JV73y6juaH4lGiVPQDt1Lj9TeHVcDa8QSIpBhHgvPYegKJAZUowU_gv4VV-W9WghvliFuPvZr3fkU1eQua_yYFAG5tCSfwVaPIlB3G7_wFktqujh2WHIEwmEJ-z3_g6hVudrcVRYee9sCImYJgfDyXLOMrYnkWRroe9XJxSzRZvxg_7Os6xvdxGy6Z8Nb2Deb-wJvIiem-rxhYYKkDlJjzl5pjnLRZaTFiPn9jmBY
