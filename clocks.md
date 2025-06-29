# Ultimate Clock‑Math Notes  
*For Middle‑School & Early Olympiad Students*  

---

## 1. Anatomy of a Clock

| Part | Description | Key Facts |
|------|-------------|-----------|
| **Hour Hand** | Short, moves once around the dial every 12 h | 0.5° per minute (30° per hour) |
| **Minute Hand** | Long, moves once around the dial every 60 min | 6° per minute |
| **Second Hand** | Thin, moves once around the dial every 60 s | 6° per second |
| **Dial** | Circle divided into 12 major marks (hours) and 60 minor marks (minutes/seconds) | Full circle = 360° |

---

## 2. Reading & Writing Time

### 2.1 12‑Hour vs. 24‑Hour Formats

| 24‑Hour | 12‑Hour | Notes |
|---------|---------|-------|
| 00:00 | 12:00 AM (midnight) | Start of day |
| 12:00 | 12:00 PM (noon) | Midday |
| 18:45 | 6:45 PM | Subtract 12 for PM times > 12:59 |
| 23:59 | 11:59 PM | One minute before midnight |

**Conversion Rules**

1. **24 → 12**:  
   - If hours = 0, write 12 and add “AM”.  
   - If 1 – 11, keep as is and add “AM”.  
   - If 12, keep 12 and add “PM”.  
   - If 13 – 23, subtract 12 and add “PM”.

2. **12 → 24**:  
   - “AM” (except 12 AM) → keep hours; if 12 AM, write 00.  
   - “PM” (except 12 PM) → add 12; if 12 PM, keep 12.

### 2.2 Digital vs. Analog

- **Digital**: HH:MM (and sometimes :SS).  
- **Analog**: Position of hands; each minute mark equals 6°.  

---

## 3. Elapsed Time & Time Arithmetic

| Scenario | Method |
|----------|--------|
| Same half‑day (e.g., 9:15 AM → 11:50 AM) | Subtract directly: 2 h 35 min |
| Across noon/midnight (e.g., 10:20 PM → 1:05 AM) | Convert both to 24‑hour, then subtract (optionally add 24 h to end time) |
| Word problems (buses, races) | Draw a timeline or use T‑chart: *Start → End = Duration* |

**Tip:** Break at the hour mark if subtraction crosses an hour (e.g., 7:52 → 9:10: first 8 min to 8:00, then 1 h 10 min).

---

## 4. Angles on a Clock Face

### 4.1 Core Formulas

1. **Minute Hand Angle (from 12)**  
   \[
   \theta_m = 6M \quad (\text{degrees})
   \]

2. **Hour Hand Angle (from 12)**  
   \[
   \theta_h = 30H + 0.5M
   \]

   - \(H\) in 12‑hour format (0–11).  
   - \(M\) in minutes (0–59).

3. **Angle Between Hands**  
   \[
   |\theta_h - \theta_m|
   \]
   If > 180°, subtract from 360° to get the smaller angle.

### 4.2 Standard Angles

| Time | Angle |
|------|-------|
| 3:00 | 90° |
| 6:00 | 180° |
| 9:00 | 90° |
| 12:00 | 0° or 360° |

---

## 5. Coincidence, Opposition & Right Angles

### 5.1 Relative Speed

- Minute hand speed = 6°/min  
- Hour hand speed = 0.5°/min  
- **Relative speed** (minute vs. hour) = 5.5°/min

### 5.2 Overlap (Coincidence)

\[
M = \frac{60}{11}H \quad (H = 0,1,\dots,11)
\]

- **Times in one 12‑hour cycle**: 11 overlaps (e.g., 1:05.45, 2:10.91, …).

### 5.3 Opposite (180° Apart)

\[
M = \frac{60}{11}(H + 6)
\]

- Yields 11 oppositions in 12 h (22 per day).

### 5.4 Right Angles (90° Apart)

\[
M = \frac{60}{11}\Bigl(H \pm \frac{3}{2}\Bigr)
\]

- Two right angles between each consecutive hour mark (22 per 12 h).

---

## 6. Seconds‑Hand Problems

### 6.1 Triple Coincidence (All Three Hands)

- **Relative speeds**:  
  - Second vs. minute = 360°/60 s − 360°/3600 s = 354°/60 s = 5.9°/s  
  - Minute vs. hour = 5.5°/min  
- First triple overlap after 12:00 occurs at ≈ 1 h 5 min 5.455 s.

### 6.2 Second–Minute Alignment

\[
\text{Second} = \frac{60}{59}M
\]
Occurs every 59 s.

---

## 7. Fast, Slow & Broken Clocks

| Type | Key Idea | Sample Problem |
|------|----------|----------------|
| **Fast Clock** | Gains \(x\) minutes every hour | “A clock gains 4 min per hour; what will it show after 6 real hours?” |
| **Slow Clock** | Loses \(y\) minutes every hour | “A clock is 10 min slow at 8:00 AM and loses 2 min per hour; when will it be correct?” |
| **Stopped Clock** | Reads the same time | “A stopped clock is correct twice a day.” |
| **Wrongly Set** | Starts at wrong initial position | “Clock set to 12:00 at 2:00 PM; find next alignment.” |

---

## 8. Time Zones & World Clocks (Optional Extension)

- **UTC Offsets**: Each 15° of longitude ≈ 1 h difference.  
- **Daylight Saving**: Adjust by ±1 h in certain regions.  
- **International Date Line**: Crossing east → subtract a day; west → add a day.

---

## 9. Problem‑Solving Strategies

1. **Draw a Dial**: Sketch positions for visual clarity.  
2. **Use Relative Motion**: Treat one hand as stationary; compare speeds.  
3. **Set Up Equations**: Convert word problems into algebraic form.  
4. **Check Reasonableness**: Overlaps must be slightly after each exact hour mark.  
5. **Memorize Benchmarks**:  
   - Overlaps every 65 4⁄11 min.  
   - Right angles every 32 8⁄11 min.  
   - Oppositions every 65 5⁄11 min.

---

## 10. Practice Problems (Progressive Difficulty)

### 10.1 Fundamentals
1. Convert 04:35 to 12‑hour format.  
2. How many minutes from 7:48 AM to 8:12 AM?  
3. A clock shows 11:20. Advance it by 95 min.

### 10.2 Angle Calculations
4. Find the angle at 2:50.  
5. At what time between 7 and 8 is the angle 60°?  
6. Determine the smaller angle at 12:49.

### 10.3 Coincidence & Alignment
7. When are the hands opposite between 3 and 4?  
8. List all right‑angle times between 9 and 10.  
9. How long after 5:00 will the hands overlap?

### 10.4 Seconds‑Hand Challenges
10. When will the minute and second hands first align after 12:00?  
11. Find the next triple coincidence after 4:00.  

### 10.5 Advanced Olympiad
12. A clock gains 3 min every 2 h. It is correct at noon. When will it next show 6:00 exactly when the true time is 5:48?  
13. Two identical clocks start together. One runs normally; the other loses 5 s per minute. After how many real minutes will they first show the same time again?

---

## 11. Quick Reference Cheat Sheet

| Concept | Formula |
|---------|---------|
| **Minute Hand Angle** | \(6M\) |
| **Hour Hand Angle** | \(30H + 0.5M\) |
| **Angle Between Hands** | \(\bigl|30H - 5.5M\bigr|\) (then adjust to ≤ 180°) |
| **Overlap Times** | \(M = \dfrac{60}{11}H\) |
| **Opposite Times** | \(M = \dfrac{60}{11}(H + 6)\) |
| **Right‑Angle Times** | \(M = \dfrac{60}{11}\bigl(H \pm \tfrac{3}{2}\bigr)\) |
| **Overlap Interval** | 65 4⁄11 min |
| **Right‑Angle Interval** | 32 8⁄11 min |

---

### Final Tip  
Practice regularly with both **quick drills** (to build speed) and **multi‑step Olympiad problems** (to deepen reasoning). Keep a small analog clock or an online simulator handy—moving the hands yourself cements understanding better than any formula sheet!