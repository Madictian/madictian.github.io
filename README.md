### Fredrik Bille
^Name is stated above^
I am a student of computer science at zealand school of applied sciences. i just started this fall after a five year sabatical due to personal reasons. My hobbies might seem very stereotypical of any pc related education, cause we game, we nerd, we obsess and im looking forward to expanding the nerding spektrume while making some money on top of it.


![image](https://media.discordapp.net/attachments/751336524452331520/753220728278482954/IMG_20200121_173613.jpg?width=200&height=200)



Currently my days are spent learning a new craft, that is programming and pass my freetime by looking at funny pictures and reposting them as funny reactions to others. trying to keep a healthy circle og laughter between my friendsgroup and classmates. other antics would a bit of iceskating coupled with the gravity excersises that follows!



![image](https://media.discordapp.net/attachments/751336524452331520/753220727527964712/Screenshot_20200510-115232.jpg?width=200&height=200) 


## Before

As mentioned i took a 5 year sabaticle, it was planned to only keep me busy for a years time, but having money, picking working hours
and having a sweet working enviroment you tend to fall into habbits. Which i am terrible at changing. what did this work provide me with?

 - I got better at interacting with all sorts of people, which was a weak point of mine as an introvert.
 
 - I got used the responsibilities of having a full-time job, the free of a part-time job and learned the importance of taking breaks.
 
 - I'd like to believe i became good at both problemsolving and prevention, doing so with mininal resources available.
 
   (disclaimer : *the situation in the picture is not my brainchild, i was just on my way to lunch!*)

![](https://media.discordapp.net/attachments/753265458047746199/753266089110143066/IMG_20190219_211545.jpg?width=200&height=250)

## Now

>All was good, you had money, time off when you wanted, what went wrong?Well conditions changed.

I had for a while thought that the place i was working was a joke from a concept standpoint, and the management was a bunch of cheapsakes.
So me and my buddies from the same team all took the decisions to look around for alternatives, computer sciences had was my first choice around, so i applied
only to that and decided i would take till winter to look around if i did not get accepted. Well the result was the favorable one and i hope my leap of faith
will inspire my buddies to do the same!


![image](https://cdn.discordapp.com/attachments/751336524452331520/753230652999991306/received_614055752555455.gif)

### Right now!

I am showing up everyday, trying my best and resolved to keep at it and leave my procrastinating self in the dust!
school is going fine i would say, i am in a study group with some people that are way better at coding than me, which can admittedly be a little disheartening
but i perservere and try my best to learn from their experience and keep up.

So farm we have make several pieces of code, and a bit of math...

- We made a table to neatly display a table of information

<summary>Click to expand!</summary>

```
        String[][] table  = new String[5][];
        table[0] = new String[] {"a",   "a^2",  "a^3",   "a^4"};
        table[1] = new String[] {"1",     "1",    "1",     "1"};
        table[2] = new String[] {"2",     "4",    "8",    "16"};
        table[3] = new String[] {"3",     "9",   "27",    "81"};
        table[4] = new String[] {"4",    "16",   "64",   "256"};
        /* Even though the perfectionist in me wouldve prefered a program
         that calculated the table and then asorted  the values */

        for (String[]   row :   table)  {
            System.out.format("%15s%15s%15s%15s\n", row);
```
- We made a piece of code to calculate the increase in a contry's population based on births, immigration and factoring death all given parameters
```
        int currentPopulation = 312032386;

        for (int x = 1; x <= 5; x++)
        //danner et for loop som kører formerings loop igen op til 5 år
        {
            for (int i = 1; i <= (365 * 24 * 60 * 60); i++)
            //danner grunlag for den sekund pøl som modulus kan tage af
            {
                if (i % 7 == 0) {
                    currentPopulation += 1;
                    // regner formering
                }
                if (i % 13 == 0) {
                    currentPopulation -= 1;
                    // regner afdøde
                }
                if (i % 45 == 0) {
                    currentPopulation += 1;
                    // regner indvandring
```
-

-

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
