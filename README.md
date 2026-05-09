# WEB-SYS-PROJECT

## Project Structure

```text
/project-root
├── /models
├── /controllers
├── /views
├── /sql        # contains SQL scripts for table setup and sample data
├── /public     # index.php, shared css/js, and role-specific frontends
│   ├── /admin
│   │   ├── /css
│   │   ├── /js
│   │   └── index.php
│   └── /employee
│       ├── /css
│       ├── /js
│       └── index.php
├── config.php  # for DB credentials, never push real passwords
├── .gitignore  # ignore node_modules, vendor, .env, config, etc
└── README.md
```
