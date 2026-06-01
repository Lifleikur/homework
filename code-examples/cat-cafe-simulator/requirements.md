# Cat Cafe Simulator Requirements

## Add Cat

A user should be able to add a cat with:

- Name
- Age
- Breed

## Validation

- Cat name is required
- Cat name must be at least 2 characters long
- Age is required
- Age must be greater than 0
- Breed is required
- Duplicate cat names are not allowed

## Breed Icons And Colours

Cats should display an icon and background colour based on breed.

Supported breeds:

- Siamese
- Persian
- Bengal
- Ragdoll
- Sphynx
- Maine Coon

Unknown breeds should use a default paw icon and white background.

Breed matching should work even if the user uses capital letters or spaces.

## Feed Cat

When a cat is fed:

- Hunger should decrease
- Food stock should decrease by 1
- Hunger should never go below 0
- Food stock should never go below 0

## Adopt Cat

When adopted:

- The cat should be removed from the active Cat List
- The cat should appear in the Adopted Cats list
- Total cats should decrease
- Adopted cats count should increase
- Revenue should increase by £25

## Statistics

The dashboard should show:

- Total cats
- Hungry cats
- Food stock
- Daily revenue
- Adopted cats

## Search

Search should:

- Find matching cats
- Be case insensitive

## Filter

Hungry cats are cats with hunger greater than 0.

## Sort

Cats should sort by age from youngest to oldest.

## General

The application should remain stable after repeated actions.