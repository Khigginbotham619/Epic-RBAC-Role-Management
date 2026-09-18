# Epic-RBAC-Role-Management
Web app for managing Epic RBAC roles, job categories, templates, and SailPoint mappings with audit logging, CSV import/export, and SQL Server persistence.
Run after unzip:

cd epic-rbac-role-management
npm install
copy .env.example .env
npm run dev
Open http://localhost:3000. Put your SQL connection string in .env, or set datastore=file for a local JSON demo. Full steps are in that zip’s README.md.
