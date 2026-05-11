<div align="center">

# 🎟️ ScratchOff Tracker

### Lottery Scratch-Off Ticket Management System

A modern web app to track, manage, and analyze your scratch-off lottery tickets — scan tickets, log wins and losses, and view daily summaries.

[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-18.x-61DAFB?style=flat&logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?style=flat&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Supabase](https://img.shields.io/badge/Supabase-Backend-3ECF8E?style=flat&logo=supabase&logoColor=white)](https://supabase.com/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.x-06B6D4?style=flat&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

</div>

---

## 📖 Overview

**ScratchOff Tracker** is a full-stack web application that helps users track their scratch-off lottery tickets. Users can scan or manually log tickets, record wins and losses, set up ticket box configurations, and review their performance through daily summaries and history views.

Built with a React + TypeScript frontend and Supabase backend, the app provides a smooth, mobile-friendly experience for on-the-go ticket tracking.

---

## ✨ Features

- 🎟️ **Ticket Scanning** — Scan tickets via camera or manual entry to log results instantly
- - 📦 **Box Setup** — Configure and manage ticket boxes with pricing and type details
  - - 📊 **Daily Summary** — View a day-by-day breakdown of tickets scratched, wins, and net profit/loss
    - - 🔐 **Authentication** — Secure user accounts with password reset functionality
      - - 🗂️ **Ticket History** — Browse all past tickets logged with win/loss status
        - - 📱 **Mobile-Friendly** — Responsive design optimized for use on phones and tablets
          - - 🌙 **Dark / Light Mode** — Theme support via `next-themes`
            - - 🔔 **Toast Notifications** — Real-time feedback for actions
             
              - ---

              ## 🛠️ Tech Stack

              | Layer | Technology |
              |---|---|
              | **Frontend** | React 18, TypeScript, Vite |
              | **Styling** | Tailwind CSS, shadcn/ui, Radix UI |
              | **Backend / DB** | Supabase (PostgreSQL + Auth) |
              | **Forms** | React Hook Form + Zod |
              | **Routing** | React Router DOM v6 |
              | **Data Fetching** | TanStack React Query |
              | **Icons** | Lucide React |

              ---

              ## 📁 Project Structure

              ```
              scratchoff-tracker/
              ├── public/               # Static assets
              ├── src/
              │   ├── components/       # Reusable UI components
              │   ├── hooks/            # Custom React hooks
              │   ├── integrations/     # Supabase client & types
              │   ├── lib/              # Utility functions
              │   ├── pages/
              │   │   ├── Index.tsx         # Dashboard / home page
              │   │   ├── BoxSetup.tsx      # Ticket box configuration
              │   │   ├── ScanTickets.tsx   # Ticket scanning & logging
              │   │   ├── DailySummary.tsx  # Daily stats view
              │   │   ├── ResetPassword.tsx # Auth password reset
              │   │   └── NotFound.tsx
              │   └── types/            # TypeScript type definitions
              ├── supabase/             # DB migrations & config
              ├── .env                  # Environment variables (do not commit)
              └── vite.config.ts
              ```

              ---

              ## 🚀 Getting Started

              ### Prerequisites

              - [Node.js](https://nodejs.org/) v18+
              - - A [Supabase](https://supabase.com/) project
               
                - ### Installation
               
                - 1. **Clone the repository**
                 
                  2.    ```bash
                           git clone https://github.com/yakshil1701/scratchoff-tracker.git
                           cd scratchoff-tracker
                           ```

                        2. **Install dependencies**
                    
                        3.    ```bash
                                 npm install
                                 ```

                              3. **Set up environment variables**
                          
                              4.    Create a `.env` file in the root and fill in your Supabase credentials:
                          
                              5.   ```env
                                      VITE_SUPABASE_PROJECT_ID=your_supabase_project_id
                                      VITE_SUPABASE_PUBLISHABLE_KEY=your_supabase_publishable_key
                                      VITE_SUPABASE_URL=https://your_supabase_project_id.supabase.co
                                      ```

                                   4. **Run the development server**
                                
                                   5.    ```bash
                                            npm run dev
                                            ```

                                         5. Open [http://localhost:5173](http://localhost:5173) in your browser.
                                     
                                         6. ### Build for Production
                                     
                                         7. ```bash
                                            npm run build
                                            npm run preview
                                            ```

                                            ---

                                            ## ⚙️ Available Scripts

                                            | Script | Description |
                                            |---|---|
                                            | `npm run dev` | Start development server |
                                            | `npm run build` | Build for production |
                                            | `npm run preview` | Preview production build |
                                            | `npm run lint` | Run ESLint |

                                            ---

                                            ## 🗄️ Database

                                            This project uses **Supabase** for authentication and data storage. Migrations are in `/supabase`. Apply via the Supabase CLI:

                                            ```bash
                                            supabase db push
                                            ```

                                            ---

                                            ## 🤝 Contributing

                                            Contributions and suggestions are welcome! Feel free to open an issue or submit a pull request.

                                            ---

                                            ## 📄 License

                                            This project is for personal use. All rights reserved © [yakshil1701](https://github.com/yakshil1701).

                                            ---

                                            <div align="center">
                                              Made with ❤️ for smarter scratch-off tracking
                                            </div>div>
