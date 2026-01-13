## 🧑‍🏫 Assignment Rules

✔ Follow the provided folder structure  
✔ Use **Page Object Model (POM)**  
✔ **Do NOT** use `page.waitForTimeout()`  
✔ Use proper and meaningful assertions  
✔ Use clear and meaningful test names  

❌ Hard-coded waits are not allowed  
❌ Poor locator strategies should be avoided  

---

## 🧪 Test Folder Structure
demoqa-playwright-assignment/
│
├── tests/                         # All test specifications
│   ├── e2e/
│   │   ├── demoqa.e2e.spec.ts     # Complete end-to-end user journey
│   │
│   ├── elements/
│   │   ├── textBox.spec.ts
│   │   ├── checkBox.spec.ts
│   │   ├── radioButton.spec.ts
│   │   ├── webTables.spec.ts
│   │   ├── buttons.spec.ts
│   │   ├── links.spec.ts
│   │   ├── uploadDownload.spec.ts
│   │
│   ├── forms/
│   │   └── practiceForm.spec.ts
│   │
│   ├── alerts-frames/
│   │   ├── alerts.spec.ts
│   │   ├── frames.spec.ts
│   │
│   ├── widgets/
│   │   ├── datePicker.spec.ts
│   │   ├── toolTips.spec.ts
│   │
│   ├── interactions/
│   │   ├── dragAndDrop.spec.ts
│
├── pages/                         # Page Object Model (POM)
│   ├── base/
│   │   └── BasePage.ts            # Common reusable actions
│   │
│   ├── HomePage.ts
│   ├── TextBoxPage.ts
│   ├── CheckBoxPage.ts
│   ├── RadioButtonPage.ts
│   ├── WebTablesPage.ts
│   ├── ButtonsPage.ts
│   ├── LinksPage.ts
│   ├── UploadDownloadPage.ts
│   ├── PracticeFormPage.ts
│   ├── AlertsPage.ts
│   ├── FramesPage.ts
│   ├── WidgetsPage.ts
│   ├── InteractionsPage.ts
│
├── test-data/                     # Static test data
│   ├── users.json
│   ├── formData.json
│
├── utils/                         # Helpers & utilities
│   ├── testUtils.ts
│   ├── waitHelpers.ts
│
├── fixtures/                      # Playwright fixtures
│   └── testFixtures.ts
│
├── reports/                       # Test execution reports
│   ├── html-report/
│   └── screenshots/
│
├── playwright.config.ts           # Playwright configuration
├── package.json                   # Project dependencies & scripts
├── tsconfig.json                  # TypeScript configuration
├── README.md                      # Assignment instructions
└── .gitignore


## 📝 Evaluation Rubric (Optional)

The assignment will be evaluated based on the following criteria:

| Area            | Marks |
|-----------------|-------|
| Test coverage   | 30    |
| Code quality    | 25    |
| Assertions      | 20    |
| POM usage       | 15    |
| Reporting & CI  | 10    |
| **Total**       | **100** |
