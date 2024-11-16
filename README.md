# Foodista

Foodista is a modern food ordering website built using **Next.js** (v13.1.1). This project showcases a fully responsive, server-side rendered application that allows users to browse, filter, and view detailed information about a variety of dishes. The backend is hosted on **Vercel**, providing seamless integration for fetching dynamic content.

## Features

### 🛠 Core Features

- **Menu Display**: Users can view a list of dishes, each represented by a visually appealing card with key details like price, discount, and type of cuisine.
- **Detailed Pages**: Each dish has a dedicated page providing details like ingredients, preparation methods, and recipes.
- **Category Filters**: Users can filter foods by difficulty and cooking time through dynamic queries, applied both client- and server-side.
- **Responsive Design**: The website adapts seamlessly to various screen sizes, offering a great user experience on all devices.

### 💻 Technologies Used

- **Frontend**: Next.js (React framework) with CSS Modules for styling.
- **Backend**: Hosted API on Vercel, delivering structured JSON data.
- **Dynamic Routing**: Implemented with `getStaticPaths` and `getStaticProps` for optimized performance.
- **Server-Side Filtering**: Integrated filters for categories through `getServerSideProps`.
- **Conventional Commits**: Maintained strict commit message guidelines for clean and understandable version control.

## Demo

You can view the live demo of the project here:

[Foodista Demo](https://foodista-app.vercel.app)

## Installation

To run this project locally, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/matador7495/Foodista-App.git

#Navigate to the project directory

cd foodista
```

### 2. Install dependencies

Make sure you have Node.js installed, then run the following command:

```bash
npm install
```

### 3. Set up environment variables

Create a .env file in the root directory with the following content:

```bash
BASE_URL=https://foodista-api-iota.vercel.app
REVALIDATE=10
```

### 4. Run the application locally

```bash
npm run dev
```

The app should now be running at http://localhost:xxxx.

## Project Structure

```bash
foodista/
├── components/
│   ├── icons/                  # SVG components for icons
│   ├── layout/                 # Layout components like Header, Footer, etc.
│   ├── modules/                # Reusable components like Card, Filters, etc.
│   ├── templates/              # Page-level components (MenuPage, DetailsPage, etc.)
├── pages/
│   ├── menu/                   # Dynamic route for menu items
│   ├── categories/             # Filters and category-related pages
│   └── index.js                # Homepage
├── public/                     # Static assets (images, icons, etc.)
├── styles/                     # Global styles
```

## License

This project is open-source and available under the [MIT License](./LICENSE).

## Acknowledgments

- Inspired by modern food delivery platforms like Uber Eats and Lovefood.
- Special thanks to **Vercel** for providing seamless deployment solutions.
