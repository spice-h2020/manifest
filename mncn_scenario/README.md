# Scenario MNCN - Treasure Hunt
***

## Description

Museum Curators of the National Museum of Natural Sciences in Madrid design a treasure hunt to enrich the experience of children visiting the Museum through gamification.

## Background

A consequential series of tasks are designed by a Museum Curator in the form a treasure hunt. Users, children in this case, have to look for clues and obtain new ones by:
* Looking for specific artefacts and scanning the QR codes associated with them
* correctly answering to questions both visually (put input in a map or drawing something) or textually

After finding all the clues, a potential reward, either physical or digital, is given to the users.

This script has not yet been executed. (as of 18/08/2021, to be verified)

## Script

The script for the Treasure Hunt is divided into preparation and running activities

### Preparation

* `Treasure hunt artefacts selection`: the curator(s) of the museum/organizer(s) of the treasure hunt select the artefacts that will be included in the treasure hunt.
* `Treasure hunt activity preparation`: The curator(s) of the museum design the number of stage and each activity for each stage of the treasure hunt.

### Running

* `artefact qrcode searching`: the User searches an artwork's QR code
* `artefact qrcode scanning`: The User scans a QR code next to the artifact and receives factual information, images, questions etc. of any of the activities of the treasure hunt.
* `artefact presentation`: Some curatorial content or set of curatorial contents (e.g. artworks or artworks' images etc.) is presented to the User with factual information.
* `multiple choice answering`: The user answers to a multiple choice question about an artwork in order to advance with the treasure hunt.
* `free text answering`: The user answers to an open question about an artwork in order to advance with the treasure hunt.
* `user artefact drawing`: The User observes the artwork and totally or partially draws it, according to the given intructions.
* `user map location`: The user puts some pins on a map in order to locate an artefact or a region, according to the given instructions.
* `clue, reward or instruction receiving`: The user receives either a clue to continue to the next stage of the treasure hunt or to the next task that can be in the form of instructions to follow to answer questions, draw something or place inputs in a map.  If it's the final activity the output could be a final prize.

All the running tasks are interchangeable and can follow one another according to the design of the treasure hunt.

## Manifest and Script

* [Script(JSON-LD)](https://github.com/spice-h2020/manifest/blob/main/mncn_scenario/00006_mncn_treasure_hunt.json): a JSON-LD serialization of the treasure hunt;
* [Manifest](https://github.com/spice-h2020/manifest/blob/main/context.json): the context of the JSON-LD file.




