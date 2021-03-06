# Data Structures

Stiching the fairytale using data structures.


## The Obvious

The king had **42** rice grains, you give him the rice grains exponential to a chessboard. So, basically you give him **2^1** on the first day, **2^2** on the second day and so on.

You know the story right? Right?

How do we calculate the amount of rice on the 64th day?

Obviously, `42 + ( 2 + 4 + 8 + 16 + ... 2^64 )`

So, it's simple! ( I suggest you using `iPython` or interactive python which allows you to directly execute python code ) 

Alright back to the king and his rice story.

So, fire up `iPython` ( just type `iPython` on the command line and press (enter, duh.)

```
▶ ipython
Python 3.7.0 (default, Jul 25 2018, 22:46:53)
Type 'copyright', 'credits' or 'license' for more information
IPython 6.5.0 -- An enhanced Interactive Python. Type '?' for help.

In [1]:

```

( it's fine if you have anything in the form `Python 3.x.y`, don't worry, just use version **3**)

So the answer is simple, 

```
42 + 2 + 4 + 8 + 16 + 32 + 64 + 128 + 256 + 512 + 1024 + 2048 + 4096 + 8192 + 16384 + 32768 + 65536 + 131072 + 262144 + 524288 + 1048576 + 2097152 + 4194304 + 8388608 + 16777216 + 33554432 + 67108864 + 134217728 + 268435456 + 536870912 + 1073741824 + 2147483648 + 4294967296 + 8589934592 + 17179869184 + 34359738368 + 68719476736 + 137438953472 + 274877906944 + 549755813888 + 1099511627776 + 2199023255552 + 4398046511104 + 8796093022208 + 17592186044416 + 35184372088832 + 70368744177664 + 140737488355328 + 281474976710656 + 562949953421312 + 1125899906842624 + 2251799813685248 + 4503599627370496 + 9007199254740992 + 18014398509481984 + 36028797018963968 + 72057594037927936 + 144115188075855872 + 288230376151711744 + 576460752303423488 + 1152921504606846976 + 2305843009213693952 + 4611686018427387904 + 9223372036854775808 + 18446744073709551616

```

You'll get the answer! But, boy this is a headache! I mean just horizontal scrolling is painful. Who does that? 

We don't. I mean, I don't.

### Anatomy of loops

Loops are analogues to programming the same way why we humans **need** computers.

Here `loops` profile picture.

```
LOOP {
 #something
}

```

A **loop** in essence is a piece of code that instructs the computer to carry out the mundane task of repeating something till a condition is met. 

If the condition can't be met, you're just being malevolent.

In python, a simple `for` loop, like the C++ `for (int i = 0; i < MAX; i++ ) printf("%n", i);` is simple.

```
for i in range(0,MAX):
	print(i) 	
```
 
**Note:** This will print till `MAX-1` like the `C++` code.
 
Running that code gives us: 

```
In [1]: for i in range(1,11):
   ...:     print(i)
   ...:
1
2
3
4
5
6
7
8
9
10
```

Voila! Much simpler than writing 10 times. 

But wait. There's a lot more to loops. You have an arsenal of commands to make your life much easier.


