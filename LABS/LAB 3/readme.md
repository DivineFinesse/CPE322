# Lab 3 — Python

## Overview
This lab involved running various Python scripts that utilized external libraries like **jdcal, astral, and geopy** for data processing.

## Steps Taken
1. Navigated to the `iot` repository and switched to the **Lesson 3** folder.
2. Installed required packages using:
   ```powershell
   pip install jdcal astral geopy
   ```
3. Ran the following scripts:
   - **julian.py** → Converted dates to Julian format.
      ![halfadder](halfadd.png)
   - **sun.py "New York"** → Retrieved sunrise and sunset times.
      ![halfadder](halfadd.png)
   - **coordinates.py "Samuel C. Williams Library"** → Got latitude & longitude.
      ![halfadder](halfadd.png)
   - **documentstats.py document.txt** → Processed text document statistics.
      ![halfadder](halfadd.png)

## Additional Findings
- Had to manually install `geopy` due to dependency conflicts.
- The `address.py` script required an internet connection for geolocation.
- Used **Terminal** instead of Bash for execution.

---
