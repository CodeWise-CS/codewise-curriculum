# Contributing to the CodeWise Curriculum

There are many ways you can help out CodeWise. Our curriculum is essential to create an engaging and effective learning experience for our users.

## ✏️ Editing Curriculums

Our curriculums are a work-in-progress. Any new lesson ideas, reordering, or lesson removals you see fit are great to get started contributing!

Start by:
1. Finding your issue and search for the course's `curriculum.md` file.
2. Creating an issue for the requested change using the correct "Curriculum Change" template.
3. Filling out the issue describing the requested change.
4. Your issue will be reviewed. Once someone is assigned to it, they may create a PR for their change.

## ✏️ Editing Lessons

Some of the lessons that are created will eventually need to be edited or improved. If you wish to add or remove a video, exercise, or question from a particular lesson, follow these steps:

1. Locate the desired lesson within the course's directory.
2. Describe the changes in an issue using the "Lesson Change" template.
3. Once your issue is approved, you may create a PR changing the JSON file for the lesson you wish to edit.

## ➕ Creating Courses

If there is a course you would like to add that is missing from CodeWise, you can create it! However, before you can do this, you must discuss this in our [Discord server's](https://discord.gg/XcUEkuecSb) "new-courses" channel by creating a post. Once it is approved by a moderator, you may proceed with these steps:

1. Create an issue using the "New Course" template. You must also link your approved post on Discord so that we know it has been approved.
2. Once you or someone else has been assigned to the issue, you can create the new directory for the course.
3. Within the directory, create a `curriculum.md` file with at least the first 10 planned lessons.
4. If you want to make some of the lessons within your `curriculum.md`, you will need to create a new issue following the instructions for creating lessons described below.

## ➕ Creating Career Paths

If there is a career path you would like to add that is missing from CodeWise, you can create it! However, before you can do this, you also must discuss this in our [Discord server's](https://discord.gg/XcUEkuecSb) "new-career-paths" channel by creating a post. Once it is approved by a moderator, you may proceed with these steps:

1. Before the career path can be created, all courses within it must first be created.
2. Create issues for your new courses using the instructions above. **You may link it to the approved career path discussion** (you do not need to post in the "new-courses" channel to be approved).
4. Once all courses have been created, make an issue using the "New Career Path" template. You must also link your approved post on Discord so that we know it has been approved.
5. Once you or someone else has been assigned to the issue, you can create the file in the `/career-paths` directory
6. Within the file, include the information as described in the [README.md](/README.md)

## ➕ Creating Lessons

You may also help us out by adding lessons from the curriculum that have not been added yet. Lessons must be created in order based on what is missing in the curriculum.

**You may only create lessons that are in the curriculum.** If you want to create a new lesson, you must follow the instructions for editing the curriculum first.

Start by:
1. Finding the course you want to create a lesson for and reviewing its `curriculum.md` file.
2. Choose the lesson to complete; the first unchecked lesson has the priority. If someone else has already created an issue regarding that lesson, you may start working on a future lesson. However, **your PR will only be approved once all previous lessons have been completed.**
3. _Thoroughly check_ that your lesson has not been created in an existing PR or already has an issue.
4. Create an issue using the correct "New Lesson" template. You will list the title, videos, exercises, and questions.
5. Once your project is assigned to someone (or yourself), you can create a PR for it.
6. **Make your lesson:** add the JSON file to the correct course directory with the information for your lesson. Remember to check your lesson's name in the `curriculum.md` by changing "- [ ]" to "- [x]"

## Making your first PR

Great! You have followed the steps above and are ready to make a change to our curriculum. If you want to make the changes described in your issue, you should check the "do myself" checkbox in the issue's template. That will let us know that we should assign the issue to you. Otherwise, leave it unchecked and we will assign it to someone who volunteers.

Now, you need to make your changes and create a PR. You should use the given PR template information and give a detailed description of what your PR is for. You will also need to list the issues your PR solves. If you are making a PR for your own issue, simply add your issue's number.
