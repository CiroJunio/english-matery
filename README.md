# 🏗️ English Mastery

> **Objective:** Systematize the acquisition of English through Spaced Repetition (SRS) and logical output. This repository serves as the technical documentation and execution log for a high-utility language database.

## 📁 Repository Architecture
* **`00_raw/`**: Source files. Contains Oxford 1000 (A1-A2) word lists and high-frequency phrase documentation.
* **`01_anki/`**: Backup directory. Stores `.apkg` exports to ensure database persistence.
* **`02_logs/`**: Execution Lab. Daily activity records and weekly neutral writing outputs.

---

## ⚙️ The Execution Algorithm

### Phase 1: Database Management (Card Creation)
* **Word Selection**: Focus on the Oxford 1000 List.
* **Card Formatting**: Use Cloze Deletion only. Every card must provide a high-utility daily context. No isolated words.
* **Phrase Selection**: Focus on the Oxford Phrase List. 
* **Logic Triggers**: Front of the card defines the **Logical Intent** (e.g., `[TO COMPARE OPTIONS]`); Back provides the phrase. Zero Portuguese translation allowed.
* **Rate Limit**: Maximum 10 new words and 5 new phrases per day.

### Phase 2: Runtime (30-Minute Daily SRS)
* **Performance**: Maintain 5-7 seconds per card. Focus on subconscious retrieval speed.
* **Vocalization**: Phrases must be articulated out loud to build muscle memory.
* **Validation**: Only mark "Good" if the response is immediate and requires no mental translation.

### Phase 3: Output Protocol (Neutral Writing)
* **Schedule**: Friday, Saturday, Sunday, and non-academic days.
* **Method**: 15 minutes of "Neutral Observer" writing.
* **Constraint**: Avoid personal topics. Write only about abstract or external concepts (Technology, Engineering, Architecture, History).
* **Process**: 10 minutes of drafting (no external aids) + 5 minutes of technical audit (LanguageTool/Pot).

---

## 📊 System Constraints
1.  **Leech Removal**: Cards failing more than 5 times must be deleted. Bad data must be purged to maintain queue efficiency.
2.  **L1 Restriction**: Use of Portuguese is prohibited within Anki cards and log files.
3.  **Consistency Rule**: If a daily block is missed, do not double the load the next day. Maintain the rate limit.

---

## 🚀 Daily Check
- [ ] Daily Anki block executed.
- [ ] Word/Phrase daily quota added.
- [ ] (If applicable) Writing log committed to `02_logs/`.

**"System Verified. Efficiency Optimized."**