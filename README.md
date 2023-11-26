# ShopMart React App

This project is a simple shopping cart application built with React and Vite.

## Table of Contents

- [Project Structure](#project-structure)
- [Demo](#demo)
- [Installation](#installation)
- [Routes](#routes)
- [Components](#components)
- [Context](#context)
- [Styling](#styling)

## Project Structure

The project is structured as follows:

- `src/`: Source code directory.
  - `components/`: React components.
  - `data/`: Data files, e.g., category list.
  - `assets/`: Images and other assets.
  - `App.jsx`: Main application component.
  - `routes.jsx`: Application routes.
  - `index.css`: Global styles.
- `public/`: Public directory for static assets.
- `index.jsx`: Entry point for rendering the React app.

## Demo

[Live Demo](https://shopmart-abhishek.netlify.app/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/abhipatel9607/shopmart_react.git
   ```

2. Change the repository:

   ```bash
   shopmart_react
   ```

3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Routes

-`/`: Main content page. -`/list/:list`: Category products page. -`/cart/:cartStatus`: Cart page. -`/detail/:category/:product`: Product detail page.

## Components

- `App`: Main application component.
- `AppHeader`: Header component with navigation and cart details.
- `MainContent`: Main content page component.
- `CategoryHeroSection`: Component displaying category hero images.
- `CategoryHero`: Hero image component for a specific category.
- `Button`: Reusable button component.
- `HeadingNavList`: Navigation list component for heading.

## Context

- `CartContext`: Context provider for managing the shopping cart state.

## Styling

Global styles are defined in index.css. Styling for components is done using local styles and CSS-in-JS.
