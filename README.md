# Collaborative Git Workflow

## Morgan's Work: Adding Book Reviews Section

### 1. Create and Switch to New Branch
```bash
git checkout main
git pull origin main         
git checkout -b add-book-reviews
```
![new branch](images/3adding-review-branch.png)

### 2. Stage and Commit changes
```bash
git add book_reviews.html
git commit -m "Add book reviews section"
git push origin add-book-reviews
```
![new branch](images/4staging-and-commiting.png)

### 3. Creating Pull Request for Morgan's Work
#### Steps:
**Navigate to repository on GitHub**

**Click "Compare & pull request" for add-book-reviews**

**Add description: "Adding book reviews section"**

**Click "Create pull request"**
![pull request](images/5compare-and-pull-request.png)
![pull request](images/6pull-request.png)
![pull request](images/7successful-pull-request.png)

### 4. Merging to Main (After Approval)
```bash
git checkout main
git merge morgan-book-reviews
git push origin main
```
![merge branches](images/8merging-branches.png)
![merge branches](images/9push-update-to-main.png)