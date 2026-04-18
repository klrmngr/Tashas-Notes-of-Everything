---
type: pc
race: "Humanoid (human)"
class:
 - "Halaster Blackcloak"
subClass:
 - "CR 23"
cover: "Halaster Blackcloak.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/23
  - source/wdmm
---
###### Halaster Blackcloak
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDMM
___

> [!infobox|no-t right]
> ![[Halaster Blackcloak.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14; 17 with mage armor |
> | :FasHeart: HP | 246 (29d8 + 116) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | WDMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 18 | 24 | 18 | 18 |
| **Mod** | +0 | +4 | +4 | +7 | +4 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 21
**Languages:** Abyssal, Celestial, Common, Draconic, Dwarvish, Elvish, Infernal, Undercommon
**Saving Throws:** Int +14, Wis +11
**Skills:** Arcana +21, History +21, Perception +11
**Damage Resistances:** fire; lightning (granted by the blast scepter, see "Special Equipment" below)

---

### Traits

**Special Equipment.** Halaster wears a robe of eyes that lets him see in all directions, gives him darkvision out to a range of 120 feet, grants advantage on Wisdom (Perception) checks that rely on sight, and allows him to see invisible creatures and objects, as well as into the Ethereal Plane, out to a range of 120 feet.
Halaster wields a blast scepter (a very rare magic item that requires attunement). It can be used as an arcane focus. Whoever is attuned to the blast scepter gains resistance to fire and lightning damage and can, as an action, use it to cast thunderwave as a 4th-level spell (save DC 16) without expending a spell slot.
Halaster also wears a horned ring (a very rare magic item that requires attunement), which allows an attuned wearer to ignore Undermountain's magical restrictions (see "Alterations to Magic").

**Arcane Recovery (1/Day).** When he finishes a short rest, Halaster recovers all his spell slots of 5th level and lower.

**Legendary Resistance (3/Day).** If Halaster fails a saving throw, he can choose to succeed instead.

**Rejuvenation.** If Halaster dies in Undermountain, he revives after 1d10 days, with all his hit points and any missing body parts restored. His new body appears in a random safe location in Undermountain.


---

### Actions

**Blast Scepter.** Halaster uses his blast scepter to cast thunderwave as a 4th-level spell. Each creature in a 15-foot cube originating from him must make a DC 16 Constitution saving throw. On a failed save, a creature takes 5d8 thunder damage and is pushed 10 feet away. On a successful save, the creature takes half as much damage and isn't pushed


---

### Legendary Actions

### 

**Cast Spell.** Halaster casts a spell of 3rd level or lower.

**Spell Ward (Costs 2 Actions).** Halaster expends a spell slot of 4th level or lower and gains 5 temporary hit points per level of the slot.


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