# Getting started with our Technical Team

To get started, you'll need to clone our GitHub repository onto your local machine. You can do this by running the following command in your terminal:

```
git clone https://github.com/Simapsee/prototype_.git
```

Once you've cloned the repository, you can navigate to the project directory and start working on the code. Before you begin, be sure to read through our CONTRIBUTING.md file to familiarize yourself with our coding standards and guidelines.

## Branching strategy

We use a branching strategy that allows for collaboration and easy merging of code. Here are the main branches you'll be working with:

- `main`: This branch contains the latest stable version of the code. It should only be updated through pull requests.

- `dev`: This branch contains the latest development version of the code. You'll be creating your own feature branches off of this branch.

- `feature`: These branches are created by you for specific feature work. They are based on the `dev` branch and should be merged back into `dev` when your work is complete.

To create a new feature branch, run the following command:

```
git checkout -b feature/your-feature-branch-name dev
```


## Pull requests

Once you've completed your feature work, it's time to create a pull request (PR) to merge your changes into the `dev` branch. Here's how to create a pull request:

1. Push your feature branch to the remote repository:

```
git push -u origin feature/your-feature-branch-name
```

2. Navigate to our GitHub repository in your browser and click on the "New pull request" button.

3. Select your feature branch as the "compare" branch and the `dev` branch as the "base" branch.

4. Fill out the PR template with a brief description of your changes and any relevant details.

5. Click on "Create pull request" and wait for your changes to be reviewed and merged.

## Code reviews

All changes to our codebase must be reviewed by at least one other team member before they can be merged into the main codebase. To request a code review, simply create a pull request and tag the appropriate team members.
# Getting started with our Technical Team

To get started, you'll need to clone our GitHub repository onto your local machine. You can do this by running the following command in your terminal:

```
git clone https://github.com/Simapsee/prototype_.git
```

Once you've cloned the repository, you can navigate to the project directory and start working on the code. Before you begin, be sure to read through our CONTRIBUTING.md file to familiarize yourself with our coding standards and guidelines.

## Branching strategy

We use a branching strategy that allows for collaboration and easy merging of code. Here are the main branches you'll be working with:

- `main`: This branch contains the latest stable version of the code. It should only be updated through pull requests.

- `dev`: This branch contains the latest development version of the code. You'll be creating your own feature branches off of this branch.

- `feature`: These branches are created by you for specific feature work. They are based on the `dev` branch and should be merged back into `dev` when your work is complete.

To create a new feature branch, run the following command:

```
git checkout -b feature/your-feature-branch-name dev
```


## Pull requests

Once you've completed your feature work, it's time to create a pull request (PR) to merge your changes into the `dev` branch. Here's how to create a pull request:

1. Push your feature branch to the remote repository:

```
git push -u origin feature/your-feature-branch-name
```

2. Navigate to our GitHub repository in your browser and click on the "New pull request" button.

3. Select your feature branch as the "compare" branch and the `dev` branch as the "base" branch.

4. Fill out the PR template with a brief description of your changes and any relevant details.

5. Click on "Create pull request" and wait for your changes to be reviewed and merged.

## Code reviews

All changes to our codebase must be reviewed by at least one other team member before they can be merged into the main codebase. To request a code review, simply create a pull request and tag the appropriate team members.
