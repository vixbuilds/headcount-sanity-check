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

- Each answer decides the next question. Some answers stop the request.
- Others recommend a step first, such as posting the job internally. The manager can do the step and answer again, or continue and write why. Skipped steps appear at the top of the summary for the Req Approver.
- At the end, the **Sanity check** button lists thin answers, repeated answers, skipped steps, and choices that continued after advice. It says Ready to submit or Strengthen these answers first. It gives no approval score.
- Answers stay in the manager's browser. Nothing is sent or saved anywhere. If the manager closes the page, their answers are gone, so they should copy the summary before they leave.

## Use your own copy

To change questions or wording for your company, download the files and edit them.

- The questions live in `index.html`, in one block that starts with `const FLOW`. Question numbers update on their own when you add or remove a question.
- `index.html` is one file and needs no server. You can put it on your intranet or any website.
- The page loads two fonts from Google Fonts. If your network blocks them, it uses the computer's own fonts.

## License

Free to use and adapt under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You can use it at work, change it, and share it. Please credit it like this:

> Headcount Sanity Check by vixbuilds, https://github.com/vixbuilds/headcount-sanity-check, licensed under CC BY 4.0. Changed by [your company] (if you changed it).

If you use the files as they are, keeping the GitHub link at the bottom of each page and this README is enough. If you change them, also add the credit line above somewhere people will see it, such as your intranet page.
