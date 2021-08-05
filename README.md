# seb-movies

This website is deployed using vercel: https://seb-movies.vercel.app/

This project is a website for browsing movies. It is based on Hulu. The project uses the React library with the Next.js framework. Tailwind CSS is used to style the application. The JIT compiler to help performance. The application's data is obtained from the The Movie Database API, providing movie posters, titles, descriptions, ratings etc. The application requests the movie objects to display them on the page.

The header component contains the website logo, and 6 buttons which show a label, color-change and animation when hovered over.

The navigation component contains all movie genres, which have a color-change and size-increase when hovered over, and a color change when clicked. The navigation bar also contains a side-scroll for the genres that cannot fit on the screen. When clicked, the URL will change, and a new request to the API will be performed. Only the movies associated with the clicked genre will be displayed in the results feed.

The results component displays the movies. The movies displayed depends on the API request, which depends on the page URL extension, which in turn depends on the genre clicked in the navigation bar.

There is lazy loading built-in with Next.js, which helps performance as only the pictures that are needed are loaded.
The Just-in-time compiler is used to render only what's needed in order to improve performance and user experience.




