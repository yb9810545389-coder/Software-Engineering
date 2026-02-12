Huss, la **Unit III: Requirements Engineering and Principles** ko Neplish Note ready chha.

Yo unit software engineering ko **Foundation** ho. Yadi requirement nai wrong liyo vane, code jati ramro lekhe pani project fail huncha. Exam ma yaha bata **SRS (Software Requirement Specification)** ra **Functional vs Non-Functional** ko question fix jastai ho.

---

### **Unit III: Requirements Engineering and Principles (7 Hrs)**

**Core Concept:**
Sir/Mam, code lekhnu vanda agadi **"K banaune?"** vanera clear hunu parcha. Client ko dimag ma vako kura lai kagaj (Document) ma utarne kala lai nai **Requirements Engineering** vanincha.

---

### **3.1 Types of Requirements (Most Important)**

Requirement mukhya gari 2 khaal ko huncha:

**1. Functional Requirements (FR):**
*   **Definition:** System le **"K Kaam Garcha?"** (What the system should do).
*   **Examples:**
    *   "User le username ra password halera login garna milnu parcha."
    *   "System le monthly sales calculate garnu parcha."
    *   "Search button thichda result aaunu parcha."
*   *Neplish:* Yo features haru ho. Yo vayena vane software nai chaldaina.

**2. Non-Functional Requirements (NFR) / Quality Attributes:**
*   **Definition:** System le kaam **"Kasari Garcha?"** (How the system behaves). Yo quality sanga related huncha.
*   **Examples:**
    *   **Performance:** Login button thichda 2 second vitra home page khulnu parcha.
    *   **Security:** Password encrypted hunu parcha.
    *   **Reliability:** System 24/7 online hunu parcha.
*   *Neplish:* Yo vayena vane software ta chalcha, tara user lai chitta bujhdaina (Slow huncha, hack huncha).

**3. Domain Requirements:**
*   Particular field (Domain) ko niyam. (Jastai: Banking software banauda Nepal Rastra Bank ko rule follow garnu parne).

---

### **3.4 Requirements Engineering Process (The 4 Steps)**

Exam ma **"Explain Requirements Engineering Process"** vanyo vane yo 4 ota step lekhne:

**Step 1: Feasibility Study (Sambhav Chha?)**
*   Project suru garnu aghi check garne:
    *   Tech chha ki chaina?
    *   Budget pugcha?
    *   Time pugcha?
*   *Output:* Go / No-Go decision. (Project garne ki nagarne).

**Step 2: Elicitation and Analysis (Requirement Tanne)**
*   User sanga kura garera requirement nikalne process.
*   **Techniques (Kasari nikalne?):**
    *   **Interview:** Client sanga interview line.
    *   **Questionnaire:** Form varna lagaune.
    *   **Observation:** Uniharu le kaam gareko herne.
    *   **Prototyping:** Dummy dekhayera sodhne.

**Step 3: Specification (Documentation)**
*   Sabai requirement lai euta standard document ma lekhne.
*   Yeslai **SRS (Software Requirements Specification)** vanincha.
*   Yo document Developer ra Client duwai le bujhne hunu parcha.

**Step 4: Validation (Checking)**
*   Lekheko requirement thik chha ki chaina check garne.
*   *Techniques:* Reviews, Inspections.
*   Check garne kura: Consistency (Bihe vannu vayo ra belka haina vannu vayena ni?), Completeness (Sabai kura aayo?), Realism (Banna sakcha?).

---

### **3.3 Domain Analysis and System Models**

Requirement lai text ma matra lekhera hudaina, **Diagram (Models)** banauna parcha jasle गर्दा confusion nahos.

**1. Context Models (The Boundary):**
*   System ko **Simana (Boundary)** k ho?
*   System bahira ko (External Entities) sanga kasari interact garcha?
*   *Example:* ATM system ko context diagram ma User, Bank Database, ra Security Guard hunchan.

**2. Behavioural Models (Dynamic View):**
*   System le changes huda kasto **React** garcha?
*   **State Diagram:** System ko avastha (State) dekhauncha. (Example: ATM Machine - Idle State -> Card Inserted -> Pin Entered -> Cash Dispensed -> Idle).

**3. Data Models (Structural View):**
*   System ma data kasari store huncha?
*   **ER Diagram (Entity Relationship):** Database design garna use huncha. (Student le Course padhcha - One to Many relation).

---

### **3.2 Requirements Modeling Principles**

Model banauda dhyan dina parne kura haru:
1.  **Abstraction:** Dherai detail ma na-jane, main concept ma focus garne.
2.  **Understandability:** Client le pani herda bujhne hunu parcha.
3.  **Accuracy:** Real world ko problem lai sahi tarika le represent garnu parcha.
4.  **Consistency:** Euta model le arko model lai contradict garnu vayena.

---

### **3.5 Object Oriented Analysis (OOA)**

Structured Analysis (DFD) purano vayo, aaja bholi **Object Oriented** chalcha.

*   **Concept:** Sansar lai **Objects** ra **Classes** ko rup ma herne.
*   **Class:** Blueprint (Naksha). E.g., 'Student'.
*   **Object:** Real thing. E.g., 'Ram (Roll no 1)'.
*   **Attributes:** Gun (Properties). E.g., Name, Age.
*   **Methods:** Kaam (Functions). E.g., Study(), GiveExam().
*   **Analysis:** OOA ma hami system lai Objects ko interaction ko rup ma herchau. Yesko lagi **UML (Unified Modeling Language)** use garinchha (Use Case, Class Diagram etc.).

---

### **Viva Quick Recap (Unit III Summary)**

Yadi external le **"Unit 3 ma k sikyau?"** vanyo vane:

"Sir, Unit 3 ma hami le **Requirements Engineering** sikyou.
*   Requirement mukhya gari **Functional** (What it does) ra **Non-Functional** (Quality like speed/security) huncha.
*   Requirement Engineering ko 4 wota step huncha: **Feasibility** (Sakinchha?), **Elicitation** (Khojne), **Specification** (SRS Lekhne), ra **Validation** (Check garne).
*   Requirement bujhna lai hami **Context Model**, **Data Model (ER)**, ra **Behavioural Model** banauchau.
*   Antya ma, requirement clear vaye matra project successful huncha."

---

**Exam Tip:** "Difference between Functional and Non-Functional Requirements" vannu vayo vane table banayera kamti ma 4 ota point lekhnu, example sahit. Pass hune brahmastra tei ho yo unit bata.
