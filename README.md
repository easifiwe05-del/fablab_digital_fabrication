# Foundations of Modeling & Fabrication
## From Design Intent to Physical Reality

**Master's Level Course**

---

## 🏠 Home

### Course Overview

> **Core Philosophy**  
> Design and making are inseparable. This course bridges the gap between digital modeling and physical fabrication, treating both as integrated aspects of the design process.

A comprehensive journey through computational design, digital fabrication, and the seamless integration of modeling and making in contemporary design practice.

**Course Tags:** Master's Level | Design & Technology | Digital Fabrication

---

## 📖 Course Overview

### Why Modeling & Fabrication Matter

Contemporary design practice has fundamentally shifted. Design today is **computational**, **material-driven**, and **production-aware**. Fabrication is no longer merely an end step—it actively shapes design decisions from the earliest conceptual stages.

This transformation is essential across multiple disciplines:

- **Architecture:** From parametric facades to robotically fabricated structures
- **Product Design:** Rapid prototyping, mass customization, and user-centered iteration
- **Engineering:** Simulation-driven design and additive manufacturing
- **Research:** Physical computing, material experimentation, and speculative design

### The Design-to-Fabrication Continuum

The design process follows an iterative cycle:

**Design → Model → Prototype → Fabricate → Evaluate → [Repeat]**

!!! warning "Critical Insight"
    This process is **iterative, not linear**. Feedback occurs at every stage, and failure serves as a powerful learning tool. Each cycle refines understanding and improves outcomes.

**Key Principles:**

1. **Design** - Conceptualize and define intent
2. **Model** - Create digital representations
3. **Prototype** - Build physical tests
4. **Fabricate** - Produce final artifacts
5. **Evaluate** - Assess and learn from outcomes

The cycle repeats, incorporating learnings at each stage.

---

## 🖥️ Digital Modeling

Digital modeling extends far beyond the representation of geometric form. It encompasses the encoding of design logic, behavioral systems, and intelligent relationships that define how designs respond to parameters, constraints, and environmental conditions.

### Types of Modeling Approaches

#### 1. Geometric Modeling
Traditional 3D modeling focusing on explicit form definition. Tools like Rhino, Blender, and SolidWorks enable precise control over surfaces, volumes, and spatial relationships.

**Applications:** Product design, architectural visualization, concept development

#### 2. Parametric Modeling
Design through relationships and dependencies. Changes to parameters propagate throughout the model, enabling rapid design exploration and variation generation.

**Applications:** Adaptive structures, mass customization, optimization studies

#### 3. Rule-Based Modeling
Systems defined by algorithms and logical rules rather than explicit geometry. Enables generative design and emergent form-finding.

**Applications:** Pattern generation, complex systems, computational design

#### 4. Simulation & Data-Driven Models
Models that respond to physical phenomena—structural analysis, thermal performance, fluid dynamics—or external datasets to inform design decisions.

**Applications:** Performance-based design, environmental analysis, predictive modeling

### Modeling Workflow Documentation

A robust modeling workflow integrates conceptual thinking with technical execution:

1. **Design Intent Definition:** Clearly articulate goals, constraints, and success criteria
2. **Method Selection:** Choose modeling approach based on design complexity and fabrication requirements
3. **Parameter Identification:** Define which aspects should remain fixed and which should be variable
4. **Model Development:** Build the digital representation with fabrication constraints in mind
5. **Validation:** Test the model against design intent and physical feasibility
6. **Documentation:** Capture decisions, iterations, and rationale throughout the process

!!! success "Best Practice"
    Models should encode design intelligence—the relationships, constraints, and logic that make the design work. A well-structured model anticipates fabrication challenges and enables rapid iteration.

### Essential Modeling Considerations

| Consideration | Description | Impact |
|--------------|-------------|---------|
| **Scale & Units** | Consistent dimensional system throughout the model | Prevents fabrication errors and material waste |
| **Tolerance Planning** | Account for manufacturing precision limits | Ensures parts fit and assemblies work as intended |
| **Material Properties** | Model behavior reflects chosen materials | Realistic performance prediction |
| **Assembly Logic** | Consider how components connect | Buildability and structural integrity |
| **File Management** | Organized versioning and documentation | Traceability and collaboration |

### Key Modeling Software

- **Rhino + Grasshopper:** Parametric design and NURBS modeling
- **Fusion 360:** Integrated CAD/CAM for product design
- **Blender:** Open-source 3D creation suite
- **SolidWorks:** Professional engineering CAD
- **Processing/Python:** Computational design scripting

---

## 🔧 Fabrication Logic

Fabrication transforms digital models into physical artifacts through the strategic application of materials, machines, and processes. Understanding fabrication logic means recognizing that **the method of making is itself a design decision** that shapes form, materiality, and meaning.

### Digital Fabrication Paradigms

Contemporary fabrication methods can be categorized into four primary paradigms:

#### 🔻 Subtractive Fabrication

**Process:** Removing material from a solid block through cutting, milling, drilling, or ablation

**Technologies:**
- CNC milling
- Laser cutting
- Waterjet cutting
- Lathe turning

**Advantages:**
- High precision and accuracy
- Excellent surface finish
- Established workflows and tooling
- Wide material compatibility

**Constraints:**
- Material waste (removed material is lost)
- Tool access limitations
- Typically 2.5D or requires multi-axis machines
- Undercuts require complex setups

**Materials:** Wood, metals, plastics, foam, composites

---

#### ➕ Additive Fabrication

**Process:** Building objects layer by layer through material deposition

**Technologies:**
- FDM/FFF (Fused Deposition Modeling)
- SLA/DLP (Stereolithography)
- SLS (Selective Laser Sintering)
- Binder jetting
- Material jetting

**Advantages:**
- Complex geometries without additional cost
- Minimal material waste
- No tooling required
- Internal structures and assemblies possible
- Design freedom

**Constraints:**
- Visible layer lines
- Support structures required for overhangs
- Material limitations (not all materials can be printed)
- Post-processing often needed
- Build time can be lengthy

**Materials:** Polymers (PLA, ABS, PETG, Nylon), resins, metals (with specialized machines), ceramics, composites

---

#### 🔄 Formative Fabrication

**Process:** Shaping material through force, heat, or pressure using molds and formwork

**Technologies:**
- Casting (concrete, resin, metal)
- Vacuum forming
- Injection molding
- Bending and stamping
- Thermoforming

**Advantages:**
- Material efficiency
- High-volume production capability
- Organic, flowing forms
- Material optimization through stress distribution
- Smooth surface finishes

**Constraints:**
- Requires tooling/molds (upfront cost)
- Draft angles required for demolding
- Undercut limitations
- Process-specific material requirements

**Materials:** Plastics, metals, concrete, composites, textiles, elastomers

---

#### 🔀 Hybrid Fabrication

**Process:** Combining multiple fabrication paradigms in sequence or simultaneously

**Examples:**
- 3D printed molds for casting
- Additive + subtractive machining
- Laser-cut assembled components
- CNC-formed pieces with 3D printed connectors

**Advantages:**
- Optimizes strengths of each method
- Increased geometric complexity
- Material diversity in single object
- Cost optimization across scales

**Constraints:**
- Workflow complexity
- Multiple machines/skills required
- Registration and alignment challenges
- Process planning complexity

**Materials:** Multi-material assemblies combining any of the above

---

!!! info "Key Insight"
    **Fabrication method is a design choice, not an afterthought.** The selected paradigm influences geometry, materiality, cost, sustainability, and aesthetic expression. Expert designers think through fabrication from the earliest conceptual stages.

---

### Materials & Tolerance

Materials are **active participants** in the design process, not passive substrates. Each material brings inherent properties, behaviors, and constraints that shape design possibilities.

#### Material Properties to Consider

**Physical Properties:**
- Strength (tensile, compressive, shear)
- Elasticity and flexibility
- Hardness and durability
- Density and weight
- Thermal expansion and conductivity

**Fabrication Behavior:**
- Cutting/machining characteristics
- Layer adhesion (for additive processes)
- Heat distortion and warping
- Tool wear effects
- Post-processing requirements

**Real-World Constraints:**
- Dimensional tolerance (±0.05mm to ±0.5mm typical)
- Material deformation under stress
- Environmental variation (humidity, temperature)
- Aging and degradation over time
- Assembly clearances and fit

#### Designing for Tolerance

Real-world fabrication invariably introduces error, deformation, and tolerance limits. Expert designers anticipate these imperfections:

- **Design for tolerance:** Build in clearances (typically 0.2-0.5mm for tight fits)
- **Expect variation:** Test materials under realistic conditions
- **Embrace imperfection:** Sometimes "defects" become design features
- **Prototype early:** Physical tests reveal material behavior better than simulation alone
- **Plan for adjustment:** Include tuning mechanisms where precision is critical

!!! warning "Critical Point"
    **Designers must design for imperfection.** No fabrication process is perfectly accurate. Understanding and accommodating real-world constraints is a hallmark of experienced practitioners.

---

### Machine Selection & Constraints

| Machine Type | Build Volume (typical) | Precision | Best For |
|-------------|----------------------|-----------|----------|
| **Laser Cutter** | 600×400mm | ±0.1mm | 2D parts, sheet materials, fast iteration |
| **CNC Mill (3-axis)** | 600×400×150mm | ±0.05mm | Precise parts, metal, 2.5D geometry |
| **FDM 3D Printer** | 200×200×200mm | ±0.2mm | Complex forms, rapid prototypes, low-cost iteration |
| **SLA Printer** | 145×145×175mm | ±0.05mm | High detail, smooth surfaces, small parts |
| **CNC Mill (5-axis)** | Varies widely | ±0.02mm | Complex 3D geometry, undercuts, production parts |
| **Waterjet Cutter** | 2000×3000mm | ±0.1mm | Thick materials, no heat-affected zone |

#### Fabrication Workflow Considerations

1. **File Preparation:** Export appropriate formats (STL, DXF, G-code)
2. **Material Setup:** Secure workpiece, verify dimensions
3. **Machine Calibration:** Home axes, check tool offsets
4. **Test Runs:** Simulate or run air passes before cutting
5. **Production:** Monitor first layer/pass carefully
6. **Post-Processing:** Cleanup, finishing, assembly

---

## 🔬 Prototyping & Iteration

Prototyping is not merely a step in the process—**it is a research methodology**. Prototypes serve as research tools, assumption tests, and evidence in design inquiry. Through iterative making, designers develop embodied knowledge that cannot be gained through digital modeling alone.

### The Role of Prototyping

#### Research Tool
Prototypes generate knowledge through making. They reveal material behaviors, structural performance, ergonomic qualities, and aesthetic effects that are difficult to predict digitally.

**Example uses:**
- Testing material flexibility and strength
- Understanding scale and proportion
- Evaluating user interaction
- Exploring aesthetic qualities

#### Assumption Test
Every design contains assumptions. Prototypes challenge these assumptions, exposing flawed thinking and revealing opportunities for improvement.

**Common assumptions to test:**
- "This joint will be strong enough"
- "Users will understand this interface"
- "This part can be manufactured"
- "The material will behave as expected"

#### Communication Device
Physical artifacts communicate design intent more effectively than drawings or models. They enable stakeholder feedback and collaborative refinement.

#### Design Evidence
In research and professional contexts, prototypes serve as evidence of design inquiry, demonstrating feasibility and documenting the design process.

---

### The Iteration Process

Effective iteration follows a structured approach that maximizes learning while managing resources:

1. **Define Hypothesis:** What are you testing? What do you expect to learn?
2. **Design the Test:** What's the minimal prototype needed to test your hypothesis?
3. **Fabricate:** Build quickly, focusing on the aspects under investigation
4. **Evaluate:** Systematically assess performance against criteria
5. **Document:** Record observations, measurements, and insights
6. **Revise:** Apply learnings to the next iteration

!!! success "Prototyping Strategy"
    Start with **low-fidelity prototypes** to test fundamental concepts. Progressively increase fidelity as understanding deepens. Reserve high-fidelity prototypes for final validation.

#### Prototyping Fidelity Levels

| Fidelity Level | Purpose | Methods | Time Investment |
|---------------|---------|---------|-----------------|
| **Low** | Concept testing, scale studies | Cardboard, foam, sketches | Minutes to hours |
| **Medium** | Functional testing, user feedback | 3D prints, laser-cut parts | Hours to days |
| **High** | Final validation, presentation | Finished materials, polish | Days to weeks |

---

### Parametric Thinking & Prototyping

Parametric thinking enables **variation without complete redesign**. By identifying and controlling key parameters, designers can explore design space efficiently and generate families of related solutions.

**Benefits of parametric prototyping:**

- Rapid exploration of design variations
- Systematic testing of parameter relationships
- Mass customization capabilities
- Optimized performance across different scenarios
- Documentation of design logic and dependencies

**Example Parameters:**
- Dimensions (height, width, thickness)
- Repetition counts (number of ribs, panels, modules)
- Angles (slope, rotation, taper)
- Material properties (flexibility, color, texture)

---

### Learning from Failure

**Failure is not the opposite of success—it is a component of learning.** Well-documented failures often teach more than successful outcomes.

| Failure Type | Common Causes | Learning Opportunity |
|-------------|---------------|---------------------|
| **Structural Failure** | Inadequate support, material limits, stress concentration | Understanding load paths, material behavior, safety factors |
| **Dimensional Inaccuracy** | Tolerance stack-up, thermal expansion, machine calibration | Precision requirements, assembly clearances, quality control |
| **Material Defects** | Improper settings, incompatible materials, environmental factors | Material science, process optimization, testing protocols |
| **Assembly Problems** | Poor planning, interference, inaccessibility | Design for assembly, exploded views, sequence planning |

#### Documenting Failures

!!! warning "Document Everything"
    Failures are only valuable if they're documented:
    
    - Photograph failed prototypes from multiple angles
    - Record machine settings and environmental conditions
    - Analyze root causes systematically
    - Share findings with your team
    - Propose solutions for next iteration

**Failure documentation template:**

```
FAILURE REPORT #[X]
Date: [Date]
Prototype: [Name/Version]
Failure Type: [Structural/Dimensional/Material/Assembly]
Description: [What happened]
Root Cause: [Why it happened]
Settings/Conditions: [Machine settings, materials, environment]
Lessons Learned: [Key insights]
Next Steps: [How to address in next iteration]
```

---

## 💭 Reflection & Critical Analysis

Reflection transforms experience into expertise. Critical analysis of the design and fabrication process develops **metacognitive awareness**—the ability to think about thinking, and make about making.

### Lessons Learned

Effective reflection addresses multiple dimensions of the design and fabrication experience:

#### Technical Insights
- What technical skills were developed?
- Which tools and processes proved most effective?
- What would you do differently from a technical standpoint?
- What unexpected technical challenges emerged?

#### Process Understanding
- How did the design evolve from concept to completion?
- What role did prototyping play in shaping the outcome?
- How did physical making inform digital modeling?
- Which iteration was most significant, and why?

#### Material Knowledge
- How did materials behave compared to expectations?
- What surprises emerged during fabrication?
- How did material constraints shape the design?
- What material combinations worked well or poorly?

#### Conceptual Development
- How did your design thinking evolve?
- What assumptions were challenged?
- What new questions emerged from the work?
- How does the project connect to broader contexts?

---

### Critical Questions for Reflection

Use these questions to guide your reflective writing:

1. What was the relationship between your initial design intent and the final outcome?
2. How did fabrication constraints influence your design decisions?
3. What role did iteration play in refining your work?
4. Which failures were most instructive? What did they teach you?
5. How did digital modeling and physical making inform each other?
6. What would you prioritize differently in a future project?
7. How does your work connect to broader contexts—cultural, environmental, technological?
8. What surprised you most about the process?
9. If you could start over, what would you change?
10. What are the next questions this project raises?

---

### Ethics & Sustainability

Design and fabrication carry **ethical responsibilities**. Every design decision has consequences—material, environmental, social, and cultural. Critical designers consider these implications intentionally.

#### Material Waste & Energy

Fabrication consumes resources and energy. Responsible designers minimize waste through:

- **Efficient nesting:** Optimize material layouts to reduce scrap
- **Material selection:** Choose recyclable, renewable, or reclaimed materials
- **Process optimization:** Minimize energy consumption and processing time
- **Lifecycle thinking:** Consider extraction, use, and disposal impacts

**Example:** A laser-cut project using plywood generates sawdust and offcuts. Could offcuts be used for smaller components? Is FSC-certified plywood available? Can the design be optimized to reduce material use?

#### Local vs Global Production

Where and how objects are made matters:

**Local Production:**
- ✅ Reduces transportation carbon footprint
- ✅ Supports local economies and makers
- ✅ Enables direct collaboration and iteration
- ❌ May have limited material/technology access
- ❌ Can be more expensive per unit

**Global Manufacturing:**
- ✅ Access to specialized technologies and materials
- ✅ Economies of scale for large production runs
- ❌ High transportation impact
- ❌ Less control over labor and environmental standards

**Consider the trade-offs:** What scale of production? What technologies are required? What's the environmental impact of shipping vs. local constraints?

#### Design for Longevity

Create objects that last and adapt:

- **Reuse:** Can the object serve multiple purposes?
- **Repair:** Can components be replaced when they fail?
- **Disassembly:** Can materials be recovered at end-of-life?
- **Timeless design:** Will it remain relevant, or contribute to disposable culture?
- **Modularity:** Can it evolve and adapt to changing needs?

#### Critical Making

!!! info "Critical Question"
    **Should everything that can be made, be made?**
    
    This fundamental question should guide all design and fabrication work. Capability without purpose leads to waste and harm.

**Questions to ask before making:**

- What value does this create?
- Who benefits from this object existing?
- What are the unintended consequences?
- Does this solve a real problem or create unnecessary consumption?
- Could the same goal be achieved with less material/energy?

---

### Sustainable Fabrication Strategies

**Before Fabrication:**
1. Question necessity—does this need to be made?
2. Simulate digitally to minimize physical prototypes
3. Choose sustainable materials and local sources
4. Design for minimal material use

**During Fabrication:**
1. Optimize toolpaths and nesting layouts
2. Minimize support structures (additive)
3. Use efficient machine settings
4. Repurpose scraps for test pieces

**After Fabrication:**
1. Document processes to avoid duplication
2. Share designs and knowledge openly
3. Plan for disassembly and material recovery
4. Consider product service systems over ownership

---

## 🎯 Learning Outcomes

By completing this course, students develop comprehensive competencies that bridge digital and physical design practices.

### Core Competencies

#### 1. Design with Fabrication Logic
Integrate fabrication considerations from the earliest design stages. Understand how manufacturing methods shape form, material choices, and design feasibility. Make informed decisions about fabrication paradigms.

**You will be able to:**
- Select appropriate fabrication methods for design goals
- Anticipate manufacturing constraints during conceptual design
- Design with tolerance and assembly in mind
- Optimize designs for specific fabrication processes

#### 2. Understand Material Behavior
Recognize materials as active design participants with inherent properties, constraints, and possibilities. Anticipate material performance under fabrication and use conditions.

**You will be able to:**
- Select materials based on performance requirements
- Predict material behavior during fabrication
- Design around material constraints creatively
- Test and document material performance

#### 3. Use Modeling as Research
Employ digital modeling not just for representation, but as a tool for inquiry, exploration, and knowledge generation. Build models that encode design intelligence and enable rapid iteration.

**You will be able to:**
- Create parametric models that enable variation
- Encode design logic and relationships
- Use simulation to predict performance
- Iterate rapidly through digital exploration

#### 4. Translate Ideas into Buildable Systems
Bridge the gap between concept and realization. Develop the technical skills, material knowledge, and systematic thinking required to transform design intent into physical reality.

**You will be able to:**
- Move fluidly between digital and physical domains
- Troubleshoot fabrication challenges
- Document processes comprehensively
- Learn from failures and iterate effectively

---

### Competency Framework

| Competency Area | Skills Developed | Assessment Methods |
|----------------|------------------|-------------------|
| **Digital Modeling** | Parametric design, CAD proficiency, file preparation, design intelligence encoding | Model quality, documentation, iteration evidence |
| **Fabrication Execution** | Machine operation, material handling, process optimization, quality control | Prototype quality, technical precision, safety compliance |
| **Design Thinking** | Problem framing, iterative refinement, failure analysis, critical reflection | Design evolution, documented learning, conceptual depth |
| **Documentation** | Visual communication, process recording, technical writing, knowledge sharing | Portfolio quality, clarity of explanation, comprehensiveness |
| **Critical Awareness** | Ethical consideration, sustainability thinking, contextual understanding | Reflective depth, consideration of impact, responsible practice |

---

### Beyond the Course

The skills, knowledge, and critical awareness developed in this course extend far beyond academic contexts:

- **Professional Practice:** Integration of digital and physical workflows is essential in contemporary design studios
- **Research:** Material exploration and computational design drive innovation in academic and industrial research
- **Entrepreneurship:** Rapid prototyping and digital fabrication enable small-scale manufacturing and product development
- **Teaching:** Understanding the design-to-fabrication continuum prepares future educators
- **Advocacy:** Critical awareness of sustainability and ethics informs responsible design leadership

!!! success "Documentation as Design Practice"
    **Documentation is not an afterthought—it is part of the design process itself.** Through documenting your work, you develop clarity of thought, communicate complex ideas, and contribute to the collective knowledge of the design community.

---

## 📚 Documentation Best Practices

This documentation serves as a template for recording your own design and fabrication journey. Effective documentation includes:

### Visual Documentation

**Essential Images:**
- High-quality photographs of prototypes and final works
- Screenshots of digital modeling process with annotations
- Diagrams explaining design logic and parametric relationships
- Process videos showing fabrication techniques
- Before/after comparisons showing iteration

**Photography Tips:**
- Use consistent lighting and backgrounds
- Show scale with reference objects or measurements
- Capture details and overall views
- Document failures as well as successes
- Include images of work-in-progress

### Written Documentation

**Content to Include:**
- Clear explanation of design intent and goals
- Description of methods and justification of choices
- Technical specifications and settings
- Analysis of results and outcomes
- Honest reflection on successes and failures
- Future directions and open questions

**Writing Style:**
- Be clear and concise
- Use active voice
- Explain technical terms
- Tell the story of your process
- Be honest about challenges

### Technical Documentation

**Files and Specifications:**
- Source files (CAD models, parametric scripts)
- Fabrication files (toolpaths, STLs, cutting layouts)
- Material specifications and sources
- Machine settings and parameters
- Bill of materials and cost analysis

**File Organization:**
```
project-name/
├── docs/
│   ├── index.md
│   ├── modeling.md
│   ├── fabrication.md
│   └── reflection.md
├── images/
│   ├── process/
│   ├── prototypes/
│   └── final/
├── files/
│   ├── cad/
│   ├── toolpaths/
│   └── stl/
└── mkdocs.yml
```

---

### Documentation Website Structure

Your MkDocs site should include these minimum pages:

1. **Home (index.md)**
   - Course overview
   - Student introduction
   - Project summary

2. **Digital Modeling (modeling.md)**
   - Modeling approach and rationale
   - Screenshots with annotations
   - Source files and parameters
   - Design iterations

3. **Fabrication Logic (fabrication.md)**
   - Machine selection and settings
   - Material choices
   - Constraints and solutions
   - Process documentation

4. **Prototyping & Iteration (prototyping.md)**
   - Test sequences
   - Failure analysis
   - Improvements across iterations
   - Lessons learned

5. **Reflection (reflection.md)**
   - Critical analysis
   - Lessons learned
   - Future directions
   - Ethical considerations

---

### MkDocs Configuration

Basic `mkdocs.yml` configuration:

```yaml
site_name: Your Project Name
site_description: Foundations of Modeling & Fabrication Documentation
site_author: Your Name

theme:
  name: material
  palette:
    primary: blue
    accent: orange
  features:
    - navigation.tabs
    - navigation.sections
    - toc.integrate
    - search.suggest

nav:
  - Home: index.md
  - Digital Modeling: modeling.md
  - Fabrication Logic: fabrication.md
  - Prototyping & Iteration: prototyping.md
  - Reflection: reflection.md

markdown_extensions:
  - admonition
  - pymdownx.details
  - pymdownx.superfences
  - tables
  - attr_list
  - md_in_html

plugins:
  - search
```

---

!!! info "Remember"
    Your documentation website is a **living portfolio**. Update it regularly, include work-in-progress, and don't wait until projects are "perfect." The messiness of the process is valuable evidence of learning.

---

## 🚀 Getting Started with MkDocs

### Installation

```bash
# Install MkDocs with Material theme
pip install mkdocs-material

# Create new project
mkdocs new my-project
cd my-project

# Start local server
mkdocs serve
```

### Local Development

- Edit markdown files in the `docs/` folder
- Preview changes at `http://127.0.0.1:8000`
- Changes auto-reload in browser

### Building & Deployment

```bash
# Build static site
mkdocs build

# Deploy to GitHub Pages
mkdocs gh-deploy
```

---

## Additional Resources

### Recommended Tools

**Digital Modeling:**
- Rhino 3D + Grasshopper
- Fusion 360
- Blender
- FreeCAD (open source)

**Documentation:**
- MkDocs Material
- GitHub Pages
- Markdown editors (Obsidian, Typora, VS Code)

**Version Control:**
- Git/GitHub for file management
- Organized folder structures
- Regular backups

### Further Reading

- **"Digital Fabrications"** by Lisa Iwamoto
- **"Fabricate"** series by UCL
- **"The New Maker Movement"** by Peter Troxler
- **Material Connexion** online database
- **Thingiverse, GrabCAD** for design inspiration

---

## Conclusion

This course establishes foundations for integrating digital design and physical fabrication. By treating modeling and making as inseparable processes, students develop the technical skills, critical thinking, and ethical awareness needed for contemporary design practice.

**Key Takeaways:**

✅ Design and making are inseparable  
✅ Fabrication method is a design choice  
✅ Materials are active design participants  
✅ Iteration and failure drive learning  
✅ Documentation is part of design practice  
✅ Ethics and sustainability matter  

---

*Master's Level Course | Foundations of Modeling & Fabrication*  
*From Design Intent to Physical Reality*
