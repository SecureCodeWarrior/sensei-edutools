# QuickFix using Intentions

Sensei hooks into the normal IntelliJ intentions dialog.

- click on the return statement line flagged as an error
- press  &amp;shortcut:ShowIntentionActions;
  - _by default `alt+enter` (Windows) or `option+enter` (macOS)_

You should see an intentions dialog popup.

## Use QuickFix

Select the QuickFix entry for `say "Welcome to Sensei!"`

The code should be amended so that the `return` statement now reads:

```java
return "Welcome to Sensei!";
```
   
Press the `[Check]` button below to complete the task. 