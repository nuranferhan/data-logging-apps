This repository contains **Python** codes for managing and storing different types of content such as *music, books, games, films *and* series.* Each application provides a user-friendly interface that allows users to add, update, delete, and sort data based on various criteria like title, genre, and status. The data is saved in JSON format, enabling users to load, save, and track their desired data. Whether you're managing a collection of books, games, music, or films and TV shows, these applications simplify media organization and analysis by offering features like search, sorting, and statistics.

One of the zip files contains the following content.
######  `film and series.zip: `
# Film and TV Show Tracking Application

This application allows users to manage a list of films and TV shows they are watching or planning to watch. It provides an interface for adding, updating, deleting, and filtering items based on various criteria such as title, genre, status, rating, theme, and description.

## Features

- **Add, Update, and Delete**: Users can add new films or TV shows, update existing entries, or delete items from the list.
- **Search and Filter**: Users can search for films/TV shows by title and filter them by type (Film, TV Show, or All Types).
- **Sorting**: The list can be sorted by columns such as name, type, status, and rating.
- **Save and Load Data**: The data is saved in a JSON file and can be loaded back when the application is reopened.
- **Background Image**: The app uses a background image that resizes with the window.
- **Statistics**: The app provides statistics on the total number of items, and the count of films and TV shows.
  
## Requirements

- Python 3.x
- `tkinter` for the GUI
- `Pillow` for handling images

You can install the necessary dependencies using pip:

```
pip install pillow
```

## Usage

1. **Run the application**: Execute the Python script to open the GUI.
2. **Add Items**: Fill out the form with the title, type (Film/TV Show), status (Watched/To Watch/Waiting), rating (1-5), theme, and description, then click the "Add" button.
3. **Update Items**: Select an item from the list and modify its details, then click the "Update" button.
4. **Delete Items**: Select an item from the list and click the "Delete" button to remove it.
5. **Search and Filter**: Use the search bar to filter by title and select a genre to filter by type.
6. **Save Data**: Click the "Save" button to save your changes to a JSON file.
7. **View Statistics**: Click the "Analyze" button to view the total number of items, films, and TV shows.

## File Structure

- `filmler_diziler.json`: The file where the list of films and TV shows is saved.

## License

This project is open-source and available under the MIT License.

