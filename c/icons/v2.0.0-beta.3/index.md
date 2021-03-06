---
layout: component-yaml
title: Icons
section: Components
version: 2.0.0-beta.3
status: active
people:
  - role: Product Owner
    name: Joe Macaluso
    email: joe.macaluso@pearson.com
  - role: Designer
    name: Van Yang
    email: van.yang@pearson.com
implementation: https://pearson-elements-v0.surge.sh/elements/icons/
downloads:
  - name: Pearson-icons-1.2.sketch
    link: ./assets/Pearson_icons_1.2.sketch
  - name: UXD Accessibility Checklist
    link: https://docs.google.com/a/pearson.com/document/d/15RLoDS-Qlu_Qz1W8UNuiHu3OtdNZ8kzKm_7jecoP5So/edit?usp=sharing
dependencies:
  - name: Colors
    version: 2.0.0

tagline: |
  This component provides a standard set of UI icons across Pearson applications.
features:
  - 18px and 24px icons
  - CSS class
  - Guidelines
usage_guidelines: |
  Use Pearson icons with a purpose. Do not use them as decorations or alter their intended use.

blocks:

  - type: section
    name: Pearson Icons

  - type: two column
    text: |
      Pearson icons are available in two sizes, **18 x 18** and **24 x 24 pixels**. You can incorporate them into your design by downloading the Pearson-icons.sketch file, located above.

      ### Web App Development
      You do not need to provide SVG or backup PNG, simply note the class name from the icons list or within the Pearson-icons.sketch file. If you wish to modify the icons, follow the guidelines below for colors, naming, and scaling.

      ### Blue and White Icons
      The default color is gray. For a blue or white version, simply add **-blue** or **-white** suffix to the class name. See Name Guide for more examples.

    contents:
        - type: table
          content: |
            | General |      |      |
            | :-----: | :--- | :--- |
            | ![](./assets/icons24/archive-24-2x.png) | archive-18 | archive-24 |
            | ![](./assets/icons24/ban-24-2x.png) | ban-18 | ban-24 |
            | ![](./assets/icons24/book-24-2x.png) | book-18 | book-24 |
            | ![](./assets/icons24/calendar-24-2x.png) | calendar-18 | calendar-24 |
            | ![](./assets/icons24/camera-24-2x.png) | camera-18 | camera-24 |
            | ![](./assets/icons24/camera-video-24-2x.png) | camera-video-18 | camera-video-24 |
            | ![](./assets/icons24/capslock-24-2x.png) | capslock-18 | capslock-24 |
            | ![](./assets/icons24/check-lg-24-2x.png) | check-lg-18 | check-lg-24 |
            | ![](./assets/icons24/check-sm-24-2x.png) | check-sm-18 | check-sm-24 |
            | ![](./assets/icons24/chevron-back-24-2x.png) | chevron-back-18 | chevron-back-24 |
            | ![](./assets/icons24/chevron-next-24-2x.png) | chevron-next-18 | chevron-next-24 |
            | ![](./assets/icons24/point-back-24-2x.png) | point-back-18 | point-back-24 |
            | ![](./assets/icons24/point-next-24-2x.png) | point-next-18 | point-next-24 |
            | ![](./assets/icons24/clock-24-2x.png) | clock-18 | clock-24 |
            | ![](./assets/icons24/delete-24-2x.png) | delete-18 | delete-24 |
            | ![](./assets/icons24/desktop-24-2x.png) | desktop-18 | desktop-24 |
            | ![](./assets/icons24/email-24-2x.png) | email-18 | email-24 |
            | ![](./assets/icons24/file-24-2x.png) | file-18 | file-24 |
            | ![](./assets/icons24/font-lg-24-2x.png) | font-lg-18 | font-lg-24 |
            | ![](./assets/icons24/font-sm-24-2x.png) | font-sm-18 | font-sm-24 |
            | ![](./assets/icons24/font-setting-24-2x.png) | font-setting-18 | font-setting-24 |
            | ![](./assets/icons24/person-24-2x.png) | person-18 | person-24 |
            | ![](./assets/icons24/group-24-2x.png) | group-18 | group-24 |
            | ![](./assets/icons24/help-fill-24-2x.png) | help-fill-18 | help-fill-24 |
            | ![](./assets/icons24/help-outline-24-2x.png) | help-outline-18 | help-outline-24 |
            | ![](./assets/icons24/image-24-2x.png) | image-18 | image-24 |
            | ![](./assets/icons24/info-fill-24-2x.png) | info-fill-18 | info-fill-24 |
            | ![](./assets/icons24/info-outline-24-2x.png) | info-outline-18 | info-outline-24 |
            | ![](./assets/icons24/note-24-2x.png) | note-18 | note-24 |
            | ![](./assets/icons24/remove-lg-24-2x.png) | remove-lg-18 | remove-lg-24 |
            | ![](./assets/icons24/remove-sm-24-2x.png) | remove-sm-18 | remove-sm-24 |
            | ![](./assets/icons24/search-lg-24-2x.png) | search-lg-18 | search-lg-24 |
            | ![](./assets/icons24/search-sm-24-2x.png) | search-sm-18 | search-sm-24 |
            | ![](./assets/icons24/settings-24-2x.png) | settings-18 | settings-24 |
            | ![](./assets/icons24/tip-24-2x.png) | tip-18 | tip-24 |
            | ![](./assets/icons24/warning-24-2x.png) | warning-18 | warning-24

            | Player  |      |      |
            | :-----: | :--- | :--- |
            | ![](./assets/icons24/audio-off-24-2x.png) | audio-off-18 | audio-off-24 |
            | ![](./assets/icons24/audio-high-24-2x.png) | audio-high-18 | audio-high-24 |
            | ![](./assets/icons24/audio-low-24-2x.png) | audio-low-18 | audio-low-24 |
            | ![](./assets/icons24/pause-24-2x.png) | pause-18 | pause-24 |
            | ![](./assets/icons24/play-24-2x.png) | play-18 | play-24 |
            | ![](./assets/icons24/screen-full-24-2x.png) | screen-full-18 | screen-full-24 |
            | ![](./assets/icons24/screen-minimize-24-2x.png) | screen-minimize-18 | screen-minimize-24 |

            | Toggle  |      |      |
            | :-----: | :--- | :--- |
            | ![](./assets/icons24/checkbox-off-24-2x.png) | checkbox-off-18 | checkbox-off-24 |
            | ![](./assets/icons24/checkbox-on-24-2x.png) | checkbox-on-18 | checkbox-on-24 |
            | ![](./assets/icons24/checkbox-tristate-24-2x.png) | checkbox-tristate-18 | checkbox-tristate-24 |
            | ![](./assets/icons24/dropdown-close-24-2x.png) | dropdown-close-18 | dropdown-close-24 |
            | ![](./assets/icons24/dropdown-open-24-2x.png) | dropdown-open-18 | dropdown-open-24 |
            | ![](./assets/icons24/favorite-off-24-2x.png) | favorite-off-18 | favorite-off-24 |
            | ![](./assets/icons24/favorite-on-24-2x.png) | favorite-on-18 | favorite-on-24 |
            | ![](./assets/icons24/item-add-24-2x.png) | item-add-18 | item-add-24 |
            | ![](./assets/icons24/item-remove-24-2x.png) | item-remove-18 | item-remove-24 |
            | ![](./assets/icons24/lock-close-24-2x.png) | lock-close-18 | lock-close-24 |
            | ![](./assets/icons24/lock-open-24-2x.png) | lock-open-18 | lock-open-24 |
            | ![](./assets/icons24/pivot-close-24-2x.png) | pivot-close-18 | pivot-close-24 |
            | ![](./assets/icons24/pivot-open-24-2x.png) | pivot-open-18 | pivot-open-24 |
            | ![](./assets/icons24/radio-button-off-24-2x.png) | radio-button-off-18 | radio-button-off-24 |
            | ![](./assets/icons24/radio-button-on-24-2x.png) | radio-button-on-18 | radio-button-on-24 |
            | ![](./assets/icons24/show-off-24-2x.png) | show-off-18 | show-off-24 |
            | ![](./assets/icons24/show-on-24-2x.png) | show-on-18 | show-on-24 |
            | ![](./assets/icons24/view-list-24-2x.png) | view-list-18 | view-list-24 |
            | ![](./assets/icons24/view-tile-24-2x.png) | view-tile-18 | view-tile-24 |
            | ![](./assets/icons24/zoom-in-24-2x.png) | zoom-in-18 | zoom-in-24 |
            | ![](./assets/icons24/zoom-out-24-2x.png) | zoom-out-18 | zoom-out-24 |


#            | ![](./assets/icons24/newspaper-24-2x.png) | newspaper-18 | newspaper-24 |
#            | ![](./assets/icons24/pin-24-2x.png) | pin-18 | pin-24 |
#            | ![](./assets/icons24/suitcase-24-2x.png) | suitcase-18 | suitcase-24 |
  - type: section
    name: Name Guide

  - type: two column
    text: |
        The name describes the **intended use, variation, pixel size,** and **scaling**.

    contents:
        - type: wide image
          src: ./assets/name-guide.png

  - type: section
    name: Colors

  - type: two column
    text: |
      ### Standard Colors:

      - [Medium Gray](/design/c/colors/v2.0.0-beta.5/#rd-medium-gray)
      - [White](/design/c/colors/v2.0.0-beta.5/#rd-white)

      ### Status Colors: <span style="font-weight:normal;">*(optional)*</span>

      - [Digital Pearson Blue](/design/c/colors/v2.0.0-beta.5/#rd-digital-pearson-blue) - primary or selected
      - [Digital Grass Green](/design/c/colors/v2.0.0-beta.5/#rd-digital-grass-green) - success or correct
      - [Strawberry Red](/design/c/colors/v2.0.0-beta.5/#rd-strawberry-red) - error or wrong

    contents:
        - type: wide image
          src: ./assets/colors.png

  - type: section
    name: Label Spacing

  - type: two column
    text: |
      Use a minimum spacing, **10 pixel**, between the icon and label.

    contents:
        - type: wide image
          src: ./assets/label-spacing.png

  - type: section
    name: Touch Target

  - type: two column
    text: |
      You can use Pearson icons as buttons. To ensure accessibility across desktop and mobile devices, a minimum touch target, **44 x 44 pixel**, is required for each icon.

    contents:
        - type: wide image
          src: ./assets/touch-target.png

  - type: section
    name: Scaling

  - type: two column
    text: |
      You can scale the icons up by **2x, 3x, 4x,** and **5x**. However, scaling them down or any .5x variation, the lines and shapes will become blurry.

    contents:
        - type: wide image
          src: ./assets/scaling.png



changelog:
  - version: 2.0.0-beta.3
    changes: |
      - ADDED: Caps lock icons.
      - ADDED: HEX links to colors section
  - version: 2.0.0-beta.2
    changes: |
      - ADDED: checkbox tri-state, dropdown, font settings, list, lock, note, pivots, pointers, tip, and zooms.
      - ADDED: class names for white and blue icons.
      - TWEAKED: bolder line-weight for 18px and 24px.
      - REMOVED: newspaper, pin, and suitcase.
  - version: 2.0.0-beta.1
    changes: |
      New Pearson UI Icons
  - version: 1.2.0-beta.1
    changes: |
      - ADDED: search-plus, search-minus, bell, clock-o
  - version: 1.1.0
    changes: |
      - ADDED: question-circle, caret-right, caret-down, light-bulb-o, and icons for archive action, plus reading, business case, video, and image content types
      - TWEAKED: Icons should now all be displayed in Pitch (#231f20)
  - version: 1.0.0
    changes: |
      Initial release
---
