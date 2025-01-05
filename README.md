# Disney+ Clone Frontend

This is the frontend application for the Disney+ clone project, optimized for bolt.new deployment.

## Project Structure
- `app/` - Next.js 13+ app directory
  - `page.tsx` - Homepage
  - `video/[id]/page.tsx` - Video player page
  - `layout.tsx` - Root layout
- `components/` - Organized by feature
  - `layout/` - Shared layout components
  - `video/` - Video-related components
  - `home/` - Homepage components
- `lib/` - Utilities and services
  - `mux.ts` - Mux video configuration
  - `imagekit.ts` - ImageKit setup
- `types/` - TypeScript definitions

## Setup for bolt.new
1. Push this repository to GitHub
2. Import into bolt.new
3. Configure Environment Variables:
   - `NEXT_PUBLIC_MUX_TOKEN`
   - `NEXT_PUBLIC_IMAGEKIT_URL`
   - `NEXT_PUBLIC_API_URL`

## Development
```bash
npm install
npm run dev
```
