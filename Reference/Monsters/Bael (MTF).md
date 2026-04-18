---
type: pc
race: "Fiend (devil)"
class:
 - "Bael"
subClass:
 - "CR 19"
cover: "Bael.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/19
  - source/mtf
---
###### Bael
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Bael.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 189 (18d10 + 90) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 17 | 20 | 21 | 24 | 24 |
| **Mod** | +7 | +3 | +5 | +5 | +7 | +7 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 23
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +9, Con +11, Int +11, Cha +13
**Skills:** Intimidation +13, Perception +13, Persuasion +13
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Dreadful.** Bael can use a bonus action to appear dreadful until the start of his next turn. Each creature, other than a devil, that starts its turn within 10 feet of Bael must succeed on a DC 22 Wisdom saving throw or be frightened until the start of the creature's next turn.

**Legendary Resistance (3/Day).** If Bael fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Bael has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** Bael's weapon attacks are magical.

**Regeneration.** Bael regains 20 hit points at the start of his turn. If he takes cold or radiant damage, this trait doesn't function at the start of his next turn. Bael dies only if he starts his turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** Bael makes two melee attacks.

**Hellish Morningstar.** Melee Weapon Attack: +13 to hit, reach 20 ft., one target. *Hit:* 16 (2d8 + 7) piercing damage plus 13 (3d8) necrotic damage.

**Infernal Command.** Each ally of Bael's within 60 feet of him can't be charmed or frightened until the end of his next turn.

**Teleport.** Bael magically teleports, along with any equipment he is wearing and carrying, up to 120 feet to an unoccupied space he can see.


---

### Legendary Actions

### 

**Attack (Cost 2 Actions).** Bael attacks once with his hellish morningstar.

**Awaken Greed.** Bael casts charm person or major image.

**Infernal Command.** Bael uses his Infernal Command action.

**Teleport.** Bael uses his Teleport action.


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