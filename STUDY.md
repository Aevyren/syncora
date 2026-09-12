# Syncora — Required Study Materials

Only the topics needed to build Syncora.

## Core Learning List

| # | Topic | Level | What to Study |
|---|---|---|---|
| 1 | **TypeScript** | Must learn | Types, interfaces, type aliases, unions, generics, narrowing, utility types, async types |
| 2 | **React** | Must learn | Components, props, state, effects, refs, custom hooks, composition |
| 3 | **Vite** | Basic | Project setup, client environment variables (`VITE_` prefix vs private secrets), dev/build workflow |
| 4 | **TanStack Router** | Must learn | File-based routing, dynamic/nested routes, layouts, params, search params, auth protection |
| 5 | **TanStack Query** | Must learn | Queries, mutations, query keys, caching, invalidation, pagination, optimistic updates, integrating with Hono RPC |
| 6 | **Zustand** | Basic–Intermediate | Stores, selectors, actions, TypeScript, client/UI state (active workspace, sidebar, modals) |
| 7 | **Tailwind CSS** | Must learn | Utility classes, layout, responsive design, typography, spacing, states, dark mode |
| 8 | **shadcn/ui + React Hook Form** | Must learn | Buttons, forms (`react-hook-form` + `@hookform/resolvers/zod`), dialogs, dropdowns, sheets, tables, command menu (`⌘K`), avatars, badges, calendar, toasts (`sonner`) |
| 9 | **Bun** | Basic | Runtime, package management, monorepo workspace commands (`bun --filter`), scripts, `bunx`, private environment variables |
| 10 | **Hono** | Must learn | Routes, context, middleware, request/response, errors, CORS, auth middleware, **Hono RPC (`hc`)** for end-to-end typed client |
| 11 | **Zod** | Must learn | Schemas, objects, enums, optional/nullable, `refine`, `parse`/`safeParse`, validation, `drizzle-zod`, form validation |
| 12 | **PostgreSQL / SQL** | Must learn | Tables, PK/FK, joins, constraints, indexes, transactions, basic queries |
| 13 | **Drizzle ORM (PostgreSQL)** | Must learn | Schema definition (`pgTable`), relations, `drizzle-kit push` (prototyping), query builder & relational queries (`db.query`), type inference (`$inferSelect`/`$inferInsert`), `postgres.js` driver |
| 14 | **Supabase Auth** | Must learn | Signup, login, logout, sessions, verification, password reset, auth state via JS SDK |
| 15 | **Supabase Storage** | Basic | Buckets, public vs private files, image/avatar uploads via JS SDK, file size limits |
| 16 | **Supabase RLS** | Must learn | `auth.uid()`, policies, workspace-level access, defense in depth |
| 17 | **Git + GitHub** | Must learn | Branches, commits, push/pull, PRs, conflicts, merge/rebase basics |
| 18 | **WebSocket Fundamentals** | Conceptual | Persistent connections, handshake, messages, lifecycle, reconnects, authentication |
| 19 | **Supabase Realtime** | Learn later | Broadcast, Presence, Postgres Changes, channels, subscriptions, authorization |
| 20 | **Supabase CLI** | Optional / Later | Local Docker environment (`init`, `start`, `stop`, local studio dashboard) if working offline |

---

## Recommended Study Order

1. TypeScript
2. React + Vite (incl. client environment variables)
3. Tailwind CSS + shadcn/ui (incl. React Hook Form & Sonner toasts)
4. TanStack Router
5. Zustand
6. Bun + Hono (incl. Hono RPC)
7. Zod + `drizzle-zod`
8. TanStack Query (powered by Hono RPC client)
9. PostgreSQL / SQL
10. Drizzle ORM (PostgreSQL)
11. Supabase Auth
12. Supabase Storage (avatars & file uploads)
13. Supabase RLS (workspace security)
14. Git + GitHub
15. WebSocket Fundamentals
16. Supabase Realtime (presence & live sync)
17. Supabase CLI (Optional / Later)

---

## Official Documentation

- **TypeScript** — https://www.typescriptlang.org/docs/handbook/intro.html
- **React** — https://react.dev/
- **Vite** — https://vite.dev/guide/
- **TanStack Router** — https://tanstack.com/router/latest/docs/quick-start
- **TanStack Query** — https://tanstack.com/query/latest
- **Zustand** — https://zustand.docs.pmnd.rs/
- **Tailwind CSS** — https://tailwindcss.com/docs
- **shadcn/ui** — https://ui.shadcn.com/docs/installation
- **React Hook Form** — https://react-hook-form.com/get-started
- **Bun** — https://bun.sh/docs
- **Hono** — https://hono.dev/docs/
- **Hono RPC Client** — https://hono.dev/docs/guides/rpc
- **Zod** — https://zod.dev/
- **drizzle-zod** — https://orm.drizzle.team/docs/zod
- **PostgreSQL Tutorial** — https://www.postgresql.org/docs/current/tutorial.html
- **Drizzle ORM** — https://orm.drizzle.team/docs/overview
- **Drizzle with Supabase** — https://orm.drizzle.team/docs/tutorials/drizzle-with-supabase
- **Supabase Auth** — https://supabase.com/docs/guides/auth
- **Supabase Storage** — https://supabase.com/docs/guides/storage
- **Supabase RLS** — https://supabase.com/docs/guides/database/postgres/row-level-security
- **Supabase Realtime** — https://supabase.com/docs/guides/realtime
- **MDN WebSocket** — https://developer.mozilla.org/en-US/docs/Web/API/WebSocket
- **Git** — https://git-scm.com/doc
