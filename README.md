# cc-crash-course

Let's build a web app to manage online activities for our LEAD FORWARD members using **InstantDB** as the backend.

Help me think through how to break this into iterative pieces and write a plan.md.

## Functional Requirements:

### 1. Authentication
- Login with Google OAuth (via InstantDB Auth)
- InstantDB handles auth tokens and session management

### 2. Single Activity Feed
- One main feed showing all posts chronologically
- View post title, author, timestamp, and content
- Real-time updates as new posts are created
- No filtering/sorting initially (just chronological)
- (Skip "Popular" sorting, advanced filters)

### 3. Minimal Content Organization
- 2-3 basic channels/categories (e.g., "General", "Knowledge Bank", "Q&A")
- Simple channel navigation
- Post to specific channel
- (Skip sub-categories, tags, or complex hierarchies)

### 4. Basic Posting & Interaction
- Create text posts with title and body
- Comment on posts
- View post details page
- Optimistic updates via InstantDB
- (Skip rich text editor, file uploads, reactions/likes)

### 5. Simple User Profiles
- Username and avatar from Google OAuth
- View user's post history
- (Skip bio, role badges, achievements, detailed profiles)

## Non-functional Requirements:

- Design the **InstantDB schema** to properly handle:
  - User data (synced from Google OAuth)
  - Posts with channel relationships
  - Comments with post relationships
  - Permissions rules for read/write access
- Define **InstantDB permission rules** to control who can create/edit/delete content
- Develop comprehensive unit tests for React components and business logic
- Create end-to-end (E2E) tests to validate core user journeys
- Use Git for all version control throughout the project
- Use ESLint for linting
- Use npm as the designated package manager
- Use descriptive commit messages for all code changes

## Design:

- Minimal, functional, practical
- Intentional use of color
- Warmer tones
- Inspired by social apps
- Responsive design for mobile and desktop

## Tech Stack:

### Frontend:
- Next.js 15 and React 19
- Tailwind CSS v4
- shadcn/ui components
- ESLint 9

### Backend:
- **InstantDB** (handles database, real-time sync, auth, permissions)
- No separate backend server needed
- Schema defined in `instant.schema.ts`

### Infra:
- GitHub (version control)
- Cloudflare Pages (frontend hosting)
- InstantDB Cloud (managed database)

Check off items in the plan as we accomplish them as a todo list. If you have open questions that require my input, add those in the plan as well.
