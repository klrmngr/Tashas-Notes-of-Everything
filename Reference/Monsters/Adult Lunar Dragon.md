---
type: pc
race: "Dragon"
class:
 - "Adult Lunar Dragon"
subClass:
 - "CR 13"
cover: "Adult Lunar Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/13
  - source/bam
---
###### Adult Lunar Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Adult Lunar Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 172 (15d12 + 75) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 12 | 20 | 10 | 13 | 15 |
| **Mod** | +6 | +1 | +5 | +0 | +1 | +2 |

**Speed:** 40 ft., burrow 20 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** darkvision 240 ft., passive Perception 21
**Languages:** Draconic
**Saving Throws:** Con +10, Wis +6
**Skills:** Perception +11, Stealth +11
**Damage Immunities:** cold

---

### Traits

**Legendary Resistance (2/Day).** If the dragon fails a saving throw, it can choose to succeed instead.

**Tunneler.** The dragon can burrow through solid rock at half its burrowing speed and leaves a 15-foot-diameter tunnel in its wake.

**Unusual Nature.** The dragon doesn't require air.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 13 (2d6 + 6) piercing damage plus 3 (1d6) cold damage.

**Claw.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage.

**Tail.** Melee Weapon Attack: +11 to hit, reach 15 ft., one target. *Hit:* 13 (2d6 + 6) bludgeoning damage.

**Cold Breath (Recharge 5–6).** The dragon exhales a blast of frost in a 60-foot cone. Each creature in the cone must make a DC 18 Constitution saving throw. On a failed save, the creature takes 36 (8d8) cold damage, and its speed is reduced to 0 until the end of its next turn. On a successful save, the creature takes half as much damage, and its speed isn't reduced.


---

### Bonus Actions

**Phase (3/Day).** The dragon becomes partially incorporeal for as long as it maintains concentration on the effect (as if concentrating on a spell). While partially incorporeal, the dragon has resistance to bludgeoning, piercing, and slashing damage.


---

### Legendary Actions

### 

**Tail Attack.** The dragon makes one Tail attack.

**Treacherous Ice.** Magical ice covers the ground in a 20-foot radius centered on a point the dragon can see within 120 feet of itself. The ice, which is difficult terrain for all creatures except lunar dragons, lasts for 10 minutes or until the dragon uses this legendary action again.


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