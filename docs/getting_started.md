# Getting Started with Compass

Welcome, Golden Path Champion! This guide will walk you through setting up Compass for your organization.
By the end of this tutorial, you'll have a customized version of Compass ready to host your own golden paths.

## Prerequisites

Before we begin, ensure you have:

- Git installed on your machine

- Python 3.7 or higher installed

## Step 1: Clone the Compass Repository

1. Open your terminal or command prompt.

2. Navigate to the directory where you want to set up Compass.

3. Run the following command to clone the Compass repository:

    ```bash
    git clone https://github.com/kevinknights29/Compass.git
    ```

4. Navigate into the newly created Compass directory:

    ```bash
    cd Compass
    ```

## Step 2: Set Up a Python Virtual Environment

1. Create a new virtual environment:

    ```bash
    python -m venv compass-env
    ```

2. Activate the virtual environment:

   - On Windows:

     ```powershell
     compass-env\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source compass-env/bin/activate
     ```

## Step 3: Install Dependencies

1. With your virtual environment activated, install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Step 4: Customize Your Compass Instance

1. Replace the logo:

   - Navigate to the `docs/assets/` directory.
  
   - Replace `compass.png` with your organization's logo (keep the filename the same).

2. Update the welcome page:

   - Open `docs/index.md` in your preferred text editor.

   - Modify the content to reflect your organization's vision and goals for golden paths.

3. Customize the getting started guide:

   - Open `docs/getting_started.md` (this file) in your text editor.

   - Adjust the content to match your organization's specific setup process and requirements.

4. Configure site settings:

   - Open `mkdocs.yml` in your text editor.

   - Update the `site_name`, `site_description`, and other relevant fields to match your organization.

## Step 5: Preview Your Compass Site

1. In your terminal, with the virtual environment still activated, run:

    ```bash
    mkdocs serve
    ```

2. Open a web browser and go to `http://127.0.0.1:8000/` to preview your Compass site.

## Step 6: Build and Deploy

1. When you're satisfied with your changes, build the static site:

    ```bash
    mkdocs build
    ```

2. The built site will be in the `site/` directory. You can now deploy this to your preferred hosting solution (e.g., GitHub Pages, Netlify, or your internal hosting).

## Next Steps

Congratulations! You now have a customized instance of Compass ready to host your organization's golden paths. Here are some next steps to consider:

1. Start creating your first golden path document in the `docs/` directory.

2. Set up a process for your team to contribute to and review golden paths.

3. Introduce Compass to your organization and start driving adoption.

Remember, golden paths are about education and standardization. As you create your paths, keep your audience in mind and strive for clarity and completeness in your instructions.

Happy path-building!
