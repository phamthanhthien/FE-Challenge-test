# ReactJS Sorting Articles

Create a basic article sorting application, as shown below. Some core functionalities have already been implemented, but the application is not complete. Application requirements are given below, and the finished application must pass all of the unit tests.

![sortingArticles](https://user-images.githubusercontent.com/45912339/206392743-cf42cac9-424d-4704-b4c6-f1f367cb3efd.gif)

The app has one component named Articles. The list of articles to be displayed is already provided in the app.

The app must have the following functionalities:

- The list of articles is passed to the App component as a prop in the form of an array of objects.
- Each article has the following three properties:
  - title: The title of the article [STRING].
  - upvotes: The number of upvotes for an article [NUMBER].
  - date: The publish date for the article in the format YYYY-MM-DD [STRING].
- By default, the articles should be displayed in the table ordered by the number of upvotes in descending order.
- Clicking on the "Most Upvoted" button should reorder and display the articles by the number of upvotes in descending order.
- Clicking on the "Most Recent" button should reorder and display the articles by date in descending order.
- You can assume that each article has a unique publish date and number of upvotes.

Your task is to complete the implementation of ```src/Articles.tsx``` and ```src/components/Articles.tsx```.
