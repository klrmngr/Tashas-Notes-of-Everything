---
type: pc
race: "Humanoid (dwarf, monk)"
class:
 - "Prisoner 13"
subClass:
 - "CR 5"
cover: "Prisoner 13.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/kftgv
---
###### Prisoner 13
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Keys from the Golden Vault
___

> [!infobox|no-t right]
> ![[Prisoner 13.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf, monk) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (mountain tattoo) |
> | :FasHeart: HP | 102 (12d8 + 48) |
> | :FasUserGroup: Race | Humanoid (dwarf, monk) |
> | :FasBook: Source | Keys from the Golden Vault |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 17 | 18 | 16 | 14 | 16 |
| **Mod** | +2 | +3 | +4 | +3 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common, Dwarvish, Elvish, Thieves' cant, Undercommon
**Saving Throws:** Con +7, Wis +5
**Skills:** Athletics +5, Deception +9, Insight +5, Perception +5, Stealth +6
**Damage Resistances:** poison
**Damage Immunities:** psychic
**Condition Immunities:** charmed

---

### Traits

**Antimagic Susceptibility.** In an area of antimagic, Prisoner 13's tattoos and reactions don't function, and she suffers the following modifications to her statistics: her AC becomes 13, she loses her immunity to psychic damage and the charmed condition, and her Tattooed Strike becomes a melee attack that deals 7 (1d8 + 3) bludgeoning damage on a hit.

**Mindlink Tattoos.** Prisoner 13 has telepathic links with dozens of agents operating throughout the land. The links allow Prisoner 13 to communicate telepathically with each of these agents while they are both on the same plane of existence.

**Mountain Tattoo.** Prisoner 13's AC includes her Constitution modifier.

**Shroud Tattoo.** Prisoner 13 can't be targeted by divination spells or any feature that would read her thoughts, and she can't be perceived through magical scrying sensors. She can't be contacted telepathically unless she allows such contact.


---

### Actions

**Multiattack.** Prisoner 13 makes two Tattooed Strike attacks.

**Tattooed Strike.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 12 (2d8 + 3) force damage.

**Firestorm Tattoo (Recharge 5–6).** Prisoner 13 magically unleashes flame from the tattoo across her back, filling a 20-foot-radius sphere centered on her. Each other creature in that area must make a DC 15 Dexterity saving throw. On a failed save, the creature takes 13 (3d8) fire damage and is knocked prone. On a successful save, it takes half as much damage and isn't knocked prone.

**River Tattoo.** Prisoner 13 magically ends any effects causing the grappled or restrained conditions on herself. If she is bound with nonmagical restraints, she slips out of them.


---

### Reactions

**Readiness.** When a creature Prisoner 13 can see within 60 feet of herself ends its turn, Prisoner 13 makes one Tattooed Strike attack or uses River Tattoo. She can then move up to her speed without provoking opportunity attacks.


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