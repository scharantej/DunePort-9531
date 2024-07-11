## Flask Application Design

### HTML Files

- **index.html**: The primary landing page that includes the visual content showcasing the board game Dune: Imperium.
  - It will incorporate high-quality images of the game components, artwork, and thematic elements.
  - It will use a color scheme inspired by the Dune universe (deep blues, rich oranges, and sandy neutrals).
  - It will contain concise, captivating text to highlight the game's features and appeal to potential players.
  - It will feature smooth and engaging animations that enhance the presentation of the game.

### Routes

- **@app.route('/')**: This route will be linked to the **index.html** file. It will serve as the home page of the Flask application, displaying the landing page for Dune: Imperium.
- **@app.route('/about')**: This route will display an additional page with more detailed information about the game, such as its gameplay mechanics, strategy tips, and historical background.
- **@app.route('/contact')**: This route will provide a form for users to contact the game creators or ask questions. It will handle form submissions and send emails accordingly.