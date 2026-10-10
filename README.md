# Headcount Sanity Check

A questionnaire hiring managers complete before they ask for a new headcount. Each answer decides the next question. Some answers stop the request. Others pause it until the manager does something first. At the end the manager gets a summary to give to whoever reviews requests.

There is also a printable PDF checklist for anyone who prefers paper.

## What is in this folder

- `index.html`: the questionnaire. It is one file and needs no server.
- `headcount-checklist.pdf`: the printable checklist. The page links to it.
- `README.md`: this file.

## Put it on GitHub Pages (free)

1. On GitHub, click **New repository**. Give it a name, such as `headcount-check`. Choose **Public**. Free GitHub Pages needs a public repository.
2. Click **uploading an existing file**. Drag in `index.html` and `headcount-checklist.pdf`. Click **Commit changes**.
3. Open **Settings**, then **Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Pick **main** and the **/ (root)** folder. Click **Save**.
4. Wait about a minute and refresh. The web address shows at the top of the Pages screen. It looks like `https://YOUR-NAME.github.io/headcount-check/`.

## Things to know

- Answers stay in the visitor's browser. Nothing is sent or saved anywhere. If someone closes the page, their answers are gone.
- The questions live in `index.html`, in one block that starts with `const FLOW`. Question numbers update on their own when a question is added or removed.
- The page loads two fonts from Google Fonts. If they cannot load, it uses the computer's own fonts.
- At the end of the form, the **Sanity check** button reads the answers and lists thin answers, repeated answers, and choices that continued after advice. It says Ready to submit or Strengthen these answers first. It gives no approval score and sends nothing anywhere.
- The private AI feedback button only appears when the page is opened inside Claude. On GitHub it stays hidden, because it would need a secret key and a server.

## License

No license is included. Add one if you want others to reuse this.
