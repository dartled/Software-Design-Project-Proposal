# Identifying A Need

Idea: Tower Defense Game

Need: Enhance critical thinking and strategy within players by creating an enjoyable and challenging tower defense game which can improve logical thinking, decision making, resource management.

Problem Statement: A tower defense game requires players to defend a tower from enemies by using (in-game) money to buy units. This can train decision-making and resource management within the target audience.

Skill Development: Strategy, Planning, Resource Management

# Requirements Outline:

__Inputs:__
- User inputs will primarily include mouse clicks for placing and upgrading units. Further, keyboard shortcuts will possibly be added for purposes such as quick unit placement (using numbered keyboard keys) and quick upgrade (using a set keyboard key).. 
Upgrading units will increase damage and range of said unit

__Processing:__
- Placement: The program will detect mouse clicks. If a unit is selected and the mouse is clicked, then the program will place the unit.
- Enemies: The program will move enemies along a set path, checking whether the enemies are in range of any placed units. Further, the program will gather the set damage statistics of the units that the enemy is within range of, and calculate the new health of the enemy, updating the enemy health accordingly. If enemies reach the end of the path or at the tower being defended, the program will stop the game and trigger a ‘stage fail’ visual. 

__Outputs:__
- Graphics: The game will display the units that were placed, the map, and the enemies
- Waves: The game will display current wave/total wave
- Health: The game will display a health bar of the tower (or whatever is being defended) and any bosses with a numerical value displaying current health/total health. There will also be a visual indicator of the health of the enemies.
- “Stage Failed”: Once enemies reach tower defended, the game will display a “stage failed” visual containing total damage, time taken, and what wave the player got up to.
- Leaderboards: The game will display leaderboards for things such as fastest clear, most damage, tournaments, etc.

__Transmission:__
- Leaderboard: The game will send scores (for tournaments) to an online, viewable leaderboard

__Storage:__
- The game will store the user’s progress and settings online so that their progress will get saved and synced even on multiple devices.



# Functional Requirements:

__User Interaction:__
- Users will primarily interact with the game using keyboard keys (for shortcuts and selecting units) and mouse clicks (for placing units)
- Actions: Users will be able to upgrade or sell their units by clicking on a placed unit and selecting what action they want to perform.

__Core Gameplay or Simulation Mechanics:__
- Players will begin with a set amount of currency which is used to buy and upgrade units. Enemies spawn in waves. The more waves have passed, the enemies get stronger/spawn more. After every wave, players will get more currency. Once they have enough currency, they will be able to place or upgrade the unit of their choice. Once placed, a unit will be able to hit enemies within its range. At the final wave, a boss will spawn. - Some stages may have a % chance to give the player a unit.

__Scoring and Feedback:__
- Very small amounts of currency are awarded for each enemy defeated. Main amount of currency awarded after every wave.
- End of game message: Displays whether the player failed or passed the wave, and displays statistics of that clear (amount of kills, dmg, etc.)
- Feedback: Visual or sound effects of unit attacks
- Scoring: Scoring will primarily be used for tournaments, certain statistic (eg. amount of damage) will be used to determine placing on the leaderboard.

__Level Progression:__
- By clearing/completing a stage (defeating all the waves and the boss) the player will gain access to the next, harder one. 
There will be achievements. By completing certain tasks, players will be able to complete an achievement and gain rewards. For eg. clearing ‘x’ amount of stages or completing all the stages.

__Saving and Loading Data:__
- Saves the player’s game data after every wave cleared.
- Settings will have an “apply’’ button, and are saved after applied
- Saved data will be stored remotely online, so that it can be accessed on multiple devices and be signed in or out.



# Non-Functional Requirements

__Performance Requirements:__
- The game should initially load in under 10 seconds. The stages should load under 5 seconds and respond to controls and unit placements without any noticeable lag. The stages should run fluidly without any graphical/visual interruptions or bugs.

__Usability Requirements:__
- The UI should be as simple and intuitive as possible, but should still look nice on the eyes. It should be easy to navigate to ensure that every feature is able to be exposed to the player to enhance their preferences and experience.
The game should include a clear tutorial to account for new players or those who would like to get immediate exposure to some of the mechanics. Further, this tutorial should have an option to be skippable, for those who already have experience within similar games or who are already familiar with the basic mechanics.

__Security Requirements:__
- Personal settings such as high scores or other in-game data will be stored securely online and will be encrypted and stored securely to ensure privacy of players. Further, The game will make use of secure login systems to allow users to access accounts on different devices.


## Consideration of Social and Ethical Issues

- Equity: Equity refers to fairness and justice and means to give everyone what they need to succeed. It is different to equality as it relates to giving in relation to what that person needs. For example, equality will mean giving a whole family all the same amounts of food, while equity will mean giving each family member the proportions of food in relation to how much they will need (younger family members may eat less then older family members)
- Accessibility: Accessibility refers to the practice of making information, activities and environments usable and meaningful for as many people as possible. An example will be adding elevators next to stairs so that people with disabilities (eg. broken leg) can still go up.

__Accessibility:__
- My game will be usable for a majority of people. My game will provide features such as control keybind customisation to ensure that this can more effectively adapt to user preferences, and visual settings (such as changing how large the text appears). By doing this, I can allow more accessibility for users with various preferences or needs.

__Privacy and Data Protection:__
- My game will collect user data for certain online features. For example, aspects like tournaments and leaderboards will be added, so scores will be put up on there. By entering a tournament, a player will agree to have their scores listed on the leaderboard. 

__Fairness and Representation:__
- My game will avoid any stereotypes or bias. The units/characters will be fictional and will avoid being referenced on any real person/people. By doing this, I can prevent any stereotypes or bias, which allows the game to be enjoyable for any player from any cultural or social group.

__Mental and Emotional Wellbeing:__
- My game will be designed as a strategic and fun challenge. Some mildly disturbing elements could be the defeating of enemies, however this will be as mild as possible. Further, the game will avoid the gacha/gambling route within unlocking units (you unlock new units as you progress, rather then rolling for new units). These will allow for a fun experience for the player, without inhibiting on mental and emotional wellbeing.

__Cultural Sensitivities:__
- My game will incorporate accepted and common symbols as well as non-religious themes to prevent any cultural misunderstanding and inappropriateness. Every visual and story element in my game will be thoroughly checked to make sure that they adhere to the appropriation of a broad range of cultures. I will also incorporate a clear message along the lines of "All aspects of this game are fictional, any reference to people, places, cultures, or things are coincidental and thus not intentional" for players to view before they first begin playing. By doing this, I can ensure that my game will not offend or get misinterpreted by anyone of any culture.