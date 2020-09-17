# olcPGEX_AdditionalColours

This lightweight extension to the [olcPixelGameEngine](https://github.com/OneLoneCoder/olcPixelGameEngine) by [Javidx9](https://github.com/OneLoneCoder) provides additional pre-defined colours.

This is intended to be a community-driven project, so please feel free to create pull requests to define more colours. See [CONTIBUTING.md](https://github.com/matt-hayward/olcPGEX_AdditionalColours/blob/develop/CONTRIBUTING.md) for more information.

## Usage

The header file should be included after the the Pixel Game Engine header. Once you have included the header file, you can access the colours and functions via the `olc::Colours` namespace.

For example:

```cpp
// Use one of the color constants
Clear(olc::Colours::ORANGE);

// Create a color using the hsv color space, this one makes a nice orange color
auto hsvColor = olc::Colours::FromHsv(40, 1, 1);
```
