| ID | Title | Preconditions | Steps | Expected Result | Status |
|----|------|---------------|-------|----------------|
| TC-01 | Load home page | None | 1. Open the application URL | Home page loads without errors | Passed |
| TC-02 | Navigate to Recetas page | Home page loaded | 1. Click on "Recetas" in navbar | Recetas page is displayed | Passed |
| TC-03 | Smooth navigation between pages | App loaded | 1. Navigate between Inicio and Recetas | Navigation is smooth and without page break | Passed |
| TC-04 | Open routine pop-up (any day) | Home page loaded | 1. Click on "Ver rutina" button | Corresponding pop-up opens | Passed |
| TC-05 | Close pop-up using X button | Pop-up opened | 1. Click on "X" icon | Pop-up closes correctly | Passed |
| TC-06 | Pop-up overlay behavior | Pop-up opened | 1. Observe background | Background is dimmed and blocked | Passed |
| TC-07 | Pop-up content visibility | Pop-up opened | 1. Scroll if needed | All routine content is visible | Passed |
| TC-08 | Pop-up title alignment | Pop-up opened | 1. Compare title and content alignment | Title and content are visually aligned | **Failed** |
| TC-09 | Pop-up layout consistency | Pop-ups opened for different days | 1. Open multiple routines | Layout is consistent across pop-ups | **Failed** |
| TC-10 | Open recipe pop-up | Recetas page loaded | 1. Click on recipe item | Recipe pop-up opens correctly | Passed |  
| TC-11 | Close recipe pop-up | Recipe pop-up opened | 1. Click on "X" icon | Recipe pop-up closes correctly | Passed |
| TC-12 | Reopen pop-up after closing | Pop-up closed | 1. Click "Ver rutina" again | Pop-up opens again without issues | Passed |
| TC-13 | Highlight current day | User is on Home page | 1. Navigate to Home page | Current day is highlighted in bold with a grey background | Passed |
