# Contributing to svg-icon.js

A big welcome and thank you for considering contributing to svg-icon.js!

## Get Started

1. Fork the repository to your own Github account.
2. Now, let's clone this repository.
    
    ```
    git clone https://github.com/rnbwdev/svg-icon.js.git
    ```
    
3. Create a branch locally with a succinct but descriptive name
4. Commit changes to the branch
5. Following any formatting and testing guidelines specific to this repo
6. Push changes to your fork.

## Bundle and Minify `svg-icon.js`

Go to `svg-icon.js` directory by running:

```
cd svg-icon.js
```

And then run:

```
npm run svg-icon.min
```

You’ll find the generated file at `/dist/svg-icon.js.min`

> The bundled file store the CSS in the same order in which you import inside the /src/index.css file.
> 

## Publish a new package

Considering you already have a NPM account, with NPM and Node.js installed on your local machine.

1. Open a terminal to login to your NPM account and fill out your username, email and password as requested.
    
    ```
    npm login
    ```
    
    > You might also be asked for a `one-time-password` if there is 2FA applied on your account.
    > 
2. We use `np` to simplify the process of publishing.
Install the `np` package globally by entering the command below. (Skip this step if np is already installed)
    
    ```
    npm install --global np
    ```
    
3. Ensure there is nothing left to commit and commit any work that is pending.
Then run the below command.
    
    ```
    np
    ```
    
    `np` will now ask you to select [SemVer](https://semver.org/) number as part of the versioning process. Select the appropriate update type.
    
    Next `np` will ask to verify your selection. Hit `Y` to continue.
    
4. Once publishing is completed, `np` will prompt a browser window for adding the release notes to GitHub. Fill in the details.

That’s all! Your package is published!

## Code of Conduct

We take our open source community seriously and hold ourselves and other contributors to high standards of communication. By participating and contributing to this project, you agree to uphold our [Code of Conduct](https://github.com/relateapp/rene.css/blob/main/CODE_OF_CONDUCT.md).

## Getting Help

The svg-icon.js community can be found on [GitHub Discussions](https://github.com/rnbwdev/svg-icon/discussions), where you can ask questions, voice ideas, and share your projects.

Contributions are always welcome and can be a quick way to get your fix or improvement slated for the next release. In general, PRs should:

- Address a single concern in the least number of changed lines as possible.
- Include documentation in the repo or on our docs site.
- Be accompanied by a complete Pull Request template (loaded automatically when a PR is created).

> For changes that address core functionality or would require breaking changes (e.g. a major release), it's best to open an Issue to discuss your proposal first. This is not required but can save time creating and reviewing changes.
> 

> Search for existing Issues and PRs before creating your own
> 

> If you find an Issue that addresses the problem you're having, please add your own reproduction information to the existing issue rather than creating a new one. Adding a reaction can also help be indicating to our maintainers that a particular problem is affecting more than just the reporter.
>