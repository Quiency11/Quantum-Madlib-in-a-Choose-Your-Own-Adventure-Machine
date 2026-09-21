Guide to Build the
Quantum Madlib
Choose Your Own Adventure Machine
A build-it-yourself guide to turning a few facts into finished documents —
deterministic, local, and out in the open.
by [ your name ]
Layer 1 — Labeling
1.  The Node — the smallest useful thing
A node is the smallest useful piece this whole system is built from. Before anything clever happens, there is just this: a single slot that holds one piece of information.
What makes a node different from an ordinary variable is that it does not care what it holds. A number, A single letter, A whole paragraph, An entire program. A yes, a no, or nothing at all. It is a wildcard: a container with no opinion about its contents.
If you have met the word “token” before, a node is a cousin of it, but looser. A token usually carries rules about what it is allowed to be. A node drops the rules. So do not think of it as a data type. Think of it as an idea: the smallest holdable idea, in whatever form that idea arrives.
And that is the whole foundation. Everything ahead is made of nothing but nodes: every rule, every layer, every report the machine builds. Learn this one thing, and the rest is just nodes, arranged and taught to talk to each other.
 
Figure 1.   A node — one slot, any contents.
From one node to a data set
Several nodes together are a data set. That is all a data set several nodes together, in an interdependent relationship. 
This book will use examples to illustrate concepts. This will occur in several examples, which will progress and mature throughout the book. 
Bellow is an example of a dataset.
In our running example, “person,” “son of Sarah,” “a Marine,” “in Florida,” and “lights off” are five nodes. Together they are one data set.
label a Livingroom lights as a noun a location  
Figure 2.   Several nodes gathered together make a data set.
What code is
Before we go further, plainly: code is a list of instructions a computer follows, one at a time, in order. Nothing more. A person can take in a whole thought at once; a computer cannot computers perform one small step, then the next, then the next therefore a code is that list of steps, written down.

For an example a code could be written to perform a function such as turning off a light. 
One of the most common ways to use language to trigger a code is match keywords. For example, if a code was written to detect “turn the living room lights off,” the list of steps would look something like:
    step 1    read the sentence
    step 2    look for the word "off"
    step 3    look for the word "living_room"
    step 4    turn that light off
But look at what that code just did. It never learned what "living room" means, or that a light is a thing that can be turned off, or that "off" describes a state a light can be in. It matched three words it was told to watch for and ran a fixed action; nothing more. The code doesn't know "living room" names a place, doesn't know "lights" are objects that exist in that place, and doesn't know "off" is something that can happen to them. It has no idea those three words are even related to each other. It worked because you told it exactly which strings to look for in exactly this sentence not because it understood anything about what the sentence meant.
One node, and everything it ignores
So how does an ordinary program “hear” the sentence? Not the way you do. It runs steps 2 and 3 above where normal programs scans for the few words it was built to recognize, “off” and “living_room,” pulls those out, and ignores everything else. That is the whole method: look for the pieces the code knows, drop the rest. It hears a command and nothing more — OFF_LivingRoom — and acts on it. To that program, the entire world was a single node: the light, and the word off. Everything else that arrived with the instruction never registered.
 
Figure 3.   A normal program keeps one node and ignores the rest of the data set.
Which breaks down to the following code. 
    nodes = {
        "action":  "off",
        "target":  "living_room",
        "device":  "lights",
    }
One program, one purpose
An ordinary program is built to do one thing. It reads its data set the same way every run and produces one result. The data set is used statically — the same shape every time — and the program walks over it toward a single fixed purpose: turn the light off. That is the whole job, and it never asks the data to be anything more.
While many people have utilized code to do several incredible things coding philosophy has several limitations. People who use code dogmatically can fall into a trap where they use code prescriptively. One code that solves a single problem. 
The benefit of my method is that codes can be launched from data sets or nodes which means that code can be affected by the data that it is changing. In that way the code is self-correcting. Furthermore, the data can be kept private. The nodes do not have to go anywhere. Nodes sit locally, on the user's own machine, read only by the program that needs them — nothing leaves. Using this will give you determinative AI like results which can instantaneously write auditable reports. Since the whole data set is kept, still and private, it can be picked up again later. This is because my method does not fall into the same traps as code. Before I go on to describe my method lets define how normal computer programs fail to differentiate my system.
What most machines throw away
In the light example above look what was actually said. The full statement is “Livingroom lights off.” This is how code treats data, a static thing gives directions this is more deductive reasoning. 
However, there is a full dataset with a bunch of information that is not being used. Potentially, if people decide the code could read. 
person, wants to turn off Livingroom light
son of Sarah, wants to turn off Livingroom light
a Retired Marine, wants to turn off Livingroom light
or a person standing in Florida, wants to turn off Livingroom light
Notice in the above each subject is turning the living room lights off. However, we don’t use that data of which person wants to shut off the Livingroom light as it does not help us achieve the purpose of turning off the light. The ordinary program threw almost the whole data set in the bin and kept one node. 
Why? Because the ordinary program was only ever built to read a single node out of the whole set. That is the quiet waste at the center of most computing: signals arrive rich and get used poor. The information is right there, who, from where, in what role, under what conditions, and the machine looks at one field and forgets the rest ever existed.
The Quantum Madlib Choose Your Own Adventure Machine (hereafter the Quantum) does the opposite. It keeps the whole data set present and still. Nothing is discarded. The function reaches in and takes only what the task in front of it needs, the light does not need to know the operator is the son of someone named Sarah to function, but the data does not vanish during the execution of the code. It waits, in full, in case the next question needs it.

Layer One — Labeling
Labeling is the process of quantifying and understanding a question. Let's set programming aside and treat programming logic as a logic game.
Suppose we have a person with the following qualities:
•	Son of Sarah
•	Retired Marine
•	Currently in Florida
Each node is a descriptor that describes an aspect of a person. Nodes are useful in some situations but not others.
For example, if we ask "What species is the subject in question?", the fact that the [subject] is "in Florida" does not answer it as a current location tells us nothing about species. The node "son of Sarah" comes closer, since it implies the [subject] is a offspring of Sarah, but this is not definitive: plenty of animals have human names. The strongest answer would come from a node stating directly that the [subject] is a "person."
Written out, the exercise reads:
What species is the subject in question?
A person.
For a computer to hold context between a question and a response, some labeling must occur. Without that logic memorialized in code, a computer cannot tell the three variables apart. This is foundational to coding, because labels tell a program how to handle its variables. Below is a method for weighing them. As in coding, the ability to weigh variables is foundational to generating good phrases; which is why labeling is a core skill.
Labeling is the first step of the process: a method of quantifying words so your computer and program better understand how to handle the words they are given. Labeling happens at the node level.
Key for the below:
•	[Purpose] = words that help resolve the purpose of the node
•	(Subject) = the subject node
•	"Preposition" = a word showing a relationship involving the noun
In the question above, we posed: "[What] "species" is the (subject in question)." Any number of questions can be asked to develop labels for a node. A person can change a single word in the same question.
TIP: Think of the question as a Mad Lib.
Similar questions could read:
•	[What] "age" is the (subject in question)
•	[What] "nationality" is the (subject in question)
•	[What] "kind of person" is the (subject in question)
•	[What] "species" is the (subject in question)
This concept is very important for later lessons.
What is labelling 
Labeling occurs at the node level however the skill is important as later nodes will be used to measure the distance between other nodes node — node, sentence, and code — and that distance creates a signal. The strength of the signal determines how well the node answers a question. The answer can then be used in unique ways. 
Below, I introduce three forms of the same phrase: sentence, code, and abbreviated (shorthand) case, and treat them as equivalents. They aren't identical in form, but they represent the same underlying idea three different ways. Looking at each form side by side shows how to label a node.  
One of the clearest coding signals is a rule like: if button pressed, then "turn off the Living Room light." The shorthand version of this might be written as:
buttonpress = OFFliving_roomlight
That shorthand — OFFliving_roomlight — is really a command carrying three signals at once:
    nodes = {
        "action" or _____:  "off",
        "target" or (subject of the question):  "living_room",
        "device type" or [] :  "lights",
    }
The code above and the sentence "turn off Living Room lights" are clues to what the writer is actually trying to communicate. To see that relationship, we label the sentence by measuring how closely it lines up with the code.
For example, if we were to read the makeup of the sentence “Turn off the Livingroom light”. We know that its coding equivalent would brake each word down and label an action = {“action":  "off”, “target":  "living_room”, “device":  "lights",}. At first glance they appear as unrelated idea sbut if you look at the function of the code vrs the function of the sentence one can understand surprising comparisons.
Sentence case: Turn off the Livingroom light
•	  Verb: Turn (Imperative verb / action)
•	  Noun (Phrase): Living room lights (Direct object)
•	  Particle / Adverb: On (Phrasal verb particle completing "turn off", or predicate specifying state)
 And 
Code case: Off_LivingRoomLight.py
action: "turn_off" target: { "location": "Living room", "device_type": "light" } state: "off"
Recall the earlier point that a computer doesn't actually understand the meaning of words. As an exercise, imagine we don't know what "turn off Living Room lights" means.
If you didn't know the sentence's meaning, you could still infer from the code that "Living room" is a location. Likewise, the word "light" has many possible senses — light speed, sunlight, lightweight — but the code equivalent narrows it immediately to a light bulb. 
Meanwhile, the sentence form tells us which lights: not lights in general, but the specific set in the living room. The sentence gets stronger because of the descriptors carried in the code, and the code becomes more legible to non-coders because of the sentence's natural phrasing. Each form sharpens the other.
This means we need to group all three forms together:
nodes (OFF living_roomlight)= “action":  "off”
Word in sentence living_room ="Noun”, “target"
Coded version = "device type" or [] :  "lights",
By "grouping them together," I mean treating the sentence form, the node form, and the program form as structural equivalents — three different encodings of the same concept: turn off the lights. Because they're grouped, a label or assumption drawn from one form can be carried over and applied to another. For example:
All three statements are equivalents. So, at the node layer, "off" = "living_room" = "lights" not because they mean the same thing in isolation, but because they're three parallel encodings of a singlualr concept. Building strong labels and choosing precise language is what makes the system stronger.
Once you see these statements as equivalent, you can see how a sentence can be coded and abbreviated. This is where things get genuinely interesting: "Living room lights" can now be labeled simultaneously as a noun, as a location, and as shorthand for the concept of a living room.
In short: labeling is the act of measuring how closely a sentence lines up with its code equivalent, and recording that relationship in a node. A sentence and its code are two different encodings of the same concept, and the node is the compressed symbol that results from tying them together. Because they're tied together, you can start from any one of the three and recover the other two: the sentence can be coded, the code can be written back out as a sentence, and either one can be compressed down to a node. The sentence carries the natural-language meaning. The code fixes that meaning into a precise, structured form. The node is the shorthand symbol that stands in for both.
Notice: the example above involves code. This is because the audience who are most likely to understand the concept are coders. However, my first prototype of the model started out with no code and just used English. One does not need code to build Quantum. This is important as the inputs can interact with code, such as the way I described above, however most of the machine is sentence strings interacting with one another. However, it is good that it can bridge written language and code as it can use either input to weigh to produce language. It's important to know that labeling is not the act of putting labels on words. This can occur more conceptually, and as one advance in the system, one can visualize the word/word sets in nodes and you label inherently. Labeling can occur on the first or second layer of the system. The above was an explanation of labeling on the first part of the system, as it was the easiest. Once you are done labeling, one must decide what to do with the data, which is what we will explore in the next chapter.
Chapter Two: What To Do with The Data
So, the last chapter was a long explanation of how to create a labeled database. A node set with labels is, ultimately, a database. That's an oversimplification of what's above, but the criticism holds. In an effort not to repeat simple context for the coder audience, this book will actually ask coders, and anyone already familiar with these concepts, to skip certain sections. Below is an explanation of boolean values.
 If you already know this, jump to [Using Boolean Values]
Boolean Values
A boolean is a value that can only be one of two things: true or false. Nothing in between, nothing else allowed.
That sounds almost too simple to explain, but it matters here because booleans are what let a node decide something. Recall the light example: buttonpress = OFFliving_roomlight. Behind that shorthand is a question the system is answering: is the button pressed, or isn't it? That question only has two possible answers, which makes it a boolean.
Sentence case: Is the button pressed?
•	Answer: Yes / No
Code case:
button_pressed: true
or
button_pressed: false
That's the whole concept. But the reason it matters for labeling is this: once a piece of a sentence can be reduced to a true/false question, it stops being fuzzy. "Turn off the Living Room light" isn't just a request, it's a set of conditions, and each condition can be checked as true or false. Is the target the living room? True. Is the device a light? True. Is the desired state "off"? True. Every one of those checks is a boolean, and a node is really just a bundle of these checks bound together.
This is what lets the system move from language, which is ambiguous, to something a machine can act on without guessing: the sentence gets broken down into a series of true/false checks, and those checks are what the node actually stores.
Using Boolean Values
If a boolean value is just a yes-or-no question, there are still interesting ways to use it. A normal piece of code might ask "is a button pressed?" and hard-code each action to that answer. In shorthand, that boolean might look like this:
buttonpress = OFFliving_roomlight
And written out as a program:
Off_LivingRoomLight.py
# If living room button is pressed:

ROOM_LIGHT_OFF_INTENTS: dict[str, LightOffIntent] = {
    "living_room": {
        "action": "turn_off",
        "target": {"location": "Living room", "device_type": "light"},
        "state": "off",
    },
}
Here, if the button is pressed, the light turns off. But imagine there are several rooms, each with its own light. The amount of code needed to express every room grows with each one you add:
livingbuttonpress = OFFliving_roomlight
bathbuttonpress   = OFFbath_roomlight
bedbuttonpress    = OFFbed_roomlight
Off_HouseLights.py
# If living room button is pressed:

ROOM_LIGHT_OFF_INTENTS: dict[str, LightOffIntent] = {
    "living_room": {
        "action": "turn_off",
        "target": {"location": "Living room", "device_type": "light"},
        "state": "off",
    },

# If bathroom button is pressed:

    "bath_room": {
        "action": "turn_off",
        "target": {"location": "Bath room", "device_type": "light"},
        "state": "off",
    },

# If bedroom button is pressed:

    "bed_room": {
        "action": "turn_off",
        "target": {"location": "Bed room", "device_type": "light"},
        "state": "off",
    },
    ...
}
Last, imagine a third version of this code that takes everything above and treats the button labels as variants of one another, so that pressing any one of them loads the same underlying pattern.
Quantum_Lights.py
# If living room, bath room, or bed room button is pressed:

if state_change(room) is pressed:
    room = livingbuttonpress | bathbuttonpress | bedbuttonpress

    load(
        Off_LivingRoomLight.py,
        Off_BathRoomLight.py,
        Off_BedRoomLight.py,
    )
Something significant just happened, and for some readers it won't be obvious from the code alone. So, for anyone not yet initiated: the trigger changed. Not the trigger itself, but how the trigger is compiled. The first version is like a direct line telephone, where each button is wired to a single output; a phone that can only ever call one set of code.
Show Image
The second version waits for a button to be pressed, and once one is, it reads which button it was and uses the room variable to decide which program to call. This is closer to dialing a number on a telephone: the phone itself doesn't change, but the number you dial does, and that number decides which line answers. If the room variable changes, the program that responds changes with it.
[add a rotary/dial telephone graphic here]
Aside: node vs. state. Look closely at what room is doing in that code. Before any button is pressed, room is a node: an open slot that could hold living_room, bath_room, bed_room, or nothing at all. It has no settled value yet, just the possibility of one. The moment a button is pressed, state_change(room) fires, and for as long as that button is held, room stops being an open node and becomes a state: a settled, boolean-backed fact that load() reads to decide which file to call. When the button is released, room reverts to a node again, empty, waiting for the next press.
How long a state holds doesn't come from the definition of "state" itself, it comes from how many constraints are placed on it. This one is brief on purpose: nothing in the system needs room to stay resolved once the light has been told what to do, so it's allowed to lapse the moment the button is released. Other states, under different constraints, can hold indefinitely. The room example is simply a case where brevity is correct.
Using Boolean Values in English
Remember earlier, the thought experiment about identifying features of a person. Suppose we have a person with the following qualities:
•	Son of Sarah
•	Retired Marine
•	Currently in Florida
The keen of eye may have noticed that within this exercise, we never named the person in question. That was deliberate, to illustrate how powerful names can be.

Quiency Delfinki
Imagine for a second you're writing to a friend named Quiency. This is an informal letter, and you correspond with him regularly. Below are two letter greetings, with two different introductions. Take each one and imagine you're writing to both individuals. The beginning of the letters reads as such:
Dear Quiency Delfinki, ...
Dear Dr. Quiency Delfinki, ...
For me, the letter to Dr. Quiency was more formal. There may have been a nod to a shared joke in each, but the delivery would be different. The point isn't that doctors are treated differently than ordinary people in society, but that a single variable can change the way you interact with an idea.
Putting the concepts together
So far, we've been working toward two seemingly unrelated ideas, which turn out to be different components of the same thing: nodes, which are labeled, and yes/no style computer code that can make calls to other computer code.
These two ideas are, in fact, the foundational way to write and interact with writing. Nodes are any values, and boolean values are codes triggered by a yes/no binary. If we go back to the example above (writing a letter to Dr. Quiency), we can use the "Dr." variable to inform the tenor of the letter.
You may pose a different set of questions to a doctor than to someone without that title. If you didn't know your friend Quiency that well, you might ask a different set of questions knowing the single fact that he's a doctor, compared to not knowing that fact at all. Here's an example:
Dear Quiency Delfinki, ...
•	How are you?
•	How's our mutual friend?
•	Did you see any movies you liked recently?
Dear Dr. Quiency Delfinki, ...
•	What's your doctorate in?
•	Where did you go to undergrad?
•	Did you see any movies you liked recently?
Here, "Doctor" is a variable that informs the rest of the conversation. This variable can be labeled a credential, and it's used just before a name. So a person can look at any credential preceding a name and use it to decide what questions to ask, or how to shift the language in a template they already have. In this example, the node MD, DO, PhD, or any other credential can change the sentences that follow the name. This is like the code from before that read the room variable to decide which room to interact with, except instead of a room, these words are interacting with other words.
States
2.2 States
States are the quantum element of the quantum machine. Nodes were called "everything" in the chapter above because they represent millions of small signals we give one another in order to understand and communicate simple ideas. States are something different. A state is what a node becomes once two things are true about it: it's been weighted as an important enough signal, and it's answerable as a boolean.
In this example, we started with the idea of Quiency having a "Dr." title, and by the end we concluded that his title was important, and that fact informed the rest of the text. Here the state is pivotal, the completion of the letter is informed by Quiency being a doctor. Once we've established that Quiency is a doctor, we can have the Quantum machine remember it, and "Quiency is a doctor" becomes a data point the system can draw on to produce other outputs.
In our example, concluding that Quiency is a doctor changed what questions we'd write to him. But the reverse also holds. Asking someone you don't know is a doctor, "What's your doctorate in?" doesn't make logical sense, so the absence of a "Dr." title on its own is a weak signal, not a no. Just because someone doesn't use the title informally doesn't mean they aren't a doctor.
This is where the third boolean answer matters. So far, we've been using the traditional idea of a boolean, a value that resolves to true or false, full stop. That's the correct dictionary definition, and it's not one this book disputes. But my system asks more of a boolean than that. It needs to reveal a third way of using it: alongside yes and no, a boolean here can also resolve to not present (null). To be clear, this isn't a claim about what a boolean is in computer science generally. It's an extension built for this system specifically, a signal that's been withheld rather than one that's simply missing. Until we're told otherwise, that's the state Quiency's title occupies, not false, just withheld. If we later learn Quiency is a doctor, the state resolves and that information becomes available to inform everything downstream.
The absence of a title means we can treat Quiency as any other person for now. Or the signal may not matter at all, the way our "turn off the Living Room light" example doesn't care how educated the person asking is. What matters is that the signals are chosen as the determinative elements for the task, you're giving the system.
The Structure of a State
We've already established what a state is: a node that's been weighted, and its outcome is an important enough signal that it has structural relevance. Here's what that looks like as a structure, not just a definition.
The label informs what the node is. The signal quantifies how important a node is. The weight tells us the sum of the calculation. Node + Node = State. A state can resolve to yes and still be too minor to change anything downstream, and a state that resolves to not present can matter enormously, if the withholding itself is the signal.
Temporary States, Compared to Permanent Ones
Go back to the button. room becomes a state the instant a button is pressed, living_room, bath_room, or bed_room, resolved, weighted, and acted on. Then the button is released and the state is gone. Nothing kept it. Nothing needed to.
That's a temporary state, temporary not because it only fires once, but because nothing downstream depends on it to determine what another node becomes. This is because the program only requires a single action to execute. Once the button is pressed, the light turns off, and the state can drop to a zero value until it's needed again to run the same loop.
The signal underneath it, a button being pressed, is fickle by nature, so the state is fickle. The state does its work and dissolves. Most individual button presses never need to graduate into their own remembered state, there's no reason for the system to remember that the living room light was pressed at 4:12 PM, so it doesn't.
The doctor example runs differently. Once "Quiency is a doctor" resolves, the system doesn't need to re-ask the question every time it writes to him. It keeps the answer. That's a permanent state, because another node depends on it to resolve: the set of questions the letter goes on to ask can't be decided until this state is resolved. And unlike the button, a credential isn't fickle, it doesn't flip back and forth, so it's safe for another node to build on top of it. States don't have to have this permanence; the only requirement of a permanent state is that it's mostly resolved and it's a settled fact. Facts can change, but a permanent fact, a strong assumption that other assumptions can rely on, is a permanent state.
The difference between a temporary and a permanent state isn't in the design, but rather the implementation. Structurally, temporary and permanent states are identical: node, label, signal, weight. The difference is in what the state is doing for the rest of the system, and how solid the assumption underneath it is. A state that only serves its own job, sitting on a signal which can change, is temporary. A state that another node depends on to resolve, sitting on a signal unlikely to change, is permanent. States don't require permanence in the strict sense, nothing in language is ever fully settled, that's simply how English works. The only requirement of a permanent state is that it's almost certainly resolved: stable enough that other parts of the system can safely build on top of it. A permanent state isn't a fact. It's a strong enough assumption that other assumptions are willing to rely on it. Duration isn't a constraint handed to the state from outside, it's a consequence of how much the rest of the system leans on it, and how fickle the assumption or assumptions underneath it actually is.
So, What Is to Be Done
A resolved state doesn't do anything by itself. It's a settled fact sitting still, labeled, answered, weighted, and waiting. room resolves to living_room, "Quiency is a doctor" resolves to yes, and both just sit there until something asks them a question.
That's the actual gap between what this chapter has built and what comes next. Labeling gets you a node. Weighting and boolean resolution get you a state. But a warehouse of correctly resolved states still isn't writing. Something has to take a state, match it against what's actually being asked, and turn it into the words that get produced. That matching is its own layer, distinct from labeling and distinct from resolution, and it's where the book goes next.
















Part Two — Question and Answer
Chapter Three: All About Madlib
Before, we get to what a Madlib is it is worth describing out loud what we are building. Quantum is a deterministic, fully local, fully auditable language engine that generates text the way a compiler generates code, not by guessing the next word, but by resolving labeled meaning through explicit, inspectable logic. It's polymorphic and deterministic: the same underlying structure can take different shapes depending on context, but every shape it takes is traceable and repeatable, not probabilistic. It runs on a fraction of the compute a model of comparable output would need, because there's no training pass to fund, just resolution against a fixed rule set. No black box, no weights you can't read. The name says what it does: Quantum Madlib Choose Your Own Adventure Machine, because a single labeled node can resolve into many possible states depending on context, because output is built by filling structured slots with those resolved values, and because different variables load different sentences depending on the data set, and on which nodes and states the machine's author decided should determine the branch. The system runs automatically once it's built. The grammar it runs on is what's painstakingly hard-coded, rule by rule, ahead of time. However, because AI is prevalent you can run a finished machine through AI or Grammarly and get a coherent factual output, this is not necessary but its an option. Using an AI, however ruins the always local, completely confidential, side of this, but if the data is not sensitive you can always replace this final step with AI editing. 
What a Mad Lib Actually Is
You already know what a Mad Lib is, even if you've never called it that. Someone hands you a story with holes cut into it. "The [ADJECTIVE] [NOUN] jumped over the [ADJECTIVE] [NOUN]." You supply words without seeing the sentence they're going into, and the fun is in the mismatch: the sentence doesn't care what you put in the blank, it just runs with it.
That's the entire mechanism. A Mad Lib is a sentence with open slots, and each slot is typed, it wants a noun, a verb, an adjective, a specific kind of word, but once that type is satisfied, the slot doesn't check any further. Any noun fits the noun slot. The sentence has no opinion beyond the category.
Our system borrows that shape and removes the part that made it fun: the not-caring. In a traditional Mad Lib, a blank will take anything that fits its type, that's the whole joke. In a Quantum Madlib, a blank is a node, and a node is not indifferent to what fills it. It's waiting on a state.
Here's what that looks like in practice.
Template:
Turn [state] the [location] [device].
Nodes filling the blanks:
Blank	Node	Resolved value
[state]	action	off
[location]	target	Living room
[device]	device_type	light
Result:
Turn off the Living room light.
The party-game Mad Lib fills its blanks with whatever the player says, unconstrained, funny because it's arbitrary. Yours fills its blanks with whatever the association between nodes has resolved into a state, constrained, and traceable, whether the result reads as sense or nonsense. It isn't guaranteeing normal-sounding output. It's guaranteeing that whatever comes out was determined on purpose, not by chance.
Auto Templating
To avoid sounding too mystical, we'll start with the easiest equivalent of what we're doing: auto templating. Auto templating is Mad Libs in their purest, most sensible form. I began this system writing reports for banks, so I'll use a bank form as the example, one that can be auto-filled using nodes, states, and outputs.
Template:
My name is [Full Name], and I was born on [Date of Birth]. I currently live at [Address], and I'm requesting to open a [Account Type] account, with a Social Security Number on file of [SSN].
Nodes, filled with Quiency's data:
[Full Name] → Dr. Quiency Delfinki
[Date of Birth] → April 12th, 1990
[Address] → 142 Birchwood Lane
[Account Type] → savings
[SSN] → 123-45-6789
[Occupation] → Police Officer
[Years Employed] → ten years
Output:
My name is Dr. Quiency Delfinki, and I was born on April 12th, 1990. I currently live at 142 Birchwood Lane, and I'm requesting to open a savings account, with a Social Security Number on file of 123-45-6789. I've worked as a Police Officer for ten years.
Nothing about the template changed, the same fixed structure that produced Jane Doe's application just produced Quiency's, because the form doesn't know or care who's filling it. Swap the nodes, get a different person, same machine.
Jane Doe's dataset:
[Full Name] → Jane Doe
[Date of Birth] → June 16th, 1995
[Address] → 142 Birchwood Lane
[Account Type] → savings
[SSN] → 153-45-6769
[Occupation] → not present
[Years Employed] → not present
My name is Jane Doe, and I was born on June 16th, 1995. I currently live at 142 Birchwood Lane, and I'm requesting to open a savings account, with a Social Security Number on file of 153-45-6769. 
Here, Occupation and Years Employed both resolve as not present, not unresolved, not blank by accident, but withheld or simply unknown, and treated as a real answer rather than a missing one. Since the template's final sentence exists to state occupation and tenure together, and both of the nodes it depends on are null, the template doesn't write a broken half-sentence guessing at what it doesn't have. It drops the sentence entirely. The output for Jane ends where her data ends: her name, birth date, address, and the account she's requesting, full stop, no occupation sentence at all. Same template that produced Quiency's four-sentence application produces Jane's three-sentence one, not because the template changed, but because two of the nodes it was checking for came back null.
Building a Quantum Madlib
Now put the two ideas together. A Quantum Madlib is a sentence full of slots, same as the traditional kind, except every slot is a node waiting on a state, and it's that state's weight that decides whether it's allowed to fill the slot at all.
Take this report above an “Application for Banking”, know that an application for banking requires a different set of variables for a person as compared to a business. 
Nodes, filled with Quiency's data:
[Business Name] → Quiency Delfinki L.L.C.
[Date Founded] → April 12th, 2013
[Address] → 18742 Woodworm Lane
[Account Type] → Business Checking
[EIN] → 12-3456789
[Business Type] → Coroner's Office
[Years in Operation] → ten years
We are going to put that into the same template as the customer one we made for Dr. Quiency Delfinki
My name is [Quiency Delfinki L.L.C.], and I was born on [April 12th, 1990]. I currently live at [18742 Woodworm Lane], and I'm requesting to open a [Business Checking] account, with a Social Security Number on file of [12-3456789].
Notice that it doesn’t work. The writing no longer makes sense. A company is not “born”, companies don’t live places. The template now turns in and anthrophamorphic inaccurate statement.
The way my system resolves this is to check for a single signal. “Quiency Delfinki L.L.C.”, here the L.L.C. becomes the first node that we weigh.. L.L.C’s are special in English because they are company formations. Here the rarely shows up in English unless it refers to a company. Because of this it is a “permanent state is that it's almost certainly resolved”. It is such a good signal that it can change the rest of the output. 
So if name ends in L.L.C. then company. if company than upload company template. 
[Business Name] → Quiency Delfinki L.L.C.
[Date Founded] → April 12th, 2013
[Address] → 18742 Woodworm Lane
[Account Type] → Business Checking
[EIN] → 12-3456789
[Business Type] → Coroner's Office
[Years in Operation] → ten years
[State of Incorporation] Delaware 
Is LLC = Yes then load template 2 
The company name is [Business Name], which is a fully registered [State of Incorporation] company founded in [Date Founded]. Within a registered address [Address], and I'm requesting to open a [Account Type] account, with an EIN Number on file of [EIN].
Auto templated to read
The company name is [Quiency Delfinki L.L.C.], which is a fully registered Deleware company founded in [April 12th, 2013]. With a registered address of [18742 Woodworm Lane], and I'm requesting to open a [Business Checking] account, with an EIN Number on file of [12-3456789].
So what happens when the rule fails? We write new rules. So the L.L.C, rule may need to be the L.L.C., Inc., L.P. rule. This is the same rule iteratively which covers many formations of companies. If we have a business, which has an EIN number, but not a LLC name then we can also use this as a state which defines what template to swap out.
Similarly, a person may have a name that ends in L.L.C. which gives a false signal to load a second template. However, this is resolved with a recursive loop. So the best signal for formation I have found is not actually the name, but the SSN/EIN. Here the Ein and social 12-3456789 vrs 123-45-6789 to see which template to use. While L.L.C. is a permeant state, I use other nodes to double check this state and any edge cases I program them in weights as I encounter them. So, the stranger situation that the program sees the stronger the weights get. Going through this process has exposed some very niche stations and helped me understand them
Explanation of Recursive Permeant States 
There are three issues which have been pointed out to me which need to be resolved before we continue. These issues are obvious to me but they need explaining to others. I will start with an explanation of each one and if you can take it at face value and understand the concepts therein. skip the section. If you need help or have trouble understanding a concept go to the explanation. Question 2 explanation should be read.
1.	The abbreviated form “Doctor” was a perment state in the letter example but now its not even listed as a node. 
Doctor is a node but is not a good signal for the example at hand. It needs to be a node later as the information maybe important in determining if the bank should accept the application. However, it is not a necessary node for the task and therefore not used as a perment state. 
2.	LLC was given as an example as a permanent state. But then it changed immediately by the second node. Does the inclusion of the second node make the state a temporary state? 
So the weights I have been referring to in the abstract are actual weights. Here: "(Boolean test) If node = "L.L.C." or "LLC" then insert template B." In this example the Boolean test is the weight. However, this is an untrue statement because sometimes parents name their children LLC. So we need to write a second Boolean value, however if Social/EIN node = Social or EIN, take form of --*** or **-*******, then override the first rule.
The state is always permanent, the weights changed.
3.	Recursion is a coding cardinal sin. 
Recursive code is messy hard to read and confuses most code. Its illegible and a signal of someone who is novice or that the code is wrong. While recursiveness and sanity checks are rare in Quantum the process creates stronger weights and node pairs and therefore, it is not considered as fopa as in traditional code.
4.	Explanation 2 has a nested Boolean in its not an arithmetic problem it’s bad code
Its true, the weights could be written here are an addition problem or a nested Boolean. I have a reason why I wrote it as an addition problem, but it wont be addressed until the “weights” chapter.
Question One Exploitation. 
One may wonder why Doctor got a node in the letter machine but not in this one. It's because Doctor is a good node here too, it just never graduates to a state, because the presence of "Doctor" doesn't determine any other variable down the line. None of this makes "Dr." a bad signal, even here. Banks build entire divisions around physician clients specifically because the credential predicts income, education, even life expectancy, its genuinely valuable signal, inside banking, for plenty of banking questions. What makes it useless here is narrower than domain: this particular task is resolving person versus legal entity. A signal's weight was never a property of the word, or even of the domain. It's a property of the relationship between the word and the exact question being resolved. Ask a different question of the same machine, and the same word can go from worthless to load-bearing without anything else changing.
Question Two Exploitation. 
Go back to the LLC signal from a few pages ago. "Ends in LLC" worked, right up until it didn't, a person whose name happened to end in "LLC" would have broken it outright. That's not a coincidence to patch over quietly. It's the ceiling every fixed, declared signal eventually hits: at some point, one signal alone isn't enough, and something has to combine it with another one.
Up to now, weight's been described as a property a state carries, how much it matters. True, but incomplete. A weight isn't just declared once and left alone. It's supervised: nodes are the workers doing the raw labor of carrying signal, and weight is what governs how loud each worker's signal gets to be when several of them are talking at once.
Here's what that looked like, worked in full, for the LLC case:
[LLC-name-state]:    +1   if the name ends in "LLC"
                       0   otherwise

[SSN-format-state]:  −2   if a nine-digit SSN format is detected
                       0   otherwise

X = [LLC-name-state] + [SSN-format-state]
Quiency Delfinki LLC, EIN on file: +1 + 0 = +1 → Company.
A person whose name happens to end in "LLC," SSN on file: +1 + (−2) = −1 → Human, the name-signal gets overridden.
Weight isn't mysticism. It's a constraint, it narrows a word down from every sense it could carry to the one that actually applies here. The SSN-format signal carries a bigger number because it's the stronger signal. Nothing more complicated than that is happening.
X here is used as the sum of the weights. Here a weight "LLC" was combined with "SSN/EIN" to add nodes together to create a combined state. Here the state [Person] or [Company] always determined what format preceded the sentence, by loading different templates, the difference here is the calculus of the weight changed, not the nature of the state (temporary or permanent). So if you take the comment before, a state is a measure of if the weight resolves a sentence. That specifically is "X," the sum is not the presence, absence, of the state. It's if the state has weights strong enough to say specifically other variables can rely on its signal. More information strengthens the "X" as they add additional constraints.
Once X resolves, "Company," in this case, it doesn't just sit there as a final answer. It can re-enter the system as a new node in its own right, one more piece of resolved signal, available to the next calculation. Once "Company" resolves, it becomes an input to the next question down the line: which template loads, whether State of Incorporation needs checking, whether Business Type gets asked for at all. Each of those downstream questions runs its own small weighted calculation, and each of those can produce an X that feeds the one after it.
Question Three Exploitation. 
If "recursive" made you flinch, that instinct is correct, and worth keeping. Most of the time, a function calling itself is a sign something's wrong: a missing base case, a broken exit condition, a bug wearing the costume of an architecture. That reflex has saved a lot of production systems from runaway loops and stack overflows. It should stay switched on.
Here's the actual function:
def resolve(node, context):
    x = weigh(node, context)          # X = [node] (operator) [node]
    if x.is_final(context):
        return x
    return resolve(x, context)        # X becomes the next input
x.is_final(context) is the hard-coded exit condition. It stops the recursion the moment a weight is decisive enough that nothing downstream needs to re-ask the question. Without a termination condition, there's no recursion, just an infinite loop, and this function has one, written directly into the code. Tree traversal, parsing, and compilers all run on this same pattern: recursion with a bounded number of steps, an exit condition sitting in the code itself, checkable by anyone reading it.
What is a Paragraph
This is the actual payoff of "Question and Answer." Before a machine can search its own resolved states for an answer, someone has to ask the right questions of the writing in the first place. That's what this section is: not a grammar lesson bolted onto the chapter, but the human version of the exact mechanism the machine runs, asked by hand, before any of it gets coded.
This is going to piss a bunch of people off, but do you remember 8th grade English? These rules of a bygone era are actually important for this. Unfortunately, to create Quantum one must have at least a basic understanding of sentence theory and grammar. For those paying attention, I write poorly, so the amount of grammar and spelling you need is nominal.
None the less, the basic tenets of writing theory are the basic tenets of the machine. These go interchangeably, and a basic understanding of how and why language is written is a prerequisite to building a quantum loop. (A quantum loop is a sentence within Quantum.)
So: what's the purpose of what you're writing? What are the themes? Does your paragraph have an introductory phrase? These aren't just helpful writing prompts. They're the Ask half of Ask and Answer, questions posed against a piece of writing, and whatever answers them is what decides which template, which form, the sentence ends up taking.
Just like writing, the form of the sentences must adhere to the intended audience. The templates you create should adhere to the method and writing style meant for the audience. Conforming to a template is actually a large part of the question. These basic literary devices help inform a rough shape of how you will write the polymorphic system. Writing form is the main constraint, a jar that holds the liquid nodes of basic parlance.
Once you have an abstract idea, you can build the introductory phrase and try to tie a template to a single permanent node. In this process it's helpful to think about 8th grade you, and the questions your teacher would ask: what are the themes? What's your voice? What's the purpose of this sentence? Your 8th grade teacher was already asking Ask and Answer questions. She just called it "theme" and "purpose" our ideas build those ideas tho, one must be more aware of theme and purpose in a shifting system as they define the systems parameters. 
Then communicate your words in the most basic form. Full template, make the words ugly and practical, make the writing clinical and sterile.
You are building a labyrinth of shifting language, the beauty is in the design, the architectural simplicity. Think of your sentence as a shifting Rubik's cube changing every second, weighing each possibility, until the weights give way to the entropy of human communication, and must be rebuilt.
In the beginning it's boring work. It's difficult to get language right, a beautiful output to your audience, and a polymorphic system, all at once. But it's not impossible, and you can create truly beautiful things in the shifting system, you're encouraged to. For now, just keep things simple, the architecture itself is difficult enough. When you're stuck, ask what this sentence's job is, and if it has no job, remove it. Nodes too, everyone earns a seat.
Every node in this book so far has earned its seat, action, target, device, credential, theme, but "earning a seat" has been carrying more weight than it's actually explained. A state has always had three parts: a label, a signal, and a weight, and the LLC/SSN example already showed one plausible version of what that weight looks like as arithmetic, +1 for a name ending in "LLC," −2 for an SSN format strong enough to override it. What it didn't show is where numbers like that actually come from, why one signal outweighs another, how weight gets assigned in the first place, not just used once it's already been decided. That's what comes next.












Layer 3: Output and Comparison
Before we get into weights, I wanted to cleanly address why I call Quantum a machine and not prompting, or a paragraph, or code. This is because the Quantum method produces an output that is decided by the author. Quantum doesn't only produce code, it produces words and answers too. That's not because it has a separate function for each. Code, a prompt for an LLM, a plain sentence, they're all built from the same raw material, words, numbers, symbols, so whichever shape the output takes is a condition of the language it's made of, not a special capability Quantum has to switch on. The whole thing is limited just by your information. Because of this, the size of a Quantum machine can be small, a single templated variable, or it can be large enough to serve as the basis for an operating system or a home assistant. What's important is that I try to leave room for the possibilities of Quantum, and I start that by attempting to use language fitting of the concept.
Chapter 4: Word Theory and Steven Pinker
The Stuff of Thought is a book by Steven Pinker, who is my favorite linguist. I only know two linguists, but he is my favorite. He wrote this book, which is an amazing work, and it helped me describe part of my system. The words are used in an incorrect context here, based on my ignorance of linguistics, but the heart of an explanation helps me give voice to something I've done subconsciously for years while building Quantum. I hope it helps you too.
In The Stuff of Thought, Steven Pinker describes polysemy (or polysemous words) and monosemy (or monosemous words):
•	Polysemy / Polysemous: Refers to a single word that has multiple related meanings or senses. For example, the word "head" can refer to the physical body part, the top of a page, or the leader of an organization.
•	Monosemy / Monosemous: Refers to a word that has only one distinct, unambiguous meaning, common in highly technical or scientific vocabulary, such as "deoxyribonucleic acid" or "laser."
Note: monosemantic/polysemantic were also considered as a naming convention, but Quantum works in a predetermined topic space, so nodes never have the chance to affect Quantum in more than one subject matter at once.
The reason polysemous/monosemous ideas matter is that in choosing whether a node is permanent or temporary, one must decide how strong a signal is. When writing sentences, choosing a polysemous signal as a permanent node is a bad idea, since the meaning of the word can get muddled. A monosemous signal, on the other hand, becomes a powerful predictor of what's meant, because it can only be interpreted one way. Therefore, learning how to turn polysemous words into monosemous ones is a useful skill.
Tip: If you're writing for a job, corporate jargon provides very strong signals.
This is where my admitted ignorance loses any linguists reading. A monosemous node can be made by combining several nodes together. While a single word may do a poor job explaining a concept, a group of two to five words can give an incredibly specific description. Let me demonstrate the theory: single state, "my friend [Michael]." Combined state, "my friend [Michael] [Jackson]." Lastly, combined states, "my [departed] [friend] and [pop legend] [Michael Jackson]." These three descriptions went from everyone, to some people, to a very specific person, with very little change. Therefore, I posit a polysemous signal can become a monosemous one, given the correct conditions.
[Footnote] This is where I lose linguists, and I want to name why plainly: not because the idea is wrong, but because I'm borrowing authority, I'm not credentialed to wield. I don't know why the field draws the distinctions it draws, only that it does, and a reader who's spent a career on this will feel that gap the moment I reach for a word like "polysemous" and use it slightly wrong. I'm not sorry for building the idea anyway. I'm glad, genuinely, that this process already has a name somewhere in a body of work I haven't earned the right to cite directly, information theory, maybe, uncertainty, entropy, something in that direction. Claude Shannon's name belongs here, as a nod, not a foundation. Someone who's actually read him can draw the real line. I'm just the one who noticed the shape of the thing before I knew what it was called.
That's what combination does once you already have strong nodes to combine. The harder question comes first: how do you find a node worth using at all? Specifically, what's happening when you do this is you're comparing the flat contents of the string to how often those characters, numbers, or symbols show up in the English language. If that comparison alone gives you a strong enough signal, you're done, that's your node. If it fails, if the pattern's too common in English generally to mean much on its own, you move to the container: instead of asking how rare this is across all of English, you ask how consistent it is across a set of documents that all do the same job. This is where most of my nodes actually come from, I'll pull twenty permanent nodes out of twenty different pieces of documentation, and what I'm really measuring at that point isn't the language, it's how the author standardized their own formatting. This is the most exciting and most difficult thing in finding good nodes, because maybe the way a form uses a semicolon is a huge signal to a node you want. If that's the semicolon in the paper, and all of these forms are identical, this is a good node.
One idea that hasn't been touched yet is using documentation to create nodes. This is the fun part. A node can be anything, a word, a sentence, a string, or a whole program, so the source of a node doesn't matter either. A paragraph before, I said I used different sets of documentation to create nodes. What I mean by this is that I took several pieces of information and only used the most accurate pieces from each document.
As a thought exercise, think about how we know someone's name in a social setting. You can learn a name by them telling it to you, or someone could have a preexisting relationship with them and tell you the name. All these sources give the same information. And because they may give different results (someone may give you a nickname or a preferred name, for instance), the truest, legally recognized way to know someone's name is a birth certificate. Think of a name as a node here, and the reliability of the source of information as a signal. The closer you get to the birth certificate, the more reliable the name of the individual is.
Chapter 5: Weights
So we are slowly building layers on the machine. The monosemous/polysemous words decide if the nodes will eventually become states or combined states. The weights sit in the middle, a computational block of nodes that determines how strong the signal is. From before, we know that this is basic arithmetic or nested Booleans, which produce a state.
I wanted to address the Boolean question here, which I mentioned before:
A person whose name happens to end in "LLC," SSN on file: +1 + (−2) = −1 → Human, the name-signal gets overridden.
Why did I add math when, in an earlier example, the function I described was a nested Boolean?
So the given description was done in arithmetic, because 1 + -2 will always equal -1. Therefore, the weight of -2 will always beat the weight of +1, by function of math. Likewise, the function can this be illustrated as a nested Boolean:
python
def resolve_entity(name, id_number):
    if name.endswith("LLC"):
        entity_type = "Company"
    else:
        entity_type = "Person"

    if matches_ssn_format(id_number):
        entity_type = "Person"        # overrides, no matter what came before
    elif matches_ein_format(id_number):
        entity_type = "Company"       # confirms

    return entity_type
The reason I used arithmetic instead of code here is for legibility, for normal people. The second reason is that I started in Excel, and I've built Boolean values more than 160 iterations long (whatever the actual maximum was), so I tend not to reach for Booleans anymore. But weights aren't Booleans or arithmetic, they're something both can express, so it doesn't really matter why I used one or the other. The problem is illustrative of what a weight is. I want to be straight about why this chapter, or this question, doesn't end in one formula: Quantum rarely has weights that are just one single statement of code or arithmetic.
Look at what "weight" has actually meant across this book so far. It was a boolean gate deciding if a button press should fire a light. It was a +1/−2 arithmetic override deciding if a name-suffix should lose to an ID format. It was a frequency test, comparing a string against how rare it is across English. It was a document-consistency test, the same semicolon showing up identically across twenty forms. It was a keyword search, right of a colon, then overridden if a stronger record exists. That's not five metaphors for one mechanism. Those are five different mechanisms, a boolean, an arithmetic comparison, a statistical rarity check, a cross-document pattern match, a plain lookup, all doing the same job, deciding how much a signal counts, without being the same thing.
When I say look at the distance between two nodes, that distance can be defined in innumerable ways. I've built nodes that needed whole programs as their weight, Python scripts just to identify the capital of a city, or whether a word is functioning as a noun in a sentence. This system uses signals that are inherent to English itself to decide states. That's what makes them so complex, because the ideas underneath them are complex. Imagine trying to codify the Bill of Rights into quantifiable relationships. Some constitutional law experts would tell you it would take millions of nodes and millions of references back to the Federalist Papers just to get it right. The weights are messy, referentially complex, and symbolic, because the concepts underneath them are messy, referentially complex, and symbolic too. Use booleans or don't. Just get an accurate answer.
A single formula that claimed to unify all of that would be lying to you. It would be trading a handful of honest, specific tools for one dishonest, general-sounding one, which is exactly the kind of move this book has been arguing against since chapter one. The discipline isn't picking the one true weighting algorithm. The discipline is recognizing, signal by signal, which tool actually fits what you're looking at, a boolean, arithmetic, a lookup, a whole subprogram, or something you haven't built yet. That's a harder skill than memorizing a formula, and it's the one you actually need. Anyone telling you weight reduces to one clean operation is selling you something simpler than the problem actually is.
I don't want to leave you with nothing, because that would be just as intellectually dishonest as saying weights can be simplified. Here's a history of how I built these machines, and maybe the evolution of how I did so can help.
The first time I built one of these machines was in Excel. The program became a Boolean tree with hundreds of parameters, and I was the only person who could understand it. Later, I was building Boolean trees that called different pieces of code, and the code would resolve node conflicts. I'd use signals from formatting, measuring prefixes, or building datasets with very specific rules to decide what a state was. Lastly, I started using weights to call code that itself transforms based on other nodes, and this is the final iteration.
This might read like a cop-out, a poor explanation of how to create weights. But speaking from experience, the way you communicate a weight only matters to the extent of how precise your state has to be. It's abstract in that way. Some of my simplest code is a call-and-answer style: what is the customer's name, find the temp file, search keyword NAME:, take everything right of the colon as the name, but if a birth certificate value exists, use that instead, unless it's zero. That's what most of my node weights actually look like. Very simple, stated codes, with the edge cases plainly stated as the rule, "the rule is the exception," and this is guided by pragmatism and legibility, not Boolean or math.
In that way, your weights will improve based on how well you can think abstractly, or code, really. If Booleans are what you're good at, use Booleans to get there. If math is what you're good at, use math. What matters is that the accuracy of the weights determines the accuracy of the machine. I'll likely write a whole book about weights and my weird computer theories someday. I hope this comes across as encouraging rather than how it feels to write, but it's difficult to fit computer science into a few paragraphs. What matters for coders is that the blank spaces are code, call code, call functions, call programs, call sentence fragments, figure out how to pin down the constraints of the nodes you have, and weigh them against the other nodes you have, until you get the desired outcome.
Ideas Sharpen
To me, ideas sharpen... I love this language. An introductory sentence grabs the attention of the reader after a brief respite and introduces a theme, good writing does, at least. In that way, if you adhere to these writing tenets, most of the theme can be carried in the first sentence. What's the concept below? Well, based on the first sentence, ideas crescendo into thoughts, but they do this by going from a vaguer version of themselves to something more specific. Good writing sharpens an idea into a claim. So, if you want to make good Quantum machines, your strongest nodes arise from your first sentences. Since we strive to write well, we create powerful introductory sentences, and thus the makeup of the introductory sentence becomes the template of the paragraph, literally.
The paragraph above highlights how writing is in good creative writing but it does not adhere to every form of writing, forms don't have an introductory sentence. Here, the method is the message and the nodes should adhere to whatever you are building. Code, for instance, doesn't care about rules of creative writing, the most important line of code is the one that is currently broken.
When comparison happens, what is actually occurring is that we group states together. These states can be hard coded by weights or placed in pairs with weights. This is important, as state relationships can and often do create sentences themselves. This is a product of writing/coding/etc., and not a function of Quantum. Take, for instance, this book, which had to explain nodes before it got to the section about comparing states. If you aren't using previous states to make new sentences, I would encourage that you do so as a practice. Some states have been through multiple rounds of verification, and they represent your main themes, ideas, and reasons for creating the body of work. In that way, they are self-fulfilling. The state output comparison will recontextualize how you approach writing and words. After you make several machines, you can see states in plain writing, and the distance between states is something I describe as the topography of writing, your heavily verified, high-weight states are the peaks, everything temporary and single-use is the valley floor.

