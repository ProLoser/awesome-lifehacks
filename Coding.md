# Coding

## Work Life Balance
It's difficult to code while context switching in and out of meetings and reviews. Sometimes challenges require digestion and feedback. The biggest blocker is lack of knowledge and decision making.

When COVID hit, most stores were only open in the middle of the afternoon. It forced me to attend meetings remotely while taking care of chores. I would then defer my programming to a separate window in my schedule. I would frequently spend multiple days deliberately avoiding programming to focus on meetings and chores and to polish my plan. When you finally sit down to code you will appreciate all the research and spec collection gathering and brainstorming you frontloaded.

Ask questions, take notes, and research while actively reviewing work of your teammates to keep them unblocked. Focus on reviews and teammate velocity. When your plan is ready, take a block of hours to disconnect from the world and focus purely on programming (or just going through emails)

I found my productivity increase reduced the need for coding sessions maybe once or twice a week. It's important to create situations where you can tunnel focus on the task at hand uninterrupted. When the plan and research is clear, your code will flow freely.

At the end of the day, you can only ask yourself to accomplish one thing. Move the needle. Hit the ball back into someone else's court. Not every ball, not every court. But challenge yourself with the lowest you can attain and see how far your momentum takes you.

## anti patterns
Code patterns are just tools. They are not typically good or bad, they are merely tools that we can choose to leverage or bias ourselves to avoid. Instead always be open to changing your perspective when given new information.

## Code Debt and Refactorability
The "R" word is not a 4 letter word although many managers seem to react that way.

Code debt exploration spikes although frequently incomplete are still extremely useful. I have left DRAFTs open years and find I am always able to come back and revisit this knowledge. Instead of forcing your team to adopt large painful changes, try to slice your draft into smaller pieces that can be used as fixes for bugs as they surface. This will help ground the effort in meaningful value for the end user and product managers.

Try to write code with the intention of refactoring. Anticipate future expectations of evolving behavior and try to adopt the relevant paradigms and patterns without increasing complexitly prematurely. It is always easier to make something simple more complicated than it is to make something complicated more simple.

Premature Optimization is like other Premature things... Emberrassing.
- Unknown

## 80/20 Rule
Focus on the 20% effort that would cover 80% of the results / users. Then identify the most frequent touch points when prioritizing remaining work.


## Peer Review

## Interface Design
Forgiveness vs Permission

minimalism and skeuomorphism

## Terminal

`ctrl + R` in Terminal will allow you to search through your command history

## JavaScript

**Inverted Switch**
```
switch (true) {
  case  x > 0:
  case  x < 0:
  case  x == 0:
}
```

**Parallel Await**
```
await Promise.all( collection.map( item => doAsyncOperation(item) ) )
```
