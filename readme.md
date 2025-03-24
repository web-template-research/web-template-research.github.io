# Webpage Template for Research Projects

This repository provides a straightforward template for creating an informative webpage to clearly and effectively showcase your research projects. It is designed to present paper details, highlights, experimental results, and supplementary materials.

You can view the template webpage here: [https://web-template-research.github.io/](https://web-template-research.github.io/)

This template was adapted from my project webpage https://clic-webpage.github.io/ ([GitHub Repository](https://github.com/clic-webpage/clic-webpage.github.io)). Additional examples include:
- [Implicit Behavior Cloning](https://implicitbc.github.io/) ([GitHub Repository](https://github.com/implicitbc/implicitbc.github.io))
- [Diffusion Policy](https://diffusion-policy.cs.columbia.edu/)



## Steps to Create Your Webpage Using GitHub Pages

### Step 1: Create a GitHub Pages Site

1. Follow the official GitHub instructions [here](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) to create a new repository named `<your-github-username>.github.io`.

   - Alternatively, you may host the webpage as a subpage on your existing personal website (guidelines will be added soon).

### Step 2: Upload the Webpage Template

1. Clone your newly created repository:
   ```bash
   git clone https://github.com/<your-github-username>/<your-github-username>.github.io.git
   ```

2. Copy all the provided template files (`index.html`, `style.css`, and the `images` folder with images and videos) into your cloned repository.

3. Commit and push the files:
   ```bash
   git add .
   git commit -m "Add webpage template files"
   git push origin main
   ```

Your webpage should now be live at:
```
https://<your-github-username>.github.io
```

**Troubleshooting:**  
If your page does not appear or there's nothing under the 'Actions' tab of your repository, ensure you have configured a publishing source for your GitHub Pages site as described [here](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

### Step 3: Customize the Webpage Content

Open `index.html` and follow the clearly marked comments to:
- Update the paper title, abstract, and author information.
- Upload your own images and videos into the `images` folder and update the paths accordingly in the HTML.
- Customize captions and descriptions for highlights and experimental results.
- Modify the layout or style by editing `style.css`.

After editing, commit and push your changes to GitHub:
```bash
git add .
git commit -m "Update webpage content"
git push origin main
```

Your webpage will update automatically upon pushing your changes.

## Folder Structure

```
.
├── index.html             # Main webpage file
├── style.css              # Stylesheet for the webpage
└── images                 # Folder containing your images and videos
    ├── your-image.jpg
    └── your-video.mp4
```

