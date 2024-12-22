# CF Solve Counter - by FA3

A Chrome extension designed to enhance the Codeforces experience by providing real-time statistics on solved problems and quick access to problem sets of different ratings.

## Features

1. **Solved Problem Counter**

   - Displays the number of attempted and solved problems on the current Codeforces Problemset page.

2. **Popup Menu**

   - Provides quick navigation links to Codeforces problem sets filtered by ratings (e.g., 1000, 1100, 1200).

## Motivation

As a competitive programmer, I wanted to improve my practice routine by solving 5 problems daily from different rating categories (1000-1400). My plan was to solve problems from the first page of each category. While looking for an extension to show the number of solved problems per page, I couldn't find one. Hence, I decided to create this extension. The additional popup menu makes navigation even more convenient.

## Screenshots

### Solved Problems Counter

<img width="959" alt="Screenshot 2024-12-22 230728" src="https://github.com/user-attachments/assets/28d918cf-f507-4564-bfa1-81af02c9791a" />

### Popup Menu

<img width="959" alt="Screenshot 2024-12-22 230909" src="https://github.com/user-attachments/assets/60e81ed1-a30e-4da5-91ab-e087989a5783" />

## Installation

1. Clone or download this repository.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer Mode** (toggle in the top-right corner).
4. Click on **Load unpacked** and select the extension folder.

## How It Works

### Content Script

- Inspects into Codeforces Problemset pages to count number of accepted and rejected problems. Then displays accepted problem as Solved provlems and displays total of accepted and rejected problem as attempted problems.

### Popup Menu

- Provides hyperlinks to different problem ratings, helping users jump directly to their desired categories.

### Settings

- Ensure that the "Hide solved problems" option is unchecked to display all solved problems properly.
<img width="224" alt="Screenshot 2024-12-22 231701" src="https://github.com/user-attachments/assets/be839f86-366a-4103-810c-beb7778c7fa3" />

## Usage

1. Navigate to any Codeforces Problemset page.

2. View the counter at the bottom-left corner showing:

   - **Attempted Problems**: Total problems you've interacted with.
   - **Solved Problems**: Successfully solved problems.

3. Click on the extension icon to open the popup menu and navigate to problems by rating.

