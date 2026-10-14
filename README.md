# Drawing pad

Paint with the mouse; clear with the secondary button.

This is a complete editable Zero project.

![Drawing pad app preview](preview.png)

## Create your own repository and clone it

1. Open [Use this template](https://github.com/codepetca/zero-drawing-pad/generate), then choose **Create a new
   repository**. Select your personal account as owner, choose your own project
   name and follow your teacher's visibility instructions.
2. Open the repository you just created in your own account. Choose **Code →
   HTTPS** and copy its URL. Clone your own repository into a new local folder:

```sh
git clone https://github.com/YOUR-USERNAME/YOUR-PROJECT.git
cd YOUR-PROJECT
```

   Replace both placeholders with your own account and repository name. These
   commands work in macOS Terminal and Windows PowerShell with Git installed.
3. Open that cloned root folder in Zero (the configured VS Code editor).
4. Choose Run App in the Zero sidebar.

Your own GitHub repository already contains the starter baseline on **main**.
The clone already connects to your own repository as origin.

## ZIP alternative

If you downloaded a ZIP instead, extract it into its own folder and open that
root folder in Zero. A ZIP has no Git history. Create your own empty GitHub
repository, leaving README, license and gitignore uninitialized. Sign in through
Zero and use **Connect a repo → Connect an existing repository…** with your own
repository's HTTPS URL, then review **Upload changes** on **main** for the initial
project. Connection alone does not upload files.


A supported JDK 17 or later is required. Read and edit the Java files in
`src/main/java`; the Zero framework source is included in its `zero` folder.

From a terminal in this project folder, run:

macOS:

```sh
./mvnw clean compile javafx:run
```

Windows PowerShell:

```powershell
.\mvnw.cmd clean compile javafx:run
```

The pinned Maven wrapper downloads build tools and JavaFX dependencies on the
first run. You can also run `./mvnw clean compile` (or
`.\mvnw.cmd clean compile`) to check your code without opening the app.

## Try one change

Change the brush colour and size. Check a click, a continuous stroke and clearing the drawing.

## Your GitHub repository and Pika

1. Sign in through Zero's GitHub profile control using your personal account.
   Configure Git's per-repository name/email identity manually; signing in does
   not configure commit identity. Real uploads require native GitHub sign-in and
   **`zero.uploadMode`: `live`** in workspace settings. The default
   simulation makes no Git changes and uploads nothing; Start and Finish also
   simulate without changing branches.
2. Personalize this README with your project idea and a short change plan.
   If edits are pending, use **Upload changes** on **main** before starting a
   change. Write a commit message, review your repository, branch and changed
   files, then confirm Commit & Upload.
3. With clean committed main, click **main → Start a change** and review the new
   branch. Edit the Java, choose **Run App**, and check the behavior you changed.
4. **Upload changes** with an explanatory commit message. Review the destination
   and changed files. Upload any pending edits before finishing.
5. Click your branch → **Finish change** and review the completed change into
   main. If Zero brings in newer main code, Run App again and review Finish again.
   Finish merges into main directly; it does not create a pull request.
6. Check your actual files on GitHub's **main** branch. Submit your own repository
   link separately in Pika, giving your teacher access if it is private.

Run App does not require GitHub sign-in. Ask your teacher for help with setup,
conflicts or failed uploads. See the [repository and upload guide](https://github.com/codepetca/zero/blob/main/docs/GETTING-STARTED.md#your-individual-workflow).

Canonical example source: https://github.com/codepetca/zero-drawing-pad
