TO BE REVISED

# Scenario `#hfm`

### Description

Users' stories on a theme elicited during a museum exhibition. In this scenario, the theme selected for the exhibition is rebellion. The objective is to enable expression and share opinions across religious, secular, and minority populations, understand differences, diverse views and address conflicts as a method for causing social cohesion.

### Background

The script (the alternative sequences of tasks) selected for the interaction between the user and a device is prepared by curators and developers. Different types of contents are suggested according to user profile as defined in the User Model created by developers.

### Script

The stages and the activities underlying the citizen curation activity.

**1. Preparation**

 * `Activity 1.1` The curators prepare the questionnaire for visitors on their personality, opinions, background information.
 * `Activity 1.2` The visitor answers the questionnaire before the visit starts.
 * `Activity 1.3` The curators select an introductory video to welcome visitors (`Activity 3.2` and others) and the questions (the script) to be prompted on the device according to the visitor's answers. The video is about the necessity and usefulness of rebellious acts from different points of views.
 * `Activity 1.4` The developers and curators select 3 videos - to be shown during the exhibition according to the user model: neutral, opposing, in favour.

**2. Preliminary analysis**

 * `Activity 2.1` The curators prepare a collection of visitors' opinions to be shown during the exhibition (`Activity 4.1`).
 * `Activity 2.2` The developers process visitor's answers and design user profiles based on a User Model.
 * `Activity 2.3` The developers prepare a collection of visitors' opinions (and backup curators' descriptions) to be shown during the exhibition according to the user model.

**3. Introductory activities**

At the entrance of the visit, in room \#0, the visitor interacts with a Tablet device.

 * `Activity 3.1` The visitor selects an avatar and a pseudo name.
 * `Activity 3.2` The visitor watches the introductory video (produced in `Activity 1.4`).
 * `Activity 3.3` On the device is prompted a question (produced in `Activity 1.4`), about which point of view she relates to. The visitor may (or may not) give an answer.
  * `Activity 3.4` If the visitor answered `None`, on the device is prompted a question (about the reasons she doesn't agree with any point of view). The visitor may (or may not) give an answer.
 * `Activity 3.5` On the device is prompted a suggestion (if she registers her email at the end of the visit, she can get a memento/souvenir summarizing her visit). The visitor may (or may not) register her email.

**4. Presentation**

The visitor enters in room \#1 (the Galileo rebellion exhibition).

 * `Activity 4.1` The curators show in the room a marquee of statements of previous visitors about the exhibits (produced in `Activity 2.1`).

**5. Running**

Interaction with the Tablet about the theme of the exhibition.

 * `Activity 4.1` The visitor interacts with a tablet next to an exhibit and selects her avatar. The visitor watches a video selected on the basis of her profile in the user model (`Activity 1.5`).
 * `Activity 4.2` On the device is prompted a question (whether she likes it or not). The visitor may (or may not) give an answer.
 * `Activity 4.3` On the device is prompted a question (how does she feel about the issue).  The visitor may (or may not) give an answer.
  * `Activity 4.4` If the visitor does not answer, on the device is prompted another question (a question on the exhibit). The visitor may (or may not) give an answer.
  * `Activity 4.5` If the user is profiled, on the device are prompted other visitors' opinions (produced in `Activity 2.2`), suggested on the basis of her user profile.
  * `Activity 4.6` If the user is not profiled, on the device are prompted curators' opinions (produced in `Activity 2.2`).
 * `Activity 4.7` On the device is prompted a question (how she feels about other opinions).  The visitor may (or may not) give an answer.
  * `Activity 4.8` If the user answered positively, the device prompt an answer (emoji).
  * `Activity 4.9` If the user answered negatively, the device prompt an answer (a rhetorical question).

The visit continues in other rooms, where other scripts may take place.

At the end of the exhibition:

 * `Activity 4.10` If the user registered her email (`Activity 2.5.1`) curators and developers prepare a souvenir/memento.

*UNCLEAR PART: She is given the choice between different bulletin boards based on different communities. She chooses and is given a list of possible questions to reflect upon (including relevancy of these topics today). She then reflects,  If she decides not to participate she is asked why she chose not to reflect. If she does reflect she is asked why she chose the particular community. She is invited to return to the bulletin board and follow the developments about this issue. She is asked if she wants notifications when there is new content.*

### Manifest and script

 * [CCO example (JSON-LD)](https://github.com/spice-h2020/manifest/tree/main/hfm_scenario/00002_example.json) A manifest for the Citizen Curation activities related to the social media campaign.
 * [Script (JSON-LD)](https://github.com/spice-h2020/manifest/tree/main/hfm_scenario/00002_script.json) The description of the script used for the activities at hand.
 * [context.json](https://github.com/spice-h2020/manifest/tree/main/context.json) The ontology specification for representing both CCO and scripts.
