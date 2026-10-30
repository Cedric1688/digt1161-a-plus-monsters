# Interview plan and blank evidence record

Status: interviews not conducted. This kit contains recruitment criteria, questions and blank fields, not participant statements or findings. Bob, Priya, Marcus and Jordan in the proposal are hypothetical personas and are not interview participants.

## Who to interview

Recruit two or three consenting real participants. Prioritise CS or programming students who know Python loops, functions and basic data structures and have used an AI assistant for coding. Classmates or students from another programming class are suitable; the participants need not be professors or company managers.

Suggested mix:

1. A Python-capable student who frequently uses AI coding assistance.
2. Another Python-capable student with a different study schedule or device preference.
3. If available, a bootcamp graduate or junior developer as an exploratory secondary audience. Otherwise recruit a third eligible student.

Use participant IDs P01–P03 in project evidence. A first-year student still learning basic loops can help test the entry prerequisite, but should not be counted as a representative primary user who already knows the basics.

## Consent and logistics

Allow about ten minutes per participant. Explain that this is a class-project research activity, participation is voluntary, questions may be skipped, and participation can stop at any time. Ask permission to take anonymised notes. Do not record audio or video without separate explicit consent. Avoid collecting names, emails, work code or assignment submissions in the research record.

Suggested opening: "We are exploring a short daily code-review practice tool for a class project. This is not a test of you. May we take anonymous notes about your coding and study habits? You can skip any question or stop at any time."

The team member conducting the interview must obtain the actual answer to consent. This script is not evidence that consent has already been obtained.

## Questions

1. When you use AI to help write code, what do you do before using that code? Tell us about a recent example without sharing private code.
2. Have you found an error in AI-generated code? How did you notice it, and what did you do next? "No" is a valid answer.
3. What makes reviewing unfamiliar code difficult for you? What do you currently use for help?
4. When and where do you practise coding, on which device, and for roughly how long?
5. After briefly describing the proposed daily challenge, what would make you try or avoid it? What part seems unclear?
6. Would a shared daily streak with friends help, add pressure, or make no difference? Why?
7. What feedback would help you understand why an answer was right or wrong?

Start with current behaviour before asking opinions about the proposed app. Do not suggest that participants must have missed AI bugs or must like streaks. Keep observed behaviour, reported behaviour and your interpretation separate.

## Optional prerequisite task

Use only after consent, and explain that it helps us understand the entry level:

```python
def count_positive(values):
    count = 0
    for value in values:
        if value > 0:
            count += 1
    return count

print(count_positive([-2, 0, 3, 5]))
```

Ask what it prints and why. Interviewer key: `2`; zero is not positive. Do not present a correct answer as evidence of broader code-review proficiency.

## One blank record per participant

| Field | Actual record to complete after the interview |
|---|---|
| Participant ID | P__ |
| Date and interviewer | Not yet recorded |
| Consent to anonymous notes | Not yet obtained |
| Relevant Python and AI experience | Not yet collected |
| Current code-checking behaviour and example | Not yet collected |
| Device, context and session length | Not yet collected |
| Difficulties and existing alternatives | Not yet collected |
| Reaction to daily practice and group streak | Not yet collected |
| Optional task observation | Not yet conducted |
| Accurate short quote, if permission allows | No quote collected |
| Researcher's interpretation | Not yet analysed |

## Synthesis after actual interviews

| Assumption | Evidence from participant IDs | Supported, challenged or still unknown | Design implication |
|---|---|---|---|
| Eligible learners need review practice | Not yet collected | Unknown | Do not assert validation |
| Five-minute mobile sessions fit their routine | Not yet collected | Unknown | Do not assert validation |
| A shared streak motivates rather than pressures | Not yet collected | Unknown | Do not assert validation |
| Existing Python knowledge is the right prerequisite | Not yet collected | Unknown | Do not assert validation |

Report disagreements and limitations. Two or three interviews provide exploratory evidence, not population-wide proof or evidence that the app improves learning. Update the proposal only with real findings. Ask the TA whether this stage requires results or permits the current research plan.
