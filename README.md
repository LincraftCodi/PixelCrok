# PixelCrok
PixelCrok is a pixel art and frame-by-frame animation editor written in Rust. Create game sprites, work with layers, and export animations and sprite sheets.
<img width="1254" height="1254" alt="image" src="https://github.com/user-attachments/assets/375502ed-80ad-41d2-a524-221501653349" />

PixelCrok
PixelCrok is a desktop pixel art and frame-by-frame animation editor for Windows, written in Rust. It is designed for creating characters, items, tiles, and other visual assets for games.

The editor brings drawing, layers, animation, and asset export into one workspace. Everything runs locally, with no account, internet connection, or cloud storage required.
Drawing and editing
Pencil, eraser, flood fill, eyedropper, lines, and geometric shapes. Adjustable brush size, mirror drawing, a pixel grid, and built-in color palettes.

Selections can be copied, cut, pasted, flipped, and moved. Pixels outside the canvas remain stored in the project, so you can move a sprite beyond the edge and bring it back.
Layers and animation
Layers support reordering, opacity, visibility, and locking to prevent accidental edits.

Animation tools include a timeline with frame thumbnails, blank and duplicate frames, individual frame durations, onion skinning, and playback directly in the editor.
Game asset export
PixelCrok exports individual images, animations, and sprite sheets. Game atlases include a PNG image and JSON metadata describing frame positions, durations, and pivot points. Frame sequences can also be exported as separate PNG files in a ZIP archive.

Supported export formats include PNG, WebP, BMP, JPEG, GIF, and MP4. The native .pxc format preserves layers, frames, and project data for further editing.
A practical workspace
The home screen displays saved projects and offers separate starting points for sprites and animations. Mouse-wheel zoom follows the cursor, while holding the right mouse button lets you pan the canvas.

The editor also includes undo, draft recovery, and a prompt to save changes before closing a modified project.
Built with Rust
The interface and editor logic are written in Rust using egui/eframe. MP4 export uses FFmpeg.
Project status
PixelCrok is under active development. Core drawing, layer editing, animation, and export tools are available. Current work focuses on improving usability, reliability, and support for game asset workflows.
