# Craghaven Mods
This is a collection of macros and mods created for the Craghaven campaign of The Stormlight Archive RPG. Cosmere RPG: The Stormlight Archive was developed by Brotherwise Games and its Foundry modules by The Metalworks. This mod requires the Stormlight Handbook (a paid module) as a dependency.

## Macros
This module includes three macros. You can simply use them from the compendium, macro directory, or the hotbar.

**Group Long Rest** provides the benefits of a long rest to all actors, including decrementing a stack of Exhausted. This macro has three versions:
* The basic **Group Long Rest** leaves Investiture as-is. (This is to remain as close to RAW as possible.)
* **Group Long Rest (fill Investiture)** additionally fills all Investiture resources to maximum. (This is if you want your group long rest to simply make everyone *combat ready*.)
* **Group Long Rest (zero Investiture)** sets all Investiture resources to zero. (This is to follow canon, where Stormlight fades from human Radiants over time.)

**Nonlethal Defeat** marks a selected token as "Defeated" with the *Unconscious* condition instead of Dead. Useful for nonlethal parties!

<img width="673" height="324" alt="image" src="https://github.com/user-attachments/assets/b287b0dc-e142-4966-bb6d-338bfbf05fcd" />

**Improve Enhance** finds the selected actor's "Enhance" action and improves it as if they had completed the Second Ideal: It becomes a free action which does not itself cost investiture.

<img width="545" height="122" alt="image" src="https://github.com/user-attachments/assets/76f0a18e-6213-4116-838a-3f7411d05e09" />

## Mods
This module contains two modified Actions, two modified Armours, and a full folder of 2nd Ideal Goals.

The **2nd Ideal Goals** add an event which triggers on the goal's completion and updates the Enhance action to suit (using the Improve Enhance macro).

### Actions
Using **Breathe Stormlight** causes your Investiture to refill to max.

Using **Enhance** actually causes your Enhanced Strength and Speed to toggle.

### Armour
Both versions of **Shardplate** have added event triggers. If you equip the armour while it has at least one charge, it turns on the Enhanced Strength and Speed; if you unequip it or use the last charge, it turns them off.

### How To Use The Mods?
There are two basic methods.

*Swap items manually.* Remove the originals from actors' sheets and replace them with the modified versions. If someone already has a 2nd Ideal goal, delete it and drag the modified version from the Craghaven Items compendium. This preserves the Handbook as-is, but can be time-consuming, and you would need to continue swapping any time someone gains one of the modified items.

*Edit the Handbook.* __This is an advanced option.__ In the Stormlight Handbook compendium, you can right-click on one of the impacted collections (`Stormlight Handbook>Items`, `Stormlight Handbook>Character Features>Radiant Paths`, `Stormlight Handbook>Rules>Actions`) and **Toggle Edit Lock**. You can then open and edit the item directly in the compendium, copying the changes over from the Craghaven compendium (such as copying the events for Shardplate).

The drawbacks of this method: It's much more complex; it edits your Handbook directly (so that even Stormlight worlds *without* the Craghaven module will be affected); and the changes will be undone when the Handbook receives an update.

The benefits: Once you edit an item once, future copies of it will benefit automatically. You could edit Radiant Shardplate once, then as soon as someone completes the Fourth Ideal, their new Shardplate has the events built in.
