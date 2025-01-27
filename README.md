# EmotionSync

EmotionSync is an innovative Python-driven web tool crafted to analyze and interpret emotional datasets. With an intuitive design, it empowers users to seamlessly explore emotional trends and visualize meaningful insights.

## OVERVIEW:

Emotionsync provides a streamlined platform to manage and examine emotional data. Developed with Flask, it supports data uploads, interactive visualizations, and user-friendly result pages for an engaging experience.

## PROJECT STRUCTURE:

EmotionSync/
- **app.py**: Core script powering the application.
- **templates/**: Contains web templates for a smooth user interface.
  - **index.html**: Landing page template.
  - **result.html**: Template for displaying results.
- **static/**: Repository for all static assets.
  - **css/**: Stylesheets for the application.
  - **data/**: Dataset files used in processing.
  - **images/**: Visual assets utilized within the app.
- **venv/**: Virtual environment to manage project dependencies.

## SETUP INSTRUCTIONS:

1. Clone this repository.
2. Move to the project directory.
3. Initialize and activate the virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

## STARTING THE APPLICATION:

Execute the following command to launch:
```bash
python app.py
```
Open your web browser and visit [http://127.0.0.1:5000](http://127.0.0.1:5000).

## HOW TO USE:

1. Start the application using `app.py`.
2. Utilize the homepage (`index.html`) for uploading emotional data files.
3. Explore the results and visual insights on the results page (`result.html`).

## LICENSE:

This software is distributed under the MIT License. For full details, refer to the LICENSE file included in the repository.

---

We welcome contributions, feedback, and ideas to enhance this project. Reach out for any suggestions or queries!
