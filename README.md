# Gut

> A version control system with gut feeling.

## Contents

1. [Motivation](#motivation)

1. [Features](#features)

1. [Installation](#installation)

1. [Usage](#usage)

    1. [Learning gut](#learning-gut)

    1. [Help message](#help-message)

1. [Contributions](#contributions)

1. [Credits](#credits)

## Motivation

Git was always complicated to use even for "pro"grammers (pun alert!). Hence we decided to make gut.
This made most of our tasks easy and increased speed and efficiency by 15 times.

## Features

* **Very very small:** The gut binary is only 2KB in size. It's like magic!

* **It's not even a binary:** Gut is purely written in programmer-friendly shell script. You can modify
it yourself too and don't have to struggle so much.

* **Has only commands you need:** Gut comes with just 5 commands because let's face it -- we only use
`commit` and `checkout` and `log`. We also removed the `add` command. See, gut knows you don't need it :)

* **Extremely high speed:** You can checkout to any commit in a matter of mili-seconds. Why did we ever
need those huge linked lists and diffs. You can go anywhere you want instantly, because what you did is
always safe with gut.

* **No more tiring commit messages (and hashes):** Gut doesn't ask you to write those long descriptive
commit messages. We know you lose half of your strength writing those. And then the misery of finding
all those hashes among your log. Gut asks you to set the id of commit yourself... JUST THE ID.

## Installation

Just copy the `gut` file somewhere in your `$PATH`. It's that simple!

## Usage

### Learning gut

1. Create a gut repository by `gut init` command.

1. Make changes to your worktree.

1. Commit your changes directly by `gut commit [id]`. See, you don't have to add files to staging area or
write a long message. JUST THE ID!

1. To view your commits use the `gut log` command.

1. To checkout to certain commit use `gut checkout [id]`.

See, you've successfully mastered gut!

### Help message

Use `gut help` to view this message.

```
Gut - A VCS with gut feeling.
Commands:
  checkout [id] -- Checkout worktree to 'id' commit.
  commit [id]   -- Commit your changes.
  help          -- Prints this message.
  init          -- Initialises the current directory as a gut repository.
  log           -- View log of commits of the repository.
Built with a lot of ♥️ by SDSLabs.
```

## Contributions

Well, gut is perfect. We don't think you can improve it any further. Still if you have a brilliant idea,
submit a pull request. We'll definitely politely discard it what-so-ever.

## Credits

Built with a lot of ♥️ by SDSLabs.

<span style="font-size:9px">Happy April Fools day! 🥳</span>
