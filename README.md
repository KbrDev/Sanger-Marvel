/* Choice widgets */

<<Action "Link text" EnergyCost TimeCost "Passage" "Other consequences">>

<<Decision "Link text" "Passage" "Other consequences">>

<<ConditionalAction "Link text" EnergyCost TimeCost "conditional1" min_val1 "conditional2" min_val2 "Passage" "Other consequences">>


/* Chat widgets */

<<Chat $CharVariable "Text">>

<<Thought "Text">>

<<Body "Text">>


/* Purchase widget */

<<Purchase "Item Name" Price "Other consequences">>


/* Image widget */

<<Image "image_address">>


/* Examples */

<<ConditionalAction "Test3" 40 1 "knowledge" 2 "willpower" 2 "Test" "<<set $Levels.FitnessXP to 100>>">>

<<Decision "Open the door" "Scene 2">>

<<Action "Test2" 120 1 "Test" "<<set $Levels.FitnessXP to 100>>">>

<<Purchase "Test4" 150>>
