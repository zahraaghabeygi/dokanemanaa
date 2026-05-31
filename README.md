# Dokane Mana/دکان معنا 


**Dokan Mana** is a Persian, single-page website for introducing and sharing podcast episodes inspired by stories and lessons from Rumi's Masnavi.

The website is built with plain **HTML**, **CSS**, and **JavaScript**, without using any framework.

## About the Project

Dokkan Mana is a simple and elegant podcast landing page.
It presents selected episodes from the first book of the Masnavi and provides direct links for listening to each episode.

The design is inspired by Persian, traditional, and mystical visual elements, using warm colors, a medallion-style logo area, and responsive episode cards.

## Features

* Persian RTL layout
* Hero section with logo and title
* Podcast episode slider
* Direct listening links for each episode
* Traditional Persian-inspired visual style
* Built with vanilla HTML, CSS, and JavaScript

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Vazirmatn Font
* Google Fonts

## Project Structure





## How to Run

To run the project, simply open the `index.html` file in your browser.

You can also use the **Live Server** extension in VS Code for a better development experience.

## Important Notes

* The `logo.jpg` file should be placed in the same folder as `index.html`.
* Episode links currently point to Google Drive files.
* Make sure the Google Drive files are publicly accessible or shared with anyone who has the link.

## How to Add a New Episode

To add a new episode, copy the structure below and place it inside the `slider-track` section in `index.html`:

```html
<div class="ep">
  <div class="ep-band"></div>
  <div class="ep-body">
    <div class="ep-meta">
      <span class="ep-num-badge">EP 8</span>
      <span class="ep-label">New Episode</span>
    </div>

    <h3 class="ep-title">Episode Title</h3>

    <div class="ep-quote-wrap">
      <p class="ep-quote">
        Short description about the episode.
      </p>
    </div>

    <a class="ep-listen" href="EPISODE_LINK_HERE" target="_blank">
      <span class="ep-listen-icon">▶</span>
      Listen to Episode
    </a>
  </div>
</div>
```

## Deployment

This project can be deployed using **GitHub Pages**.

Steps:

1. Upload the project files to a GitHub repository.
2. Go to the repository **Settings**.
3. Open the **Pages** section.
4. Select the `main` branch.
5. Choose `/root` as the publishing folder.
6. Save the settings.

After a short time, GitHub will provide a public link for the website.

## Future Improvements




## License

The source code of this project is licensed under the MIT License.

The Dokkan Mana name, logo, podcast audio files, and written content are owned by Dokkan Mana and may not be reused without permission.
