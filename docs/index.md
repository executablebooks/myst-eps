(governance:meps)=
# MyST Enhancement Proposals

Because the MyST specification has many interior and exterior stakeholders, we use a more formal and structured process around changing the specification.
These are called **MyST Enhancement Proposals (MEPs)**.

This process is encoded in https://github.com/executablebooks/myst-enhancement-proposals and in this documentation.
The sections below describe the process, and the [MEP index](meps/index) is where you can find all of our MEPs.

```{toctree}
:maxdepth: 1
overview
meps/index
```

```{admonition} Work in progress!
This process is relatively new.
Bear with us, and please provide feedback if you think the process can be improved!
```

## MyST Specification

The MyST specification is at [`spec.myst-tools.org`](https://spec.myst-tools.org) (repository: https://github.com/executablebooks/myst-spec).
It is the source of truth for MyST Markdown syntax.

When a MEP is accepted, it is generally implemented by modifying the specification and the documentation around it.
MyST parsers may then choose to implement these changes on their own.

```{toctree}
:hidden:
MyST specification <https://spec.myst-tools.org>
```

## Goals of the MEP process

Below are a few goals that guided the MEP process as it currently exists.

- **Formal without being oppressive**. Provide slightly more structure than our organizational policy, to account for the fact that MEPs have many more stakeholders and decision-makers. However keep it as simple as possible to avoid overly-complex discussion that leads to frustrating and inefficient decision-making.
- **Make the process inclusive**. Ensure a process for discussion and deciding that is inclusive and that encourages productive discussion from many parts of the project.
- **Make the process efficient**. Ensure that there is enough information, and with the right structure, to have focused asynchronous discussion that leads to a decision-making cadence that is sustainable for the project.
- **Design for many stakeholders**. Ensure that the specification evolves in a way that benefits our major stakeholders, and that is not unintentionally over-fit to the perspective of only a subet of the Executable Books community.