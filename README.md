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
license and version. Older versions keep the terms under which they were originally released;
adding a project to the registry does not retroactively revoke an earlier license.

## Applying the license

For a bundled JavaScript release, preserve the `/*! ... */` header from
[notices/bundled-js-header.txt](notices/bundled-js-header.txt) during minification and ship the
full license as `LICENSE.md` beside the bundle. For a packaged release, include
[notices/release-NOTICE.md](notices/release-NOTICE.md) and the full license in the archive.

Use an immutable version URL in distributed artifacts:

```text
https://github.com/ruyari-cupcake/cupcake-licenses/blob/v1.0.0/licenses/CUPCAKE-RESTRICTED-1.0.md
```

The short notice is a pointer, not a substitute for including the complete terms when the
distribution format allows it.

## Important limits

- A notice and license create legal and machine-readable boundaries; they do not technically
  prevent copying.
- GitHub public repositories remain viewable and forkable under GitHub's Terms. GitHub also
  receives its own platform license from uploaders, including rights stated in its current
  Terms for AI features and affiliated AI/ML technologies. Keep source private if that grant is
  unacceptable.
- A `robots.txt` file inside a GitHub repository cannot control GitHub-wide crawling. The Robots
  Exclusion Protocol is a crawler request, not access authorization.
- The AI/TDM reservation is deliberately explicit, but enforceability and statutory exceptions
  vary by jurisdiction. Obtain advice from a qualified lawyer before relying on these terms for
  a dispute or commercial licensing program.

Korean guide: [README.ko.md](README.ko.md). AI-facing notice:
[AI-USAGE-POLICY.md](AI-USAGE-POLICY.md). Machine-readable policy:
[machine-readable/ai-policy.json](machine-readable/ai-policy.json). Source-backed platform and
legal context: [LEGAL-NOTES.md](LEGAL-NOTES.md).
