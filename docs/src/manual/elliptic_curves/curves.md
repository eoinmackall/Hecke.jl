```@meta
CurrentModule = Hecke
CollapsedDocStrings = true
DocTestSetup = Hecke.doctestsetup()
```
# Elliptic Curves

## Creation of elliptic curves

Elliptic curves can be created using the `elliptic_curve` function.

```@docs
elliptic_curve
elliptic_curve(::MPolyRingElem, ::MPolyRingElem, ::MPolyRingElem)
```

```@docs
elliptic_curve_from_j_invariant
```

## Basic properties

```@docs
base_field(::EllipticCurve)
base_change(::Field, ::EllipticCurve)
base_change(::Any, ::EllipticCurve)
coefficients(::EllipticCurve)
a_invariants(::EllipticCurve)
b_invariants(::EllipticCurve)
c_invariants(::EllipticCurve)
discriminant(::EllipticCurve)
j_invariant(::EllipticCurve)
equation(::EllipticCurve)
hyperelliptic_polynomials(::EllipticCurve)
```

## Models
