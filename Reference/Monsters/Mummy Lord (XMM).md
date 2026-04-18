---
type: pc
race: "Undead (cleric)"
class:
 - "Mummy Lord"
subClass:
 - "CR 15"
cover: "Mummy Lord.png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/undead
  - size/small
  - cr/15
  - source/xmm
---
###### Mummy Lord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Mummy Lord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Small Undead (cleric) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 187 (25d8 + 75) |
> | :FasUserGroup: Race | Undead (cleric) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 17 | 11 | 19 | 16 |
| **Mod** | +4 | +0 | +3 | +0 | +4 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Truesight 60 ft., passive Perception 19
**Languages:** Common plus three other languages
**Saving Throws:** Int +5, Wis +9
**Skills:** History +5, Perception +9, Religion +5
**Damage Vulnerabilities:** fire
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the mummy fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The mummy has Advantage on saving throws against spells and other magical effects.

**Undead Restoration.** If destroyed, the mummy gains a new body in 24 hours if its heart is intact, reviving with all its Hit Points. The new body appears in an unoccupied space within the mummy's lair. The heart is a Tiny object that has AC 17, HP 10, and Immunity to all damage except Fire.


---

### Actions

**Multiattack.** The mummy makes one Rotting Fist or Channel Negative Energy attack, and it uses Dreadful Glare.

**Rotting Fist.** m +9, reach 5 ft. *Hit:* 15 (2d10 + 4) Bludgeoning damage plus 10 (3d6) Necrotic damage. If the target is a creature, it is cursed. While cursed, the target can't regain Hit Points, it gains no benefit from finishing a Long Rest, and its Hit Point maximum decreases by 10 (3d6) every 24 hours that elapse. A creature dies and turns to dust if reduced to 0 Hit Points by this attack.

**Channel Negative Energy.** r +9, range 60 ft. *Hit:* 25 (6d6 + 4) Necrotic damage.

**Dreadful Glare.** wis DC 17, one creature the mummy can see within 60 feet.  25 (6d6 + 4) Psychic damage, and the target has the Paralyzed condition until the end of the mummy's next turn.


---

### Reactions

**Whirlwind of Sand.**  The mummy is hit by an attack roll.  The mummy adds 2 to its AC against the attack, possibly causing the attack to miss, and the mummy teleports up to 60 feet to an unoccupied space it can see. Each creature of its choice that it can see within 5 feet of its destination space has the Blinded condition until the end of the mummy's next turn.


---

### Legendary Actions

### 

**Glare.** The mummy uses Dreadful Glare. The mummy can't take this action again until the start of its next turn.

**Necrotic Strike.** The mummy makes one Rotting Fist or Channel Negative Energy attack.


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