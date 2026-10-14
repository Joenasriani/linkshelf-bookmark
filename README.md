# LinkShelf Bookmark

A React bookmark organizer built around visual shelves. The source provides a single component for creating shelves, saving links, searching bookmarks, and rearranging saved items.

## Implemented features

- Create and select bookmark shelves with emoji icons.
- Add, edit, and delete bookmarks with titles, URLs, and optional descriptions.
- Use site favicons, emoji icons, or uploaded images for bookmarks.
- Search saved links and display them in a responsive card grid.
- Drag and drop bookmarks to change their ordering.
- Store shelves and links in the browser's `localStorage` under `linkshelf-shelves` and `linkshelf-links`.

## Source and requirements

The repository currently contains **one file: `Index.html`**. Despite its extension, the file contains a React component written with JSX and ES module imports from `react` and `lucide-react`. It is not a complete HTML document or a ready-to-run standalone website.

To use it, place the component in an existing React project configured to compile JSX, install the React and Lucide React dependencies, and import/render the exported `LinkShelf` component. A complete runnable starter project, dependency manifest, and build configuration are **not included** in this repository.

## Limitations

- Bookmarks are stored locally in the current browser; there is no account system, cloud backup, or cross-device synchronization in the inspected source.
- Clearing browser site storage may erase saved shelves and bookmarks.
- Favicons use Google's favicon service and therefore may make external network requests. Links and custom icon URLs can also load external resources.
- The project has not been verified through a build, automated tests, or a deployment audit.
- The `Index.html` filename does not make the JSX component directly executable by opening it in a browser.

Credit: Joe Nasr

Portfolio: https://joe-nasr-signals.vercel.app/
