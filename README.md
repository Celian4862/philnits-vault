# philnits-vault

A flashcard Obsidian vault containing all past exam questions & explanations for the PhilNITS exam: created to collaboratively prepare for the upcoming PhilNITS exam in a single week.

## Usage

```bash
git clone git@github.com:Luzefiru/philnits-vault.git
```

Then, we open the `philnits-vault` using Obsidian and we can press the `Review flashcards` button on the left ribbon.

### Troubleshooting: Can't Review Previously-Reviewed Flashcards

> [!WARNING]
> The Spaced Repetition plugin will set a timer with a minimum of 1 day before the next time you can review the card.

To work around this, you have to do `CTRL + P > Spaced Repetition: Select a deck to cram` to review all the cards in the deck, ignoring the schedule of previously-reviewed cards.

## Conventions on Creating Flashcards

> [!NOTE]
> To create a new note, do `CTRL + N` and write the name before doing `CTRL + T` to select the `000 Flashcard` template.

Take note of the following labelling conventions.

- note names should correspond to the PDF related to it together with the question number.
  - ie. question #55 `2023A_FE_AM_Questions.pdf` turns into `2023A_FE_AM_55`
- always add a `#category` to the `Category:` section in the metadata heading in order for us to separate the decks.
  - view the list of [[#Available Flashcard Categories]].
  - feel free to add more categories if none of the existing ones cover the topic your question is related to.
    - discuss it between the contributors before adding it.

### Flashcard Format

```md
Created: YYYY-MM-DD HH:mm
Category: #category-from-list
Status: #philnits

# 2024S_FE-A_83

What is the question of the current number?
a) wrong
b) wrong
c) answer
d) wrong
?
c) answer

This is an explanation detailing the different actions or concepts taken to understanding the answer.

You can use LaTeX syntax in between two $$ like $\frac{a_{1}}{x^{2}}$.

You can also copy paste images into the explanation with CTRL + V.

This is the end of the explanation, I hope you now understand why c) is the answer at the first line of the card's back.

## %% ignore this, it's the flashcard terminator %%

# References %% add your references here %%

-
```

- put the correct answer in the FIRST LINE of the flashcard answer.
- the separator for the front & back of the flashcard is the `?` character on a new line.
- the end marker of a flashcard is a `---` separator in a new line.

## Available Flashcard Categories

> [!NOTE]
> Feel free to add more as necessary after discussing with the other flashcard contributors.
>
> - these determine the flashcard deck partitions.

- `#number-systems`
	- binary, decimal, octal, hexadecimal number conversions
- `#operating-systems`
	- CPU scheduling, kernel, functionalities, types of OS
- `#project-management`
	- project management concepts, Scrum, Agile, Waterfall Method
- `#accounting`
	- balance sheets, profit calculation, P/L statements
- `#probability`
	- statistics, probability
- `#cybersecurity`
	- Information Security
- `#systems-architecture`
	- UML2
- `#sets`
	- union, interception, Venn Diagram word problems
- `#digital-logic`
	- Boolean algebra, logic circuits
- `#algorithms`
	- Common algorithms
- `#hardware`
	- Computer architecture and physical components
- `#data-structures`
	- Stacks, Queues, Trees, Graphs
- `#programming`
	- Strings, Integers, Characters, Programming Languages
- `#web-technologies`
	- JavaScript, CSS, Ajax
- `#information-management`
	- Databases, SQL
- `#statistics`
	- Correlations, Regressions
- `#networking`
	- OSI layers, subnetting, network topology, protocols
- `#service-management`
	- ITIL, Service Strategy, IT Service Management, IT Service Delivery & Reliability
- `#math`
	- algebraic problems, basic arithmetic word problems 
- `#software`
	- general software-related topics i.e., graphics software
- `#data-encoding`
	- ways to format, send, and store data, compression, data serialization, decoding
- `#business-administration`
	- business development, analysis, strategy, secretary work
- `#software-testing`
	- test-driven development, terminology, types of tests, test automation
- `#devops`
	- system administration, server provisioning, automated deployment, system integration, containerization
- `#automata-theory`
	- state transitions, automata questions