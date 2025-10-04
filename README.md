# cc-crash-course

Let's build a web app to manage online activities for our NGO members.

Help me think through how to break this into iterative pieces and write a plan.md.

## Functional Requirements:

- There should be like a personas like anonymous user, members and also admins. 
- The admin can initiate challenges and the members can sign up. 
- A member can gain scores after completing tasks within a challenge, Admin can approve or reject with a reason. 
- Members and admin can publish blogs. other users can like and comments.
- There should be a feed view where anonymous users can see the recent blogs and also the challenges.
- There should be a leaderboard view where we list all the members with their scores.

## Non-functional Requirements:

- Design the db schema to support multi-tenancy for multiple communities.
- Develop comprehensive unit tests for React components and business logic.
- Create end-to-end (E2E) tests to validate core user journeys.
- Use Git for all version control throughout the project.
- Use ESLint for linting.
- Use npm as the designated package manager.
- Use descriptive commit messages for all code changes.

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
- Cloudflare Pages

### Backend:
- Cloudflare Workers
- Cloudflare Workers KV
- Cloudflare R2

### Infra:
- GitHub (version control)
- Cloudflare Workers, KV and R2

Check off items in the plan as we accomplish them as a todo list. If you have open questions that require my input, add those in the plan as well.
