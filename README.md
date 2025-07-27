# Learn Pinia Vue 3 State Management in 10 Minutes

A minimal Vue 3 + Pinia application demonstrating state management concepts through a simple counter example.

## What You'll Learn

- Setting up Pinia with Vue 3
- Creating stores with the Composition API
- State, getters, and actions
- Sharing state between components

## Project Structure

src/
├── components/
│ ├── AComponent.vue # Component using Pinia store
│ └── BComponent.vue # Another component sharing the same state
├── stores/
│ └── counter.js # Pinia store with state, getters, actions
├── App.vue # Main app component
└── main.js # App entry point with Pinia setup


## Technologies Used

- **Vue 3** - Progressive JavaScript framework
- **Pinia** - Vue state management library
- **Vite** - Fast build tool and dev server

## Quick Start

```sh
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
