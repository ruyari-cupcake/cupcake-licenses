# Cupcake Licenses

Canonical license terms and reusable notices for software published by
[Ruyari Cupcake](https://github.com/ruyari-cupcake).

The current software license is the
[Cupcake Restricted Use License 1.0](licenses/CUPCAKE-RESTRICTED-1.0.md)
(`LicenseRef-Cupcake-Restricted-1.0`). It permits ordinary use of an authorized,
unmodified release, but does not permit modification, reverse engineering,
unofficial redistribution, automated collection, or supplying the software to an AI/LLM for
inspection, explanation, debugging, transformation, training, or derivative generation.

This is a proprietary source-available license, not an open-source license.

## Which projects are covered?

The machine-readable [project registry](registry/projects.json) records projects selected for
adoption. A particular file or release is covered only when its own notice identifies this
license and version.

## Applying the license

For a bundled JavaScript release, preserve the `/*! ... */` header from
[notices/bundled-js-header.txt](notices/bundled-js-header.txt) during minification and ship the
full license as `LICENSE.md` beside the bundle. For a packaged release, include
[notices/release-NOTICE.md](notices/release-NOTICE.md) and the full license in the archive.

Use an immutable version URL in distributed artifacts:

```text
https://github.com/ruyari-cupcake/cupcake-licenses/blob/v1.0.0/licenses/CUPCAKE-RESTRICTED-1.0.md
```

Include the complete terms whenever the distribution format allows it.

Korean guide: [README.ko.md](README.ko.md). AI-facing notice:
[AI-USAGE-POLICY.md](AI-USAGE-POLICY.md). Machine-readable policy:
[machine-readable/ai-policy.json](machine-readable/ai-policy.json).
