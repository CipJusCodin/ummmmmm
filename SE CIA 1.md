# Software Engineering Exam Solutions (80 Marks Total)

## Question 1: (10 Marks)
**Describe the key features and qualities that a new CRM software should have to ensure it meets the needs of our sales team, integrates seamlessly with our existing systems, and provides a competitive edge in the market? Explain attributes of a good software with real time example.**

### Key Attributes of Good Software (from PDF):

```
┌─────────────────────────────────────────────────────────┐
│                 GOOD SOFTWARE ATTRIBUTES                │
├─────────────────────────────────────────────────────────┤
│  ┌─────────────────┐  ┌─────────────────┐              │
│  │ MAINTAINABILITY │  │ DEPENDABILITY & │              │
│  │                 │  │    SECURITY     │              │
│  │ • Easy to update│  │ • Should not fail│              │
│  │ • Easy to modify│  │ • No cyberattack │              │
│  │ • Accommodate   │  │ • Reliable       │              │
│  │   changes       │  │   operation      │              │
│  └─────────────────┘  └─────────────────┘              │
│                                                         │
│  ┌─────────────────┐  ┌─────────────────┐              │
│  │   EFFICIENCY    │  │  ACCEPTABILITY  │              │
│  │                 │  │                 │              │
│  │ • Uses resources│  │ • Easy to use   │              │
│  │   wisely        │  │ • Integrates    │              │
│  │ • Memory &      │  │   well with     │              │
│  │   processing    │  │   other systems │              │
│  └─────────────────┘  └─────────────────┘              │
└─────────────────────────────────────────────────────────┘
```

**CRM Software Requirements:**

**1. Maintainability**
- Easy to update as business needs change
- Modifiable to accommodate new sales processes
- System should evolve with changing customer requirements

**2. Dependability & Security**
- Must not fail during critical sales operations
- Secure customer data from unauthorized access
- Reliable operation during peak usage periods

**3. Efficiency**
- Uses system resources wisely (memory, processing power)
- Fast response times for sales team productivity
- Optimal performance with large customer databases

**4. Acceptability**
- Easy to use for sales team members
- Integrates well with existing business systems
- User-friendly interface that team can adopt quickly

**Real-time Example from PDF:**
Like the **iLearn Digital Learning Environment** case study, a CRM should be:
- **Service-Oriented**: Components can be replaced or updated
- **Flexible Configuration**: Different setups for different sales teams
- **Integrated Services**: Can connect with other business apps via API
- **Types of Services**: Utility services (basic functions), Application services (email, reporting), Configuration services (control how features are shared)

---

## Question 2: (10 Marks)
**When developing a Learning Management System for our university to ensure it is secure, scalable, and user-friendly for students, teachers, and administrators mention the different non functional requirements that need to be addressed with a neat diagram.**

### Non-Functional Requirements for LMS (Based on PDF):

```
                    NON-FUNCTIONAL REQUIREMENTS
                         FOR UNIVERSITY LMS
    ┌─────────────────┬─────────────────┬─────────────────┐
    │    SECURITY     │   SCALABILITY   │   USABILITY     │
    │                 │                 │                 │
    │ • Dependable    │ • Handle system │ • Easy to use   │
    │   operation     │   growth        │ • User-friendly │
    │ • No cyber      │ • Support more  │ • Acceptable    │
    │   attacks       │   users         │   interface     │
    │ • Secure data   │ • Accommodate   │ • Easy learning │
    │ • Reliable      │   expansion     │ • Intuitive     │
    └─────────────────┴─────────────────┴─────────────────┘
    ┌─────────────────┬─────────────────┬─────────────────┐
    │  PERFORMANCE    │  RELIABILITY    │ MAINTAINABILITY │
    │                 │                 │                 │
    │ • Efficient use │ • System uptime │ • Easy to update│
    │   of resources  │ • Minimal       │ • Modifiable    │
    │ • Memory &      │   failures      │ • Adaptable to  │
    │   processing    │ • Consistent    │   changes       │
    │ • Fast response │   operation     │ • System        │
    │   times         │ • Error recovery│   evolution     │
    └─────────────────┴─────────────────┴─────────────────┘
```

**Based on iLearn Case Study from PDF:**

**Key Aspects:**
- **Service-Oriented**: Components can be replaced or updated as needed
- **Flexible Configuration**: Different setups for different user types (students, teachers, administrators)

**Types of Services (from PDF):**
- **Utility Services**: Basic functions used by other services
- **Application Services**: Email, conferencing, educational content delivery
- **Configuration Services**: Control how services are shared among users

**Service Integration:**
- **Integrated Services**: Can connect with other university systems via API
- **Independent Services**: Run separately, requiring manual data coordination

**General Issues Affecting Software (from PDF):**
- **Heterogeneity**: Software must work across different devices and networks
- **Scale**: Software ranges from small devices to massive systems
- **Security & Trust**: Must be reliable and secure for daily use

---

## Question 3: (10 Marks)
**How can we ensure that the social media algorithm we are developing aligns with ethical principles, such as promoting public good, avoiding harm, and respecting user privacy, while still achieving business goals? Explain the ACM code of ethics.**

### ACM/IEEE Code of Ethics (from PDF):

```
                        ACM CODE OF ETHICS
    ┌───────────────────────────────────────────────────────────┐
    │  1. PUBLIC INTEREST    │  2. CLIENT & EMPLOYER           │
    │     Act in a way that  │     Serve employers while       │
    │     benefits society   │     considering public welfare  │
    ├───────────────────────────────────────────────────────────┤
    │  3. PRODUCT QUALITY    │  4. JUDGMENT                    │
    │     Deliver high-      │     Maintain professional      │
    │     standard software  │     integrity                  │
    ├───────────────────────────────────────────────────────────┤
    │  5. MANAGEMENT ETHICS  │  6. PROFESSION INTEGRITY        │
    │     Leaders should     │     Uphold the software        │
    │     promote ethical    │     engineering profession's   │
    │     development        │     reputation                 │
    ├───────────────────────────────────────────────────────────┤
    │  7. COLLEGIALITY      │  8. CONTINUOUS LEARNING         │
    │     Treat colleagues   │     Keep updating skills and    │
    │     fairly and         │     promote ethics in the      │
    │     supportively       │     field                      │
    └───────────────────────────────────────────────────────────┘
```

### Software Engineering Ethics (from PDF):

**Ethical Behavior Involves:**

1. **Confidentiality** - Respect client and employer privacy, even without formal agreements
2. **Competence** - Only take on work within your expertise
3. **Intellectual Property Rights** - Follow laws regarding patents and copyrights
4. **Computer Misuse** - Avoid unethical actions like hacking or spreading malware

**Ethical Dilemmas (from PDF):**
- Disagreeing with unethical policies of management
- Employer releasing untested safety-critical software
- Working on projects that raise ethical concerns

**Applying Ethics to Social Media Algorithm:**

**1. Public Interest**: Algorithm should act in a way that benefits society
**2. Client & Employer**: Serve business goals while considering public welfare
**3. Product Quality**: Deliver high-standard algorithm functionality
**4. Professional Judgment**: Maintain integrity in algorithm design decisions
**5. Management Ethics**: Leaders should promote ethical algorithm development
**6. Profession Integrity**: Uphold software engineering profession's reputation
**7. Collegiality**: Work fairly with team members on algorithm development
**8. Continuous Learning**: Keep updating skills and promote ethics in algorithm design

---

## Question 4: (10 Marks)
**Apply the Waterfall Model to develop a Student Attendance Management System for our school, ensuring that each stage—from gathering requirements to maintenance—is carefully planned and executed to meet the needs of teachers, students, and administrators? With the diagram explain each stage.**

### Waterfall Model (from PDF):

```
    WATERFALL MODEL FOR ATTENDANCE MANAGEMENT SYSTEM
    
    ┌─────────────────────────────────────────────────┐
    │        REQUIREMENTS ANALYSIS & DEFINITION       │
    │                                                 │
    │ • Customers and engineers define what the       │
    │   software should do and any limitations        │
    │ • Gather needs from teachers, students, admin   │
    │ • Specify system constraints and requirements   │
    └─────────────────────┬───────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────────────────────┐
    │           SYSTEM & SOFTWARE DESIGN              │
    │                                                 │
    │ • The software is designed and planned          │
    │ • System architecture and components            │
    │ • Database design and user interfaces           │
    └─────────────────────┬───────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────────────────────┐
    │        IMPLEMENTATION & UNIT TESTING            │
    │                                                 │
    │ • The software is programmed                    │
    │ • Individual components are coded               │
    │ • Unit testing of each component                │
    └─────────────────────┬───────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────────────────────┐
    │         INTEGRATION & SYSTEM TESTING            │
    │                                                 │
    │ • Components are integrated together            │
    │ • System tested to ensure it meets requirements │
    │ • Validation that system works correctly        │
    └─────────────────────┬───────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────────────────────┐
    │           OPERATION & MAINTENANCE               │
    │                                                 │
    │ • The software is updated to meet changing needs│
    │ • System deployed and maintained                │
    │ • Evolution of software over time               │
    └─────────────────────────────────────────────────┘
```

**Problems of Waterfall Model (from PDF):**
- Difficult to accommodate changes once the process starts
- Rigid partitioning into phases makes responding to new requirements hard
- Suitable only for stable requirements

**Stage Explanation for Attendance System:**

1. **Requirements Analysis & Definition**: Define what the attendance system should do - teachers need to mark attendance, students need to view their attendance, administrators need reports

2. **System & Software Design**: Design the system organization and plan how components will work together

3. **Implementation & Unit Testing**: Program the attendance tracking features and test individual components

4. **Integration & System Testing**: Integrate all components and test the complete system functionality

5. **Operation & Maintenance**: Deploy the system and modify it over time to meet changing school needs

---

## Question 5: (10 Marks)
**How does the process of involuntary detention work in the context of a mental health crisis, and what steps must the crisis team follow to ensure the individual's rights are protected while addressing their immediate needs? Illustrate with a neat diagram.**

### Mentcare Mental Health Patient System (from PDF):

```
        MENTCARE PATIENT MANAGEMENT PROCESS
    
    ┌─────────────────────────────────────────────────┐
    │              PATIENT IDENTIFICATION             │
    │                                                 │
    │ • Stores patient history and treatment details  │
    │ • Used in clinics, hospitals, community centers │
    │ • Patient information management                │
    └─────────────────────┬───────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────────────────────┐
    │               CARE MANAGEMENT                   │
    │                                                 │
    │ • Doctors can update and view patient records   │
    │ • Treatment plan development                    │
    │ • Medical history tracking                      │
    └─────────────────────┬───────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────────────────────┐
    │              PATIENT MONITORING                 │
    │                                                 │
    │ • Warns doctors about high-risk patients        │
    │ • Must alert staff about suicidal patients      │
    │ • Must alert staff about dangerous patients     │
    └─────────────────────┬───────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────────────────────┐
    │                  REPORTING                      │
    │                                                 │
    │ • Tracks patient numbers and treatments         │
    │ • Drug cost monitoring                          │
    │ • Helps health managers track performance       │
    └─────────────────────┬───────────────────────────┘
                          │
                          ▼
    ┌─────────────────────────────────────────────────┐
    │              PRIVACY & SAFETY                   │
    │                                                 │
    │ • Only authorized staff access patient records  │
    │ • System works offline but syncs when online    │
    │ • Provides timely patient information           │
    └─────────────────────────────────────────────────┘
```

**Mentcare System Features (from PDF):**

**Goals:**
- Helps health managers track performance
- Provides timely patient information for doctors

**Key Features:**
- **Care Management**: Doctors can update and view patient records
- **Patient Monitoring**: Warns doctors about high-risk patients
- **Reporting**: Tracks patient numbers, treatments, and drug costs

**Critical Concerns:**
- **Privacy**: Only authorized staff should access patient records
- **Safety**: Must alert staff about suicidal or dangerous patients

**System Operation:**
- Works offline but syncs with central database when online
- Used in clinics, hospitals, and community centers
- Stores patient history and treatment details

**Mental Health Crisis Management Steps:**
1. **Patient Assessment**: System alerts about high-risk patients
2. **Care Coordination**: Doctors update patient records with crisis information
3. **Safety Monitoring**: System warns about suicidal or dangerous patients
4. **Treatment Tracking**: Monitor patient progress and treatment effectiveness
5. **Privacy Protection**: Ensure only authorized staff access sensitive information

---

## Question 6: (10 Marks)
**Mention the different metrics available for specifying non functional requirements with an example for each.**

### Metrics for Non-Functional Requirements (From PDF):

The PDF provides a comprehensive table of **metrics for non-functional requirements**:

#### 1. Speed Metrics

**Measures:**
- **Transactions per second**
- **Response time**

**Examples:**
- **E-commerce System**: Must process 1000 transactions per second during peak hours
- **Web Application**: Page response time must be less than 3 seconds
- **Banking System**: Transaction processing should complete within 2 seconds

#### 2. Size Metrics

**Measures:**
- **MB (Megabytes)**
- **Number of ROM chips**

**Examples:**
- **Mobile Application**: App size should not exceed 50 MB for download
- **Embedded System**: System should fit within 2 ROM chips
- **Database**: Storage requirement should not exceed 100 GB

#### 3. Ease of Use Metrics

**Measures:**
- **Training time**
- **Help frames count**

**Examples from PDF:**
- **Mentcare System**: "Medical staff must learn all functions in 4 hours"
- **Learning System**: "After training, errors should not exceed 2 per hour"
- **User Interface**: Maximum 5 help screens should be sufficient for basic operations

#### 4. Reliability Metrics

**Measures:**
- **Mean time to failure**
- **Failure rate**

**Examples:**
- **Hospital System**: Mean time to failure should be minimum 8760 hours (1 year)
- **Banking Application**: Failure rate should not exceed 0.1% of all transactions
- **Air Traffic Control**: System should have failure rate less than 0.001%

#### 5. Availability Metrics

**Measures:**
- **Probability of uptime**

**Examples from PDF:**
- **Mentcare System**: "The system must be available during clinic hours (Mon–Fri, 08:30–17:30). Downtime should not exceed 5 seconds per day during working hours"
- **E-commerce Platform**: 99.9% availability required
- **Educational System**: 98% availability during academic hours

#### 6. Robustness Metrics

**Measures:**
- **Restart time**
- **Data corruption probability**

**Examples:**
- **Database System**: System restart after failure should be within 60 seconds
- **File Storage**: Data corruption probability should be less than 0.001%
- **Web Server**: Recovery time after crash should not exceed 30 seconds

#### 7. Portability Metrics

**Measures:**
- **% of target-dependent code**
- **Number of target systems**

**Examples:**
- **Cross-platform Software**: Target-dependent code should be less than 15%
- **Mobile Application**: Should support minimum 3 operating systems (iOS, Android, Windows)
- **Web Application**: Should work on at least 5 different browsers

### Comprehensive Metrics Table (From PDF):

```
Non-Functional Requirements Metrics:

┌─────────────────────────────────────────────────────────────┐
│                    METRICS CLASSIFICATION                   │
└─────────────────────────────────────────────────────────────┘

┌─────────────────┬─────────────────────┬─────────────────────┐
│    PROPERTY     │       MEASURE       │      EXAMPLE        │
├─────────────────┼─────────────────────┼─────────────────────┤
│                 │ • Transactions/sec  │ • Banking: 1000     │
│     SPEED       │ • Response time     │   transactions/sec  │
│                 │                     │ • Web: <3 sec       │
│                 │                     │   response          │
├─────────────────┼─────────────────────┼─────────────────────┤
│                 │ • MB                │ • Mobile app:       │
│     SIZE        │ • Number of ROM     │   <50 MB           │
│                 │   chips             │ • Embedded: 2       │
│                 │                     │   ROM chips         │
├─────────────────┼─────────────────────┼─────────────────────┤
│                 │ • Training time     │ • Medical staff:    │
│  EASE OF USE    │ • Help frames       │   4 hours training  │
│                 │   count             │ • Max 2 errors/hr   │
│                 │                     │   after training    │
├─────────────────┼─────────────────────┼─────────────────────┤
│                 │ • Mean time to      │ • Hospital system:  │
│   RELIABILITY   │   failure           │   MTTF 8760 hours   │
│                 │ • Failure rate      │ • <0.1% failure     │
│                 │                     │   rate              │
├─────────────────┼─────────────────────┼─────────────────────┤
│                 │ • Probability of    │ • Mentcare: 99.9%   │
│  AVAILABILITY   │   uptime            │   during clinic     │
│                 │                     │   hours             │
│                 │                     │ • <5 sec downtime   │
├─────────────────┼─────────────────────┼─────────────────────┤
│                 │ • Restart time      │ • Database: <60     │
│   ROBUSTNESS    │ • Data corruption   │   sec restart       │ 
│                 │   probability       │ • <0.001% data      │
│                 │                     │   corruption        │
├─────────────────┼─────────────────────┼─────────────────────┤
│                 │ • % target-         │ • <15% target-      │
│  PORTABILITY    │   dependent code    │   dependent code    │
│                 │ • Number of target  │ • Support 3+        │
│                 │   systems           │   platforms         │
└─────────────────┴─────────────────────┴─────────────────────┘
```

### Real Examples from PDF Case Studies:

#### Mentcare System Examples:

**1. Product Requirement (Availability):**
- "The system must be available during clinic hours (Mon–Fri, 08:30–17:30)"
- "Downtime should not exceed 5 seconds per day during working hours"

**2. Organizational Requirement (Security):**
- "Users must authenticate using a health authority identity card"

**3. External Requirement (Compliance):**
- "The system must comply with patient privacy laws (HStan-03-2006-priv)"

#### Usability Requirements Example:

**Goal vs. Verifiable Requirement:**
- **Goal**: "The system should be easy to use and minimize errors"
- **Testable Requirement**: 
  - "Medical staff must learn all functions in 4 hours"
  - "After training, errors should not exceed 2 per hour"

### Goals vs. Requirements (From PDF):

**Problem**: Non-functional requirements can be hard to state precisely and difficult to verify

**Solution**: Convert goals into verifiable requirements
- **Goal**: General intention (e.g., "The system should be easy to use")
- **Verifiable Requirement**: Measurable and testable (e.g., "Users must make no more than 2 errors per hour after 4 hours of training")

This comprehensive metrics framework ensures that non-functional requirements are:
1. **Measurable**: Can be quantified
2. **Testable**: Can be verified during testing
3. **Achievable**: Realistic given available resources
4. **Relevant**: Important for system success

---

## Question 7: (10 Marks)
**Describe the structure of requirement document.**

<img width="467" alt="image" src="https://github.com/user-attachments/assets/71c77dc9-0c66-4e99-8dfc-b0256b4e919f" />

---

## Question 8: (10 Marks)
**Explain the requirement engineering process to develop a Patient Management System for our hospital, ensuring that we gather, analyze, and document the needs of doctors, nurses, and patients effectively with a neat diagram.**

### Requirements Engineering Process (From PDF):

**Requirements Engineering** is the process of defining system services and constraints, with outputs being **system requirements** (descriptions of services & constraints).

#### Common RE Activities:
1. **Requirements Elicitation** – Gathering system needs
2. **Requirements Analysis** – Refining and structuring  
3. **Requirements Validation** – Checking correctness
4. **Requirements Management** – Handling changes over time

**RE is iterative** → Steps are repeated throughout development following a **spiral process** where each phase is refined and improved over time.

### Patient Management System Requirements Engineering Process:

```
Requirements Engineering Process for Patient Management System:

┌─────────────────────────────────────────────────────────────┐
│                 REQUIREMENTS ELICITATION                    │
│                                                             │
│  ┌─────────────────────────────────────────────────────┐    │
│  │                 STAKEHOLDER ANALYSIS                │    │
│  │                                                     │    │
│  │  ┌─────────────┐ ┌─────────────┐ ┌─────────────┐    │    │
│  │  │   DOCTORS   │ │   NURSES    │ │  PATIENTS   │    │    │
│  │  │             │ │             │ │             │    │    │
│  │  │• Access     │ │• Coordinate │ │• View       │    │    │
│  │  │  patient    │ │  care       │ │  records    │    │    │
│  │  │  records    │ │• Update     │ │• Schedule   │    │    │
│  │  │• Prescribe  │ │  treatments │ │  appointments│   │    │
│  │  │  medication │ │• Monitor    │ │• Receive    │    │    │
│  │  │• Diagnose   │ │  vitals     │ │  notifications│  │    │
│  │  │• Treatment  │ │• Administer │ │• Access     │    │    │
│  │  │  planning   │ │  medication │ │  test results│   │    │
│  │  └─────────────┘ └─────────────┘ └─────────────┘    │    │
│  │                                                     │    │
│  │  ┌─────────────┐ ┌─────────────┐ ┌─────────────┐    │    │
│  │  │ADMINISTRATORS│ │MEDICAL STAFF│ │ IT SUPPORT  │    │    │
│  │  │             │ │             │ │             │    │    │
│  │  │• Generate   │ │• Maintain   │ │• System     │    │    │
│  │  │  reports    │ │  records    │ │  maintenance│    │    │
│  │  │• Manage     │ │• Ensure     │ │• Data       │    │    │
│  │  │  resources  │ │  compliance │ │  backup     │    │    │
│  │  │• Monitor    │ │• Quality    │ │• Security   │    │    │
│  │  │  performance│ │  control    │ │  management │    │    │
│  │  └─────────────┘ └─────────────┘ └─────────────┘    │    │
│  └─────────────────────────────────────────────────────┘    │
│                                                             │
│  Elicitation Techniques:                                    │
│  • Interviews with stakeholders                             │
│  • Ethnography (observing current workflows)                │
│  • User stories and scenarios                               │
│  • Prototyping for complex features                         │
└─────────────────────────────┬───────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────┐
│              REQUIREMENTS ANALYSIS & SPECIFICATION          │
│                                                             │
│  ┌─────────────────────────────────────────────────────┐    │
│  │            FUNCTIONAL REQUIREMENTS                  │    │
│  │                                                     │    │
│  │  Patient Management:                                │    │
│  │  • Patient registration and demographic data        │    │
│  │  • Medical history maintenance                      │    │
│  │  • Appointment scheduling system                    │    │
│  │  • Treatment plan management                        │    │
│  │                                                     │    │
│  │  Clinical Operations:                               │    │
│  │  • Electronic health records (EHR)                 │    │
│  │  • Prescription management                          │    │
│  │  • Laboratory test ordering and results            │    │
│  │  • Diagnostic imaging integration                   │    │
│  │                                                     │    │
│  │  Administrative Functions:                          │    │
│  │  • Billing and insurance processing                │    │
│  │  • Report generation and analytics                 │    │
│  │  • Resource management                             │    │
│  │  • Regulatory compliance tracking                  │    │
│  └─────────────────────────────────────────────────────┘    │
│                                                             │
│  ┌─────────────────────────────────────────────────────┐    │
│  │          NON-FUNCTIONAL REQUIREMENTS                │    │
│  │                                                     │    │
│  │  Product Requirements:                              │    │
│  │  • System available 24/7 with 99.9% uptime        │    │
│  │  • Response time < 2 seconds for patient queries   │    │
│  │  • Support 500 concurrent users                    │    │
│  │  • Data backup every 4 hours                       │    │
│  │                                                     │    │
│  │  Organizational Requirements:                       │    │
│  │  • HIPAA compliance for patient privacy            │    │
│  │  • FDA regulations for medical devices             │    │
│  │  • Hospital-approved security standards            │    │
│  │                                                     │    │
│  │  External Requirements:                             │    │
│  │  • Integration with existing hospital systems      │    │
│  │  • Interoperability with external labs             │    │
│  │  • Accessibility standards compliance              │    │
│  └─────────────────────────────────────────────────────┘    │
└─────────────────────────────┬───────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────┐
│               REQUIREMENTS VALIDATION                        │
│                                                             │
│  ┌─────────────────────────────────────────────────────┐    │
│  │               VALIDATION TECHNIQUES                  │    │
│  │                                                     │    │
│  │  Requirements Reviews:                              │    │
│  │  • Systematic manual analysis with stakeholders     │    │
│  │  • Include doctors, nurses, and patients           │    │
│  │  • Formal review meetings and documentation        │    │
│  │                                                     │    │
│  │  Prototyping:                                       │    │
│  │  • Build executable model for validation           │    │
│  │  • Test critical workflows with medical staff      │    │
│  │  • Validate user interface with end users          │    │
│  │                                                     │    │
│  │  Test-case Generation:                              │    │
│  │  • Develop tests to check testability              │    │
│  │  • Create scenarios for patient care workflows     │    │
│  │  • Validate system integration points              │    │
│  └─────────────────────────────────────────────────────┘    │
│                                                             │
│  ┌─────────────────────────────────────────────────────┐    │
│  │              VALIDATION CHECKS                      │    │
│  │                                                     │    │
│  │  • Validity: Does system meet healthcare needs?    │    │
│  │  • Consistency: No conflicting requirements?       │    │
│  │  • Completeness: All medical functions included?   │    │
│  │  • Realism: Can be implemented with resources?     │    │
│  │  • Verifiability: Can requirements be tested?     │    │
│  └─────────────────────────────────────────────────────┘    │
└─────────────────────────────┬───────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────┐
│               REQUIREMENTS MANAGEMENT                        │
│                                                             │
│  ┌─────────────────────────────────────────────────────┐    │
│  │           REQUIREMENTS MANAGEMENT PLANNING           │    │
│  │                                                     │    │
│  │  Identification:                                    │    │
│  │  • Unique IDs for cross-referencing                │    │
│  │  • REQ-PM-001: Patient Registration                │    │
│  │  • REQ-PM-002: Medical History Access              │    │
│  │  • REQ-PM-003: Prescription Management             │    │
│  │                                                     │    │
│  │  Change Management Process:                         │    │
│  │  • Assess impact and cost of changes               │    │
│  │  • Medical staff approval for clinical changes     │    │
│  │  • Regulatory compliance review                    │    │
│  │                                                     │    │
│  │  Traceability Policies:                            │    │
│  │  • Link requirements to design decisions           │    │
│  │  • Map user needs to system functions              │    │
│  │  • Connect test cases to requirements              │    │
│  │                                                     │    │
│  │  Tool Support:                                     │    │
│  │  • Requirements management database                │    │
│  │  • Version control for requirement changes         │    │
│  │  • Impact analysis tools                           │    │
│  └─────────────────────────────────────────────────────┘    │
│                                                             │
│  ┌─────────────────────────────────────────────────────┐    │
│  │         REQUIREMENTS CHANGE MANAGEMENT               │    │
│  │                                                     │    │
│  │  Step 1: Problem Analysis & Change Specification    │    │
│  │  • Analyze change proposal from medical staff       │    │
│  │  • Assess impact on patient safety                 │    │
│  │  • Provide feedback to requester                   │    │
│  │                                                     │    │
│  │  Step 2: Change Analysis & Costing                 │    │
│  │  • Use traceability data for impact assessment     │    │
│  │  • Consider regulatory compliance requirements     │    │
│  │  • Decide whether to proceed with change           │    │
│  │                                                     │    │
│  │  Step 3: Change Implementation                      │    │
│  │  • Modify requirements document                     │    │
│  │  • Update system design accordingly                │    │
│  │  • Notify all affected stakeholders                │    │
│  └─────────────────────────────────────────────────────┘    │
└─────────────────────────────────────────────────────────────┘
```

### Requirements Engineering Stages for Patient Management System:

#### Stage 1: Requirements Discovery
**Involves gathering information from stakeholders:**
- **Managers**: Hospital administrators, department heads
- **Users**: Doctors, nurses, patients  
- **Engineers**: IT staff, system integrators
- **External regulators**: Healthcare compliance officers

**Techniques Used:**
- **Interviews**: Structured discussions with medical staff
- **Ethnography**: Observing current patient care workflows  
- **Prototyping**: Early system demonstrations for feedback

#### Stage 2: Requirements Classification & Organization
**Grouping requirements into categories:**
- **Patient Care Requirements**: Registration, treatment, monitoring
- **Clinical Requirements**: Prescriptions, lab results, diagnostics
- **Administrative Requirements**: Billing, reporting, compliance
- **Technical Requirements**: Integration, security, performance

#### Stage 3: Requirements Prioritization & Negotiation
**Resolving conflicts and ranking by importance:**
- **Critical**: Patient safety and data security
- **Important**: Workflow efficiency and reporting
- **Desirable**: Advanced analytics and mobile access

#### Stage 4: Requirements Specification
**Formal documentation using:**
- **Natural Language**: Clear, numbered sentences
- **Structured Templates**: Consistent format for all requirements
- **UML Diagrams**: Use cases for patient interactions
- **Tabular Specifications**: Decision tables for complex logic

### Example Patient Management System Requirements:

#### Functional Requirements:
1. **REQ-PM-001**: The system shall allow doctors to access patient medical history within 2 seconds
2. **REQ-PM-002**: Nurses shall be able to update patient vital signs in real-time
3. **REQ-PM-003**: Patients shall receive automated appointment reminders 24 hours in advance

#### Non-Functional Requirements:
1. **Performance**: System must support 500 concurrent users with <2 second response time
2. **Security**: All patient data must be encrypted and HIPAA compliant
3. **Availability**: System must maintain 99.9% uptime during hospital operating hours

### Challenges in Healthcare Requirements Engineering:

**From PDF - Challenges in Requirements Elicitation:**
- **Stakeholders may not know what they want**: Medical staff may not understand technical possibilities
- **Domain-specific language**: Medical terminology can be complex for developers
- **Conflicting requirements**: Different departments may have competing needs
- **Regulatory changes**: Healthcare regulations evolve, requiring system updates

### Success Factors:

1. **Early Stakeholder Involvement**: Include all user groups from the beginning
2. **Iterative Process**: Regular feedback and refinement cycles
3. **Regulatory Compliance**: Ensure all requirements meet healthcare standards
4. **Change Management**: Formal process for handling evolving needs
5. **Validation**: Continuous testing with real healthcare workflows

This systematic approach ensures the Patient Management System meets the complex needs of healthcare environments while maintaining safety, security, and regulatory compliance.
