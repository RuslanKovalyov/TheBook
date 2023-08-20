# 📘 Contributing to TheBook.co.il

First and foremost, a heartfelt **thank you** for considering a contribution to TheBook.co.il. Every effort, big or small, helps make this platform an invaluable resource for all.

## 🚀 How Can I Contribute?

### 🐞 Reporting Bugs

- 🔍 **Ensure the bug was not already reported** by searching under [Issues](https://github.com/RuslanKovalyov/TheBook/issues).
  
- If you can't find an open issue addressing the problem, [open a new one](https://github.com/RuslanKovalyov/TheBook/issues/new). Please include a **descriptive title and detailed description**. Attach relevant data or code samples if possible.

### 💡 Suggesting Enhancements

- Simply open a new issue, detailing your idea, and possibly provide examples or further explanations.

### 📥 Pull Requests

1. 🍴 Fork the repo and create your branch from `master`.
2. If you've added code, consider writing tests for it.
3. Make sure tests (if any) pass.
4. Ensure your code respects our linting conventions.
5. Submit that pull request!

### 📚 Incorporating Texts

- Ensure the text is free of copyright issues or has necessary permissions.
  
- Always reference the source of the text.
  
- Strive for consistency in formatting and presentation with the existing resources on TheBook.co.il.

## 📖 Styleguides

### 📝 Git Commit Messages

- Use present tense ("Add feature" not "Added feature").
  
- Opt for the imperative mood ("Move cursor to..." not "Moves cursor to...").
  
- Keep the first line concise, ideally below 72 characters.
  
- Reference issues and pull requests after the first line when necessary.

### 🐍 Python Code Style

- Adherence to the [PEP 8](https://www.python.org/dev/peps/pep-0008/) style guide is appreciated.

### ❤️ Django Development Practices

- Django Initialization: Within TheBook repository, our Django backend is prominently initialized as Django. This distinct naming is designed for immediate framework identification, ensuring contributors can effortlessly discern the core backend structure. It's imperative to adhere to Django's best practices throughout the development process.

- App Naming Convention: Our main app is designated as app_main. This naming approach signals its primary role within the Django framework and sets a precedent for other apps' names. Adopting this convention aids in maintaining a consistent, intuitive structure as the project scales.

- Future-Ready Structure: We've architectured our repository with an eye on the future. The current structure facilitates easy integration of other potential frameworks, such as React, directly at the root level, underscoring our commitment to adaptability and embracing technological evolution.

- Models, Views, and Templates: Your contributions should have models, views, and templates that are organized and modular. While class-based views can enhance clarity, the emphasis should always be on creating concise and efficient views.

- Database Migrations: For any alterations to the database, ensure you create and thoroughly test migrations before submitting any pull request.

- Dependencies Management: Introducing new dependencies mandates an update to the requirements.txt file. Additionally, your pull request should contain a concise justification for the inclusion of the new dependency.

## 📌 Final Notes

Let's maintain a high standard for TheBook.co.il. Ensure your contributions are in line with our conventions and elevate the quality of content and code alike. Here's to building something great, together!
