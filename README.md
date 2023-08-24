# obsGameInputOverlays

Free overlays for the Input-Overlay OBS plugin.

## What

[Input-Overlay](https://obsproject.com/forum/resources/input-overlay.552/ "Official plugin page") is a free [OBS](https://obsproject.com/ "Official OBS website") plugin to show controller input while gaming and stuff.

To be clear, I'm not the author of the plugin.

## How

The files (for each game) you need are the layout image (`layers_table.png`) and the layout config file (`overlay.json`).

Store these two files somewhere OBS can see them, and then in OBS, add an "InputOverlay" and add these two files to it, done.

Keep in mind that it will continuously record key presses, so only show it during gameplay (so you don't accidentally leak passwords and such).

### Change keybindings

To change keybindings, follow the steps below. Alternatively, you could manually edit the [keycodes](https://github.com/univrsal/input-overlay/wiki#where-are-the-keycodes "Official plugin FAQ - Where are the keycodes?") in the `overlay.json` file.

<details closed><summary>Click to toggle tutorial</summary>

1. Put both files (`layers_table.png` and `overlay.json`) in the [online editor](https://univrsal.github.io/input-overlay/cct/ "Official online config file editor").
2. To move on the canvas, use _right mouse click_ and to stop moving _middle mouse click_.
3. Click on an image and select __"Edit selected element"__ on the right.
4. Then on the left, make sure __"Record keycode"__ is checked, then click on the input field next to __"Keycode"__ and press the key you want for it. To apply, hit OK.
5. When you're all done, select __"Export to JSON"__, and now that's your new config file (replaces `overlay.json`) with your custom keybindings.

</details>

## Games

- [BattleBlock Theater®](./battleblocktheater/README.md#what "Open README for BattleBlock Theater® overlay")
- [Distance](./distance/README.md#what "Open README for Distance overlay")

## Credits

If you use these overlays, I would appreciate it if you credit me / this page as I did draw the images and did the layout myself (with the online editor), but it's __not necessary__.

Also, see [the GitHub page for the Input-Overlay plugin](https://github.com/univrsal/input-overlay "GitHub repository of the Input-Overlay plugin").

Again, I'm not the author of the plugin, just of the files found here.
