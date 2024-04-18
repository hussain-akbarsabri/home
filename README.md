# Getting started

Project is open source. Feel free to make your own version. All you need to do is to fork this repository, edit [src/editable-stuff/config.js](./src/editable-stuff/config.js) and add resume.

## Prerequisites

You should have [Node.js](https://nodejs.org/en/) and [Git](https://git-scm.com/) installed on your computer. You should also own a GitHub account.

## Structure

- Navigation bar (optional)
- Body
  - Name | Profession
  - Contact / Follow / Find me / Facebook / LinkedIn / GitHub / Instagram / Email / CodePen
  - Resume | About me
- About Me
  - Display picture (optional)
  - About myself, my Interests, Goals and Hobbies
  - Things I'm good at (Skills)
  - Resume button
- Recent Projects (using GitHub API) (optional)
- Leadership (optional)
  - Paragraph
  - Carousel images
- Skills (optional)
  - Technical Skills
  - Soft Skills
- Footer
  - Footer Note (optional)
  - Copyrights - open source
  - Acknowledgements

## Setup And Deployment

1. To Get Started, Fork this repository to your GitHub account:
2. Clone the forked repo from your account using:
3. Open in editor and edit [src/editable-stuff/config.js](./src/editable-stuff/config.js) file.
4. Add your resume as <resume.pdf> in place of [src/editable-stuff/resume.pdf](./src/editable-stuff/)
5. Edit [title](./public/index.html#L34) and meta [description](./public/index.html#L13) in [public/index.html](./public/index.html).
6. Change URL in [package.json](./package.json) file:
   ```json
    "homepage": "https://<your-username>.github.io/portfolio"
   ```
7. After editing run the following bash commands:
   ```bash
   npm install
   npm start
   ```
8. To deploy website, run:
   ```bash
    npm run build
    npm run deploy
   ```
9. Congrats your site is up and running. To see it live, visit:
   ```https
     https://<your-username>.github.io/portfolio
   ```
10. To change the thumbnail image:
    - Navigate to the "public" folder.  
    - There you will see "social-image.png".  
    - Delete it.   
    - Take a screenshot of your version and rename it "social-image.png" and place it there.
Next time if you make changes, repeat from step 8.
Facing issues? Feel free to contact at hussain.akbarsabri@gmail.com.
