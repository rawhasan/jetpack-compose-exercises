# Jetpack Compose Exercises
Exercise projects I've done while learning native Android development with Kotlin and Jetpack Compose. Can help anyone who is just starting to learn Android development with Kotlin.

## #1. [Basic Navigation](https://github.com/rawhasan/compose-exercise-navigation-basics)
- Simple navigation between two screens with passing values using Jetpack Compose.
- Allow entering only letters on the TextField.

<br />

<p float="left">
    <img src = "https://user-images.githubusercontent.com/67064997/127823749-87a23b7b-ae8b-46a3-a883-a9b267e57381.png" width="200" />
    <img src="https://user-images.githubusercontent.com/67064997/127823753-36363485-9b20-4dbb-a436-996abe6b6a2c.png" width="200" />
</p>

<br />

## #2. [Viewmodel Sharing](https://github.com/rawhasan/compose-exercise-viewmodel-sharing)
- Sharing a `View Model` between composables inside Jetpack Compose Navigation.
- Providing a **numeric keyboard** for number input.
- Showing **number format conditionally** based on the floating point digits (0.0 or 0).

<br />

<p float="left">
    <img src = "https://user-images.githubusercontent.com/67064997/127863143-71ffb8b8-46dc-41fd-9cca-0f5c025ddd46.png" width="200" />
    <img src="https://user-images.githubusercontent.com/67064997/127863134-73b5f22f-f4ea-4352-b23e-fe93b827883e.png" width="200" />
</p>

<br />

## #3. [Lazy Column Scrolling](https://github.com/rawhasan/compose-exercise-lazy-column-scrolling)
- Display a simple scrollable list using Lazy Column.
- Loading images from internet using the Coil library.
- Applying text and background color.

<br />
<img src="https://user-images.githubusercontent.com/67064997/127976999-1317bbfb-d9c9-487d-b5d8-3d48c0921c25.png" width="200" />

<br />

## #4. [LazyColumn Sync](https://github.com/rawhasan/compose-exercise-lazy-column-sync)
- Sync list on a LazyColumn after adding and deleting items.
- Using TopAppBar, Button with an icon, built-in icons.
- Filling up the whole remaining space by an UI element.
- Hiding keyboard on enter press and on button click.
- Case insensitive check for a word on a list.
- Make a word sentence case.
- Allow entering only letters on the TextField.
- TopAppBar icon change on click (ascending/descending order).
- Delete items from LazyColumn on click.
- Show leading icon on TextField.
- Show trailing icon on TextField based on error.
- Show separate error message with TextField based on error.

- [ ] FIXME: Strange sorting bug. Keeps the new words separate while sorting.

<br />

<p float="left">
  <img src="https://user-images.githubusercontent.com/67064997/128343506-6b5ae70e-f3f4-4d3c-917f-cc6342a07f1f.png" width="200" />
  <img src="https://user-images.githubusercontent.com/67064997/128351895-ab210e56-ae71-44d8-ad76-44740ef43c4a.png" width="200" />  
</p>

<br />

## #5. [State Hoisting](https://github.com/rawhasan/compose-exercise-state-hoisting)
- Implementing state hoisting to manage a list of people and their age.
- Row click handling by removing the item from a LazyColumn.
- Input validation (name & age).
- Replace multiple spaces from an input.
- Capitalize first character of each word in a sentence.
- Hiding keyboard on enter press and on button click.  
- Generating unique ID as model field.

<br />

<img src="https://user-images.githubusercontent.com/67064997/128541787-6ea0ee16-d041-4059-bf47-87a078d3be52.png" width="200" />

<br />

## #6. [LazyVerticalGrid](https://github.com/rawhasan/compose-exercise-lazy-vertical-grid)
- Making a grid layout using the experimental LazyVerticalGrid composable.
- Making a column scrollable vertically.
- Using Scaffold with TopAppBar and NavHost.
- Navigation back button on TopAppBar.
- Change TopAppBar title dynamically in different screens (using a shared view model).

<br />

<p float="left">
  <img src="https://user-images.githubusercontent.com/67064997/128686864-503e759a-c20f-42a7-9a11-a8bf2bc26d90.png" width="200" />
  <img src="https://user-images.githubusercontent.com/67064997/128686855-01064390-e29e-43a5-9bba-cc3c714348f0.png" width="200" />  
</p>

<br />

## #7. [Image Sources](https://github.com/rawhasan/compose-exercises-image-source)
- Show user-selected image from the gallery.
- Show user-entered image from a web URL.

- [ ] TODO: Verify image exists on provided URL before showing.
- [ ] TODO: Show the previous image in case of an non-existing image on the URL.
- [ ] TODO: Display image from the camera when the Camera API from Compose arrives.

<br />

<p float="left">
  <img src="https://user-images.githubusercontent.com/67064997/129017019-204c7a74-b0cd-4070-b58a-e97c87d21b35.png" width="200" />
  <img src="https://user-images.githubusercontent.com/67064997/129017029-2e29ed19-3ba5-4c45-8d17-d6310165b5c9.png" width="200" />  
  <img src="https://user-images.githubusercontent.com/67064997/129017026-4e7b8a3d-3e5f-40e2-b041-c32880a9e837.png" width="200" />
</p>

<br />

## #8. [Room Basics](https://github.com/rawhasan/compose-exercise-room-basics)
- Add, show, edit, and delete data from a Room database using Jetpack Compose.
- TextField background color change.
- Keep only one edit form open at a time.

<br />

<img src="https://user-images.githubusercontent.com/67064997/129380620-aedce818-05e1-4c6d-9b9d-66e85bf072de.png" width="200" />

<br />

## #9. [Room CRUD](https://github.com/rawhasan/compose-exercise-room-crud)
- Scaffold with TopAppBar and FAB.
- Set title dynamically from different screens by raising event.
- Turn on/off FAB in different screens by raising event.
- Show alert dialog to confirm an action.

<br />

<p float="left">
  <img src="https://user-images.githubusercontent.com/67064997/129905189-628faa43-df63-40f8-b9c1-37ff41d56356.png" width="200" />
  <img src="https://user-images.githubusercontent.com/67064997/129905197-73cfdb03-dfdc-4c1c-9c19-4258a948595f.png" width="200" />  
  <img src="https://user-images.githubusercontent.com/67064997/129905201-ec2fe7a4-0d74-4770-b32f-ac238440cca1.png" width="200" />
  <img src="https://user-images.githubusercontent.com/67064997/129905203-b3836041-6dbf-4b19-84e6-12ba31bd0f51.png" width="200" />
</p>

