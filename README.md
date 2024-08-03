# Blog Capstone Project

This is a capstone project for creating a blog website with RESTful routing using Flask. The project includes functionalities for creating, editing, and deleting blog posts. The blog is styled using Bootstrap and CKEditor is used for rich text editing.

## Features

- Create new blog posts with a title, subtitle, author, image URL, and body content.
- Edit existing blog posts.
- Delete blog posts.
- View all blog posts on the home page.
- View individual blog posts.
- Simple and clean UI using Bootstrap.
- Rich text editing with CKEditor.

## Getting Started

### Prerequisites

Make sure you have the following installed on your system:

- Python 3.x
- Flask
- Flask-Bootstrap
- Flask-SQLAlchemy
- Flask-WTF
- Flask-CKEditor
- SQLAlchemy

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Prathamesh326/blog-capstone-project-RESTful-routing-upgraded-blog-website.git
cd blog-capstone-project-RESTful-routing-upgraded-blog-website
```

2. Install the required packages:

On Windows:
```bash
python -m pip install -r requirements.txt
```

On MacOS:
```bash
pip3 install -r requirements.txt
```

3. Run the application:

```bash
python main.py
```

4. Open your web browser and navigate to `http://127.0.0.1:5003` to see the blog in action.

## File Structure

```
blog-capstone-project-RESTful-routing-upgraded-blog-website/
│
├── static/
│   ├── assets/
│       ├── img/
│
├── templates/
│   ├── header.html
│   ├── footer.html
│   ├── index.html
│   ├── make-post.html
│   ├── post.html
│
├── main.py
├── requirements.txt
```

## Routes

- `/`: Home page displaying all blog posts.
- `/post/<int:post_id>`: Individual blog post page.
- `/new-post`: Create a new blog post.
- `/edit-post/<int:post_id>`: Edit an existing blog post.
- `/delete/<post_id>`: Delete a blog post.
- `/about`: About page.
- `/contact`: Contact page.

## Technologies Used

- Flask: A lightweight WSGI web application framework in Python.
- Flask-Bootstrap: A Flask extension that includes Bootstrap to make styling easy.
- Flask-SQLAlchemy: An extension for Flask that adds support for SQLAlchemy.
- Flask-WTF: An extension for Flask that integrates WTForms.
- Flask-CKEditor: An extension for Flask that integrates CKEditor.


## Acknowledgments

- The project is based on the lessons learned from the [Udemy course](https://www.udemy.com/course/100-days-of-code/) by Dr. Angela Yu.
