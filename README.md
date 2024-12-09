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
