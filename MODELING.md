# Modelling

Lead with the out-of-sample comparison. Same rows in every model. N_train = 55,738. N_test = 13,935.

| Model | OOS R² |
|---|---:|
| Industriousness only | **.360** |
| Order + standards + duty | .117 |
| All four facets | .374 |

Industriousness alone recovers **36%** of delay variance out of sample. The rest of conscientiousness recovers **12%**. Adding it gains **1.4 points**.

Nested in-sample OLS on the same 69,673 complete cases: industriousness R² = .364; full facets .377; ΔR² = .013.

M4 standardised betas: industriousness .53; order .15; standards −.002 (*p* = .62); duty −.021 (*p* < .001, two-hundredths of a SD).

Held-out AUC: industriousness .79; no industriousness .65; full .79.
