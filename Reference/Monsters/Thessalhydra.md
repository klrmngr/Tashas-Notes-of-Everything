---
type: pc
race: "Monstrosity"
class:
 - "Thessalhydra"
subClass:
 - "CR 4"
cover: "Thessalhydra.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/4
  - source/hftt
---
###### Thessalhydra
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HftT
___

> [!infobox|no-t right]
> ![[Thessalhydra.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 69 (6d12 + 30) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | HftT |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 12 | 20 | 5 | 10 | 7 |
| **Mod** | +4 | +1 | +5 | -3 | +0 | -2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** —
**Skills:** Perception +4
**Damage Immunities:** acid
**Condition Immunities:** blinded; charmed; deafened; frightened; stunned

---

### Actions

**Multiattack.** The thessalhydra makes one maw attack and one Flurry of Bites.

**Flurry of Bites.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 10 (4d4) poison damage.

**Maw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage plus 5 (1d10) acid damage.

**Tail Pincer.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 10 (1d12 + 4) slashing damage, and the target is grappled. As an action, the target can escape the grapple by succeeding on a DC 14 Strength (Athletics) or Dexterity (Acrobatics) check (its choice). Until this grapple ends, the thessalhydra can't use its tail pincer.

**Acid Saliva (Recharge 5–6).** The thessalhydra spits a glob of acid at a point it can see within 30 feet of it. Each creature within 10 feet of that point must make a DC 15 Dexterity saving throw, taking 18 (4d8) acid damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Detect.** The thessalhydra makes a Wisdom (Perception) check with advantage.

**Tail Swipe.** The thessalhydra makes a tail pincer attack.


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