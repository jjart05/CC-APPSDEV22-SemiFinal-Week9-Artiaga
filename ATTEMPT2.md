# Attempt 2

Completed the remaining Part 6 items:

- `NavigationManager` is injected in `Students.razor` and `ViewDetails(int id)`
  navigates to `/student/{id}`
- `Pages/StudentDetails.razor` uses `@page "/student/{id:int}"` and a
  `[Parameter] public int Id`
- The First Name input uses `@onkeydown` to capitalize the first letter
- `StudentCard.razor.css` applies scoped hover styles (CSS isolation)
