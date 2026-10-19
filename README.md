# Pre-submission curation checklist

A small, open-source checklist for reviewing a curated study before asking for feedback. It is built with plain HTML and CSS only: no JavaScript, no build step, no dependencies.

It follows the four-stage workflow described in [Beyond Data Entry: Building a Better Curation Workflow for Microbiome Research](https://medium.com/@aruna.fatima/beyond-data-entry-building-a-better-curation-workflow-for-microbiome-research-d9775589c680):

1. Verify the study metadata
2. Validate the experimental design
3. Trace every signature to its evidence
4. Review before requesting feedback

This is an unofficial helper. It is not an official BugSigDB tool, and it doesn't replace the [BugSigDB Curation Policy](https://bugsigdb.org/Curation_Policy), scientific judgment or peer review.

## Use it

Open `index.html` in a browser. To host it, serve the folder with GitHub Pages or any static host.

- Each stage shows **Complete** when all its boxes are checked.
- A banner appears when every stage is complete.
- **Clear checklist** resets the form. **Print** gives a clean paper copy.
- Checked items are not saved between visits. That would need JavaScript, which this project deliberately avoids.

## Contribute

Contributions are welcome, especially from curators who can say what the checklist is missing or where it is unclear.

- Open an issue to suggest a checklist item or wording change.
- For code changes, keep it HTML and CSS only and check keyboard access, dark mode and print.
- Edit the checklist items in `index.html`. Styles are in `style.css`.

## Requirements

A current browser with support for the CSS `:has()` selector (all major browsers since late 2023).

## License

[MIT](LICENSE)
