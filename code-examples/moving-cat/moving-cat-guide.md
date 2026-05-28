# Moving Cat HTML Guide 🐱

## Step 1: Install Live Server (IMPORTANT)

Before running the file, install the Live Server extension in VS Code.

### How to install:

1. Open VS Code
2. Press:

Cmd + Shift + X

3. In the search bar, type:

Live Server

4. Find:
Live Server (by Ritwick Dey)

5. Click Install

---

## Step 2: Open the File

In VS Code:

1. Open the project folder
2. Go to:

code-examples/moving-cat.html

---

## Step 3: Run the File

Right click the file and click:

Open with Live Server

OR click “Go Live” in the bottom-right corner.

This will open the page in your browser.

---

## What You Should See

A cat 🐈 moving across the screen.

---

## Step 4: Try Editing It

### Make the cat faster

Find:

position += 4 * direction;

Change to:

position += 8 * direction;

---

### Change the animal

Find:

<div id="cat">🐈</div>

Try:

<div id="cat">🐕</div>

---

### Change background colour

Find:

background: #f0f4f8;

Try:

background: lightblue;

---

## Step 5: Save Changes

Press:

Cmd + S

The browser updates automatically.

---

## Step 6: Push Your Changes to GitHub

In the terminal:

git status  
git add .  
git commit -m "Update moving cat example"  
git push  

---

## Goal of This Exercise

This is just a simple starting point to help you practise:

- using VS Code  
- editing code  
- seeing changes live in the browser  
- understanding basic JavaScript  
- using Git & GitHub  

Don’t worry about making it perfect — just experiment and have fun 🙂