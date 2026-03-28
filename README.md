# Daily React Practice Repo

This repository automatically creates a new React component **every day** using GitHub Actions. It helps keep your GitHub contributions green while practicing React.

## 📂 Structure
- `components/` - Daily React component files will be generated here.
- `README.md` - Updated daily with a note of the new component.
- `.github/workflows/daily-react.yml` - GitHub Action workflow that handles daily updates.

## ✅ How it Works
- GitHub Actions runs daily and:
  - Creates `components/Component_YYYYMMDD.jsx` with a simple React component
  - Updates the `README.md` with today's date
  - Commits and pushes changes automatically

## 💡 Notes
- You can modify the workflow to include more complex components.
- Keep learning React by checking the daily generated component files.
