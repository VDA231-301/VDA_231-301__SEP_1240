![SEP 1240](https://github.com/user-attachments/assets/b21e1412-e7df-4388-a324-79cb23a7d63b)

# SEP 1240 – Mechanical Material Test Results
## JSON Subschema according to VDA 231‑301

## Purpose and Scope

This repository provides a **specific JSON subschema for the digital exchange of test results according to SEP 1240**,  
*“Testing and Documentation Guideline for the Experimental Determination of Mechanical Properties of Steel Sheets for CAE Calculations”*.

The subschema defines a **machine‑readable representation of experimentally determined mechanical material properties** and supports the standardized, transparent, and interoperable exchange of test results between laboratories, material suppliers, OEMs, and engineering systems.

It is based on the **VDA 231‑301 recommendation** and represents a specialized extension of the generic VDA 231‑301 JSON schema.

---

## Position within VDA 231‑301

Within the VDA 231‑301 ecosystem:
- the **generic schema** defines the common structure for digital material test reports,
- this **SEP 1240 subschema** specifies the data elements required to represent mechanical test results generated according to SEP 1240.

The subschema enables consistent digital transfer of mechanical material data and supports the reuse of experimentally determined properties in downstream engineering and simulation workflows.

---

## Relation to the SEP 1240 Test Guideline

SEP 1240 defines **experimental test methods and documentation requirements** for determining mechanical material properties, particularly for use in **CAE and simulation contexts**.

⚠️ **Important clarification:**
- This repository **does not describe the test procedures themselves**.
- It does **not define material models, parameter fitting, simulation methods, or result interpretation**.
- It provides a **technical data structure only** for representing *test results* obtained according to SEP 1240 in a digital format.

The authoritative description of the SEP 1240 guideline is published exclusively by the responsible organization and is available via the official publication channels.

---

## Documentation of Test Series and Detailed Measured Values

The subschema specifies the **format in which data from test series shall be documented**.  
This includes, for example, the structured mapping of **individual measured values**, such as data points derived from **stress–strain curves**.

By enabling the digital representation of detailed test series data, the subschema supports a level of transparency and data depth that typically goes beyond classical certificate‑based documentation.  
It can therefore be used as a **supplement to conventional documentation**, such as inspection certificates according to **EN 10204 (e.g. 3.1)**, when such documents do not provide sufficient detail for engineering analyses, simulation, or systematic data reuse.

---

## Typical Use Cases

The SEP 1240 subschema supports use cases such as:
- digital exchange of mechanical test results between laboratories and OEMs
- structured handover of material test data to CAE and simulation environments
- traceable documentation of experimentally determined material properties
- integration of detailed test series data into material databases and engineering IT systems

The subschema improves **data consistency, automation, and reproducibility** across system boundaries.

---

## Applicability Beyond the Automotive Industry

Although SEP 1240 originates from the automotive context, the subschema is **not limited to automotive applications**.

Any industry that relies on:
- experimentally determined mechanical material properties,
- digital material data management,
- or simulation‑driven product development

can benefit from a standardized, machine‑readable representation of mechanical test results, for example:
- mechanical and plant engineering
- steel and metal processing industries
- industrial equipment manufacturing
- research and development environments

---

## Example Files

This repository contains example files illustrating the usage of the subschema:
- JSON examples representing SEP 1240 test results
- the corresponding JSON Schema definition

These examples are provided for **illustration and implementation support only**.

---

## Important Note

> [!IMPORTANT]
> This subschema provides **structured mechanical test result data only**.  
> It does **not** perform material evaluation, suitability assessments,
> simulation validation, or approval decisions.
> Such decisions remain the responsibility of the applicable engineering,
> quality, and release processes.

---

## License and Contribution

The VDA 231‑301 JSON schemas, including this SEP 1240 subschema, are released under the **MIT License**, allowing free use, modification, and distribution.

Contributions are welcome.  
Any changes intended to become part of the official VDA recommendation must follow the formal VDA committee and release process.
