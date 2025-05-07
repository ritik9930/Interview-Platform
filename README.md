<h1 align="center"><b>✨ CODENEXUS - Interview Platform ✨</b></h1>

![Demo App](/public/image.png)

## Features:

- [x] 🚀 **Tech stack:** Next.js & TypeScript, Stream, Convex, Clerk
- [x] 🎥 **Video Calls**
- [x] 🖥️ **Screen Sharing**
- [x] 🎬 **Screen Recording**
- [x] 🔒 **Authentication & Authorization**
- [x] 💻 **Server Components, Layouts, Server Actions**
- [x] 🎭 **Client & Server Components**
- [x] 🛣️ **Dynamic & Static Routes**
- [x] 🎨 **Styling with Tailwind & Shadcn UI**
- [x] ✨ **Server Actions**

## High-Level Architecture
- Frontend: Built using Next.js and TypeScript, providing a responsive and intuitive user interface.
- Backend: Handles server-side logic, user authentication, and video call functionalities.
- Database: Uses Convex for storing user data, interview details, and video call records.
- Video Communication: Utilizes Stream for real-time video calls, screen sharing, and recording.

## Core Components
- User Authentication: Managed by Clerk, ensuring secure login and role-based access control.
- Video Calls: High-quality, real-time video communication with features like screen sharing and recording.
- Interview Management: Allows scheduling, conducting, and recording interviews.
- User Interface: Styled with Tailwind CSS and Shadcn for a modern and responsive design.

## Workflow Steps
### 1. User Registration and Login:
  - Users sign up or log in using Clerk.
  - User roles (interviewer or candidate) are assigned.

### 2. Scheduling Interviews:
  - Interviewers can schedule interviews, specifying date, time, and participants.
  - Notifications are sent to participants.

### 3. Conducting Interviews:
  - Participants join the video call using Stream.
  - Features like screen sharing and recording are available during the call.

### 4. Storing Interview Data:
  - Interview details and recordings are stored in the Convex database.
  - Metadata (e.g., interview date, participants) is linked to the recordings.

### 5. Reviewing Interviews:
  - Interviewers can review recorded interviews.
  - Feedback and notes can be added to each interview record.

## Optimization Techniques
- **Server-Side Rendering:** Enhances performance by rendering content on the server.
- **Dynamic and Static Routes:** Optimizes navigation and improves user experience.
- **Caching:** Reduces load times by storing frequently accessed data in memory.
- **Rate Limiting:** Prevents abuse by controlling the number of requests a user can make.

## Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

## Run the app

```shell
npm run dev
```
## Credentials 🔐

### For Using Admin Dashboard use these credentials 
```shell
Email: test@gmail.com
Password: David@954
```

## ⚠ Disclaimer
This tool is developed for educational and developmental purposes. It's crucial to understand the implications and responsibilities of using such technologies in real-world applications.


## Still need help?
Open an issue on our GitHub repository, and we will help you as soon as possible.

Enjoy exploring and extending this project! Feel free to contribute and suggest improvements.

## Contact

If you want to contact me you can reach me at [Twitter](https://x.com/SandhitK).

## Developer
<table>
    <tr align="center">
        <td>
        Sandhit Karmakar
        <p align="center">
            <img src = "https://avatars.githubusercontent.com/u/90787826?v=4" width="150" height="150" alt="Dhruv Shah">
        </p>
            <p align="center">
                <a href = "https://github.com/Sandhit06">
                    <img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36" alt="GitHub"/>
                </a>
                <a href = "https://www.linkedin.com/in/sandhit-karmakar/" target="_blank">
                    <img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36" alt="LinkedIn"/>
                </a>
                <a href = "mailto:sandhitkarmakar@gmail.com" target="_blank">
                    <img src = "https://www.iconninja.com/files/312/807/734/share-send-email-chat-circle-message-mail-icon.svg" width="36" height="36" alt="Email"/>
                </a>
            </p>
        </td>
    </tr>
</table>

<p align="center">
    Made with ❤️ by <a href="https://github.com/Sandhit06">Sandhit Karmakar</a>
</p>
