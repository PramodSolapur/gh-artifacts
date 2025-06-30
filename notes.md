#### Jobs Artifacts

job artifacts are files or directories that you choose to save (upload) from one job so they can be downloaded later, either:
- 📥 By another job in the same workflow
- 📥 Manually from the GitHub Actions UI
- 📥 Via the GitHub API or CLI
They are temporary storage for passing build/test output, logs, binaries, reports, etc.



#### Where do the files go?
They are:

- Uploaded to GitHub's temporary artifact storage
- Scoped to this specific workflow run
- Available for download by other jobs in the same run
- Downloadable manually from the "Actions" tab in the GitHub UI