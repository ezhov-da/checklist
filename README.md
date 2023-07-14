# Checklist format

A guide on why and how the checklist format is described.

The main and most important rule:
> The checklist should be easy to read in a regular editor by the user

## Why plain text?

Plain text is software and operating system independent.
It is searchable, portable, lightweight and easy to manipulate.

## 6 components of the checklist

```
1. # Checklist name
2. -- Section
3. - Unfulfilled item
4. + Completed item
5. * Description block that applies to both the entire checklist and its sections and items
6. . Comment inside the checklist
```

1. The character '#' denotes a line with the name of the checklist and must be at the beginning of the line. After it is
   written the name
   checklist.
2. The characters '--' denote a section and must be at the beginning of the line. After them, the name of the section is
   written
3. The character '-' denotes an unfulfilled list item.
4. The '+' symbol indicates the completed list item.
5. The character '*' denotes the beginning and end of the block. There can be several blocks and they can be treated as
   the entire checklist,
   as well as to the section and to the points.
6. Symbol '.' denotes a comment.

## Checklist example

### Housework

```
# Housework
. list is not final

-- Car
- To wash a car
*
Don't forget to close the windows
*
- Check tire pressure

-- Cleaning
- Clean up the rooms
*
Decide what to do with old children's toys
*
```