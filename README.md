# FileAssistant

This is an AI assistant for help with file organization.

## Line Width Standards

This repo encourages shorter lines of code
to facilitate side-by-side comparison during code reviews:

- Under 80 characters is ideal.
- 100 characters is fine, just not preferred.
- 120 characters is the max allowed length.
- Anything over 120 characters must be wrapped.

To help with this, vertical ruler settings have been defined.
See [`.editorconfig`](./.editorconfig) for more information
on how to enable them your IDE of choice.

## Conventional Commits

This repo uses [Conventional Commits](https://www.conventionalcommits.org)
to standardize the formatting of commit messages and
automate processes such as versioning and the generation of release notes.
While not strictly required,
it's still highly recommended to follow this standard
as it helps maintain the Semantic Versioning strategy.

To help with this, a Git message template is available by running
`git config commit.template .gitmessage` from the root of the repo.
It should then be visible whenever you run `git commit` while excluding the `-m`,
or in whatever other Git tool you prefer to use. This
[Cheat sheet](https://kapeli.com/cheat_sheets/Conventional_Commits.docset/Contents/Resources/Documents/index)
by Bogdan Popescu can help with the message format if you're new to CC.

## How to build the code

This is just a standard Visual Studio solution.
[FileAssistant.sln](./FileAssistant.sln) is at the root of the repo.
Simply open it and build.

## Community

This project is licensed under the standard [MIT license](./LICENSE).

While this is a personal project, I welcome any and all contributions!
Review [CONTRIBUTING.md](./CONTRIBUTING.md) and [SECURITY.md](./SECURITY.md)
for information about how you can take part.

Please also review the [Code of Conduct](./CODE_OF_CONDUCT.md)
before taking an active roll with this project.
