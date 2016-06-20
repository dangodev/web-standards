# Dialogs

Popups that block further user interaction until a selection is made from the options given.

- [ ] Dialogs should always contain a non-destructive backout option (e.g. `Cancel`); never force a dialog to choose between two destructive choices.
- [ ] Avoid using `Yes` as an affirmative choice, and instead repeat the key verb in the question asked (ie. _Are you sure you want to delete?_ `Cancel` | `Delete`)
- [ ] In LTR languages, always place the affirmative (read: possibly destructive) action on the right; cancel or non-destructive option on the left.
