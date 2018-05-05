My bachelor thesis, written in 2016. Pdf is in `build/`

Abstract
========
Within this thesis a comparison between two veto regions (DC and EXT) for the IceCube detector is made in the 1 to 1000 GeV energy range.
Simulation data consisting of muons, electron neutrinos and muon neutrinos is used.
Applying the vetoes to those events yields two new sets of events, each consisting only of events passing the corresponding veto.
Relevant features are selected via mRMRe and used in a two staged random forest separation.
First, all neutrinos are separated from muons, then muon neutrino candidates are separated from the remaining electron neutrinos.
For each stage the passing event rates and correlation between reconstructed and true energy are compared.
The DC-Veto is shown to be superior, with an expected muon neutrino rate of 4.63 µHz and a correlation of 0.7.



TUDoThesis
=====================

LaTeX class file and template for a thesis written at TU Dortmund

The template is build for use with _lualatex_ and _biblatex_ with _biber_,
the class file can be used with the LaTeX engine of your choice, it is completely independent.

This is an unofficial document which was created from my bachelor thesis, which itself
was strongly influenced by the latex files which kdungs used for his bachelor's thesis.

All used packages and commands are explained
in depth in the materials of the PeP et al. LaTeX Workshop:

http://toolbox.pep-dortmund.de/notes.html
