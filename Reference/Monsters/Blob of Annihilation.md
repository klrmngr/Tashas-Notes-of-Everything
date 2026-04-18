---
type: pc
race: "Ooze (titan)"
class:
 - "Blob of Annihilation"
subClass:
 - "CR 23"
cover: "Blob of Annihilation.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/ooze
  - size/gargantuan
  - cr/23
  - source/xmm
---
###### Blob of Annihilation
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Blob of Annihilation.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Gargantuan Ooze (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 448 (23d20 + 207) |
> | :FasUserGroup: Race | Ooze (titan) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 14 | 28 | 10 | 16 | 10 |
| **Mod** | +8 | +2 | +9 | +0 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 120 ft., passive Perception 13
**Languages:** —
**Saving Throws:** Dex +9, Con +16
**Damage Resistances:** bludgeoning; piercing; slashing
**Damage Immunities:** acid; necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained; stunned; unconscious

---

### Traits

**Astral Implosion.** If the blob is reduced to 0 Hit Points, it implodes and ejects any creatures and objects engulfed by it into the Astral Sea. The blob itself vanishes, leaving behind a layer of slime on everything that was within 600 feet of it. In 1d20 years, the blob reconstitutes on a random world in the Material Plane.

**Legendary Resistance (4/Day).** If the blob fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The blob has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The blob makes two Pseudopod attacks and uses Engulf. It can replace one attack with a use of Restraining Glob.

**Pseudopod.** m +15, reach 30 ft. *Hit:* 24 (3d10 + 8) Force damage.

**Engulf.** The blob moves up to its Speed and can move through the spaces of Huge or smaller creatures and objects. str DC 23, each creature or object whose space the blob enters for the first time during this move.  The target is engulfed. While engulfed, a target has Total Cover against attacks and other effects outside the blob, and when the blob moves, the engulfed target moves with it. A nonmagical object is destroyed after spending 1 minute engulfed.
While engulfed, a creature takes 21 (6d6) Force damage at the start of each of its turns, is suffocating, has the Restrained condition, and repeats the save at the end of each of its turns. An engulfed creature that is reduced to 0 Hit Points dissolves into ash, which is ejected into the Astral Sea.  The target escapes and enters the nearest unoccupied space.

**Restraining Glob.** The blob lobs a slimy glob at one Large or smaller creature it can see within 600 feet of itself. dex DC 23, the targeted creature.  18 (3d6 + 8) Acid damage. The glob rolls the target 60 feet straight toward the blob, and the target has the Restrained condition until the end of its next turn, when the glob harmlessly dissolves.  Half damage only.


---

### Legendary Actions

### 

**Decay.** The blob deals 14 (4d6) Necrotic damage to each creature engulfed by it. The blob can't take this action again until the start of its next turn.

**Grasping Glob.** The blob uses Restraining Glob. The blob can't take this action again until the start of its next turn.

**Lashing Goop.** The blob makes one Pseudopod attack.


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