## <a name="tech-stack">Tech Stack</a>

- Next.js
- TypeScript
- Clerk
- getstream
- shadcn
- Tailwind CSS

## <a name="features">Features</a>

**Authentication**: Implemented authentication and authorization features using Clerk, enabling secure user logins via social sign-on or traditional email and password methods, ensuring granular access control.

**New Meeting**: Initiated new meetings swiftly, configuring camera and microphone settings beforehand for seamless join-in.

**Meeting Controls**: Empowered participants with comprehensive meeting controls, including recording, emoji reactions, screen sharing, muting/unmuting, sound adjustments, grid layout, participant list view, and individual management (pinning, muting, unmuting, blocking, video share permissions).

**Exit Meeting**: Managed meeting closures, allowing participants to leave or creators to end sessions for all attendees.

**Schedule Future Meetings**: Scheduled upcoming meetings with specified date and time, accessible via the 'Upcoming Meetings' page for easy sharing or immediate access.

**Past Meetings List**: Provided access to detailed logs of previous meetings, including metadata for reference.

**View Recorded Meetings**: Enabled viewing of recorded meeting sessions for review or archival purposes.

**Personal Room**: Established personalized meeting rooms with unique links for instant gatherings, shareable among participants.

**Join Meetings via Link**: Facilitated easy access to others' meetings through shared links.

**Secure Real-time Functionality**: Ensured all platform interactions were secure and real-time, safeguarding user privacy and data integrity.

**Responsive Design**: Implemented responsive design principles for optimal user experience across diverse devices, seamlessly adapting to varying screen sizes and resolutions.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/MuhammadHunainKhurram/video-conference-app.git
cd zoom-clone
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

Replace the placeholder values with your actual Clerk & getstream credentials. You can obtain these credentials by signing up on the [Clerk website](https://clerk.com/) and [getstream website](https://getstream.io/)

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
