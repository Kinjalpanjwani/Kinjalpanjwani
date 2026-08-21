# Installation

Upload these files to the root of your GitHub profile repository:

```text
Kinjalpanjwani/
├── .github/
│   └── workflows/
│       └── snake.yml
├── assets/
│   ├── hero.svg
│   └── terminal.svg
└── README.md
```

Then:

1. Open the repository's **Actions** tab.
2. Select **Generate contribution snake**.
3. Choose **Run workflow**.
4. Wait for the workflow to create the `output` branch.
5. Refresh your GitHub profile.

The snake will regenerate automatically every day. If the workflow cannot publish, open **Settings → Actions → General → Workflow permissions** and enable **Read and write permissions**.

