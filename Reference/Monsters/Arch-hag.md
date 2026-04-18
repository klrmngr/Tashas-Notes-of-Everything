---
type: pc
race: "Fey"
class:
 - "Arch-hag"
subClass:
 - "CR 21"
cover: "Arch-hag.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/21
  - source/xmm
---
###### Arch-hag
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Arch-hag.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 333 (29d10 + 174) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 15 | 23 | 19 | 19 | 25 |
| **Mod** | +7 | +2 | +6 | +4 | +4 | +7 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Truesight 60 ft., passive Perception 21
**Languages:** all
**Saving Throws:** Dex +9, Wis +11
**Skills:** Deception +14, Perception +11, Persuasion +21
**Damage Resistances:** cold; fire; psychic
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the hag fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The hag has Advantage on saving throws against spells and other magical effects.

**Spiteful Escape.** When the hag drops to 0 Hit Points, it dies only if it is within 30 feet of its anathema (a thing the DM chooses as the hag's most hated thing). Otherwise, the hag drops to 1 Hit Point and teleports to a harmless demiplane, and it can't return to the plane it left for 2d6 days. When the hag teleports away, each creature within 60 feet of the space it left is cursed. Until the curse ends, a creature has Disadvantage on ability checks and saving throws, and the hag knows its location anywhere in the multiverse.


---

### Actions

**Multiattack.** The hag makes two Spectral Claw attacks and uses Crackling Wave.

**Spectral Claw.** m,r +14, reach 10 ft. or range 60 ft. *Hit:* 17 (3d6 + 7) Force damage. If the target is a Large or smaller creature, it has the Prone condition.

**Crackling Wave.** dex DC 22, each creature in a 60-foot Cone.  32 (5d12) Lightning damage.  Half damage.  The target is cursed until the end of the hag's next turn. The target can't take Reactions until the curse ends.


---

### Bonus Actions

**Witch Strike.** Each creature cursed by the hag and within 60 feet of it takes 14 (4d6) Lightning damage.


---

### Legendary Actions

### 

**Hag's Swipe.** The hag makes one Spectral Claw attack.

**Malicious Magic.** The hag uses Spellcasting to cast Dimension Door or Hypnotic Pattern. The hag can't take this action again until the start of its next turn.


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