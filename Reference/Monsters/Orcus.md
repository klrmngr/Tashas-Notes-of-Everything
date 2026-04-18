---
type: pc
race: "Fiend (demon)"
class:
 - "Orcus"
subClass:
 - "CR 26"
cover: "Orcus.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/26
  - source/mpmm
---
###### Orcus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Orcus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 26 (90,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor); 20 (with the Wand of Orcus) |
> | :FasHeart: HP | 405 (30d12 + 210) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 14 | 25 | 20 | 20 | 25 |
| **Mod** | +8 | +2 | +7 | +5 | +5 | +7 |

**Speed:** 40 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 22
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +10, Con +15, Wis +13
**Skills:** Arcana +13, Perception +13
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** necrotic; poison; bludgeoning, piercing, slashing that is nonmagical
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Orcus fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Orcus has advantage on saving throws against spells and other magical effects.

**Master of Undeath.** Orcus can cast animate dead (at will) and create undead (3/day). He chooses the level at which the spells are cast, and the creatures created by them remain under his control indefinitely. Additionally, he can cast create undead even when it isn't night.

**Special Equipment.** Orcus wields the Wand of Orcus.


---

### Actions

**Multiattack.** Orcus makes three Wand of Orcus, Tail, or Necrotic Bolt attacks.

**Wand of Orcus.** Melee Weapon Attack: +19 to hit, reach 10 ft., one target. *Hit:* 24 (3d8 + 11) bludgeoning damage plus 13 (2d12) necrotic damage.

**Tail.** Melee Weapon Attack: +16 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) force damage plus 9 (2d8) poison damage.

**Necrotic Bolt.** Ranged Spell Attack: +15 to hit, range 120 ft., one target. *Hit:* 29 (5d8 + 7) necrotic damage.

**Conjure Undead (1/Day).** While holding the Wand of Orcus, Orcus conjures type=undead whose combined average hit points don't exceed 500. These creatures magically rise up from the ground or otherwise form in unoccupied spaces within 300 feet of Orcus and obey his commands until they are destroyed or until he dismisses them as an action.


---

### Legendary Actions

Orcus can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature's turn. Orcus regains spent legendary actions at the start of his turn.

### 

**Attack.** Orcus makes one Tail or Necrotic Bolt attack.

**Creeping Death (Costs 2 Actions).** Orcus chooses a point on the ground that he can see within 100 feet of him. A cylinder of swirling necrotic energy 60 feet tall and with a 10-foot radius rises from that point and lasts until the end of Orcus's next turn. Creatures in that area have vulnerability to necrotic damage.


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