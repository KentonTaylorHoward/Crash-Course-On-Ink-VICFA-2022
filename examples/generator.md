# *Story Generator*

## Playable Example

<iframe
  src="https://kentontaylorhoward.github.io/Crash-Course-On-Ink-VICFA-2022/#/examples/generator/"
  style="width:100%; height:600px;"
></iframe>

## ink Code

```ink
// Variables must be created with default values.
VAR people = ""
VAR location = ""
VAR feature = ""
// Set the random location.
~ location = "{~station|planet}"
// Set the people.
~ people = "{~robots|cyborgs|humans}"
// Set the feature.
~ feature = "{~gleaming tower|busy marketplace|giant flower}"

"Ready for a dynamic story?" you ask.
"Nearly out of fuel, you make an emergency landing.
You are on a {location} and see it filled with {people}.
Looking closely, you see a {feature}."
```
