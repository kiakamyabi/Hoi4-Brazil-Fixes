# 📈 Brazil Fixes 📉
  
Should work with open beta 1.14.3

Adds a 5th Research Slot for all ideologies, fixed some bugs and tuned some focuses be more interesting for Brazil in the Trials of Allegiance DLC. <br>
  
Democratic Brazil is mostly finished. <br>
You can actually get most of South America in the United States of South America path. <br>
Non-Aligned is about a third finished. <br>
Communist & Fascist is barely touched. <br>

Has no changes to the AI and doesn't add any new focuses, meaning it should be compatible with anything compatible with vanilla. <br>

Feel free to do whatever you want with this code. Some of it should be in the game. Feel free to hire me as well, and maybe give me a million dollars. <br>

## DEMOCRATIC BRAZIL 🗽
 
<details>
  
## Ban The Communist Party 🌹 🏛️ (Focus) [Balance]
```diff
+ Political Power = +100
```
>Buff to make the conservative democratic side more appealing.
 _______ 
## The United States of Brazil  🎖️ 🕵️ (Focus) [Balance]
  ```diff
! From 35 Days to 70.
+ Defense Drift from +0.10 to +0.30
+ Army Morale from +0.05 to +0.10
+ Compliance Growth from +0.05 to +0.20
+ Resistance Target On Our Occupied States +0.10
+ Civilian Intel To Others -10%
+ Resistance Decay +0.20
+ Non-core Manpower +0.05
+ Supply Combat Penalties On Core -0.20
  ```
>Liberal Democratic Brazil gets non-core manpower and high compliance, giving them more long term potential with non-core land.
_______
## Order and Progress 🎖️ 🕵️ (Focus) [Balance]
  ```diff
! From 35 Days to 70.
- Army Core Attack removed. = 0.05
- Army Core Defense removed. = 0.05
+ Recruitment factor from +0.02 to +0.10
+ Resistance Damage to Garrison -0.20
+ Required Garrison -0.20
+ Encryption +1
+ Army Intel to Others -10
+ Enemy Operative Capture Chance +0.20
+ Root Out Resistance Effectiveness +0.50
+ Army Attack +0.10
  ```
>Conservative Democratic Brazil gets more aggressive military bonuses and can deal with resistance easier.
_______
  
## War Bonds 🏭 ⚔️ 🏛️ (Focus) [Bugfix]
#### Replaced all requirements with:
``` diff
+ War support > 0.50
+ Stability > 0.50
```
#### War Bonds (National Spirit):
``` diff
- Consumer Goods Factor from -15% to -10%.
- War support factor removed = +20%
+ Weekly war support = 0.10%.
+ Weekly stability = 0.10%.
```
>Now more interesting because you have to **balance** your war support and stability before you can get it. 
>Bonus less up front and better **long term**.
  
 _______
  
## The International Crisis 🗺️ ⚔️ (Focus) [Bugfix]
```diff
+ Added can Send Volunteers Rule
! Focus now takes 35 days instead of 70. 
```
>Democracies can't send volunteers making this previously useless.
  _______
  
  </details> 
  
_______

## GOOD NEIGHBOR POLICY PATH
#### (DEMOCRATIC BRAZIL 🗽, NON-ALIGNED 'ESTADO NOVO' 🎩 & MONARCHISM 👑)

<details>
  
## Good Neighbor Policy 🌎 💱 (Focus) [Balance, Depth]
#### Requirements:
``` diff
+ Now requires Brazil to not be engaged in any offensive wars with countries in North America, South America, or the Caribbean.
```
#### Now has three outcomes for event:

* Option A will give a **30 Opinion Bonus** & **100 Trade Influence** for **48 months**.
* Option B will give a **10 Opinion Bonus** & **30 Trade Influence** for **24 months**.
* Option C gives **nothing**, the nation **rejects** Brazil. **Status quo**.

#### Other Changes:
``` diff
+ Now event also sent to countries in North America.
+ Opinion bonus is now mutual. Trade Influence added is also mutual.
```
>Reward is far greater with **Trade Influence** gain potential, particularly with the **USA**.
>Now has more depth by checking for ideologies. Actually requires you to be a good neighbor and not be elbow dropping your cousins.
_______
 ## The Washington Accords 🏭 🗺️ 💱 (Focus) [Balance, Depth]
#### Requirements:
``` diff
+ Now requires the major that USA is at war with to not be Democratic or a nation that holds elections.
+ Now requires USA to not be justifying on Brazil.
+ Now requires USA to not have capitulated.
+ Now requires USA must hold elections.
+ Now requires USA to not be fascist.
+ Now requires USA to not be justifying on Brazil.
- No longer requires USA to be Democratic
- Brazil to not be in a faction.
```
#### Other Changes:
```diff
! From 35 Days to 70.
+ Now shows what happens if USA refuses deal in tooltip. Brazil will have -50 opinion of USA.
+ Now any major country at war with the USA will get a -50 negative opinion of Brazil.
+ Now Brazil and USA will get +100 Trade Influence with each other.
+ Now any major country at war with the USA will get -100 Trade Influence with Brazil.
```
#### The Washington Accords (National Spirit):
``` diff
- War support factor removed = +5%
- Democracy drift removed = +0.01
+ Offensive War Stability Factor = +20%
+ Defensive War Stability Factor = +20%
+ Mobilization Speed = +0.30
```
> Now actually **aligns you with the USA**, even if you made your own faction or joined another. Greater rewards (**Trade Influence**) and bonuses that will help you in a **war**, at the expense of alienating yourself from USA's **major enemies**. Can now align with more than just **Democratic USA**; **Communist USA** and I think **Non-Aligned** can be aligned with, as long as **they hold elections**.
_______
 ## No Fascism In South America ⚔️ 🌎 ☠️ (Focus) [Bugfix, Balance]
```diff
+ Added Additional Puppet Wargoals against all Non-Aligned countries in South America.
- No longer locked if the USA is fascist.
+ Instead of specifically selecting some countries to not be included, now specifies that Strategic Regions 34 (Central America), 205 (Yucatan Peninsula), and 53 (Caribbean Sea) are not included.
```
>Now as the **United States of South America** you can actually get all of **South America**. Previously Non-Aligned wouldn't join your faction and you **couldn't invade** them.
>Also, before this you could get **wargoals** on countries in **Central America** and the **Caribbean** but not El Salvador, Panama, Mexico or the Dominican Republic, leading to very weird and **inconsistent wargoals**.
_______
## No Communism In South America ⚔️ 🌎 🌹 (Focus) [Bugfix, Balance]
``` diff
! Focus now takes 35 days instead of 70.
- No longer locked if the USA is communist.
+ Now specifies that Strategic Regions 34, 205, and 53 are not included.
```
>Now you get **wargoals** for countries only in **South America**.
_______
## Increase Defense Spending 🏭 (Focus) [Balance]
### New requirements:
  ```diff
+ World tension > 0.30
OR
+ War support > 0.70
 ```
 ### Other Changes:
  ```diff
- Consumer Goods Factor from -15% to -10%.
+ Factory Output from +5% to +10%.
+ Dockyard Output from +5% to +10%.
+ Building slot for state gaining Military Factory from 1 to 3.
+ Military Factory +2
+ Building slot for state gaining Dockyard from 1 to 3.
! From 365 Days to 450.
  ```
>Simple buff to an industry focus but now with a higher requirement. Gives you more flexibility in what focuses to pick.
_______
## South American Joint Military Exercises 🎖️ 🌎 (Focus) [Balance]
  ```diff
! From 35 Days to 70.
- No longer gives random terrain traits with chance of failure.
+ Now gives guaranteed Jungle Rat trait and 2 Logistics skill to all army leaders of nations in South America who are in your faction.
```
>Previously it was too random and I prefer predictability. Now gives South America a unique advantage in being very good at fighting in forests and consuming less supplies.
  _______
## American-Brazilian Technology Exchange 🎓 (Focus) [Balance]
```diff
+ Adds 1 Extra Research Slot.
! Focus now takes 70 days instead of 35.
```
>I have genetically enhanced all Brazilians. You're welcome.
_______
## Latin American Research Council 🎓 (Focus) [Balance]
```diff
+ Adds 1 Extra Research Slot.
```
>I have genetically enhanced all Brazilians. You're welcome.
_______
  
  </details>
  
_______
## DOMINATION OF THE AMERICAS PATH 
#### (FASCIST BRAZIL ☠️, NON-ALIGNED 'ESTADO NOVO' 🎩 & MONARCHISM 👑)

<details>

****
## America De Sul 🎓 (Focus) [Balance]
```diff
+ Adds 1 Extra Research Slot.
```
>I have genetically enhanced all Brazilians. You're welcome.
  
 </details>
 
_______

## COMMUNIST BRAZIL 🌹

 <details>

## Establish ULASR 🎓 (Focus) [Balance]
```diff
Adds 1 Extra Research Slot.
```
>I have genetically enhanced all Brazilians. You're welcome.
****
## End South American Capitalism ⚔️ 🌎 🗽 (Focus) [Bugfix]
```diff
+ Instead of specifically selecting some countries to not be included, now specifies that Strategic Region of 34, 205 and 53 are not included. Meaning you get wargoals for countries only in South America.
+ Focus can now be activated if a Non-Aligned nation is a viable target.
```
>Previously, this focus wouldn't be activatable if **only Non-Aligned targets** were available, as it only checked for **Democracies**.
>Also, same problems as "No Fascism In South America" with El Salvador, Panama, Mexico or the Dominican Republic.

  </details>
