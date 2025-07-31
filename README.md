# 📰 Angular Infinite Scroll Post List

This is a simple Angular 19 project that fetches posts from a mock API (`jsonplaceholder.typicode.com`) and displays them with infinite scrolling. It demonstrates standalone component architecture, API integration, loading/error state handling, and responsive post rendering.

---

## 🔧 What I Built

I developed an *Infinite Scroll Post List* app with the following features:

- Standalone component architecture in Angular 19  
- Pagination with infinite scroll on window scroll  
- Async API data fetch using Angular HttpClient  
- Reusable post card component  
- Handles loading and error states  
- Random avatar image generation with `picsum.photos`  
- Clean and responsive UI with SCSS  

---

## 💡 Key Features

- 🧠 Asynchronous post fetching using Angular `HttpClient`
- 🔁 Reusable `PostService` for data communication
- 🧩 Modular `PostComponent` for displaying each post
- ⏳ Scroll-based pagination using `@HostListener`
- 📷 Random profile photos using `https://picsum.photos`
- ⚠️ Graceful error handling and loading spinner

---

## 🧱 Technologies Used

- **Angular 19**
- **TypeScript**
- **HTML & SCSS**
- **Standalone Components**
- **HttpClientModule**
- **RxJS**

---

## 📁 Project Structure

```plaintext
src/
├── app/
│   └── components/
│       ├── post-list/
│       │   ├── post-list.component.ts       # Fetch logic, scroll listener
│       │   ├── post-list.component.html     # Loop through posts + loading/error
│       │   ├── post-list.component.scss     # Post list styling
│       └── post/
│           ├── post.component.ts            # Displays single post and avatar
│           ├── post.component.html          # Post card layout
│           ├── post.component.scss          # Post card styling
│
├── services/
│   └── post.service.ts                       # HTTP request with pagination

```
## 🔗 Preview

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Click%20Here-blue?style=for-the-badge)](https://ahmad-889.github.io/infinite-scroll/)


---

## 🚀 Running the Project

To start the development server, run:

```bash
npm install
ng serve

```
