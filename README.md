# Your Name — Week 03: Tools & Workflow

A multi-page portfolio website built as part of the IYF Season 10 Web Development Program. This week focused on mastering the command line, Git version control, and professional documentation.

## Live Demo

[View Live Site](https://yourusername.github.io/iyf-s10-week-03-yourusername)

## Screenshot

![Project Screenshot](./images/screenshot.png)

## Features

- ✅ Responsive design (mobile & desktop)
- ✅ Multi-page layout (Home, About, Projects, Contact)
- ✅ Working contact form UI
- ✅ Full Git history with meaningful commits
- ✅ Feature branches and merge conflict resolution

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Custom Properties)
- Git & GitHub
- Bash / PowerShell scripting

## Project Structure

```
iyf-s10-week-03-yourusername/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── css/
│   └── styles.css
├── images/
│   └── screenshot.png
├── new-project.sh
├── terminal-log.md
├── .gitignore
└── README.md
```

## What I Learned

- Navigating the file system using only terminal commands
- Creating and managing files/folders via CLI (no GUI)
- Writing and running shell scripts to automate project setup
- Initialising Git repos, making meaningful commits, and managing branches
- Resolving merge conflicts manually
- Pushing to and pulling from GitHub
- Writing a professional README

## Git Workflow Used

```bash
# Feature branch workflow
git checkout -b feature/about-page
# ... make changes ...
git add .
git commit -m "feat: add about page content"
git checkout main
git merge feature/about-page
git branch -d feature/about-page
```

## Future Improvements

- [ ] Add JavaScript interactivity
- [ ] Implement dark mode toggle
- [ ] Connect contact form to a backend
- [ ] Add project filtering on the Projects page

## Contact

- Email; fabianmunga163@gmail.com
- LinkedIn: [Your Name](https://linkedin.com/in/yourprofile)
- GitHub: [@fabby442](https://github.com/fabby442)

## License

This project is open source and available under the [MIT License](LICENSE).