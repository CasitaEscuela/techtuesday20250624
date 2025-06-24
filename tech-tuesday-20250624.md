---
marp: true
---

# Happy :joy: Version Control for your Power BI Dashboards :bar_chart:



#### made with :heart: by Adriel E. González Martínez for eIQS Puerto Rico

---

# The problem

1. Power BI files (**.pbix**) are binary, meaning we can not track changes at the content level like we do it for text-based files (e.g., .sql, .json, .txt). 
2. You can't easily view diffs between different versions of **.pbix** files.

---

# The (or at least a possible) Solution

1. Close your eyes :persevere: and hope for the best
2. Or, Save their work in **.PBIP** file format, which breaks down into <abbr title="JavaScript Object Notation">**JSON**</abbr> components. This format makes the files editable in tools like VS Code. 

---

# STEP #1: Let's set up your Environment

## What tools you will need? 

1. <a href="https://optum.service-now.com/euts_intake?id=euts_appstore_app_details&appKeyId=42944" target="_top" title="Click here to install POWER BI DESKTOP (64-bit version) code The UHG way...">Power BI Desktop</a>
2. <a href="https://optum.service-now.com/euts_intake?id=euts_appstore_app_details&appKeyId=43001" target="_top" title="Click here to install VISUAL STUDIO CODE The UHG way...">Visual Studio Code</a> 
3. <a href="https://optum.service-now.com/euts_intake?id=euts_appstore_app_details&appKeyId=42218" target="_top" title="Click here to install GIT The UHG way...">Git</a>
4. <a href="https//:github.com" target="_top" title="Create a GITHUB account or log in to yours">Github Account</a>


---

## How to install Git (The UHG way...)
<video src="https://casitaescuela.github.io/media/install-git-the-optum-way.mp4" width=auto height=auto controls></video>

---

## IF Git truly installed? 

```shell
C:\Users\agonz615>where git
```
<figure>
    <img src="https://casitaescuela.github.io/media/where-is-git.png"   width="800" height="auto" alt="Capture of windows command prompt. It    shows the command to locate the path to a given file.">
    <figcaption>
        A (Windows) command prompt showing the command to locate the path to a given file.
    </figcaption>
</figure>

---

## But, What version am I running?  

```shell
C:\Users\agonz615>git --version
```
<figure>
    <img src="https://casitaescuela.github.io/media/version-of-git.png"   width="800" height="auto" alt="A (Windows) command prompt showing the git command with the version parameters.">
    <figcaption>
        A (Windows) command prompt showing the git command with the version parameters.
    </figcaption>
</figure>

---

# STEP #2: Create a (REPO)sitory

<figure>
    <img src="https://casitaescuela.github.io/media/github-create-repo.png"   width="1024" height="auto" alt="A capture of the create repository section inside a Github account.">
    <figcaption>
        A capture of the create repository section inside a Github account.
    </figcaption>
</figure>

---

# STEP #3: Create Branches inside your REPO

<figure>
    <img src="https://casitaescuela.github.io/media/github-branches.png"   width="1024" height="auto" alt="A capture of the Branches section inside a Github repository.">
    <figcaption>
        A capture of the Branches section inside a Github repository.
    </figcaption>
</figure>

---

## STEP #4: Clone a Git REPO from Github (The CLI way...)

```shell
C:\Users\agonz615>
git clone https://github.com/your-github-username/your-repo-name.git
```
<figure>
    <img src="https://casitaescuela.github.io/media/git-clone.png"   width="1024" height="auto" alt="A (Windows) command prompt showing the git clone command.">
    <figcaption>
        A (Windows) command prompt showing the git clone command.
    </figcaption>
</figure>

---

## STEP #4: Clone a Git REPO from Github (The VSCode way...)

<video src="https://casitaescuela.github.io/media/clone-repo-from-vscode.mp4" width="1024" height=auto controls></video>


---

## STEP #5: Change your branch A.K.A checkout (The VSCode way...)

<video src="https://casitaescuela.github.io/media/checkout-from-vscode.mp4" width="1024" height=auto controls></video>


---

# LET'S DO THIS :muscle:

Now make changes and keep saving using the **.pbix** file format.
