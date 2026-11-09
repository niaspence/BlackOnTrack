# BlackOnTrack x Black Girls Code

## Step 0: Copy and paste the link
https://onecompiler.com/html

## Step 0.5: Copy the file from index.html and styles.css into their respective files in the link

## Step 1: Tell us who you are
 
Open `index.html`. Near the top, change the words inside the quote marks:
 
```html
<meta name="author" content="Your Name">
<meta name="field" content="Computer Science">
```
 
- Keep the quote marks.
## Step 2: Name your page
 
Scroll down a little and change the page title and the sentence below it:
 
```html
<h1>Website Page Name</h1>
<p class="about">Write one sentence about the website you're building.</p>
```
 
Ask yourself: what is this page for, and who will use it? For example, "First-Gen Engineering Advice" and one sentence about who it helps.
 
## Step 3: Add your advice
 
Your page has four sections:
 
1. **Group Commonality** (change this heading to the thing your group shares, and use the section for advice about it)
2. **Clubs we recommend**
3. **Campus resources worth knowing**
4. **Internships and how to get them**
In each one, you'll see a card between a `START` line and an `END` line:
 
```html
<!-- START:clubs -->
<div class="card">
  <h3>Title goes here</h3>
  <p>Your tip or story goes here.</p>
  <a href="https://link-goes-here.com">Link text</a>
</div>
<!-- END:clubs -->
```
 
1. Change the words in the example cards, or delete them.
2. To add another card, copy everything from `<div class="card">` to `</div>` and paste it right below, **before** the `END` line.
3. Skip any section you have nothing for. Empty is fine.
**Your group has been given topics to split up. Write about the ones you picked so we don't get five copies of the same card.**
 
## Step 4 (fun): Make it yours
 
Open `styles.css`. At the top you'll see a block called **MY STYLE**. Change the value after any colon, save, and watch your page change:
 
```css
--accent: #1d5c63;      /* try #c0392b, #6a1b9a, #2e7d32 */
--font: "Trebuchet MS", sans-serif;   /* try Georgia, serif */
--corner: 6px;          /* try 0px or 20px */
```
 
Your colors and fonts only show up on **your** page. The combined site uses one shared look, so go wild.
 
## Quick tricks
 
| I want to... | Type this |
|---|---|
| Add a link | `<a href="https://site.com">Click here</a>` |
| Make text **bold** | `<strong>words</strong>` |
| Make text italic | `<em>words</em>` |
| Add a bullet list | `<ul><li>First</li><li>Second</li></ul>` |
 
## Golden rules
 
1. Only change the words between `>` and `<`, or the values after a `:` in the CSS.
2. Every `<something>` needs a matching `</something>`.
3. Don't delete the `START` and `END` lines. They're how your cards get collected.
4. Don't rename `styles.css`. Your page finds it by name.
5. Stuck? Undo your last change (Ctrl+Z), or wave over a helper.
## When you're done
 
1. Read your page out loud to your group and check that every link works.
2. Tell your group leader you're finished.
3. Your page will be combined with everyone else's into one big resource hub for the whole community.
Thank you! The advice you wrote today is going to help people who come after you.
