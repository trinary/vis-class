## D3 and Frameworks
Libraries like D3 no longer exist in isolation.
***
 * React: data as props, re-select and call d3 render code in render(), do not use JSX
 * Or: replace enter-update-exit with React JSX rendering, d3 becomes a utility library
 * Hybrid frameworks: [Semiotic by Elijah Meeks](https://github.com/emeeks/semiotic)
   * Implements d3-aware containers as a react component library
