# AID-FORK-LombaxNip-
A fork of mimi Cat&lt;nip> AID

**see the raw for full information**

[<LombaxNip>]
Made by F L A T

It's a fork of Cat<nip>, most of the operators and such are similar

Example:

Key:Kuruptco

[ <Kuruptco=birdfolk biped bird> ]

[ <Kuruptco description=a tall humanoid bird, you can see them flying in the sky & wandering the mountains,they are considered as good swordfighter but having a very bad agility> ]

[ <Kuruptco feathers color=blue/red/yellow> ]

[ <Kuruptco=tall & slender> ]

[ <Kuruptco clothing=none> ]

1]Operators

[] =Line Encapsulation (to ensure stability and lesser leaking)
< =start of a line
> =end of a line
"=" = is/are/equal (basically Catnip "=")
"/" = or
"&" = and
"&&" stronger and (never tested)
" : " strong correlation between 2 keys in two different entry (in test/to verify)
For example

WI 1=
Key:Key1 
Entry=Key1:Key2

WI 2=

Key=Key2
Key=Key2:Key1 

"," = same as a normal ,

"  " = space

Square Bracket [] is used to encapsulate a line, to ensure it doesn't leak with the others lines. I recommand to use it at every start of a line with a Space just after " [ <> ]

<> is a line, a line always need the Key + "=" or ":"

Example: <Key=i love keys>

Prose can be used after a =

Like <Key=i love keys, they are so beautiful>


2]Limitation:

1)30 token at least (to verify)

2)Boring word or Token can make the bot repeat the full description, Instead of AI generated

For example:

<Key description=He is a big bird who like flying....etc etc>

AI will give="He is a big bird who like flying....etc etc"

Instead of:
"Johnny is a fat bird, despise it's fatness he like to fly"

3)it seems that, if you do something like that

[ <Key advantages=easy to transport> ]

The AI can, write it like this:

"KEY ADVANTAGES:

Easy to transport in a pocket.....etc etc"

Other limitation may exist

3] General use

Can be used for quick description or for quick writing of a WI

Items=work if did well

Shotgun example:*to be verified*

Key=Shotgun

Entry=

[ <Shotgun description=weapon who use shotgun shell and can kill easily>] 

(Additional)

[ <Shotgun damage=high> ]

[ <Shotgun speed=low> ]

Location=work if did well

Example:

Key=Veldin

Entry

[ <Veldin description=a big desertic planet> ]

(Additionnal)

[ <Veldin inhabitant:Lombax> ]

[ <Veldin Location:a other bigger location> ]

Races=work

Example:

Key=Kuruptco

Entry=

[ <Kuruptco=birdfolk biped bird> ]

[ <Kuruptco description=a tall humanoid bird, you can see them flying in the sky & wandering the mountains,they are considered as good swordfighter but having a very bad agility> ]

[ <Kuruptco feathers color=blue/red/yellow> ]

[ <Kuruptco=tall & slender> ]

[ <Kuruptco clothing=none> ]

(Additionnal)

[ <Kuruptco abilities=Swordfighting & high agility> ]


Classes=work

Key=Explorer

(Work but can be very broken, need to be modified or verified)

[ <Explorer purpose=exploring planet for fun> ]

[ <Explorer advantage=better travelling & knowledge> ]

[ <Explorer disadvantage=none> ]

[ <Starting items=Aphelion ship> ]

Faction=to verify

(WIP)

4]Compatibility

Prose and seems to work with Neanderthal

(WIP/to verify)
