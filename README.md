# Figures for delphes/delphes PR 214 (ARCTracing)

Linked from the PR description; not part of the PR diff. All made with the module as in the PR branch (multi-cell optics,
spherical-cap mirrors, main-cell reconstruction):

- `validation_*`: ARCTracing (fast) vs Geant4 full simulation for the three cards (case study C Xe 2 bar, baseline B Xe 2 bar,
  baseline B C4F10) in the 14 cell-sized polar-angle bins: 3-sigma reach, separation, Cherenkov angle, resolution and
  ring-finding rate vs momentum and polar angle, photons per ring and angle bias.
- `separation_vs_idea.png`: track-level separation of the three ALFA cards vs IDEA dN/dx and time of flight.
- `flavour_*`: s vs ud jet tagging (ROC) and the pi/K/p content of s and ud jets.
