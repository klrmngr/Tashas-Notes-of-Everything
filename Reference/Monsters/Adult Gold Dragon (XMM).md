---
type: pc
race: "Dragon (metallic)"
class:
 - "Adult Gold Dragon"
subClass:
 - "CR 17"
cover: "Adult Gold Dragon.png"
campaign:
locations:
tags:
  - race/metallic
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/17
  - source/xmm
---
###### Adult Gold Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Adult Gold Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Huge Dragon (metallic) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 243 (18d12 + 126) |
> | :FasUserGroup: Race | Dragon (metallic) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 14 | 25 | 16 | 15 | 24 |
| **Mod** | +8 | +2 | +7 | +3 | +2 | +7 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 120 ft., passive Perception 24
**Languages:** Common, Draconic
**Saving Throws:** Dex +8, Wis +8
**Skills:** Insight +8, Perception +14, Persuasion +13, Stealth +8
**Damage Immunities:** fire

---

### Traits

**Amphibious.** The dragon can breathe air and water.

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon makes three Rend attacks. It can replace one attack with a use of (A) Spellcasting to cast Guiding Bolt (level 2 version) or (B) Weakening Breath.

**Rend.** m +14, reach 10 ft. *Hit:* 17 (2d8 + 8) Slashing damage plus 4 (1d8) Fire damage.

**Fire Breath (Recharge 5–6).** dex DC 21, each creature in a 60-foot Cone.  66 (12d10) Fire damage.  Half damage.

**Weakening Breath.** str DC 21, each creature that isn't currently affected by this breath in a 60-foot Cone.  The target has Disadvantage on Strength-based D20 Tests and subtracts 3 (1d6) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.


---

### Legendary Actions

### 

**Banish.** cha DC 21, one creature the dragon can see within 120 feet.  10 (3d6) Force damage, and the target has the Incapacitated condition and is transported to a harmless demiplane until the start of the dragon's next turn, at which point it reappears in an unoccupied space of the dragon's choice within 120 feet of the dragon.  The dragon can't take this action again until the start of its next turn.

**Guiding Light.** The dragon uses Spellcasting to cast Guiding Bolt (level 2 version).

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