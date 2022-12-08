# React: Slideshow App

Create a basic slideshow application, as shown below. Application requirements are given below, and the finished application must pass all of the unit tests.

![slideshowApp](https://user-images.githubusercontent.com/45912339/206393914-5d6525ec-f8de-42f4-9da4-4965cd68042c.gif)

Your task is to complete the implementation of ```src/Slides.tsx``` and ```src/components/Slides.tsx``` according to the following requirements.

- The Slides component takes an array of slides as a prop. Each element of this array denotes a single slide and is an object with 2 properties: string title and string text.
- On application launch, the first slide must be rendered.
- Clicking on the "Next" button shows the next slide. This button is disabled when the current slide is the last one.
- Clicking on the "Prev" button shows the previous slide. This button is disabled when the current slide is the first one.
- Clicking on the "Restart" button returns to the first slide. This button is disabled when the current slide is the first one.
- You can assume that the passed slides array contains at least one slide.
