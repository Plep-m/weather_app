# Git Commit Message Convention

## Format

<type>: <description>

[optional body]

[optional footer]


## Components

- `<type>`: Denotes the type of the commit. It could be one of the following:
  - `feat`: for a new feature
  - `fix`: for a bug fix
  - `docs`: for documentation updates
  - `style`: for changes related to code style
  - `refactor`: for code refactoring
  - `test`: for adding or modifying tests
  - `chore`: for regular maintenance or tooling changes

- `<description>`: A brief, clear, and concise description of the changes made in the commit.

- `[optional body]`: Additional information about the commit. This can include more detailed explanations if necessary.

- `[optional footer]`: Any extra details or references, such as issue numbers, JIRA ticket numbers, etc.

## Example

feat: Add user authentication feature

Added a new user authentication system using OAuth2 for better security and user management.

Implemented login and registration endpoints
Integrated OAuth2 for social login
Closes #123


Following a consistent commit message convention helps in maintaining a clean and understandable Git history. It's important to keep the messages clear, concise, and meaningful. Also, adhere to your team's or project's specific guidelines if they differ from this general convention.