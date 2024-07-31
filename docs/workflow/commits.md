# Commit Guidelines

## Commit Message Structure

Structure your commit message as follows:

```
<type>(<scope>): <subject>

<body>

<footer>
```

- Type: Describes the kind of change (see types below)
- Scope: (Optional) Describes what is affected by the change
- Subject: A brief description of the change
  - Use the imperative mood: "Add" not "Added"
  - Start with a capital letter
  - Do not end with a period
  - Keep it under 50 characters

- Body: (Optional) More detailed explanation of the change
  - Separate from subject with a blank line
  - Wrap lines at 72 characters
  - Use to explain the what and why of the change, not the how

- Footer: (Optional) Reference issues affected or closed by the change

## Commit Types

See the [Glossary](glossary.md) for a list of commit types and examples.

## Example of a Detailed Commit Message

```
feat(auth): Implement two-factor authentication

- Add option for users to enable 2FA
- Implement TOTP (Time-based One-Time Password) generation
- Create UI for 2FA setup and verification

This feature enhances account security by allowing users to add an extra 
layer of protection to their login process.

Closes #123
```

For more examples, please refer to the [Glossary](glossary.md).
```