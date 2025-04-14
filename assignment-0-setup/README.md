# Assignment 0: Course Setup

Welcome to **Python Programming – Spring 2025**!  
This short assignment will help you get your environment ready and ensure you're set up for success in the course.

---

## ✅ Objectives

- Set up access to Google Colab  
- Create and link a GitHub repository  
- Run your first notebook  
- Understand the basic tools used in this course  

---

## 🧰 Instructions

### 1. Sign in to Google Colab
- Visit [Google Colab](https://colab.research.google.com/)
- Sign in with your Google account

**Set up your computing environment:**  
We are going to use **Google Colab** for this class. It provides free access to a GPU, which we may use in later assignments.  
In your **Google Drive**, create a folder for this class. You will be saving the Colab notebooks you run in this folder.

- Open a new notebook and try running this simple cell:

    ```python
    print("Hello, Python 2025!")
    ```

---

### 2. Create a GitHub Account (if you don’t already have one)
- Go to [https://github.com/](https://github.com/) and create an account using your preferred email  
- **Set up a GitHub account. All assignments for this course will be distributed through GitHub Classroom.**  
- You will receive Slack links that generate a private assignment repository for you  
- You must accept each assignment before starting work on it

> **Note**: If you choose to use `ssh` with Git, you'll need to follow [these instructions to generate an SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)  
> Then follow [these instructions to add your public key to GitHub](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

---

### 3. Open the Assignment Link from the Slack Channel
- Locate the **GitHub Classroom assignment link** posted in Slack  
- Follow the link to create your own copy of the assignment repository  
- Make sure your GitHub account is linked correctly to the classroom

---

### 4. Run `Python_Programming_Assignment_0.ipynb` in Google Colab
- Open the notebook in Colab by double-clicking it from your Google Drive folder  
- If needed, copy the notebook to your class folder in Drive  
- Run all cells in the notebook — no coding required  
- This notebook runs a few checks and introduces tools we’ll use this term  
- When finished:
  - Go to **File → Download → Download `.ipynb`**
  - Replace the notebook in your **local cloned GitHub repository**

---

### 5. Create a `setup.txt` File
- In the root of your local repository, add a file named `setup.txt` with the following content:

    ```
    Name: [Your Full Name]
    GitHub Username: [Your GitHub Username]
    Colab Tested: Yes
    ```

---

### 6. Answer the Markdown Questions
- In the `Python_Programming_Assignment_0.ipynb` notebook, fill in your answers in the provided Markdown cells

---

### 7. Push Your Changes to GitHub
From the **root of your local assignment repository**, run the following commands:

```bash
git add .
git commit -m "Completed Assignment 0"
git push
```

> ✅ **For all assignments in this course**, it’s your responsibility to ensure your submission is pushed to your GitHub Classroom repository.

### 💡 Optional: Use GitHub Web Interface Instead
If you prefer not to use Git:

- Go to your repository on [GitHub](https://github.com/)
- Delete the original `Python_Programming_Assignment_0.ipynb` file  
- Upload your updated file using **Add file → Upload files**  
- Click **Commit changes** to finalize

---

## 📬 Submission

No separate submission is required. Your instructor will review your GitHub Classroom repository.

---

## 💯 Grading (5%)

Each student who correctly submits their work will receive **5 points**.

| Task                                   | Points |
|----------------------------------------|--------|
| Colab notebook runs                    | 1      |
| GitHub repo created via assignment link | 1      |
| `setup.txt` file completed             | 1      |
| Markdown questions answered            | 1      |
| Pushed to GitHub successfully          | 1      |

---

## ⏭️ Next

Continue on to **Assignment 1** once it’s released.  
*(Unlike Assignment 0, Assignment 1 isn’t just a setup exercise. Don’t wait too long to get started!)*

---

## 🆘 Need Help?

- Post in the class Slack `#help` channel  
- Ask during class or office hours  
- Refer to [GitHub Docs](https://docs.github.com/en)  
- Review the [Colab FAQ](https://research.google.com/colaboratory/faq.html)  

---

Happy setup! 🎉
