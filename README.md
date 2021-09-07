# angular-d62jgy

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/angular-d62jgy)

### Expected behavior
Pressing Next to increment the selected step programmatically should mark the next step selected in the UI.

### Actual behavior
Pressing Next skips the new mat-steps and marks the first not newly introduced mat-step with the content of the new mat-step.

### How to reproduce the bug:
- click "Show Thyself!"
- click "Next"
- note that gray highlight is on the fourth step instead of second
- click "Next"
- note that gray highlight is on the second step instead of third
- click "Next"
- note that gray highlight is on the third step instead of fourth
