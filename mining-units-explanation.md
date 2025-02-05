# Mining Units Explanation

## Base Units
```
Hashrate:     106.4641 TH/s
              [value]   [unit]
              T = Tera (trillion)
              H = Hashes
              /s = per second

PaymentRate:  0.0190 BTC/TH/day
              [value] [unit]
              BTC = Bitcoin
              /TH = per Terahash
              /day = per day
```

## Unit Analysis
```
Earnings = Hashrate × PaymentRate

(BTC/day) = (TH/s) × (BTC/TH/day)

Unit reduction:
- TH cancels out between denominator and numerator
- /s from hashrate × /day gives per day
- Final unit is BTC/day
```

## Example Calculation
```
Input:
- 106.4641 TH/s
- 0.0190 BTC/TH/day

Calculation with units:
106.4641 (TH/s) × 0.0190 (BTC/TH/day)
= 2.02282 BTC/day

Units validate because:
(TH/s) × (BTC/TH/day) = BTC/day
```

## Common Unit Conversions
```
Hash Rates:
1 PH/s = 1,000 TH/s
1 TH/s = 1,000 GH/s
1 GH/s = 1,000 MH/s

Time:
1 day = 24 hours
1 hour = 3,600 seconds
```
