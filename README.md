# The Ledger That Remembers Why

A vision for **verifiable finance at scale**, and the case for Radix as an execution substrate for institutional and agentic finance.

This repository contains the static website for *The Ledger That Remembers Why*, an independent discussion paper on what financial infrastructure needs to provide as markets move from digitising records to digitising execution.

## The argument

Financial infrastructure increasingly needs to establish more than the fact that value moved. It needs to make the asset, authority, rules and outcome of a transaction verifiable at the point of execution.

The paper proposes seven technology-neutral principles for that architecture and uses Radix as a worked case. It looks at where the current model is strong, where important gaps remain, and what community-led scaling work should prove.

The north star is simple:

> **Verifiable finance at scale.**

## Key themes

- assets understood by the execution environment
- attributable and auditable state changes
- verification inside the transaction boundary
- deterministic technical finality
- confidentiality without giving up verifiability
- explicit, scoped and attestable authority
- verification that survives network boundaries
- scaling the Radix Engine rather than optimising for a headline TPS number

Privacy with proof remains the main institutional gap. The paper also argues that Hyperscale should be judged by whether the Radix Engine and its financial semantics scale under real workloads, not by synthetic throughput alone.

## Files

- `index.html`: the complete dependency-free website
- `README.md`: this file

## Run locally

No build step is required. Open `index.html` in a browser.

## Deploy with GitHub Pages

1. Put `index.html` and `README.md` in the repository root.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`.
5. Save.

GitHub will publish the site on a `github.io` URL. A custom domain can be added later from the same Pages settings.

## Before publishing

Replace the placeholder canonical and Open Graph URL in `index.html`:

`https://example.com/the-ledger-that-remembers-why`

with the final public URL.

It is also worth checking the publication date, author metadata and social preview text before launch.

## Status

This is an independent discussion paper. It is not an official publication of any Radix entity. References to future capabilities or priorities are proposals for discussion rather than statements of an adopted roadmap.

The paper is intended to be challenged. The point is not to ask the community or the market to accept the thesis on trust, but to make the thesis testable.
