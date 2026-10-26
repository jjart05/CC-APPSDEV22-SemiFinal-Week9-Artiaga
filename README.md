# CC-APPSDEV22 SemiFinal Week 9 — Student Portal UI

Blazor WebAssembly frontend for the Student Portal. Reusable `StudentCard`
components, client-side routing, event-driven student additions, CSS isolation,
and a loading state.

## Setup

```bash
dotnet restore
```

## Run

```bash
dotnet watch run
```

Open the printed localhost URL (default `http://localhost:5160`) and go to
`/students`.

## Pages

- `/` — default Home
- `/students` — student list, add form, and loading state
- `/student/{id}` — details page reached by `NavigationManager`

## Attempt 2 additions

- `NavigationManager` navigates to `/student/{id}` from View Details
- `StudentDetails.razor` with `@page "/student/{Id:int}"`
- `@onkeydown` capitalizes the first letter of First Name as you type
- `StudentCard.razor.css` scoped hover styles
