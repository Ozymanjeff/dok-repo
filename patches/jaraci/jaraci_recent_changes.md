
# About

This is the recent changes list for Jaraci balance mod.
Full combined changelog can be found [HERE](jaraci.md)

# Table of contents

- [About](#about)
- [Table of contents](#table-of-contents)
- [Changes](#changes)
	- [2020-01-11](#2020-01-11)
	- [2020-01-19 (Jaraci Cup #4)](#2020-01-19-jaraci-cup-4)
	- [2020-01-22](#2020-01-22)
	- [2020-01-31](#2020-01-31)
	- [2020-02-01](#2020-02-01)
	- [2020-02-03](#2020-02-03)
	- [2020-02-05](#2020-02-05)
	- [2020-02-06](#2020-02-06)
	- [2020-02-08](#2020-02-08)
	- [2020-02-11](#2020-02-11)
	- [2020-02-12](#2020-02-12)
	- [2020-02-15](#2020-02-15)
	- [2020-02-17](#2020-02-17)
	- [2020-02-18](#2020-02-18)
	- [2020-02-22](#2020-02-22)
	- [2020-02-23](#2020-02-23)
	- [2020-02-25](#2020-02-25)
	- [2020-02-26](#2020-02-26)
	- [2020-02-27](#2020-02-27)
	- [2020-02-28](#2020-02-28)
	- [2020-02-29](#2020-02-29)
	- [2020-03-02](#2020-03-02)
	- [2020-03-06](#2020-03-06)
	- [2020-03-07](#2020-03-07)
	- [2020-03-09](#2020-03-09)
	- [2020-03-10](#2020-03-10)
	- [2020-03-11](#2020-03-11)
	- [2020-03-14](#2020-03-14)
	- [2020-03-15](#2020-03-15)
	- [2020-03-21](#2020-03-21)
	- [2020-03-28](#2020-03-28)
	- [2020-04-05](#2020-04-05)
	- [2020-04-06](#2020-04-06)
	- [2020-04-09](#2020-04-09)
	- [2020-04-10](#2020-04-10)
	- [2020-04-17 (Jaraci Cup #5)](#2020-04-17-jaraci-cup-5)
	- [2020-04-30](#2020-04-30)
	- [2020-05-01](#2020-05-01)
	- [2020-05-06](#2020-05-06)
	- [2020-05-10](#2020-05-10)
	- [2020-05-11](#2020-05-11)
	- [2020-05-22](#2020-05-22)
	- [2020-05-23](#2020-05-23)
	- [2020-05-25 (Jaraci Cup #6)](#2020-05-25-jaraci-cup-6)
	- [2020-07-08](#2020-07-08)
	- [2020-07-12](#2020-07-12)
	- [2020-07-18](#2020-07-18)
	- [2020-07-26 (Jaraci Cup #7)](#2020-07-26-jaraci-cup-7)
	- [2020-09-23](#2020-09-23)
	- [2020-09-25](#2020-09-25)
	- [2020-10-07 (Jaraci Cup #8)](#2020-10-07-jaraci-cup-8)
	- [2020-10-18](#2020-10-18)
	- [2020-11-21 (Jaraci Cup #9)](#2020-11-21-jaraci-cup-9)
	- [2020-12-18](#2020-12-18)
	- [2020-12-19](#2020-12-19)
	- [2020-12-21](#2020-12-21)
	- [2021-01-05](#2021-01-05)
	- [2021-01-06](#2021-01-06)
	- [2021-01-06 (2)](#2021-01-06-2)
	- [2021-01-09](#2021-01-09)
	- [2021-01-30](#2021-01-30)
	- [2021-01-09](#2021-01-09-1)

# Changes

## 2020-01-11
* General:
	* Made improvements to unit base target priority:
		* Carriers: reduced
		* Salvagers: reduced
		* Heavy railguns: increased
		* Strike craft: increased (to match HR)
		* Baserunners: reduced
		* Turret: reduced
		* AA turret: reduced

## 2020-01-19 (Jaraci Cup #4)
* Coalition/Soban:
	* Tactical bomber damage: `1850 => 1700`

## 2020-01-22
* Gaalsien:
	* Baserunner heal aura ability status effect heal per tick: `4 => 3` (Total healing: `1000 => 800`)

## 2020-01-31
* General:
	* Target priority:
		* Baserunner: `reduced` (now lowest priority of all)
		* Strike craft: `reduced` (now slightly higher than salvagers)
		* Salvagers: `increased` (now slightly higher than 0)
* Coalition/Soban:
	* AAV max movement speed: `80 => 84`
	* Assault cruiser tactical missile barrage max range: `1200 => 1000`
* Coalition:
	* Carrier:
		* Max movement speed: `53 => 50`
		* Cruise missile area of effect: `470 => 500`
	* Railgun armor: `2 => 0`
* Soban:
	* Carrier max movement speed: `60 => 50`
	* Railgun armor: `1 => 0`
	* Battlecruiser:
		* Hitpoints: `3800 => 3000`
		* Armor: `15 => 13`
		* Movement dynamics:
			* Max movement speed: `54 => 62`
			* Max speed turn radius: `130 => 160`
			* Acceleration time: `1.2s => 1.9s`
			* Braking time: `0.9s => 1.2s`
* Gaalsien/Khaaneph:
	* Production cruiser sensors range: `1000 => 1200`
	* Railgun tech research time: `50s => 45s`
	* Heavy railgun EMP round damage: `200 => 150`
	* Assault railgun:
		* Hitpoints: `660 => 700`
		* Production time: `20s => 19s`
		* Armor: `6 => 3`
		* Max movement speed: `92 => 100`
	* Assault ship:
		* Production time: `17s => 18s`
		* Damage: `35 => 38`
		* Area of effect falloff: `Quadratic => Linear`
		* Max movement speed: `70 => 75`
		* Max range: `755 => 750`
	* Interceptor:
		* Area of effect: `60 => 80`
* Gaalsien:
	* Carrier:
		* Hyper-sonic missile barrage missile area of effect falloff: `Linear => Quadratic`

## 2020-02-01
* Gaalsien/Khaaneph:
	* Heavy railgun EMP affected by high ground: `Yes => No`

## 2020-02-03
* General:
	* Target prioritization:
		* Heavy railguns:
			* Weapon effectiveness weight: `50 => 80`
			* Auto target sticky bias: `1750 => 200`
		* ALM:
			* Distance weight: `0.5 => -0.1`
		* Gun turret:
			* Priority as target: `500 => 50`
* Coalition/Soban:
	* Support cruiser repair rate: `12 => 11`
* Coalition:
	* Carrier PD rate of fire: `7 => 8`
* Soban:
	* ALM:
		* World height offset: `0 => 15`
		* Power shunt reload time:
			* Level 1: `7s => 6.5s`
			* Level 2: `6s => 5.5s`
			* Level 3: `5s => 4.5s`
			* Level 4: `4s => 3.5s`
			* Level 5: `3s => 2.5s`
	* Baserunner ECM jammer:
		* Cost: `Free => 50CU`
		* Slow down effect: `40% => 65%`
		* Cooldown: `90s => 30s`
* Gaalsien/Khaaneph:
	* Heavy railgun:
		* Range: `1860 => 1900` (now matches C/S railgun again)
		* Accuracy: (Now matches C/S railgun accuracy)
			* Short: `6% => 6.25%`
			* Medium: `5% => 5.75%`
			* Long: `4% => 5.5%`
		* EMP:
			* Duration: `2.5s => 2s`
			* Disables abilities: `No => Yes`
			* Disables weapons: `No => Yes`

## 2020-02-05
* General:
	* Heavy railgun:
		* Max range: `1900 => 2000`
		* Population cost: `3 => 4`
* Coalition/Soban:
	* Missile battery mortar barrage:
		* Damage packets: `40 => 35`
		* Area of effect falloff: `Quadratic => Linear`
		* Area of effect: `205 => 220`
	* Assault cruiser population cost: `4 => 5`
* Coalition:
	* Battlecruiser population cost: `6 => 7`
* Soban:
	* Targeting jammer:
		* Cost: `50CU => Free`
		* Cooldown: `30s => 60s`
		* Hitpoints: `500 => 1200`
		* Speed reduction modifier: `65% => 45%`
	* Battlecruiser population cost: `5 => 7`
* Gaalsien/Khaaneph:
	* Ranged calibration penalties:
		* Max speed: `66% => 50%`
		* Turn radius: `66% => 50%`
	* Honourguard cruiser population cost: `5 => 7`
* Gaalsien:
	* Siege cruiser population cost: `4 => 5`
* Khaaneph:
	* Carrier cruise missile damage: `450 => 500`
	* Siege cruiser population cost: `5 => 6`

## 2020-02-06
* General:
	* Heavy railgun population cost: `4 => 3`
* Coalition/Soban:
	* Battlecruiser population cost: `7 => 6`

## 2020-02-08
* Coalition/Soban:
	* Production level 1 upgrade cost: `500CU 40RU => 400CU 40RU`
	* Vehicle armor upgrade level 3 hitpoints granted: `200 => 100`
	* LAV:
		* Long range accuracy: `62 => 59`
		* Tech:
			* Cost: `300CU => 400CU`
			* Research time: `40s => 30s`
	* AAV:
		* Tech research time: `50s => 55s`
		* Armor: `9 => 8`
		* Hitpoints: `1250 => 1200`
	* Railgun:
		* Tech research time: `50s => 55s`
		* Mag accelerator damage bonus: `60 => 40`
		* Accuracy:
			* Short: `6.25% => 8%`
			* Medium: `5.75% => 7.5%`
			* Long: `5.5 => 7%`
	* Strike fighter cost: `200CU 85RU => 200CU 90RU`
	* Assault cruiser:
		* Cost: `450CU 220RU => 550CU 220RU`
		* Max movement speed: `70 => 65`
* Coalition:
	* Turret:
		* Rate of fire: `5 => 4`
		* Burst: `0.2s => 0.25s`
	* Railgun:
		* Cost: `230CU 80RU => 240CU 80RU` (to match Soban railguns)
		* Damage: `195 => 150`
		* Reload time: `2.3s => 1s`
* Soban:
	* Railgun:
		* Damage: `135 => 150`
		* Cooldown: `1.5s => 0.2s`
		* Reload: `1.85s => 2s`
	* Targeting jammer:
		* Hitpoints: `1200 => 1100`
		* Cooldown: `60s => 80s`
		* Projectile: `Mine => Scanner` (increased travel speed)
* Gaalsien/Khaaneph:
	* Skimmer:
		* Tech research time: `35s => 25s`
		* Sensors range: `1050 => 1100`
	* Railgun armor upgrade level 3 hitpoints granted to heavy railguns: `200 => 100`
	* Assault railgun:
		* Cost: `220CU 50RU => 250CU 50RU`
		* Hitpoints: `700 => 670`
		* Max range: `1000 => 1100`
	* Heavy railgun:
		* Damage: `195 => 190`
		* Movement speed: `57 => 65`
		* Accuracy:
			* Short: `6.25% => 10%`
			* Medium: `5.75% => 9.5%`
			* Long: `5.5% => 9%`
	* Interceptor:
		* Area of effect: `80 => 70`
		* Damage against carriers: `100 => 60`
	* Production cruiser contact radius: `1250 => 1350`
* Gaalsien:
	* Siege cruiser autofire:
		* Damage: `140 => 120`
		* Reload: `3s => 4s`

## 2020-02-11
* Coalition/Soban:
	* AAV:
		* Armor: `8 => 6`
		* Hitpoints: `1200 => 1250`
	* Railgun production research time: `55s => 60s`
* Gaalsien/Khaaneph:
	* Assault ship:
		* Tech cost: `500CU 100RU => 500CU 125RU`
		* Tech research time: `60s => 65s`
		* Hitpoints: `960 => 1100`
		* Armor: `6 => 5`
* Gaalsien:
	* Fixed an issue where the entity which granted vision for hypersonic missile barrage had a population cost (`1 => 0`)

## 2020-02-12
* Coalition:
	* AAV max speed: `84 => 80`
	* Railgun:
		* Wind-up: `1.6s => 2s`
		* Reload time: `1s => 1.5s`
* Soban:
	* Railgun:
		* Wind-up: `1.6s => 2s`
		* Cooldown: `0.2s = 1.2s`
		* Reload time: `2s => 3.2s`
* Gaalsien/Khaaneph:
	* Missile ship fabrication research time: `55s => 45s`
* Khaaneph:
	* Carrier PD:
		* Rate of fire: `6 => 8`
		* Range: `950 => 1050`
	* Baserunner max speed: `70 => 80`

## 2020-02-15
* General:
	* Heavy railgun target prioritization:
		* Weapon effectiveness weight: `80 => 500`
		* Auto target sticky bias: `200 => 50`
		* Angle weight: `10 => 25`
* Coalition/Soban:
	* LAV:
		* Tech cost: `400CU => 350CU`
		* Accuracy:
			* Short: `94% => 96%`
			* Medium: `82% => 85%`
	* AAV:
		* Tech cost: `350CU 85RU => 400CU 85RU`
		* Hitpoints: `1250 => 1150`
		* Armor: `6 => 8`
* Gaalsien/Khaaneph:
	* Sandskimmer tech research time: `25s => 30s`
	* Heavy railgun population cost: `3 => 4`
	* Assault railgun:
		* Hitpoints: `670 => 750`
		* Max speed: `100 => 90`
		* Damage packets: `1 => 2`

## 2020-02-17
* General:
	* Demo pack:
		* Cost: `50CU => 150CU`
		* Damage: `175 => 350`
		* Packets: `1 => 2`
	* Baserunner:
		* Cost: `250CU 60RU => 250CU 50RU`
		* Hitpoints: `2500 => 2200`
	* Priority as target:
		* Carrier: `increased`
		* HR: `increased`
		* Baserunner: `decreased`
* Coalition/Soban:
	* LAV production time: `12s => 13s`
	* AAV:
		* Cost: `240CU 25RU => 260CU 25RU`
		* Range: `800 => 900`
		* Sensors: `1000 => 1100`
		* Slow effect: `50% => 35%`
	* Railgun tech cost: `400CU 165RU => 350CU 165RU`
	* Support cruiser:
		* Cost: `580CU 40RU => 500CU 50RU`
		* Production time: `45s => 35s`
		* Hitpoints: `4100 => 3200`
		* Armor: `3 => 7`
		* Turn radius: `85 => 75`
	* Tactical bomber damage: `1700 => 1500`
* Gaalsien/Khaaneph:
	* Production cruiser cost: `640CU 60RU => 600CU 60RU`
	* Sandskimmer:
		* Sensors range: `1100 => 1150`
		* Production time: `11s => 12s`
	* Assault ship:
		* Hitpoints: `1100 => 1050`
		* Range: `750 => 840`
		* Area of effect: `110 => 120`
		* Sensors: `1000 => 1100`
		* Contact radius: `1200 => 1250`
	* Railgun fabrication tech cost: `450CU 200RU => 350CU 250RU`

## 2020-02-18
* General:
	* Carrier PD weapons:
		* Accuracy against medium targets: `115% => 100%`
		* Benefit from high ground: `Yes => No`
* Coalition/Soban:
	* Medium vehicle armor upgrade level 3 cost: `300CU 400RU => 300CU 300RU`
	* AAV tech cost: `400CU 85RU => 400CU 115RU`
	* Railgun
		* Damage: `150 => 130`
		* Mag accelerator damage bonus: `40 => 25`
* Coalition:
	* Carrier:
		* Hitpoints: `12000 => 11000`
		* Cruise missile damage: `2500 => 2400`
* Soban:
	* Carrier hitpoints: `10000 => 9000`
* Gaalsien/Khaaneph:
	* Assault ship tech cost: `500CU 125RU => 450CU 135RU`
	* Railgun armor upgrades:
		* Level 2 cost: `200CU 200RU => 250CU 200RU`
		* Level 3 cost: `200CU 400RU => 300CU 300RU`
	* Heavy railgun:
		* Cost: `320CU 100RU => 350CU 100RU`
		* Damage: `190 => 155`
* Gaalsien:
	* Carrier hitpoints: `10100 => 9200`
* Khaaneph:
	* Carrier hitpoints: `10500 => 9500`

## 2020-02-22
* General:
	* Demo pack damage: `350 => 275`
* Gaalsien/Khaaneph:
	* Honourguard cruiser damage: `550 => 500`

## 2020-02-23
* General:
	* C/G Carrier level 0 range systems:
		* PD & missile range: `500 => 700`
		* Fixed an issue where power shunt description was incorrect and showed range as being 600, whereas it was only 500
* Coalition/Soban:
	* AAV hitpoints: `1150 => 1070`
	* Mag accelerator cost: `400CU 100RU => 100CU 250RU`
	* Strike fighter:
		* Tech cost: `450CU 250RU => 450CU 200RU`
		* Cost: `200CU 90RU => 200CU 85RU`
		* Damage: `120 => 100`
	* Assault cruiser:
		* Tech cost: `500CU 300RU => 500CU 250RU`
		* Damage: `55 => 50`
		* Area of effect: `80 => 90`
	* Battlecruiser:
		* Tech cost: `550CU 350RU => 550CU 300RU`
		* Production time: `65s => 60s`
* Coalition:
	* Battlecruiser:
		* Hitpoints: `4200 => 3500`
		* Armor: `16 => 15`
		* Range: `1300 => 1400`
* Soban:
	* Battlecruiser:
		* Tech research time: `110s => 95s`
		* Hitpoints: `3000 => 2900`
		* Range: `1750 => 1900`
* Gaalsien/Khaaneph:
	* Production cruiser hitpoints: `4100 => 3900`
	* Fixed a bug where railgun tech cost wasn't modified (cost: `450CU 200RU => 350CU 250RU`)
	* Assault ship:
		* Tech cost: `450CU 135RU => 350CU 125RU`
		* Max health: `1100 => 930`
		* Armor: `5 => 6`
		* Range: `840 => 940`
		* Damage: `38 => 35`
		* Area of effect: `120 => 140`
		* Burst: `0.8-1s => 0.75s-0.85`
	* Assault railgun:
		* Cost: `250CU 50RU => 240CU 45RU`
		* Production time: `19 => 16`
		* Armor: `3 => 0`
		* Damage: `60 => 55`
		* Reload: `2.4s => 2.6s`
	* Interceptor:
		* Tech cost: `550CU 250RU => 450CU 250RU`
		* Reload: `3.8s => 4.5s`
* Gaalsien:
	* Carrier:
		* Armor: `30 => 20`
		* Hypersonic missile barrage damage: `300 => 280`
* Khaaneph:
	* Fixed an issue where carrier weapon systems were incorrectly displaying base PD rate of fire (6 instead of 8)
	* Blast drone max speed: `160 => 180`

## 2020-02-25
* General:
	* C/G Carrier level 0 range systems PD & missile range: `700 => 650`

## 2020-02-26
* Coalition/Soban:
	* Artillery cruiser:
		* Autofire damage: `140 => 100`
		* Barrage recharge: `65s => 100s`
* Coalition:
	* Cruise missile recharge: `150s => 170s`
	* Battlecruiser production time: `60s => 55s`
* Soban:
	* Microwave emitter recharge: `110s => 150s`
* Gaalsien/Khaaneph:
	* Assault ship damage: `35 => 32`
* Gaalsien:
	* Hyper-sonic missile barrage:
		* Recharge: `120s => 160s`
		* Damage: `280 => 260`
	* Scanner sensors radius: `1400 => 1350`
	* Siege cruiser:
		* Armor: `5 => 3`
		* Autofire:
			* Damage: `120 => 80`
			* Reload: `4s => 10s`
		* Barrage:
			* Damage: `150 => 170`
			* Recharge: `50s => 120s`
* Khaaneph:
	* Siege cruiser barrage:
		* Damage: `260 => 280`
		* Recharge: `65s => 100s`

## 2020-02-27
* General:
	* Salvager cost: `150CU => 100CU`
	* Demo pack cost: `150CU => 200CU`
* Coalition/Soban:
	* Support cruiser:
		* Repair rate: `11 => 9`
		* G2G weapon (DPS: `4-2 => 37-29`):
			* Damage: `3 => 17`
			* Burst: `0.4-0.8s => 1.0-1.2s`
			* Cooldown: `2s => 0.5s`
			* Reload: `4s => 2s`
			* Accuracy: `75%/55%/35% => 45%/35%/35%`
			* Ranges: `300/600/900 => 400/600/1100`
			* Can target air: `No => Yes`
			* Damage against air: `100% => 200%`
			* Damage against probes: `100% => 20%`
			* Accuracy against non-small targets: `100% => 150%`
			* Benefits from high ground: `Yes => No`
			* Turret:
				* Field of fire: `8 => 360`
				* Field of view: `140 => 360`
				* Rotation speed: `75 => 160`
	* LAV:
		* Armor: `0 => 1`
		* Accuracy:
			* Short: `96 => 100`
			* Long: `59 => 62`
	* AAV:
		* Tech cost: `400CU 115RU => 400CU 65RU`
		* Suppression ability slow effect: `35% => 42%`
	* Gunship area of effect: `220 => 200`
* Coalition:
	* Baserunner turret:
		* Damage: `55 => 65`
		* Rate of fire: `4 => 3`
		* Burst duration: `0.25s => 0.334s`
		* Reload: `2.2s => 1.65s`
		* Range: `1200 => 1300`
		* Accuracy: `100%/100%/100% => 100%/95%/85%`
		* World height offset: `5 => 15`
* Gaalsien/Khaaneph:
	* Refinery mode cost: `700CU 40RU => 600CU 80RU`
	* Production cruiser AA weapon (DPS: `79-45 => 45-28`):
		* Can target ground: `No => Yes`
		* Line of sight required: `No => Yes`
		* Damage: `20 => 17`
		* Rate of fire: `12 => 10`
		* Range: `1250 => 1200`
		* Accuracy: `70%/55%/40% => 55%/45%/35%`
		* Accuracy against non-small targets: `100% => 150%`
		* Damage against air: `100% => 200%`
		* Damage against probe: `35% => 45%`
	* Assault ship:
		* Tech cost: `350CU 115RU => 450CU 80RU`
		* Damage: `32 => 30`
	* Assault railgun:
		* Range: `1100 => 1150`
		* Dart maneuver duration: `2s => 3s`
	* Heavy railgun EMP ability:
		* Damage: `150 => 100`
		* Status effect duration: `2s => 2.5s`

## 2020-02-28
* General:
	* Salvager:
		* Hitpoints: `900 => 950`
		* Cost: `100CU => 150CU`
	* Demo pack cost: `200CU => 150CU`
* Coalition/Soban:
	* Baserunner hitpoints: `2200 => 2400`
	* LAV (overall DPS increased by about 12%):
		* Production time: `13s => 12s`
		* Damage: `12 => 11`
		* Rate of fire: `5 => 6`
		* Short range accuracy: `100% => 90%`
	* AAV:
		* Hitpoints: `1070 => 1150`
		* Weapon (DPS: `85 => 82`):
			* Damage: `17 => 18`
			* Rate of fire: `13 => 12`
	* Heavy railgun:
		* Fixed an issue where damage was set incorrectly: `150 => 130`
		* Accuracy: `8%/7.5%/7% => 7%/6.5%/6%`
		* Turret rotation speed: `180 => 250`
	* Support cruiser G2G weapon:
		* Range: `1100 => 950`
		* Damage against air: `200% => 130%`
* Coalition:
	* Turret:
		* Range: `1300 => 1400`
		* Area of effect: `0 => 70`
		* Area of effect falloff: `None => Linear`
* Gaalsien/Khaaneph:
	* Salvager armor: `0 => 3`
	* Skimmer:
		* Production time: `12s => 11s`
		* Hitpoints: `610 => 630`
		* Short range accuracy: `100% => 85%`
	* Production cruiser AA weapon (anti-ground functionality reverted):
		* Can target ground: `Yes => No`
		* Line of sight required: `Yes => No`
		* Damage: `17 => 20`
		* Rate of fire: `10 => 12`
		* Range: `1200 => 1250`
		* Accuracy: `55%/45%/35%=> 70%/55%/40%`
		* Accuracy against non-small targets: `150% => 100%`
		* Damage against air: `200% => 100%`
		* Damage against probe: `45% => 35%`
	* Heavy railgun:
		* Fixed an issue where damage was set incorrectly: `190 => 155`
		* Accuracy: `10%/9.5%/9% => 7%/6.5%/6%`
		* Turn radius: `150 => 50`
		* EMP shell ability:
			* Research cost: `200CU 100RU => 300CU 100RU`
			* Research time: `30s => 35s`
			* Recharge time: `45s => 100s`
			* Damage: `100 => 70`
			* Range: `1350 => 1250`
			* Stun duration: `2.5s => 2.2s`
			* Area of effect: `150 => 135`
* Gaalsien:
	* Carrier hitpoints: `9200 => 8800`
	* Baserunner:
		* Hitpoints: `2200 => 2000`
		* Scanner:
			* Ability cooldown: `120s => 140s`
			* Sensors radius: `1350 => 1300`

## 2020-02-29
* AAV TTK vs AS:
	* Armor 0: `6.38s => 6.07s`
	* Armor 1: `6.96s => 6.58s`
	* Armor 2: `8.48s => 7.93s`
	* Armor 3: `11.23s => 10.37s`

---

* Coalition/Soban:
	* Strike fighter:
		* Damage: `100 => 110`
		* Damage packets: `1 => 2`
* Coalition:
	* Baserunner turret:
		* Damage: `65 => 60`
		* Rate of fire: `3 => 4`
		* Number of bursts: `12 => 14`
		* Long range accuracy: `85% => 60%`
		* Area of effect: `70 => 85`
		* Area of effect falloff type: `Linear => Quadratic`
* Gaalsien/Khaaneph:
	* Assault ship:
		* Hitpoints: `930 => 960`
		* Armor: `6 => 5`
		* Range: `940 => 920`
		* Movement speed: `75 => 72`
	* Interceptor damage packets: `1 => 2`

## 2020-03-02
* Coalition/Soban:
	* Gunship area of effect: `200 => 180`
* Coalition:
	* Turret:
		* Damage: `60 => 55`
		* Area of effect: `85 => 105`
		* Number of bursts: `14 => 16`
* Gaalsien/Khaaneph:
	* Sandskimmer weapon (DPS: `38.2 => 38.8`):
		* Damage: `13 => 11`
		* Long range accuracy: `88.21% => 80%`
		* Rate of fire: `5 => 6`
		* Cooldown: `0.22s => 0.3s`
		* Reload: `0.5s => 0.6s`
		* Burst: `0.7-0.76s => 0.78-0.84s`

## 2020-03-06
* Coalition/Soban:
	* AAV production time: `16s => 18s`
* Gaalsien/Khaaneph:
	* Assault railgun:
		* Armor: `0 => 3`
		* Sensors range: `1000 => 1150`

## 2020-03-07
* General:
	* Demo pack:
		* Cost: `150CU => 100CU`
		* Damage: `275 => 220`
	* Heavy railgun range: `2000 => 2060`
* Coalition/Soban:
	* LAV:
		* Tech research time: `30s => 35s`
		* Hitpoints: `570 => 500`
		* Damage: `11 => 12`
	* AAV:
		* Cost: `260CU 25RU => 260CU 20RU`
		* Hitpoints: `1150 => 850`
		* Production time: `18s => 17s`
		* Damage: `18 => 16`
	* Assault cruiser:
		* Area of effect: `90 => 75`
		* Missile barrage damage: `200 => 180`
	* Gunship:
		* Damage: `42 => 40`
		* Area of effect: `180 => 160`
* Coalition:
	* Carrier hitpoints: `12000 => 9800`
* Soban:
	* Carrier hitpoints: `9100 => 9300`
* Gaalsien/Khaaneph:
	* Sandskimmer:
		* Hitpoints: `670 => 540`
		* Damage: `11 => 12`
	* Assault railgun damage packets: `2 => 1`
* Gaalsien:
	* Carrier hitpoints: `8800 => 9100`
* Khaaneph:
	* Blast drone:
		* Production time: `45s => 50s`
		* Hitpoints: `400 => 450`
		* Max speed: `180 => 220`
	* Siege cruiser:
		* Armor: `13 => 12`
		* Damage: `150 => 130`
		* Area of effect: `210 => 240`
		* Barrage damage: `280 => 260`

## 2020-03-09
* General:
	* Carrier power level upgrades hitpoints granted per upgrade: `0 => 300`
* Coalition/Soban:
	* AAV:
		* Hitpoints: `850 => 890`
		* Suppression slow effect: `42% => 35%`
	* Support cruiser PD weapon:
		* Damage: `17 => 15`
		* Rate of fire: `12 => 10`
* Coalition:
	* Carrier hitpoints: `9800 => 9000`
* Soban:
	* Carrier hitpoints: `9300 => 8500`
* Gaalsien:
	* Carrier hitpoints: `8800 => 8000`
* Khaaneph:
	* Carrier hitpoints: `9500 => 8700`
	* Blast drone:
		* Hitpoints: `450 => 500`
		* Max speed: `220 => 200`
		* Population cost: `1 => 2`
		* Damage: `680 => 620`
		* Production time: `50s => 60s`
	* Baserunner:
		* Hitpoints: `2200 => 1700`
		* Smoke wall ability cooldown: `70s => 55s`
		* Passive regen ability:
			* Enabled: `No => Yes`
			* No-damage activation delay: `10s`
			* Regeneration amount: `20`
			* Time between regeneration ticks: `1s`
	* Siege cruiser:
		* Reload: `2.5s => 4.5s`
		* Number of bursts: `2 => 3`
		* Area of effect: `240 => 270`
		* Barrage:
			* Damage: `250 => 240`
			* Cooldown: `100s => 140s`

## 2020-03-10
* Coalition/Soban:
	* Carrier movement attributes:
		* Turn radius: `150 => 120`
		* Acceleration time: `2s => 1.5s`
		* Braking time: `2s => 1.5s`
	* Railgun tech cost: `300CU 165RU => 300CU 125RU`
	* Support cruiser cost: `500CU 50RU => 450CU 50RU`
	* Probe:
		* Sensors radius: `1200 => 1250`
		* Cost: `150CU => 100CU`
	* LAV (DPS: `38.6 => 41.2`):
		* Max speed: `110 => 120`
		* Speed boost ability:
			* Speed bonus: `60% => 45%`
			* Turn radius increase: `50% => 35%`
		* Number of bursts: `2 => 3`
		* Medium range accuracy: `85% => 82%`
		* Long range accuracy: `62% => 59%`
	* AAV cost: `260CU 20RU => 250CU 20RU`
* Coalition:
	* Baserunner turret cooldown: `60s => 75s`
* Soban:
	* ALM target prioritization distance weight: `-0.1 => 0.1`
* Gaalsien/Khaaneph:
	* Heavy railgun cost: `350CU 100RU => 350CU 110RU`
	* Assault railgun:
		* Armor: `3 => 5`
		* Sensors radius: `1150 => 1250`
		* Contact radius: `1250 => 1350`
		* Range: `1150 => 1250`
		* Accuracy: `16%/15%/14% => 26%/25%/23%`
	* Production cruiser:
		* Vision radius: `1200 => 1350`
		* Contact radius: `1350 => 1450`

## 2020-03-11
* Coalition/Soban:
	* AAV:
		* Damage: `16 => 18`
		* Cost: `250CU 20RU => 240CU 20RU`
* Gaalsien/Khaaneph:
	* Assault ship:
		* Hitpoints: `960 => 860`
		* Area of effect: `140 => 120`
	* Assault railgun:
		* Accuracy: `26%/25%/23% => 26%/20%/18%`
		* Hitpoints: `750 => 650`

## 2020-03-14
* General:
	* Carrier power upgrades:
		* Fixed an issue where level 2 and up upgrades weren't granting hitpoints
		* Hitpoints granted per power level: `300 => 200`
	* Strike craft damage upgrades:
		* Damage increase per upgrade `2 => 1`
		* CU cost: `400 => 300`
* Coalition/Soban:
	* LAV (DPS: `41.2 => 38.6`):
		* Number of bursts: `3 => 2`
		* Medium range accuracy: `82% => 85%`
	* AAV:
		* Hitpoints: `890 => 940`
		* Damage: `18 => 17`
	* Heavy railgun wind-up: `2s => 1.6s`
* Coalition:
	* Carrier:
		* Fixed PD rate of fire display not matching real value
		* PD weapon damage: `18 => 20`
		* Penetrating weapon damage: `45 => 50`
		* Range systems power shunt:
			* Fixed an issue where carrier missile systems had 350 more range than intended at power level 1 and up
			* Level 0: `650 => 800`
			* Level 1: `850 => 900`
		* Weapon systems power shunt PD rate of fire bonus:
			* Level 1: `25% => 20%`
			* Level 2: `50% => 35%`
			* Level 3: `75% => 55%`
			* Level 4: `115% => 80%`
	* Turret:
		* Damage: `55 => 52`
		* Cooldown: `75s => 80s`
	* Heavy railgun reload: `1.4s => 1.6s`
* Soban:
	* Heavy railgun:
		* Cooldown: `1.2s => 1.3s`
		* Reload: `3.2s => 3.3s`
* Gaalsien/Khaaneph:
	* Production cruiser AA weapon short range accuracy: `70% => 60%` 
	* Heavy railgun ranged calibration upgrade cost: `150CU 150RU => 200CU 200RU`
* Gaalsien:
	* Carrier:
		* PD weapon damage: `18 => 20`
		* Penetrating PD weapon damage: `45 => 50`
		* Rate of fire: `9 => 10`
		* Range systems power shunt:
			* Fixed an issue where carrier missile systems had 350 more range than intended at power level 1 and up
			* Level 0: `650 => 800`
			* Level 1: `850 => 900`
		* Weapon systems power shunt PD rate of fire bonus:
			* Level 1: `25% => 20%`
			* Level 2: `45% => 35%`
			* Level 3: `65% => 50%`
			* Level 4: `90% => 70%`
	* Siege cruiser barrage damage: `170 => 150`
* Khaaneph:
	* Carrier:
		* PD weapon damage: `18 => 20`
		* Penetrating PD weapon damage: `45 => 50`
		* Rate of fire: `8 => 10`
		* Weapon systems power shunt PD rate of fire bonus:
			* Level 1: `50% => 25%`
			* Level 2: `100% => 40%`
			* Level 3: `150% => 65%`
			* Level 4: `200% => 100%`
	* Baserunner smoke cooldown: `55s => 40s`

## 2020-03-15
* Coalition/Soban:
	* LAV:
		* Cooldown: `0.4s => 0.65s` (Pure DPS: `38.6 => 36`)
		* Long range accuracy: `59 => 61` (DPS: `22.32 => 21.96`)
	* AAV:
		* Range: `900 => 950`
		* Slow effect: `35% => 25%`

## 2020-03-21
* Coalition/Soban:
	* Support cruiser armor: `7 => 6`

## 2020-03-28
* Coalition/Soban:
	* AAV:
		* Range: `950 => 1000`
		* Area of effect: `0 => 45` (Linear falloff)
* Coalition:
	* Turret
		* Cost: `250CU => 300CU`
		* Damage: `52 => 45`
		* Number of bursts: `16 => 18`
		* Range: `1400 => 1450`
	* Battlecruiser range: `1400 => 1350`

## 2020-04-05
* General:
	* Demo pack damage: `220 => 200`
* Coalition/Soban:
	* Turret:
		* Recharge: `80s => 90s`
		* Armor: `2 => 1`
		* Hitpoints: `700 => 720`
		* Damage: `45 => 50`
		* Packets: `1 => 2`
		* Number of bursts: `18 => 15`
		* AOE: `105 => 75`
	* Missile battery mortar damage packets: `35 => 30`
	* Support cruiser repair rate: `9 => 8`
* Coalition:
	* Battlecruiser damage: `200 => 220`
* Gaalsien/Khaaneph:
	* Assault railgun:
		* Armor: `5 => 4`
		* Damage: `55 => 52`
		* Range: `1250 => 1200`
	* EMP shell:
		* Stun duration: `2.2s => 2.5s`
		* Area of effect: `135 => 145`
		* Range: `1250 => 1300`
	* Missile ship direct fire barrage:
		* Damage: `170 => 160`
		* Area of effect: `160 => 150`
* Khaaneph:
	* Siege cruiser production time: `60s => 55s`

## 2020-04-06
* Coalition/Soban:
	* Missile battery priority as target: `reduced`
* Coalition:
	* Battlecruiser:
		* Cost: `550CU 250RU => 600CU 280RU`
		* Production time: `55s => 50s`
		* Hitpoints: `3500 => 3650`
* Soban
	* Battlecruiser:
		* Cost: `520CU 280RU => 570CU 280RU`
		* Production time: `60s => 50s`
* Gaalsien/Khaaneph:
	* Missile ship priority as target: `reduced`
* Gaalsien:
	* Carrier:
		* Reestablish systems hitpoints per tick:
			* Level 1: `45 => 35`
			* Level 2: `60 => 50`
			* Level 3: `75 => 65`
			* Level 4: `90 => 80`
* Khaaneph:
	* Carrier:
		* Hitpoints: `8700 => 9500`
		* Armor: `25 => 15`
		* Base speed: `30 => 45`
		* Sensor radius: `1000 => 1200`
		* Contact radius: `1000 => 1350`
		* Cruise missile:
			* Damage: `500 => 650`
			* AOE: `150 => 120`
			* Damage against carriers: `100% => 70%`
			* Base missile warmup time: `6s => 10s`
		* Mobility support:
			* Speed bonuses:
				* Level 1: `3 => 8%`
				* Level 2: `6 => 11%`
				* Level 3: `10 => 14%`
				* Level 4: `15 => 17%`
				* Level 5: `20 => 20%`
			* Vision bonuses:
				* Level 1: `70 => 100`
				* Level 2: `110 => 150`
				* Level 3: `150 => 200`
				* Level 4: `200 => 250`
				* Level 5: `250 => 300`
		* Reestablish systems hitpoints per tick:
			* Level 1: `45 => 35`
			* Level 2: `60 => 50`
			* Level 3: `75 => 65`
			* Level 4: `90 => 80`
	* Siege cruiser:
		* Cost: `650CU 200RU => 620CU 250RU`
		* Tech research time: `90s => 95s`
		* Hitpoints: `3050 => 3200`
		* Sensors radius: `1000 => 1150`
		* Contact radius: `1250 => 1300`
		* Production time: `55s => 45s`

## 2020-04-09
* Coalition:
	* Carrier:
		* Turn radius: `120 => 65`
		* Acceleration time: `1.5s => 1.1s`
		* Braking time: `1.5s => 1.1s`
* Soban:
	* Carrier:
		* Turn radius: `120 => 65`
		* Acceleration time: `1.5s => 1.1s`
		* Braking time: `1.5s => 1.1s`
		* Ranges:
			* Level 0: `850 => 1000`
			* Level 1: `1100 => 1250`
			* Level 2: `1350 => 1450`
			* Level 3: `1550 => 1650`
			* Level 4: `1750 => 1900`
			* Level 5: `1950 => 2150`

## 2020-04-10
* Coalition/Soban:
	* Support cruiser weapon ROF: `10 => 8`

## 2020-04-17 (Jaraci Cup #5)
* Soban:
	* LAV boost ability - fixed an issue where the ability wasn't modified like the Coalition variant.

## 2020-04-30
* Coalition/Soban:
	* Support cruiser:
		* Armor: `6 => 5`
		* G2All weapon burst: `1.0-1.2s => 0.8-0.9s` (DPS: `48.3 => 38.1`)
		* G2A weapon (DPS: `43.2 => 38.1`):
			* Damage: `175 => 50`
			* Burst count: `1 => 4`
			* Burst duration: `1s => 0.3s`
			* Cooldown: `0.7s => 0s`
			* Reload: `3s => 4s`
			* Area of effect: `80 => 40`
			* Range: `1350 => 1200`
	* LAV (DPS: `36 => 36.1`, vs 9 armor: `9 => 15.8`):
		* Hitpoints: `500 => 450`
		* Armor: `1 => 2`
		* Damage: `12 => 16`
		* ROF: `6 => 5`
		* Burst: `0.95-1.05s => 0.95-1s`
		* Damage against air: `50% => 70%`
		* Accuracy against medium, large, xlarge: `100% => 130%`
	* AAV tech cost: `400CU 65RU => 400CU 75RU`
	* Railgun base damage: `120 => 130`
	* Strike fighter damage: `110 => 120`
	* Battlecruiser:
		* Cost: `600/580CU 280RU => 650CU 280RU`
		* Production time: `50s => 65s`
* Coalition:
	* Carrier:
		* Hitpoints: `9000 => 8800`
		* Reactive armor power shunt:
			* Level 3 armor: `75 => 65`
			* Level 4/5 armor: `100 => 85`
	* Baserunner turret cooldown: `90s => 110s`
	* Battlecruiser (DPS: `97.2 => 99.4`):
		* Now uses same target prioritization as railguns.
		* Hitpoints: `3650 => 3300`
		* Armor: `15 => 25`
		* Range: `1350 => 1250`
		* Reload time: `5s => 4.8s`
		* Max movement speed: `54 => 62`
* Soban:
	* ALM:
		* Damage: `120 => 110`
		* AOE: `90 => 80`
	* Battlecruiser (DPS: `59.3 => 42.4`):
		* Hitpoints: `2900 => 2700`
		* Damage: `320 => 280`
		* Wind-up: `0.6s => 2.2s`
		* Cooldown: `3s => 1s`
		* Reload: `5s => 8s`
		* Range: `1900 => 1650`
* Gaalsien/Khaaneph:
	* Assault ship:
		* Cost: `280CU 30RU => 320CU 35RU`
		* Production time: `18s => 17s`
		* Hitpoints: `860 => 950`
		* Self regeneration per tick: `20 => 15`
		* Area of effect falloff: `Linear => Quadratic`
	* Assault railgun (DPS: `57.2 => 57.3`)
		* Damage: `52 => 43`
		* Number of burst: `4 => 5`
		* Self regeneration per tick: `13 => 7`
		* Range: `1200 => 1130`
* Khaaneph:
	* Carrier:
		* Cruise missile:
			* Packets: `1 => 2`
			* Recharge:
				* Level 1/2: `10s => 9s`
				* Level 3: `9s => 8s`
				* Level 4: `8s => 7s`
				* Level 5: `7s => 6s`
		* Speed bonus status effects:
			* Level 2: `11% => 12%`
			* Level 3: `14% => 16%`
			* Level 4: `17% => 20%`
			* Level 5: `20% => 25%`
	* Blast drone production time: `60s => 70s`

## 2020-05-01
* Coalition/Soban:
	* AAV (DPS: `91 => 91.2`, vs 9 armor: `43 => 39.9`):
		* Damage: `17 => 16`
		* ROF: `13 => 14`
		* Burst: `0.5-0.55s => 0.48-0.53s`
	* Support cruiser:
		* Repair rate: `8 => 7`
		* G2All weapon modifier vs air: `130% => 100%`
* Soban:
	* Battlecruiser:
		* Tech research time: `95s => 110s` (to match C)
		* Cooldown: `1s => 1.2s`
		* Reload: `8s => 8.5s`

## 2020-05-06
* Coalition/Soban:
	* LAV (DPS: `36.1 => 38.2`):
		* Hitpoints: `450 => 420`
		* Cooldown: `0.65s => 0.45s`
	* AAV:
		* Tech research time: `55s => 60s`
		* Damage: `16 => 15`
		* Burst: `0.48-0.53s => 0.5-0.55s`
		* Area of effect: `45 => 0`
	* Gunship damage: `40 => 36`
	* Heavy railgun damage: `130 => 155`
	* Bomber:
		* Hitpoints: `1500 => 1350`
		* Armor: `12 => 20`
		* Max speed: `370 => 390`
		* Turn radius: `350 => 310`
* Coalition:
	* Battlecruiser hitpoints: `3200 => 2700`
	* Railgun reload: `1.6s => 2.0s` (DPS: `31 => 33.7`)
* Soban:
	* Railgun reload: `3.3s => 4.25s` (DPS: `31.7 => 33.9`)
* Gaalsien/Khaaneph:
	* Sandskimmer (DPS: `42.4 => 45`):
		* Damage: `12 => 11`
		* ROF: `6 => 7`
		* Cooldown: `0.3s => 0.35s`
	* Assault ship:
		* Cost: `320CU 35RU => 300CU 35RU`
		* Hitpoints: `950 => 1000`
		* Damage: `30 => 32`
	* Assault railgun:
		* Production time: `16s => 17s`
		* Damage: `43 => 42`
	* Heavy railgun (DPS: `59.6 => 64.2`):
		* Damage: `155 => 180`
		* Reload: `0s => 0.2s`

## 2020-05-10
* General:
	* Carrier hitpoints granted per power level: `200 => 150`
	* Salvager target priority: `5 => 2`
* Coalition/Soban:
	* Baserunner probe max movement speed: `250 => 200`
	* LAV hitpoints: `420 => 450`
* Coalition:
	* Carrier:
		* PD ROF: `8 => 6`
		* Level 3 reactive armor shunt total armor: `65 => 60` (consistency fix)
	* Baserunner turret damage: `50 => 54`
	* Battlecruiser damage: `220 => 200`
* Soban:
	* Carrier hitpoints: `8500 => 8600`
* Gaalsien/Khaaneph:
	* Heavy railgun:
		* Reload: `0.2s => 0s`
		* EMP:
			* Damage: `70 => 110`
			* Cooldown: `100s => 90s`
* Gaalsien:
	* Carrier:
		* Hitpoints: `8000 => 8100`
		* PD ROF: `10 => 8`
	* Scanner deployment range: `2500 => 2650`
* Khaaneph:
	* Carrier hitpoints: `9500 => 9600`

## 2020-05-11
* Coalition:
	* Carrier:
		* Hitpoints: `8800 => 9000`
		* Armor power shunt:
			* Level 2: `40 => 35`
			* Level 3: `60 => 45`
			* Level 4/5: `85 => 60`
	* Battlecruiser armor: `25 => 15`
* Soban:
	* Carrier:
		* Hitpoints: `8600 => 8800`
		* Armor power shunt:
			* Level 1: `25 => 20`
			* Level 2: `35 => 25`
			* Level 3: `45 => 35`
			* Level 4/5: `60 => 50`
* Gaalsien/Khaaneph:
	* Assault railgun:
		* Hitpoints: `650 => 600`
		* Range: `1130 => 1100`
		* Accuracy: `26%/20%/18% => 20%/16%/14%`
		* Max speed: `90 => 85`
		* Acceleration time: `0.93s => 1.5s`
		* Braking time: `0.93s => 1.2s`
		* Dart maneuver:
			* Fixed an issue where ability duration wasn't increased as intended (Duration: `2s => 3s`)
			* Cooldown: `60s => 30s`
	* Missile ship direct fire barrage damage: `160 => 140`
* Khaaneph:
	* Carrier cruise missile:
		* Damage: `650 => 670`
		* Packets: `2 => 5`
		* Area of effect: `120 => 140`

## 2020-05-22
* Coalition/Soban:
	* Level 2 production cost: `500CU 40RU => 600CU 80RU`
	* Probe:
		* Hitpoints: `170 => 120`
		* Contact radius: `1100 => 1450`
	* AAV:
		* Cost: `240CU 20RU => 250CU 20RU`
		* Suppression slow effect: `25% => 35%`
	* Artillery cruiser precision barrage cooldown: `30s => 60s`
* Coalition:
	* Carrier cruise missile damage: `2400 => 2300`
* Gaalsien/Khaaneph:
	* Assault ship damage: `32 => 30`
	* Production cruiser
		* Hitpoints: `3900 => 3500`
		* Armor: `5 => 6`
		* Sensors radius: `1350 => 1450`
		* Contact radius: `1450 => 1600`
* Gaalsien:
	* Carrier super-sonic missile damage: `250 => 240`
	* Scanner deployment range: `2650 => 2550`
	* Siege cruiser barrage cooldown: `120s => 100s`
* Khaaneph:
	* Blast drone:
		* Cost: `100CU => 150CU`
		* Hitpoints: `500 => 540`
		* Braking time: `0.75s => 0.1s`

## 2020-05-23
* Coalition/Soban:
	* Artillery cruiser autofire:
		* Packets: `2 => 1`
		* Modifiers:
			* vs carrier: `100% => 60%`
			* vs small: `100% => 50%`
* Gaalsien:
	* Siege cruiser autofire:
		* Damage: `80 => 120`
		* Packets: `2 => 1`

## 2020-05-25 (Jaraci Cup #6)
* Coalition/Soban:
	* Assault cruiser:
		* Ability cooldowns: `50s => 40s`
		* Overdrive armor bonus: `25% => 50%` (`15 => 18`)
* Gaalsien/Khaaneph:
	* Assault ship hitpoints: `1000 => 960`
* Gaalsien:
	* Siege cruiser:
		* Tech cost: `450CU 150RU => 250CU 150RU`
		* Cost: `300CU 120RU => 300CU 150RU`
		* Hitpoints: `1600 => 1400`
		* Movement speed: `65 => 60`
		* Barrage (damage: `2700 => 2160`):
			* Ability cooldown: `100s => 90s`
			* Damage: `150 => 120`
			* Packets: `2 => 1`
			* Rate of fire: `4 => 5`
			* Number of bursts: `3 => 2`
			* Burst duration: `1.7s => 1.8s`
			* Cooldown: `1.6s => 1.4s`

## 2020-07-08
* Coalition/Soban:
	* Gun turret target priority: `reduced`
	* AA turret cost: `200CU => 250CU`
	* AAV armor: `9 => 8`
	* Missile battery reload time: `3s => 2.5s`
	* Support cruiser missile AA damage: `50 => 55`
	* Gunship damage: `36 => 37`
	* Tactical bomber:
		* Damage: `1500 => 1600`
		* AOE: `220 => 200`
* Coalition:
	* Battlecruiser:
		* Hitpoints: `2700 => 3000`
		* Range: `1250 => 1200`
* Soban:
	* Battlecruiser hitpoints: `2700 => 2900`
* Gaalsien/Khaaneph:
	* Assault ship:
		* AOE falloff: `Quadratic => Linear`
		* Armor upgrade cost:
			* Level 2: `200CU 150RU => 200CU 200RU`
			* Level 3: `250CU 200RU => 250CU 250RU`
	* Heavy railgun:
		* Hitpoints: `750 => 850`
		* Armor: `3 => 0`
		* Reload: `0 => 0.4s` (total firing sequence time: `2.6s => 3.0s`)
		* EMP round ability range: `1300 => 1350`
	* Interceptor:
		* Armor: `3 => 2`
		* Damage: `110 => 100`
		* AOE: `70 => 62`
	* Honourguard cruiser cost: `550CU 270RU => 550CU 250RU`
* Gaalsien:
	* Siege cruiser:
		* Tech research cost: `250CU 150RU => 500CU 200RU`
		* Cost: `300CU 150RU => 450CU 270RU`
		* Production time: `30s => 50s`
		* Population cost: `5 => 6`
		* Hitpoints: `1400 => 2000`
		* Sensors range: `1000 => 1400`
		* Contact range: `1250 => 1550`
		* Movement speed: `60 => 52`
		* Barrage:
			* Recharge: `90s => 110s`
			* Base range: `2000 => 2350`
			* Damage: `120 => 220`
			* Damage packets: `1 => 2`
			* AOE: `100 => 200`
			* Rate of fire: `5 => 1`
			* Burst: `1.8s => 2.05s`
			* Number of bursts: `2 => 4`
			* Cooldown: `1.4 => 3.25s`
			* Damage against small: `50% => 25%`
			* Damage against carrier: `60% => 50%`
		* Autofire weapon:
			* Damage: `120 => 200`
			* Damage packets: `1 => 2`
		* PD weapon damage: `3 => 14` (DPS: `6.7 => 31.5`)
		* EMP weapon:
			* Damage: `300 => 450`
			* Affected by high ground: `Yes => No`
* Khaaneph:
	* Carrier PD:
		* Range: `1050 => 950`
		* Rate of fire: `8 => 7`
		* Fixed incorrect rate of fire tooltip.
	* Siege Cruiser:
		* Hitpoints: `3200 => 2800`
		* Sensors radius: `1150 => 1100`
		* Contact radius: `1300 => 1200`
		* Barrage weapon:
			* AOE Falloff: `Quadratic => Linear`
			* Recharge time: `140s => 100s`
			* Range: `2250 => 2000`
		* Direct fire weapon:
			* Damage: `130 => 120`
			* AOE: `280 => 250` (Quadratic falloff)
			* Range: `1000 => 1150`
		* EMP weapon affected by high ground: `Yes => No`

## 2020-07-12
* Coalition/Soban:
	* Missile battery mortar packets: `30 => 35`
	* Artillery cruiser:
		* Cost: `450CU 200RU => 500CU 200RU`
		* Armor: `6 => 2`
		* Population cost: `4 => 5`
* Soban:
	* Targeting jammer population cost: `1 => 0`
* Gaalsien/Khaaneph:
	* Sandskimmer hitpoints: `540 => 550`
	* Assault railgun:
		* Reload time: `2.6s => 2s`
		* Dart maneuver:
			* Duration: `2s => 2.5s`
			* Recharge time: `30s => 25s`
* Gaalsien:
	* Siege cruiser:
		* Cost: `450CU 270RU => 400CU 230RU`
		* Production time: `50s => 55s`

## 2020-07-18
* Gaalsien:
	* Carrier Speed power shunt:
		* Level 0: `15 => 35`
		* Level 1: `35 => 50`
		* Level 2: `55 => 65`
		* Level 3: `70 => 80`
		* Level 4: `85 => 95`
		* Level 5: `105 => 110`

## 2020-07-26 (Jaraci Cup #7)
* Coalition/Soban:
	* LAV (DPS: `38.2 => 38.6`, Long range DPS: `23.3 => 25`):
		* Damage: `16 => 14`
		* Cooldown: `0.45s => 0.3s`
		* Burst: `0.9-0.95s => 0.95-1.15s`
		* Accuracy distant: `61% => 65%`
	* AAV:
		* Hitpoints: `930 => 980`
		* Armor: `8 => 6`
	* Missile battery cost: `300CU 90RU => 300CU 85RU`
* Coalition:
	* Gun turret (DPS: `117.2 => 127.9`):
		* Damage: `54 => 52`
		* Burst duration: `0.334s => 0.28s` (This is a buff)
* Gaalsien/Khaaneph:
	* Sandskimmer max speed: `130 => 140` (Raiding: `150 => 160`)
	* Bomber (total damage per sortie `3200 => 2700`):
		* Damage: `800 => 900`
		* Hold upgrade:
			* Cost: `400CU 200RU => 400CU 150RU`
			* Inventory size: `4 => 3`

## 2020-09-23
* Coalition/Soban:
	* Probe contact radius: `1450 => 1550`
	* LAV weapon cooldown: `0.3s => 0.4s` (DPS: `38.6 => 37.5`)
	* AAV:
		* Cost: `250CU 20RU => 260CU 20RU`
		* AOE radius: `0 => 30`
		* AOE falloff type: `None => Linear`
		* Suppression:
			* Slow effect: `35% => 42%`
			* Duration: `2s => 2.65s`
	* Assault cruiser ability cooldown: `40s => 30s`
	* Support cruiser AA:
		* Damage: `55 => 70`
		* AOE: `40 => 60`
		* Reload: `4s => 5s`
* Soban:
	* ALM:
		* Damage: `110 => 150`
		* Packets: `2 => 3`
		* AOE: `80 => 86`
	* Battlecruiser:
		* Research cost: `550CU 300RU => 450CU 200RU`
		* Damage: `280 => 300`
* Gaalsien/Khaaneph:
	* Production cruiser:
		* Refinery mode cost: `600CU 80RU => 550CU 80RU`
		* Cost: `600CU 60RU => 650CU 60RU`
		* Ranges: `650/950/1250 => 900/1200/1380`
		* Accuracies: `60/55/40 => 55/45/25`
	* Sandskimmer:
		* Tech cost: `300CU => 350CU`
		* Research time: `30s => 35s`
		* Production time: `11s => 10s`
		* Regeneration activation delay: `5.5s => 10s`
	* Assault railgun (DPS: `69.6 => 66.7`):
		* Damage: `42 => 48`
		* Burst duration: `0.11s => 0.09s`
		* Number of bursts: `5 => 6`
		* Reload: `2s => 3s`
		* Dart maneuver:
			* Cost: `100CU 70RU => 150CU 30RU`
			* Duration: `2.5s => 3s`
	* Heavy railgun reload: `0.4s => 0.6s`
	* Assault ship:
		* Damage: `30 => 28`
		* AOE falloff type: `Linear => Quadratic`
	* Interceptor AOE: `62 => 67`
	* Honourguard cruiser:
		* Tech cost: `500CU 350RU => 500CU 280RU`
		* Damage: `500 => 450`
		* AOE: `220 => 250`
	* Siege cruiser range upgrade research time: `50s => 70s`
* Gaalsien:
	* Baserunner heal ability cooldown: `80s => 75s`
	* Siege cruiser:
		* Research cost: `500CU 200RU => 400CU 150RU`
		* Production time: `50s => 45s`
		* Cost: `400CU 230RU => 400CU 180RU`
		* Armor: `3 => 9`
		* Speed: `52 => 66`
		* Acceleration time: `1.25s => 3s`
		* Barrage:
			* Ability cooldown: `110s => 45s`
			* Ranges: `1000/1500/2350 => 800/1200/1550`
			* Min range: `900 => 450`
			* Damage: `220 => 140`
			* Rate of fire: `1 => 3`
			* AOE: `200 => 120`
			* Burst duration: `2.05s => 1.75s`
			* Number of bursts: `4 => 2`
			* Cooldown between bursts: `3.25s => 2.5s`
			* Range upgrade ranges: `900/1850/2500 => 800/1300/1800`
		* Autofire:
			* Reload: `10s => 9s`
			* Damage: `200 => 140`
			* Number of bursts: `1 => 2`
* Khaaneph:
	* Siege cruiser tech research time: `95s => 90s`

## 2020-09-25
* Coalition:
	* Turret:
		* Damage: `52 => 55`
		* AOE: `75 => 80`
* Gaalsien:
	* Siege cruiser:
		* Autofire damage: `140 => 160`
		* Barrage:
			* Damage: `140 => 180`
			* ROF: `3 => 5`
			* Burst duration: `1.75s => 1.35s`
			* AOE: `120 => 95`
			* Max range: `1550 => 1650`
			* Range upgrade max range: `1800 => 1900`

## 2020-10-07 (Jaraci Cup #8)
* Coalition/Soban:
	* LAV armor upgrade CU cost: `300 => 350`
	* Tactical bomber turn radius: `310 => 250`
* Soban:
	* Battlecruiser damage: `300 => 340`
* Gaalsien/Khaaneph:
	* Missile ship direct missile barrage cooldown: `90s => 80s`
	* Heavy Railgun:
		* Hitpoints: `850 => 820`
		* Ranged calibration research cost: `200CU 200RU => 200CU 230RU`
* Gaalsien:
	* Siege cruiser barrage:
		* Cooldown time: `45s => 40s`
		* Range: `1650 => 1750`
		* Range upgrade range: `1900 => 2000`
* Khaaneph:
	* Siege cruiser barrage falloff: `Linear => Quadratic`

## 2020-10-18
*Not yet reflected in the main changelog.*
* General:
	* Baserunner priority as target: `reduced`
* Coalition/Soban:
	* AA turret:
		* Cost: `250CU => 300CU`
		* Hitpoints: `1100 => 900`

## 2020-11-21 (Jaraci Cup #9)
*Not yet reflected in the main changelog.*
* Coalition/Soban:
	* LAV armor: `2 => 1`
	* AAV turret rotation: `120 => 190`
* Gaalsien/Khaaneph:
	* Sandskimmer hitpoints: `550 => 490`
	* Production cruiser ROF: `12 => 11`

## 2020-12-18
*Not yet reflected in the main changelog.*
* General:
	* Carrier PDs:
		* Damage: `20 => 30`
		* Penetrating rounds damage: `50 => 75`
		* Fixed broken ROF descriptions
* Coalition/Soban:
	* LAV distant range accuracy: `65% => 63%`
	* AA turret affected by high ground: `Yes => No`
	* AAV:
		* Tech cost: `400CU 75RU => 350CU 75RU`
		* AOE: `15 => 0`
		* Hitpoints: `980 => 920`
		* Suppression slow effect: `42% => 55%`
	* Railgun:
		* RU cost: `80 => 85`
		* Max movement speed: `70 => 73` 
		* Accuracy: `7%/6.5%/6% => 40%/100%/65%`
		* Damage vs small: `100% => 60%`
	* Fighter and gunship:
		* Tech cost: `450CU 200RU => 400CU 200RU`
		* Strike fighter:
			* Range: `1250 => 1200` (vanilla value)
			* Production time: `26s => 27s`
	* Support cruiser PD weapon:
		* Damage: `15 => 16`
		* ROF: `8 => 6`
		* Tracer speed: `1000 => 1300` (visuals)
* Coalition:
	* Carrier:
		* Hitpoints: `9000 => 9200`
		* PD base ROF: `6 => 2`
		* Cruise missile damage against large targets: `170% => 160%`
	* Railgun:
		* Reload: `2s => 1.8s`
		* Accuracy vs small: `200% => 100%`
		* Accuracy vs ground small support: `200% => 100%`
* Soban:
	* Railgun:
		* Cooldown: `1.3s => 1.25s`
		* Reload: `4.25s => 4.0s`
		* Accuracy vs small: `500% => 100%`
* Gaalsien/Khaaneph:
	* Salvager armor: `3 => 5`
	* Assault ship:
		* Damage: `28 => 29`
		* AOE: `120 => 130`
	* Heavy railgun:
		* Cost: `350CU 110RU => 350CU 105RU`
		* Production time: `18s => 24s`
		* Max movement speed: `57 => 61`
		* Accuracy: `7%/6.5%/6% => 40%/100%/65%`
		* Damage vs small: `100% => 60%`
		* Accuracy vs small: `200% => 100%`
		* Accuracy vs ground small support: `200% => 100%`
	* Assault railgun:
		* Max speed: `85 => 89`
		* Armor: `4 => 5`
	* Interceptor weapon leads target: `No => Yes`
	* Honourguard cruiser AA upgrade cost: `300CU 200RU => 300CU 300RU`
* Gaalsien:
	* Carrier PD base ROF: `8 => 3`
* Khaaneph:
	* Carrier:
		* PD base ROF: `7 => 3`
		* Cruise Missile systems power shunt missile reload time:
			* Level 2: `9s => 8s`
			* Level 3: `8s => 7s`
			* Level 4: `7s => 6s`
			* Level 5: `6s => 5s` 
	* Blast Drone armor: `0 => 1`
	* Siege cruiser:
		* Tech cost: `500CU 250RU => 600CU 250RU`
		* Cost: `620CU 250RU => 700CU 250RU`
		* Main weapon AOE: `250 => 230`

## 2020-12-19
*Not yet reflected in the main changelog.*
* Coalition/Soban:
	* Carrier movement dynamics:
		* Turn radius: `65 => 130`
		* Max ease into turn time: `5s => 1s`
	* Support cruiser movement dynamics max ease into turn time: `3s => 0.8s`
	* LAV accuracy: `90%/85%/63% => 92%/88%/65%`
	* Level 2 production upgrade cost: `400CU 40RU => 300CU 40RU`
* Gaalsien/Khaaneph:
	* Production cruiser:
		* Cost: `650CU 60RU => 700CU 100RU`
		* Production time: `60s => 50s`
	* Heavy railgun:
		* Cost: `350CU 105RU => 350CU 110RU`
		* Ranged calibration upgrade cost: `200CU 230RU => 200CU 300RU`
		* EMP round upgrade cost: `300CU 100RU => 400CU 100RU`

## 2020-12-21
*Not yet reflected in the main changelog.*
* General:
	* Strike craft armor upgrades hitpoints granted per upgrade: `30 => 20`

## 2021-01-05
*Not yet reflected in the main changelog.*
* Coalition/Soban:
	* Baserunner max ease into turn time: `1s => 0.6s`
	* LAV accuracy: `92%/88%/65% => 90%/85%/63%`

## 2021-01-06
*Not yet reflected in the main changelog.*
* General:
	* Increased all railgun priority as target
* Coalition/Soban:
	* Carrier speed: `50 => 45`
	* Logistics module:
		* Armor: `5 => 3`
		* Cost: `250CU => 270CU`
	* LAV:
		* Boost cooldown: `30s => 40s`
		* Accuracy modifier against Medium: `130% => 115%`
	* AAV (DPS: `74.9/66.1/57.3 => 75.2/65.8/57.3`):
		* Damage: `15 => 16`
		* Weapon accuracy: `85%/75%/65% => 80%/70%/61%`
		* Smoke cooldown: `90s => 80s`
	* Railgun:
		* Tech cost: `350CU 125RU => 300CU 100RU`
		* CU cost: `240 => 250`
	* Missile battery mortar packets: `35 => 30`
	* Gunship damage: `37 => 39`
* Coalition:
	* Logistics module:
		* Hitpoints: `900 => 1100` (matches Soban ALM)
		* Sensors radius: `1200 => 1400`
		* Contact radius: `1225 => 1550`
	* Carrier hitpoints: `9200 => 9000`
* Gaalsien/Khaaneph:
	* Carrier PD rate of fire: `3 => 4`
	* Production cruiser cost: `700CU 100RU => 650CU 60RU`
	* Sandskimmer:
		* Hitpoints: `490 => 510`
		* Sensors radius: `1150 => 1200`
		* Contact radius: `1250 => 1300`
		* Regeneration:
			* Start time threshold: `10s => 15s`
			* Health recovered per tick: `20 => 12`
	* Assault ship:
		* Armor: `5 => 6`
		* Regeneration:
			* Start time threshold: `10s => 15s`
			* Health recovered per tick: `15 => 12`
	* Dart maneuver research time: `30s => 20s`
	* Heavy railgun ranged calibration:
		* Research time: `45s => 55s`
		* Movement speed penalty: `50% => 65%`
		* Range bonus: `370 => 330`

## 2021-01-06 (2)
*Not yet reflected in the main changelog.*
* Coalition/Soban:
	* Level 1 production upgrade cost: `300CU 40RU => 350CU 40RU`

## 2021-01-09
*Not yet reflected in the main changelog.*
* Coalition/Soban:
	* AAV armor: `6 => 7`
* Gaalsien/Khaaneph:
	* Assault railgun:
		* Hitpoints: `600 => 650`
		* Armor: `5 => 6`
		* Reload: `3s => 4s`
	* Honourguard cruiser reload: `4.5s => 5s`

## 2021-01-30
*Not yet reflected in the main changelog.*
* General:
	* Added updated carrier power shunt descriptions (was commented out due to a bug in Subsystem that recently got fixed)
	* Carrier weapon systems missile damage: `200 => 175`
	* Strike craft armor upgrade RU cost:
		* Level 1: `75RU => 100RU`
		* Level 2: `150RU => 175RU`
* Coalition/Soban:
	* Carrier speed: `45 => 47`
	* Railgun hitpoints: `750 => 820`
	* Artillery cruiser standard barrage:
		* Damage: `200 => 240`
		* AOE: `100 => 92`
* Coalition:
	* Carrier
		* Hitpoints: `9000 => 8700`
		* PD ROF: `2 => 3`
		* Armor power shunt:
			* Level 0: `25 => 15`
			* Level 1: `30 => 20`
			* Level 2: `35 => 25`
			* Level 3: `45 => 35`
			* Level 4: `60 => 50`
	* Turret hitpoints: `720 => 850`
	* Battlecruiser damage: `180 => 210`
* Soban:
	* Carrier:
		* Hitpoints: `8800 => 8500`
		* Weapon systems missiles: (Consistency with other carriers fixes)
			* Damage: `128 => 175`
			* Wind-up: `0 => 0.5s`
			* Range: `500 => 700`
		* PD:
			* Reload: `15s => 13s`
			* Cooldown: `10s => 9s`
			* Accuracy & Modifiers: Fixed to match soban railguns.
		* Armor power shunt:
			* Level 0: `15 => 10`
			* Level 1: `20 => 15`
			* Level 2: `25 => 20`
			* Level 3: `35 => 30`
			* Level 4: `50 => 45`
	* Battlecruiser:
		* Hitpoints: `2900 => 2800`
		* Armor: `13 => 14`
		* Damage: `340 => 360`
* Gaalsien/Khaaneph:
	* Carrier PD ROF: `4 => 5`
	* Heavy railgun speed: `61 => 58`
	* Dart maneuver:
		* Tech cost: `150CU 30RU => 50CU 80RU`
		* Cooldown: `25s => 35s`
	* Honourguard cruiser:
		* Production time: `55s => 50s`
		* Damage: `450 => 420`
		* Speed: `55 => 52`
		* Range: `2100 => 1950`
		* Wind-up: `2.5s => 2.2s`
		* Reload: `5s => 5.3s`
* Gaalsien:
	* Siege cruiser:
		* Armor: `9 => 7`
		* Barrage damage: `180 => 210`
		* AOE: `95 => 90`
* Khaaneph:
	* Siege cruiser area of effect: `240 => 230`

## 2021-01-09
*Not yet reflected in the main changelog.*
* Coalition/Soban:
	* AAV hitpoints: `920 => 970`
