git clone https://github.com/TejasBhosale123/my-website.git
cd my-website
git branch
git checkout -b feature-improve-docs
git add .
git commit -m "Improved documentation for Docker getting started"
git push origin feature-improve-docs
git checkout main
git merge feature-improve-docs
