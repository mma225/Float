# Build NusaRebuilt.exe without installing Python on your PC

This project includes a GitHub Actions workflow that builds the Windows executable on a Windows runner.

1. Create a GitHub account if you do not already have one.
2. Create a new repository, for example `nusa-rebuilt`.
3. Extract this ZIP and upload all files/folders inside the extracted project to the repository. Keep the `.github/workflows/build-windows.yml` folder structure.
4. Open the repository's **Actions** tab.
5. Select **Build NusaRebuilt Windows EXE** and click **Run workflow** (or push to the `main` branch).
6. Wait for the workflow to finish successfully.
7. Open the completed workflow run and download the artifact named **NusaRebuilt-Windows11-EXE**.
8. Extract the artifact; it contains `NusaRebuilt.exe`.

The EXE is built on Windows and is intended to run without a separate Python installation. Windows SmartScreen may show an unknown-publisher warning because this is an unsigned community build.

This does not produce the original Nusa executable and does not bypass Nusa Pro licensing. It builds this independent reimplementation.
