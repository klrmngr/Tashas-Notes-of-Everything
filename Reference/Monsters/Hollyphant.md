---
type: pc
race: "Celestial"
class:
 - "Hollyphant"
subClass:
 - "CR 5"
cover: "Hollyphant.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/small
  - cr/5
  - source/bgdia
---
###### Hollyphant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Hollyphant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Celestial |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 36 (8d6 + 8) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 11 | 12 | 16 | 19 | 16 |
| **Mod** | +0 | +0 | +1 | +3 | +4 | +3 |

**Speed:** 20 ft., fly 120 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Celestial, telepathy 120 ft.
**Saving Throws:** Dex +3, Con +4, Cha +6
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Aura of Invulnerability.** An invisible aura forms a 10-foot-radius sphere around the hollyphant for as long as it lives. Any spell of 5th level or lower cast from outside the barrier can't affect creatures or objects within it, even if the spell is cast using a higher level spell slot. Such a spell can target creatures and objects within the barrier, but the spell has no effect on them. Similarly, the area within the barrier is excluded from the areas affected by such spells. The hollyphant can use an action to suppress this trait until its concentration ends (as if concentrating on a spell).

**Magic Weapons.** The hollyphant's weapon attacks are magical.


---

### Actions

**Tusks.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) piercing damage.

**Trumpet (3/Day).** The hollyphant blows air through its trunk, creating a trumpet sound that can be heard out to a range of 600 feet. The trumpet also creates a 30-foot cone of energy that has one of the following effects, chosen by the hollyphant:

**Trumpet of Blasting.** Each creature in the cone must make a DC 14 Constitution saving throw. On a failed save, a creature takes 17 (5d6) thunder damage and is deafened for 1 minute. On a successful save, a creature takes half as much damage and isn't deafened. Nonmagical objects in the cone that aren't being held or worn take 35 (10d6) thunder damage.

**Trumpet of Sparkles.** Creatures in the cone must make a DC 14 Constitution saving throw, taking 22 (4d8 + 4) radiant damage on a failed save, or half as much damage on a successful one. Evil creatures have disadvantage on the saving throw. Good creatures in the cone take no damage.


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