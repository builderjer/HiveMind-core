## Jarbas Mycroft Hive

Join the mycroft collective, utils for mycroft-core mesh networking

## Components

- [Minds]()
- [Drones]()
- [Nodes]()
- [Terminals]()
- [Bridges]()

## Concept

Set of 3 skills

    telepathy_mind
    telepathy_drone
    telepathy_hivemind

* mind - turns that mycroft-core instance into a mycroft server
* drone - turns that mycroft-core instance to a mind client, all kinds of messagebus interactions are possible
* hivemind - get a list of public(or not) minds, ask them anything, this would be a volunteer network of everyone using the skill, private, or a combination


minds parse and filters requests, connecting clients require api keys
drones - pass the bus message along every time, blindly trust hive mind orders


Building your own Hive

* terminals - standalone connections to interface with a Hive Mind
* nodes - direct connections to a mycroft-core instance messagebus, provide micro services
* bridges - connect external services to a Hive Mind, useful for chatbots

## Use Cases

- Create a chatbot, demo for [hack.chat](https://hack.chat/?JarbasAI) and [twitch](https://www.twitch.tv/jarbasai)
- Create a private distributed mycroft network
- Chat rooms / Intercom
- Ask public hiveminds on fallback, i got a skill installed that solves your problem? you got the answer
- Turn any internet enabled device on a mycroft enabled component
- Talk with mycroft anywhere
- Fully customizable, advanced mesh network structures can be created by combining the available components