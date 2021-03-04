Two similar scenarios apply to the `#gam` Citizen Curation activities.

# 1. GAMgame online

### Description

Users' stories on museum artefacts elicited via a web application. The objective is to enable users to tell stories (`Goal: storytelling`) and share their opinions, memories, and emotions, while looking / selecting artefacts of interest (`Goal: Story-based Narrative List`).

### Background

The script selected for the interaction between the user and a device is prepared by curators and developers. Curators select pictures of artefacts from the GAM collection to be presented to users (in random order every time). Users pick 1-n pictures and for each of them they may share:

  * a text on a memory, a feeling, an emotion elicited by the picture
  * emojis
  * hashtags

If the user chooses at least 3 pictures (?), the application recommends another picture to be included in the story. The recommendation is based on the analysis of the user story, e.g. narrative-based, emotion-based, random recommendation. The user may accept the recommended picture or not.

The script has been executed on 25-26th November 2020.

### Script

The stages and the tasks underlying the citizen curation activity.

**Activity Preparation**

 * `Selection of artefacts / Selection of multimedia contents` The curators create a list of pictures of artefacts to be shown to users.

**Running stage**

 * `Presentation of curatorial content` The web application shows the list of pictures in a random order.
 * `Selection of artefacts / Selection of multimedia contents` The user may pick 1 picture.
 * `Free-text answering` The web application prompts three suggestions (templates) to encourage the user writing a story about the selected picture: "Mi ricorda:" (It reminds me), "Mi fa sentire:" (It makes me feel), "Mi fa pensare a:" (It makes me think of). The user may or may not answer.
 * `Add emoticon` The web application allows the user to add an emoticon related to the selected picture. The user may or may not answer.
 * `Tagging` The web application allows the user to add a list of hashtags related to the selected picture. The user may or may not answer.
 * `Recommendation` The web application recommends the user another picture to be included in the story. The user may or may not accept the suggestion.

These tasks can be repeated in loop as many times as the user wants. At the end of the activity, the user stories are stored.

### Manifest and script

 * [Script (JSON-LD)](https://github.com/spice-h2020/manifest/tree/main/gam_scenario/00003_script.json) The description of the script used for the activities at hand.
 * [context.json](https://github.com/spice-h2020/manifest/tree/main/context.json) The ontology specification for representing both manifest and script.

# 2. GAMgame form

### Description

Users' stories on museum artefacts elicited via an online form. The objective is to enable users to tell stories and to share preferences with friends (`Goal: storytelling`, `Goal: sharing interpretations with family or friends`) and share their opinions, memories, and emotions, while looking / selecting artefacts of interest (`Goal: Story-based Narrative List`).

### Background

The script selected for the interaction between the user and an online form is prepared by curators and developers. Curators select pictures of artefacts from the GAM collection to be presented to users (in random order every time). Users pick 1-n pictures and for each of them they may share:

  * a text on a memory, a feeling, an emotion elicited by the picture
  * emojis
  * hashtags

Once the user has selected all the artefacts and built the story, s/he is asked to recommend an artefact to a friend.

The script has been executed on 25-26th November 2020.

### Script

The stages and the tasks underlying the citizen curation activity.

**Activity Preparation**

 * `Selection of artefacts / Selection of multimedia contents` The curators create a list of pictures of artefacts to be shown to users.

**Running stage**

 * `Presentation of curatorial content` The web application shows the list of pictures in a random order.
 * `Selection of artefacts / Selection of multimedia contents` The user may pick 1 picture.
 * `Free-text answering` The web application prompts three suggestions (templates) to encourage the user writing a story about the selected picture: "Mi ricorda:" (It reminds me), "Mi fa sentire:" (It makes me feel), "Mi fa pensare a:" (It makes me think of). The user may or may not answer.
 * `Add emoticon` The web application allows the user to add an emoticon related to the selected picture. The user may or may not answer.
 * `Tagging` The web application allows the user to add a list of hashtags related to the selected picture. The user may or may not answer.

These tasks can be repeated in loop as many times as the user wants.

 * `Selection of artefacts / Recommendation` The user may select an artefact to be recommended to a friend. 

At the end of the activity, the user stories are stored.

### Manifest and script

 * [Script (JSON-LD)](https://github.com/spice-h2020/manifest/tree/main/gam_scenario/00004_script.json) The description of the script used for the activities at hand.
 * [context.json](https://github.com/spice-h2020/manifest/tree/main/context.json) The ontology specification for representing both manifest and script.
