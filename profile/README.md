## Physical Reasoning

**An open science of world models.** Physical Reasoning is an open source research collective
studying world models: systems that learn the dynamics of the physical world and predict what
happens next. We work across robotics, self-driving, prediction markets, and the sciences, and we
judge models on real outcomes: forecasts are frozen before the outcome is known and scored against
what actually happens, against simple baselines, and against the market on the same outcome. We
conduct our research in public, and every result is published, including negative ones, together
with the code to reproduce it.

### Projects

| Project | What it is |
| --- | --- |
| [isotherm](https://github.com/physicalreasoning/isotherm) | A calibrated decision model for Kalshi daily temperature ladders, evaluated walk-forward against the market's own price with sealed out-of-sample tests; live as a REST API and MCP server. |
| [forward](https://github.com/physicalreasoning/forward) | Sealed forward tests for world models: every entry is frozen and hashed before a round opens and scored only on outcomes that resolve after the freeze. |
| [causal-jepa](https://github.com/physicalreasoning/causal-jepa) | A negative result on joint-embedding predictive architectures for prediction-market strike ladders, with pre-registered gates and the diagnostics that failed to predict it. |
| [WM-data-scrutiny](https://github.com/physicalreasoning/WM-data-scrutiny) | Coverage audit of 1,300 clips from 5 open-source manipulation datasets against 8 physical phenomena; identifies multi-object interaction, occlusion, and failure recovery as structural gaps in existing robot training data. | 
| [web](https://github.com/physicalreasoning/web) | Source for [physicalreasoning.ai](https://physicalreasoning.ai). |

### Read more

- Site: [physicalreasoning.ai](https://physicalreasoning.ai)
- Blog: [physicalreasoning.ai/blog](https://physicalreasoning.ai/blog/)
  - [Prediction is not understanding, until it is](https://physicalreasoning.ai/blog/prediction-vs-understanding/)
  - [The weather market learned to read the forecast](https://physicalreasoning.ai/blog/the-weather-market-learned-to-read-the-forecast/)
  - [We tried to break our own diagnostic](https://physicalreasoning.ai/blog/we-tried-to-break-our-own-diagnostic/)
- Join us: [physicalreasoning.ai/join](https://physicalreasoning.ai/join/)

Our public code is licensed under Apache-2.0. To report a security issue, see our
[security policy](https://github.com/physicalreasoning/.github/blob/main/SECURITY.md).
