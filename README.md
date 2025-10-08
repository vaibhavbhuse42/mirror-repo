# Mirror Repository Project

## 📌 Project Overview

This project explains how to create and configure a Mirror Repository in GitHub.
I have documented all the steps I followed, along with screenshots for clarity.

## 🛠 Steps Followed
### 1. Create Repository on GitHub

First, I created a new repository in my GitHub account.

Then I went into the Repository Settings.

In settings, I enabled the Mirror Repository option.

After that, I copied the HTTPS URL of my repository.

![](/img/Screenshot%202025-10-08%20225617.png)

![](/img/Screenshot%202025-10-08%20230002.png)


### 2. Generate Personal Access Token

I generated a Personal Access Token (PAT) from GitHub.

This token is used for authentication instead of password.

While pushing my code, I entered GitHub username and this token.

![](/img/Screenshot%202025-10-08%20230639.png)

### 3. Clone the Repository with Mirror

Then I cloned my repository using the mirror option.

This allows me to create a local copy which syncs with GitHub mirror repo.

![](/img/Screenshot%202025-10-08%20232740.png)

![](/img/Screenshot%202025-10-09%20000040.png)

### 4. Create Project File

After cloning, I created a file called index.html.

This was just for testing whether the mirror setup works correctly.

![](/img/Screenshot%202025-10-08%20235106.png)

![](/img/Screenshot%202025-10-08%20235628.png)


### 5. Commit and Push Changes

Next, I committed my changes.

Then I pushed the file into my GitHub mirror repository.

Successfully, the file appeared on my repository.

![](/img/Screenshot%202025-10-08%20230925.png)

![](/img/Screenshot%202025-10-08%20230106.png)

## 🚀 Final Output

The repository is now mirrored properly.

Any new file or changes I make locally can be pushed directly to the mirror repository.

![](/img/Screenshot%202025-10-08%20234735.png)

## 🔑 Key Learnings

How to create and configure a Mirror Repository in GitHub.

How to generate and use Personal Access Token (PAT).

How to clone, add, commit, and push changes to the mirror repository.

Verified that mirror repository works successfully with project files.