---
type: pc
race: "Giant"
class:
 - "Fomorian Warlock of the Dark"
subClass:
 - "CR 12"
cover: "Fomorian Warlock of the Dark.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/12
  - source/bgg
---
###### Fomorian Warlock of the Dark
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Fomorian Warlock of the Dark.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 207 (18d12 + 90) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 13 | 20 | 9 | 14 | 18 |
| **Mod** | +6 | +1 | +5 | -1 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Giant, Undercommon
**Saving Throws:** Wis +6, Cha +8
**Skills:** Arcana +3, Perception +6, Stealth +5

---

### Traits

**Blood Rune.** The fomorian has a blood rune inscribed on an effigy or some other object in its possession. While holding or wearing the object bearing the rune, the giant can use its Corrupting Hex action and Poisoning Rebuke reaction.
The object bearing the blood rune has AC 15; 30 hit points; and immunity to necrotic, poison, and psychic damage. The object regains all its hit points at the end of every turn, but it turns to dust if reduced to 0 hit points or when the fomorian dies. If the rune is destroyed, the fomorian can inscribe a blood rune on an object in its possession when it finishes a short or long rest.

**Devil's Sight.** Magical darkness doesn't impede the fomorian's darkvision.

**Legendary Resistance (3/Day).** If the fomorian fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The fomorian makes three Greatclub attacks. If the fomorian has its blood rune, it can replace one of these attacks with a use of Corrupting Hex.

**Greatclub.** Melee Weapon Attack: +10 to hit, reach 15 ft., one target. *Hit:* 19 (3d8 + 6) bludgeoning damage plus 7 (2d6) necrotic damage.

**Corrupting Hex (Requires Blood Rune).** The fomorian targets one creature it can see within 60 feet of itself. The target must succeed on a DC 16 Charisma saving throw or take 27 (6d8) necrotic damage and become cursed for 24 hours. While cursed this way, the target's speed is reduced by half, and if it tries to cast a spell, it must first succeed on a DC 16 Intelligence check or the spell fails and is wasted.

**Eldritch Burst.** Magical energy explodes in a 20-foot-radius sphere centered on a point the fomorian can see within 120 feet of itself. Each creature in that area must make a DC 16 Dexterity saving throw. On a failed save, a creature takes 32 (5d12) force damage and has the prone condition. On a successful save, a creature takes half as much damage only.


---

### Bonus Actions

**Creeping Gloom (Recharge 6).** The fomorian momentarily conjures grasping darkness in a 30-foot-radius sphere centered on a point it can see within 120 feet of itself. Each creature in that area must succeed on a DC 16 Constitution saving throw or take 11 (2d10) necrotic damage and have the blinded condition until the end of its next turn.


---

### Reactions

**Poisoning Rebuke (Requires Blood Rune).** In response to being damaged by a creature the fomorian can see within 60 feet of itself, the fomorian forces that creature to make a DC 16 Constitution saving throw; on a failed save, the creature has the poisoned condition until the end of its next turn.


---

> [!column|flex 3]
>> [!important]- QUESTS:
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Name
>>     filters:
>>       and:
>>         - file.inFolder("Compendium/Party/Quests")
>>         - file.hasLink(this.file)
>>     order:
>>       - file.name
>> ```
>
>> [!note]- HISTORY
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Session Notes
>>     filters:
>>       and:
>>         - file.inFolder("Session Notes")
>>         - file.hasLink(this.file)
>> ```