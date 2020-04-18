**Note: below is based on the google doc [Advanced Flower Genetics by Paleh]( https://docs.google.com/document/d/1ARIQCUc5YVEd01D7jtJT9EEJF45m07NXhAm4fOpNvCs). What I did is adding the genetic analysis to the oringial guide. During the process I found out some of the by product flowers can be used to breed as well. I have noted the findings in genetic analysis as well**. The flower raw data used in my program to do genetic analysis is from [ACNH Flower Research](https://docs.google.com/spreadsheets/d/1EzNu6FUFqH3_nbXQvgy4z5Jqmj_78-dPutSN2OFk8pQ/edit?usp=sharing)

## **Guaranteed blue rose path**
> **Note**: due to spawning mechanics in New Horizons, it’s recommended to have multiple pairs at each step to speed up breeding. This means starting with a bunch of whites to get your first purples, getting multiple offspring from each step so you have a reasonable amount of pairs per step. In New Leaf, this matters much less.

### 1.  Target: purple-1 (25%) and black (25%)

#### white (seed) x white (seed) = purple-1 (25%) + white (toss away!) 
<details><summary> genetics </summary>
<p>
 
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

</p></details>

#### red (seed) x red (seed) = black (25%) + red (seed, 25%) + pink (not used)
<details><summary> genetics </summary>
<p>
 
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
</p></details>


### 2. Target: white-1 (100%)
#### purple-1 x yellow (seed) = white-1 (100%)
<details><summary> genetics </summary>
<p>
 
* parents:
```
rose, yellow, rrYYwwbb (seed)
rose, purple, rryyWWbb
```
* Offsprings:
```
rose, white, rrYyWwbb  rate: 1.0
```

</p></details>


### 3. Target: purple-2 (25%)
#### white-1 x purple-1 = purple2 (25%) + purple-1 (25%) + white (toss away!)
<details><summary> genetics </summary>
<p>
 
* parents:
```
rose, white, rrYyWwbb
rose, purple, rryyWWbb
```
* Offsprings:
```
rose, purple-2, rrYyWWbb  rate: 0.25 - good purples
rose, white, rrYyWwbb  rate: 0.25
rose, purple-1, rryyWWbb  rate: 0.25  - bad purples
rose, white, rryyWwbb (seed) rate: 0.25

purple rate: 0.5
white rate: 0.5
```
As you can see, there will be 2 kinds of white: white(seed) and white-1, there is no good way to distinguish them. 
</p></details>

### 3-1. Option1: Choose the right purple
#### Test purple-1 vs purple-2 with yellow (seed)
 * purple-2 x yellow (seed) = yellow(50%) + white-1 (50%)
 * purple-1 x yellow (seed) = white-1 (100%) 
 * **purple-2 is the ones that can make yellow offsprings**

<details><summary> **Click for details** </summary>
<p> 
 
* This is where it gets tricky. Only half of the purple offspring **(purple with gene rrYyWWbb)** will have the required genes for the next step, so you have two options. You could place them all in a large plot together and move on to the next step, knowing that you may not be able to produce white offspring at all, or you can test breed them to seed yellows to pick out the good purples and guarantee that you can complete the next step.
* **The good purples (rrYyWWbb)** can produce yellows 50% of the time when crossed with seed yellows, while **the bad purples (rryyWWbb) only produce whites**. If it doesn’t produce a yellow after 3-4 breedings, you can safely get rid of the purple. You will need at least two good purples in New Leaf, and one in New Horizons, since it’s best to duplicate the good purple in NH.
* Important New Horizons notes: 
  * Due to flowers now being able to duplicate themselves, if you’re not doing a 1-on-1 breeding layout, it’s recommended to block open spots around your purple parent at this step.
  * For the same reasons, if you do any layout other than 1-on-1 breeding for the test breeding, it’s required to block open spots around the seed yellows.
  * **After you have one confirmed good purple, the easiest thing to do is to stop breeding the parents, isolate the purple, and water it to duplicate it.**
</p></details>

### 3-2. Option2: move to step4 by breeding all purples together - lower chance getting required white-2 


### 4. Target: white-2 (25% if follow 3-1)
#### purple-2 x purple-2 = white-2 (25%) + purple-1 (25%) + purple-2 (50%) 
<details><summary> genetics </summary>
<p>
 
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
</p></details>


### 5. Target: red-2 (100%)
#### white-2 x black = red-2 (100%)
<details><summary> genetics </summary>
<p>
 
* parents:
```
rose, white, rrYYWWbb
rose, black, RRyywwbb
```
* Offsprings:
```
rose, red, RrYyWwbb  rate: 1.0
```
</p></details>

#### **[want to stop here?]: red2 x red2 = blue (1.65%)**
<details><summary>genetics</summary>
<p>

* Parents:
```
red (RrYyWwbb)
```
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

### 6. Target orange (12.5%)
#### red-2 x white-2 = orange (12.5%) + red-2 (12.5%) + red-3(12.5%) + red-4 (12.5%) + purple-2(12.5%) + other(toss)
<details><summary>genetics</summary>
<p>
 
* parent
```
flower1: rose, red-2, RrYyWwbb
flower2: rose, white, rrYYWWbb
```
* Offsprings:
```
rose, orange, RrYYWwbb  rate: 0.125  - guaranteed route
rose, red-4, RrYYWWbb  rate: 0.125  - all reds can breed togther
rose, red-3, RrYyWWbb  rate: 0.125
rose, red-2, RrYyWwbb  rate: 0.125
rose, white, rrYYWWbb  rate: 0.125
rose, yellow, rrYYWwbb  rate: 0.125
rose, purple, rrYyWWbb  rate: 0.125 - this is the same purple used to get white*
rose, white, rrYyWwbb  rate: 0.125
```
</p>
</details>

#### [Want to stop here?] orange x orange = blue (6.25)
<details><summary>Genetics</summary>
<p>

```
orange x orange (RrYYWwbb)
```
 
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
 
#### [TIP] Breeding the reds also have high chance of getting blue

<details><summary>red1 x red1 (RrYYWWbb) - 25% </summary>
<p>
 
```
rose, blue, RRYYWWbb  rate: 0.25
rose, red, RrYYWWbb  rate: 0.5
rose, white, rrYYWWbb  rate: 0.25
```
</p></details> 

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
 
### 7. Target: red-3 (25%)
#### white-2 x orange = red-3(25%) + orange(25%) + white-2(25%) + yellow (toss away!)
<details><summary>Genetics</summary>
<p>
 
* parents:
```
rose, white, rrYYWWbb
rose, orange, RrYYWwbb
```
* Offsprings:
```
rose, red, RrYYWWbb  rate: 0.25
rose, orange, RrYYWwbb  rate: 0.25  -  this orange is the same with parent orange
rose, white, rrYYWWbb  rate: 0.25  - this white is the same with parent white
rose, yellow, rrYYWwbb  rate: 0.25  - discard the yellow
```
</p></details>

NOTE: you can keep breeding the offspring oranges and whites for more reds since they contain the same gene as parents. 


### 8. Target: blue (25%)
#### red-3 + red-3 = blue(25%) + red-3(50%) + white-2(25%)
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
