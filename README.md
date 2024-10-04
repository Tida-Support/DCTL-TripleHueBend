# Davinci Resolve DCTL: TripleHueBend

This DCTL operates similarly to a magnetic field for colors, enabling colors to shift rapidly toward up to three selected target hues. This results in a unique "push-pull" effect on color distribution, allowing colors to be attracted to or repelled from these target hues based on user-defined parameters.

![Text](https://github.com/Tida-Support/DCTL-TripleHueBlend/blob/main/TripleHueBend.png)

## Target Hues and Their Significance
At the heart of this DCTL are its intuitive controls, allowing for precise customization of target hues:

- Target Hue 1 (18.5): This hue represents a skintone within the HSL color space, providing a solid foundation for naturalistic color adjustments.
- Target Hue 2 (198.5): Directly opposite in the color wheel, this hue creates a strong contrast.
- Target Hue 3 (98.5): A preset green hue, useful for introducing further tones.

Each of these target hues can be adjusted through sliders, making it easy to define their influence in grading.

## Blend Weight Control
Each hue selection is paired with a Blend Weight slider, which allows colorists to tune the strength of each hue's influence. These sliders range from -1.0 to 1.0, enabling control over how strongly colors are drawn toward or pushed away from the designated target hues.

##Saturation Controls for Each Hue
To further refine the behavior of each target hue, new Saturation controls have been added:
- Sat 1: Controls the saturation impact for Target Hue 1. This slider ranges from 0.0 to 2.0, enabling nuanced control over how saturated or muted the skintone target becomes.
- Sat 2: Allows for saturation adjustments on Target Hue 2, influencing how much the opposite hue stands out or recedes.
- Sat 3: Manages saturation for Target Hue 3, which can add vibrancy or softness to green tones.

## Saturation and Luminance Dynamics
The DCTL also incorporates controls for adjusting saturation and luminance dynamics:

### Saturation control
- Saturation Power: Initially set at 2.0, this slider determines how much saturation influences the blending process, enhancing the push-pull dynamics.
- Saturation Slope: This slider allows for further refinement of the blending curve based on saturation, enabling either smooth or aggressive transitions in color adjustments.

### Luminance control:
- Luminance Power: Influences how brightness impacts blending behavior.
- Luminance Slope: Modifies the blending curve based on luminance, allowing for nuanced brightness adjustments.

### Swirl Feature
Additionally, the DCTL includes a Swirl checkbox that enables a unique "swirl" behavior in hue adjustments. When activated, this feature introduces a circular bending effect around the target hues.

### Skip Hue 3 Feature
The addition of the Skip Hue 3 checkbox allows for quick exclusion of the third hue from the color shift. When enabled, Target Hue 3 is skipped, and no color adjustments are made to that particular hue, simplifying the grading process when the third hue isn't required.

## Exclusion of Neutral Colors
Importantly, the Triple-Hue-Bend DCTL is designed to exclude the influence of neutral colors—namely white, gray, and black. This ensures that the focus remains on vibrant color adjustments without interference from these neutral tones, allowing for more precise control over the color palette.
