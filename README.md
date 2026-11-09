# Banksian-Fibron-Scope
State/Phase 12pi Waveform Folding Scope for advanced waveform construction and analysis.




### Interactive Geometric Construction and Reciprocal Winding Visualizer

**Banksian Fibron Scope** is an interactive 3D mathematical visualization tool accompanying the *Banksian Fibron Space* publication.

It allows users to construct, modify, and explore geometric waveforms using reciprocal angular winding, ordered rotation matrices, and hierarchical coordinate frames.

The purpose of this project is to make the underlying geometric constructions accessible for independent experimentation.

## Getting Started

The Scope is a standalone HTML application.

1. Download `FibronScope.html` from this repository.
2. Open it in a modern web browser.
3. Select a preset or create a new fold.
4. Adjust the waveform parameters, rotation angles, and viewing controls.

No installation or external mathematical software is required.

If GitHub Pages is enabled for this repository, the Scope can also be used directly through the hosted website.

## Main Features

### Geometric Construction

- **Wave-Fold:** Reciprocal winding across two or three rotational axes.
- **Shear-Fold:** Paired geometric waveforms with a derived midpoint or nucleus.
- **Fold Progression:** Translation of folded structures through an anchor.
- **Shear Division:** Experimental multi-waveform constructions and centroid relationships.
- **Hierarchical Complexes:** Nested geometric objects with inherited coordinate frames.

### Interactive Tools

The interface includes five main tabs:

| Tab | Purpose |
|---|---|
| Objects | Create and edit points, anchors, waveforms, and rotations |
| Parameters | Adjust variables, sampling, and rendering options |
| Presets | Load example configurations |
| Matrices | Inspect local and inherited rotation matrices and compare recurrence |
| Lens | View the reference chord-mirror geometry |

### Navigation and Visualization

- Drag to rotate the camera.
- Shift + drag to pan.
- Scroll to zoom.
- Toggle perspective and orthographic views.
- Show or hide coordinate axes.
- Export a PNG snapshot.
- Adjust sampling density to inspect trajectories more closely.

The timeline allows users to advance, reverse, pause, or step through the construction.

The **Next 12π** control advances the viewing interval by one canonical phase-return cycle.

## Mathematical Reference

The canonical reciprocal winding coefficients are:

\[
g_+(S)=\frac{S}{2}, \qquad
g_-(S)=\frac{2}{S}
\]

For \(S=3\):

\[
g_+=\frac32,\qquad g_-=\frac23
\]

The local waveform is carried through ordered three-dimensional rotation matrices.

The canonical construction has a common phase-return interval of:

\[
T=12\pi
\]

This establishes a repeat interval for the component phases. Spatial recurrence depends on the selected waveform and anchor motion.

For mathematical derivations, definitions, assumptions, and limitations, consult the accompanying **Banksian Fibron Space publication and BFS Proof Index**.

## Preset Configurations

The included examples demonstrate:

- Two-lens Wave-Fold
- Three-lens Wave-Fold
- Shear-Fold pole pair
- Hierarchical geometric construction
- Experimental Shear Division

These presets are starting points for exploration rather than restrictions on possible configurations.

Users are encouraged to alter parameters, construct new hierarchies, and investigate their own geometric relationships.

## Scope and Limitations

Banksian Fibron Space is presented as a geometric construction framework.

The visualizer demonstrates the behavior of specified mathematical operations. Its output does not independently establish physical laws or confirm that a particular trajectory represents a physical particle or phenomenon.

Some constructions are exploratory. The accompanying proof index distinguishes established identities, conditional theorems, definitions, and open questions.

## License

This project is released for public use and experimentation under the terms specified in the repository's `LICENSE` file.

Users are welcome to study, share, modify, and extend the available material in accordance with that license.

## Associated Materials

- **Banksian Fibron Space:** Mathematical publication
- **BFS Proof Index:** Indexed definitions and mathematical derivations
- **Fibron Scope:** Interactive geometric visualization tool

---

*Explore the geometry. Test the constructions. Build something interesting.*
