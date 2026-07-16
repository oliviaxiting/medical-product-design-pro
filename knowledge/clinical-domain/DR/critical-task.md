# DR Critical Tasks


## 1. Overview


Critical Tasks are tasks in the DR examination workflow where errors may result in:

- Patient safety risks
- Incorrect examination results
- Repeat exposure
- Workflow interruption


Medical imaging product design should identify and protect critical tasks.

Design principle:

> For critical tasks, the system should reduce the probability of errors, improve situation awareness, and support timely error detection and recovery.


---

# 2. Patient Identification


## Purpose

Ensure that:

> The correct patient receives the correct examination.


## Potential Risks

Errors may result in:

- Wrong patient examination
- Incorrect medical records
- Potential impact on diagnosis and treatment


## Common Causes of Errors

Including:

- Incorrect patient information entry
- Similar patient identities
- Incomplete emergency patient information
- Insufficient verification


## Design Controls

The system should:

- Clearly display patient identity information
- Highlight critical identification information
- Provide confirmation at critical points


## AI Assistance Principle

AI may:

- Detect abnormal information patterns
- Provide risk alerts


AI should not:

- Replace patient identity confirmation


---

# 3. Examination Selection


## Purpose

Select the correct examination type and imaging protocol.


## Potential Risks

Errors may result in:

- Incorrect imaging conditions
- Reduced image quality
- Repeat examination


## Common Causes of Errors

Including:

- Incorrect examination body part selection
- Incorrect protocol selection
- Misunderstanding of examination requirements


## Design Controls

The system should support:

- Clear examination information display
- Protocol templates
- Intelligent recommendations


## AI Assistance Principle

AI may:

- Recommend suitable protocols based on examination information
- Detect abnormal selections


The radiographer remains responsible for:

- Final protocol confirmation


---

# 4. Patient Positioning


## Purpose

Position the patient according to imaging requirements.


Patient positioning is one of the most important tasks in DR workflow.


## Potential Risks

Errors may result in:

- Insufficient anatomical coverage
- Incorrect projection angle
- Poor image quality
- Repeat exposure


## Influencing Factors

Including:

- Patient physical condition
- Patient cooperation ability
- Examination body part
- Imaging requirements


## Design Controls

The system may provide:

- Real-time visual assistance
- Human body recognition
- Positioning guidance
- Geometry feedback


## AI Assistance Principle

AI may:

- Analyze patient position
- Provide adjustment suggestions
- Identify potential positioning issues


AI should not:

- Replace the radiographer's final judgement


---

# 5. Exposure Parameter Confirmation


## Purpose

Confirm appropriate exposure conditions for the current patient and examination task.


## Potential Risks

Errors may result in:

- Insufficient image quality
- Inappropriate radiation dose
- Repeat exposure


## AI-assisted Parameter Recommendation


High-end DR systems may recommend exposure parameters based on:

- Examination protocol
- Anatomical region
- Patient characteristics
- Imaging requirements


Examples include:

- kV
- mAs
- Exposure combinations


## Design Controls

The system should:

- Clearly display recommended parameters
- Explain parameter status
- Allow radiographer adjustment


Design principle:

> AI recommends, radiographer confirms.


---

# 6. Exposure Authorization


## Purpose

Confirm whether X-ray exposure can be performed.


## Why It Is a Separate Critical Task


Correct exposure parameters:

≠

Permission to perform exposure.


Exposure authorization represents the final confirmation that:

- Patient information is correct
- Examination requirements are satisfied
- System status is ready


## Potential Risks

Including:

- Exposure on the wrong patient
- Exposure of the wrong body part
- Exposure before preparation is complete


## Design Controls

The system should clearly communicate:

- Preparation status
- Exposure status
- Current workflow stage


## AI Assistance Principle

AI may:

- Check conditions
- Provide abnormality alerts


AI should not:

- Automatically authorize exposure


Final responsibility remains with the radiographer.


---

# 7. Image Quality Evaluation


## Purpose

Confirm whether acquired images meet diagnostic requirements.


## Potential Risks

Errors may result in:

- Poor-quality images entering diagnostic workflow
- Reduced examination quality
- Repeat exposure


## AI Quality Control Capability


AI may perform immediate image quality analysis after exposure.


Analysis may include:

- Anatomical coverage
- Projection positioning
- Image quality
- Potential repeat exposure risks


## AI Quality Control Output


AI may:

- Identify potential issues
- Explain detected problems
- Provide improvement suggestions


Examples:

- Possible insufficient lung apex coverage
- Possible patient rotation affecting image quality
- Recommendation to confirm positioning


## Design Boundary


AI quality control results should be:

> Supporting information for decision-making


Not:

> Automatic examination judgement


AI should not:

- Automatically determine that an image must be repeated
- Automatically reject images
- Replace radiographer image quality judgement


The radiographer makes the final decision regarding image acceptance.


---

# 8. Equipment Operation Safety


## Purpose

Ensure safety during equipment adjustment, automated assistance, and system operation.


## Scope


This principle applies to different DR system types, including:

- Fixed DR systems
- Mobile DR systems
- Intelligent DR systems


It does not depend on a specific hardware implementation.


## Potential Risks

Including:

- Unclear equipment status
- Unpredictable automation behavior
- Failure to recognize abnormal conditions
- Unsafe patient or operator conditions


## Design Controls

The system should:

- Clearly display equipment status
- Provide operation feedback
- Provide abnormal condition alerts
- Maintain appropriate human control


## AI Assistance Principle

AI may:

- Predict potential risks
- Identify abnormal states


AI should not:

- Hide critical equipment information
- Replace safety confirmation


---

# 9. Critical Task Design Principles


For all critical tasks, DR system design should follow:


## 9.1 Information Visibility

Critical information should always be visible.


Users should understand:

- Current status
- Completed actions
- Required next steps


---

## 9.2 Error Prevention First

The goal is not only to help users recover from errors.

The priority is:

> Prevent errors before they occur.


---

## 9.3 Transparent Automation

Automation should be:

- Understandable
- Predictable
- Controllable


---

## 9.4 Clear Human-Machine Responsibility


AI:

- Supports decision-making


Radiographer:

- Makes final clinical confirmation

