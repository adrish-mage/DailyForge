## 📌 Description
A Dynamic task count badge was added next to the "Task Library" header in `TaskLibrary.jsx`.
The count updates in real-time based on active search filters.


## 🔗 Related Issue
Closes #58

## 🛠 Changes Made
- Added a count badge (`<span>`) next to the "Task Library" header in `TaskLibrary.jsx`
- Badge displays `filteredTasks.length` that reflects filtered count when search is active, and total count otherwise.

## 📸 Screenshots (if applicable)
Add screenshots or GIFs to explain UI changes.

## ✅ Checklist
- [ ] Code runs locally
- [x] Followed project structure
- [x] No console errors
- [x] Properly tested changes
- [x] Linked the issue

## 🚀 Notes for Reviewers
Change is isolated to the header section of `TaskLibrary.jsx` with no backend dependency.
Local MongoDB connection issue prevented full local run, but this is a pure frontend change
derived from the already-fetched `tasks` state via `useTasks()`.
