

Yo unit **5 Hours** ko vaye pani Exam ma **Long Question** (Explain Spiral Model/Agile) ra Viva ma **Difference** (Waterfall vs Agile) sodhne main unit ho.

---

### **Unit II: Software Process Models and Agility**

**Core Concept:**
Sir/Mam, Software hawa taal ma banayera hudaina. Euta **Systematic Tarika** (Roadmap) chaincha jaslai hami **Process Model** vanchau. Kun project lai kun model thik huncha vanera hami yo unit ma sikchau.

---

### **2.1 Software Development Lifecycle (SDLC)**

**Definition:**
SDLC vaneko software ko **"Janma dekhi Mrityu"** (Birth to Death) samma ko chakra ho. Software kasari banne ra kasari maintain hune vanne framework ho.

**Main 5 Phases (Generic View):**
1.  **Communication:** User sanga kura garne, requirement bujhne.
2.  **Planning:** Estimating, scheduling, tracking.
3.  **Modeling:**
    *   *Analysis:* Requirement lai detail ma herne.
    *   *Design:* Architecture ra UI banaune.
4.  **Construction:**
    *   *Code:* Programming garne.
    *   *Test:* Bug khojne.
5.  **Deployment:** User lai software dine ra support garne.

---

### **2.2 Prescriptive Process Models (Traditional Models)**

Yiniharu purano style ko models hunn, jaha process strict huncha.

**1. Waterfall Model (Linear Sequential):**
*   **Concept:** Jharna (Waterfall) jastai pani mathi bata tala jharcha, farkera mathi jadaina. Ek choti 'Analysis' sakkiyepachi firta aauna mildaina.
*   **Use:** Jab **Requirement 100% Clear** chha ra change hudaina (Ex: Simple Calculator, Attendance System).
*   *Neplish Problem:* Real world ma requirement sadhai change vairakhcha, tei vayera yo fail khancha. "Blocking state" aauxa (Euta phase nasaki arko suru hudaina).

**2. Incremental Model:**
*   **Concept:** Pura software ekai choti nadine. Tukra-tukra (**Increments**) ma dine.
    *   *First Increment:* Core product (Basic features).
    *   *Next Increment:* Extra features thapdai jane.
*   **Faida:** User le chado software chalauna paucha.

**3. Prototyping Model (Viva Favorite):**
*   **Concept:** User lai k chaincha thaha chaina? Paila euta **"Dummy"** (Khelouna) banaune. User lai dekhaune. User le "Yesto haina yesto chaiyo" vancha. Ani balla Real software banauna thalne.
*   **Use:** Jab **Requirement Unclear** huncha.
*   **Risk:** Kaile kahi client le "Dummy" lai nai real sochera "Lau malai tei deu" vandincha.

**4. Spiral Model (Risk Driven):**
*   **Concept:** Yo **Ghumi-Ghumi** (Loop) ma bancha. Prototyping ra Waterfall ko mix ho.
*   **Key Feature:** Harek loop ma **Risk Analysis** garincha.
*   **Use:** Thulo ra mahango project ma (Ex: NASA, Banking Software) jaha risk lina sakidaina.

**5. RAD (Rapid Application Development):**
*   **Concept:** "Malai 2-3 mahina vitra software chaincha." Chito banauna lai "Component Reuse" garne (Banisakeko code use garne).
*   **Constraint:** Dherai manchhe chaincha (Human Resource) ra Modular garna milne project huna parcha.

**6. Aspect-Oriented Software Engineering (AOSE):**
*   **Concept:** Software ma kei kura haru "Cross-cutting" hunchan (Jastai Security, Logging - jun sabai module ma chaincha). AOSE le yesta kura lai xuttai **"Aspect"** banayera manage garcha.

---

### **2.3 Agile Software Development (Modern & Most Important)**

**1. The Agile Concept:**
Purano model (Waterfall) ma documentation dherai hunthyo, change garna mildaina thiyo. Agile le vanyo:
*   **Individuals & Interactions** > Process & Tools.
*   **Working Software** > Comprehensive Documentation (Thulo file vanda chalne software thulo ho).
*   **Customer Collaboration** > Contract Negotiation.
*   **Responding to Change** > Following a Plan.

**2. 2.3.1 Extreme Programming (XP):**
Yo coding ma focus garne agile method ho.
*   **Pair Programming:** Euta computer ma dui jana developer basne. Eutale type garcha, arkole check garcha.
*   **TDD (Test Driven Development):** Code lekhnu vanda aghi Test case lekhne.
*   **Continuous Integration:** Din ma dherai choti code merge garne.

**3. 2.3.2 Scrum (The Industry Standard - Viva Q):**
Aaja bholi 90% IT company ma Scrum use huncha.
*   **Roles:**
    *   **Product Owner (PO):** Client ko representative. "K banaune" vanera list (Backlog) banaucha.
    *   **Scrum Master:** Team ko helper (Servant Leader). Rule palana garaune.
    *   **Development Team:** Kaam garne manchhe haru.
*   **Artifacts:**
    *   **Product Backlog:** Kaam ko list.
    *   **Sprint Backlog:** Yo mahina (Sprint) garne kaam ko list.
*   **Events:**
    *   **Sprint:** 2-4 weeks ko time box jaha kaam sakincha.
    *   **Daily Standup:** Bihe 15 min ko meeting. "Hijo k gare? Aaja k garchu? K samasya chha?"

**4. 2.3.3 Agile Scaling:**
Sano team (5-9 jana) lai Agile thik chha. Tara 100 jana ko team vayo vane? Teti bela **SAFe (Scaled Agile Framework)** use garincha.

---

### **2.4 Pros, Cons and Applicability (Summary Table)**

Viva ma "Kun bela kun use garne?" vanyo vane:

| Model | Pros (Ramro) | Cons (Naramro) | Applicability (Kahile Use Garne?) |
| :--- | :--- | :--- | :--- |
| **Waterfall** | Simple, Easy to manage | Change garna mildaina | Requirement 100% fix vaye matra. |
| **Prototype** | User feedback paincha | Paisa ra time waste huna sakcha | Requirement clear nabhaye. |
| **Spiral** | Risk management huncha | Complex ra Mahango huncha | High-risk, Thulo project ma. |
| **Incremental**| Chado product paincha | Planning garo huncha | Product lai tukrauna milcha vane. |
| **Agile (Scrum)** | Flexible, Customer happy | Senior developer chaincha | Startups, Web dev, Changing requirement huda. |

---

### **Viva Quick Recap (Unit II Summary)**

Yadi external le **"Unit 2 ma k padhyau?"** vanyo vane:

"Sir, Unit 2 ma hami le **Software Process Models** padhyou.
*   Software banaune systematic tarika lai **SDLC** vanincha.
*   Requirement clear huda **Waterfall** thik huncha, clear nabhaye **Prototype** banaunu parcha.
*   Thulo ra Risk vako project ma **Spiral Model** best ho.
*   Tara aaja bholi ko dynamic world ma, jaha requirement change vairakhcha, tei vayera **Agile (Scrum/XP)** dherai use huncha. Agile le documentation vanda **Working Software** lai priority dincha."
