1. Now that I've spent more time working on larger projects, I definitely feel better about how I'll adapt to working in the professional world. I know that what I'd be working on would take even longer than what I'm used to, but it'd be more or less the same as what I've already done, just more of it.

2. If I were building a choose your own adventure game for the browser, and the user has clicked a button to make a decision, I would run the respective function that goes along with that button. That function would create a new paragraph element using `document.createElement('p')`, set it's text content to the description of the next room/choice using `para.textContent = 'next room'`, and then append it to the body/whatever the parent element may be using `parentElement.appendChild(para)`. Then I would create buttons for each of the user's next choices using the same method I used to create the paragraphs, setting their text content using the same method, and appending them to the parent element using the same method. Each of these buttons would have their respective functions that lead to the next place and the process would repeat until the end.

3. Data structures are useful because they give us effective ways to store and sort through data in the appropriate situations. For example, the DOM is a data structure called a tree, where nodes contain nodes, and those nodes can contain other nodes, and so on. The DOM would not work as any other data structure. For example, if the DOM was a linked list, each node would only be able to point to one other thing instead of branching out. This would severely limit our ability to sort through it. If it were a stack, nodes wouldn't point to anything and would just come one after the other. A tree allows one node to point to multiple nodes and in doing so allows us to navigate through the DOM as effectively as possible.