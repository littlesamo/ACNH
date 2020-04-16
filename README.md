I added the genetic analysis to the oringial note by Paleh
## **Guaranteed blue rose path**
> **Note**: due to spawning mechanics in New Horizons, it’s recommended to have multiple pairs at each step to speed up breeding. This means starting with a bunch of whites to get your first purples, getting multiple offspring from each step so you have a reasonable amount of pairs per step. In New Leaf, this matters much less.

### 1.  Breed two seed whites together to get a purple (25% chance), Breed two seed reds for black (25%)

#### white x white
* parents:
```
rose, white, rryyWwbb (seed)
rose, white, rryyWwbb (seed)
```
* Offsprings:
```
Offsprings:
rose, purple, rryyWWbb  rate: 0.25
rose, white, rryyWwbb (seed) rate: 0.5
rose, white, rryywwbb  rate: 0.25

purple rate: 0.25
white rate: 0.75

```

#### red x red
* parents:
```
rose, red, RRyywwBb (seed)
rose, red, RRyywwBb (seed)
```
* Offsprings:
```
rose, pink, RRyywwBB  rate: 0.25
rose, red, RRyywwBb (seed) rate: 0.5
rose, black, RRyywwbb  rate: 0.25
```

### 2. Breed that purple with a seed yellow to get white (100%)
* parents:
```
rose, yellow, rrYYwwbb (seed)
rose, purple, rryyWWbb
```
* Offsprings:
```
rose, white, rrYyWwbb  rate: 1.0
```

### 3. Cross that white back to purple to get purple offspring (50%)
* parents:
```
rose, white, rrYyWwbb
rose, purple, rryyWWbb
```
* Offsprings:
```
rose, purple, rrYyWWbb  rate: 0.25 - good purples
rose, white, rrYyWwbb  rate: 0.25
rose, purple, rryyWWbb  rate: 0.25  - bad purples
rose, white, rryyWwbb (seed) rate: 0.25

purple rate: 0.5
white rate: 0.5
```

#### Choose the right purple
* This is where it gets tricky. Only half of the purple offspring **(purple with gene rrYyWWbb)** will have the required genes for the next step, so you have two options. You could place them all in a large plot together and move on to the next step, knowing that you may not be able to produce white offspring at all, or you can test breed them to seed yellows to pick out the good purples and guarantee that you can complete the next step.
* **The good purples (rrYyWWbb)** can produce yellows 50% of the time when crossed with seed yellows, while **the bad purples (rryyWWbb) only produce whites**. If it doesn’t produce a yellow after 3-4 breedings, you can safely get rid of the purple. You will need at least two good purples in New Leaf, and one in New Horizons, since it’s best to duplicate the good purple in NH.
* Important New Horizons notes: 
  * Due to flowers now being able to duplicate themselves, if you’re not doing a 1-on-1 breeding layout, it’s recommended to block open spots around your purple parent at this step.
  * For the same reasons, if you do any layout other than 1-on-1 breeding for the test breeding, it’s required to block open spots around the seed yellows.
  * After you have one confirmed good purple, the easiest thing to do is to stop breeding the parents, isolate the purple, and water it to duplicate it.

### 4. Breed two of the purples (rrYyWWbb) from the last step to get white* (25%)
* parents:
```
rose, purple, rrYyWWbb
rose, purple, rrYyWWbb
```
* Offsprings:
```
rose, white, rrYYWWbb  rate: 0.25  -- this is white*
rose, purple, rrYyWWbb  rate: 0.5
rose, purple, rryyWWbb  rate: 0.25

white rate: 0.25
purple rate: 0.75
```

### 5. Breed the white* with the black for reds (100%)
* parents:
```
rose, white, rrYYWWbb
rose, black, RRyywwbb
```
* Offsprings:
```
rose, red, RrYyWwbb  rate: 1.0
```
**At this point, these are the “hybrid reds” that are capable of producing blue offspring. However, the following steps will gradually increase the odds of blue offspring from 1 in 64 up to 1 in 4.**
``` 
blue rate: 0.015625
orange rate: 0.234375
black rate: 0.09375
red rate: 0.40625
white rate: 0.125
yellow rate: 0.078125
purple rate: 0.046875
```

<details><summary>red (RrYyWwbb) x red -> 1.56% blue</summary>
<p>
 
* Offsprings:
```
rose, blue, RRYYWWbb  rate: 0.015625
rose, orange, RRYYWwbb  rate: 0.03125
rose, orange, RRYYwwbb  rate: 0.015625
rose, black, RRYyWWbb  rate: 0.03125
rose, red, RRYyWwbb  rate: 0.0625
rose, orange, RRYywwbb  rate: 0.03125
rose, black, RRyyWWbb  rate: 0.015625
rose, black, RRyyWwbb  rate: 0.03125
rose, black, RRyywwbb  rate: 0.015625
rose, red, RrYYWWbb  rate: 0.03125
rose, orange, RrYYWwbb  rate: 0.0625
rose, orange, RrYYwwbb  rate: 0.03125
rose, red, RrYyWWbb  rate: 0.0625
rose, red, RrYyWwbb  rate: 0.125
rose, orange, RrYywwbb  rate: 0.0625
rose, red, RryyWWbb  rate: 0.03125
rose, red, RryyWwbb  rate: 0.0625
rose, red, Rryywwbb  rate: 0.03125
rose, white, rrYYWWbb  rate: 0.015625
rose, yellow, rrYYWwbb  rate: 0.03125
rose, yellow, rrYYwwbb (seed) rate: 0.015625
rose, purple, rrYyWWbb  rate: 0.03125
rose, white, rrYyWwbb  rate: 0.0625
rose, yellow, rrYywwbb  rate: 0.03125
rose, purple, rryyWWbb  rate: 0.015625
rose, white, rryyWwbb (seed) rate: 0.03125
rose, white, rryywwbb  rate: 0.015625
```

</p>
</details>

### 6. Cross the hybrid reds back with the whites* for oranges (12.5%)
* parent
```
flower1: rose, red, RrYyWwbb
flower2: rose, white, rrYYWWbb
```
* Offsprings:
```
rose, orange, RrYYWwbb  rate: 0.125  - guaranteed route
rose, red1, RrYYWWbb  rate: 0.125  - all reds can breed togther
rose, red2, RrYyWWbb  rate: 0.125
rose, red3, RrYyWwbb  rate: 0.125
rose, white, rrYYWWbb  rate: 0.125
rose, yellow, rrYYWwbb  rate: 0.125
rose, purple, rrYyWWbb  rate: 0.125
rose, white, rrYyWwbb  rate: 0.125
```
#### If you stop here, these oranges can be bred together for a 6.25% chance at blue offspring.
<details><summary> orange x orange (RrYYWwbb) -> 6.25% blue </summary>
<p>
 
```
rose, blue, RRYYWWbb  rate: 0.0625
rose, orange, RRYYWwbb  rate: 0.125
rose, orange, RRYYwwbb  rate: 0.0625
rose, red, RrYYWWbb  rate: 0.125
rose, orange, RrYYWwbb  rate: 0.25
rose, orange, RrYYwwbb  rate: 0.125
rose, white, rrYYWWbb  rate: 0.0625
rose, yellow, rrYYWwbb  rate: 0.125
rose, yellow, rrYYwwbb (seed) rate: 0.0625
```
</p></details>
 
#### Breeding the reds also have high chance of getting blue

<div style="margin-left:150px">
<details><summary>red1 x red1 (RrYYWWbb) - 25% </summary>
<p>
 
```
rose, blue, RRYYWWbb  rate: 0.25
rose, red, RrYYWWbb  rate: 0.5
rose, white, rrYYWWbb  rate: 0.25
```
</p></details> </div>

<details><summary>red1 (RrYYWWbb) x red2 (RrYyWWbb) - 12.5%</summary>
<p>
 

```
rose, blue, RRYYWWbb  rate: 0.125
rose, black, RRYyWWbb  rate: 0.125
rose, red, RrYYWWbb  rate: 0.25
rose, red, RrYyWWbb  rate: 0.25
rose, white, rrYYWWbb  rate: 0.125
rose, purple, rrYyWWbb  rate: 0.125
```
</p></details> 

<details><summary>red1 (RrYYWWbb) x red3 (RrYyWwbb) - 6.25% </summary>
<p>
 
```
rose, blue, RRYYWWbb  rate: 0.0625
rose, orange, RRYYWwbb  rate: 0.0625
rose, black, RRYyWWbb  rate: 0.0625
rose, red, RRYyWwbb  rate: 0.0625
rose, red, RrYYWWbb  rate: 0.125
rose, orange, RrYYWwbb  rate: 0.125
rose, red, RrYyWWbb  rate: 0.125
rose, red, RrYyWwbb  rate: 0.125
rose, white, rrYYWWbb  rate: 0.0625
rose, yellow, rrYYWwbb  rate: 0.0625
rose, purple, rrYyWWbb  rate: 0.0625
rose, white, rrYyWwbb  rate: 0.0625
```
</p></details> 

<details><summary>red2 (RrYyWWbb) x red2 (RrYyWWbb) - 6.25%</summary>
<p>
 
```
rose, blue, RRYYWWbb  rate: 0.0625
rose, black, RRYyWWbb  rate: 0.125
rose, black, RRyyWWbb  rate: 0.0625
rose, red, RrYYWWbb  rate: 0.125
rose, red, RrYyWWbb  rate: 0.25
rose, red, RryyWWbb  rate: 0.125
rose, white, rrYYWWbb  rate: 0.0625
rose, purple, rrYyWWbb  rate: 0.125
rose, purple, rryyWWbb  rate: 0.0625
```
</p></details> 

<details><summary>red2 (RrYyWWbb) x red3 (RrYyWwbb) - 3.125%</summary>
<p>
 
```
rose, blue, RRYYWWbb  rate: 0.03125
rose, orange, RRYYWwbb  rate: 0.03125
rose, black, RRYyWWbb  rate: 0.0625
rose, red, RRYyWwbb  rate: 0.0625
rose, black, RRyyWWbb  rate: 0.03125
rose, black, RRyyWwbb  rate: 0.03125
rose, red, RrYYWWbb  rate: 0.0625
rose, orange, RrYYWwbb  rate: 0.0625
rose, red, RrYyWWbb  rate: 0.125
rose, red, RrYyWwbb  rate: 0.125
rose, red, RryyWWbb  rate: 0.0625
rose, red, RryyWwbb  rate: 0.0625
rose, white, rrYYWWbb  rate: 0.03125
rose, yellow, rrYYWwbb  rate: 0.03125
rose, purple, rrYyWWbb  rate: 0.0625
rose, white, rrYyWwbb  rate: 0.0625
rose, purple, rryyWWbb  rate: 0.03125
rose, white, rryyWwbb (seed) rate: 0.03125
```
</p></details> 

<details><summary>red3 (RrYyWwbb) x red3 (RrYyWwbb) - 1.56%</summary>
<p>
 
```
rose, blue, RRYYWWbb  rate: 0.015625
rose, orange, RRYYWwbb  rate: 0.03125
rose, orange, RRYYwwbb  rate: 0.015625
rose, black, RRYyWWbb  rate: 0.03125
rose, red, RRYyWwbb  rate: 0.0625
rose, orange, RRYywwbb  rate: 0.03125
rose, black, RRyyWWbb  rate: 0.015625
rose, black, RRyyWwbb  rate: 0.03125
rose, black, RRyywwbb  rate: 0.015625
rose, red, RrYYWWbb  rate: 0.03125
rose, orange, RrYYWwbb  rate: 0.0625
rose, orange, RrYYwwbb  rate: 0.03125
rose, red, RrYyWWbb  rate: 0.0625
rose, red, RrYyWwbb  rate: 0.125
rose, orange, RrYywwbb  rate: 0.0625
rose, red, RryyWWbb  rate: 0.03125
rose, red, RryyWwbb  rate: 0.0625
rose, red, Rryywwbb  rate: 0.03125
rose, white, rrYYWWbb  rate: 0.015625
rose, yellow, rrYYWwbb  rate: 0.03125
rose, yellow, rrYYwwbb (seed) rate: 0.015625
rose, purple, rrYyWWbb  rate: 0.03125
rose, white, rrYyWwbb  rate: 0.0625
rose, yellow, rrYywwbb  rate: 0.03125
rose, purple, rryyWWbb  rate: 0.015625
rose, white, rryyWwbb (seed) rate: 0.03125
rose, white, rryywwbb  rate: 0.015625
```
</p></details> 
 
### 7. Cross the oranges back to whites* for reds (25%)
* parents:
```
rose, white, rrYYWWbb
rose, orange, RrYYWwbb
```
* Offsprings:
```
rose, red, RrYYWWbb  rate: 0.25
rose, orange, RrYYWwbb  rate: 0.25
rose, white, rrYYWWbb  rate: 0.25
rose, yellow, rrYYWwbb  rate: 0.25
```

### 8. Breed two of those reds together for blue (25%)
* parents:
```
rose, red, RrYYWWbb
rose, red, RrYYWWbb
```
* Offsprings:
```
rose, blue, RRYYWWbb  rate: 0.25
rose, red, RrYYWWbb  rate: 0.5
rose, white, rrYYWWbb  rate: 0.25
```
