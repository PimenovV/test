# test
Tests and learning

## Updating Images

The website uses local images stored in the `/images` directory. The current images are placeholders and examples. You can replace them with your own images by following these steps:

1.  **Place your image files** into the `images` directory.
2.  **Update the image references**:
    *   **Option 1 (Recommended for simplicity):** Name your image files exactly the same as the placeholder files you want to replace. For example, to replace the profile picture, name your image `profile.png` and place it in the `images` directory. It will automatically replace the existing `images/profile.png`.
        *   `images/profile.png`
        *   `images/service_document.png`
        *   `images/service_website.png`
        *   `images/service_proofreading.png`
        *   `images/service_generic.png`
        *   `images/portfolio_project1.png`
        *   `images/portfolio_project2.png`
    *   **Option 2 (If using different filenames):** If you use a different filename (e.g., `my_awesome_profile.jpg`), you will need to update the corresponding `<img>` tag's `src` attribute in the `index.html` file. For example, you would change `<img src="images/profile.png" ...>` to `<img src="images/my_awesome_profile.jpg" ...>`.

**Recommended Image Dimensions (approximate):**

*   Profile Picture (`profile.png`): 200x200 pixels
*   Service Icons (`service_*.png`): 80x80 pixels
*   Portfolio Project Images (`portfolio_*.png`): 300x200 pixels

Using images with significantly different dimensions might affect the layout, so try to use images close to these sizes or adjust the CSS if needed.
