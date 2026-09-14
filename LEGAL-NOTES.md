# Legal and platform notes

These notes explain why the repository uses explicit terms and why private source remains the
strongest practical control. They are not part of the License and are not legal advice.

Checked on 2026-09-14:

- [GitHub's repository licensing guide](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)
  says default copyright law applies when no license is provided, while public GitHub users may
  still view and fork under GitHub's Terms.
- [GitHub Terms of Service, Section D](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service#d-user-generated-content)
  grants public-repository users platform viewing/forking rights and grants GitHub and its
  affiliates separate platform rights that currently include AI/ML development and training.
  A project license cannot withdraw a grant made directly to GitHub by accepting those Terms.
- [RFC 9309](https://www.rfc-editor.org/rfc/rfc9309.html) states that `robots.txt` rules are not
  access authorization and are not a substitute for real access controls.
- [Directive (EU) 2019/790, Article 4](https://eur-lex.europa.eu/eli/dir/2019/790/oj/eng)
  recognizes reservation of rights against the general text-and-data-mining exception,
  including machine-readable reservations for online content. Section 4 of the License makes
  that reservation explicit without claiming it overrides mandatory local law.

The practical stack is therefore: keep valuable source private; distribute only the necessary
bundle or package; place a preserved notice in that artifact; include the full versioned terms;
and use technical access controls wherever actual secrecy is required.
