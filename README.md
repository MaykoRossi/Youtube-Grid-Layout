# YouTube Replica Homepage

This project is a replica of the YouTube homepage, focusing on the layout and structure using HTML and CSS. The page includes a sidebar for subscribed channels, a grid layout for recommended videos, and a responsive design to ensure proper display across various screen sizes.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [File Structure](#file-structure)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project aims to create a simplified replica of YouTube's homepage, primarily focusing on the following elements:
- A header with the YouTube logo, a search bar, and a user avatar.
- A sidebar displaying subscribed channels.
- A grid layout showcasing recommended videos with thumbnails, titles, channels, and view counts.

## Features

- **Responsive Design**: The layout adapts to different screen sizes using CSS grid and media queries.
- **Grid Layout**: Videos are displayed in a 4x4 grid that scales down to 3x3, 2x2, or 1x1 depending on the screen width.
- **Subscribed Channels Sidebar**: A static sidebar listing several channels to simulate the subscription feature on YouTube.

## Technologies Used

- **HTML5**: For the structure of the webpage.
- **CSS3**: For styling, including the use of CSS Grid for the layout and media queries for responsiveness.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/youtube-replica.git
    ```
2. Navigate to the project directory:
    ```bash
    cd youtube-replica
    ```
3. Open `index.html` in your web browser.

## File Structure


- **index.html**: The main HTML file containing the structure of the page.
- **styles.css**: The CSS file responsible for styling the page, including grid layout and responsiveness.
- **imgs/**: Directory containing images for the YouTube logo, user avatar, channel avatars, and video thumbnails.

## Usage

Simply open the `index.html` file in any modern web browser to view the YouTube replica homepage.

### Responsiveness

- The layout is fully responsive, with the grid adjusting from 4 columns to 1 column depending on the screen size.
- The sidebar remains fixed on the left, while the video grid scales accordingly.

## Screenshots

### Desktop View

![Desktop View](screenshots/desktop-view.png)

### Mobile View

![Mobile View](screenshots/mobile-view.png)

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository, make changes, and submit a pull request.

1. Fork the project.
2. Create your feature branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
