# Installation Guide

Follow these steps to install and set up the project.

## Step 1: Download the Model

Download the `model.h5` from the following link:

[Download model.h5](https://drive.google.com/file/d/1GcoUqB6WhT0BeqD4nbqVJy4yJfO61v4Z/view?usp=drive_link)  

## Step 2: Place the Model

After downloading, place the `model.h5` file in the `detection/models/` folder after making a "models" folder inside detection folder.

## Step 3: Open your project folder in terminal

Open 'Lung-cancer-detection' folder inside the terminal

## Step 4: Install Dependencies

Open your terminal and navigate to the root directory of the project, then run:

```bash
pip install -r requirements.txt
```

## Step 5: Run the Django Development Server
Finally, start the Django development server by running:

```bash
python manage.py runserver
```
The app will be accessible at http://127.0.0.1:8000/ in your browser.
