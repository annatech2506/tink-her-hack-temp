<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# Focus Flow-Focus Enhancing system 🎯

## Basic Details
Purpose: Personal focus tracking and productivity improvement
Tech Stack: HTML, CSS, JavaScript (frontend only)
Key Features: Timer-based focus sessions, reflection prompts, rating system, session analytics

### Team Name: Anna Mijo's Team

### Team Members
- Member 1: Anna Mijo -Jyothi Engineering College

### Hosted Project Link
fffocusflow1.netlify.app

### Project Description
The AI Focus System is a simple yet powerful web app designed to help users stay focused and improve productivity. Users can choose a focus duration, start a timer, and immerse themselves in distraction-free work. After each session, they can reflect on their focus, rate their performance ⭐, and record what distracted them 📝.

The app keeps track of completed sessions and total focus minutes 📊, giving users insights into their productivity patterns. While it’s currently a lightweight tool, it has the potential to evolve into an AI-powered personal focus assistant, offering adaptive suggestions and streak tracking 🔮.

This project is perfect for anyone looking to build healthy focus habits in a structured and fun way! 🎯💡

### The Problem statement
Many students and professionals struggle to maintain focus during work or study sessions. Distractions from phones, social media, and environment make it difficult to track productivity or understand where attention is lost. Existing solutions are either too complex, expensive, or fail to provide personalized feedback on focus habits.

### The Solution
Focus System offers a simple, interactive way to improve focus:
Users select a session duration and start a distraction-free timer ⏲️
After the session, they can rate their focus ⭐ and reflect on distractions 📝
The app tracks completed sessions, total focus minutes, and streaks 📊
Based on feedback, users gain insights into their focus patterns, helping them gradually improve productivity

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: HTML,CSS,Java Script
- Tools used: VS code,Edge

## Features

Custom Focus Timer ⏱️: Users can select different durations (1, 5, 10, 25 minutes) for a distraction-free focus session.
Circular Progress Visualization 🔵: Shows the timer’s progress in a sleek circular animation, making it easy to track session time.
Reflection & Rating System 📝⭐: After each session, users can rate their focus and note what distracted them for self-improvement.
Analytics Dashboard 📊: Tracks completed sessions, total focus minutes, and provides basic insights into productivity patterns.

## Implementation

### For Software:

#### Installation
No special installation required. Just download or clone the project files to your local machine.

#### Run
Open the index.html file in any modern web browser (Chrome, Edge, Firefox).

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)


<img width="1280" height="562" alt="image" src="https://github.com/user-attachments/assets/d8ae0ed4-1a2d-480e-ab57-f17a216b0acb" />


<img width="1280" height="562" alt="image" src="https://github.com/user-attachments/assets/6d054171-e407-4cc2-8afd-2b127cb064f8" />


<img width="1280" height="562" alt="image" src="https://github.com/user-attachments/assets/ef13df44-c0c5-4957-be0b-691176649590" />

#### Diagrams

**System Architecture:**

          ┌──────────────────┐
          │  User Interface  │
          │  (HTML + CSS)    │
          └────────┬─────────┘
                   │
        ┌──────────┴──────────┐
        │      Application    │
        │    Logic (JS)       │
        │ - Timer             │
        │ - Session control   │
        │ - Reflection & Rating│
        │ - Analytics         │
        └──────────┬─────────┘
                   │
        ┌──────────┴──────────┐
        │  Storage / Data     │
        │ - LocalStorage      │
        │ - Session tracking  │
        │ - Total minutes     │
        │ - Reflections & Ratings│
        └─────────────────────┘

**Application Workflow:**

[Start: Home Screen]
         │
         ▼
[Select Focus Duration]
         │
         ▼
[Click Start]
         │
         ▼
[Timer Runs] ──────────────► [Update Circular Progress]
         │
         ▼
[End Session / Timer Complete]
         │
         ▼
[Reflection & Rating]
         │
         ▼
[Store Data in LocalStorage]
         │
         ▼
[Update Analytics Dashboard]
         │
         ▼
[Back to Home Screen / Next Session]
User chooses a focus session duration on the home screen.

Timer starts; circular progress shows session countdown.

User can stop early or let it complete.

After the session, user rates their focus and records distractions.

All session data is stored locally and analytics are updated.

User can start the next session, and the cycle continues.

#### Build Photos

<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/4e77d330-7eab-4b38-9e23-9ad63be0ab60" />


Home Screen 🏠

Duration selector dropdown

Start Focus Session button

Timer Screen ⏱️

Circular SVG timer

Time display (minutes:seconds)

Stop Session button

Reflection Screen 📝

Star rating system (1–5 stars)

Textarea for recording distractions

Submit Reflection button

Analytics Dashboard 📊

Display of completed sessions

Display of total focus minutes

(Future enhancement) Streaks and insights

Application Logic ⚙️

Timer countdown using JavaScript

Progress circle animation

Session data storage in localStorage

Rating and reflection handling

Styles & UI Effects 🎨

Gradient animated background

Glassmorphism container

Hover effects on buttons

Fade-in animations

![Build](Add photos of build process here)
*Explain the build steps*

<img width="1280" height="562" alt="image" src="https://github.com/user-attachments/assets/89ec8239-c735-4a7d-842c-65a7723cf821" />
How It Works

Home Screen 🏠

Users select the duration of their focus session (1, 5, 10, or 25 minutes) using a dropdown.

Clicking Start Focus Session transitions to the timer screen.

Focus Timer ⏱️

A circular SVG timer shows real-time countdown.

The timer dynamically updates the progress circle and the numeric display.

Users can stop the session early, which transitions them to the reflection screen.

Reflection & Rating 📝⭐

After completing or stopping a session, users can rate their focus using a 1–5 star system.

Users can also record distractions in a textarea.

This feedback is stored in the browser’s localStorage for persistence.

Analytics Dashboard 📊

Tracks completed sessions and total focus minutes.

Can be expanded to show streaks, trends, and focus insights.

User Interface & Design 🎨

Modern gradient animated background with smooth transitions.

Glassmorphism-style container with blur effect for focus.

Hover effects and fade-in animations make the app visually engaging.


## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:** `https://api.yourproject.com`

##### Endpoints

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
```

---

### For Hardware Projects:

#### Bill of Materials (BOM)

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹450 | [Link] |
| LED | 5 | Red, 5mm, 20mA | ₹5 each | [Link] |
| Resistor | 5 | 220Ω, 1/4W | ₹1 each | [Link] |
| Breadboard | 1 | 830 points | ₹100 | [Link] |
| Jumper Wires | 20 | Male-to-Male | ₹50 | [Link] |
| [Add more...] | | | | |

**Total Estimated Cost:** ₹[Amount]

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

---

### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]
```

**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does

**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information

**Examples:**

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```

#### Demo Output

**Example 1: Basic Processing**

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```

**Example 2: Advanced Usage**

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```

**Command:**
```bash
python script.py -v --format json data.json
```

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```

---

## Project Demo

### Video
https://drive.google.com/file/d/1JCtp4Uj0r6AZAEynHQIH9_lkQt33rOqu/view?usp=sharing

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** chat gpt

**Purpose:** [What you used it for]
 "Code review and optimization suggestions"

**Key Prompts Used:**
- "Optimize this database query for better performance"

**Percentage of AI-generated code:** [Approximately 40%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- [Name 1]: [Specific contributions - e.g., Frontend development, API integration, etc.]
- [Name 2]: [Specific contributions - e.g., Backend development, Database design, etc.]
- [Name 3]: [Specific contributions - e.g., UI/UX design, Testing, Documentation, etc.]

---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
