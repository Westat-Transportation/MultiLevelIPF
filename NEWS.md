# Version 0.0.4

- Parameter `all_weights` to `import` that allows importing also intermediate
  weights.  The output format of `import` has changed, the weights for each
  algorithm are now always a list of weight vectors, even in the default case
  `all_weights == FALSE` (#5).

# Version 0.0.3

- Import results of old Python code (#1).

# Version 0.0.2

- Initial setup