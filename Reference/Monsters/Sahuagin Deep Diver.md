---
type: pc
race: "Humanoid (sahuagin)"
class:
 - "Sahuagin Deep Diver"
subClass:
 - "CR 4"
cover: "Sahuagin Deep Diver.png"
campaign:
locations:
tags:
  - race/sahuagin
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/gos
---
###### Sahuagin Deep Diver
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Sahuagin Deep Diver.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (sahuagin) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 91 (14d8 + 28) |
> | :FasUserGroup: Race | Humanoid (sahuagin) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 15 | 12 | 13 | 9 |
| **Mod** | +2 | +3 | +2 | +1 | +1 | -1 |

**Speed:** 30 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Sahuagin
**Saving Throws:** Con +4, Wis +3
**Skills:** Perception +5, Stealth +5

---

### Traits

**Blood Frenzy.** The deep diver has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Brine Lurker.** The deep diver has advantage on Dexterity (Stealth) checks made while submerged in water.

**Limited Amphibiousness.** The deep diver can breathe air and water, but it needs to be submerged at least once every 4 hours to avoid suffocating.

**Lure.** The deep diver can cause its lure to light up or darken at will. While the lure is lit, the deep diver sheds bright light in a 30-foot radius centered on itself and dim light for an additional 20 feet.

**Shark Telepathy.** The deep diver can magically command any shark within 120 feet of it, using a limited telepathy.


---

### Actions

**Multiattack.** The deep diver makes two attacks with its glaive, or one attack with its bite and two with its claws.

**Glaive.** Melee Weapon Attack: +4 to hit, reach 10 ft., one target. *Hit:* 13 (2d10 + 2) slashing damage.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage.

**Claws.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) slashing damage.

**Light of Sekolah.** The deep diver pulses magical light from its lure. Any creature within 30 feet of the deep diver that can see the light must succeed on a DC 11 Wisdom saving throw or be charmed until the end of its next turn. A creature charmed in this way is incapacitated as it stares at the light.


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