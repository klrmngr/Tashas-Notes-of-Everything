---
type: pc
race: "Dragon (metallic)"
class:
 - "Ancient Gold Dragon"
subClass:
 - "CR 24"
cover: "Ancient Gold Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/24
  - source/xmm
---
###### Ancient Gold Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ancient Gold Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon (metallic) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 22 |
> | :FasHeart: HP | 546 (28d20 + 252) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 14 | 29 | 18 | 17 | 28 |
| **Mod** | +10 | +2 | +9 | +4 | +3 | +9 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 27
**Languages:** Common, Draconic
**Saving Throws:** Dex +9, Wis +10
**Skills:** Insight +10, Perception +17, Persuasion +16, Stealth +9
**Damage Immunities:** fire

---

### Traits

**Amphibious.** The dragon can breathe air and water.

**Legendary Resistance (4/Day, or 5/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Spellcasting to cast Guiding Bolt (level 4 version) or (B) Weakening Breath.

**Rend.** m +17 to hit, reach 15 ft. *Hit:* 19 (2d8 + 10) Slashing damage plus 9 (2d8) Fire damage.

**Fire Breath (Recharge 5–6).** dex DC 24, each creature in a 90-foot Cone.  71 (13d10) Fire damage.  Half damage.

**Weakening Breath.** str DC 24, each creature that isn't currently affected by this breath in a 90-foot Cone.  The target has Disadvantage on Strength-based D20 Tests and subtracts 5 (1d10) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


---

### Legendary Actions

### 

**Banish.** cha DC 24, one creature the dragon can see within 120 feet.  24 (7d6) Force damage, and the target has the Incapacitated condition and is transported to a harmless demiplane until the start of the dragon's next turn, at which point it reappears in an unoccupied space of the dragon's choice within 120 feet of the dragon.  The dragon can't take this action again until the start of its next turn.

**Guiding Light.** The dragon uses Spellcasting to cast Guiding Bolt (level 4 version).

**Pounce.** The dragon moves up to half its Speed, and it makes one Rend attack.


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