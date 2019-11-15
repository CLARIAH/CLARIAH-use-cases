# Background
The [CLARIAH Media Suite](https://mediasuite.clariah.nl/) includes a component for manual video annotation. This component is developed by Jaap Blom and Marijn Koolen as part of the CLARIAH annotation client/server [see CLARIAH Annotation working group](https://clariah.github.io/scholarly-web-annotation/). AV annotation is an essential requirement for film, television, oral historians, and other scholars who use AV media in their research. Typical tasks in AV annotation are: manual or automatic selection of segments of interest (generally time-based, but also to parts of frames), adding tags/codes manually (or automatically) to those segments, adding comments, links, transcripts, and other user or automatic metadata. These tasks typically occur during the research phases of corpus creation (rapid annotations) and analysis phase (more in-depth annotation) (Melgar, Koolen, Huurdeman & Blom, 2017).

Because not all the possibilities for annotating AV media can/should be developed by the CLARIAH annotation tool, we seek to achieve interoperability with important tools. One of them is [ELAN](https://tla.mpi.nl/tools/tla-tools/elan/).

# Use cases for interoperabiility between the Media Suite annotation tool and ELAN

These use cases resulted from task analysis of different scholarly workflows (add link here to broad WP5 use cases). From that analysis, we selected two main use cases for interoperability:

## Use case 1. Using content from the Media Suite to annotate AV content in ELAN
As a scholar using video/audio items for detailed close-reading and analysis, I need to play content from the Media Suite in ELAN, so I can annotate it using all ELAN functionalities which are not available in the CLARIAH Media Suite. 
Advanced functionality of ELAN which is not offered (and most likely won't be offered in the future) by the Media Suite includes:

- ELAN is a desktop version, which in some cases (e.g., high precision in segmenting, speed) scholars prefer to the Media Suite web-based application.
- ELAN makes it possible to perform detailed structural and advanced segmentation of audio-visual items using dependent tiers. This is mostly useful for: aesthetic analyses (films, television programs), and multimodal analyses (e.g., verbal and non-verbal analyses of oral history interviews) which require to define relations between tiers.
- A secondary reason (there are not yet examples of this from the users) is that ELAN includes more than 14 audio recognizers, which could be used by scholars for the detailed analysis of the audio signal (manual and semi-automatic, e.g., based on silence gaps).

## Use case 2. Importing annotations and media made with ELAN to the user's own material into the Media Suite
1. As a scholar using my own video/audio items for detailed close-reading and analysis with ELAN, I would like to be able to import my media and annotations to the Media Suite, so I can benefit from the functionalities offered by the Media Suite and relate my content to other AV content available there.
   This use case assumes that the user starts annotating her own AV materials in ELAN and has made some annotations already. For example: the user may have segmented a video into shots, and may have added his own classification/codes to those shots. The user may realize that she would also like to:
   a) Show/display her annotations together with the AV material via the Web (e.g., during a presentation or lecture), give the possibility offered by the Media Suite's resource viewer, which shows the AV source along with annotations in a dedicated web page.
   b) Benefit from combining the analysis of her own material with other material offered by the Media Suite (for example, television, radio, film, or oral history interviews offered by DANS, Eye, or Sound and Vision). Note: this use case is actually already supported via the exporting function offered by the Media Suite and ELAN, but for scholars with limited data skills, combining data from the exports produced by the two tools may be challenging.

### Use case 2.1. Same as 2, but for transcripts
As a scholar using ELAN to work with transcriptions of my own video/audio items, I would like to import those transcripts (and my AV item) into the Media Suite, so I can use the interactive transcript web presentation.
This sub-use case is the same as use case 2, but only for transcripts. This scenario of use is expected to occur mostly with oral historians (as it was discussed at the CLARIN [Munich OH workshop](https://docs.google.com/presentation/d/1cqI4bnfPzWfG605J8IqXSya-Hhgd8RB854SMnboIj84/edit#slide=id.g429c75591d_0_0)). Transcripts can be either created manually in ELAN (using ELAN's transcription mode), or created externally and imported into ELAN. This happens when, for instance, a transcript doesn't have time spans, and scholars want to align it with the AV material, which ELAN facilitates in a couple of ways.
Note: besides ELAN, at least one scholar working with audio interviews reported to use YouTube for aligning transcripts (Youtube supports automatic alignment).

# References
Melgar Estrada, Liliana, Marijn Koolen, Hugo Huurdeman, en Jaap Blom. “A process model of time-based media annotation in a scholarly context”. In CHIIR 2017: ACM SIGIR Conference on Human Information Interaction and Retrieval. Oslo, 2017.