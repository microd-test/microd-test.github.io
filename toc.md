# Build notes

## 10/10
- asm - Built using asm rather than wasm 
- asm2 - HBX doesn't work!
- Gamma and GammaTest - built using different wasm properties but wasm is unsupported on iOS11+

## 10/11
- Build_001 - standard materials, default setup
- Build_002 - standard materials with swatches, default setup
- Build_003 - standard materials with swatches, custom lighting
- Build_004 - standard materials with swatches, custom lighting, room
    - ~~looks darker on iOS~~
    - bot have AA issues on shadows
- Build_005 - standard materials with swatches, custom lighting, only floor, white clear color
    - ~~color is still dark~~
- Build_006 - graphics quality changed to standard ultra settings
    - MSAA levels have no effect in WebGL 1
- Build_007 - disabled Allow HDR on the camera
    - MSAA is a little bit better
- Build_008a - MicroD shaders adjusted to match linear, skybox, custom lighting
- Build_009 - added room back in
    - Lighting and model look fine

### Notes
- Builds 3 - 5
    - Swatch color stayed the same, contrast between white background and swatch made it look slightly darker
    - AA is still a big issue 

## 10/15
- Build_010 - testing a touch screen camera script
    - Needs a bunch of modifications to rotate around the model 
- Build_011 - different camera script
    - Too fast and no clamp on rotationgit