---
type: pc
race: "Giant (bard)"
class:
 - "Cloud Giant Destiny Gambler"
subClass:
 - "CR 19"
cover: "Cloud Giant Destiny Gambler.png"
campaign:
locations:
tags:
  - race/bard
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/19
  - source/bgg
---
###### Cloud Giant Destiny Gambler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Cloud Giant Destiny Gambler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 19 (22,000 XP) |
> | :RiSwordFill: Type | Huge Giant (bard) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 337 (27d12 + 162) |
> | :FasUserGroup: Race | Giant (bard) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 12 | 22 | 19 | 16 | 22 |
| **Mod** | +8 | +1 | +6 | +4 | +3 | +6 |

**Speed:** 40 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 30 ft. (requires cloud rune), passive Perception 19
**Languages:** Common, Giant
**Saving Throws:** Con +12, Int +10, Wis +9, Cha +12
**Skills:** Deception +18, Insight +9, Perception +9
**Damage Immunities:** thunder

---

### Traits

**Cloud Rune.** The giant has a cloud rune inscribed on a mask in its possession. While holding or wearing the mask bearing the rune, the giant has truesight within a range of 30 feet and can use its Thunderous Clap action and Negate Spell reaction.
The mask bearing the cloud rune has AC 15; 45 hit points; and immunity to necrotic, poison, and psychic damage. The mask regains all its hit points at the end of every turn, but it turns to dust if reduced to 0 hit points or when the giant dies. If the rune is destroyed, the giant can inscribe a cloud rune on a mask in its possession when it finishes a short or long rest.


---

### Actions

**Multiattack.** The giant makes three Flying Staff attacks.

**Flying Staff.** Melee or Ranged Weapon Attack: +14 to hit, reach 10 ft. or range 30/90 ft., one target. *Hit:* 18 (3d6 + 8) bludgeoning damage plus 16 (3d10) thunder damage. The staff magically returns to the giant's hand immediately after a ranged attack.

**Thunderous Clap (Requires Cloud Rune).** The giant magically summons a thundercloud that fills a 30-foot-radius sphere centered on a point the giant can see within 60 feet of itself. The cloud spreads around corners. Each creature in that area must make a DC 20 Constitution saving throw as the cloud emits a thunderous boom. On a failed save, a creature takes 52 (8d12) thunder damage and has the prone condition. On a successful save, a creature takes half as much damage only. The thunderclap is audible within 300 feet of the cloud's center point.
The cloud's area is heavily obscured. The cloud lingers until the start of the giant's next turn or until a strong wind disperses it.


---

### Reactions

**Negate Spell (Requires Cloud Rune).** When the giant sees a creature within 60 feet of itself casting a spell, the giant tries to interrupt it. If the creature is casting a spell using a spell slot of 3rd level or lower, the spell fails and has no effect. If the creature is casting a spell of 4th level or higher, it must succeed on a DC 18 Intelligence saving throw, or the spell fails and has no effect.


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