# Client

TODO

```
KeyBindings AutomapBindings;
KeyBindings Bindings;

readonly Font BigFont;
readonly int  CleanHeight;
readonly int  CleanHeight_1;
readonly int  CleanWidth;
readonly int  CleanWidth_1;
readonly int  CleanXFac;
readonly int  CleanXFac_1;
readonly int  CleanYFac;
readonly int  CleanYFac_1;
readonly Font ConFont;
readonly Font IntermissionFont;
readonly Font SmallFont;
readonly Font SmallFont2;
readonly Font NewConsoleFont;
readonly Font NewSmallFont;

ui float         BackbuttonAlpha;
ui int           BackbuttonTime;
ui int           MenuActive;
ui BaseStatusBar StatusBar;

readonly ui bool NetGame;

int LocalViewPitch;
```

### `AutomapBindings`

TODO

### `Bindings`

TODO

### `BigFont`

The `bigfont` for the current game.

### `CleanHeight`

The current screen height divided by `CleanYFac`. **Not deterministic.**

### `CleanHeight_1`

The current screen height divided by `CleanYFac_1`. **Not deterministic.**

### `CleanWidth`

The current screen width divided by `CleanXFac`. **Not deterministic.**

### `CleanWidth_1`

The current screen width divided by `CleanYFac_1`. **Not deterministic.**

### `CleanXFac`

Integral scaling factor for horizontal positions to scale from 320x200 to the
current virtual resolution. **Not deterministic.**

### `CleanXFac_1`

Integral scaling factor for horizontal positions to scale from 320x200 to the
current virtual resolution, accounting for aspect ratio differences. **Not
deterministic.**

### `CleanYFac`

Integral scaling factor for vertical positions to scale from 320x200 to the
current virtual resolution. **Not deterministic.**

### `CleanYFac_1`

Integral scaling factor for vertical positions to scale from 320x200 to the
current virtual resolution, accounting for aspect ratio differences. **Not
deterministic.**

### `ConFont`

The console font.

### `IntermissionFont`

The font used in intermission screens.

### `SmallFont`

The `smallfnt` for the current game.

### `SmallFont2`

The alternate `smallfnt`.

### `NewConsoleFont`

TODO

### `NewSmallFont`

TODO

### `BackbuttonAlpha`

Alpha of the back button in menus.

### `BackbuttonTime`

The time until the back button starts fading out in menus.

### `MenuActive`

The current active menu state. One of:

| Name             | Description                                                    |
| ----             | -----------                                                    |
| `Menu.Off`       | No active menu.                                                |
| `Menu.OnNoPause` | Menu is opened, but the game is not paused.                    |
| `Menu.On`        | Menu is open, game is paused.                                  |
| `Menu.WaitKey`   | Menu is opened, waiting for a key for a controls menu binding. |

### `StatusBar`

TODO

### `NetGame`

Whether this is a networked game or not.

### `LocalViewPitch`

The pitch angle (in degrees) of `ConsolePlayer`'s view. **Not deterministic.**

<!-- EOF -->
