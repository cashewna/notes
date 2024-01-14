---
title: "03 - Financial Independence"
pubDate: 2024-01-08
description: "Financial independence is a state where an individual or household has accumulated sufficient financial resources to cover its living expenses without having to depend on active employment or work to earn money in order to maintain its current lifestyle."
author: "Krishna Khong"
image:
    url: "https://docs.astro.build/assets/full-logo-light.png"
    alt: "The full Astro logo."
tags: ["genc3004", "24T0", "financial independence", "unit 3"]
---
# Financial Independence

## Present value of perpetuity
A security that pays a never-ending cash stream.

present_value = cash_flow / (real_return - growth)

```python
if growth > 0:
    perpetuity grows over time
elif growth == 0:
    perpetuity remains the same over time
else:
    perpetuity decreases over time
```

## Present value of annuity
Assume that superannuation/funds are used up over a period of time.

Can also be used to determine borrowing capacity.

present_value = cash_flow * ((1 - (1 + rate)^-period) / rate)