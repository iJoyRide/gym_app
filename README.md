![image](https://github.com/user-attachments/assets/ff7eb7d7-08b7-4d34-b93a-f27bcb35fee8)


# Setup Instructions

### Step 1: Activate the Virtual Environment
To activate the `uv` virtual environment, use the following command:

For **Windows**:
```bash
.\.venv\Scripts\activate
```

For **macOS/Linux**:
```bash
source .venv/bin/activate
```

### Step 2: Build Docker Image
To build the required Docker image, including dependencies such as `uv`, run the following command:

```bash
docker compose build
```

### Step 3: Run the Docker Image
To run the image, use the following command:

```bash
docker compose up 
```
### Step 4: Go to FastAPI postman

```bash
http://localhost:8000/docs   
```

# Git best practices

### Step 1: Creating a new branch
```bash
git checkout -b SCRUM-7
```

### Step 2: Staging changes
```bash
git add .
```

### Step 3: Pushing changes to branch
```bash
git commit -m "(Feat): Added upload and saving feature"
```

### Step 4: Pushing to new branch 
```bash
git push -u origin SCRUM-7
```

### Step 5: Delete local branch
```bash
git branch -d SCRUM-7
```

### The commit type can include the following:

    feat – a new feature is introduced with the changes
    fix – a bug fix has occurred
    chore – changes that do not relate to a fix or feature and don't modify src or test files (for example updating dependencies)
    refactor – refactored code that neither fixes a bug nor adds a feature
    docs – updates to documentation such as a the README or other markdown files
    style – changes that do not affect the meaning of the code, likely related to code formatting such as white-space, missing semi-colons, and so on.
    test – including new or correcting previous tests
    perf – performance improvements
    ci – continuous integration related
    build – changes that affect the build system or external dependencies
    revert – reverts a previous commit

