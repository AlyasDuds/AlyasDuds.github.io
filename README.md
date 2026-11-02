# Dann Mykell Martin — Portfolio

Personal portfolio of **Dann Mykell Martin**, systems developer building web applications for legal records, company assets, and postal operations.

**Live site:** [alyasduds.github.io](https://alyasduds.github.io/)

## Projects

| Project | Status | Highlights |
|---|---|---|
| **Legal Case Management System** | In progress (team project) | Case tracking, hearing calendar and deadline reminders, document storage, billing, role-based access |
| **Inventory Asset Management System** | In progress | Asset register with tags and barcodes, transfer history, maintenance and depreciation, low-stock alerts, audit trail |
| **Postal Profile System** | 80% complete | Office profiles across 9 postal areas, live dashboard, quarterly connectivity reports (PDF and Excel), approval workflow |

### Team

The Legal Case Management System is built with a dev team:

- [phlpostjosh](https://github.com/phlpostjosh) — Senior Developer
- [ShirouOne2](https://github.com/ShirouOne2)
- [rlphstps](https://github.com/rlphstps)

## Skills

- **Backend:** Java, Spring Boot, Spring Security, Spring Data JPA, Hibernate, REST API, WebSocket
- **Frontend:** Thymeleaf, Bootstrap 4, JavaScript, Chart.js, HTML/CSS, DataTables
- **Database and DevOps:** PostgreSQL, MySQL, Apache POI, iText PDF, Git, Maven
- **Other languages (basic):** PHP, C#, C++

## Project structure

```
.
├── index.html        # The whole portfolio (HTML, CSS, JS in one file)
├── README.md
├── legal-1.png ...   # Legal Case screenshots
├── inventory-1.png ...
├── pps-1.jpg ...     # Postal Profile System screenshots
└── pps-demo.mp4      # Postal Profile System demo video
```

Screenshot and video file names are listed in the `PROJECTS` object inside `index.html`. To add or change media, put the file next to `index.html` and update that list. A project with no files shows "coming soon".

## Run locally

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy with GitHub Pages

1. Push `index.html` and the media files to the repository root.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Because this repository is named `AlyasDuds.github.io`, the site is live at `https://alyasduds.github.io/`.

## Contact

- Email: [danmartin172629@gmail.com](mailto:danmartin172629@gmail.com)
- GitHub: [AlyasDuds](https://github.com/AlyasDuds)
