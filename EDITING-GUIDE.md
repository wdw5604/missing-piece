# ✏️ Missing Piece Website — Editing Guide

**No coding experience needed!** You can edit the website directly in your browser using GitHub.

---

## 🔗 Quick Link

Go to: **https://github.com/wdw5604/missing-piece**

---

## How to Edit (Step by Step)

### 1. Open the file you want to edit
- Click on **`index.html`** in the GitHub repo
- Click the **pencil icon** ✏️ (top right of the file) to start editing

### 2. Make your changes
- Use **Ctrl+F** (or Cmd+F on Mac) to search for the text you want to change
- Edit the text directly — see the examples below

### 3. Save your changes
- Scroll to the bottom
- Click the green **"Commit changes"** button
- The website will **automatically update** in about 10 seconds!

---

## 📝 Common Edits

### Change a Blog Post Title
Search for the current title and replace it:
```
<h3><a href="#">The Playoff Picture Is Getting Clearer — Here's What to Watch</a></h3>
```
Just change the text between `>` and `</a>` :
```
<h3><a href="#">Your New Title Here</a></h3>
```

### Change a Blog Post Description
Search for the description text and replace it:
```
<p>With Week 7 in the books, the contenders and pretenders...</p>
```
Just change the text between `<p>` and `</p>`.

### Change the Date on a Post
Search for the date and replace it:
```
<span class="blog-card-date">October 20, 2026</span>
```

### Change the Sport Tag (NFL, NBA, MLB, etc.)
```
<span class="blog-card-tag">NFL</span>
```
Just replace `NFL` with whatever sport you want.

---

## 🎥 Add a YouTube Video

1. Go to your YouTube video
2. Click **Share** → **Embed** → Copy the URL (looks like `https://www.youtube.com/embed/XXXXXXXXXXX`)
3. In `index.html`, find a video block and replace the `src` URL:

```html
<iframe
  src="https://www.youtube.com/embed/YOUR_VIDEO_ID_HERE"
  title="Your Video Title"
  ...
```

Just change `YOUR_VIDEO_ID_HERE` to your actual video ID.

---

## 🎙️ Change a Podcast Episode

Search for the episode you want to edit. Each episode looks like this:

```html
<div class="podcast-episode-number">EP 12</div>
```
Change the episode number.

```html
<h4>Playoff Chaos, MVP Races & the Trades Nobody Saw Coming</h4>
```
Change the episode title.

```html
<p>We dive into a wild week across the NFL...</p>
```
Change the episode description.

---

## ➕ Add Brand New Content

### Add a New Blog Post
1. Open `index.html` and search for `HOW TO ADD A NEW BLOG POST`
2. You'll see a ready-to-use template in the comments
3. Copy everything between `<!--` and `-->`, paste it ABOVE that comment
4. Remove the `<!--` and `-->` around your pasted block
5. Fill in your title, date, description, etc.

### Add a New YouTube Video
1. Search for `HOW TO ADD A NEW YOUTUBE VIDEO`
2. Same process — copy the template, paste above, fill in your details

### Add a New Podcast Episode
1. Search for `HOW TO ADD A NEW PODCAST EPISODE`
2. Same process — copy the template, paste above, fill in your details

---

## 🎨 Change Colors or Styles

Open **`css/style.css`** and search for these values at the top:

| What | Variable | Current Color |
|------|----------|---------------|
| Dark navy background | `--navy-dark` | `#1a2a40` |
| Main navy | `--navy` | `#2a3f5f` |
| Gold accent | `--gold` | `#c8a96e` |
| Cream/off-white text | `--cream` | `#f5f0e8` |
| Page background | `--off-white` | `#faf8f4` |

---

## 🖼️ Replace an Image

1. Go to the **`assets/images/`** folder on GitHub
2. Click **"Add file"** → **"Upload files"**
3. Upload your new image
4. In `index.html`, update the image filename to match:
```html
<img src="assets/images/your-new-image.jpg" alt="Description">
```

---

## ⚠️ Tips

- **Don't delete** anything between `< >` angle brackets — just change the text between them
- If something breaks, click the **"History"** button on GitHub to see previous versions and restore them
- Changes go live automatically in ~10 seconds after you commit
- When in doubt, just tell Andrew what you want changed and he'll do it! 😄
