# Web-based Video Editing Platform – Frontend

## Project Title
Web-based Video Editing Platform (Frontend Only)

## Objective
A browser-based video editor built entirely with frontend technologies. It allows users to:
- Upload custom videos via drag-and-drop
- Rearrange audio and cutscenes visually
- Add subtitles, text overlays, and styled images
- Preview changes in real-time
- Simulate exporting and downloading the final video

This is a UI/UX-focused project with mock APIs simulating backend processes.

---

## Tech Stack

| Technology        | Purpose                                       |
|-------------------|-----------------------------------------------|
| Next.js           | Application framework                         |
| React.js          | Component-based UI                            |
| Tailwind CSS      | Styling                                       |
| ShadCN UI         | Pre-styled UI components                      |
| Redux Toolkit     | State management for timeline and overlays    |
| Optional          |                                               |
| React Dropzone    | Drag-and-drop uploads                         |
| React DnD         | Timeline scene rearrangement                  |
| HTML5 `<video>` / React Player | Video preview and playback       |

---

## Project Structure
video-editor/ │ ├── app/ # Next.js app router structure │ ├── upload/ # Video upload section │ ├── timeline/ # Video timeline editing UI │ ├── audio/ # Audio management panel │ ├── subtitles/ # Subtitles and text overlay │ ├── images/ # Static image overlay │ └── preview/ # Real-time preview and render controls │ ├── components/ # Reusable components ├── store/ # Redux slices for video, audio, subtitles ├── utils/ # Helper functions and mock APIs ├── public/ # Static assets ├── styles/ # Tailwind and global styles └──

---

## Functional Areas

### 1. Video Upload Section
- Drag-and-drop support using React Dropzone
- Simulated upload progress
- Display thumbnail preview

### 2. Video Timeline Interface
- Horizontal timeline with frame markers
- Add or remove scenes (mock logic)
- Drag-and-drop rearrangement using React DnD
- Simulated cut and edit controls

### 3. Audio Management
- Static waveform visualization
- Mute or rearrange segments (UI only)
- Background music input (mocked)

### 4. Subtitles and Text Overlay
- Add and edit subtitles
- Control timing, font, and position
- Text overlays with font, color, and placement options

### 5. Image Overlay
- Upload and position images
- Drag and resize functionality
- Optional styling: border, opacity, animation

### 6. Preview and Render
- Real-time video preview using HTML5 `<video>` or React Player
- Mock render button with loading animation
- Simulated export and download button

---

## Getting Started

1. Clone the Repository
git clone https://github.com/your-username/video-editor.git
cd video-editor

2. Install Dependencies
npm install

4. Run Locally
npm run dev
Open your browser and go to http://localhost:3000

