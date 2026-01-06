# Structure Proposal for Magnetic Effects of Electric Current

## Chapter Overview
- **Total Pages:** 70
- **Main Topics:** 13 sections
- **Content Type:** Theory, Examples, Exercises, Solutions

## Proposed File Structure

### 1. Main Index File
```
04-magentic_effects_of_current/index.md
```
- Parent index with navigation to all sections
- Lists all 13 main sections
- Links to exercises and solutions

### 2. Theory Sections (13 files)

Based on Chapter Topics from page 1:

1. **01-magnet-and-magnetism.md** (Pages ~2-3)
   - Magnet and Magnetism
   - Introduction to magnetism
   - Types of magnets (natural, artificial)
   - Properties of magnets

2. **02-magnetic-field.md** (Pages ~3-4)
   - Definition of magnetic field
   - Magnetic field lines
   - Representation of magnetic field
   - Units (Tesla, Gauss)
   - Vector nature of magnetic field

3. **03-magnetic-field-lines.md** (Pages ~4)
   - Properties of magnetic field lines
   - Direction of field lines
   - Density and strength relationship
   - Field line patterns

4. **04-classification-of-magnetic-materials.md** (Pages ~5)
   - Diamagnetic materials
   - Paramagnetic materials
   - Ferromagnetic materials
   - Examples of each type

5. **05-earths-magnetic-field.md** (Pages ~5-6)
   - Earth as a magnet
   - Origin of Earth's magnetism
   - Features of Earth's magnetic field
   - Magnetic axis and geographic axis

6. **06-magnetic-effect-of-current.md** (Pages ~10-15)
   - Oersted's experiment
   - Magnetic field due to straight current carrying wire
   - Right-hand thumb rule
   - Magnetic field due to circular coil
   - Solenoid
   - Permeability

7. **07-force-on-moving-charge.md** (Pages ~15-20)
   - Force on a moving charge in magnetic field
   - Lorentz force
   - Fleming's left-hand rule
   - Motion of charged particles

8. **08-force-on-current-carrying-conductor.md** (Pages ~20-25)
   - Force on current carrying conductor
   - Force between parallel current carrying wires
   - Applications (Loud speaker, Moving coil galvanometer)

9. **09-electric-motor.md** (Pages ~25-30)
   - Working principle
   - Construction
   - Applications
   - Improvements

10. **10-electromagnetic-induction.md** (Pages ~30-35)
    - Faraday's law
    - Lenz's law
    - Induced EMF
    - Induced current
    - Examples

11. **11-electric-generator.md** (Pages ~35-40)
    - AC Generator
    - DC Generator
    - Working principle
    - Construction
    - Applications

12. **12-transformer.md** (Pages ~40)
    - Working principle
    - Step-up transformer
    - Step-down transformer
    - Applications

13. **13-household-electric-circuit.md** (Pages ~40-45)
    - Three-wire system
    - Live wire, Neutral wire, Earth wire
    - Color coding
    - Safety measures
    - Fuses and circuit breakers

### 3. Exercise Files

14. **concept-application-exercise-1.md** (Pages ~45-50)
    - Very Short Answer Type Questions
    - Short Answer Type Questions

15. **concept-application-exercise-2.md** (Pages ~50-60)
    - Multiple Choice Questions
    - Assertion-Reason Type Questions

16. **concept-application-exercise-3.md** (Pages ~60-65)
    - Correct Answer Type Questions
    - Exemplar Type Questions

### 4. Solution Files

17. **concept-application-exercise-1-solutions.md**
18. **concept-application-exercise-2-solutions.md**
19. **concept-application-exercise-3-solutions.md**

### 5. Supporting Files

20. **images/** directory
    - All circuit diagrams, figures, and illustrations
    - Naming convention: `04-fig1.png`, `04-fig2.png`, etc.

## Page Distribution Estimate

- **Pages 1:** Chapter Topics/Index
- **Pages 2-6:** Sections 01-05 (Basic concepts)
- **Pages 7-15:** Section 06 (Magnetic Effect of Current)
- **Pages 16-25:** Sections 07-08 (Forces)
- **Pages 26-30:** Section 09 (Electric Motor)
- **Pages 31-35:** Section 10 (Electromagnetic Induction)
- **Pages 36-40:** Sections 11-12 (Generator, Transformer)
- **Pages 41-45:** Section 13 (Household Circuit)
- **Pages 46-65:** Exercises (3 sets)
- **Pages 66-70:** Solutions/Answers

## File Naming Convention

- Section files: `01-magnet-and-magnetism.md`, `02-magnetic-field.md`, etc.
- Exercise files: `concept-application-exercise-1.md`, etc.
- Solution files: `concept-application-exercise-1-solutions.md`, etc.
- Images: `04-fig1.png`, `04-fig2.png`, etc. (or section-specific like `06-fig1.png`)

## Navigation Order

```
nav_order: 4 (for index.md)
nav_order: 1-13 (for theory sections)
nav_order: 14-16 (for exercises)
nav_order: 17-19 (for solutions)
```

## Next Steps

1. Create `index.md` with structure
2. Extract and create each theory section markdown file
3. Extract exercises and create exercise files
4. Extract solutions and create solution files
5. Identify and extract all images
6. Create SVG diagrams where needed (similar to electricity chapter)

