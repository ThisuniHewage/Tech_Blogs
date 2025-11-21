# Loops in Java = My Mom Nagging Me to Wake Up (You’ll Feel This)

Before I joined university, I genuinely thought “loop” only meant when Spotify keeps playing the same song on repeat.  
Two months into Java, my whole world changed. Loops are literally the reason your Netflix show auto-plays the next episode, your game character keeps running, and… why my mom can nag me 50 times without typing it 50 times.

### The Pain Before Loops (We’ve All Been Here)
Imagine your lab instructor says:  
“Write a program to print ‘Hello World’ 100 times.”  

Your first instinct (don’t lie):

```java
System.out.println("Hello World");
System.out.println("Hello World");
System.out.println("Hello World");
// ...97 more lines of pure suffering
```
Copy-paste 99 times? Still takes forever and your wrist dies.
But if you know loops? → 3–4 lines and you’re done. Magic.

## for Loop – When You Know Exactly How Many Times Mom Will Nag

Real-life scenario: Morning time. Mom enters your room to wake you up.

First try → you pretend to be dead.

Second try → still dead.

But you KNOW she will nag exactly 10 times before she loses it and pulls the blanket.
So on the 10th “WAKE UP!!!” you finally get up (to save your life).
That’s a for loop situation where you know the exact number of repetitions.

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
