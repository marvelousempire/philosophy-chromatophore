# AN-005 — Butterfly

**Current research state:** two distinct mechanisms are well established; species and particular wing structure must be identified when making more specific claims.

## A. Metamorphosis — real biological transformation

Egg → caterpillar (larva) → chrysalis (pupa) → adult butterfly. Development involves major reorganization of tissues, regulated by biological processes. **An actual developmental change**, not a color filter or a UI transition.

## B. Structural color — light, geometry and human perception

Some butterfly wings contain microscopic ridges, layers and other structures on their scales. These interact with light through reflection, interference, diffraction and scattering. The color *seen* by an observer depends on how the scales are structured, the wavelength and angle of arriving light, the viewing angle, and the observer's visual system. Changing the light or viewpoint can change brightness or apparent hue **without the butterfly changing its wing structure or pigment at that moment**. Some species' optical appearance is less angle dependent than others. This is called **iridescence** when color varies with viewing or lighting angle.

**Worked Morpho example:** A blue Morpho wing can show strikingly different reflected intensity and apparent color with different viewing or lighting directions, owing to its layered wing scales. Do not claim every blue butterfly behaves the same way, or that a butterfly actively changes pigment when someone walks around it.

### Inputs and outputs

| Field | Scientific observation |
|---|---|
| Physical object state | Wing scale structure and pigmentation |
| Light source | Wavelength distribution, brightness and arrival direction |
| Viewing geometry | Direction of observation relative to wing scales |
| Optical result | Wavelengths/intensity/polarization reflected toward the viewer |
| Perceived result | Color/brightness as processed by the viewer's vision |
| What may remain fixed | The same wing, scales, pigments, animal and identity |

**Software design candidate:** separate *physical or underlying application state* from *rendered appearance* and from *viewer interpretation*; record lighting, camera/viewpoint and actual states. This is an analogy, not proof that screens can reproduce natural wing optics or human perception exactly.

### Research sources
- Vukusic et al. (2002), *Mechanisms of structural colour in the Morpho butterfly*, https://pmc.ncbi.nlm.nih.gov/articles/PMC1691047/
- Vukusic et al. (2006), *Exaggeration and suppression of iridescence*, https://pmc.ncbi.nlm.nih.gov/articles/PMC1618482/
- *Morpho butterfly flashiness crucially depends on wing scale curvature* (2024), https://pmc.ncbi.nlm.nih.gov/articles/PMC11557224/
- *The actin cytoskeleton plays multiple roles in structural colour formation in butterfly wing scales* (2024), https://pmc.ncbi.nlm.nih.gov/articles/PMC11106069/

See [optics and perception](07-optics-and-perception.md) for the complete observation path.
