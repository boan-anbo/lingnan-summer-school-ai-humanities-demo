# Discovery Trail: Lingnan Origin Candidate

## Original task

Collect exactly one promising open-internet source candidate for the question:

> Did Lingnan begin in Macau around 1899, or in Guangzhou/Canton?

The agent was instructed not to make the final historical judgment.

## Tool situation

The subagent reported:

- web search worked
- page opening worked
- `curl` download worked
- local PDF-to-image rendering worked with `pdftoppm`
- GUI browser was not available

## Search path

The subagent used a small search budget. It reported these queries:

- `Lingnan University history founded Macau 1899 Guangzhou Canton`
- `Lingnan University Canton Christian College Macau 1899 history`

It checked a small set of first-page or highly relevant hits:

- Yale Library exhibit
- Lingnan Digital Commons record
- Lingnan University milestones
- Lingnan Foundation history

## Selected candidate

The selected source candidate was:

- Title: `Canton Christian College: its field and work in China`
- Owner: Digital Commons @ Lingnan University
- Collection: Records of Lingnan University (Guangzhou, 1888-1952)
- Author/date shown: Canton Christian College, 1908
- URL: https://commons.ln.edu.hk/lingnan_trustees_records/2/
- Type: open-access institutional repository PDF / scan

The candidate was chosen because it has clear visible provenance, a date close to the events under discussion, and a downloadable PDF.

## Saved artifacts

The subagent saved:

- `canton-christian-college-field-work-china-1908.pdf`
- `canton-christian-college-field-work-china-1908-page1.png`

After opening the PDF, we searched inside the text and rendered the relevant page:

- `rendered-pages/page-12.png`
- `rendered-pages/page-12-macao-crop.png`

## What happened after discovery

The first page showed repository provenance, but it did not contain the Macau/Macao passage.

We then searched the PDF text for `Macao`, `Macau`, and related dates. The relevant passage appeared on PDF page 12, not page 1.

The important wording is around:

> In June of 1900 ... the school was moved to Macao ... where it remained until ... 1904.

This is a useful teaching point: finding a credible candidate is not the same as verifying the claim. The human still has to open the source, inspect the page, and decide what the passage actually says.

## Classroom explanation

I asked the agent to search the open web, but with a strict limit: find only one promising candidate. It checked a few likely sources and chose a Lingnan Digital Commons PDF because the source page clearly identified the owner, collection, date, citation, and downloadable file. Then we opened the PDF ourselves. The first page only proved provenance; the relevant Macao passage was later in the document. That is why the next step is human inspection and note-taking, not automatic conclusion.
