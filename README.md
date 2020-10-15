# Cursor Divergence

I was trying to get a GUI to work and found that `gui.pick_node()` wasn't working as I expected. After some experimentation I ended up creating this project to see if I could find any differences between implementing a mouse cursor in a GUI and a non-GUI environment.

The black cursor is in the game environment and the white cursor is in the GUI environment. Run this from within defold. At the default resolution (960 x 640), both cursors move as one, and are in the same location as my OS cursor. Now maximise the game window. For me I now get the black game cursor behaving as before, but visually it has been slightly stretched horizontally and vertically. The white GUI cursor moves, but lags further away from the correct position the closer I move towards the edge of the window.

Is this something I'm doing wrong, or a bug in defold?

---