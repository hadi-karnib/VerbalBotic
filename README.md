<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

> A web app for empowering individuals with speech and communication challenges, providing accessible and personalized speech therapy at their fingertips.
>
> VerbalBotic aims to transform the traditional speech therapy experience by providing a user-friendly platform that adapts to each user's unique needs. We are dedicated to empowering our users by enhancing their ability to communicate more effectively, focusing on convenience, personalization, and measurable progress to ensure user satisfaction.

### User Stories

- As a user, I want to assess my speech capabilities through the app, so I can understand my areas of improvement.
- As a user, I want to track my progress over time, so I can see how much I have improved and stay motivated.

<!-- Tech stack -->
<img src="./readme/title3.svg"/>

### Empower Speech is built using the following technologies:

- This project uses the [React Native framework](https://reactnative.dev/), a cross-platform mobile development framework that allows us to develop the app for both iOS and Android using a single codebase.
  -For state management, the app utilizes [Redux](https://redux.js.org/), providing a predictable state container for managing application state, including user sessions, data, and notifications.
- For persistent storage (database), the app uses the [MongoDB](https://www.mongodb.com/) a NoSQL database that efficiently manages user data, speech therapy sessions, and progress tracking.
  -Speech analysis is powered by [FastAPI](https://fastapi.tiangolo.com/), a modern Python-based web framework, which integrates machine learning models to assess and provide personalized speech therapy feedback.
- 🚨 Node.js and Express.js are used to manage backend functionalities, including user authentication, session tracking, and interaction with the AI models for speech analysis.
- User audio files and other assets are stored in AWS S3, ensuring secure and scalable file storage for the application.

<br><br>
