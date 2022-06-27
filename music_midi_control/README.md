# MIDI-DDSP: Detailed Control of Musical Performance via Hierarchical Modeling

Implement a hierarchical generative model of musical performance to
provide both realism and control. Similar to conventional synthesizers and samplers
that use the MIDI standard, MIDI-DDSP converts note timing, pitch, and
expression information into fine-grained parameter control of DDSP synthesizer modules.
The hierarchical structure underlying the process of creating music involves a
composer writing a piece as a series of notes. A performer interprets these notes through a myriad of
nuanced, sub-second choices about articulation, dynamics, and expression. These expressive gestures are realized as audio through the short-time pitch and timbre changes of the physical vibration
of the instrument. MIDI-DDSP is built on a similar 3-level hierarchy (notes, performance, synthesis)
with interpretable representations at each level.

# Basic information about the project

Main paper / reference: Wu, Y., Manilow, E., Deng, Y., Swavely, R., Kastner, K., Cooijmans, T., Courville,A., Huang, C., & Engel, J. (2021). MIDI-DDSP: Detailed control of musical performance via hierarchical modeling. arXiv preprint arXiv:2112.09312.

Main dataset: Creating a multi-track classical music performance dataset for multi-modal music analysis: challenges, insights, and applications, https://datadryad.org/stash/dataset/doi:10.5061/dryad.ng3r749

Original code: https://github.com/magenta/midi-ddsp

Language: Jupyter notebook in Python or Matlab etc (include version, etc)

# Installation
Can be installed with:
pip install midi-ddsp
midi_ddsp_download_model_weights

# Executing / performing basic analysis
you can execute MIDI synthesis with the following command:
midi_ddsp_synthesize --midi_path <path-to-midi>
You can try on a example MIDI from the repository:
midi_ddsp_synthesize --midi_path ./midi_example/ode_to_joy.mid
You can also try a colab notebook demo available at: 
https://colab.research.google.com/github/magenta/midi-ddsp/blob/main/midi_ddsp/colab/MIDI_DDSP_Demo.ipynb

# Credits

15/06/2022 Frederico Lopes https://github.com/fredhrl

# References

Wu, Yusong, et al. "MIDI-DDSP: Detailed control of musical performance via hierarchical modeling." arXiv preprint arXiv:2112.09312 (2021).
