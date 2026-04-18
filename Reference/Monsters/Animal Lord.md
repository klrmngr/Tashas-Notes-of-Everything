---
type: pc
race: "Celestial"
class:
 - "Animal Lord"
subClass:
 - "CR 20"
cover: "Animal Lord.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/20
  - source/xmm
---
###### Animal Lord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Animal Lord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 323 (34d8 + 170) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 25 | 20 | 19 | 23 | 22 |
| **Mod** | +7 | +7 | +5 | +4 | +6 | +6 |

**Speed:** 60 ft., fly 60 ft. ((hover)), swim 60 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 28
**Languages:** all
**Saving Throws:** Con +11, Wis +12
**Skills:** Acrobatics +13, Athletics +13, Perception +18, Stealth +13
**Damage Resistances:** cold; fire; necrotic; psychic; radiant
**Condition Immunities:** charmed; frightened; stunned

---

### Traits

**Animal Lordship.** An animal lord represents a Forager, Hunter, or Sage (DM's choice), which determines certain traits in this stat block.

**Legendary Resistance (4/Day).** If the animal lord fails a saving throw, it can choose to succeed instead.

**Lordly Presence.** wis DC 20, any enemy that starts its turn in a 30-foot Emanation originating from the animal lord.  The target suffers one of the following effects:
- **Captivated (Forager Only).** The target has the Charmed condition until the end of its next turn. While Charmed, the target has the Incapacitated condition.
- **Fearful (Hunter Only).** The target has the Frightened condition until the end of its next turn.
- **Mired (Sage Only).** The target takes 10 (3d6) Psychic damage, and the target is magically bewildered until the end of its next turn. While bewildered, the target subtracts 1d4 from its saving throws.

**Magic Resistance.** The animal lord has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The animal lord makes two attacks, using Rend or Radiant Ray in any combination, and uses Animal Spirit.

**Rend.** m +13, reach 5 ft. *Hit:* 14 (2d6 + 7) Slashing damage plus 7 (2d6) Force damage.

**Radiant Ray.** r +12, range 120 ft. *Hit:* 20 (4d6 + 6) Radiant damage.

**Animal Spirit.** The animal lord conjures an animal spirit that strikes at a creature and then disappears. dex DC 20, one creature the animal lord can see within 120 feet.  28 (4d10 + 6) Radiant damage.  Half damage.  One of the following effects occurs:
- **Fortify (Forager Only).** The animal lord gains 20 Temporary Hit Points.
- **Marked as Prey (Hunter Only).** The animal lord has Advantage on attack rolls against the target until the start of the animal lord's next turn.
- **Pesky Swarm (Sage Only).** The target has Disadvantage on attack rolls and ability checks until the end of its next turn.


---

### Bonus Actions

**Shape-Shift.** The animal lord shape-shifts into a Huge or smaller version of the animal it represents or a Medium or Small Humanoid, or it returns to its true form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.


---

### Legendary Actions

### 

**Feral Strike.** The animal lord moves up to its Speed without provoking Opportunity Attacks, and it makes one Rend attack.

**Radiant Strike.** The animal lord makes one Radiant Ray attack.


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