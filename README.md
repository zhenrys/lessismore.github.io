# Henry Zhang | Academic Homepage

🌐 **Live Site:** [https://zhenrys.github.io](https://zhenrys.github.io)

Welcome to the source repository of my **academic homepage**, built with [Jekyll](https://jekyllrb.com/) and the [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) theme.  
It serves as my personal research profile — featuring my background, research interests, publications, projects, and personal highlights.

---

## ⚙️ Tech Stack for This Website

- **Framework:** Jekyll + AcadHomepage  
- **Languages:** HTML, Markdown, SCSS, Liquid  
- **Styling:** Custom Tailwind-inspired SCSS tweaks for typography and color scheme  
- **Deployment:** GitHub Pages  


---

## 🚀 A useful pipline example(for myself, you can design yours)
```bash
# do some changes to the about.md, then
cd ~/website/zhenrys.github.io

# local test
bundle exec jekyll serve
bundle exec jekyll serve --detach
# Visit: http://localhost:4000

# deploy to the site
git add .
git commit -m "commit change for xxx" # ⚠️remember to change
git pull origin main --rebase
git push origin main
```

💡 Tips:
* _pages/about.md is the main body of your homepage; edit this file for textual and layout changes.
* _config.yml controls the sidebar and metadata; modify it for title, social links, and navigation.
* images/ holds all visual resources.
* When github connection goes wrong, push via SSH adn ensure your SSH key is configured properly to avoid authentication issues.


⭐ Acknowledgement
This homepage is adapted from AcadHomepage and modified by Henry Zhang for improved responsiveness, layout customization, and personal branding.

