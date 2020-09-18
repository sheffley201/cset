1. I think I did pretty well in the first course. The first 3 weeks were pretty easy for me, and the 4th was finally more challenging but I was able to get
everything down with enough time. Something I would like to do differently in the next course is to look at the extra references a little more, so I can have an
even better understanding of things and maybe learn some more tips and tricks.

2. In the werequirrel example, there were many uses of objects and arrays. A very good example of this was Jacques' journal. In his journal, he uses arrays within objects in an array. His journal was one big array of each day. Each day was an object that inluded the events for each day, and whether he turned into a squirrel or not. And the events of each day were stored in an array. An array is a type of object that has values in a praticular order. An example in Jacques' journal is :

```let events = ["work", "touched tree", "pizza", "running"]```

These values can be accessed with the number representing their spot in the array, or their index. The way you would access them would be events[0], events[1], etc.

Objects, however have properties and their values can be accessed using those properties. Objects are also in no particular order like an array is. An example of an object in Jacques' journal is on of the entries:
```
let day1 = {
  squirrel: false,
  events: ["work", "touched tree", "pizza", "running"]
};
```
This object has two properties and those properties could be accessed with day1.squirrel and day1.events.

3. The author chose arrays for the events because it was just a list of things that didn't need properties. The journal entries, however, are easier to keep track of with properties like envents for what he did and squirrel for whether or not he turned into a squirrel. For my game, I could have used an object to keep track of things like the players name, and health. So instead of dying right away you would lose health and keep going, and only die when you run out of health. For an array I could store all of the wrong choices a player made and show them at the end, and possibly calculate a score based off of that.
