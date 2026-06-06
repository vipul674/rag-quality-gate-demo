# Golden Evaluation Dataset — Internship Application Documentation Assistant

This dataset contains 25 regression-focused evaluation questions for the fictional **NovaTech Summer Internship Program 2026** documentation set.

## Distribution

| Group | Count | Purpose |
|---|---:|---|
| Easy factual | 10 | Direct answer exists in one document |
| Multi-document | 9 | Requires combining two or more documents |
| Edge/confusing | 6 | Tests similar wording, deadline exceptions, and missing-policy assumptions |

## Easy factual

### EASY-001

**Question:** Who is eligible to apply for the NovaTech Summer Internship Program 2026?

**Expected answer / reference:** Applicants must be currently enrolled in a recognized undergraduate or postgraduate program, graduate in 2026, 2027, or 2028, be available from June 1 to August 7, 2026, be legally eligible for a paid internship, have a laptop and stable internet, and commit at least 35 hours per week.

**Expected source document:** `internship_eligibility.md`

**Difficulty level:** Easy

### EASY-002

**Question:** What is the minimum academic requirement for applicants?

**Expected answer / reference:** Applicants need at least a 7.0 CGPA out of 10, or 70% aggregate, or equivalent academic standing based on their institution's grading system.

**Expected source document:** `internship_eligibility.md`

**Difficulty level:** Easy

### EASY-003

**Question:** What file format must the resume be submitted in?

**Expected answer / reference:** The resume must be submitted as a PDF file.

**Expected source document:** `resume_guidelines.md`

**Difficulty level:** Easy

### EASY-004

**Question:** What is the required resume file naming format?

**Expected answer / reference:** The resume file should use the format FirstName_LastName_Track_Resume.pdf, for example Aarav_Sharma_AIEngineering_Resume.pdf.

**Expected source document:** `resume_guidelines.md`

**Difficulty level:** Easy

### EASY-005

**Question:** What are the five stages of the application process?

**Expected answer / reference:** The five stages are online application submission, document screening, online assessment, technical or portfolio interview, and final selection and offer confirmation.

**Expected source document:** `application_process.md`

**Difficulty level:** Easy

### EASY-006

**Question:** When is the online assessment window?

**Expected answer / reference:** The online assessment window is March 22, 2026 to March 24, 2026.

**Expected source document:** `deadline_policy.md`

**Difficulty level:** Easy

### EASY-007

**Question:** How many relevant projects must applicants submit?

**Expected answer / reference:** Applicants must submit at least one relevant project and may submit up to three projects.

**Expected source document:** `project_submission_rules.md`

**Difficulty level:** Easy

### EASY-008

**Question:** How long is the usual interview?

**Expected answer / reference:** Most applicants attend one interview of 30 to 45 minutes.

**Expected source document:** `interview_preparation.md`

**Difficulty level:** Easy

### EASY-009

**Question:** What email should applicants use for general application support?

**Expected answer / reference:** Applicants should email internships-support@novatech.example for general application support.

**Expected source document:** `contact_escalation_flow.md`

**Difficulty level:** Easy

### EASY-010

**Question:** What are common resume mistakes applicants should avoid?

**Expected answer / reference:** Common resume mistakes include uploading DOCX instead of PDF, exceeding the page limit, missing graduation year, missing contact details, listing skills they cannot explain, vague project descriptions, missing project links, overly visual formatting, unprofessional file names, and sensitive identity numbers.

**Expected source document:** `common_mistakes.md`

**Difficulty level:** Easy

## Multi-document

### MULTI-001

**Question:** What documents are required during the application and before joining if selected?

**Expected answer / reference:** During application, applicants must provide information including resume upload, project or portfolio link, academic details, track preference, and short answers. Before joining, selected applicants must submit a signed offer letter, government-issued ID, college ID card, recent transcript or marksheet, bank details, emergency contact information, confidentiality agreement, and internship participation consent form if required by the college.

**Expected source document:** `application_process.md; resume_guidelines.md`

**Difficulty level:** Medium

### MULTI-002

**Question:** Can a 2027 undergraduate student with 7.2 CGPA apply, and what resume length should they use?

**Expected answer / reference:** Yes. A 2027 undergraduate student is eligible if they meet the other requirements, and 7.2 CGPA satisfies the minimum 7.0 CGPA requirement. As an undergraduate, they should submit a one-page resume.

**Expected source document:** `internship_eligibility.md; resume_guidelines.md`

**Difficulty level:** Medium

### MULTI-003

**Question:** If an applicant has an AI project, what should the resume and project submission explain?

**Expected answer / reference:** The resume project section should include the project name, problem solved, technologies used, personal contribution, measurable result if available, and a link. The AI project submission should explain the model or API used, input and output format, evaluation method, failure cases, data source, safety or misuse considerations, and cost or latency tradeoffs if relevant.

**Expected source document:** `resume_guidelines.md; project_submission_rules.md`

**Difficulty level:** Medium

### MULTI-004

**Question:** What should an applicant do if the assessment platform fails during the test window?

**Expected answer / reference:** They should contact assessment-help@novatech.example, which has a 24-hour response time during the assessment window. Extra attempts are allowed only if the assessment platform confirms a technical failure.

**Expected source document:** `deadline_policy.md; contact_escalation_flow.md`

**Difficulty level:** Medium

### MULTI-005

**Question:** How should a product design applicant prepare and what must they submit?

**Expected answer / reference:** A product design applicant must submit a portfolio or case study link. Their design submission should include a problem statement, target users, user research summary, wireframes or prototypes, design decisions, usability considerations, and final screens or flows. They should prepare design thinking, user research, wireframes, usability testing, portfolio walkthrough, and accessibility basics for the interview.

**Expected source document:** `faq.md; project_submission_rules.md; interview_preparation.md`

**Difficulty level:** Medium

### MULTI-006

**Question:** What happens after a student receives an offer, and what is the deadline to accept it?

**Expected answer / reference:** Selected applicants receive an offer by email and must confirm acceptance within 5 calendar days of receiving the offer. If they do not accept in time, NovaTech may withdraw the offer and contact a waitlisted candidate.

**Expected source document:** `application_process.md; deadline_policy.md`

**Difficulty level:** Medium

### MULTI-007

**Question:** What should applicants include in a support email, and what subject line format is recommended?

**Expected answer / reference:** Applicants should use the same email address used in the application and include full name, application ID if available, internship track, registered email address, clear issue description, and screenshot if relevant. The recommended subject format is [NovaTech Internship 2026] Issue Type - Full Name - Application ID.

**Expected source document:** `contact_escalation_flow.md; common_mistakes.md`

**Difficulty level:** Medium

### MULTI-008

**Question:** What should an AI Engineering applicant prepare for the interview and what baseline skills are expected for eligibility?

**Expected answer / reference:** For eligibility, AI Engineering applicants are expected to have Python, machine learning fundamentals, prompt engineering basics, APIs, and basic understanding of embeddings or vector databases. For the interview, they should prepare Python basics, machine learning concepts, evaluation metrics, prompt engineering, embeddings, vector search, APIs, limitations of LLMs, and responsible AI basics.

**Expected source document:** `internship_eligibility.md; interview_preparation.md`

**Difficulty level:** Medium

### MULTI-009

**Question:** What should applicants verify before submitting to avoid common project and application mistakes?

**Expected answer / reference:** Applicants should verify their selected track, email address, academic details, project links, resume format, and deadlines. For projects, they should ensure the README is clear, links are accessible, no API keys or credentials are exposed, the work is relevant to the selected track, copied tutorial work is not submitted as original, and personal contribution is explained.

**Expected source document:** `common_mistakes.md; project_submission_rules.md; application_process.md`

**Difficulty level:** Medium

## Edge/confusing

### EDGE-001

**Question:** If a student misses the March 15 application deadline, can they use the March 18 resume correction window to submit a new application?

**Expected answer / reference:** No. The resume correction window is only for applicants who submitted before the deadline and need to replace a corrupted PDF, fix an accidentally uploaded wrong file, or upload a readable version of the same resume. It cannot be used to submit a new application after missing the original deadline.

**Expected source document:** `deadline_policy.md`

**Difficulty level:** Hard

### EDGE-002

**Question:** Can a late application be accepted because the applicant had individual internet issues or laptop problems?

**Expected answer / reference:** No. Late applications are not accepted unless there is a documented platform outage affecting multiple applicants. Individual internet issues, laptop problems, exam schedules, or missed reminders do not qualify for extension.

**Expected source document:** `deadline_policy.md`

**Difficulty level:** Hard

### EDGE-003

**Question:** Who should a student contact for a deadline extension?

**Expected answer / reference:** There is no standard individual deadline extension path. Late applications are accepted only for a documented platform-wide outage. For application support or clarification, the relevant contact is internships-support@novatech.example, but individual issues do not qualify for deadline extension.

**Expected source document:** `deadline_policy.md; contact_escalation_flow.md`

**Difficulty level:** Hard

### EDGE-004

**Question:** Can a student submit a project after the interview to improve their chances?

**Expected answer / reference:** The documents do not provide a post-interview project submission option. Projects are part of the application submission and review flow, and applicants should be ready to explain submitted projects during the interview.

**Expected source document:** `application_process.md; project_submission_rules.md; interview_preparation.md`

**Difficulty level:** Hard

### EDGE-005

**Question:** Is GitHub mandatory for all applicants?

**Expected answer / reference:** No. GitHub is strongly recommended for technical tracks but is not mandatory if the applicant provides another valid project link. Product Design applicants must submit a portfolio or case study link.

**Expected source document:** `faq.md; project_submission_rules.md`

**Difficulty level:** Hard

### EDGE-006

**Question:** Is a copied tutorial project acceptable if the student understands it?

**Expected answer / reference:** A tutorial-inspired project is allowed only if the applicant made meaningful original changes and can explain the implementation. A copied tutorial project with no original contribution is not acceptable.

**Expected source document:** `faq.md; project_submission_rules.md; common_mistakes.md`

**Difficulty level:** Hard

