# Twitter Follow Card

This is a simple React application that displays a list of Twitter users along with their profile information and a follow/unfollow button.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ZekeScript/repository-name.git
   ```

2. Install the dependencies:

   ```bash
   cd repository-name
   npm install
   ```

3. Start the application:

   ```bash
   npm start
   ```

4. Open your web browser and visit `http://localhost:3000` to see the application in action.

## Usage

The application renders a list of Twitter users and their corresponding follow cards based on the data provided in the `users` array. Each follow card displays the user's avatar, name, username, and a follow/unfollow button.

You can modify the user data by editing the `users` array in the `App.js` file. The `users` array contains objects with the following properties:

- `userName`: The Twitter username of the user.
- `name`: The user's full name.
- `isFollowing`: A boolean value indicating whether the user is currently being followed or not.

By default, the application renders three follow cards with example user data. You can add or remove users by modifying the `users` array accordingly.

## Screenshots

![image](https://github.com/ZekeScript/twitter-follow-card/assets/57415369/bb5fddf4-9d71-4ac5-9c4a-9b3a1aca5e21)
![image](https://github.com/ZekeScript/twitter-follow-card/assets/57415369/c0f76ace-b8bb-4ea5-9b07-1b15dc5d0435)

## Component: TwitterFollowCard

The `TwitterFollowCard` component is responsible for rendering an individual follow card. It receives the following props:

- `userName`: The Twitter username of the user.
- `initialIsFollowing`: A boolean value indicating whether the user is initially being followed or not.

The follow card displays the user's avatar, name, username, and a follow/unfollow button. Clicking the button toggles the follow status of the user.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This application uses the [unavatar.io](https://unavatar.io) service to fetch user avatars based on their usernames.
