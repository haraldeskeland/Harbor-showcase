# Contributing to Harbor Showcase

Thank you for your interest in contributing to the Harbor showcase repository!

## Adding Screenshots

To add screenshots to the showcase:

1. **Prepare your images:**
   - Use high-quality screenshots (recommended resolution: 1920x1080 or higher)
   - Save in PNG or JPG format
   - Ensure any sensitive data is removed or masked
   - Use consistent styling across all screenshots

2. **Add images to the repository:**
   ```bash
   # Place images in the screenshots directory with these exact names:
   - images/screenshots/landing-page.png
   - images/screenshots/dashboard.png
   - images/screenshots/orders.png
   - images/screenshots/inventory.png
   - images/screenshots/kanban-board.png
   - images/screenshots/margins.png
   ```

3. **Update the README:**
   - Uncomment the image markdown lines in the Screenshots section
   - Remove the placeholder text below each commented image tag
   - The format is already set up: `![Alt Text](path/to/image.png)`

## Example

Current state (before adding images):
```markdown
### Landing Page
<!-- ![Landing Page](images/screenshots/landing-page.png) -->
*Screenshot of the landing page will be displayed here*
```

After adding images:
```markdown
### Landing Page
![Landing Page](images/screenshots/landing-page.png)
```

## Submitting Changes

1. Fork the repository
2. Create a new branch for your changes
3. Add your images and update the README
4. Commit your changes with a clear message
5. Submit a pull request

## Questions?

If you have any questions, please open an issue in the repository.
