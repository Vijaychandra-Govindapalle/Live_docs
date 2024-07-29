# Live Docs

## Live Docs is a live collaborative document manager and editer that allows you to collaboratively edit and manage a document in real time.

### Features 
- Multiple users can create, edit, and delete documents they own.
- Users can share their documents and set permissions for other users.
- Users can add inline and general comments, with threading for discussions.
- Notify users of document shares, new comments, and collaborator activities.
- Show active collaborators with real-time presence indicators.

Checkout the app [here](https://live-docs-drab.vercel.app/)

### Techstack 
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF.svg?style=for-the-badge&logo=Clerk&logoColor=white)


[Liveblocks](https://liveblocks.io/)




### Quick start
#### Prerequisites

Make sure you have the following installed on your machine:
- [Git](https://git-scm.com/)
- [Node](https://nodejs.org/en/blog/announcements/v18-release-announce/#fetch-experimental)
- [npm](https://www.npmjs.com/)

#### Cloning the Repository
```
https://github.com/Vijaychandra-Govindapalle/Live_docs.git
cd Live_docs
```
#### Installation
```
npm install
```

#### Set Up Environment Variables

Create a new file named .env in the root of your project and add the following content:

```
#Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

#Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```
Replace the placeholder values with your actual Clerk & LiveBlocks credentials. You can obtain these credentials by signing up on the [clerk](/https://clerk.com/) and [liveblocks](https://liveblocks.io/).

#### Running the Project
```
npm run dev
```



