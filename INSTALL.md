# Installation instructions

1. Clone this repo
2. Locate the the Firefox profile directory using the `about:support` page
3. Quit Firefox
4. Create a backup of this profile
5. Create a symlink from the root of this repo to `${PROFILE}/chrome`, e.g.

```
ln -s /path/to/FF-ULTIMA /path/to/ff/profile/chrome
```

4. Create a symlink from this repo's `user.js` file to `${PROFILE}/user.js`, e.g.

```
ln -s /path/to/FF-ULTIMA/user.js /path/to/ff/profile/user.js
```

5. Restart Firefox; the theme should be applied
