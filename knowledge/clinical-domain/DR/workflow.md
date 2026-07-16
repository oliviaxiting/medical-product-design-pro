# DR Clinical Workflow


## Overview

Digital Radiography (DR) workflow is designed around a complete imaging examination process:

Examination Request → Examination Preparation → Patient Positioning → Exposure Acquisition → Image Quality Confirmation → Data Transmission


The workflow should reflect real clinical practice in radiology departments.

The design goal is to support:

- Patient safety
- Efficient examination workflow
- Accurate positioning
- Reduced repeat exposure
- High-quality diagnostic images


---

# 1. Standard DR Workflow

The standard workflow applies to routine outpatient and scheduled DR examinations.


## Workflow Overview


Examination Request

↓

Examination Part Registration & Protocol Selection

↓

Patient Identification

↓

Patient Positioning

↓

Exposure Preparation

↓

Exposure Acquisition

↓

AI Image Quality Analysis

↓

Image Quality Confirmation

↓

Data Transmission to PACS


---

# 1.1 Examination Request & Protocol Selection


## Purpose

Receive examination tasks and prepare the correct imaging protocol.


## Sources

- RIS/HIS system
- Hospital examination request


## Radiographer Tasks

The radiographer:

- Reviews examination information
- Confirms examination body part
- Selects appropriate imaging protocol


## Design Considerations

The system should support:

- Clear examination information display
- Protocol templates
- Reduced repetitive input
- Prevention of protocol selection errors


---

# 1.2 Patient Identification


## Purpose

Ensure the correct patient receives the correct examination.


## Required Information

- Patient name
- Patient ID
- Examination body part


## Safety Principle

Patient identification is a critical safety task.

The system should not hide or skip identity confirmation through automation.


---

# 1.3 Patient Positioning


## Purpose

Acquire the correct anatomical position for imaging.


Patient positioning is one of the most important tasks in DR workflow.


## Radiographer Considerations

The radiographer confirms:

- Patient posture
- Anatomical region
- Detector position
- X-ray tube position
- SID
- Beam alignment


## Advanced DR Assistance

High-end DR systems may support:

- Camera-based patient monitoring
- AI-assisted positioning guidance
- Automatic calculation of imaging geometry


Automatic positioning may calculate:

- Projection angle
- Detector position
- X-ray tube position
- SID
- Centering information


The system assists positioning, but the radiographer remains responsible for final confirmation.


---

# 1.4 Exposure Preparation & Acquisition


## Purpose

Confirm exposure conditions and complete image acquisition.


Before exposure, the system should provide:

- Patient information
- Examination protocol
- Positioning status
- Geometry status
- Exposure parameters


## AI-assisted Exposure Parameter Recommendation


High-end DR systems may recommend exposure parameters based on:

- Examination protocol
- Anatomical region
- Patient characteristics
- Imaging requirements


AI provides:

- Parameter recommendation
- Optimization suggestions


The radiographer:

- Reviews recommended parameters
- Evaluates suitability for the current patient
- Confirms exposure


## Safety Principle

AI assists decision-making.

The final exposure confirmation remains the responsibility of the radiographer.


AI should not:

- Automatically authorize exposure
- Hide critical exposure information


---

# 1.5 Exposure Acquisition


## Purpose

Complete X-ray image acquisition.


During acquisition, the system should clearly communicate:

- Exposure status
- System status
- Operation state


The user should always understand:

- What is happening
- Whether the system is ready
- What action is required


---

# 1.6 AI Image Quality Analysis


## Purpose

Provide immediate feedback after exposure.


AI quality analysis occurs immediately after image acquisition.


AI may analyze:

- Anatomical coverage
- Positioning accuracy
- Image quality
- Potential repeat exposure risks


AI provides:

- Problem detection
- Quality feedback
- Improvement suggestions


The radiographer makes the final decision regarding image acceptance or repeat acquisition.


---

# 1.7 Image Quality Confirmation and Data Transmission


## Purpose

Complete examination workflow.


The radiographer confirms:

- Image quality
- Examination completeness


Then:

- Images are transmitted to PACS
- Examination is completed


---

# 2. Emergency Trauma Workflow


Emergency workflow is not simply an accelerated version of the standard workflow.


Emergency patients may have:

- Trauma
- Limited mobility
- Reduced cooperation ability
- Incomplete patient information


However:

The radiographer completes the current patient's examination workflow before proceeding to the next patient.


---

# Emergency Workflow Overview


Emergency Patient ID Creation

↓

Examination Part and Protocol Selection

↓

Patient Positioning

↓

Exposure Preparation

↓

Exposure Acquisition

↓

AI Image Quality Analysis

↓

Image Quality Confirmation

↓

Data Transmission

↓

Patient Information Completion


---

# 2.1 Emergency Patient Information


Emergency examinations may use an emergency ID as a temporary patient identifier.


The system should support:

- Fast examination initiation
- Temporary patient registration


After examination:

- Complete patient information
- Update examination records


## Safety Principle

Emergency efficiency should not remove necessary patient identification and examination confirmation.


---

# 3. Special Patient Considerations


Special patient conditions influence workflow design but do not replace the standard workflow.


---

# 3.1 Elderly Patients


## Characteristics

- Reduced mobility
- Reduced vision
- Reduced hearing
- Longer preparation time


## Design Considerations

Support:

- Clear visual feedback
- Simple instructions
- Reduced cognitive workload


---

# 3.2 Mobility Impaired Patients


Including:

- Wheelchair patients
- Bedridden patients
- Patients with limited movement ability


## Design Considerations

Support:

- Reduced patient movement requirements
- Safe positioning assistance
- Clear safety information


---

# 3.3 Pediatric Patients


## Characteristics

- Limited cooperation ability
- Different body sizes
- Need for caregiver assistance


## Design Considerations

Support:

- Parent/caregiver presence
- Child-friendly guidance
- Prevention of unintended operation


---

# 4. Examination Complexity and Interaction Requirement


Not every DR examination requires the same level of interaction support.


The system should adapt interaction complexity according to examination requirements.


## Low Complexity Examination


Example:

Chest AP examination


Characteristics:

- Standard positioning
- High repeatability
- Experienced workflow


Possible workflow:

Console-based operation can complete the examination without PAD.


---

## Medium Complexity Examination


Examples:

- Chest lateral
- Special projections


May require:

- Additional positioning guidance
- More geometry information


---

## High Complexity Examination


Examples:

- Emergency trauma
- Pediatric examination
- Mobility impaired patients


May benefit from:

- Additional patient-side interaction
- PAD assistance
- Enhanced guidance


---

# 5. System Responsibility Model


## Console


Console is the primary operation center of the DR system.


Console provides complete examination capability:

## Patient Management

- RIS/HIS integration
- Patient registration
- Patient identification


## Examination Management

- Examination part selection
- Protocol selection


## Positioning Assistance

- Real-time camera preview
- AI positioning guidance
- Position adjustment feedback
- Geometry information


Example:

The system may provide guidance such as:

- Move slightly left
- Adjust patient position
- Confirm alignment


## Exposure Management

- Exposure parameter display
- AI parameter recommendation
- Exposure confirmation


## Image Management

- Image acquisition
- AI quality analysis
- Image review
- PACS transmission


---

# PAD


PAD is not a replacement for Console.


PAD is a scenario-based interaction extension.


PAD may support:

- Patient-side guidance
- Positioning assistance
- Device status feedback
- Teaching scenarios


PAD is especially useful for:

- Complex positioning
- Emergency examinations
- Mobility impaired patients
- Training scenarios


For simple examinations, such as chest AP, the complete examination can be performed through Console without PAD.


---

# 6. AI Assistance Principle


AI should:

- Recommend
- Detect
- Analyze
- Explain


AI supports:

- Positioning assistance
- Exposure parameter recommendation
- Image quality analysis
- Risk identification


AI should not:

- Replace radiographer judgement
- Automatically authorize exposure
- Hide critical information


The final clinical decision remains with the radiographer.
