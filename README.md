# Git Version Control Assignment

## Objective

<p>In this assignment, you'll learn how to pull changes from an online repository, make edits, and push those changes back to the repository. This is crucial for understanding how to collaborate on coding projects using version control.</p>

### Prerequisites:

- Git installed on your computer
- Access to the online repository (GitHub, GitLab, or any other Git hosting service)
- A code editor (e.g., VSCode)

---

## Instructions

### 1. Clone the repository (if not already done)

<p>If you haven’t cloned the repository yet, use the following command:</p>

```bash
 git clone <repository-url>
```

### 2. Navigate to the project directory

<p>Move into the directory of the cloned repository:</p>

```bash
cd <repository-directory>

```

### 3. Pull the latest changes

<p>Before making any changes, ensure your local repository is up to date with the remote repository:</p>

```bash
git pull origin Assignment-one

```

_(Note: Replace main with master if that’s the default branch of the repo.)_

### 4. Make your changes

#### 1. Creating your HTML boilerplate

<ol>
<li>Create a file name it index.html at root of the project</li>
<li>Add HTML skeleton to this file</li>
<li>Inside the body of the HTML create a heading of order 1 with your name</li>
</ol>

### 5. Add your changes to the staging area

<p>After making changes, add them to the staging area:</p>

```bash
git add <path/to/file/to/add/to/add/to/staging>
```

_To add all modified files, you can use (Not recommended)_

```bash
git add .

```

### 6. Commit your changes

<p>Once your changes are staged, commit them with a message describing what you did:</p>

```bash
git commit -m "Brief description of the changes"

```

### 7. Push your changes to the remote repository

<p>Finally, push your committed changes to the online repository:</p>

```bash
git push origin Assignment-one
```

**Notes:**

- Always pull changes before starting work to avoid conflicts.
- Make sure your commit messages are descriptive but concise.
- If you encounter any conflicts while pulling or pushing changes, review the conflict and resolve it manually.

**Task:**

- Modify the `index.html` file in the repository by adding your name inside the `<body>` tag.
- Follow the steps above to push your changes to the remote repository.

```bash

This will help your student get a feel for Git version control!

```
