1. For me, the pace of the program is just right. At times I feel like I could go faster, but it's nice to slow down and really make sure I understand everything we're learning. And seeing what the project was for this week really helps me see how much we've actually learned even though it might not seem like that much.

2. Functions are a useful tool to organize large programs because it cuts down on clutter, especially if you are using a certain block of code often. Other than being able to use a certain block of code over and over, it also makes the code easier to read, provided they are named appropriately. Another useful thing about functions is that they can call eachother, or themselves, making it very easy to hop around from function to function.

3. In JavaScript, depending on where variables are declared, only certain parts of the code can see them and use them. This is called scope and the two types of scope are global and local. An example of this in real life is in a zoo where there are zookeepers and animals. The zookeeper can go anywhere they want, like a global variable, but the animals are in their exhibits and cannot go to other exhibits.
Here is an example of global scope in JavaScript:
```
let x = 5;
for (let counter = 0; counter < 5; counter +=1) {
  x += 1;
}
console.log(x);
```
The final value of x would come out as 10 because the loop can see the x that was declared outside in the global scope.
However, if the x were declared inside the loop, it would be in the loop's scope, and the console.log would show an error, since it cannot access x at all.  This is local scope:
```
for (let counter = 0; counter < 5; counter +=1) {
  let x = 5;
}
console.log(x);
```

