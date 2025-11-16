# How to Complete This Assignment

This guide will walk you through forking the repository, editing the code, and submitting your work so it gets automatically graded.

## Prerequisites

Before you start, make sure you have:
- A GitHub account (free at [github.com](https://github.com))
- Python 3 installed on your computer ([python.org](https://www.python.org/downloads/))
- A code editor (VS Code, PyCharm, or any text editor)
- Git installed on your computer ([git-scm.com](https://git-scm.com/))

---

## Step 1: Fork the Repository

1. Go to the repository page on GitHub
2. Click the **Fork** button in the top right corner
3. This creates your own copy of the repository under your GitHub account
4. You'll be redirected to your forked repository

---

## Step 2: Clone Your Fork to Your Computer

1. On your forked repository page, click the green **Code** button
2. Copy the HTTPS URL (it should look like `https://github.com/YOUR-USERNAME/python-lesson-01-hello.git`)
3. Open your terminal/command prompt and navigate to where you want to save the project
4. Run the following command:
`git clone https://github.com/YOUR-USERNAME/python-lesson-01-hello.git`
5. Navigate into the project folder:
`cd python-lesson-01-hello`

---

## Step 3: Complete the Assignment

1. Open the `hello.py` file in your code editor
2. Read the comments carefully — they explain what you need to do
3. **Edit only the line(s) marked for editing**
4. **Do NOT modify any other code** (especially the bottom section marked "Do NOT modify")
5. Save your file

### Example:
- **Before:** `print("Goodbye, world!")`
- **After:** `print("Hello, world!")`

---

## Step 4: Test Your Code Locally (Optional but Recommended)

Before pushing, test your code on your computer:

1. Open your terminal in the project folder
2. Run your script:
`python hello.py`
3. Check that the output matches the expected result in the assignment instructions

---

## Step 5: Commit Your Changes

1. In your terminal, add your changes to Git:
`git add hello.py`
2. Commit your changes with a meaningful message:
`git commit -m "Complete Hello World assignment"`

---

## Step 6: Push Your Changes to GitHub

1. Push your committed changes to your forked repository:
`git push origin main`

2. Your changes are now on GitHub!

---

## Step 7: Automatic Grading

Once you push your code, GitHub Actions will automatically run the test file (`test_project.py`) to check your work.

### How to Check Your Grade:

1. Go to your forked repository on GitHub
2. Click the **Actions** tab at the top
3. You should see a workflow run with your commit message
4. Click on the run to see the results:
- ✅ **Green checkmark** = Your code passed the tests!
- ❌ **Red X** = Your code didn't pass — review the error message and try again

### If You Failed the Tests:

1. Read the error message carefully — it tells you what went wrong
2. Go back to step 3 and fix your code
3. Repeat steps 5 and 6 (commit and push)
4. Check the Actions tab again — a new run should start automatically

---

## Troubleshooting

### "Permission denied" or Git errors
- Make sure Git is installed on your computer
- Make sure you're in the correct project folder in your terminal

### Tests keep failing
- Re-read the assignment instructions in `README.md` and `hello.py`
- Check that your output matches **exactly** (including capitalization, spaces, punctuation)
- Make sure you only edited the line(s) you were supposed to edit

### Can't see the Actions tab
- Make sure you're on your forked repository, not the original
- The Actions tab appears on the repository page

### Still stuck?
- Review this guide step-by-step again
- Ask your instructor or study group for help
- Check the error message in the Actions tab — it often tells you exactly what's wrong

---

## Summary

1. **Fork** the repo
2. **Clone** it to your computer (optional)
3. **Edit** the code (only the marked lines)
4. **Test** locally (recommended - optional)
5. **Commit** your changes
6. **Push** to GitHub
7. **Check** the Actions tab for automatic grading

Good luck! 🚀
