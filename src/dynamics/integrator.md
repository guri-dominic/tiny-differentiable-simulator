
# TODO:
+ [ ] implement RKMK (order2)
    + [ ]
+ [ ] generalized RKMK via Butcher Tableaus

```cpp
template <typename Algebra>
void integrate_rkmk2(MultiBody<Algebra> &mb, typename Algebra::VectorX &q,
                     typename Algebra::VectorX &qd,
                     const typename Algebra::VectorX &qdd,
                     const typename Algebra::Scalar &dt) {
    // TODO
}
```
## derivation
+ **from HW1**


```cpp
template <typename Algebra>
void integrate_rkmk2_qdd(MultiBody<Algebra>& mb, typename Algebra::VectorX& q,
    typename Algebra::VectorX& qd,
    const typename Algebra::VectorX& qdd,
    const typename Algebra::Scalar& dt) {
        // TODO
    }
```

## Benchmark
+ `pendulum_example_gui.cpp` --> `./example/pendulum_example_tiny_gui`
    + ran this for X hours & calculate energy
    
***

## 
```cpp
generic_integrator(..., butcher_tableau=RKMK2()){
    // TODO
}
```