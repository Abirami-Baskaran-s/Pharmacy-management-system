
# Abirami's Contributions to Pharmacy Management System

**Student ID:** 270780482  
**Role:** Process Analyst & Sequence Diagram Specialist  
**Course:** MBI801 - Information Systems Analysis and Design  
**Project:** Pharmacy Management System

---

##  Overview of My Contributions

As the **Process Analyst** for the Pharmacy Management System project, I was responsible for documenting the detailed behavioral aspects of our two core use cases through comprehensive use case descriptions and system sequence diagrams.

---

##  Key Deliverables

### 1. Detailed Use Case Descriptions (Task 4)

I authored complete textual descriptions for two critical use cases that form the backbone of our pharmacy system:

####  Use Case 1: Upload Prescription

**Primary Actor:** Customer/Patient

**Key Elements I Documented:**
- Comprehensive stakeholder identification (System, Pharmacist, Doctor, Patient)
- Clear goal statement for successful prescription validation
- Detailed preconditions ensuring data quality
- Step-by-step main scenario flow
- Two alternative flows for error handling
- Exception conditions and edge cases
- Complete postconditions for both success and failure paths

**Highlights:**
- Identified critical validation steps for prescription authenticity
- Documented error handling for invalid file formats
- Specified security requirements for data encryption
- Defined clear notification workflows

####  Use Case 2: Preparing Medication

**Primary Actors:** Pharmacist, Customer/Patient

**Key Elements I Documented:**
- Multi-actor stakeholder mapping
- Precise preconditions for medication safety
- Detailed 8-step main scenario
- Three alternative flows (out of stock, unclear information, etc.)
- Comprehensive exception condition handling
- Success, failure, and hold-state postconditions

**Highlights:**
- Documented automated inventory checking workflow
- Specified supplier integration for restocking
- Defined doctor clarification process
- Outlined customer notification touchpoints

---

### 2. System Sequence Diagrams (Task 6)

I created detailed UML sequence diagrams that visualize the step-by-step interactions between system components for both use cases.

####  Sequence Diagram 1: Upload Prescription

**Components Visualized:**
- Customer (Actor)
- PrescriptionHandler (Controller)
- Database (Domain)
- NotificationService (Domain)
- Pharmacist (Actor)
- Doctor (Validation Entity)

**Key Interactions Documented:**
1. File upload and format validation
2. Doctor signature verification
3. Data encryption process
4. Secure database storage
5. Automated pharmacist notification
6. Customer confirmation

**Alternative Flows Shown:**
- Invalid file format handling
- Invalid doctor signature scenario
- Network failure recovery
- Corrupted file management

**Technical Details:**
- Synchronous vs. asynchronous message flows
- Object activation periods
- Return message patterns
- Exception handling branches

####  Sequence Diagram 2: Preparing Medication

**Components Visualized:**
- Pharmacist (Actor)
- PharmacistForm (View)
- InventoryManager (Controller)
- Database (Domain)
- Inventory (Domain)
- NotificationService (Domain)
- Customer (Actor)
- Doctor (Actor for clarifications)
- Supplier (External)

**Key Interactions Documented:**
1. Prescription list retrieval
2. Stock availability verification
3. Medication preparation workflow
4. Status updates to database
5. Multi-channel customer notifications
6. Restock request automation
7. Doctor clarification process

**Alternative Flows Shown:**
- Out of stock → Supplier restock request
- Unclear prescription → Doctor clarification
- Medication nearing expiry → Warning system

**Technical Details:**
- Real-time inventory checking
- Transaction management
- Concurrent access handling
- Automated notification triggers

---

##  Tools & Techniques Used

### Diagram Creation Tools
- **PlantUML** for initial drafts
- **Lucidchart** for final professional versions
- **Draw.io** for quick iterations

### Documentation Standards
- **UML 2.5 Specification** for sequence diagram notation
- **IEEE Standards** for use case documentation
- **Team Style Guide** for consistency

### Collaboration Tools
- **Google Docs** for collaborative writing
- **WhatsApp** for team coordination
- **GitHub** for version control
- **Email** for formal communications

---

## 📚 Methodology & Approach

### 1. Requirements Gathering
- Analyzed system vision document (by Claire)
- Reviewed event decomposition table
- Studied use case list and diagrams (by Umanga)
- Identified gaps in workflow understanding

### 2. Use Case Analysis
- Identified all actors and stakeholders
- Defined clear goals and preconditions
- Mapped main and alternative flows
- Documented exception scenarios
- Specified postconditions

### 3. Sequence Diagram Design
- Identified all participating objects
- Mapped message flows between objects
- Defined synchronous and asynchronous interactions
- Documented alternative execution paths
- Validated against use case descriptions

### 4. Integration & Validation
- Cross-referenced with CRC cards (Claire)
- Validated against class diagrams (Bryan)
- Aligned with activity diagrams (Umanga)
- Incorporated peer feedback
- Refined based on tutor comments

---

##  Skills Demonstrated

### Technical Skills
 **UML Proficiency**: Applied UML 2.5 notation correctly for sequence diagrams  
 **System Analysis**: Identified complex system interactions and data flows  
 **Documentation**: Created clear, comprehensive technical documentation  
 **Tool Mastery**: Proficient in multiple diagramming tools  

### Analytical Skills
 **Process Mapping**: Documented complete workflows with alternatives  
 **Exception Handling**: Identified and documented edge cases  
 **Stakeholder Analysis**: Mapped all relevant actors and their roles  
 **Critical Thinking**: Anticipated potential system failures  

### Soft Skills
 **Team Collaboration**: Worked effectively with multidisciplinary team  
 **Communication**: Conveyed complex processes clearly  
 **Attention to Detail**: Ensured accuracy across all deliverables  
 **Time Management**: Met all deadlines with high-quality work  

---

##  Learning Outcomes

### Key Learnings

1. **System Design Thinking**
   - Understanding how different layers interact
   - Importance of separation of concerns
   - Impact of design decisions on system behavior

2. **Documentation Skills**
   - Writing clear, actionable use cases
   - Creating professional sequence diagrams
   - Balancing detail with readability

3. **Collaborative Design**
   - Integrating work from multiple team members
   - Ensuring consistency across artifacts
   - Giving and receiving constructive feedback

4. **Problem Solving**
   - Identifying alternative flows
   - Handling exception scenarios
   - Designing for robustness

### Challenges Overcome

#### Challenge 1: Complexity Management
**Issue:** Upload prescription process had many branches and error conditions  
**Solution:** Used UML alt frames to clearly separate main and alternative flows  
**Learning:** Complex processes need hierarchical documentation

#### Challenge 2: Tool Selection
**Issue:** Different tools had varying capabilities and limitations  
**Solution:** Tested multiple tools, created comparison matrix  
**Learning:** Tool selection impacts quality and efficiency

#### Challenge 3: Consistency
**Issue:** Ensuring my diagrams aligned with team's class diagrams  
**Solution:** Regular sync meetings, shared terminology document  
**Learning:** Communication is key in collaborative projects

#### Challenge 4: Clarity vs. Completeness
**Issue:** Balancing comprehensive detail with diagram readability  
**Solution:** Multiple abstraction levels, references to detailed docs  
**Learning:** Know your audience and purpose for each artifact

---

##  Integration with Team Deliverables

### Connection to Claire's Work (CRC Cards)
- My sequence diagrams validate the responsibilities identified in CRC cards
- Message flows correspond to collaborations defined in CRC
- Confirmed that PrescriptionHandler and InventoryManager have appropriate methods

### Connection to Bryan's Work (Class Diagrams)
- Objects in my sequence diagrams map to classes in design class diagrams
- Messages I documented become methods in class specifications
- Validated that class structure supports required interactions

### Connection to Umanga's Work (Use Case & Activity Diagrams)
- My use case descriptions expand on Umanga's use case diagram
- Sequence diagrams complement activity diagrams (different perspectives)
- Alternative flows in both artifacts are consistent

---

##  Project Impact

### Business Value
My documentation helps stakeholders understand:
- **How** the system processes prescriptions securely
- **What** happens when things go wrong (error handling)
- **Who** is responsible for each action
- **When** notifications are sent to users

### Technical Value
My diagrams provide developers with:
- Clear interaction patterns to implement
- Message sequences for each use case
- Exception handling requirements
- Integration points between components

### Educational Value
This work demonstrates:
- Professional-level system analysis skills
- Industry-standard UML documentation
- Best practices in process modeling
- Comprehensive requirement documentation

---

## ⏱️ Time Investment

| Activity | Hours | Percentage |
|----------|-------|------------|
| Research & Learning | 3 | 20% |
| Use Case Description Writing | 4 | 27% |
| Sequence Diagram Creation | 6 | 40% |
| Reviews & Revisions | 2 | 13% |
| **Total** | **15** | **100%** |

### Timeline
- **Sep 11:** Use cases selected and analysis started
- **Sep 12:** First draft of use case descriptions completed
- **Sep 13:** Initial sequence diagrams created
- **Sep 14:** First review with Claire, revisions made
- **Sep 15:** Final diagrams and descriptions completed
- **Sep 16:** Comprehensive documentation written
- **Sep 18:** Final integration and team review

---

##  Quality Metrics

### Use Case Descriptions
-  **Completeness:** All required sections included
-  **Clarity:** Clear language, no ambiguity
-  **Accuracy:** Validated against system requirements
-  **Consistency:** Aligned with other team deliverables

### Sequence Diagrams
-  **Readability:** Clear at normal viewing size
-  **Comprehensiveness:** All interactions shown
-  **Correctness:** Validated by team review

**Revision Rounds:**
- Use Case 1: 2 revisions
- Use Case 2: 3 revisions
- Sequence Diagram 1: 3 revisions
- Sequence Diagram 2: 4 revisions

---

## Key Insights

### What Worked Well
1. **Early Collaboration:** Regular team meetings ensured alignment
2. **Iterative Approach:** Multiple review cycles improved quality
3. **Tool Flexibility:** Having multiple tool options prevented bottlenecks
4. **Documentation:** Writing documentation alongside diagrams improved understanding

### What I Would Improve
1. **Earlier Diagram Creation:** Start visual work sooner in the process
2. **More Templates:** Create reusable templates for faster work
3. **Automated Validation:** Use tools to check UML compliance automatically
4. **Version Control:** Better file versioning during iteration

---

## 📖 References & Resources

### Books & Materials
1. "UML Distilled" by Martin Fowler
2. "Applying UML and Patterns" by Craig Larman
3. MBI801 Course Lecture Notes
4. "Writing Effective Use Cases" by Alistair Cockburn

### Online Resources
1. PlantUML Documentation
2. Lucidchart UML Tutorial
3. UML Best Practices Guide
4. Healthcare System Design Patterns

---

## Achievements

### Skills Developed
- Advanced UML sequence diagram creation
- Professional use case documentation
- System interaction modeling
- Technical communication
- Collaborative design work

### Team Contribution
- Met all deadlines on time
- Supported teammates with reviews
- Maintained high quality standards
- Contributed to final presentation

---

## Personal Reflection

Working on the Pharmacy Management System project has been an invaluable learning experience. As the Process Analyst, I developed a deep understanding of how system components interact and how to document these interactions clearly.

**Most Rewarding Aspect:**  
Seeing my sequence diagrams come to life and realizing they could guide actual system implementation was incredibly satisfying.

**Biggest Challenge:**  
Balancing completeness with readability in the sequence diagrams. I wanted to show every detail but also needed to keep diagrams understandable.

**Key Takeaway:**  
Good documentation is as important as good design. Clear sequence diagrams and use cases bridge the gap between requirements and implementation.

**Future Application:**  
The skills I developed in process analysis and visual documentation will be valuable in any future information systems project, whether in healthcare or other domains.

---

## Contact & Portfolio

**LinkedIn:**https://www.linkedin.com/in/abiramihi/
**GitHub:** (https://github.com/Abirami-Baskaran-s)
**Project Repository:**(https://github.com/Abirami-Baskaran-s/Pharmacy-management-system)

---

<div align="center">

**Abirami**  
*Process Analyst & Sequence Diagram Specialist*

*"Bringing clarity to complexity through visual documentation"*

**MBI801 - Information Systems Analysis and Design**  
**Yoobee College of Creative Innovation 2025**

</div>

---

## Appendix

### A. Terminology Used

| Term | Definition |
|------|------------|
| **Sequence Diagram** | UML diagram showing object interactions over time |
| **Use Case** | Description of system functionality from user perspective |
| **Actor** | External entity that interacts with the system |
| **Lifeline** | Vertical dashed line representing object existence |
| **Activation** | Period when object is performing an action |
| **Message** | Communication between objects |
| **Alt Frame** | Alternative execution paths in sequence diagram |


### B. Validation Checklist

My personal checklist for each diagram:
- [ ] All actors from use case present
- [ ] Lifelines properly labeled
- [ ] Messages have clear labels
- [ ] Activation bars used correctly
- [ ] Alternative flows in alt frames
- [ ] Return messages where appropriate
- [ ] Consistent with use case description
- [ ] Follows UML 2.5 standards
- [ ] Readable at normal size
- [ ] Exported at 300 DPI

---

*Last Updated: September 2025*
