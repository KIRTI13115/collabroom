# collabroom
Web Based Mini Project 

Team Members 
1. Kirti Gupta
2. Dolly Kushwaha
3. Titiksha
4. Vaishnavi Batham
5. Komal
   
Using Next.js and Typescript, this project focuses on building video conferencing web app. It enables users to securely log in, create meetings and access various meeting functionalities such as recording, screen sharing, and managing participants.

Tech Stack 
1. Next.js
2. TypeScript
3. Clerk
4. getstream
5. shadcn
6. Tailwind CSS

Features
The web app will comprise of following features:
1. Authentication 
2. New meeting 
3. Meeting controls
4. Exit meeting
5. Schedule Future meetings
6. Join meetings via link
7. Secure real time functionality
8. Responsive Design
git fetch upstream

##  How to Run the Project Locally

Follow the steps below to set up and run the project on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install Dependencies

Make sure you have **Node.js (v18 or above)** installed.

```bash
npm install
```

### 3. Setup Environment Variables

Create a `.env.local` file in the root directory and add the following:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
CLERK_SECRET_KEY=your_secret_key

NEXT_PUBLIC_STREAM_API_KEY=your_stream_key
STREAM_SECRET_KEY=your_stream_secret
```

### 4. Run the Development Server

```bash
npm run dev
```

### 5. Open in Browser

Go to:

```
http://localhost:3000
```

---

