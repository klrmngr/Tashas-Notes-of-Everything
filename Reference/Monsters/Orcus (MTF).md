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
  - source/mtf
---
###### Orcus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
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
> | :FasShield: AC | 17 (natural armor); 20 with the Wand of Orcus |
> | :FasHeart: HP | 405 (30d12 + 210) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

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

**Wand of Orcus.** The wand has 7 charges, and any of its properties that require a saving throw have a save DC of 18. While holding it, Orcus can use an action to cast animate dead, blight, or speak with dead. Alternatively, he can expend 1 or more of the wand's charges to cast one of the following spells from it: circle of death (1 charge), finger of death (1 charge), or power word kill (2 charges). The wand regains 1d4 + 3 charges daily at dawn.
While holding the wand, Orcus can use an action to conjure undead creatures whose combined average hit points don't exceed 500. These undead magically rise up from the ground or otherwise form in unoccupied spaces within 300 feet of Orcus and obey his commands until they are destroyed or until he dismisses them as an action. Once this property of the wand is used, the property can't be used again until the next dawn.

**Legendary Resistance (3/Day).** If Orcus fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Orcus has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** Orcus's weapon attacks are magical.

**Master of Undeath.** When Orcus casts animate dead or create undead, he chooses the level at which the spell is cast, and the creatures created by the spells remain under his control indefinitely. Additionally, he can cast create undead even when it isn't night.


---

### Actions

**Multiattack.** Orcus makes two Wand of Orcus attacks.

**Wand of Orcus.** Melee Weapon Attack: +19 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) bludgeoning damage plus 13 (2d12) necrotic damage.

**Tail.** Melee Weapon Attack: +16 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) piercing damage plus 9 (2d8) poison damage.


---

### Legendary Actions

### 

**Tail.** Orcus makes one tail attack.

**A Taste of Undeath.** Orcus casts chill touch (17th level).

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