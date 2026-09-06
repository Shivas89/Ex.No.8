# Ex.No.8 – Automated Workflow Using Structured Prompts

## Aim

To develop an automated workflow using structured prompts for an AI-based Smart Study Management System to automate study planning, revision scheduling, task creation, note generation, quiz generation, and FAQ creation.

## AI Tools Required

* ChatGPT
* Large Language Model (LLM)
* Python
* Web Browser
* Visual Studio Code

## Project Used

### SMARTSTUDY – AI-Based Personal Study Management System

SMARTSTUDY is an AI-assisted application designed to help students organize their academic activities using structured prompts.

The system provides features such as:

* Personalized study planning
* Revision scheduling
* Task generation
* Note summarization
* Quiz generation
* Exam preparation
* FAQ generation

## Experiment Overview

Structured prompts can be used to automate repetitive academic activities.

For SMARTSTUDY, the workflow automates:

1. Study Plan Generation
2. Revision Schedule
3. Task Planning
4. Note Generation
5. Quiz Generation
6. FAQ Generation

## Problem Statement

Develop an AI-assisted automated workflow that accepts student information and uses structured prompts to automatically generate personalized study plans, revision schedules, academic tasks, notes, quizzes, and frequently asked questions.

The workflow should reduce repetitive planning work and provide organized learning support.

# Automated Workflow

```text
                 Student Information
                         |
                         v
                Structured Prompt
                         |
                         v
                 Large Language Model
                         |
          +--------------+--------------+
          |              |              |
          v              v              v
     Study Planning   Learning      Assessment
          |              |              |
          v              v              v
    Study Schedule     Notes          Quiz
    Revision Plan      Summary        Questions
          |              |              |
          +--------------+--------------+
                         |
                         v
                  Student Review
                         |
                         v
                Final Study Material
```

# Input to the Workflow

```text
Student Name:
Student

Subject:
Digital Electronics

Topic:
Karnaugh Maps

Available Study Time:
2 Hours

Learning Level:
Intermediate

Goal:
Examination Preparation

Main Requirements:
- Learn concepts
- Practice problems
- Revise important topics
```

# Procedure

1. Select the SmartStudy project.
2. Identify repetitive academic activities.
3. Collect student information.
4. Design structured prompts for each activity.
5. Provide the information and prompts to the LLM.
6. Generate the required outputs.
7. Review the AI-generated results.
8. Correct inaccurate information.
9. Combine the outputs into an automated workflow.
10. Evaluate the usefulness of structured prompting.

# Workflow 1 – Study Plan Generation

## Objective

Automatically generate a personalized study plan from basic student information.

### Structured Prompt

```text
Act as an AI study planner.

Create a 2-hour study plan for Digital Electronics,
specifically Karnaugh Maps.

Student level: Intermediate
Goal: Examination preparation.

Include:
- Concepts
- Examples
- Practice
- Revision

Use a clear time-based format.
```

### Automated Output

| Time        | Activity             |
| ----------- | -------------------- |
| 0–30 min    | Learn K-Map basics   |
| 30–60 min   | Study grouping rules |
| 60–100 min  | Solve problems       |
| 100–120 min | Revision             |

### Result

The structured prompt converts student information into a personalized study schedule.

# Workflow 2 – Revision Schedule

## Objective

Automatically create a revision schedule for important topics.

### Structured Prompt

```text
Act as an examination preparation assistant.

Create a revision schedule for Karnaugh Maps.

Prioritize:
- Important concepts
- Common mistakes
- Problem solving
- Quick revision
```

### Automated Output

| Day   | Revision Activity    |
| ----- | -------------------- |
| Day 1 | Basic K-Map concepts |
| Day 2 | Grouping rules       |
| Day 3 | 3-variable problems  |
| Day 4 | 4-variable problems  |
| Day 5 | Full revision        |

### Result

The AI converts the topic into an organized revision schedule.

# Workflow 3 – Task Planning

## Objective

Automatically convert learning goals into actionable study tasks.

### Structured Prompt

```text
Act as an academic task planner.

Convert the following learning goal into tasks.

Categorize tasks into:
- Learning
- Practice
- Revision
- Assessment

For each task provide:
- Task name
- Priority
- Expected outcome
```

### Automated Output

| Category   | Task                      | Priority |
| ---------- | ------------------------- | -------- |
| Learning   | Study K-Map basics        | High     |
| Learning   | Learn grouping rules      | High     |
| Practice   | Solve 3-variable problems | High     |
| Practice   | Solve 4-variable problems | High     |
| Revision   | Review important rules    | Medium   |
| Assessment | Take a short quiz         | High     |

### Result

The structured prompt converts a general learning goal into actionable tasks.

# Workflow 4 – Note Generation

## Objective

Automatically convert a topic into short revision notes.

### Structured Prompt

```text
Act as an academic note-making assistant.

Create short and simple revision notes for Karnaugh Maps.

Include:
- Definition
- Important rules
- Steps
- Common mistakes
- Key points

Do not include unnecessary information.
```

### Automated Output

## Karnaugh Map – Quick Notes

* K-Map is used to simplify Boolean expressions.
* Groups should contain powers of two.
* Make the largest possible groups.
* Groups can overlap.
* Diagonal cells cannot be grouped.
* Don't-care conditions may be used when useful.

### Result

The AI converts a complex topic into concise revision material.

# Workflow 5 – Quiz Generation

## Objective

Automatically generate practice questions for examination preparation.

### Structured Prompt

```text
Act as an examination question generator.

Generate 5 questions about Karnaugh Maps.

Include:
- 2 basic questions
- 2 application questions
- 1 challenging question

Provide answers separately.
```

### Automated Output

| Question Type | Number |
| ------------- | -----: |
| Basic         |      2 |
| Application   |      2 |
| Challenging   |      1 |

### Result

The structured prompt generates questions according to the student's required difficulty level.

# Workflow 6 – FAQ Generation

## Objective

Automatically generate frequently asked questions for students.

### Structured Prompt

```text
You are an academic support assistant.

Generate 10 frequently asked questions about
Karnaugh Maps.

Each FAQ should contain:
- Question
- Simple answer

Cover concepts, grouping, variables,
don't-care conditions and common mistakes.
```

### Automated Output

### 1. What is a Karnaugh Map?

A Karnaugh Map is a graphical method used to simplify Boolean expressions.

### 2. Why are K-Maps used?

They help reduce Boolean expressions and simplify digital logic circuits.

### 3. How many cells are in a 4-variable K-Map?

A 4-variable K-Map contains 16 cells.

### 4. Can groups overlap?

Yes. Overlapping groups are allowed when they help produce a simpler expression.

### 5. Can diagonal cells be grouped?

No. Groups must contain adjacent cells.

### Result

The structured prompt automatically creates simple educational FAQ content.

# Complete Automated Workflow

```text
                  Student Data
                       |
                       v
              Structured Prompt
                       |
                       v
             Large Language Model
                       |
        +--------------+--------------+
        |              |              |
        v              v              v
   Study Plan      Revision        Task Planning
        |              |              |
        +--------------+--------------+
                       |
                       v
                  Note Generation
                       |
                       v
                  Quiz Generation
                       |
                       v
                  FAQ Generation
                       |
                       v
                 Student Review
                       |
                       v
                Final Study Plan
```

# Prompt Design Used

The workflow follows this structured prompting pattern:

```text
ROLE
  ↓
STUDENT CONTEXT
  ↓
TASK
  ↓
INPUT DATA
  ↓
CONSTRAINTS
  ↓
OUTPUT FORMAT
  ↓
VALIDATION
```

## Example Structured Prompt

```text
Role:
Act as an AI academic study assistant.

Context:
You are helping an engineering student prepare for an examination.

Task:
Create a personalized study plan.

Input:
Subject: Digital Electronics
Topic: Karnaugh Maps
Time: 2 hours
Level: Intermediate

Constraints:
Use simple language.
Do not include unrelated topics.

Output Format:
Study Goal
Time Schedule
Important Concepts
Practice
Revision
```

# Automation Benefits

| Manual Activity      | Automated Output      | Benefit               |
| -------------------- | --------------------- | --------------------- |
| Creating study plans | Personalized schedule | Saves time            |
| Planning revision    | Revision timetable    | Better preparation    |
| Creating tasks       | Organized task list   | Improves productivity |
| Writing notes        | Short notes           | Faster revision       |
| Creating questions   | Practice quiz         | Better assessment     |
| Preparing FAQs       | Student FAQs          | Easy learning support |

# Advantages of Structured Prompts

## 1. Consistency

Structured prompts produce outputs in a predictable format.

## 2. Reduced Manual Work

Repeated academic planning activities can be generated automatically.

## 3. Personalization

The workflow can use the student's subject, level, available time, and goal.

## 4. Better Organization

Learning activities are divided into clear categories.

## 5. Improved Productivity

Students can spend more time learning rather than planning.

## 6. Reusability

The same prompt templates can be used for different subjects and topics.

## 7. Better Learning Support

The system can provide study plans, notes, quizzes, and revision schedules from the same student information.

# Validation and Human Review

AI-generated academic content should be reviewed before being used for examination preparation.

The following checks should be performed:

* Verify technical information.
* Check the study schedule.
* Confirm answers to quiz questions.
* Check that generated notes are accurate.
* Verify that no important topics are missing.
* Review the final study plan.

# Result

The **SMARTSTUDY automated workflow** successfully demonstrates how structured prompts can transform basic student information into personalized study plans, revision schedules, tasks, notes, quizzes, and FAQs.


# Conclusion


The experiment demonstrates that structured prompts can automate repetitive academic activities and provide personalized learning support.By combining role, context, task, input, constraints, output format, and validation, a Large Language Model can generate consistent and useful educational outputs.Thus, structured prompt-based workflows can improve student productivity, organization, creativity, and practical problem-solving.

