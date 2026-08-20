# 👋 Our Dev Wall

A class project where every student adds their own profile card to a shared wall.

This website is built by the students. Every card you see was added by a classmate as their very first pull request on GitHub.

---

## What is this?

This is a simple website that shows a wall of student profiles. Each student adds their own card by editing a JSON file and opening a Pull Request.

**Your task:** Add your own card to the wall. That's it.

---

## How to add your card

### Step 1: Fork this repository

1. Click the **Fork** button at the top-right of this page.
2. This creates your own copy of the project under your GitHub account.
3. Wait for it to finish. You'll be redirected to your copy.

### Step 2: Find or create your folder

1. In your forked repository, go to the **`students/`** folder.
2. Look for a folder with **your GitHub username** (for example, `rahul_dev/`).
3. If your folder doesn't exist, create it:
   - Click **"Add file" → "Create new file"**
   - Name it: `students/your-github-username/profile.json`
   - For example: `students/janedoe/profile.json`

### Step 3: Edit your profile.json

Open your `profile.json` file and paste this template. Change the values to match your details:

```json
{
  "name": "Your Name",
  "github": "your-github-username",
  "about": "A short sentence about yourself.",
  "favoriteTech": "JavaScript",
  "image": ""
}
```

**What each field means:**

| Field | What to write | Example |
|-------|--------------|---------|
| `name` | Your full name | `"Rahul Kumar"` |
| `github` | Your GitHub username (exactly as it appears) | `"rahul_dev"` |
| `about` | One sentence about yourself | `"Trying web development for the first time."` |
| `favoriteTech` | Something you're learning or already know | `"JavaScript"` |
| `image` | Path to your photo (leave empty for initials) | `"./photo.jpg"` |

**About field examples** — keep it casual:
- "I like making weird websites."
- "Trying JavaScript for the first time."
- "I have no idea what I'm doing yet."
- "Here to build something cool."

### Step 4: Add a photo (optional)

1. Take a photo of yourself (or use any picture).
2. Name it `photo.jpg`.
3. Put it in the same folder as your `profile.json`.
4. In your `profile.json`, set `"image": "./photo.jpg"`.
5. Keep the image small — under 500KB is ideal.

### Step 5: Commit your changes

1. Go back to your repository.
2. Click **"Commit changes"**.
3. Write a message like: `Add my profile`
4. Click **"Commit changes"** again.

### Step 6: Open a Pull Request

1. Go to the original repository (not your fork).
2. You should see a yellow banner: **"Compare & pull request"**. Click it.
   - If you don't see it, go to **Pull requests → New pull request**.
3. Add a title like: `Add Rahul's profile`
4. Click **"Create pull request"**.

### Step 7: Done! 🎉

Your teacher will review and merge your Pull Request. Once merged, your card will appear on the Dev Wall.

---

## What happens after my PR is merged?

Your profile card will appear on the website automatically. The website reads the `students/` folder and renders every profile it finds.

---

## FAQ

**Q: What if I made a mistake?**
Edit your `profile.json` file and push another commit. The Pull Request will update automatically.

**Q: What if my folder already exists?**
Just open the existing `profile.json` file and edit it. Don't create a new folder.

**Q: What if two students have the same name?**
That's why we use GitHub usernames as folder names. `rahul_dev` and `rahulk23` are different folders.

**Q: What if my Pull Request has conflicts?**
Your teacher will help you resolve them. Don't worry about it.

**Q: Can I see the website before my PR is merged?**
Open `index.html` in your browser to preview locally. Or just wait for your teacher to merge it!

---

## Project structure

```
├── index.html          ← The main web page
├── css/style.css       ← The styles
├── js/config.js        ← Repository settings (teacher edits this)
├── js/app.js           ← Loads and displays student profiles
├── students/           ← Student folders go here
│   ├── rahul_dev/
│   │   ├── profile.json
│   │   └── photo.jpg
│   └── janedoe/
│       └── profile.json
├── README.md           ← You're reading this
└── LICENSE
```

---

## Quick reference

| What you want to do | Where |
|---------------------|-------|
| Add your profile | `students/your-username/profile.json` |
| Add your photo | `students/your-username/photo.jpg` |
| Change your bio | Edit the `about` field in your `profile.json` |
| Change your tech | Edit the `favoriteTech` field |
| Fix a typo | Edit your `profile.json` and commit |

---

Built with ❤️ by the class. Happy coding!
