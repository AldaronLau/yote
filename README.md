# Yote
A text editor / IDE for C, Rust, Aratar or Python code.

The goal of this editor is different from others in that it has it's own repository format, code isn't actually stored as text but in it's own compressed format.  Undo history is always saved in the file until a commit.  History is stored as patches, with a snapshot for the most recent on each branch, and for each version.  Artwork always uses snapshots, and is treated separately.
