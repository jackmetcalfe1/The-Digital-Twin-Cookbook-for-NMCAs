# Contributing to the Digital Twin Cookbook for NMCAs

Thank you for helping to improve this cookbook. It is a living resource: the
recipes are stronger when National Mapping and Cadastral Agency (NMCA) staff,
researchers and wider practitioners share corrections, evidence and real cases.

You do **not** need to be a software developer to contribute. Most contributions
are improvements to the words, evidence and worked examples on the pages. This
guide explains the kinds of contribution we welcome and the simplest way to make
each one.

## Who can contribute

- **NMCA employees** — practitioners applying the recipes in a real agency. Your
  worked examples, corrections and "this did not match our situation" feedback
  are especially valuable.
- **Researchers and academics** — people who can strengthen or update the
  evidence base behind a recipe or the underlying NMCA-DT Framework.
- **Wider practitioners and partners** — anyone working with Digital Twins,
  geospatial information or public-sector data who can improve clarity or add a
  relevant case.

## The simplest route: open an issue

If you are not comfortable editing files directly, the easiest way to contribute
is to **[open an issue](../../issues/new/choose)**. Choose the template that
matches what you want to do and fill in the form. A maintainer will pick it up at
the next triage (see [GOVERNANCE.md](GOVERNANCE.md)).

You can also raise a question or share experience in
**[Discussions](../../discussions)** if the repository has them enabled.

## Types of contribution

The five contribution types below cover almost everything. Each lists the easiest
route and what a good contribution contains.

### 1. Minor correction

A typo, broken link, wrong cross-reference, or a small wording fix that does not
change the meaning of a recipe.

- **Easiest route:** open a *Recipe feedback / problem* issue, or edit the page
  directly (see *Editing a page directly* below).
- **What to include:** the page affected and the corrected text.

### 2. Recipe improvement

A change to the substance of a recipe — clearer steps, a better quality check, an
added input or output, or a sharper decision question.

- **Easiest route:** open a *Recipe feedback / problem* issue describing the
  change, or open a pull request.
- **What to include:** which part of the recipe changes and why, and how it helps
  the NMCA make the decision the recipe supports. Note if it affects the
  templates or the workflow pathways.

### 3. New case example

A short, real or realistic worked example of how an NMCA applied (or could apply)
a recipe. Case examples make the cookbook concrete.

- **Easiest route:** open a *Case study contribution* issue.
- **What to include:** the country / agency context (anonymised if needed), the
  decision faced, which recipe(s) were used, what was produced, and what was
  learned. State clearly whether the case is real, adapted or illustrative.

### 4. Academic / evidence update

A change to the references, evidence notes or framework claims that underpin a
recipe — for example new research, a revised principle, or a correction to a
cited source.

- **Easiest route:** open a *Recipe feedback / problem* issue and mark it as an
  evidence update, or open a pull request that edits the references.
- **What to include:** the claim affected, the full citation for the new or
  corrected source, and a one-line note on how it changes the recipe's guidance.
  Evidence updates are reviewed against the cookbook's academic-practitioner
  tone: practical guidance, transparent about its evidence strength.

### 5. Governance proposal

A change to how the cookbook is maintained, scoped or released — for example the
maintainer model, the triage cadence, or the boundaries of what the cookbook
covers.

- **Easiest route:** open a *Governance proposal / question* issue.
- **What to include:** the change proposed, the problem it solves, and any effect
  on contributors or users. Governance changes are decided by consensus among
  maintainers with a documented rationale (see [GOVERNANCE.md](GOVERNANCE.md)).

## Editing a page directly

Every page on the live site has **Suggest an edit**, **Discuss this recipe** and
**Report a problem** links at the foot of the page. The quickest way to fix or
improve text is:

1. Open the recipe on GitHub and choose **Suggest an edit** (this opens the file
   in the GitHub editor and creates a branch and pull request for you).
2. Make your change. Keep the existing front matter (the lines between the `---`
   markers at the top of each file) intact.
3. Describe your change in the pull request, following the
   [pull request template](.github/pull_request_template.md).

You do not need to install anything locally. If you prefer to work locally, this
is a [Jekyll](https://jekyllrb.com/) site built with GitHub Pages; clone the
repository, edit the Markdown files and open a pull request.

## Style and tone

- Write for a non-technical NMCA reader. Plain language, short sentences.
- Keep the academic-practitioner tone: practical advice that is honest about its
  evidence and its assumptions.
- Cite sources for evidence claims. Mark assumptions and uncertainty rather than
  hiding them.
- Use British English spelling to match the existing pages.

## What happens to your contribution

Issues and pull requests are triaged quarterly and bundled into an annual review
and release. Urgent corrections (broken links, factual errors) are handled
sooner. See [GOVERNANCE.md](GOVERNANCE.md) for the full model.

---

Maintained as part of EuroSDR-funded research. For questions outside GitHub,
contact Jack Metcalfe — `jack.metcalfe.16@ucl.ac.uk`.
