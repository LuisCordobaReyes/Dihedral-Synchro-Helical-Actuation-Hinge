# Additive-Manufacturing
Material Extrusion (FDM, SLA), Vat Photopolymerization, Powder Bed Fusion (PBF), Material Jetting, Binder Jetting, Direct Energy Deposition (DED), and Sheet Lamination.

## Additive Manufacturing Overview: FDM & SLA

Additive manufacturing (AM) builds parts layer by layer from a 3D model, rather than removing material like machining. Under the ISO/ASTM 52900 standard, AM splits into seven process categories. This project touches two of the most common desktop processes — FDM (Material Extrusion) and SLA (Vat Photopolymerization).

## Fused Deposition Modeling (FDM)

FDM — also called Fused Filament Fabrication (FFF) — is a material extrusion process. A solid thermoplastic filament is driven by a feed gear into a heated nozzle (hotend), where it melts to a semi-molten state. The nozzle, carried on a motion gantry (Cartesian or CoreXY), traces each layer's cross-section onto the build plate following sliced G-code toolpaths, depositing a bead of molten plastic that fuses to the layer beneath it as it cools and solidifies. After completing a layer, the platform indexes one layer height in Z and the process repeats; overhangs are supported by sacrificial printed structures. FDM runs common engineering thermoplastics (PLA, PETG, ABS, ASA, TPU, nylon, polycarbonate, and carbon-fiber composites), making it the cheapest and most accessible route to functional, mechanically robust parts. Its trade-offs are visible layer lines, coarser resolution, and anisotropic strength — parts are weaker along the Z axis because inter-layer bonds are weaker than the continuous plastic within a layer.

## Stereolithography (SLA)

SLA is a vat photopolymerization process — a fundamentally different mechanism from extrusion. Instead of melting a solid, it selectively cures a liquid photopolymer resin with ultraviolet light. A UV laser steered by galvanometer mirrors (classic SLA), or a full-layer image projected by an LCD mask (MSLA) or DLP projector, exposes the resin cross-section and triggers photopolymerization — the UV energy crosslinks liquid monomers into a solid polymer. In the common bottom-up configuration, the build platform lifts one layer height after each exposure, peeling the cured layer from the vat film, and repeats. Finished parts are not ready off the printer: they require washing in isopropyl alcohol to remove uncured resin, followed by a UV post-cure to reach full mechanical properties. SLA delivers exceptional resolution, fine detail, and smooth surface finish, ideal for cosmetic models, molds, dental, and jewelry — at the cost of messy, hazardous liquid resin (PPE required), mandatory post-processing, more brittle and UV-sensitive parts, and typically smaller build volumes.
