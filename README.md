# User Registration Form

A modern, responsive registration form with real-time validation built with HTML, CSS, and JavaScript.

## Features

- **Real-time Validation**: Fields are validated as users type
- **Comprehensive Field Validation**:
  - First/Last Name: Letters only (2-50 characters)
  - Username: Alphanumeric + underscore (3-20 characters)
  - Email: Valid email format
  - Phone: Valid phone number format
  - Date of Birth: Must be 13+ years old
  - Required field indicators
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Modern UI**: Glass morphism design with smooth animations
- **Success Modal**: Confirmation message after successful registration

## Technologies Used

- HTML5
- CSS3 (with animations and glass morphism effects)
- Vanilla JavaScript (no frameworks)
- Google Fonts (Playfair Display & Work Sans)

## Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., `registration-form`)
5. Choose "Public" visibility
6. Click "Create repository"

### Step 2: Upload Files

#### Option A: Using GitHub Web Interface

1. In your new repository, click "uploading an existing file"
2. Drag and drop the `index.html` file
3. Scroll down and click "Commit changes"

#### Option B: Using Git Command Line

```bash
# Initialize git in your project folder
git init

# Add the files
git add index.html README.md

# Commit the files
git commit -m "Initial commit: Add registration form"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" section in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select branch: "main" and folder: "/ (root)"
6. Click "Save"

### Step 4: Access Your Site

After a few minutes, your site will be live at:
```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

## Validation Rules

| Field | Validation Rule |
|-------|----------------|
| First Name | Letters, spaces, hyphens, apostrophes only (2-50 chars) |
| Last Name | Letters, spaces, hyphens, apostrophes only (2-50 chars) |
| Username | Letters, numbers, underscore only (3-20 chars) |
| Email | Valid email format (user@domain.com) |
| Phone | Numbers, spaces, hyphens, plus, parentheses (10-20 chars) |
| Date of Birth | Must be at least 13 years old |
| Gender | Required selection |
| Country | Required selection |
| Company Name | Optional, minimum 2 characters if filled |
| Home Address | Required, minimum 10 characters |
| Office Address | Optional, minimum 10 characters if filled |

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Customization

You can customize the form by modifying the CSS variables in the `:root` selector:

```css
:root {
    --primary: #1a1a2e;        /* Main background color */
    --accent: #e94560;         /* Accent color for buttons */
    --success: #06d6a0;        /* Success state color */
    --error: #ef476f;          /* Error state color */
}
```

## License

This project is open source and available for educational purposes.

## Assignment Information

**Course**: CS 409-IT3258 - Mobile Computing  
**Assignment**: 2.2 Creating Registration Form w/ Validation  
**Due Date**: Feb 16 by 11:59pm  
**Points**: 32  
**AI Usage Category**: Limited

## Honor Pledge

"I affirm that I have not given or received any unauthorized help on this assignment and that this work is my own."

## AI Usage Disclosure

I used artificial intelligence tools (Claude AI) for this activity. The AI assisted with:
- Creating the HTML structure and form layout
- Implementing CSS styling and animations
- Writing JavaScript validation logic
- Adding real-time input restrictions (preventing numbers in name fields, letters in phone field)
- Guidance on GitHub Pages deployment

All code was reviewed, tested, and understood before submission.

## References

- [MDN Web Docs - HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
- [MDN Web Docs - Form Validation](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Google Fonts](https://fonts.google.com/) - Playfair Display & Work Sans
- [CSS Gradient Generator](https://cssgradient.io/)
- Claude AI (Anthropic) - Code assistance and implementation
