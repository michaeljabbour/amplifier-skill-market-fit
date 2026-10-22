---
bundle:
  name: market-fit
  version: 0.1.0
  description: >-
    Coaches a person to one clear, customer-named offer while growing their own
    judgment: the market-fit skill, a /fit working mode, and a staged,
    human-gated recipe.

# Thin root: a lean host plus this bundle's behavior. Most users should add only
# the behavior to their existing host (see README).
includes:
  - bundle: git+https://github.com/microsoft/amplifier-foundation@main#subdirectory=bundles/anchors/bundle.md
  - bundle: market-fit:behaviors/market-fit
---

@anchors:context/system.md
