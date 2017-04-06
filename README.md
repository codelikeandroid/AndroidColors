# Android Transparent Colors
Usually when you create the design for an Android app we must add some transparency to different UI elements according to the requirements.

In order to have a transparent background, but not fully transparent, you should compute the hex number assigned to the desired percent of transparency in the alpha channel.

<img align="center" src="https://magdamiu.files.wordpress.com/2017/03/android-transparent-colors-1.png?w=660" alt="magdamiu">

For example to make the red color have 20% in the alpha channel you should use this code #CCFF0000.

In the example, CC is the hex number for 255 * 0.8 = 204. Note that the first two hex digits are for the alpha channel.

The format is #AARRGGBB, where:

- AA is the alpha channel,
- RR is the red channel,
- GG is the green channel and
- BB is the blue channel.

I’m assuming that 20% transparent means 80% opaque. If you meant the other way, instead of CC use 33 which is the hex for 255 * 0.2 = 51.

Hex Opacity Values

- 100% — FF
- 95% — F2
- 90% — E6
- 85% — D9
- 80% — CC
- 75% — BF
- 70% — B3
- 65% — A6
- 60% — 99
- 55% — 8C
- 50% — 80
- 45% — 73
- 40% — 66
- 35% — 59
- 30% — 4D
- 25% — 40
- 20% — 33
- 15% — 26
- 10% — 1A
- 5% — 0D
- 0% — 00

You can take a look at the [Android documentation for colors](https://developer.android.com/guide/topics/resources/more-resources.html#Color).

