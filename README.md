## Pixel Power

##### Templates JSON for Pixel Power Extension.

Everyone is welcomed to contribute your ideas to the templates.json. Just add the templates you want and pull request, I'll check out and merge if it fits the rules.

> Rules:
>
> Nothing sensitive. Nothing political.
>
> Advertising not allowed. Exception example: height of iPhone 6s.

------

#### **Format:**

##### A type:

```javascript
"name": [
  // Leave 0 position for units
  [
    "unit name": number
    // the number will be used to multiply with pixels
    ...
  ]
  // Templates
  [],
  ...
]
```

Types like time, energy and length. Any template must be put under a right type.

##### A template:

```javascript
[
  // Unit info
  [
    "unit name",
    bool // round the result
  ],
  // Conversion info
  [
    "display name",
    number, // will divide result with this number
    bool // round the result
  ]
]
```