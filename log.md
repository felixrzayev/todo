# TODO List

## Start
- Add server interactive mode > Program.cs
    - `app.MapRazorComponents<App>().AddInteractiveServerRenderMode();`
    - `builder.Services.AddRazorComponents().AddInteractiveServerComponents();`
- Add routable component
    - Pages > TodoList.razor
- Models folder > ToDoItem class
- Repository class

## State variables
- Declare list of items
- Get items from repo
- display them
- add to NavMenu

## Add new task button
- Add button
- Add method
- Add default item first
- Specify server interactivity
- refresh the list > inside add item method

## Input task name
- Change list item type to input element
- two way data biding `@bind-value`

## Mark task as completed
- display checkbox
    - show in one row
- display completed date
- remove bullet point
- pop up the real data
    - do this in model itself
    - add private variable
    - in set: when setting, assign datetime now
- strikethrough completed