# SlickFox - Personalized Firefox Configuration

Enhance your Firefox browsing experience with SlickFox, a customized user interface designed for efficiency and style.

## How to Apply SlickFox Configuration

Follow these simple steps to apply the configuration to your Firefox browser:

1. Type `about:profiles` into your Firefox address bar and go to the page.
2. In the profile you're using, find and open the root directory folder specified on the page.
3. Inside the root directory, create a new folder named "chrome" (if it doesn't already exist).
4. Download the `userchrome.css` file from this repository and place it inside the "chrome" folder you just created.
5. Type `about:config` into your Firefox address bar and go to the page.
   - Paste `toolkit.legacyUserProfileCustomizations.stylesheets` into the search bar.
   - Set the value to `true` to enable custom stylesheets support.
6. Go back to `about:profiles` and click the "Restart Normally" button to apply the configuration changes.

## Preview Images

![Default State](https://github.com/Kamimusuhi/SlickFox/assets/130303898/b47867d4-1584-4c13-baca-0cb9a4573f08)
*Default state of the interface.*

![Hover/Focus State](https://github.com/Kamimusuhi/SlickFox/assets/130303898/d839d68d-7027-42dd-90d2-fc31c64270d4)
*Interface when hovered/focused.*


If you encounter any issues or have questions, please feel free to reach out. Happy browsing!
