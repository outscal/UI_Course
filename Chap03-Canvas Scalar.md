## Canvas Scalar

This component is used for controlling the overall scale and pixel density of UI elements in the Canvas.

- **Scale Mode -** It is used to determine how UI elements in the Canvas are scaled.
    - **Constant Pixel Size -** Makes UI elements retain the same size in pixels regardless of screen size.
    - **Scale With Screen Size -** Scales the UI elements according to the screen size.
    - **Constant Physical Size -**  Makes UI elements retain the same physical size regardless of screen size and resolution.
- **Reference Resolution -** The reference resolution, for which the UI layout is designed for. If the screen resolution is larger, the UI will be scaled up, and if it's smaller, the UI will be scaled down.
- **Match -** Determines if the scaling is using the width or height as a reference, or a mix in between.
- **Reference Pixels Per Unit -** If a sprite has this 'Pixels Per Unit' setting, then one pixel in the sprite will cover one unit in the UI.

![scalar.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a980eac4-4f6b-4346-ac6a-65e7512528dd/scalar.png)
