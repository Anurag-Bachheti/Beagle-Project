# Beagle Page

## Project Overview (100 Marks)

### Tasks
#### **1. HTML Setup:**
- Begin your HTML project.
- Ensure inclusion of `<head>` tags with:
  - A `<title>` tag.
  - A **favicon** link.
  - A **stylesheet** link.

#### **2. Design UI:**
- Follow the **Figma design** for layout, colors, and fonts.

#### **3. Create Sections:**
- **Top Section:**
  - Add a "Read More" link leading to **Wikipedia**.
- **Image Section:**
  - Embed a **Beagle image**.
- **Trivia Section:**
  - Create an **ordered list** with appropriate formatting.

#### **4. Anchor Tags:**
- Ensure "Read More" and "More Images" links are accurately linked.
- Link "More Images" to a **Google Images search**.

### Key Evaluation Points
✅ **Head Tags:** Validate the presence of `<head>` tags with all necessary components.
✅ **User Interface:** Confirm that the layout, colors, and fonts align with the **Figma design**.
✅ **Sections:** Verify the creation of three sections with assigned **class names**.
✅ **Anchor Tags:** Ensure the correct functioning of "Read More" and "More Images" links.
✅ **Images:** Include an **image of a Beagle dog**.
✅ **Ordered List:** Create a trivia section as an **ordered list** with proper formatting.
✅ **Repo and Hosting:** Establish a **GitHub repository** and deploy the project.

### Code Explanation
#### **1. Favicon Fix**
```html
<link rel="icon" type="image/png" href="/favicon.png">
```
🔹 Removed incorrect `stylesheet="index.css"` attribute.

#### **2. Beagle Blog Section**
```html
<div class="blog-section">
    <h1><u>The Beagle Blog</u></h1>
    <p>The <b>Beagle</b> is a breed of small scent hound...</p>
    <a href="https://en.wikipedia.org/wiki/Beagle" target="_blank" rel="noopener noreferrer">Read More</a>
</div>
```
✅ Added **class name** for styling.
✅ Secured the external link