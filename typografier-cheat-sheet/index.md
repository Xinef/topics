---
layout: cheatsheet

groups:
  - title: 'Font sizes'
    items:
      - name: '`.yotta`'
        details:
          - 'Two sizes larger than the `<h1>`.'
      - name: '`.zetta`'
        details:
          - 'One size larger than the `<h1>`.'
      - name: '`.exa`, `<h1>`'
        details:
          - 'Same size as the `<h1>`.'
          - 'Five sizes larger than body copy.'
      - name: '`.peta`, `<h2>`'
        details:
          - 'Four sizes larger than body copy.'
      - name: '`.tera`, `<h3>`'
        details:
          - 'Three sizes larger than body copy.'
      - name: '`.giga`, `<h4>`'
        details:
          - 'Two sizes larger than body copy.'
      - name: '`.mega`, `<h5>`'
        details:
          - 'One size large than body copy.'
      - name: '`.kilo`, `<h6>`, `<p>`, *default*'
        details:
          - 'The default font size, body copy.'
      - name: '`.milli`, `<small>`'
        details:
          - 'One size smaller than the body copy.'
      - name: '`.micro`'
        details:
          - 'Two sizes smaller than the body copy.'

  - title: 'Spacing'
    items:
      - name: '`.push`'
        details:
          - 'Adds consistent margin to the bottom.'
          - '*Try to avoid using top margins for consistency.*'
      - name: '`.push-none`, `.push-0`'
        details:
          - 'Remove the bottom margin.'
      - name: '`.push-2`, `.push-1-2`, `.push-1-4`, `.push-1-8`'
        details:
          - 'Add differing sizes of margin to the bottom.'
          - 'Available as fully written out versions: `.push-double`, `.push-half`, `.push-quarter`, `.push-eighth`.'
      - name: '`.push-r`, `.push-r-1-2`, `.push-r-1-4`, `.push-r-1-8`'
        details:
          - 'Add differing sizes of margin to the right.'
          - 'Available as fully written out versions: `.push-right`, `.push-right-half`, `.push-right-quarter`, `.push-right-eighth`.'
      - name: '`.gutter`,`.gutter-2`, `.gutter-1-2`, `.gutter-1-4`, `.gutter-1-8`'
        details:
          - 'Adds padding to left and right sides.'
          - 'Available as fully written out versions: `.gutter-double`, `.gutter-half`, `.gutter-quarter`, `.gutter-eighth`.'
      - name: '`.island`,`.island-2`, `.island-1-2`, `.island-1-4`, `.island-1-8`'
        details:
          - 'Adds padding to all four sides.'
          - 'Available as fully written out versions: `.island-double`, `.island-half`, `.island-quarter`, `.island-eighth`.'
      - name: '`.pad-t`,`.pad-t-2`, `.pad-t-1-2`, `.pad-t-1-4`, `.pad-t-1-8`'
        details:
          - 'Adds padding to top of the box.'
          - 'Available as fully written out versions: `.pad-top`, `.pad-top-double`, `.pad-top-half`, `.pad-top-quarter`, `.pad-top-eighth`.'
      - name: '`.pad-b`,`.pad-b-2`, `.pad-b-1-2`, `.pad-b-1-4`, `.pad-b-1-8`'
        details:
          - 'Adds padding to bottom of the box.'
          - 'Available as fully written out versions: `.pad-bottom`, `.pad-bottom-double`, `.pad-bottom-half`, `.pad-bottom-quarter`, `.pad-bottom-eighth`.'

  - title: 'Utilities'
    items:
      - name: '`.text-left`, `.text-right`, `.text-center`'
        details:
          - 'Text alignment classes.'
          - '*These are brute force and not responsive, so use only when it will always need that alignment.*'
      - name: '`.bold`, `.italic`, `.not-bold`, `.not-italic`, `.normal`'
        details:
          - 'Font style and weight classes.'
          - '`.normal` will set both `font-weight` and `font-style`'
          - '*These are brute force and not responsive, so use only when it will always need that style or weight.*'
      - name: '`.text-upper`, `.text-lower`'
        details:
          - 'Font capitalization classes: all uppercase & all lowercase.'
          - '*These are brute force and not responsive, so use only when it will always need that capitalization.*'
      - name: '`.hang-punc`'
        details:
          - 'Add to an element at the beginning of a line to make the character hang in the margin.'
          - 'Great for use in blockquotes to hang the beginning quotation mark.'
          - '*This class will only exist when the “Hang punctuation” option is selected.*'
          - |
            ```html
            <blockquote>
              <p><span class="hang-punc">“</span>Dinosaurs are amazing!”</p>
            </blockquote>
            ```
      - name: '`.wrapper`'
        details:
          - 'Sets the `max-width` of an element to `52em`—which is a fairly good line-length for a website body.'
      - name: '`.max-length`'
        details:
          - 'Sets the `max-width` of an element to `36em`—which is a fairly good line-length for text content.'

---
