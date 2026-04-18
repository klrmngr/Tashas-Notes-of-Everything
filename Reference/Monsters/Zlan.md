---
type: pc
race: "Undead (wizard)"
class:
 - "Zlan"
subClass:
 - "CR 18"
cover: "Zlan.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/18
  - source/fraif
---
###### Zlan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Zlan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Huge Undead (wizard) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 199 (19d12 + 76) |
> | :FasUserGroup: Race | Undead (wizard) |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 19 | 21 | 18 | 14 |
| **Mod** | +5 | +1 | +4 | +5 | +4 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 20
**Languages:** all
**Saving Throws:** Dex +7, Con +10, Int +11, Wis +10
**Skills:** Arcana +17, History +11, Perception +10
**Damage Resistances:** lightning; necrotic
**Damage Immunities:** cold; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Chardalyn Sense.** Zlan senses the emotions of anyone touching a piece of chardalyn within 100 miles of itself.

**Legendary Resistance (3/Day).** If Zlan fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** Zlan has Advantage on saving throws against spells and other magical effects.

**Next of the Seven (6/Year).** If Zlan dies within 100 miles of a piece of chardalyn at least 4 inches long, it re-forms from that piece of chardalyn in 1d10 days, regaining all its Hit Points. The new body appears in the unoccupied space nearest to the piece of chardalyn, and another lich's mind in the body seizes psychic control of the body.


---

### Actions

**Multiattack.** Zlan makes three attacks, using Slam or Bewildering Bolt in any combination. It can replace two attacks with a use of Spellcasting.

**Slam.** m +11, reach 10 ft. *Hit:* 12 (3d4 + 5) Bludgeoning damage plus 22 (4d10) Necrotic damage.

**Bewildering Bolt.** r +11, range 120 ft. *Hit:* 27 (4d10 + 5) Psychic damage, and the target has the Charmed condition until the end of its next turn.


---

### Legendary Actions

### 

**Retaliation.** Zlan makes one Slam or Bewildering Bolt attack.

**Stoke Paranoia.** wis DC 19, one creature Zlan can see within 30 feet (with Disadvantage if the target is holding or wearing chardalyn).  27 (6d8) Psychic damage and the target has the Charmed condition for 1 minute or until Zlan dies. While Charmed, the target doesn't act as an ally to any creature.  Half damage only.  Zlan can't take this action again until the start of its next turn.


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