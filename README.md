# *Eucalyptus regnans* F.Muell. — Mountain Ash

**Organization / Repository:** `https://github.com/intenteco/eucalyptus-regnans`  
**Taxon Concept URIs:** `urn:qualia:taxon:eucalyptus_regnans` · `did:q42:taxon:eucalyptus_regnans`  
**Work-Packet Status:** `ECO-WP-04A` (Species Ontology, Q42 Volumes & Claim Ledger) & `ECO-WP-04B` (3D CAD `.vibe` / `.hmc`, `.m64`, `.emf`, PBR, XPBD & Native `.10d` Previews) completed; `ECO-WP-GATE` (Visual & Domain Gate Review) pending.  
**Commons Governance:** Social Permissive Commons (`SPC`) · CC-BY-4.0 dataset metadata · Local Contexts TK/BC provenance notices.

---

## 1. Taxonomic Concept & Authoritative Identifiers

| Field | Value / Identifier |
|---|---|
| **Scientific Name** | *Eucalyptus regnans* F.Muell. |
| **Biological Superlative** | World's tallest flowering plant (angiosperm) and tallest hardwood tree |
| **Family / Genus / Subgenus** | Myrtaceae · *Eucalyptus* · subg. *Eucalyptus* · sect. *Pseudophloius* (Pryor & Johnson) / *Eucalyptus* (Brooker) · ser. *Regnantes* |
| **Vernacular Names** | Mountain Ash, Giant Ash, Swamp Gum, Victorian Ash, Stringy Gum, White Mountain Ash |
| **APNI Name** | `https://id.biodiversity.org.au/name/apni/101747` |
| **APNI / APC Taxon** | `https://id.biodiversity.org.au/taxon/apni/51290024` |
| **GBIF Backbone** | `GBIF:3176566` (`https://www.gbif.org/species/3176566`) |
| **EUCLID Key** | [`eucalyptus_regnans`](https://apps.lucidcentral.org/euclid/text/entities/eucalyptus_regnans.htm) |
| **VicFlora** | [`e580e052-ec06-444f-a9db-8f83060fc057`](https://vicflora.rbg.vic.gov.au/flora/taxon/e580e052-ec06-444f-a9db-8f83060fc057) |
| **ALA Taxon Page** | [`bie.ala.org.au`](https://bie.ala.org.au/species/https%3A/id.biodiversity.org.au/taxon/apni/51290024) |

### Non-Substitution Taxonomic Boundaries (`TREE-01`)
- Do **not** substitute *Eucalyptus fastigata* (Brown Barrel — shares rare paired axillary umbels, but has rough bark over the entire trunk and branches and a slightly domed capsule disc).
- Do **not** substitute *Eucalyptus obliqua* (Messmate Stringybark — rough bark extending to branchlets, single axillary umbels, barrel-shaped fruit).
- Do **not** substitute *Eucalyptus delegatensis* (Alpine Ash — glaucous/bluish juvenile leaves and single axillary umbels).
- **Working Locality Scope:** Victorian Central Highlands / Yarra Ranges, Dandenongs, Strzeleckis, and Otway Ranges (VIC), plus Huon, Derwent, and North-East valleys (TAS); exact site and individual occurrence specimen remain pending field resolution.

---

## 2. Anatomical Subsystems (`PO:*` & `living_world_anatomy` Pins)

1. **Massive Fluted Buttress Root System (`PO:0025025`, `PO:0000038`, `PO:0000042`, `PO:0005707`):**  
   Wide-spreading lateral and deep sinker roots with radial buttress flute harmonics ($k = 3\dots7$) anchoring 65–95+ m boles in deep fertile loams. **Lignotuber strictly absent** — *E. regnans* is an obligate seeder killed by stand-replacing crown fire.
2. **Straight Columnar Bole, Basal Stringybark Stocking & Decorticating Ribbon Bark (`PO:0025004`, `PO:0005513`, `PO:0005509`, `PO:0005417`, `PO:0005511`, `PO:0005352`, `PO:0005353`):**  
   Straight columnar trunk (`65.0–95.0 m`, historical records `>100.0 m`) with a rough fibrous brown/grey-black "stringybark" stocking on the lower `5.0–15.0 m`, transitioning to smooth cream, pale grey, or white upper bark shedding in long decorticating ribbons `5.0–12.0 m` long.
3. **High-Forking Pipe-Model Crown Boughs (`PO:0009006`, `PO:0020100`):**  
   High-forking ascending scaffold boughs obeying Shinozaki/WBE pipe-model area conservation ($r_{\text{parent}}^{2.49} = \sum r_{\text{child}}^{2.49}$), fork angles `32.0°–48.0°`, golden divergence angle `2.399963 rad`, and open air-gapped sub-crown foliage clusters (`45%–65%` sky transmittance).
4. **Green-Leaved Ash Foliage (`PO:0025034`):**  
   - **Juvenile foliage:** Opposite and shortly petiolate for 2–3 pairs then alternate, ovate with oblique base (`5.5–12.0 × 2.2–5.0 cm`), glossy green (**never glaucous**).  
   - **Adult foliage:** Alternate, petiolate (`0.8–2.5 cm`), pendulous, glossy green concolorous falcate-lanceolate leaves (`9.0–23.0 × 1.5–5.0 cm`) with oblique base, acute lateral veins, remote intramarginal vein, and schizogenous oil glands (`PO:0005018`).
5. **Diagnostic Paired 9–15 Flowered Bud Umbels (`PO:0009046`, `PO:0006322`, `PO:0009084`):**  
   Predominantly **paired** axillary umbels (peduncles `0.4–1.4 cm`), bearing **9–15** pedicellate (`0.3–0.7 cm`) clavate-to-obovoid buds (`0.4–0.7 × 0.2–0.4 cm`) with single conical-to-rounded apiculate opercula (outer scar absent) and white stamens; flowering March–May.
6. **Cupular-Obconical Woody Capsules (`PO:0009001`, `PO:0009010`):**  
   Pedicellate cupular-obconical gumnuts (`0.5–0.8 × 0.4–0.7 cm`) with slightly descending disc, 3 rim-level or enclosed valves, and pyramidal brown seeds (`1.5–3.0 mm`) stored in a bradysporous canopy seed bank.

---

## 3. Biophysical, Allometric & Fire-Ecology Reference Parameters

| Parameter | Value / Range | Unit | Notes / Evidence Status |
|---|---|---|---|
| Pipe-model exponent ($n$) | `2.49` | dimensionless | $r_{\text{parent}}^n = \sum r_{\text{child}}^n$ (modeled Eucalyptus allometry) |
| High-forking bough angle | `32.0–48.0` (nominal `40.0`) | deg | Sourced morphological range |
| Golden divergence angle / internode ratio | `2.399963` / `0.85` | rad / ratio | Modeled FSPM branching grammar |
| Mature height | `55.0–95.0` (historical `>100.0`) | m | Living verified *Centurion* ~100 m (EUCLID / VicFlora) |
| Diameter at breast height (DBH) | `2.0–6.5` | m | Sourced (EUCLID / VicFlora) |
| Specific Leaf Area (SLA) | `8.4` | m²/kg | Sourced nominal (AusTraits) |
| Air-dry wood density ($\rho$) | `650.0` | kg/m³ | Sourced timber mechanics (AusTraits) |
| Longitudinal Young's modulus ($E$) | `16.0` | GPa | Sourced timber mechanics (AusTraits) |
| Xylem cavitation resistance ($\Psi_{50}$) | `-2.9` | MPa | Sourced hydraulic trait (AusTraits) |
| Fire regeneration strategy | Obligate seeder (lignotuber absent) | — | Stand-replacing ash-bed germination post-wildfire |
| Veteran hollow formation window | `120–400` | yr | Critical denning habitat for *Gymnobelideus leadbeateri* |

---

## 4. `InstanceState64` Ontogenetic Stages

Individual trees are parameterized deterministically via a 64-byte `InstanceState64` descriptor (`seed`, `ontogenetic_age_norm`, `height_scale [0.75..1.25]`, `site_vigor [0.40..1.20]`, `environmental_stress [wind_prevailing_bias, drought_leaf_drop, fire_char_height, epicormic_sprout_factor]`):

- **`0.00–0.15` Ash-Bed Sapling:** Dense post-fire mineral ash-bed regeneration without lignotuber; glossy green ovate oblique juvenile leaves.
- **`0.15–0.45` Rapid Pole-Stage Spar:** Straight self-pruning spar (`12–55 m`) developing basal stringybark stocking and transitional falcate crown.
- **`0.45–0.80` Tall Wet-Sclerophyll Canopy Giant:** `55–95 m` columnar bole, `5–15 m` rough basal stocking, smooth cream/grey/white upper bark shedding `5–12 m` ribbons, paired 9–15 bud umbels & cupular-obconical capsules.
- **`0.80–1.00` Ancient Multi-Century Buttressed Hollow-Bearing Veteran:** Massive fluted buttress roots (`2.0–6.5 m` DBH), weathered broken crown limbs forming `120–400 yr` hollows critical for Leadbeater's Possum (*Gymnobelideus leadbeateri*) and Southern Greater Glider (*Petauroides volans*).

*(Note: `ontogenetic_age_norm` is a procedural developmental stage index, not an asserted chronological age.)*

---

## 5. Biocultural Custodianship & Country Provenance

*Eucalyptus regnans* spans South-Eastern Australian tall wet-sclerophyll Countries including **Wurundjeri**, **Taungurung**, **Boonwurrung**, **GunaiKurnai**, and **Gadubanud / Eastern Maar** Country across Victoria (Yarra Ranges, Central Highlands, Dandenongs, Strzeleckis, Otway Ranges), alongside **Palawa / Lutruwita** Country in Tasmania (Huon, Derwent, and North-East valleys).

This repository records Country attribution under **Social Permissive Commons (`SPC`)** with **Local Contexts TK/BC notice placeholders** (`TK_Notice_Open_To_Collaborate`, `BC_Notice_Biocultural_Provenance`) acknowledging Indigenous Cultural and Intellectual Property (ICIP) without asserting community-authored labels absent direct First Nations co-design.

---

## 6. Repository Artifacts, Sealed Digests & Production Metrics (`ECO-WP-04A` + `ECO-WP-04B`)

| Artifact | Status | SHA-256 / Details |
|---|---|---|
| `synth.project.json`, `.gitignore` | Authored | Synth `synth.project/v1` descriptor |
| `.synth/bookmarks.json`, `.synth/jobs.json` | Authored | 11 biodiversity endpoints; 2 `.q42` compile jobs |
| `ontology/taxon.ttl` | Authored | `0acb3ce62bfd2aa45470afe64f63bc92932903ab0d49973818dfccea703d27d1` (`26,247` bytes) |
| `ontology/index.ttl` | Authored | `67aa7904928105ce4d6c9afedc38df7579f02bc1eb50bed93355a4f406bb3f52` (`6,756` bytes) |
| `dist/taxon.q42` | Sealed & SPARQL-verified | `5d47d5bb85d43f9f9f020b32fb1763aeb667fa6e9522a15830dfb2f2d18b67fc` (`430` quins, `442` lex terms, `35,680` bytes) |
| `dist/index.q42` | Sealed & SPARQL-verified | `809a92124e33cce92fccb31ec47fa4895d4290535eb91cf718f91b0e911e6df9` (`100` quins, `93` lex terms, `8,598` bytes) |
| `source/eucalyptus-regnans.vibe` | Authored (`ECO-WP-04B`) | `1d2db95497d4bddb056a820fa1096670d5830b043db2fb9c7e8f643957fafdee` (`783,582` bytes; `329` semantic parts) |
| `source/actuation.vibe` | Authored (`ECO-WP-04B`) | `888958cf35a860d082063f44e5f74c94953c5ce0907f1c85502d8bc17893ec67` (`14,191` bytes; `InstanceState64`, wind, obligate-seeder fire, rhizosphere mycorrhizal EMF/exudate coupling) |
| `dist/eucalyptus-regnans.hmc` | Sealed & Strict-Reopened | `7fc1e16e47a3a9ea8b76a1e49c3835fe164c038af9a191fac1cceb08252af1e5` (`33,060,428` bytes; `strict_replay_verified: true`) |
| `dist/eucalyptus-regnans.10d` | Exported (`production16`) | `f61aa4c3dd1c913e9d01f4faa212919830b0af970c957a3efd0e63c7628da946` (`3,689,408` bytes; `100,916` verts, `176,312` tris) |
| `dist/eucalyptus-regnans-pbr.10d` | Exported (`production16`) | `87c210b248775f3319396a35b5bb7d86a79b6270a6887a5407839a5ed1421f0c` (`26,509,672` bytes) |
| `dist/eucalyptus-regnans-substrate.m64` | Exported (`strata`) | `011533ef649008e652039a34b5dd156cb3d685a3d60a8db9c28a4464b94da767` (`16,512` bytes; `16×16` @ `-37.68, 145.68, 620 m`) |
| `dist/eucalyptus-regnans-field.emf` | Exported (`EMF v4`) | `24bee3ce67de763b9b9f87ab2ffea069df156c6dd878b385350963d270dbafa4` (`1,777,088` bytes; canopy PAR/NIR/RF + rhizosphere bio-electric `0.85/12.5/32 Hz` waveguide) |
| `dist/receipt.json` | Authored (`ECO-WP-04B`) | Full production + strict reopen + native review receipt (`deaabb207c7c0af9a9f397ffba914d376da948962af0c1a9204abc7b8616dacc`) |
| `previews/front-view-assumed.png` | Rendered (`2048×2048`) | `9731d5847ea0d51113cccd9538c134bb1f5b0e1b0c1f44584b74e473681c020c` (`410,946` bytes) |
| `previews/side-view-assumed.png` | Rendered (`2048×2048`) | `b612aa1cda9dc7a8b5344bcf8a69843dd0eb1683c924af44d2a90ffacb2db426` (`396,395` bytes) |
| `previews/three-quarter-view-assumed.png` | Rendered (`2048×2048`) | `9aa9b65f59bda112a18715a93d1a99f404c6b650ad5d64df62bdb3303f7ea780` (`428,079` bytes) |
| `previews/turnaround.png` | Rendered | `be378c839020f134afe9e2ea3c9c7554dd49c21a927878e73f26418e35995360` (`80,257` bytes) |
| `previews/blueprint.svg` | Rendered | `4fe7627ad59ffb6748e30cfad8fabb8ec089730e7aa33d90bd5fea0c2efa8db3` (`89,689` bytes) |
| `previews/spectral-slice.png` | Rendered (`256×256`) | `01c00f0d90095e44ddce167eeafc758d546377685f8bdacb7479197d21627b62` (`2,557` bytes) |
| `previews/bark-albedo.png` | Synthesized (`256×256`) | `c5061488a69902f68b5362e3a2f529682a2513608a7d5f3fe7ff7b0f024e2678` (`47,568` bytes) |
| `previews/bark-normal.png` | Synthesized (`256×256`) | `43f05a8f00d403182ff9a14b31b14ba19abc81fe804ee10ead423197f9d56fbc` (`36,773` bytes) |
| `previews/bark-orm.png` | Synthesized (`256×256`) | `7714626309374f9e058a32e9f0a738e541bb6b736bebc05d2043c4f746df51d8` (`13,993` bytes) |
| `previews/review-receipt.json` | Sealed (`native-10d-preview/v1`) | `0f5bb81a55601cdcbc5b31afee9daac41b8a0a7328bf5ee9078a0eb5819be6e3` (`3,533` bytes) |
| `dossier/claims.json` | Updated (`incomplete`) | `working-eco-wp-04b`; `TREE-09` passed, `TREE-03..08,10,11` partial; pending `ECO-WP-GATE` |

### 3D CAD Specimen Metrics (`dist/eucalyptus-regnans.10d`, Run `intenteco-ereg-04b-r6`)
- **Bounds (`min` .. `max`, m):** `[-11.2447, -5.2230, -11.6770]` .. `[12.1406, 37.2655, 10.9790]` (`42.49 m` total vertical span including `-5.22 m` taproot, `37.27 m` above ground)
- **Mesh Complexity:** `100,916` vertices, `176,312` triangles, `329` semantic `PO:*` / mycorrhizal parts (`smooth` shading)
- **Organ & Rhizosphere Breakdown:** **5-order subterranean root graph + mycorrhizal network:** `1` deep central taproot (`-5.22 m`), `1` 6-fluted plank buttress collar (`+4.55..-1.20 m`, NO lignotuber), `8` wide-spreading primary lateral structural roots (`8.2–10.3 m` reach matching canopy width), `24` bifurcating secondary lateral roots (`30%, 55%, 80%`), `14` deep vertical sinker roots (`-2.8..-4.75 m`), `28` tertiary/quaternary feeder root fans (`-0.25..-2.05 m`), `16` cream-gold/amber-ochre interlocking mycelial hyphal cords (`-0.25..-2.2 m`, `r = 1.5–9.5 m`) + instanced ectomycorrhizal Hartig-net feeder mantles; **Trunk & Bark Layers:** `3` concentric internal tissue layers (`Heartwood PO:0005849`, `Sapwood PO:0005848`, `VascularCambium PO:0005597`), `1` `11.5 m` fibrous stringybark stocking + `6` feathered vertical tongues (`10.4–14.8 m`), `1` smooth cream upper bole + `6` bark mottling patches + `16` hanging decorticating ribbons (`4.2–7.8 m`); **5-order canopy branch graph:** `3` S-curved ascending co-dominant leaders (`leader_alpha`, `leader_beta`, `leader_gamma`), `6` 3D S-curved primary boughs, `42` Order 2 secondary limbs (`30%, 50%, 70%, 85%, 100%` forks), `84` Order 3 tertiary branchlets, `48` Order 4 quaternary terminal twigs/umbel peduncles (`n = 2.49`), `8` epicormic bud nodes; **3-layer foliage & reproductive blooms:** `504` deep-green inner proximal leaves + `1,512` mid-canopy cascading curtains + `960` bright-green young outer shoots (`2,976` curved falcate blades across `132` clusters), `352` paired axillary clavate bud umbels, `288` white staminal flower blooms, `288` cupular-obconical capsules.
