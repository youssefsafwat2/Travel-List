# Travel Packing List App

This is a simple travel packing list application built with React. The app allows users to manage their packing list by adding, toggling, deleting items, and clearing the entire list.

## Features

- **Add Items**: Users can add items to their packing list.
- **Toggle Items**: Users can mark items as packed/unpacked.
- **Delete Items**: Users can remove individual items from the list.
- **Clear List**: Users can clear the entire packing list with confirmation.

## Components

The application is built using the following components:

1. **App**: The main component that manages the state of the packing list and renders other components.
2. **Logo**: Displays the logo of the application.
3. **Form**: Allows users to input and submit new items to the packing list.
4. **PackingList**: Displays the list of items, with options to toggle, delete, or clear the list.
5. **Stats**: Displays statistics about the packing list, such as the total number of items and how many are packed.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/youssefsafwat2/Travel-List.git
   ```

2. Navigate to the project directory:

   ```bash
   cd travel-packing-list
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run start
   ```

The application will be available at `http://localhost:3000`.

## Usage

1. Enter the name of the item you want to add to your packing list.
2. Click "Add" to add the item to the list.
3. Click the checkbox next to an item to mark it as packed/unpacked.
4. To delete an item, click the delete button (trash icon) next to the item.
5. To clear the entire list, click "Clear List", then confirm the action in the popup.

## Technologies Used

- **React**: For building the UI and managing the component state.
- **JavaScript (ES6+)**: For writing the application logic.
- **CSS**: For styling the application.
