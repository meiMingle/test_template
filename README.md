This is an example repository to help reproduce a recent bug in GitHub Actions.

Bug report: https://github.com/actions/runner/issues/2550

When one creates a new project based on a template repository that contains a workflow that listens for the `push` event, the workflow runs twice.

Go ahead and try it out — hit the "Use this template" button and create a new repository based on this template.
Then navigate to the Actions tab, and you'll see that the workflow runs twice. 🤷

<img width="1325" alt="image" src="https://user-images.githubusercontent.com/108333/232506137-a338c305-c87a-4db5-8ce6-087f3779f007.png">
