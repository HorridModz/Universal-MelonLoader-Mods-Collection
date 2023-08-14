## RuntimeGraphicsSettings
A mod to allow tweaking some graphics settings at runtime to get those extra few frames.  
Works best when your game has an in-game UI for mod settings (as another mod, naturally).

Settings description:
 * -1 on integer settings means "don't change the default value"
 * MSAALevel - multi-sampled anti-aliasing level. Valid values are 2, 4 and 8
 * AllowMSAA - toggle MSAA at runtime
 * AnisotropicFiltering - texture anisotropic filtering
 * RealtimeShadows - allow realtime shadows
 * SoftShadows - use soft shadows if shadows are enabled. Soft shadows are more expensive.
 * PixelLights - maximum amount of pixel lights that can affect an object
 * Texture decimation - Reduces texture resolution by 2^(this setting). A value of 0 means full-resolution textures, a value of 1 means half-res, 2 would be quarter res, and so on.
 * GraphicsTier - Unity Graphics Hardware Tier. Valid values are 1, 2 and 3. Only affects shaders loaded after it was changed. 