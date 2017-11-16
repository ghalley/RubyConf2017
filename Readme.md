# Day 01

## Keynote: Good Change, Bad Change
#### Matz

Ruby's birthday: Feb 24 1993

Community membership is inclusive, but fluid

Changes can be good and bad.
- Bad: makes you work unwillingly, makes you angry, without benefits

Benefits:
- Performance
- Productivity
- Excitement
- Joy

Ruby releases are approximately every Christmas.

## Human Errors
#### Olivier Lacan

Context is useful before feedback

What is an error?
- state or condition of being wrong in conduct or judgement
- obsererved_value != true_value
- latin def is "wandering about"

Middle-users
- between the computers and end users

Can be better, as a community, about providing context with error messages

## Orbital Rocket Guidance with Ruby
#### Nate Berkopec

Computers in space have to be real-time, reliable, and simple

Charles Draper at MIT, built guidance computer in Apollo mission

Soviets had more reliance on computers in spaceflight, providing less room for human error.

Gravity turn

Tilt away from launch tower for a second, then back

github.com/speedshop


## Nothing New Under the Sun
#### Justin Searls, Josh Greenwood

Why use ruby?
- extreme programming roots
- Rails?
- MINASWAN
- Rails
    - Gave ruby a purpose in the community: write web apps

pair programming often means co-located troubleshooting

## Finding Beauty in the Mundane
#### Megan Tiu!

Some tasks are less fun.

Focus on empathy
- mindful of others touching our code

Combat Tech Debt
- What's the grungiest task you've been putting off.

1. Updating Dependencies
    - more secure applications

2. Writing Documentation
    - internally
    - helps spread knowledge
    - prevents silos
    - better onboarding
    - your future self
    - start with a glossary of common terms
    - comment as you write

3. Testing
    - reliable software
    - refactoring becomes easier

4. Linting
    - break down into smaller pieces
    - helps to learn best practices
    - establishes a style guide

5. Refactoring

## Steal This Talk: Features Ruby Doesn't Have Yet
#### John Feminella

Where we are

MUMPS - specific language for medical center
- key-value store directly accessible

## Keynote: Getting Old
#### Chad Fowler

"Systems Euthanizer"

"Legacy"
- such a bad connotation, but it doesn't always have to be

Nodoby. Will. Remember. Your. Work. When. You. Die.

"Working Effectively With Legacy Code" by Michael Feathers

http://tinyurl.com/codealive
- Code survives by providing value and being difficult to replace

Kill and replace cells regularly
- easy to replace small components

Mutability of a system is enhanced by the immutability of its components

Accomplished with super simple interfaces.

# Day 02

## Keynote
#### Andy Croll

TL;DR Life is short, entropy wins.

Alan Watts: "The point of the dancing is the dance."

Not about the journey, but about enjoying the movement

## Lending Privilege
#### Anjuan Simmons

Leonard Nimoy demanded equal pay for Nichelle Nichols, lending his privilege to her.

There is real, studied, financial benefits to diversity and inclusion.

The more people looking at a problem, the more likely it can be quickly and easily solved

U.S. Constitution is a pull request system via amendments.

## Getting Unstuck: Scientific Method for debugging
#### Caroline Taymor

Scientific Method:
- Gather knowledge
- ask questions
- make a hypothesis
- design an experiment
- run the experiment
- take good notes
- make a conclusion
- share out, or restart the process

Write things down.

Go over everything you actually know about a bug.

start with a single question

take an educated guess

try something to test your guess out

take notes on what you expected as well as what you got

were you right or not?

Share.

tech.taymor.io/posts/getting-unstuck

## When you thought you couldn't refactor anymore
#### Claudio B.

`Enumerable#find` - finds first for block that returns true
`(19..99).find{|i| i%17 == 0} #> 34`

speakerdeck.com/claudiob

## Leadership Starts with Listening
#### Heidi Helfand

Slow down and connect

Good listening can draw out other people to grow into leadership

Tool #1: Levels of Listening

1. Inward Focused
    + zoning out and thining about other things
2. Attention Out
3. Body Language/Vibe

Tool #2: Powerful Questions
- Designed to direct curiousity
- help them discover their own solutions
- get them into action

"What do you want?"
"What's important about this?"
"What's one step you can take?"

"What" is a great word to use for powerful questions

paraphrase what they said, forces you to process it and understand

acknowledge feelings

"3 before me" let 3 people speak before you do if you worry about dominating the conversation

boomerangs: turning convo on yourself. Be wary of it.

Pair more, using powerful questions to teach junior devs

## Finding Responsibility
#### Caleb Thompson

We can be last line of defense against potentially dangerous/unethical practices.

Considering worst case scenario as part of the dev process

## Get Off The Tightrope
#### Tom Stuart

##### The Problem: Trying to do a big thing all at once.
- all the things in your head

##### The Symptoms
- feels constantly stressful
- disappear down rabbit holes, hard to see the edges of the problem
- get too invested in early mistakes
- learn to hate being interrupted/distracted
- takes long time to pick up thread again

##### The Causes
- Eager to make progress
- unsure how big it's going to be
- unsure how far you have to go
- belief that programmers are special

##### Remedies
- story mapping
- use git for clean, clear history
- small, focused commits
- notes and conversations
- practice explaining your train of thought

Meta-strategy: notice the risk, then break it down

##### Why is this important?
- great devs are great at getting off the tightrope

codon.com/get-off-the-tightrope
