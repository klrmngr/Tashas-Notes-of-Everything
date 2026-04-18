---
type: pc
race: "Elemental"
class:
 - "Mist Hulk"
subClass:
 - "CR 6"
cover: "Mist Hulk.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/6
  - source/bgg
---
###### Mist Hulk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Mist Hulk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 94 (9d10 + 45) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 21 | 20 | 11 | 13 | 16 |
| **Mod** | +4 | +5 | +5 | +0 | +1 | +3 |

**Speed:** 0 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Auran, Giant
**Saving Throws:** Con +8, Wis +4, Cha +6
**Skills:** Perception +4, Stealth +8
**Damage Resistances:** thunder
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; paralyzed; poisoned; restrained

---

### Traits

**Air Form.** The mist hulk can enter another creature's space and stop there. It can move through a space as narrow as 1 inch without squeezing.

**Death Burst.** When the mist hulk dies, it bursts in a wave of water. Each creature within 10 feet of it must make a DC 16 Dexterity saving throw. On a failed save, a creature takes 11 (2d10) bludgeoning damage and has the prone condition. On a successful save, a creature takes half as much damage only.


---

### Actions

**Multiattack.** The mist hulk makes two Slam attacks.

**Slam.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) cold damage.

**Hideous Wailing (Recharge 5–6).** The mist hulk releases a wail infused with magical anguish. Each creature within 30 feet of it must make a DC 14 Wisdom saving throw. A creature in the mist hulk's space has disadvantage on the saving throw. On a failed save, a creature takes 14 (4d6) psychic damage and has the incapacitated condition for 1 minute. The affected creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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