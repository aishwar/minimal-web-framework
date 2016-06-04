# minimal-web-framework
Most frameworks are massive. What are the different parts you need to build a modern web application?

## List of things a single page application relies on:

- Router: to manage navigation across pages
- Theme: a style of how the page should look
- View/UI elements
  + Ones that can display data (lists etc.)
  + Ones that can have behaviour (buttons etc.)
  + UI elements can have states (invalid etc.). UI elements can be bound to a model. UI elements need to be updated when models change. The ideal UI elements are well designed such that you can use just the pieces you need and it all fits perfectly.
  + There is a great amount of flexibility here. There are the basic elements, like forms, text boxes etc.; there are the more custom elements like graphical visualizations etc.
  + UI elments need to have the flexibility to be expressive and heavily customizable, but they also need a strict interface that will allow different elements to be pluggable and usable.
- Model/Ability to communicate with a data source
  + AJAX
  + LocalStore etc.
- Controller: a place to coordinate action across views and models. A mechanism to group sets of functionality, so we don't have one giant place where all the coordination happens.

