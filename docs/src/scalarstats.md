# Scalar Statistics

The package implements functions for computing various statistics over an array of scalar real numbers.

## Moments

```@docs
Base.var(v::StatsBase.RealArray, w::AbstractWeights; mean=nothing, corrected::DepBool=nothing)
Base.std(v::StatsBase.RealArray, w::AbstractWeights; mean=nothing, corrected::DepBool=nothing)
mean_and_var
mean_and_std
skewness
kurtosis
moment
```

## Measurements of Variation

```@docs
span
variation
sem
mad
```

## Z-scores

```@docs
zscore
zscore!
```

## Entropy and Related Functions

```@docs
entropy
renyientropy
crossentropy
kldivergence
```

## Quantile and Related Functions

```@docs
percentile
iqr
nquantile
quantile
Base.median{W<:Real}(v::StatsBase.RealVector, w::AbstractWeights{W})
```

## Mode and Modes

```@docs
mode
modes
```

## Summary Statistics

```@docs
summarystats
describe
```
