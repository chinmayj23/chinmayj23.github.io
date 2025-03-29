# Personal Website

This is my personal website showcasing my academic background, research interests, and professional experience.

## Features

- Modern, responsive design
- Smooth scrolling navigation
- Animated sections
- Mobile-friendly layout
- Clean and professional look

## Setup

1. Clone this repository:
```bash
git clone https://github.com/yourusername/personal-website.git
cd personal-website
```

2. Add your personal information:
   - Update the content in `index.html` with your personal details
   - Add your profile picture to the `images` folder
   - Update the contact links with your email and social media profiles

3. Customize the design:
   - Modify colors in `css/style.css` by updating the CSS variables
   - Add or modify sections in `index.html` as needed
   - Update the JavaScript animations in `js/main.js` if desired

## Deployment to GitHub Pages

1. Create a new repository on GitHub named `yourusername.github.io`

2. Push your website to the repository:
```bash
git init
git add .
git commit -m "Initial website commit"
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

3. Enable GitHub Pages:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "main" branch as the source
   - Save the changes

Your website will be available at `https://yourusername.github.io`

## Local Development

To view the website locally, you can use any local server. For example, with Python:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then open your browser and visit `http://localhost:8000`

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Font Awesome Icons

## License

This project is open source and available under the MIT License. 