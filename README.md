# Survey Data Encodings

## Demographics
* **tech-level**: "How would you rate your level of computer proficiency?"
  * 1: Far below average
  * 2: Slightly below average
  * 3: Average
  * 4: Slightly above average
  * 5: Far above average
  * blank: Prefer not to say
* **edu-level**: "What is the highest degree or level of school you have completed? (If currently enrolled, highest degree received)"
  * 1: Some high school, no diploma, and below
  * 2: High school graduate, diploma or equivalent (for example: GED)
  * 3: Some college credit, no degree
  * 4: Trade/technical/vocational training
  * 5: Bachelor's degree, and above
  * blank: Prefer not to say

## Task delegability factors
* **s_social_skills**: "This task requires social skills to complete."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree
* **s_creativity**: "This task requires creativity to complete."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree
* **d_effort**: "This task requires a great deal of time or effort to complete."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree
* **d_expertise**: "It takes significant training or expertise to be qualified for this task."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree
* **d_abilities**: "I am confident in my own abilities to complete this task."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree
* **r_accountable**: "In case of mistakes or failure on this task, someone needs to be held accountable."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree
* **r_uncertainty**: "A complex or unpredictable environment/situation is likely to cause this task to fail."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree
* **r_impact**: "Failure would result in a substantial negative impact on my life or the lives of others."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree
* **m_intrinsic**: "I would feel motivated to perform this task, even without needing to; for example, it is fun, interesting, or meaningful to me."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree
* **m_learning**: "I am interested in learning how to master this task, not just in the completing the task."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree
* **m_important**: "I consider this task especially valuable or important; I would feel committed to completing this task because of the value it adds to my life or the lives of others."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree
* **t_machine_ability**: "I trust the AI agent's ability to reliably complete the task."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree
* **t_process**: "Understanding the reasons behind the AI agent's actions is important for me to trust the AI agent on this task (e.g, explanations are necessary)."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree
* **t_values**: "I trust the AI agent's actions to protect my interests and align with my values for this task."
  * 1: Strongly disagree
  * 2: Disagree
  * 3: Neutral
  * 4: Agree
  * 5: Strongly agree

* **label**
  * 1: "Full AI automation"
  * 2: "The AI leads and the human assists"
  * 3: "The human leads and the AI assists"
  * 4: "No AI assistance"

Note on **label**: CSVs encode 4 as Human Only, 1 as Machine Only. This is arbitrary and unrelated to results, since the subjects simply saw an un-numbered list of delegability options in the survey.
Our analysis in paper and website, however, uses 1 as Human Only and 4 as Machine Only (axis was flipped in analysis such that a larger number corresponds to higher delegability).
