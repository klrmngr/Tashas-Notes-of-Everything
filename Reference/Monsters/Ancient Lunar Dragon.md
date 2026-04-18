---
type: pc
race: "Dragon"
class:
 - "Ancient Lunar Dragon"
subClass:
 - "CR 19"
cover: "Ancient Lunar Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/19
  - source/bam
---
###### Ancient Lunar Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Ancient Lunar Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 297 (17d20 + 119) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 12 | 24 | 12 | 15 | 17 |
| **Mod** | +8 | +1 | +7 | +1 | +2 | +3 |

**Speed:** 40 ft., burrow 20 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** darkvision 240 ft., passive Perception 24
**Languages:** Draconic
**Saving Throws:** Con +13, Wis +8
**Skills:** Perception +14, Stealth +13
**Damage Immunities:** cold

---

### Traits

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.

**Tunneler.** The dragon can burrow through solid rock at half its burrowing speed and leaves a 20-foot-diameter tunnel in its wake.

**Unusual Nature.** The dragon doesn't require air.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +14 to hit, reach 15 ft., one target. *Hit:* 15 (2d6 + 8) piercing damage plus 7 (2d6) cold damage.

**Claw.** Melee Weapon Attack: +14 to hit, reach 10 ft., one target. *Hit:* 15 (2d6 + 8) slashing damage.

**Tail.** Melee Weapon Attack: +14 to hit, reach 20 ft., one target. *Hit:* 15 (2d6 + 8) bludgeoning damage.

**Cold Breath (Recharge 5–6).** The dragon exhales a blast of frost in a 90-foot cone. Each creature in the cone must make a DC 21 Constitution saving throw. On a failed save, the creature takes 36 (8d8) cold damage, and its speed is reduced to 0 until the end of its next turn. On a successful save, the creature takes half as much damage, and its speed isn't reduced.


---

### Bonus Actions

**Phase (3/Day).** The dragon becomes partially incorporeal for as long as it maintains concentration on the effect (as if concentrating on a spell). While partially incorporeal, the dragon has resistance to bludgeoning, piercing, and slashing damage.


---

### Legendary Actions

### 

**Tail Attack.** The dragon makes one Tail attack.

**Treacherous Ice.** Magical ice covers the ground in a 20-foot radius centered on a point the dragon can see within 120 feet of itself. The ice, which is difficult terrain for all creatures except lunar dragons, lasts for 10 minutes or until the dragon uses this legendary action again.

**Wing Attack (Costs 2 Actions).** The dragon beats its wings. Each creature within 15 feet of the dragon must succeed on a DC 21 Dexterity saving throw or take 12 (1d8 + 8) bludgeoning damage and be knocked prone. The dragon can then fly up to half its speed without provoking opportunity attacks.


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