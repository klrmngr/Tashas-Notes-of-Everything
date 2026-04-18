---
type: pc
race: "Giant (titan)"
class:
 - "Scion of Skoraeus"
subClass:
 - "CR 23"
cover: "Scion of Skoraeus.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/giant
  - size/gargantuan
  - cr/23
  - source/bgg
---
###### Scion of Skoraeus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Scion of Skoraeus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Gargantuan Giant (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 444 (24d20 + 192) |
> | :FasUserGroup: Race | Giant (titan) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 20 | 26 | 19 | 24 | 14 |
| **Mod** | +9 | +5 | +8 | +4 | +7 | +2 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 24
**Languages:** Giant, Primordial
**Saving Throws:** Dex +12, Wis +14
**Skills:** Acrobatics +12, Perception +14
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid
**Condition Immunities:** charmed; frightened; paralyzed; petrified

---

### Traits

**Legendary Resistance (6/Day).** If the scion fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The scion has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The scion deals double damage to objects and structures.


---

### Actions

**Multiattack.** The scion makes one Crystal Club attack and two Slam attacks, then uses Entombing Grasp if available. Alternatively, the scion makes two Runic Boulder attacks.

**Crystal Club.** Melee Weapon Attack: +16 to hit, reach 30 ft., one target. *Hit:* 35 (4d12 + 9) bludgeoning damage. The scion can cause the club to flare with bright light, and the target must succeed on a DC 22 Constitution saving throw or take 18 (4d8) radiant damage and have the blinded condition until the start of the scion's next turn.

**Slam.** Melee Weapon Attack: +16 to hit, reach 20 ft., one target. *Hit:* 31 (4d10 + 9) force damage.

**Runic Boulder.** Ranged Weapon Attack: +16 to hit, range 120/480 ft., one target. *Hit:* 27 (4d8 + 9) bludgeoning damage. The boulder explodes. The target and each creature within 30 feet of it must make a DC 22 Dexterity saving throw. On a failed save, a creature takes 19 (3d12) force damage and has the prone condition. On a successful save, a creature takes half as much damage only.

**Entombing Grasp (Recharge 6).** The scion wreathes its hand in petrifying magic and touches one Huge or smaller creature it can see within 20 feet of itself. The target must succeed on a DC 24 Dexterity saving throw or take 28 (8d6) force damage and have the grappled condition (escape DC 19). At the start of the scion's next turn, if the target is still grappled, the target has the petrified condition.


---

### Bonus Actions

**Earth-Shaking Movement.** The scion moves up to its speed and then sends a shock wave through the ground in a 60-foot radius circle centered on itself. Each creature on the ground in that area that is concentrating must succeed on a DC 24 Constitution saving throw or lose concentration.


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