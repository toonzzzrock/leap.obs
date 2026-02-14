### Features

- Support for multiple keyboard layouts
- Ergonomic indexing and tagging
- Fully customizable

### How it works

Leap provides 3 navigation modes:

- Jump to the beginning of the word
- Jump to the beginning of the line

#### Basic workflow:

1. Activate jump mode (e.g. Jump to any character)
2. Type the first character you want to jump to (the editor won't dim yet)
3. Type the second character
4. Tags will appear at the positions of matching character pairs, and the editor will dim for focus
5. Type the character shown on the tag at the position you want to jump to

<br/>

### Recent fixes

- Fixed tag generation after 2-character search so jump labels continue to appear and can be narrowed.
- Fixed decoration ordering issues that could hide all labels/highlights in some searches.
- Improved rendering for inline code (`` `...` ``) so highlights and jump labels are shown more reliably.
