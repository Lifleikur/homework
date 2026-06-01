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

## Feed Cat

A user should be able to feed a cat.

When a cat is fed:

- Hunger should decrease
- Food stock should decrease by 1
- Hunger should never go below 0
- Food stock should never go below 0

## Adopt Cat

A user should be able to adopt a cat.

When adopted:

- The cat should be removed from the list
- Total cats should decrease
- Revenue should increase by £25

## Statistics

The dashboard should show:

- Total cats
- Hungry cats
- Food stock
- Daily revenue

## Search

A user should be able to search cats by name.

Search should:

- Find matching cats
- Be case insensitive

## Filter

A user should be able to show only hungry cats.

Hungry cats are cats with hunger greater than 0.

## Sort

A user should be able to sort cats by age from youngest to oldest.

## General

The application should remain stable after repeated actions.