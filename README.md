# ALGOSUP Archives

## Table of Contents

- [ALGOSUP Archives](#algosup-archives)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
    - [Guidelines](#guidelines)
  - [Project Management - Project Manager](#project-management---project-manager)
    - [Serious Game - by _Maxime T._ (100%)](#serious-game---by-maxime-t-100)
    - [Adopte 1 Candidat (Flutter App) - by _Antoine P._ (100%)](#adopte-1-candidat-flutter-app---by-antoine-p-100)
  - [Functional Specification - Program Manager](#functional-specification---program-manager)
    - [Quickest Path - by _Antoine P._ (90%)](#quickest-path---by-antoine-p-90)
    - [Quickest Path – by _Alexis L._ (70%)](#quickest-path--by-alexis-l-70)
  - [Technical Specification - Tech Lead](#technical-specification---tech-lead)
  - [Test Plan \& Test Case - Quality Assurance](#test-plan--test-case---quality-assurance)
    - [FPGA Frogger Clone - by _Antoine P._ (70%)](#fpga-frogger-clone---by-antoine-p-70)
  - [User Manual - Technical Writer](#user-manual---technical-writer)
    - [FPGA Frogger Clone - by _Thibaud M._ (100%)](#fpga-frogger-clone---by-thibaud-m-100)
    - [Sportshield - by _Victor L._ (90%)](#sportshield---by-victor-l-90)
    - [Quickest Path – by _Camille G._ (80%)](#quickest-path--by-camille-g-80)

## Introduction

Welcome to the **ALGOSUP Archives** — a curated collection of high-quality documents created by ALGOSUP students.

The goal of this repository is to provide a valuable learning resource for current and future promotions.
By showcasing strong examples across different document types, we aim to help students improve their writing, structure, and overall approach to documentation.

Whether you're drafting your first technical specification or refining a test plan, this archive is here to inspire and guide you.
Feel free to explore the examples, learn from them, and when you're ready — contribute your own best work to the collection.

### Guidelines

- **Quality over quantity**
  We prioritize clarity, completeness, and professionalism. Only documents that demonstrate strong structure and valuable content will be added.
- **Diversity**
  Try to avoid duplicating content. If multiple documents exist on the same project, we’ll keep only the most representative or highest-quality one to avoid redundancy.

> [!CAUTION]
> This archive is a resource for learning, **not for copy-pasting.**
> Use the documents to inspire your own work, understand structure, and reflect on good practices. Your submissions should always be original and reflect your personal understanding.

## Project Management - Project Manager

### Serious Game - by _Maxime T._ (100%)

**_Project overview:_**
Development of a serious game designed to sensitize children and adults to the climate change issue.

**_Comments received:_**

```text
+ Your Gantt charts presents a reasonable breakdown of your total workload.
+ Excellent weekly reporting, very professional, and including a good level of detailing, without sacrificing concision. Kudos!
+ Good reporting on your progression with your “KPI” spreadsheet.
```

**_Summary:_**
Excellent work! We’d definitely hire you as a team manager.

**Folder link:** [Serious Game](./Management/100-SeriousGame-MaximeT/)

### Adopte 1 Candidat (Flutter App) - by _Antoine P._ (100%)

**Project overview:**  
Creation of a Tinder-like recruitment application solely focusing on soft skills.

**Comments received:**

```text
+ The Gantt chart is very well detailed.
+ There’s a precise breakdown of the tasks.
+ The comparison and reflection of the initial planning of the Gantt chart and the actual timeframes help understand how you performed.
+ Although it’s not part of the planning, congratulations on your thoughtful post-mortem, as it indicates you learned how to plan things even better for next time. You also explained very clearly the discrepancies between your original plan and the execution.
+ Very good charts showing how your team progressed to complete tasks over time.
+ Good document structure and good English.
+ Well detailed weekly reporting, all the information we’d be interested to follow up on your progress week-by-week is there.
```

**Summary:**  
Very impressive work. You did the job of managing the project better than we would have, so you would be the ideal hire if we needed a project manager. This is the type of work which makes us happy to review. Keep it up!

**Documents link:** [Adopte 1 Candidat](./Management/100-Adopte1Candidat-AntoineP/)

## Functional Specification - Program Manager

### Quickest Path - by _Antoine P._ (90%)

**_Project overview:_**
Development of an API designed to calculate the fastest route between two locations using the U.S. road network.

**_Comments received:_**

```text
+ Good document structure.
+ Effective use of headers to specify the response format.
+ Clearly defined hardware and performance constraints.
+ Good use of HTTP response codes.

- Instead of “shortest path duration”, use a more precise term such as shortest path distance, or shortest path travel time.
- The input format for the imported graph is only specified indirectly through error messages. There should be a dedicated section explicitly defining this format.
- What is the unit of the “total_time” output? Seconds? Minutes? Hours?
- You specify that the dataset size may not exceed 16GB, but you did not state what is the maximum amount of memory that your software may allocate.
```

**_Summary:_**
The document is well-structured, with a clear response format and properly defined performance constraints. However, terminology should be more precise, the graph input format presented more clearly, and time units must be explicitly stated. (edited)

**Document link:** [Quickest Path](./Functional/90-QuickestPath-AntoineP/functional_specification.md)

### Quickest Path – by _Alexis L._ (70%)

**_Project overview:_**
Development of an API designed to calculate the fastest route between two locations using the U.S. road network.

**_Comments received:_**

```text
+ Excellent document structure
+ Clear and well-written product description
+ Precise mapping of HTTP status codes to error conditions

- The expected input format for importing nodes should be formally specified
- Unclear how many simultaneous requests the system should support
- Unit of "travel_time" output is not defined (seconds, minutes, hours?)
- Memory usage limits are not stated
```

**_Summary:_**  
This document is well-organized and technically sound, with detailed product descriptions and strong handling of HTTP error codes. However, it would benefit from more precise technical specifications, especially regarding input formatting, performance limits, and data units.

**Document link:** [Quickest Path](./Functional/70-QuickestPath-AlexisL/FunctionalSpecification.md)

## Technical Specification - Tech Lead

## Test Plan & Test Case - Quality Assurance

### FPGA Frogger Clone - by _Antoine P._ (70%)

**Project overview:**  
Recreate the classic Frogger Arcade Game using an on-chip FPGA and Verilog.

**Comments received:**

```+ Good job using a simulator to aid the testing.
+ Good and well documented test strategy.
+ It seems like you specified tests for all the aspects of the game mechanics.
- A spreadsheet with 50 different tabs isn’t a very effective/professional way to organize your data—try a format that’s more adequate to your needs and is more effective next time.
- Use a grammar checker “without significant bug.”
```

**_Summary:_**  
Professional testing, congratulations. Next, just make sure to check the English in your documents, and work harder to make your documentation more concise, and structure your documents in way that’s most effective for them to be read/used.

**Documents link:** [FPGA Frogger Clone](./QA/70-FPGA-FroggerClone-AntoineP/)

## User Manual - Technical Writer

### FPGA Frogger Clone - by _Thibaud M._ (100%)

**_Project overview:_**
Recreate the classic Frogger Arcade Game using an on-chip FPGA and Verilog.

**_Comments received:_**

```text
+ Good document structure
+ Good typesetting
+ Good job providing an installer script
+ Excellent explanation of the gameplay
```

**_Summary:_**
Professional and engaging manual, congratulations!

**_Document link:_** [FPGA Frogger Clone](./UserManual/100-FPGA-FroggerClone-ThibaudM/user_manual_froggo.pdf)

### Sportshield - by _Victor L._ (90%)

**_Project overview:_**
Development of an electronic component designed as an anti-theft device for skis and snowboards.
**_Comments received:_**

```text
+ Well-structured document.
+ Concise document.
+ Very detailed information on how to use the device’s functionalities.
+ Good images showing how to attach the device to a sports gear.
+ Good images of the application’s interface, it allows the user to get to know the application well through your manual.
+ Good job providing the operation temperature for using and storing the device.
+ Professional use of English.
+ The little extras such as “recycling” are useful and didn’t stop you from keeping your document concise. Kudos!

± Good job advising the user to unpair the device before he or she sells it. You could have described what is the negative consequence of selling or purchasing a device without observing this instruction.
± It’s good that you provide a French version of the manual, but it contains two images where there’s English text. Also, your English manual has several images with French text.
± “Safety and Handling” section is good but feels slightly disjointed. Maybe you could have had one section about user safety and another one about operating conditions.
```

**_Summary:_**
We were impressed with the professionalism of your document. Crucially, you found an outstanding balance between detail and concision.

**Document link:** [Sporthield](./UserManual/90-Sportshield-VictorL/)

### Quickest Path – by _Camille G._ (80%)

**_Project overview:_**
Development of an API designed to calculate the fastest route between two locations using the U.S. road network.

**_Comments received:_**

```text
+ Simple and concise.
+ Multi-language.
+ Includes pictures.
+ Includes installation instructions.
+ Good typesetting.
+ Good English.

- You could have shown the user what happens on error conditions. What is shown in case an ID that doesn’t exist is input?
- You could have explained how users can build from the source.
- The manual says “Ensure you are using a computer that meets the minimum hardware requirements.”, but these requirements aren’t specified.
```

**Document link:** [Quickest Path API](./UserManual/80-QuickestPath-CamilleG/user_manual.pdf)
