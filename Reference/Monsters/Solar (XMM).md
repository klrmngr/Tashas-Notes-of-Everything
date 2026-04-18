---
type: pc
race: "Celestial (angel)"
class:
 - "Solar"
subClass:
 - "CR 21"
cover: "Solar.png"
campaign:
locations:
tags:
  - race/angel
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/21
  - source/xmm
---
###### Solar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Solar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Large Celestial (angel) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 21 |
> | :FasHeart: HP | 297 (22d10 + 176) |
> | :FasUserGroup: Race | Celestial (angel) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 22 | 26 | 25 | 25 | 30 |
| **Mod** | +8 | +6 | +8 | +7 | +7 | +10 |

**Speed:** 50 ft., fly 150 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 24
**Languages:** all; telepathy 120 ft.
**Skills:** Perception +14
**Damage Immunities:** poison; radiant
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Divine Awareness.** The solar knows if it hears a lie.

**Exalted Restoration.** If the solar dies outside Mount Celestia, its body disappears, and it gains a new body instantly, reviving with all its Hit Points somewhere in Mount Celestia.

**Legendary Resistance (4/Day).** If the solar fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The solar has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The solar makes two Flying Sword attacks. It can replace one attack with a use of Slaying Bow.

**Flying Sword.** m,r +15, reach 10 ft. or range 120 ft. *Hit:* 22 (4d6 + 8) Slashing damage plus 36 (8d8) Radiant damage. The sword magically returns to the solar's hand or hovers within 5 feet of the solar immediately after a ranged attack.

**Slaying Bow.** dex DC 21, one creature the solar can see within 600 feet.  If the creature has 100 Hit Points or fewer, it dies. It otherwise takes 24 (4d8 + 6) Piercing damage plus 36 (8d8) Radiant damage.


---

### Legendary Actions

### 

**Blinding Gaze.** con DC 25, one creature the solar can see within 120 feet.  The target has the Blinded condition for 1 minute.  The solar can't take this action again until the start of its next turn.

**Radiant Teleport.** The solar teleports up to 60 feet to an unoccupied space it can see. dex DC 25, each creature in a 10-foot Emanation originating from the solar at its destination space.  11 (2d10) Radiant damage.  Half damage.


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