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
![new branch](images/4staging-and-commiting.png)