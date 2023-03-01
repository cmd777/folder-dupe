# Folder duping bug

How it works: for some reason, folders that contain other folders are duped.

# How to replicate:

**Note: This bug is not visible on mobile, as it requires the folder tree to be opened. If you have a screen that is at least 768 pixels wide, it should work then (unless it gets patched.)**

- Click on the testing/123 folder
- Click on the . . . (to go back)
- Click on the . . . (to go back)

The following folders should appear twice:

- .github/workflows
- abc/temp
- cmd/testing
