# Reinforced Concrete Beam Loads: Professor's Board Method

Status: source-grounded study notes transcribed from the user's uploaded Lecture 2 and classroom board photos. These notes preserve the professor's approach and distinguish readable board content from uncertain handwriting.

## Exam question data visible in the uploaded slide/photo
- Slab thickness: 12 cm
- Concrete strength: fcu = 250 kg/cm²
- Steel yield strength: fy = 3600 kg/cm²
- Live load: 300 kg/m² = 0.300 t/m²
- Floor covering: 150 kg/m² = 0.150 t/m²
- Floor height: 3.0 m
- Walls stated on outer beams
- Plan grid dimensions visible: A-B = 1.5 m, B-C = 3.0 m, C-D = 5.0 m; grid 1-2 = 4.0 m, 2-3 = 2.0 m
- Required beams: B1, B2, B3, B4 and B6

## Professor's board workflow

### 1. Calculate ultimate slab area load
The board uses the larger of the lecture combinations. In this worked example, the board writes:

Wsu = 1.5(D.L + L.L)

Wsu = 1.5[(2.5 × 0.12) + 0.15 + 0.30] = 1.125 t/m²

Use 1.125 t/m² as the worked-example ultimate slab load when using this exact professor method and these question values.

### 2. For each beam, identify the three terms
The board labels B1 as:

O.W + Wall + Slab

The same concept appears throughout the board calculations:
- Own weight of beam
- Wall load, if present
- Slab contribution, using the tributary/equivalent distribution sketched for that beam

Do not automatically add a wall to a beam if the professor's specific worked line explicitly has +0. Check the plan and the exact beam line; flag inconsistencies with the prompt.

### 3. Beam self-weight
Lecture 2 gives:

wb = b × t × γc

Lecture 2 uses γc = 2.5 t/m³. Apply the professor's factor shown in the specific board line (the board commonly writes 1.4 × b × t × 2.5).

Board example for B1 appears to use b = 0.125 m and t = 0.5 m:

1.4 × 0.125 × 2.5 × 0.5 = 0.21875 ≈ 0.219 t/m

### 4. Wall-load treatment shown on the board
Lecture 2 slide 9 states:
- wall = h × γw × 0.8 for moment
- wall = h × γw × 1.0 for shear
- γw = 250–300 for half-brick; γw = 500 for one-brick (as written on the lecture slide)

However, the photographed professor board uses a separate worked expression for wall terms with:
- a factor 1.4
- a wall unit-weight value apparently written as 1.4 t/m³ in the worked B3 line
- wall thickness 0.25 m for full-brick
- wall height as floor height minus beam depth

Visible B3 wall expression appears to be:
1.4 × 1.4 × (3 − 0.6) × 0.25

This appears to equal 1.176 t/m. The handwriting/factor placement should be rechecked against a clearer image before treating this value as definitive.
For every new problem, prioritize reproducing the exact board method if the professor's line is legible, and explicitly distinguish it from the simplified Lecture 2 slide formula. Never silently swap one for the other.

### 5. Slab contribution
Use the slab load and the geometric tributary shape written/sketched on the board. For B1, the board's visible expression appears to be:

[((0.5 × 4 × 2) + ((4 + 1)/2 × 1.5)) / 4] × 1.125

The board labels the resulting B1 load about 2.4 t/m. From visual inspection, the expression may be blurred/ambiguous, so keep the professor's boxed result ≈ 2.4 t/m as a visual transcription, not as an independently verified exact calculation. Recheck with a clearer crop before relying on the precise term transcription.

### 6. Board results visible in photos
These are visual transcriptions of the boxed numbers, not a complete independent re-solve:
- Ultimate slab load: 1.125 t/m²
- B1: about 2.4 t/m (board line includes own weight + wall + slab labels, but appears to show wall term +0)
- Beam B2: about 3.075 t/m (one photo's heading appears possibly "B2"; verify)
- Beam B3: about 5.5 t/m
- For B3, the professor further sketches/labels piecewise sections:
  - AB: 3.6 t/m over 2 m
  - BC: 4.6 t/m over 4 m
- Beam B6 reactions/sketch: concentrated load of 4.8 t shown on the span sketch, with B6 distributed load about 2.98 t/m, length 8 m, and reactions about YA = 1.92 t and YB = 13.72 t (read from the board photo; verify labels if used).

## Table lookup for two-way slab equivalents (Lecture 2)
Lecture 2 formula:
- Wα = Ws × α × (Ls/2), equivalent load for maximum bending moment
- Wβ = Ws × β × (Ls/2), equivalent load for maximum shear
- Ws = ts × γc + flooring + live load
- If using α and β, calculate dead-load equivalents (g) and live-load equivalents (p) separately; compare Wsu = 1.4g + 1.6p against Wsu = 1.5(g + p), and choose the bigger.
- Lecture table headings list ratio entries 1.0 to 2.0; α = .667, .725, .769, .803, .829, .852, .870, .885, .897, .908, .917; β = .500, .545, .583, .615, .643, .667, .688, .706, .722, .737, .750.
- The worked lecture example uses α = .81 and β = .62 at r = 4/3. Follow the closest table-value instruction only when that is the requested classroom method. Do not invent an exact coefficient not present in the lecture.

## Answering rules for future problems
1. Use only the user's lecture, question drawing, and professor board method unless explicitly asked for outside verification.
2. Equation first, then substitution.
3. Round reported results to exactly 3 decimal places.
4. Keep explanations short: one calculation step per line, not lengthy prose.
5. Check which beams have walls and identify wall type/parameters from the problem before calculating.
6. Follow the professor's specific load-distribution sketches for each beam; do not assume all beams have identical loading.
7. For main beams/girders receiving secondary-beam reactions, include concentrated loads as shown on the board.
8. When handwriting is unclear or board calculation conflicts with the question statement/lecture slide, flag the discrepancy rather than guessing.
9. Do not treat inferred or generated annotated diagrams as source evidence. The original uploaded board photos and lecture slide control.

## Source index
- User-uploaded Lecture 2.pptx, especially slides 5–9.
- Original uploaded classroom board photos 285836.jpg, 285837.jpg, 285838.jpg.
- Original uploaded Question 2 photo 285829.jpg.
- Additional close-ups of Question 2 and board solution photos 286151.jpg–286155.jpg.
