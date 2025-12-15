30 Days to Learn Elixir and Phoenix
Inspired by Laracasts' "30 Days to Learn Laravel", here's a structured 30-day self-paced learning plan to get you from zero to building real-world web applications with Elixir (the language) and Phoenix (the web framework).
Phoenix is Elixir's productive, high-performance web framework—often compared to Laravel or Rails but with built-in real-time features (via LiveView), concurrency, and fault-tolerance powered by the Erlang VM. By the end, you'll be comfortable building modern, interactive apps.
Prerequisites

Basic programming knowledge (any language).
Install Elixir (v1.17+), Erlang, and PostgreSQL: Follow https://elixir-lang.org/install.html and https://hexdocs.pm/phoenix/installation.html.

Core Resources

Free: Official docs/guides (hexdocs.pm/phoenix), Elixir School (elixirschool.com), Alchemist Camp YouTube screencasts.
Books: Programming Phoenix ≥1.4 (PragProg) and Programming Phoenix LiveView for deeper dives.
Paid (recommended for structure):
Pragmatic Studio's Elixir/OTP + Full-Stack Phoenix courses.
Udemy: "The Complete Elixir and Phoenix Bootcamp" (updated 2025).

Practice: Build small projects daily; use mix phx.new to generate apps.

The 30-Day Plan
Days 1-7: Master Elixir Fundamentals (Focus on functional programming basics—no Phoenix yet.)

Day 1: Installation, IEx (REPL), basic syntax, data types, operators.
Day 2: Pattern matching, immutability, and the pipe operator (|>).
Day 3: Modules, functions, anonymous functions, recursion.
Day 4: Lists, maps, keywords, enums (Enum module).
Day 5: Processes, messages, concurrency basics.
Day 6: Error handling (try/rescue), tasks, agents.
Day 7: Mix (build tool), ExUnit testing; build a simple CLI app.

Days 8-15: Phoenix Basics (Traditional MVC-style Phoenix.)

Day 8: Create your first Phoenix app (mix phx.new hello), explore structure (routers, controllers, views, templates).
Day 9: Routing, controllers, actions, plugs.
Day 10: Templates (HEEx), layouts, views.
Day 11: Ecto (database): Schemas, migrations, queries.
Day 12: Contexts (bounded contexts for organization), generators (phx.gen).
Day 13: Forms, changesets, validation.
Day 14: Authentication (use mix phx.gen.auth).
Day 15: Build a simple CRUD app (e.g., blog or todo list).

Days 16-25: Phoenix LiveView (The game-changer: Real-time, interactive UIs without writing JavaScript.)

Day 16: Intro to LiveView: Mount, render, handle events.
Day 17: Live routes, assigns, streams.
Day 18: Forms and validation in LiveView.
Day 19: Live components, function components.
Day 20: JS interop (hooks when needed), file uploads.
Day 21: Presence (track online users), PubSub.
Day 22: Build a real-time app (e.g., chat or dashboard).
Day 23: Advanced: Streams, temporary assigns, loading states.
Day 24: Authentication and authorization in LiveView.
Day 25: Testing LiveView (with Phoenix.LiveViewTest).

Days 26-30: Advanced Topics & Project

Day 26: Channels (for WebSockets if not using LiveView), Umbrellas (multi-app projects).
Day 27: Deployment (Fly.io, Render, or Gigalixir), environment config.
Day 28: Performance, telemetry, clustering.
Day 29: Start a capstone project (e.g., real-time forum, e-commerce dashboard, or Twitter clone).
Day 30: Finish/refactor project, explore extras (Ash framework, Nerves for embedded, or GraphQL with Absinthe).

Tips for Success

Code every day—modify generators, break things, fix them.
Join the community: Elixir Forum, #elixir on Slack/Discord.
If stuck: Read hexdocs.pm/phoenix guides—they're excellent.
After 30 days: Dive into OTP for production-grade apps or contribute to open-source Phoenix projects.
