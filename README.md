# EchoLearn - Assistive Speech and Communication System

EchoLearn is a web-based platform that combines an Augmentative and Alternative Communication (AAC) board with AI-powered pronunciation assessment. It helps children with speech difficulties communicate using picture-based tiles and improve their pronunciation through real-time, phoneme-level feedback.

---

## Features

### 1. AAC Communication Board
- 15 categories (Food, Animals, Emotions, Body Parts, Clothing, School, etc.)
- Picture-based tiles for easy communication
- Sentence builder bar with speak and clear buttons
- Custom tile addition and deletion (edit mode)
- Text-to-speech output with Indian English voice

### 2. Pronunciation Assessment
- Real-time speech recognition using Microsoft Azure Speech Services
- Phoneme-level scoring (0-100% for each sound)
- Error type detection (Mispronunciation, Omission, Insertion)
- Position tracking (Beginning, Middle, End of words)
- Star rating system (0-3 stars based on score)

### 3. Articulation Visualization
- Static mouth images for each phoneme
- 3D animated mouth videos showing correct tongue and lip position
- Play button to watch articulation demonstration

### 4. Baseline Assessment
- 21 standardized words covering all 44 English phonemes
- One-time test taken when child first registers
- Scores stored as baseline for before/after comparison

### 5. Progress Tracking Dashboard
- Overall improvement metrics
- Practice sessions bar chart (last 7 sessions)
- Mastered words section (3 consecutive attempts >=70%)
- Practice by difficulty pie chart (Easy/Medium/Hard)
- Before vs After phoneme comparison grids (44 phonemes)
- Phoneme position breakdown panel (Beginning/Middle/End)
- Adaptive recommendations (weakest 5 phonemes with suggested words)
- Search and pagination for practice history

### 6. Practice History
- Word-wise grouping with best score and trend indicator
- Score progression line chart per word
- Expandable attempt details with phoneme breakdown
- Timestamps for each practice attempt

### 7. User Authentication
- Child account creation and login
- All practice data stored per child

---

## Tech Stack

- Frontend- React.js, Recharts,HTML,CSS,JavaScript
- Backend- Node.js, Express.js
- Database-MongoDB, Mongoose
- Speech AI-Microsoft Azure Speech Services


## System Architecture:

<img width="1013" height="648" alt="image" src="https://github.com/user-attachments/assets/8350ef1e-097f-480e-91a6-118993674178" />
