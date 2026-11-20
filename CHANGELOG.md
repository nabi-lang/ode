# Changelog

All notable changes to this package. Versions follow semver, independent of the Nabi toolchain.

## 0.1.0 (unreleased)

First release.

- `solve_ivp` with adaptive methods `Rk23`, `Rk45`, `Dop853`, `Radau`,
  `Bdf`, `Rodas` and `Auto` (stiff / non-stiff switching), dense output and
  event location.
- Fixed-step Runge-Kutta: Euler, midpoint, Heun, RK4.
- Symplectic integrators: symplectic Euler, Verlet, leapfrog, Yoshida 4
  and 6.
- Boundary value problems: `solve_bvp` and `solve_bvp_params`, 4th order
  collocation with mesh refinement.
- Test problems (`problems::robertson`, `van_der_pol`, `lorenz`, `kepler`,
  and more).
- The `ops` feature (default): `Flow` composition and `⊳`.
- Pure Nabi, every target including wasm. Needs Nabi 0.1 or later; depends
  on `linalg`.
