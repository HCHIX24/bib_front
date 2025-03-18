# Biblioteca CHIX

Welcome to **Biblioteca CHIX**, a library management system that allows users to browse books and borrow them with ease. This is the frontend for the Biblioteca CHIX project.

## Features

- **Carousel Section**: Displays a dynamic carousel showcasing books available in the library.
- **User & Book Dropdowns**: Select a user and a book to borrow, with loan duration options.
- **Borrow and Return Book Buttons**: Allows users to borrow or return books with ease.
- **Book Collection**: View a collection of books with their details and a "Borrow" button for each.
- **Responsive Design**: Built with Bootstrap, the layout is fully responsive for mobile and desktop views.

## Technologies Used

- **HTML5**: Structure of the webpage.
- **CSS (Bootstrap 5)**: Styling and layout of the page.
- **JavaScript (Axios)**: For making HTTP requests and dynamic page updates.
- **Bootstrap**: For responsive, grid-based design and pre-built UI components.
  
## Project Structure

The project is organized as follows:

/backend /static /css - style.css # Custom styles for the frontend /js - script.js # JavaScript to handle dynamic content /images - [Various Book Cover Images] # Book images used in the carousel and cards index.html # Main HTML file for the project

## How to Run the Project

1. Clone the repository to your local machine:
git clone https://github.com/yourusername/biblioteca-chix.git

2. Open `index.html` in your browser.

3. The page should load with a carousel of book covers and options to select a user, book, and loan type.

## How It Works

1. **Book Carousel**: Displays book covers with `carousel` functionality. The user can navigate through book images.

2. **Book Selection**: Users can select a book from the dropdown, with options for different loan durations:
- **Short (1-2 days)**
- **Medium (3-5 days)**
- **Long (6-10 days)**

3. **Borrow and Return Buttons**: 
- The "Borrow Book" button will allow the user to borrow a book.
- The "Return Book" button allows the user to return a previously borrowed book.

4. **Book Cards**: A collection of books, with each card showing a book cover, title, description, and a "Borrow" button.

## Customizing the Project

You can customize the following files:

- **`images/`**: Add your own book cover images.
- **`style.css`**: Modify the styles to match your branding.
- **`script.js`**: Add more interactivity or additional API calls.

## Future Improvements

- Implement backend functionality to allow real-time borrowing and returning of books.
- Add user authentication and management for a fully functional library system.
- Enhance book details with ratings, reviews, and more.


