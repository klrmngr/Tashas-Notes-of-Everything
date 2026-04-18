---
type: pc
race: "Aberration"
class:
 - "Aboleth"
subClass:
 - "CR 10"
cover: "Aboleth.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/10
  - source/xmm
---
###### Aboleth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Aboleth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 150 (20d10 + 40) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 9 | 15 | 18 | 15 | 18 |
| **Mod** | +5 | -1 | +2 | +4 | +2 | +4 |

**Speed:** 10 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 20
**Languages:** Deep Speech; telepathy 120 ft.
**Saving Throws:** Dex +3, Con +6, Int +8, Wis +6
**Skills:** History +12, Perception +10

---

### Traits

**Amphibious.** The aboleth can breathe air and water.

**Eldritch Restoration.** If destroyed, the aboleth gains a new body in 5d10 days, reviving with all its Hit Points in the Far Realm or another location chosen by the DM.

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the aboleth fails a saving throw, it can choose to succeed instead.

**Mucus Cloud.** While underwater, the aboleth is surrounded by mucus. con DC 14, each creature in a 5-foot Emanation originating from the aboleth at the end of the aboleth's turn.  The target is cursed. Until the curse ends, the target's skin becomes slimy, the target can breathe air and water, and it can't regain Hit Points unless it is underwater.
While the cursed creature is outside a body of water, the creature takes 6 (1d12) Acid damage at the end of every 10 minutes unless moisture is applied to its skin before those minutes have passed.

**Probing Telepathy.** If a creature the aboleth can see communicates telepathically with the aboleth, the aboleth learns the creature's greatest desires.


---

### Actions

**Multiattack.** The aboleth makes two Tentacle attacks and uses either Consume Memories or Dominate Mind if available.

**Tentacle.** m +9, reach 15 ft. *Hit:* 12 (2d6 + 5) Bludgeoning damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 14) from one of four tentacles.

**Consume Memories.** int DC 16, one creature within 30 feet that is Charmed or Grappled by the aboleth.  10 (3d6) Psychic damage.  Half damage.  The aboleth gains the target's memories if the target is a Humanoid and is reduced to 0 Hit Points by this action.

**Dominate Mind (2/Day).** wis DC 16, one creature the aboleth can see within 30 feet.  The target has the Charmed condition until the aboleth dies or is on a different plane of existence from the target. While Charmed, the target acts as an ally to the aboleth and is under its control while within 60 feet of it. In addition, the aboleth and the target can communicate telepathically with each other over any distance.
The target repeats the save whenever it takes damage as well as after every 24 hours it spends at least 1 mile away from the aboleth, ending the effect on itself on a success.


---

### Legendary Actions

### 

**Lash.** The aboleth makes one Tentacle attack.

**Psychic Drain.** If the aboleth has at least one creature Charmed or Grappled, it uses Consume Memories and regains 5 (1d10) Hit Points.


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