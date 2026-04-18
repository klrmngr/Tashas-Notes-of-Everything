---
type: pc
race: "Humanoid (human)"
class:
 - "Naes Inuus"
subClass:
 - "CR 13"
cover: "Naes Inuus.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/13
  - source/mabjov
---
###### Naes Inuus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Naes Inuus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (breastplate, shield) |
> | :FasHeart: HP | 187 (25d8 + 75) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 16 | 13 | 20 | 14 |
| **Mod** | +2 | +2 | +3 | +1 | +5 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Celestial, Common, Elvish
**Saving Throws:** Con +8, Wis +10
**Skills:** Insight +10, Medicine +15, Persuasion +7, Religion +11
**Damage Resistances:** necrotic

---

### Actions

**Mace.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage plus 14 (4d6) radiant damage.

**Corona of Beauty.** Naes activates an aura of sunlight that lasts for 1 minute or until he dismisses it using an action. He emits bright light in a 60-foot-radius and dim light 30 feet beyond that. His enemies in the bright light have disadvantage on saving throws against any spell that deals fire or radiant damage.

**Radiant Beauty of Sune (Recharge 4–6).** Naes dispels any magical darkness within 30 feet of him. Additionally, each hostile creature within 30 feet of Naes that does not have 3 must make a DC 18 Constitution saving throw, taking 60 radiant damage on a failed saving throw, half as much damage on a successful one. A creature that fails the saving throw has the blinded condition for 1 minute.


---

### Reactions

**Hard to Kill (1/Day).** If Naes would drop to 0 hit points as a result of taking damage, or is subjected to an effect that would kill him instantaneously without doing damage, Naes instead drops to 1 hit point.


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