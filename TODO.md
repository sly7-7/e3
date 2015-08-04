- [-] Support Mouse Events
  - [X] Mouse Enter
  - [X] Mouse Leave
  - [X] Mouse Move
  - [X] Mouse Down
  - [X] Mouse Up
  - [X] Click
  - [ ] Mouse Events should piggy-back on the render queue if possible
- [X] Support removing objects when they're destroyed.
- [ ] Support sort order on #each — maybe destroy & recreate group?
- [ ] Create Various Shape Renderables
  - [X] Rectangle
  - [X] Vertical Line
  - [X] Horizontal Line
  - [ ] Text
  - [ ] Path* (this needs some thought for canvas/svg compatibility)
  - [ ] Polygon (Same applies as path).
- [X] Create Array Helpers
  - [X] Extent (Include "padding" option)
  - [X] Unique
- [-] Create Scales (Feature Parity with D3?)
  - [X] Linear Scale
  - [ ] Ordinal Scale
  - [ ] Date Scale
  - [X] Bind Scale to Renderable Property Helper
- [ ] Create Layout Engines
  - [ ] Force Direction
  - [ ] Collision Detection
- [-] Create Stacked Groups (provides previous & next data)
  - [ ] Stacked Renderable Types (Stacked Bar, Pie, Stacked Area)
- [ ] Transition Enter State with Previous Scale
  - [ ] How to handle Ordinal Scales where value didn't exist previously? (closest index?)
- [ ] Add Animation Easing Functions
  - [ ] Basic Quad Easing
  - [ ] Elastic Easing
  - [ ] Linear Easing