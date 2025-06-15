 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
index a7325f901f57acf66b11f6179d8e13aadf18de80..cb9bd613b3423fb866715b47a9f4ceb457b73ab4 100644
--- a/README.md
+++ b/README.md
@@ -1,48 +1,15 @@
-# Aleksander R. Rodriguez Kozlowski | Interactive Resume
+# Personal Website
 
-Welcome to my personal resume website. I built this site to give a quick, professional overview of who I am, what I’ve done, and what I can offer.
+This repository contains the source code for my personal website. The site is built with HTML, CSS and JavaScript and includes:
 
-I'm a detail-focused professional with experience in program analysis, quality management, and government records tracking. I enjoy solving problems, building systems that work better, and learning new tools that make life easier. Whether it's leading a project, creating dashboards, or tuning engines — I get the job done.
+- A responsive navigation bar
+- Hero section with stock imagery
+- About section with a short bio
+- Project gallery with links to GitHub repositories
+- Contact form powered by Formspree
 
-This website shows some of my GitHub projects, and it's built using HTML, CSS, and JavaScript. It automatically updates to show the latest work from my GitHub account.
+My resume is available directly from the site and can be found in this repository as `Aleksander Rodriguez_Resume V1.pdf`.
 
-## Highlights
+To view the website locally, open `index.html` in a web browser. For a live version, you can publish the site with GitHub Pages.
 
-- Built to show my personal projects and professional accomplishments
-- Easy to update and expand with a user-friendly layout
-
-## About Me
-
-- **Graduated:** Bachelor’s of Science in Project Management, Arizona State University (2025)
-- **Current Role:** Management and Program Analyst – United Stated Department of Agriculture
-- **Focus Areas:** Program development, risk analysis, and team collaboration
-- **Tools I Use:** GitHub, Power BI, Excel, SharePoint, ArcGIS, Fusion360, TunerPro, and more
-- **Creative Side:** I run a YouTube channel where I am currently restoring a 2004 Chevy Silverado 2500HD
-
-## Projects
-
-The "GitHub Projects" section below pulls directly from my GitHub account. It shows the work I’ve done on coding, automation, and other tools. Use the search bar to filter projects by name or keywords.
-
-## How I Built This
-
-This site is made with:
-
-- **HTML & CSS** for layout and styling
-- **JavaScript** for interactivity and GitHub integration
-- **GitHub API** to fetch and display my public repositories
-
-## View the Live Website
-
-[Visit the Live Website](https://alekrodriguezresume.github.io/Resume/)
-
-## Contact
-
-**Aleksander R. Rodriguez Kozlowski**  
-Palm Bay, Florida  
-LinkedIn: [Alek Rodriguez](https://linkedin.com/in/alekrodriguez)
-Email: [alekrodriguezresume@gmail.com](mailto:alekrodriguezresume@gmail.com)  
-GitHub: [alekrodriguezresume](https://github.com/alekrodriguezresume)
-
----
-
-Thank you for visiting — let’s connect!
+Feel free to clone this repo and adapt it for your own portfolio.
 
EOF
)
