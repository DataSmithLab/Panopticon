# Panopticon Rules & Instructions

## 1. Settings

### 1.1. Resources In This Game:
- **Data Points**: Each player starts with **1000 Data Points**. Data Points are used for various actions within the game, such as proposing designs, winning inquiries, revising designs, and other in-game activities.
- **Trust Score**: Unlike Data Points, the Trust Score is not tied to individual players but to the slots they occupy on the board. When a player claims a slot for their design, the **Trust Score for that design starts at 15**.
  - The Trust Score can decrease if valid inquiries are made against the design.
  - If a design's Trust Score falls below **0**, the player loses ownership of that slot, which yields one available slot in that digital type.

### 1.2. Hypotheses Questions In This Game:
- When players land on a service type space and decide to claim the land, they will roll the dice to randomly draw a hypothesis question, which is designed to be tested by the respective digital services within the game.

### 1.3. Board Layout: 24 Spaces in Total

<div align="center">
  <a href="figures/Colored_Game_Board.png">
  <img src="figures/Labeled_GameBoard.png" width="1000"/>
</div>

- **14 Digital Service Spaces**
  - **Digital Service Space Types:**
    - Social Networking Apps (Facebook, Instagram, Snapchat, Zoom, etc.)
    - Health & Fitness (Strava, AutoSleep, Nike Run Club, Calm, etc.)
    - Productivity Apps (Notion, Notability, Trello, Google Calendar, etc.)
  - **Slot Limitation**: Each type of digital space will have one slot for experimental design. This means that at any given time, only one unique design idea can be proposed for each type.
  - **Consistency Across Board**: Even if a digital space type (e.g., "Social") appears multiple times on the board, the design ideas within those spaces must be the same. For example, if "Social" appears three times, the designs proposed in all "Social" spaces should be consistent and limited to the unique design ideas allowed.
- **4 Corner Spaces:**
  - **Go (Start)**: Players start at this place.
  - **Data Reboot**: Players have **1 min 30 sec** to revise their experimental designs without any costs.
  - **Patent Piracy**: Players can claim another player's space by paying the required fee and drawing a random question to replace the existing design with their own within **2 min**.
- **4 Special Action Spaces:**
  - **Insightful Inquiry**: Players must inquire about one of the existing designs when landing on this space. The landowner will have **1 min** to revise their designs based on the inquiry.

## 2. Game Rules

### 2.1. Starting the Game:
- Players roll the dice to determine the order of play. The player with the highest roll will draw a theme card from the deck of theme cards and will also go first.
- Place your token on the "GO" space.

### 2.2. Moving Around the Board:
- Roll the dice and move your token the number of spaces indicated.
- Follow the instructions on the space you land on, which may include claiming a digital service slot, receiving research grants, etc.

### 2.3. Landing on a Service with an Empty Slot(s):
- **Claiming the Slot:**
  - Sketch your data science experimental design intended to test the corresponding hypothesis.
  - Pay a **one-time claim fee** (Refer to Table 1).
- **Choosing Not to Claim:**
  - You become a user of that digital service type instead.
  - You will need to give some of your **data points** to the service providers (Refer to Subscription Fee in Table 1). The data points should be equally shared between the service providers.
  - After paying the data points, you may also choose to critique the existing design in the current service type.
- **Critiquing an Existing Design:**
  - Before coming up with your inquiries, you may ask the design owner clarification questions about the design to better understand its details and functionality.
  - The judge scores your critique based on the rubric (Figure 1).
  - **Critique Levels:**
    - **Score ≤ 4**: Invalid, no rewards.
    - **Score > 4**: Valid, you receive a reward of `(average score * 10)` data points and Trust Score redemption (Refer to Table 2).
  - If the critique passes, the owner of that design decides whether to revise the design with this suggestion.
  - If the owner **agrees to revise**, other players cannot apply this critique until the owner has revised.
  - If the owner **refuses**, the game continues.

### 2.4. Landing on a Service with No Empty Slots:
- Pay **data points** to the service provider (Refer to Subscription Fee in Table 1).
- Critique existing designs (Refer to 2.3.2 and 2.3.3).
- If a critique drops a design's **Trust Score to 0 or below**, you may **claim a new design** for that service type immediately, or the slot will be available to other players.

### 2.5. Landing on a Service with Your Own Design (Critiquing & Revising Rules):
- **Revising Based on a Valid Critique:**
  - You can only revise it the next time you land on the corresponding service type.
  - Pay a **revising fee** of **250 Data Points** (Refer to Table 2).
  - If the critique targets a specific node, all nodes after it can be revised simultaneously.
  - Trust Score increases according to the “Trust Score Redemption” in Table 2.

### 2.6. Who Wins?
- The game continues until **a player bankrupts** or **the agreed session time is reached** and the player with the most **Data Points** wins.

## Appendix

### Table 1: Claim and Subscription Fees for Each Service Type
| Service Type         | Claim Fee | Subscription Fee |
|----------------------|-----------|------------------|
| Health & Fitness    | 450       | 300              |
| Social Networking   | 450       | 300              |
| Productivity        | 450       | 300              |

### Table 2: Levels of a Critique and Corresponding Revising Fee
| Range (exclusive, inclusive] | Fixed Revising Fee | Trust Score Redemption |
|------------------------------|--------------------|------------------------|
| Level 1 Critique (11, 15]    | 250                | +11                    |
| Level 2 Critique (5, 11]     | 250                | +5                     |
| Level 3 Critique (4, 5]      | 250                | +4                     |

### Figure 1: Critique Score Rubric
![Critique Score Rubric](https://github.com/DataSmithLab/Panopticon/blob/main/figures/Fig1.png)
