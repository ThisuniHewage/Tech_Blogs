# Tech Blog 01 – Loops (Explained Like You're in Uni With Me)

Before I started my degree, I honestly thought “loops” were just something that happened in Spotify playlists. But two months into coding, I discovered their actual magic and now I’m here to explain what loops really are, in the simplest (and funniest) way possible, so you too can feel like a genius.

### Why Do We Even Need Loops?
Imagine your lab instructor says:  
“Write a program to print ‘Hello World’ 100 times.”  

What would you do?

Maybe something like this:

```java
System.out.println("Hello World");
System.out.println("Hello World");
System.out.println("Hello World");
// ...97 more lines of pure suffering
```
Sure, you could copy–paste… but it still takes time, looks messy, and makes you question all your life choices.

But if you know loops? → 3–4 lines and you’re done. Magic.

## For Loop — When You Know Exactly How Many Times Mom Will Nag

Real-life scenario: Morning time. Mom enters your room to wake you up.
Think of a real-life situation.

Your mom comes into your room every morning to wake you up.
The first time? You don’t get up.
Second? Nope.
She keeps nagging until you finally leave the bed.

After years of experience, you know this pattern:
If she nags 10 times, the 11th time she will definitely lose her temper so you have to wake up.

This kind of predictable repetition = perfect for a 'for loop'.

```java
for (int i = 1; i <= 10; i++) {
    System.out.println(i + ". WAKE UPPP!!!!");
}
```

This runs exactly 10 times. No more, no less.

Now back to the lab task, printing “Hello World” 100 times:
```java
for (int i = 1; i <= 100; i++) {
    System.out.println("Hello World");
}
```
Boom. 100 times. Zero pain.

### How Does This Black Magic Actually Work?

Let’s break down the three parts inside the parentheses:
1. int i = 1 → starting point (mom’s first nag)
2. i <= 100 → condition: keep going as long as this is true
3. i++ → after each loop, increase i by 1 (next nag)

Initialization → Condition → Increment/Decrement. 

## While Loop — When Mom Won’t Stop Until the Room Is Actually Clean

This scenario is painfully accurate.

Your mom will NEVER stop nagging until your room is cleaned, laundry folded, and your soul cleansed.

This is where while loops shine, they run until a condition becomes true.

```java

while (!roomIsClean) {
    System.out.println("Clean the room!!!!!!!!!");
}

```
This loop continues until the room is clean.

### Printing "Hello World" with a While Loop

```java
int count = 1;

while (count <= 100) {
    System.out.println("Hello World");
    count++;
}

```

### What's happening here?
-You start with a counter: count = 1

-The loop keeps running as long as count <= 100

-Each loop prints “Hello World”

-After every print, count increases by 1

Once count becomes 101, the condition becomes false → loop stops.

## Common Beginner Mistake: Infinite Loops

Be careful! If you forget to change the variable inside your loop, or your condition never becomes false, the loop will run forever.

Example of an accidental infinite loop:

```java
while (count <= 100) {
    System.out.println("Hello World");
    // forgot count++
}

```
Your program will print forever and cry for help.
So always check your:

-condition

-increment/decrement

-starting value


## When should you use which loop?

| Loop Type | When to Use It|
|------------|----------------|
| **for loop** | Use when you know exactly how many times the loop should run. |
| **while loop** | Use when you don't know the exact number of repetitions and the loop depends on a condition. |

Loops make your life (and code) easier by letting you repeat actions without writing the same line again and again.

Now you know:

-what a for loop is

-what a while loop is

-when to use each

-and what mistakes to avoid

### Up next in Tech Blog 02:
do-while loops & nested loops explained with funny real-life examples.
