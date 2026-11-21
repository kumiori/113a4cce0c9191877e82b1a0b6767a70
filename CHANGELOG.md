# Changelog

## 0.3.1

- Publish a versioned capabilities manifest in the wheel and release assets,
  accessible through `get_capabilities()` and `game-gamer capabilities`.
- Add reproducible immutable-release tooling and downstream upgrade proposals
  with compatibility reports and explicit human review.
- Include the 0.3.0 public extension contract: registered commands, policies,
  projections, exact extension binding, replay and branching support.
- Include the 0.3.0 world-driven mission lifecycle and optional target locking.

The public upstream previously contained 0.2.0; 0.3.0 was a local Commons bundle.
This release preserves its event schemas and extension contract. No saved-world
migrations or application extension version changes are performed.
