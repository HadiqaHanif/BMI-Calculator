# BMI Calculator

A simple Python program that calculates BMI from user-entered weight (kg) and height (m), then prints the weight category.

## How to Run

```bash
python bmi_calculator.py
```

## Categories

| BMI Range | Category |
|-----------|----------|
| < 18.5 | Underweight |
| 18.5 – 24.9 | Healthy Weight |
| 25.0 – 29.9 | Overweight |
| ≥ 30.0 | Obese |

## Note

The correct BMI formula is `weight / height²`, but this code uses `weight / height`. Update to `weight / (height ** 2)` for accurate results.
