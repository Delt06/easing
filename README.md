# Easing

An implementation of easing functions.

## Contents

- `Ease` enum: different easing functions
- `EaseExtensions` static class: `GetValue` extension method

## Code example

```
var ease = Ease.OutBack;
var value = ease.GetValue(0.5f, overshoot: 2f);
```

## References

Equations are taken [here](https://easings.net/).