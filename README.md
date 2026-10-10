# Headcount Sanity Check

A set of free resources for HR teams that review requests for new headcount.

## For HR teams

There are three resources. Each one is for a different person.

| File | Who uses it | What it does |
|---|---|---|
| `index.html` | Hiring managers | A questionnaire they fill out before they ask for a new headcount. At the end they get a summary to give to their Req Approver. |
| `headcount-checklist.pdf` | Hiring managers | The same questionnaire on paper, for anyone who prefers to fill it in by hand. The questionnaire page links to it. |
| `sample-team-survey.pdf` | HR or the Req Approver | An anonymous survey for the hiring manager's current team. It covers workload, work-life balance, and how work is shared. |

**Req Approver** means whoever reviews and approves headcount requests at your company. It can be one person or a group.

### About the team survey

- Do not give the survey to hiring managers, and do not link to it from the questionnaire. The manager should not send it or see it before the team answers.
- Page 3 is for HR only. Remove it before you send the survey to the team.
- Copy the questions into an anonymous online form, such as Microsoft Forms or Google Forms, with name and email collection turned off. Handwriting on paper can be recognized.
- Share combined results with the manager only if at least 5 people answer.

## How the questionnaire works

Each answer decides the next question. Some answers stop the request. Others recommend a step first, such as posting the job internally. The manager can do the step and answer again, or continue and write why. Skipped steps appear at the top of the summary for the Req Approver.

## Put it on GitHub Pages (free)

1. On GitHub, click **New repository**. Give it a name, such as `headcount-check`. Choose **Public**. Free GitHub Pages needs a public repository.
2. Click **uploading an existing file**. Drag in `index.html`, `headcount-checklist.pdf`, and `sample-team-survey.pdf`. Click **Commit changes**.
3. Open **Settings**, then **Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Pick **main** and the **/ (root)** folder. Click **Save**.
4. Wait about a minute and refresh. The web address shows at the top of the Pages screen. It looks like `https://YOUR-NAME.github.io/headcount-check/`.

The survey PDF is a template, so it is fine to keep it in a public repository. Its link is `https://YOUR-NAME.github.io/headcount-check/sample-team-survey.pdf`. Share that link with HR teams, not hiring managers.

## Things to know

- Answers stay in the visitor's browser. Nothing is sent or saved anywhere. If someone closes the page, their answers are gone.
- The questions live in `index.html`, in one block that starts with `const FLOW`. Question numbers update on their own when a question is added or removed.
- The page loads two fonts from Google Fonts. If they cannot load, it uses the computer's own fonts.
- At the end of the form, the **Sanity check** button reads the answers and lists thin answers, repeated answers, skipped steps, and choices that continued after advice. It says Ready to submit or Strengthen these answers first. It gives no approval score and sends nothing anywhere.
- The private AI feedback button only appears when the page is opened inside Claude. On GitHub it stays hidden, because it would need a secret key and a server.

## License

No license is included. Add one if you want others to reuse this.
