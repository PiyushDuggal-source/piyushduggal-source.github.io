---
title: Weird Dictionaries simplified.
date: 2023-11-17 00:00:00 +0530
categories: [programming, python, tech]
tags: [python, iitmbs, iitm]
---

## Weird Dictionaries simplified 📚

Hey everyone 👋 <br/>
This is my first ever `blog` on the internet, I am excited to share my journey with you.

So we are here for **Dictionaries** right?

Q: What are Dictionaries? <br/>
A: A book? A book that contains many pages? A book that has meanings of other words??

Well, technically yes... But **Pythonically** 🐍 no!!

So, what is a **Dictionary** in Python? <br/
Lets compare it with real world dictionaries. Imagine a real-world dictionary that helps you find the meaning of words. Python dictionaries work similarly, but instead of words and meanings, they store `key-value` pairs. These key-value pairs allow you to quickly find information based on a unique "_key._"

In simple words, think of a **Dictionary** as Locker Room 🔒, where each _key_ 🔑 opens a specific _lock!_ 🔐

So, what are we waiting for? Lets start with a simple example.

### Creation

```python
# Creating an empty dictionary
my_dict = {}

# Adding key-value pairs
my_dict['apple'] = 'A fruit that keeps the doctor away 🍎'
my_dict['banana'] = 'Yellow fruit loved by monkeys 🍌'
my_dict['cherry'] = 'Small red fruit used in desserts 🍒'

print(my_dict)
```

Output:

```sh
{'apple': 'A fruit that keeps the doctor away 🍎', 'banana': 'Yellow fruit loved by monkeys 🍌', 'cherry': 'Small red fruit used in desserts 🍒'}
```

Congratulations! 🎉 You've just created your own Python dictionary! The output will show all the key-value pairs stored in the dictionary.

<div>
<img height="200px" src="https://tenor.com/en-GB/view/catjam-cat-dancing-cat-music-music-cat-cute-cat-gif-23392229.gif" alt="cat emoji gif">
</div>

<!-- <div> -->
<!-- yay! <img height="25px" src="https://tenor.com/en-GB/view/wiggle-wiggles-wiggling-yee-dance-gif-17719249.gif" style="height: 20px" alt="wiggle emoji gif"> -->
<!-- </div> -->

Now wait!.. Hold your horses..🐴

Let me explain! <br/>

### Explanation

```python
my_dict = {}
```

- This line initializes an empty dictionary named `my_dict`. In Python, dictionaries are defined using curly braces **{}**.

```python
my_dict['apple'] = 'A fruit that keeps the doctor away 🍎'
my_dict['banana'] = 'Yellow fruit loved by monkeys 🍌'
my_dict['cherry'] = 'Small red fruit used in desserts 🍒'
```

- These lines add key-value pairs to the `my_dict` dictionary.
- In Python dictionaries, each value is associated with a unique key. Here, '**apple**', '**banana**', and '**cherry**' are keys 🔑, and the corresponding _strings_ are their associated values ℹ️.
- To add a key-value pair to a dictionary, we use square brackets (**[]**) with the key 🔑 inside them on the left side of the assignment operator (**=**), followed by the value on the right side.
- Well, you know the `print` part, right ?

### Accessing

Now comes the usage 🧪<br/>

```python
print(my_dict['apple'])
```

- By specifying the key ('**apple**' in this case), you can instantly retrieve the associated value ('**A fruit that keeps the doctor away 🍎**').

### Usage

WHY **Dictionaries** ? 🤔 💭

- **Fast Information Retrieval** 🔎: Dictionaries allow lightning-fast retrieval of values associated with a given key.
- **Flexibility** 🧰: Dictionaries can be used to store any type of data, including lists, dictionaries, and other complex data structures.
- **Dynamic Nature** 🌿: Dictionaries can be modified easily by adding, updating, or removing key-value pairs.
- **And many more!** 🎉:

### Conclusion

Python dictionaries are not just another data structure; they're magical tools for organizing information effortlessly. These are helpful in complex algorithms and data structures.

Thanks very much!
Happy hacking!

by [@piyushduggal-source](https://github.com/piyushduggal-source) (_mr_unchained_)

_Note: I did not use ChatGPT, kasam se.._
