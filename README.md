# obsGameInputOverlays

Ready to use OBS Input Overlays for specific games

## What

[Input Overlay](https://obsproject.com/forum/resources/input-overlay.552/) is a free [OBS](https://obsproject.com/) plugin to show controller input while gaming and stuff.

## How

The files (for each game) you need are the "layers_table.png" image and the "overlay.json" layout file.

Store these two files somewhere OBS can see them, and then in OBS, add an "InputOverlay" and add these two files to it, done.

<details closed>
<summary>Change keybindings</summary>

To modify keybindings, put both files in the [official input overlay online editor](https://univrsal.github.io/input-overlay/cct/)
and click on an image and select "Edit selected element" on the right.

You might need to move the canvas with one right click and stop moving with one left click to see the image.
Because these are HQ images and the zoom is not big enough.

Then on the left, there is an input field labeled "Keycode" where you input your key
(the site should detect any button press and update this field) to apply hit OK.

When you're ready, select "Export to JSON" and now that's your new "overlay.json" file with your custom keybindings.

</details>

## Games

<details open>
<summary>Supported Games</summary>

- [BattleBlock Theater](./battleblocktheater/#What)

</details>

## Credits

If you use these overlays, I would appreciate it if you credit me / this page as I did draw the images and did the layout myself (with the online editor),
but it's not necessary.

Also, see the [GitHub page for the Input-Overlay plugin](https://github.com/univrsal/input-overlay).
