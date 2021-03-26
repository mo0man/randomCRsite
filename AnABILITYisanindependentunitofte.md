# An ABILITY is an independent unit of text on a card or counter or a basic action.

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. **All rules text on a card or counter is part of an ability.**

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. **The basic actions are defined in section 5.2.7 and section 5.2.8.**

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. **An ability’s text can include other abilities that it could grant to cards or counters or introduce directly to the game state. See also s ection 9.9.**
         1. **Each ability is categorized as either a static ability, a paid ability, a conditional ability, or a play ability. These types of abilities are discussed in sections 9.4, 9.5, 9.6, and 9.7, respectively.**
         1. **Abilities marked with \[interrupt\] or that include the words “prevent” or “avoid” in their instructions have special timing rules that differ from other abilities. See s ection 9.8.**
      1. **To RESOLVE AN ABILITY means to resolve each of that ability’s instructions in the order they appear. If an ability contains more than one instruction, a checkpoint occurs between each consecutive instruction. To RESOLVE AN INSTRUCTION means to carry out that instruction.**
         1. **While resolving an ability, other abilities can meet their conditions. When this happens, a “chain reaction” is created. The current instruction finishes resolving, then more recent abilities fully resolve before the next instruction of the original ability. If any other abilities meet their conditions while resolving the “chained” abilities, then another “chain” is created before continuing to resolve the previous chained abilities. Resolve each set of chained abilities one at a time, from the most recently met condition to the oldest, before continuing with the original ability that started the chain reaction.**

&nbsp;

***Example: The Runner’s identity is Armand “Geist” Walker. They access a Snare\! from R\&D with only 2 cards in their grip. Before taking a tag or suffering any net damage, the Runner triggers Decoy’s ability in order to avoid the tag. Using the Decoy meets the trigger condition of Geist’s ability. As this is the most recent ability to meet its trigger condition, Geist’s ability must resolve first, before Decoy avoids the tag and before Snare\! finishes resolving. The Runner draws a card from Geist, avoids the tag from Snare\! with Decoy, and then finally suffers (and survives) the 3 net damage from Snare\!.***

1. &nbsp;
   1. &nbsp;
      1. **The SOURCE of an ability is the card, counter, or game rule that originated it.**

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. **Each card is the source of its own printed abilities.**

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. **The source of abilities granted to a card or counter by another effect is the card or counter they were granted to, not the source of the effect that granted the ability.**

***Example: Dedicated Processor is hosted on Corroder, granting it the ability “2\[c\]:***

***\+4 strength.” The source of this ability is Corroder, not Dedicated Processor.***

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. **The source of a lingering ability is the card that created it. See section 9.8.**

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. **Each paid and conditional ability becomes independent of its source at a certain point before it resolves, as described in rule 9.5.4 and r ule 9.6.13. If the source card or counter changes zones after that point, the ability cannot act on the source, but it can refer to properties of its source. The ability uses the properties of the source as they last existed before the zone change.**

***Example: The Runner has Gorman Drip v1 installed, with 4 hosted virus counters. They use its paid ability, which has a cost that includes trashing Gorman Drip v1. Since the virus counters’ host was uninstalled, they are returned to the bank during the checkpoint immediately after the cost is paid. When the ability resolves, the counters are no longer present, but the ability can still tell that there were 4 hosted counters in Gorman Drip v1’s last installed state, so the Runner gains 4 credits.***

***Example: The Corporation trashes Allele Repression with 3 advancement counters on it. The Corporation is able to swap 3 cards out of Archives for 3 cards in HQ, even though the advancement counters were returned to the bank when Allele Repression was trashed. Additionally, Allele Repression itself is now a card in Archives, and could be swapped back to HQ.***

1. &nbsp;
   1. &nbsp;
      1. **Whereas an ability, instruction, or declaration is made up of text, an EFFECT is what happens in the game because of that text.**
         1. **Any of a non-static ability’s effects that apply beyond the duration of that ability’s resolution become independent of that ability and its source. The game engine takes responsibility for managing these LINGERING EFFECTS directly, and deletes them from the game state as their durations expire. See s**&nbsp; **ection 9.9.**

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. **When determining whether a certain ability has the potential to change the game state, look only at the expected effects of the ability. Do not consider its costs or restrictions, and do not consider other abilities that could become pending or relevant because of triggering or resolving the ability. See rule**

**&#49; .2.5 of the Golden Rules.**

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. **Any time a player chooses to resolve an optional ability or an optional part of an ability, the player is considered to be USING that ability and the source card of that ability. Players do not “use” abilities that are entirely mandatory.**
         1. **A paid ability is considered used once the trigger cost has been paid. See s ection 9.5.8 for the steps of using a paid ability.**
         1. **A conditional ability is considered used once the relevant optional effects of the ability have been resolved by the controller of the ability. See section**

**&#57; .6.15 for the steps of triggering and resolving conditional abilities.**

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. **If an ability allows a player to spend or move counters to pay a cost, that ability’s source card is considered used once the cost has been paid.**
         1. **A player can only use an ability if its effect has the potential to change the game state. See r ule 1.2.5.**
      1. **Abilities are ACTIVE if they are eligible to be resolved or apply to the current game state, and INACTIVE otherwise. By default, a card’s abilities are active if and only if that card is active (see section 1.8.3). Abilities of counters are active for as long as the counter exists.**
      1. **Some types of abilities are active even while their source card is inactive.**

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. **Conditional abilities that meet their conditions when their source card is accessed are active even while that card is inactive.**
         1. **Abilities stating that they are active in a particular zone are active in that zone. Abilities that can only ever meet their conditions in a particular zone are active in that zone. Abilities that can only affect the game state from a particular zone are active in that zone. When determining whether these stipulations apply, refer only to the game rules, not to any other effects that may be changing how cards move between zones.**

***Example: I’ve Had Worse has an ability that meets its trigger condition when it is trashed due to damage. Normally, this can only occur by moving I’ve Had Worse from the grip to the heap. Therefore, this ability is active in the heap. However, if I’ve Had Worse is trashed, but the Corp uses Skorpios Defense Systems to remove it from the game instead of adding it to the heap, the ability is not active.***

***Example: The last ability on Subliminal Messaging states in part, “you may add Subliminal Messaging to HQ from Archives.” This ability can only ever do anything if Subliminal Messaging is in Archives, so the ability is active there.***

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. **Abilities that modify when or if their source card can be played, installed, or rezzed are active even while that card is inactive.**
         1. **Abilities that modify the cost to install, rez, or play their source card are active even while that card is inactive.**
         1. **Abilities that modify the advancement requirement of their source card or create an additional cost to steal their source card are active even while that card is inactive.**
         1. **Abilities allowing a card to be advanced are active even while that card is unrezzed.**
   1. **Timing and Priority**
      1. **The ACTIVE PLAYER is the player whose turn it is. The other player is the INACTIVE PLAYER.**

***
_Created with the Personal Edition of HelpNDoc: [Easy EBook and documentation generator](<https://www.helpndoc.com>)_
