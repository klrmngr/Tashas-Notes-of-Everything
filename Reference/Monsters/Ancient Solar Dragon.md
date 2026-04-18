---
type: pc
race: "Dragon"
class:
 - "Ancient Solar Dragon"
subClass:
 - "CR 21"
cover: "Ancient Solar Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/21
  - source/bam
---
###### Ancient Solar Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Ancient Solar Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 425 (23d20 + 184) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 15 | 26 | 17 | 18 | 16 |
| **Mod** | +9 | +2 | +8 | +3 | +4 | +3 |

**Speed:** 30 ft., fly 120 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 240 ft., passive Perception 28
**Languages:** Draconic
**Saving Throws:** Dex +9, Con +15, Wis +11, Cha +10
**Skills:** Perception +18, Stealth +9
**Damage Immunities:** radiant
**Condition Immunities:** blinded

---

### Traits

**Flyby.** The dragon doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.

**Nebulous Thoughts.** Magical attempts to read the dragon's mind or glean its thoughts fail automatically.

**Siege Monster.** The dragon deals double damage to objects and structures.

**Unusual Nature.** The dragon doesn't require air.


---

### Actions

**Multiattack.** The dragon makes one Bite attack and one Tail attack.

**Bite.** Melee Weapon Attack: +16 to hit, reach 20 ft., one target. *Hit:* 19 (3d6 + 9) piercing damage plus 10 (3d6) radiant damage.

**Tail.** Melee Weapon Attack: +16 to hit, reach 20 ft., one target. *Hit:* 13 (1d8 + 9) bludgeoning damage.

**Photonic Breath (Recharge 5–6).** The dragon exhales a flashing mote of radiant energy that travels to a point the dragon can see within 240 feet of itself, then blossoms into a 40-foot-radius sphere centered on that point. Each creature in the sphere must make a DC 23 Constitution saving throw, taking 66 (12d10) radiant damage on a failed save, or half as much damage on a successful one.


---

### Legendary Actions

### 

**Tail Attack.** The dragon makes one Tail attack.

**Blinding Brilliance (Costs 2 Actions).** The dragon emits magical light in a 30-foot-radius sphere centered on itself. Each creature in this area must succeed on a DC 23 Wisdom saving throw or be blinded until the end of its next turn.


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