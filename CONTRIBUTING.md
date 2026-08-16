# Contributing

This project uses a **trunk-based branching strategy**. Everyone works from the `main` branch, creates a short-lived branch for their work, and opens a Pull Request (PR) when their work is ready.

## 1. Before You Start

Make sure your local repository is up to date:

```bash
git switch main
git pull
```

Always start new work from the latest `main`.

## 2. Create a Branch

Create a new branch for the task you're working on:

```bash
git switch -c YOUR-BRANCH-NAME
```

Use a short, descriptive name that explains what you're working on. For example:

```bash
git switch -c fix-network-bug
```

Avoid working directly on `main`.

## 3. Make Your Changes

Make the changes needed for your task.

Check what you've changed with:

```bash
git status
git diff
```

When you're happy with your changes, stage and commit them:

```bash
git add .
git commit -m "Describe what you changed"
```

Keep commits focused on one logical change.

## 4. Push Your Branch

The first time you push a new branch, use:

```bash
git push -u origin YOUR-BRANCH-NAME
```

After that, you can simply use:

```bash
git push
```

Your branch will now be available on GitHub.

## 5. Create a Pull Request

Go to your repository on GitHub. You should see an option to create a Pull Request for your recently pushed branch.

When creating the PR:

1. Make sure the **base branch** is `main`.
2. Make sure the **compare branch** is your feature branch.
3. Give the PR a clear title describing your changes.
4. Briefly explain what you changed.
5. Create the Pull Request.

Do **not** merge your own Pull Request immediately. Have another group member review it first.

## 6. Review and Merge

A group member should review the Pull Request.

If changes are requested:

1. Make the requested changes on your existing branch.
2. Commit them.
3. Push the branch again.

The Pull Request will automatically update.

Once the group is happy with the changes, merge the Pull Request into `main`.

## 7. Clean Up

After your Pull Request has been merged, switch back to `main` and update it:

```bash
git switch main
git pull
```

You can then delete your old local branch:

```bash
git branch -d YOUR-BRANCH-NAME
```

## The Workflow

For each task, follow this cycle:

```text
main
  │
  ├── create branch
  │
  ▼
your-branch
  │
  ├── make changes
  ├── commit
  ├── push
  │
  ▼
Pull Request
  │
  ├── review
  ├── fix if necessary
  │
  ▼
main
```

### Rules to Remember

- **Never commit directly to `main`.**
- Keep branches **short-lived** and focused on one task.
- Pull from `main` before starting new work.
- Open a Pull Request when your work is ready.
- Have another group member review your Pull Request.
- Delete branches after they have been merged.
