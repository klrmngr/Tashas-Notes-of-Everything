---
type: pc
race: "Dragon"
class:
 - "Adult Solar Dragon"
subClass:
 - "CR 14"
cover: "Adult Solar Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/14
  - source/bam
---
###### Adult Solar Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Adult Solar Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 200 (16d12 + 96) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 15 | 22 | 15 | 16 | 14 |
| **Mod** | +7 | +2 | +6 | +2 | +3 | +2 |

**Speed:** 30 ft., fly 90 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 180 ft., passive Perception 23
**Languages:** Draconic
**Saving Throws:** Dex +7, Con +11, Wis +8, Cha +7
**Skills:** Perception +13, Stealth +7
**Damage Immunities:** radiant
**Condition Immunities:** blinded

---

### Traits

**Flyby.** The dragon doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Legendary Resistance (2/Day).** If the dragon fails a saving throw, it can choose to succeed instead.

**Nebulous Thoughts.** Magical attempts to read the dragon's mind or glean its thoughts fail automatically.

**Siege Monster.** The dragon deals double damage to objects and structures.

**Unusual Nature.** The dragon doesn't require air.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and one Tail attack.

**Bite.** Melee Weapon Attack: +12 to hit, reach 15 ft., one target. *Hit:* 14 (2d6 + 7) piercing damage plus 7 (2d6) radiant damage.

**Tail.** Melee Weapon Attack: +12 to hit, reach 20 ft., one target. *Hit:* 10 (1d6 + 7) bludgeoning damage.

**Photonic Breath (Recharge 5–6).** The dragon exhales a flashing mote of radiant energy that travels to a point the dragon can see within 180 feet of itself, then blossoms into a 30-foot-radius sphere centered on that point. Each creature in the sphere must make a DC 19 Constitution saving throw, taking 55 (10d10) radiant damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Tail Attack.** The dragon makes one Tail attack.

**Burst of Light (Costs 2 Actions).** The dragon emits magical light in a 30-foot-radius sphere centered on itself. Each creature in this area must succeed on a DC 23 Wisdom saving throw or be blinded until the end of its next turn.


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