# Let's Schedule
Let’s Schedule is a smart scheduling mobile application that helps people effectively manage their schedules. The app features automated task scheduling, which can generate a schedule for people based on the priorities of the given tasks and the expected time each task takes up given the user’s existing schedule.

Scheduling apps primarily rely on the user coming up with all of the tasks they need to complete, estimating the duration and priority of each task, and finding the appropriate time slots for these tasks in their schedule. This requires a lot of time and decision-making. Automating a part of this process will reduce the effort required by users to plan their day so that they can use this energy instead to complete what they need to do. Let’s Schedule is for users who want to waste less time planning their day.

## Build Instructions

- **Backend:**
    - install ruby and neccessary gems
    - set up database by running command line instruction `$ rails db:schema:load`
- **Frontend:**
    - Follow instructions on the [React Native website](https://reactnative.dev/docs/environment-setup) to set up the CLI (*not* Expo) for Android development.
    - Run `npm install` to install dependencies

## Test Instructions
- **Backend:** from the project repository, run the command line instruction `$ rails
  test` to test the entire framework. 

  Alternatively, can test a specific test case with an optional route.

  Example: to test only `user_controller` behavior, run `$ rails test
  test/controllers/user_controller`
- **Frontend:** Run `npm test` in the project repo

## Run Instructions

- **Backend:** Start a server with the command `$ rails server` and begin sending HTTP
  requests to specified port
- **Frontend:** Launch an Android emulator or connect a device, then run `npx react-native start` to start the Metro server. Once it is started, type `a` to install the app on the connected Android device. For information on how to use the app, see [the wiki](https://github.com/lets-schedule/lets-schedule-frontend/wiki).

## Functional operational use cases
- **Backend:**
    - Create User
    - Delete User
    - Get a specific User
    - Create Task
    - Delete Task
    - Get a specific Task
    - Create Event
    - Delete Event
    - Get a specific Task
- **Frontend:**
    - Creating new events
    - Modifying events
    - Creating new tasks
    - Auto-scheduling tasks on calendar (must press "Done")
    - Deleting tasks

