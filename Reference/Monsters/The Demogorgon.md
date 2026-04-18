---
type: pc
race: "Giant"
class:
 - ""The Demogorgon""
subClass:
 - "CR 8"
cover: ""The Demogorgon".png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/8
  - source/imr
---
###### "The Demogorgon"
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: IMR
___

> [!infobox|no-t right]
> ![["The Demogorgon".png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 123 (13d12 + 39) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | IMR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 8 | 17 | 6 | 10 | 8 |
| **Mod** | +5 | -1 | +3 | -2 | +0 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Giant, Orc
**Skills:** Perception +3

---

### Traits

**Two Heads.** The ettin has advantage on Wisdom (Perception) checks and on saving throws against being blinded, charmed, deafened, frightened, stunned, and knocked unconscious.

**Wakeful.** When one of the ettin's heads is asleep, its other head is awake.


---

### Actions

**Multiattack.** The ettin makes two attacks: one with its battleaxe and one with its morningstar.

**Battleaxe.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) slashing damage.

**Morningstar.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) piercing damage.

**Fire Breath (Recharge 5–6).** The ettin's right head exhales fire in a 30-foot cone. Each creature in that area must make a DC 14 Dexterity saving throw, taking 45 (10d8) fire damage on a failed save, or half as much damage on a successful one.

**Cold Breath (Recharge 5–6).** The ettin's left head exhales an icy blast in a 30-foot cone. Each creature in that area must make a DC 14 Constitution saving throw, taking 45 (10d8) cold damage on a failed save, or half as much damage on a successful one.

**Gaze.** The ettin turns its magical gaze toward one creature that it can see within 120 feet of it. That target must make a DC 14 Wisdom saving throw. Unless the target is incapacitated, it can avert its eyes to avoid the gaze and to automatically succeed on the save. If the target does so, it can't see the ettin until the start of the ettin's next turn. If the target looks at the ettin in the meantime, it must immediately make the save.
If the target fails the save, it suffers one of the following effects of the ettin's choice or at random:

**Beguiling Gaze.** The target is stunned until the start of the ettin's next turn or until the ettin is no longer within line of sight.

**Hypnotic Gaze.** The target is charmed by the ettin until the start of the ettin's next turn. The ettin chooses how the charmed target uses its actions, reactions, and movement.

**Insanity Gaze.** The target suffers the effect of the confusion spell without making a saving throw. The effect lasts until the start of the ettin's next turn. The ettin doesn't need to concentrate on the spell.


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