# DAUB (E-commerce Shopify Website)

**Project Overview:**
DABB is an online store specializing in men's t-shirts. We offer a curated collection of high-quality tees designed to cater to various styles and preferences.

## Features

* **Home Page:** Explore latest collection and discover global trends.
* **Seamless Sharing:** Share experiences through a personalized feed.
* **Personalized Feeds:** Tailor content based on interests.
* **Bucket Lists:** Create private lists for selective sharing.
* **Reward Coins:** Earn and redeem coins for rewards.
* **Cross-Platform Compatibility:** Access DAUB on most devices because is a website.
* **Private Sharing:** Share links without revealing your profile.
* **Seamless Payments:** Make payments without QR codes or phone numbers.

## Bug List

### Critical Bugs
| Title | Description | Severity | Affected Pages | Bug Patch |
|---|---|---|---|---|
| **Bug 1** | Wishlist click redirects to login page when logged out. | Critical | Home | [Patch Link] |
| **Bug 2** | Logo is not centered. | Critical | Home | [Patch Link] |
| ... | ... | ... | ... | ... |

### High Priority Bugs
| Title | Description | Severity | Affected Pages | Bug Patch |
|---|---|---|---|---|
| **Bug 1** | Wishlist is enabled even when not logged in. | High | Product | [Patch Link] |
| **Bug 2** | Wishlist heart icon is too small. | High | Product | [Patch Link] |
| ... | ... | ... | ... | ... |

### Medium Priority Bugs
| Title | Description | Severity | Affected Pages | Bug Patch |
|---|---|---|---|---|
| **Bug 1** | No pop-up for email sent notification. | Medium | Login | [Patch Link] |
| **Bug 2** | Sign in with Google is not enabled. | Medium | Login | [Patch Link] |
| ... | ... | ... | ... | ... |

### Low Priority Bugs
| Title | Description | Severity | Affected Pages | Bug Patch |
|---|---|---|---|---|
| **Bug 1** | Account activation via forgot password. | Low | Create Account | [Patch Link] |
| **Bug 2** | Same mail body for account creation and forgot password. | Low | Create Account | [Patch Link] |
| ... | ... | ... | ... | ... |

## Bug Patches

| Title | Description | Date Applied | Changes Made |
|---|---|---|---|
| **Patch 1** | Added pop-up for email sent notification. | [Date] | Implemented JavaScript to trigger pop-up. |
| **Patch 2** | Fixed account activation issue. | [Date] | Corrected backend logic for activation. |
| ... | ... | ... | ... |

# Bug Report: E-commerce Website Improvements

## Home Page

1. **Wishlist Redirect**: When logged out, clicking the wishlist should redirect to the login page.
2. **Center the Logo**: The logo needs to be centered. Apply CSS styles (e.g., `text-align: center;` or `margin: 0 auto;`) to achieve this.
3. **"Shop Now" Button**: Ensure that the "Shop Now" button opens the entire collection page. Update the button's URL accordingly.
4. **Wishlist Option Next to Cart**: Add a wishlist icon/link next to the cart at the top. Implement redirection to the wishlist page or prompt for login.
5. **Top Banner Styling**: Adjust the color and thickness of the top banner using CSS.

## Product Page

1. **Enable Wishlist**: Only show the wishlist heart icon when users are logged in.
2. **Heart Icon Size**: Increase the size of the wishlist heart icon to match other icons.
3. **Remove Wishlist Text**: Hide the text associated with the wishlist icon.

## Login Page

1. **Pop-up for Email Sent Notification and Errors**: After form submission, display a pop-up for email sent notifications and error messages.
2. **"Sign in with Google" Option**: Enable users to sign in with their Google account.
3. **Mark Mandatory Fields**: Add an asterisk (*) to mandatory fields on all form pages.
4. **Redirect After Sign-In**: Redirect users to the home page after clicking "Sign in," rather than the account page.

## Create Account Page

1. **Email Confirmation Pop-up**: After clicking "Create Account," show a pop-up indicating that an email has been sent for confirmation. Allow login only after email confirmation.
2. **Mark Mandatory Fields**: Mark mandatory fields with an asterisk (*) on all form pages.

## Contact Page

1. **Phone Number Support**: Add phone number support with a 10-digit limit check. Display an alert before submission.

## Forgot Password Page

1. **Reset Password Redirect**: After clicking "Reset Password," redirect users to the login page with a message: "Password has been changed."

## Manage Address Page

1. **Change "Province" to "State"**: Update the label for the address field.
2. **Asterisk for Mandatory Fields**: Mark mandatory address fields with an asterisk (*).
3. **Display Errors**: Implement validation checks for mandatory fields and display relevant error messages.


**Note:**

* Replace the placeholders with actual bug descriptions, severities, affected pages, and patch details.
* Link to the corresponding GitHub Issues for each bug and patch.
* Use Markdown formatting for tables and headers.
* Consider adding a section for known issues or future enhancements.

By following this structure, you'll create a clear and informative README that helps contributors understand the project's status and contribute effectively.
