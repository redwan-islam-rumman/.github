#Contribution Guidelines

## How to Contribute

1. Fork the repository
2. Create a new branch for your feature or bug fix
3. Make your changes
4. Write tests for your changes (if applicable)
5. Run the test suite to ensure all tests pass
6. Commit your changes following the [Commit Message Guidelines](#commit-message-guidelines)
7. Push your branch to your fork
8. Submit a pull request to the main repository

## Commit Message Guidelines

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification for our commit messages. This leads to more readable messages that are easy to follow when looking through the project history.

### Commit Message Format

Each commit message consists of a **header**, a **body**, and a **footer**. The header has a special format that includes a **type**, an optional **scope**, and a **subject**:

```
<type>(<scope>): <subject>

<body> (optional)

<footer>  (optional)
```

#### Type

Must be one of the following:

- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation only changes
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **perf**: A code change that improves performance
- **test**: Adding missing tests or correcting existing tests
- **chore**: Changes to the build process or auxiliary tools and libraries such as documentation generation

#### Scope

The scope is optional and should be the name of the npm package affected (as perceived by the person reading the changelog generated from commit messages).

#### Subject

The subject contains a succinct description of the change:

- Use the imperative, present tense: "change" not "changed" nor "changes"
- Don't capitalize the first letter
- No dot (.) at the end

#### Body (optional)

The body should include the motivation for the change and contrast this with previous behavior.

#### Footer (optional)

The footer should contain any information about Breaking Changes and is also the place to reference GitHub issues that this commit closes.

Breaking Changes should start with the word `BREAKING CHANGE:` with a space or two newlines. The rest of the commit message is then used for this.

### Examples

```
feat(lang): add Polish language

fix(player): prevent racing of requests

docs(readme): update install instructions

style(whitespace): remove whitespace from config file

refactor(auth): improve refresh token logic

perf(pencil): remove graphiteWidth option

test(middleware): add tests for user authentication

chore(deps): update dependency @types/react to v16.9.32
```

By following these guidelines, you help maintain a clean and organized project history. Thank you for your contributions!
