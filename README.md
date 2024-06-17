## ZOOM-CLONE using NEXT JS


- This is a intermediate Zoom-Clone made by using next js and the tech stack below . I used Cleck for safe user auth and Stream api keys for video conferencing functionalities.The project also uses Shadcn for advance animations and components . 

  
## TECH-STACK

- Next.js
- TypeScript
- Clerk
- getstream
- shadcn
- Tailwind CSS

## FEATURES


- Authentication : using cleak

- Schedule Future Meetings

- Basic Meeting controls  : Recording , End meeting , Audio controls , Video controls

- Past Meetings list and can also view recodings of past meetings

- Join Meetings via Invite Link

- Personal Room for Private Meetings
  

## Installation


- To install use the following commands

  -Clone the repo
  
  ```
    git clone https://github.com/adrianhajdin/zoom-clone.git
    cd zoom-clone
  ```
  - Then install all the node modules required
    
  ```
    npm install
  ```

  - Create a new .env or .env.local file
  
    ```
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=
    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
    NEXT_PUBLIC_STREAM_API_KEY=
    STREAM_SECRET_KEY=
    ```

  - Run the server 
  ```
    npm run dev
  ```

-![image](https://github.com/adiboy-23/nextjs-zoom/assets/123615666/296f2b2d-5b6b-4729-8866-b6e8338a64fb)

- ![image](https://github.com/adiboy-23/nextjs-zoom/assets/123615666/d2efba7f-f883-4d95-aee3-0770f6129a9e)


