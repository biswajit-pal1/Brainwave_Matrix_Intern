# My Tailwind Project

This is a responsive website built using **HTML**, **JavaScript**, and
**Tailwind CSS (CLI build)**.

## 🚀 Features

-   Responsive design with Tailwind CSS
-   Custom theme with Poppins & Inter fonts
-   Interactive JavaScript components (menu toggle, scroll animations,
    FAQ accordion)
-   Gradient hover effects

## 📂 Project Structure

    .
    ├── index.html       # Main HTML file
    ├── script.js        # JavaScript for interactions
    ├── style.css        # Tailwind input (with @import "tailwindcss")
    ├── output.css       # Tailwind generated CSS (include this in index.html)
    └── assets/          # Images and other static assets

## ⚡ How to Run

1.  Clone the repository:

    ``` bash
    git clone https://github.com/<your-username>/<repo-name>.git
    cd <repo-name>
    ```

2.  Open `index.html` in your browser.

That's it --- no build step required, since **output.css** is already
included.

## 🛠 Development (if you want to rebuild Tailwind)

If you make changes to `style.css`, recompile Tailwind:

``` bash
npx tailwindcss -i ./style.css -o ./output.css --watch
```
