# Bug Bounties

The QuantumSavory open source organization is continuously running bounties for bug fixes and enhancements to the tools we are developing. 
The goal of this program is three-fold: building community; providing opportunities for novices; creating better software.

To see all currently available bug bounties use [the organization's search page](https://github.com/search?q=org%3AQuantumSavory+label%3A%22bug+bounty%22&type=issues) or look directly at the issue trackers of the underlying projects. Here is a non-exhaustive list:

- [`QuantumSavory.jl`](https://github.com/QuantumSavory/QuantumSavory.jl/issues?q=is%3Aissue+is%3Aopen+label%3A%22bug+bounty%22)
- [`QuantumClifford.jl`](https://github.com/QuantumSavory/QuantumClifford.jl/issues?q=is%3Aissue+is%3Aopen+label%3A%22bug+bounty%22)
- [`QuantumSymbolics.jl`](https://github.com/QuantumSavory/QuantumSymbolics.jl/issues?q=is%3Aissue+is%3Aopen+label%3A%22bug+bounty%22)

And we have external projects on which we have put bounties (they do not show up in the organization's search page linked above):

- [`QuantumOptics.jl`](https://github.com/qojulia/QuantumOptics.jl/issues?q=is%3Aissue+is%3Aopen+label%3A%22bug+bounty%22)
- [`ResumableFunctions.jl`](https://github.com/JuliaDynamics/ResumableFunctions.jl/issues?q=is%3Aissue+is%3Aopen+label%3A%22bug+bounty%22)

You can always propose your own funded project, if you would like to contribute something of value that is not yet covered by an official bounty. Just contact us, e.g. by posting on the issue tracker or in the "quantum" topic on the [julia discourse forum](https://discourse.julialang.org/).

All bounty projects are expected to be polished, tested, and documented -- not simply a code dump. In particular, code should be structured so that it is easy to review (e.g. squash messy commits, follow github etiquette, organize big changes in separate commits so the reviewer can keep their bearings). Documentation should be high-quality, potentially including more than simply docstrings. Examples might be expected to be implemented. We will help you and guide you during the polishing steps, especially if you are a new contributor.

Larger projects (≥$800) will be set up more in the style of Summer of Code Projects. Chiefly, that means we would expect some form of "proof of skill", as usually required from GSoC and JSoC applicants, most commonly done by submitting and getting merged a simple pull request dealing with a minor issue.

If someone abandons a bounty project and someone else finishes it, whoever finishes the project gets the award. The original author will always be contacted and given a chance to finish their work withing a reasonable scope of time. We would like to discourage participants from reserving one bounty and submitting unrelated bounties: such bounties will be honored, but we might request that the original reservation be removed to enable other participants to engage.

The Funding for these bounties comes from the National Science Foundation and from the NSF Center for Quantum Networks.
The payouts are managed by the NumFOCUS foundation and processed in bulk once every two months.
If you live in a country in which NumFOCUS can make payments, you can participate in this bounty program.

### Payout procedure after bounty completion

To process a payment after a completed bounty please do the following: Email [skrastanov@umass.edu](mailto:skrastanov@umass.edu) with your name, email, and bounty PR URL. You will be given a link at which to upload your invoice (as a PDF, here is a [popular template](https://create.microsoft.com/en-us/templates/invoices)). It will need to include:

- a unique invoice number (you can make it up, it is for your record keeping)
- date of submission
- period when the work was completed
- specifying this is for an "Award: bug bounty - <brief description or issue/PR number>" (the word "award" is important for proper tax filing)
- the total amount
- your information: name, email, postal address
- bill it to "NumFOCUS for the Julia project"

For tax purposes we will also need everyone to submit a [W-9 (for payments in the US)](https://www.irs.gov/pub/irs-pdf/fw9.pdf) or a [W-8 (if out of the country)](https://www.irs.gov/pub/irs-pdf/fw8ben.pdf) -- just upload it when you fill out the invoice form. Do not worry if some part of the form is byzantine or unclear -- just leave it empty and the NumFOCUS folks will let you know if they need more information. Apologies for this complication, the US tax system is a bit antiquated.
