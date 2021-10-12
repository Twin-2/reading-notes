# Lecture Context API

## Global state

Mutable data that all components can access freely without it having to be passed

components can "look up" usint `contect.<whatever>` to get info from the parent

good for things that are global and **stable**

## Changing context

Use useState to create a setState method. Pass this in as part of the context then all children can access that setState.

- you do not want to directly change context because it will not trigger a rerender

## Questions

set state with a callback function?

nesting of function in the useForm?
