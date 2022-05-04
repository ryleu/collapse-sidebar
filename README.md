# collapse-sidebar
collapse the left sidebar in discord

## screenshots

### collapsed
![Screenshot from 2022-05-03 21-08-42](https://user-images.githubusercontent.com/69326171/166610823-741b2253-7511-4e72-b95d-093e0d7e4838.png)

### expanded
![Screenshot from 2022-05-03 21-10-02](https://user-images.githubusercontent.com/69326171/166610831-c33ba0c0-3ff5-4f0d-883c-579f2adc9c6d.png)

that's pretty much it.

## super small mode

if you want to go super small, you can edit `~/.config/discord/settings.json` (`~/.config/discordcanary/settings.json` for powercord / other canary users)

add this to it:

```json
"MIN_WIDTH": 0,
"MIN_HEIGHT": 0,
```

mine looked like this before:

```json
{
  "BACKGROUND_COLOR": "#202225",
  "IS_MAXIMIZED": false,
  "IS_MINIMIZED": false,
  "WINDOW_BOUNDS": {
    "x": 4,
    "y": 48,
    "width": 1178,
    "height": 1028
  },
  "MINIMIZE_TO_TRAY": false
}
```

now it looks like this:

```json
{
  "BACKGROUND_COLOR": "#202225",
  "IS_MAXIMIZED": false,
  "IS_MINIMIZED": false,
  "MIN_WIDTH": 0,
  "MIN_HEIGHT": 0,
  "WINDOW_BOUNDS": {
    "x": 4,
    "y": 48,
    "width": 1178,
    "height": 1028
  },
  "MINIMIZE_TO_TRAY": false
}
```
