# tanstack-query-nextjs-demo

A practical demonstration of TanStack Query (React Query) with Next.js App Router for efficient server and client-side data fetching, caching, and state management

## Features

```yaml
Server-side prefetching: Data ready on initial page load
Client-side caching: Prevent unnecessary fetches
Automatic cache invalidation: Keep data fresh
Query key-based filtering: Organize and group queries
Loading and error states: Smooth UX with proper state handling
```

## Demo Project Included

```yaml
Basic Query Example: Shows filter-based query caching
Infinite Query Example: Demonstrates infinite scroll with pagination
```

## Prerequisites

```yaml
node.js: 20.15.1
npm: 10.7.0

yarn: 1.22.22

next.js: 15.3.3
react: 19.0.0
tanstack/react-query: 5.79.0
```

## Getting Started

First, run the development server:

```bash
yarn

yarn dev
```

Open [http://localhost:3000](http://localhost:3000)

## Key Concepts Demonstrated

- **Query Keys**: Unique identifiers used for caching
- **Hydration**: Transfer server state to client
- **StaleTime**: How long data stays fresh
- **Prefetching**: Load data ahead of time
- **Query Functions**: Async data fetching

## How to Test

- Watch the "Fetching" indicator in the debug panel
- Try different filters to see caching in action
- Watch network requests in browser DevTools
- See how data is served from cache vs fetched
- Check React Query DevTools panel (bottom-right corner) to monitor:
  - Active queries and their states
  - Query cache contents
  - Refetch timing and stale status
  - Cache persistence between navigation

---

&copy; 2025 All rights reserved.
