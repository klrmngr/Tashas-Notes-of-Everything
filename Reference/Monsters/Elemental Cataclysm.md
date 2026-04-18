---
type: pc
race: "Elemental (titan)"
class:
 - "Elemental Cataclysm"
subClass:
 - "CR 22"
cover: "Elemental Cataclysm.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/elemental
  - size/gargantuan
  - cr/22
  - source/xmm
---
###### Elemental Cataclysm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Elemental Cataclysm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Gargantuan Elemental (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 20 |
> | :FasHeart: HP | 370 (20d20 + 160) |
> | :FasUserGroup: Race | Elemental (titan) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 19 | 27 | 9 | 14 | 9 |
| **Mod** | +8 | +4 | +8 | -1 | +2 | -1 |

**Speed:** 60 ft., burrow 60 ft., fly 80 ft. ((hover)), swim 80 ft. &nbsp;|&nbsp; **Senses:** Truesight 150 ft., passive Perception 12
**Languages:** Primordial
**Saving Throws:** Dex +11, Con +15, Wis +9, Cha +6
**Damage Immunities:** acid; cold; fire; lightning; poison; thunder
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained; stunned; unconscious

---

### Traits

**Earth Glide.** The cataclysm can burrow through nonmagical, unworked earth and stone. While doing so, the cataclysm doesn't disturb the material it moves through.

**Legendary Resistance (4/Day).** If the cataclysm fails a saving throw, it can choose to succeed instead.

**Siege Monster.** The cataclysm deals double damage to objects and structures.


---

### Actions

**Multiattack.** The cataclysm makes two Elemental Burst attacks.

**Elemental Burst.** m,r +15, reach 30 ft. or range 150 ft. *Hit:* 25 (5d6 + 8) damage of a type chosen by the cataclysm: Acid, Cold, Fire, Lightning, or Thunder.

**Cataclysmic Event (Recharge 4–6).** The cataclysm creates one of the following effects at random (roll 1d4):
- **1: Clinging Flames.** dex DC 23, each creature in a 60-foot-radius Sphere centered on a point the cataclysm can see within 150 feet.  45 (13d6) Fire damage.  Half damage.  The target starts burning.
- **2: Freezing Waves.** str DC 23, each creature in a 90-foot Cone.  22 (5d8) Bludgeoning damage plus 22 (5d8) Cold damage, and the target has the Prone condition.  Half damage only.  The target's Speed is reduced to 0 until the end of its next turn.
- **3: Raging Storm.** A storm cloud fills a 60-foot-radius Sphere centered on a point the cataclysm can see within 150 feet. The cloud lasts for 1 minute or until the cataclysm uses Cataclysmic Event again. Creatures entirely in the cloud have the Blinded and Deafened conditions and can't cast spells with a Verbal component. dex DC 23, each creature that enters the cloud for the first time on a turn or starts its turn there.  18 (4d8) Lightning damage plus 18 (4d8) Thunder damage.  Half damage.
- **4: Swallowing Earth.** str DC 23, each creature in a 90-foot Cube originating from a point on the ground within 150 feet.  18 (4d8) Bludgeoning damage plus 18 (4d8) Acid damage, and the target has the Prone condition and is buried under rubble. A buried target has the Restrained condition, has Total Cover, and is suffocating. As an action, a buried creature or another creature within 5 feet of it can make a DC 18 Strength (Athletics) check. On a successful check, the creature is no longer buried.  Half damage only.


---

### Legendary Actions

### 

**Eruption.** The cataclysm makes one Elemental Burst attack.

**Rumbling Movement.** The cataclysm moves up to its Speed, Fly Speed, or Swim Speed without provoking Opportunity Attacks. Each creature within 5 feet of the cataclysm as it moves is targeted once by the following effect. con DC 23.  The target has the Prone condition.  The cataclysm can't take this action again until the start of its next turn.


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