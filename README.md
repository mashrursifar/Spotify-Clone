# Responsive Layout Updates

This Spotify clone adapts across desktop, tablet, and mobile screen sizes.

## Breakpoints

- **1200px and below:** Sidebar, cards, and player sections scale down.
- **768px and below:** Navigation moves above the content, the library panel is hidden, and card rows become horizontally scrollable.
- **600px and below:** The player uses a compact layout with only essential playback controls visible.
- **380px and below:** Navigation text and card widths reduce further for very small screens.

## Media Player Improvements

- The fixed player has a reserved area so page content stays visible above it.
- Player information, playback controls, and volume controls use a grid layout to prevent overlap.
- Dynamic viewport sizing keeps the layout stable as mobile browser toolbars appear or disappear.

## Card Rows

- Album and playlist cards can be scrolled horizontally on small screens.
- Their visible scrollbar is hidden to keep the interface clean while touch scrolling remains available.
