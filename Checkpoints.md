# Checkpoints

1. &nbsp;
   1. &nbsp;
      1. A CHECKPOINT is a timing point wherein cards or counters that have entered an illegal state are corrected, expired effects are removed, and other important conditions are checked. This procedure is automatically performed at several timing points during the game, and entails the following steps, which are performed in order:

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. Each active conditional ability looks at the changes to the game state since the beginning of the last checkpoint to see if its condition has been met. **Any ability that has met its condition creates the appropriate instances of itself and marks them as pending, as described in section 9.6.**
         1. Any ability with a duration that has passed is removed from the game state.

&nbsp;

*Example: During the checkpoint that follows the end of an encounter, abilities that increased the strength of an icebreaker during that encounter expire and the icebreaker’s strength is correspondingly lowered.*

*Example: The Corp has Targeted Marketing in the play area when the Runner steals an agenda. In the next checkpoint, the game recognizes that the ability on Targeted Marketing that was preventing the operation from being trashed no longer applies, and so the Corp trashes Targeted Marketing as if it were completing its resolution.*

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. If the agendas in either player’s score area total 7 or more agenda points, that player wins the game. If both players would win this way simultaneously, the game ends in a draw.
         1. If two or more unique cards with the same name are active, for each such name, all of those cards except the one that became active most recently are trashed.
         1. If any cards or counters break any restrictions of card abilities or the game rules (such as the Runner’s memory limit) or are installed or hosted in an illegal location, a minimal set of those cards or counters are trashed. If there are multiple distinct minimal sets of installed cards that could be trashed such that the remaining cards are installed legally and one player controls all the cards in those sets, that player chooses which set to trash. If the sets contain cards controlled by both players, the active player chooses. If there are multiple distinct minimal sets of hosted cards and counters that could be trashed such that the remaining hosted objects are legal, the player who controls the host card determines which of those sets is trashed.

*Example: The Runner has installed programs with total memory cost equal to their memory limit when the Corp plays Bad Times, reducing the memory limit by 2\[MU\]. The Runner can trash any two programs with a memory cost of 1\[MU\], or any one program with a memory cost of 2\[MU\] or greater. They cannot trash any 0\[MU\] programs, nor can they trash any set of more than one program with a greater total memory cost than 2\[MU\], since those choices would not represent a minimal set of cards to trash.*

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. Any cards or counters that were hosted on an agenda that moved from a score area to any zone other than a score area are trashed.
         1. Any cards or counters that were hosted on an installed card that was uninstalled are trashed, **except for cards or counters that are temporarily in the set aside zone because of rule 9.5.5.** This step is repeated until no more cards or counters are trashed.

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. Any remote server with no cards either in or protecting it and no cards in the process of being installed with a destination in or protecting it ceases to exist.
         1. Any cards in discard piles that had been converted into counters or agendas return to their printed characteristics.
         1. Any counters in a discard pile are returned to the bank.

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. After a checkpoint is completed, if it marked any conditional abilities as pending, a new reaction window immediately opens to handle those abilities, even if this takes place during another reaction window. After a reaction window closes, the game proceeds to whatever timing step or priority window was due to occur after the checkpoint that caused it to open.
      1. Whenever a player would receive priority, first a checkpoint occurs. See also section 9 .2.4.
      1. Whenever a player pays a cost, a checkpoint occurs immediately afterward, before continuing with the effect or timing structure in which the cost was paid. See also section 1 .15.
      1. Whenever all the steps of a timing structure have been completed, a checkpoint occurs. During this checkpoint, the timing structure is considered to have ended for purposes of meeting the trigger conditions of conditional abilities and disabling effects with a duration matching the completed timing structure. After the checkpoint, any abilities that have become pending **are handled** normally. Finally, the game proceeds to the next appropriate timing structure. See also section 9.2.2.
      1. While resolving the effects of a card ability, a checkpoint occurs in between each separate instruction. See section 9.9.

***
_Created with the Personal Edition of HelpNDoc: [Free Web Help generator](<https://www.helpndoc.com>)_
