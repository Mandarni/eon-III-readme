# Eon III
Welcome to Eon III, an immersive role-playing experience where epic adventures await! In this captivating tabletop RPG system, you will embark on thrilling quests, explore fantastical realms, and unleash the power of magic. With its unique mechanics and engaging gameplay, Eon III offers an unforgettable journey for both seasoned players and those new to the world of tabletop gaming.

In Eon III, you'll discover a dynamic system that combines strategic decision-making with thrilling dice mechanics. The Ex System introduces exploding dice, adding a dynamic element to tests and combat, where high rolls can lead to additional dice being rolled, increasing your chances of success. Whether you're engaging in a crucial battle or attempting a challenging task, the Ex System keeps you on the edge of your seat, creating moments of tension and excitement.

The magic system in Eon III is a realm of wonder and intricacy. As a spellcaster, you'll navigate the art of conjuring and weaving filaments, each with its own distinct properties. The choices you make in filament selection, transmutation, and successful weaving of effects shape the outcome of your spells. Specialize in a specific type of magic and become a master of its arcane secrets, whether you choose to harness the destructive power of fire or the enigmatic forces of the mind.

But beware, for the world of Eon III is not without its perils. The health system diverges from traditional hit points, introducing a multi-faceted approach to physical well-being. Trauma, pain, bleeding, blood loss, exhaustion, and the risk of unconsciousness and death all intertwine to create a realistic and challenging portrayal of your character's resilience. Careful management of these factors becomes crucial to survival, as neglecting injuries or pushing beyond your limits can have dire consequences.

Eon III invites you to become the hero of your own epic tale, where your choices shape the narrative and your character's destiny. Craft your persona, whether a brave warrior, a cunning rogue, or a mystical sorcerer, and set forth into a world brimming with adventure and mystery. With each step, you'll uncover secrets, encounter formidable foes, and forge alliances that shape the course of your journey.

So gather your companions, grab your dice, and let the world of Eon III ignite your imagination. Prepare for a grand adventure where danger and triumph await at every turn. Welcome to Eon III, where legends are born and epic tales come to life!

 ## Ex System
 In the Eon system, the Ex system utilizes exploding dice mechanics. When rolling dice for any test or damage, such as Ex3d6 to succeed at a normal difficulty task, the following process is followed:

 1. Roll the specified number of dice, in this case, three six-sided dice (d6).
 2. If any of the dice roll a maximum value of 6, replace that 6 with two new dice and add their results to the total.
 3. Continue this process for each additional 6 rolled, replacing it with two new dice until no more 6s are rolled.

For example, if you roll 1, 5, 6, you replace the 6 with two new dice and obtain results of 1, 5, 3, 4. The total would then be calculated by summing all the rolled numbers.

This exploding dice mechanic introduces a dynamic element to the outcomes, as high rolls can lead to additional dice being rolled, potentially increasing the result.


## Health System
The health system in Eon III takes a different approach compared to traditional health points. Instead, it introduces various elements that reflect the physical condition and endurance of a character. The system incorporates trauma, pain, bleeding, blood loss, exhaustion, and the risk of unconsciousness and death. Here's an overview of these components:

* Trauma: Injuries inflicted on a character can result in trauma. Accumulated trauma can have severe consequences, potentially leading to unconsciousness or even death. If a character's trauma reaches a critical level, they must make Death saves to avoid succumbing to their injuries.
* Pain: Alongside trauma, characters also experience pain from injuries. Excessive pain can cause a character to lose consciousness. When a character's pain reaches a certain threshold, they must make Chock saves to prevent falling unconscious.
* Bleeding and Blood Loss: In Eon III, wounds can cause bleeding. As the rounds progress, accumulated bleeding can lead to blood loss, which further weakens the character. Blood loss can have detrimental effects and increase the risk of death. Managing bleeding and addressing wounds promptly becomes crucial in sustaining a character's survival.
* Exhaustion: Engaging in intense physical activities like combat or extended running can result in exhaustion. The more exhausted a character becomes, the more their abilities and chances of success are affected. Managing exhaustion levels is important to maintain optimal performance in strenuous situations.

These various components interact to create a dynamic and immersive health system. The accumulation of trauma, pain, bleeding, blood loss, and exhaustion adds depth and realism to the challenges faced by characters. Players must carefully manage their character's condition, as the consequences of neglecting or mishandling injuries can be severe.


## Magic System
The magic system in Eon emphasizes the process and challenges of casting spells. It involves several steps that must be successfully completed to cast a spell:

* Conjure Filaments: To begin casting a spell, the caster must conjure the filaments, which are the strands that make up the magical effect. Spells can utilize multiple filaments, and each filament has a specific type, such as fire or heat. The caster needs a nearby natural source related to the filament's type. For example, to conjure fire filaments, a fire source would be required.

* Transmute Filaments: In some cases, the caster may need to transmute the filaments if they are of an inappropriate type for the desired effect. Transmutation involves changing one type of filament into another. It is easier to convert filaments that are related (e.g., fire into heat), but impossible to convert incompatible types (e.g., fire into cold).

* Weave Effects: Once the filaments are conjured and potentially transmuted, the caster must weave the individual effects of the spell. Each effect requires a separate roll. The difficulty of weaving each effect is determined by the Ex-dice (e.g., Ex5d6) where a higher number of exploding dice drastically increase the difficulty.

For example, the spell "Bzarons Quick Recovery", which is a healing spell that recovers Trauma, mitigate Pain and recover Stamina, consists of the following steps:

1. Harness 5 filaments of Biotropy (Ex5d6).
2. Transform some filaments into Astrotopy (Ex3d6).
3. Weave the effect to heal Trauma (Ex2d6).
4. Weave the effect to heal Pain (Ex1d6).
5. Weave the effect to recover Stamina (Ex2d6).

Successfully completing each step is necessary to cast the spell and achieve its intended effects. The Ex-dice for each step determine the level of difficulty in successfully casting the spell. Simple spells might only take a single round to cast, while more complicated spells might take several rounds. 

The Eon system's magic system provides versatility, requiring strategic choices in filament selection, transmutation, and successful weaving of effects. Due to each type of filament being its own skill, many chose to specialize in a select group of magic. Which makes for thematic characters, such as Psychomancers, Pyromancers, etc. 

It adds depth and complexity to magical abilities, making spellcasting an engaging and challenging aspect of gameplay.


# Development roadmap

## Milestone 1: Dice Mechanics
* [X] Implement the "exploding dice" system. This will involve coding the dice to reroll and accumulate totals under certain conditions (usually a maximum roll).
* [X] Implement other dice mechanics specific to Eon III, if any.
* [X] Develop a system for attribute-based dice rolls.
* [X] Implement a testing mechanism for these dice systems.

## Milestone 2: Health System
* [X] Develop the process for tracking character health.
* [X] Integrate the health system into the Health tab.
* [X] Develop the mechanic that adjusts the number of dice rolled based on the initiation of a new row of pain points beyond the first. This needs to account for different attributes that determine the number of columns in the pain points row.
* [X] Thoroughly test this mechanic with different numbers of pain points and attribute values.
* [X] Develop a similar mechanic for exhaustion points, taking into account that it affects difficulty every third row (i.e., 3, 5, 7, etc.).
* [X] Implement Pain and Exhaustion Difficulty Modifiers
* [X] Test the exhaustion mechanic thoroughly with different numbers of exhaustion points and attribute values.

## Milestone 3: Implement Base Task Difficulty
* [X] Create a method to define the base difficulty level of tasks, which will determine the base number of exploding dice rolled.
* [X] Implement an interface for GMs or players to set the difficulty level of a task, probably through a popup window.
* [X] Test the implementation of base task difficulty levels with different tasks and difficulty levels.

## Milestone 4: Items
* [ ] Develop systems for item usage, inventory management, and item effects.
* [ ] Integrate these systems into the Items tab.

## Milestone 5: Skills System Expansion
* [X] Improve the ObXd6 dice results so that the result is portrayed in an intuitive manner for the users, such as result, effect, etc.
* [ ] Develop systems for skill advancement, use, and testing, including integration with the dice system.
* [ ] Expand the existing Skills tab with these additional features.
* [ ] Implement a system for unique or unusual skills, including custom skills.
* [ ] Build a function to calculate the success or failure of a task, based on dice roll results and the character's skill level.
* [ ] Ensure that this function works with the difficulty modifiers from Milestones 1 and 2.
* [ ] Test this comprehensive system with a variety of skill levels, difficulty levels, and character statuses.

## Milestone 6: Effects
* [ ] Define how status effects work in the system, and their interactions with health and skills systems.
* [ ] Develop the interface for managing status effects in the Effects tab.

## Milestone 7: Combat System
* [ ] Implement systems for status effects or conditions related to health.
* [ ] Implement damage and healing mechanics.
* [ ] Define combat mechanics, including attack and defense rolls, turn order, damage calculation.
* [ ] Integrate dice mechanics, skills, health, effects, and items into combat.
* [ ] Create the combat interface in the Combat tab.
* [ ] Implement a system such that exhaustion increases during combat when players take actions.

## Milestone 8: Magic System
* [ ] Define magic mechanics, including casting spells, the use of magic points or equivalent, and spell effects.
* [ ] Implement dice mechanics and effects into the magic system.
* [ ] Create the magic interface in the Spells tab.
* [ ] Implement a system for learning, preparing, and using spells.

## Milestone 9: Character Features
* [ ] Develop systems for defining character features, including unique advantages and disadvantages.
* [ ] Define how race and gender influence character features and mechanics.
* [ ] Integrate these features into the character sheet.

## Milestone 10: Compendium Packs
* [ ] Develop a system for organizing and populating the Compendium Packs.
* [ ] Populate Compendium Packs with content for monsters, races, and rules.
* [ ] Begin documenting the system and all its functions, ensuring that any user can understand how to use and troubleshoot the system.
* [ ] Test the guide with users who are new to the system and adjust based on feedback.
* [ ] Publish the guide and make it easily accessible to users.

## Milestone 11: Character Creation
* [ ] Develop a system to guide players through creating a character, including a step-by-step process prompt.
* [ ] Integrate this process into the character sheet, activating upon the first time a player opens it.

## Milestone 12: UI/UX Polish and System Testing
* [ ] Refine user interface and user experience across all tabs.
* [ ] Perform system-wide testing, debugging, and balancing.
* [ ] Gather user feedback and implement necessary changes.
* [ ] Gather feedback from users on any issues or difficulties they encounter while using the system.
* [ ] Refine and optimize the system based on the feedback received, addressing any bugs and usability issues.
* [ ] Regularly update the guide and documentation to reflect any changes made in this milestone.


# Version History

0.3.1
* Added difficulty popup window with very easy - very difficult buttons

0.2.1
* Added a proto-version of the health system, moving on to milestone 3.

0.1.4
* Reworked the UI/UX of the dice output

0.1.3
* Revised README
* Added difficulty modifiers due to exhaustion and pain to difficulty of skills.

0.1.2
* Got a working trauma, pain, exhaustion, bleed and bloodloss GUI in place, that stores the values correctly. Still need to tie in the mechanics of the consequences of being exhausted, in pain, hurt, etc. 

0.1.1
* Work has begun on the health system. Implemented the design for the health tab and now need to get it to work.

0.1.0
* Milestone 1 has been achieved. Now we got a fully functioning exploding dice system. 

0.0.5
* Exploding dice still needs more work, so that is next step. 
* Improved the aesthetics of the sheet with parchment textures and improved css schema. 


0.0.4 
* Next challenge to tackle is the exploding dice, since it underpins many systems. 
* Skill section functions properly now, except for the roll-behaviour, which requires implementation of exploding dice. 


# Known bugs
* None known at the moment.


# Contact
alexander.nielsen@gmail.com
