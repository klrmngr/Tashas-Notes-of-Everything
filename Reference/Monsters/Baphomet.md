---
type: pc
race: "Fiend (demon)"
class:
 - "Baphomet"
subClass:
 - "CR 23"
cover: "Baphomet.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/23
  - source/mpmm
---
###### Baphomet
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Baphomet.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 319 (22d12 + 176) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 14 | 26 | 18 | 24 | 16 |
| **Mod** | +10 | +2 | +8 | +4 | +7 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 24
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +9, Con +15, Wis +14
**Skills:** Intimidation +17, Perception +14
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison; bludgeoning, piercing, slashing that is nonmagical
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Labyrinthine Recall.** Baphomet can perfectly recall any path he has traveled, and he is immune to the maze spell.

**Legendary Resistance (3/Day).** If Baphomet fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Baphomet has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Baphomet makes one Bite attack, one Gore attack, and one Heartcleaver attack. He also uses Frightful Presence.

**Bite.** Melee Weapon Attack: +17 to hit, reach 10 ft., one target. *Hit:* 19 (2d8 + 10) piercing damage.

**Gore.** Melee Weapon Attack: +17 to hit, reach 10 ft., one target. *Hit:* 17 (2d6 + 10) piercing damage. If Baphomet moved at least 10 feet straight toward the target immediately before the hit, the target takes an extra 16 (3d10) piercing damage. If the target is a creature, it must succeed on a DC 25 Strength saving throw or be pushed up to 10 feet away and knocked prone.

**Heartcleaver.** Melee Weapon Attack: +17 to hit, reach 15 ft., one target. *Hit:* 21 (2d10 + 10) force damage.

**Frightful Presence.** Each creature of Baphomet's choice within 120 feet of him and aware of him must succeed on a DC 18 Wisdom saving throw or become frightened for 1 minute. A frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. These later saves have disadvantage if Baphomet is within line of sight of the creature.
If a creature succeeds on any of these saves or the effect ends on it, the creature is immune to Baphomet's Frightful Presence for the next 24 hours.


---

### Legendary Actions

### 

**Heartcleaver Attack.** Baphomet makes one Heartcleaver attack.

**Charge (Costs 2 Actions).** Baphomet moves up to his speed without provoking opportunity attacks, then makes a Gore attack.


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