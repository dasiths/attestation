# in-toto Attestation Framework

The in-toto Attestation Framework provides a specification for generating
verifiable claims about any aspect of how a piece of software is produced.
Consumers or users of software can then validate the origins of the software,
and establish trust in its supply chain, using in-toto attestations.

## Learning about in-toto attestations

Visit [https://in-toto.io](https://in-toto.io) to learn about the larger
in-toto project.

For a deeper dive, we recommend reading through our [documentation] to learn
more about the goals of the in-toto Attestation Framework.

## Working with in-toto attestations

The core of the in-toto Attestation Framework is the [specification] that
defines the format for in-toto attestations and the metadata they contain.

We also provide a set of [attestation predicates], which are metadata
formats vetted by our maintainers to cover a number of common use cases.

For tooling integration, we provide [protobuf definitions] of the spec.
We currently only provide a pre-generated library for Go.

## Is your use case not covered by existing predicate types?

Take a look at the open [issues] or [pull requests] to see if your usage has
already been reported. We can help with use cases, thinking through options,
and questions about existing predicates. Feel free to comment on an existing
issue or PR.

## Want to propose a new predicate type?

If you still can't find what you're looking for, open a new issue or
pull request. Before opening a request for a new metadata format, please
review our [New Predicate Guidelines].

## Governance

The in-toto Attestation Framework is part of the [in-toto] project under the
[CNCF].

Use `@in-toto/attestation-maintainers` to tag the maintainers on GitHub.

## Disclaimer

The in-toto Attestation Framework is still under development. We are in the
process of developing tooling to enable better integration and adoption of
the framework. In the meantime, please visit any of the language-specific
[in-toto implementations] to become familiar with current tooling options.

[CNCF]: https://www.cncf.io/projects/in-toto/
[New Predicate Guidelines]: docs/new_predicate_guidelines.md
[attestation predicates]: spec/predicates/
[documentation]: docs/
[in-toto]: https://in-toto.io
[in-toto implementations]: https://github.com/in-toto
[issues]: https://github.com/in-toto/attestation/issues?q=is%3Aopen+is%3Aissue
[protobuf definitions]: docs/protos.md
[pull requests]: https://github.com/in-toto/attestation/pulls?q=is%3Aopen+is%3Apr
[specification]: spec/
