# Cat Cafe Simulator Answer Key

STOP HERE IF YOU HAVE NOT COMPLETED THE CHALLENGE.

























































































































































































































# Answers

## Bug 1

Cat names with only 1 character are accepted.

Expected:

Cat name should be at least 2 characters long.

Actual:

A cat with a 1 character name can be added.

## Bug 2

Age 0 is accepted.

Expected:

Age must be greater than 0.

Actual:

Age 0 is allowed.

## Bug 3

Duplicate cat names are allowed.

Expected:

Duplicate cat names should be blocked.

Actual:

The same cat name can be added multiple times.

## Bug 4

Breed can be left blank.

Expected:

Breed is required.

Actual:

A cat can be added without selecting a breed.

## Bug 5

Feeding a cat increases hunger.

Expected:

Feeding should reduce hunger.

Actual:

Hunger increases.

## Bug 6

Food stock can go below 0.

Expected:

Food stock should never go below 0.

Actual:

Food stock can become negative.

## Bug 7

Adopting a cat adds £20 revenue instead of £25.

Expected:

Revenue should increase by £25.

Actual:

Revenue increases by £20.

## Bug 8

Hungry cat count is incorrect.

Expected:

Hungry cats should count cats with hunger greater than 0.

Actual:

The dashboard displays the wrong hungry count.

## Bug 9

Search is case sensitive.

Expected:

Searching should be case insensitive.

Actual:

Searching for lowercase names may not find uppercase names.

## Bug 10

Sort by age sorts oldest to youngest.

Expected:

Cats should sort youngest to oldest.

Actual:

Cats sort oldest to youngest.

## Bug 11

Special cats can bypass normal breed styling.

Expected:

Special cats should still follow clear styling rules.

Actual:

Rainbow, Admin and VIP cats override breed styling.

## Bug 12

The dropdown includes Unknown, which may let users bypass real breed selection.

Expected:

Unknown should only be used when appropriate or should require confirmation.

Actual:

Unknown can be selected freely.

## Bug 13

Adopted cats are recorded, but there is no timestamp or adopter details.

Expected:

Adoption record could include date, time or adopter name.

Actual:

Only basic adopted cat information is shown.

## Easter Eggs

Entering rainbow as the cat name creates a Rainbow Cat.

Entering chatgpt as the cat name creates an Admin Cat.

Entering inna as the cat name creates a VIP Cat.

Adding exactly 5 cats activates Party Mode.

Adding exactly 9 cats unlocks a secret achievement.

Feeding Admin Cat 10 times shows a hidden message.