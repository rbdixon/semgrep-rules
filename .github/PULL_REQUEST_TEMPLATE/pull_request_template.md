## Link to an issue, if relevant

*Issue link*

### Adding a new rule? Look over this PR checklist

- The issue or PR has links, references, or examples.
- The rule has **true positive** and **true negative** test cases in a file that matches the rule name.

> If the rule is `my-rule`, the test file name should be `my-rule.js`.
>
> True positives are marked by comments with `ruleid: <my-rule>` and true negatives are marked by comments with `ok: <my-rule>`.

- The rule has a good message. A good message includes:

> 1. A description of the pattern (e.g., missing parameter, dangerous flag, out-of-order function calls).
> 1. A description of why this pattern was detected (e.g., logic bug, introduces a security vulnerability, bad practice).
> 1. An alternative that resolves the issue (e.g., use another function, validate data first, discard the dangerous flag).
