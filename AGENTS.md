\# PhotoPoP Website Instructions



\## Project structure



\- This is a static website.

\- `index.html` is the main page.

\- Images are stored in `images/`.

\- Preserve existing relative file paths unless a change requires restructuring.

\- Use UTF-8 for all text files.



\## Editing rules



\- Make only changes related to the user's request.

\- Do not rewrite unrelated text, styles, or layout.

\- Do not rename or delete existing images unless explicitly requested.

\- Preserve desktop and mobile usability.

\- Add appropriate alt text when adding images.

\- Do not add unnecessary frameworks or dependencies.



\## Preview and validation



\- Preview the website through a local HTTP server.

\- The preview command is:

&#x20; `npx --yes serve . -l 8000`

\- Confirm that `index.html` loads successfully.

\- Confirm that all referenced images load.

\- Check for broken relative links and obvious browser errors.

\- Check the page at desktop and mobile widths.



\## Visual review



For visual changes, capture the completed page at:



\- Desktop: 1440 × 900

\- Mobile: 390 × 844



When possible, provide before-and-after screenshots in the task result.

Do not commit temporary screenshots or preview artifacts to the repository.



\## Git workflow



\- Base work on the latest `main` branch.

\- Make changes on a dedicated task branch.

\- Use a short descriptive branch name beginning with `codex/`.

\- Do not merge changes into `main`.

\- After validation, summarize the changes and tests performed.

\- Create a pull request when requested.

\- The repository owner performs the final merge.

