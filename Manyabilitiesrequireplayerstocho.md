# Many abilities require players to choose 1 or more cards or counters to affect. Each card or counter chosen for an ability is a TARGET of that ability.

***Example: Top Hat reads in part, “you may choose 1 of the top 5 cards of R\&D and access it.” The target of this instruction is the card in R\&D the Runner chooses.***

***Example: One of the subroutines on Colossus reads in part, “Trash 1 installed program and 1 installed resource.” The targets of this subroutine are the two cards that will be trashed.***

***Example: Trick of Light reads, “Move up to 2 advancement tokens from a card to another installed card that can be advanced.” The targets of this operation are the advancement tokens to be moved and the destination card. If 2 tokens are chosen, they must be hosted on the same card.***

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. **Cards found during a search are not considered targets of the instruction that performs the search. Players do not need to announce what card(s) they expect to find before the search actually takes place. See section 4.2 for rules about searching.**
         1. **Only cards and counters are announced as targets. If an instruction directs a player to choose (or "name") a number, a card type, a subtype, a card name, a server, or one of a specified set of effects, this is not announcing a target. Those choices are not made until the instruction resolves.**
      1. **Immediately before an instruction becomes imminent, the player resolving that instruction must first choose the targets required by that instruction. For each time the instruction requires a player to choose cards or counters, that player ANNOUNCES appropriate targets. Once players are finished announcing targets for an instruction, the instruction becomes imminent, and players have the opportunity to modify the effects of that instruction with interrupt abilities before it resolves. See section 9.8.**
         1. **When a player announces a card as a target, they indicate clearly which card is being chosen without changing its facedown/faceup status or location.**
         1. **The player resolving the instruction can only choose cards and counters that are valid targets for that instruction. A target is valid for an instruction if it meets any specified requirements of that instruction or can otherwise be acted upon by that instruction.**
         1. **Unless an instruction explicitly specifies the zone from which a target is selected, only cards and counters in the play area are valid targets for that instruction.**

***Example: The Corp resolves a subroutine that says “\[sub\] The Runner trashes 1 program.” The Runner must trash one of their installed programs and may not trash a program from their grip or stack.***

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. **Some effects allow a player to choose multiple cards as targets for a single announcement. Section 9.11.2 contains rules about resolving effects involving sets of cards.**
         1. **A player may announce the targets for an instruction in any order, but a card or counter can only be chosen as a target once for each announcement. If there are not enough valid targets available, then that player chooses as many distinct targets as possible and the remaining targets are not announced.**

***Example: The Runner accesses an Aggressive Secretary with three advancement tokens on it. The Runner only has two installed programs, so the Corp chooses both of those programs for Aggressive Secretary. After the programs have been chosen, they are both trashed simultaneously.***

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. **Targets cannot be chosen for an instruction at any other time. Even if the game state changes due to interrupt abilities while the instruction is imminent, unannounced targets remain unchosen.**
      1. **At the time an instruction resolves, if any of its targets either have become invalid or were not announced, as much of that ability resolves as possible without acting on the unannounced or invalid targets, following rules 1 .2.3 and 1.2.4 of the Golden Rules. A target can be invalid because the chosen card or counter is no longer in the zone it was in when it was targeted, or because the target no longer meets other requirements specified by the targeting ability.**
      1. **After the instruction that targeted a card or counter has resolved, subsequent instructions of the same ability can continue to act on that target without needing to select it again, even if the ability moves the target or change its properties.**
         1. **If an ability has instructions remaining that will act on a target, but that target is uninstalled or is otherwise moved to a new zone by a different ability before the first ability’s remaining instructions resolve, then those instructions can no longer act on that target. This includes instructions within delayed conditional abilities created by the original ability (see rule 9.6.14).**

***Example: Howler’s ability targets a card in HQ. Its first instruction installs that card, and its second instruction creates a delayed conditional ability that refers to that card in the play area. The latter ability can find and act on the card as long as it is still installed. If another effect uninstalls that card before the delayed conditional ability attempts to act on it, the ability will no longer be able to locate it (see rule 8.2.10).***

1. &nbsp;
   1. Costs
      1. In order to initiate an action or ability or use an optional ability, a player may be required to pay a cost. A cost can take the form of any card, counter, or other item a player must spend; an effect a player must resolve; or other type of requirement a player must meet. If a player cannot pay the full cost of an action or ability all at once **with** cards and counters they control, they cannot use the effect associated with that cost.
         1. The act of paying a cost cannot be modified or cancelled by optional prevent/avoid abilities.

*Example: The Runner can trash Clone Chip to trigger its paid ability, but cannot use LLDS Energy Regulator to prevent Clone Chip from being trashed this way.*

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. If a **static** ability or a mandatory **conditional ability interrupt** would prevent the steps of paying a cost from being carried out if they were performed as an effect, that cost cannot be paid.

&nbsp;

*Example: The Runner cannot pay the additional cost to steal Obokata Protocol while Guru Davinder is installed, because the Runner could not currently take 4 damage if instructed to: Guru Davinder’s first ability would prevent the damage.*

1. &nbsp;
   1. &nbsp;
      1. &nbsp;
         1. If a cost is subject to effects modifying its value, determine its final value from its default value by first applying each effect that increases the cost, then applying each effect that lowers the cost. Finally, if the value determined by this process is less than 0, set the value to 0.
         1. A cost of 0 can still be paid by a player, even though no items are paid.

&nbsp;

*Example: If Freedom Khumalo: Crypto-Anarchist accesses a Beanstalk Royalties from R\&D, the Runner can use Freedom Khumalo’s ability to trash the Beanstalk Royalties. Even though the Runner does not remove any virus counters from any cards, they have still paid the cost.*

1. &nbsp;
   1. &nbsp;
      1. After a player pays a cost, a checkpoint occurs. See rule 10.3.

&nbsp;

1. &nbsp;
   1. &nbsp;
      1. Some cards have a printed play or install cost of X. The value of X is determined when the card is played or installed, after applying any modifiers which affect the play or install cost of that card.
         1. If the play or install cost of a card with a play or install cost of X needs to be referenced at any other time, X is considered to be 0.
      1. There are six main types of costs: install costs (found mainly on hardware, programs, and resources, and incurred when installing ice), play costs (found on operations and events), rez costs (found on assets, upgrades, and ice), paid ability trigger costs, additional costs, and nested costs.

***
_Created with the Personal Edition of HelpNDoc: [Create iPhone web-based documentation](<https://www.helpndoc.com/feature-tour/iphone-website-generation>)_
