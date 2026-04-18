---
type: pc
race: "Fey"
class:
 - "Riffler"
subClass:
 - "CR 5"
cover: "Riffler.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/small
  - cr/5
  - source/bmt
---
###### Riffler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Riffler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Fey |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 90 (20d6 + 20) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 12 | 11 | 15 | 17 |
| **Mod** | -1 | +3 | +1 | +0 | +2 | +3 |

**Speed:** 30 ft., burrow 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Sylvan
**Saving Throws:** Dex +6, Cha +6
**Skills:** Arcana +6, Insight +5, Sleight Of Hand +9, Stealth +6
**Damage Resistances:** necrotic; radiant

---

### Traits

**Card Sense.** The riffler can smell the presence of magical cards, including Decks of Many Things and other magical decks, within 1 mile of itself. It knows the direction to any such cards in that range. Effects that protect a target from divination magic block this sense.

**Riffling Step.** The riffler can burrow through any nonmagical material that isn't iron, shuffling the substance through which the riffler moves aside like cards to form a tunnel that closes behind the riffler.


---

### Actions

**Multiattack.** The riffler makes two Spectral Card attacks.

**Spectral Card.** Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 8 (1d10 + 3) force damage plus 5 (1d10) damage that is radiant if the d10 roll is an even number and necrotic if it's odd.

**Card Spray (Recharge 5–6).** The riffler magically unleashes a spray of spectral cards in a 30-foot cone. Each creature in that area must make a DC 14 Dexterity saving throw. On a failed save, a creature takes 27 (5d10) force damage and has the restrained condition for 1 minute as cards bind it. On a successful save, a creature takes half as much damage only. A restrained creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Plane Shift.** The riffler casts the Plane Shift spell targeting only itself, requiring no material components and using Charisma as the spellcasting ability.


---

### Reactions

**Shuffle Destiny.** When a creature the riffler can see within 30 feet of itself makes an ability check, an attack roll, or a saving throw, the riffler can magically force that creature to roll a d6 and either add the number rolled to the total or subtract it from the total (riffler's choice), potentially changing the outcome.


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