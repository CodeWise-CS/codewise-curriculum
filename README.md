# CodeWise Curriculum

Welcome to the **CodeWise** curriculum repository! This repository hosts the learning materials, including videos, quizzes, courses, and career path data, designed to help users learn coding and advance their careers in technology.

## **About CodeWise**

CodeWise is a platform dedicated to empowering learners with accessible and comprehensive coding education. Whether you're a beginner starting from scratch or a professional looking to upskill, CodeWise offers content tailored to your learning goals.

This is kept **free** due to the open-source nature of our curriculum. Each topic in a course consists of various tutorial options, code compilation, and quizzes.

## **Curriculum Contents**

### 1. **Courses**
   - **Overview**: Structured courses, each consisting of multiple modules with videos, exercises, and quizzes.
   - **Location** `courses/[course name]` folder

### 2. **Videos**
   - **Overview**: Engaging and instructional video content covering a wide range of topics, from beginner tutorials to advanced concepts.
   - **Format**: Public YouTube tutorial video ID with start time, end time, length, channel, and title

### 3. **Quizzes**
   - **Overview**: Interactive quizzes to test your knowledge and reinforce learning after each lesson.
   - **Format**: JSON-based data for integration with the website.

### 4. **Career Paths**
   - **Overview**: Collections of courses relating to a specific career path.
   - **Format**: JSON array consisting of course names
   - **Location**: `career-paths/` folder.

## 🚀 **Getting Started**

1. **Fork the repository**
2. **Clone the repository**  
   ```bash
   git clone https://github.com/YOUR-USERNAME/codewise-curriculum.git
   cd codewise-curriculum
   ```
3. **Explore the files**
Navigate through the folders to find relevant materials:

1. `courses/`
2. `career-paths/`

3. **Contribute to CodeWise**
Create a new `.json` file in the appropriate directory and put all the necessary information.

The planned curriculum is listed in the courses' `curriculum.md` file. It organizes the topics that will be covered and their order (lessons that have not been created may be listed here).

Course lesson format (consisting of a lesson and exercise):
```js
[
  {
    "lessonName": /* lesson's name */,
    "type": "lesson",
    "videos": [
      {
        "name": /* video name */,
        "channel": /* channel */,
        "length": /* video length formatted as MM:SS */,
        "id": /* YouTube video ID (e.g., "x7X9w_GIm1s" for https://www.youtube.com/watch?v=**x7X9w_GIm1s**) */,
        "startSeconds": /* seconds at which the video should start (null if N/A) */,
        "endSeconds": /* seconds at which the video should end (null if N/A) */
      },
      ... /* other video options. 1st video in array should be the "recommended" video */
    ],
    "exercises": [
      {
        "title": /* exercise title */,
        "content": /* description of the exercises with examples. E.g., "Write a program that greets a user named John Doe with the message \"Hello, John Doe!\"\n\nThen, try greeting yourself by changing the name." */
      },
      ... /* other exercise options */
    ]
  },
  {
    "lessonName": "[lesson's name] - Exercise",
    "type": "exercise",
    "questions": [
      {
        "type": "fill_in",
        "question": /* question */,
        "text": /* answer text with blanks surrounded by "<@>" (e.g., "for i in <@>range<@>(12)") */
      },
      {
        "type": "multiple_choice",
        "question": /* question */,
        "answers": [
        {
          "answer": /* correct answer option */,
          "correct": true
        },
        {
          "answer": /* incorrect answer option */,
          "correct": false
        },
        {
          "answer": /* incorrect answer option */,
          "correct": false
        },
        {
          "answer": /* incorrect answer option */,
          "correct": false
      },
      /* ... any combination of question types */
    ]
  },
]
```

Career path format:
``` js
{
   /* course name (e.g., "frontend-engineer") */: {
    "title": /* course title (e.g., "Front-end Engineer") */,
    "courses": /* array of courses (e.g., "html-css", "javascript", "react", ...) */
  }
}
```

## 🤝 **Contributing**

We welcome contributions from the community! If you have ideas for new materials, improvements, or fixes, check out our [contribution guidelines](/CONTRIBUTING.md).

## 📧 **Contact**

For questions or support, reach out to: iacopo.schianchi@gmail.com

## **License**

This project is licensed under the MIT License. Feel free to use and adapt the materials as needed.

Welcome to CodeWise!
