# Hospital Management System with Machine Learning Integration

**Undergraduate Computer Science project | Valley View University, Ghana | 2021–2022**  
**Author:** Victor Ashun

## Overview

A final-year BSc Computer Science project exploring a web-based hospital management system alongside an experimental machine-learning component for chest X-ray classification.

The project addressed hospital workflows such as patient records and appointments, while investigating how an ML-assisted prediction workflow could be integrated into a clinical information system. It was an **academic prototype, not a production healthcare product or medical diagnostic device**.

## Technologies

| Area | Technologies used or documented |
| --- | --- |
| Web application | C#, ASP.NET Core MVC (.NET 5) |
| Persistence | Microsoft SQL Server, Entity Framework Core |
| Authentication and access | ASP.NET Identity, role-based access |
| Machine-learning experimentation | ML.NET, AutoML |
| Development | Visual Studio |

## Application component

The undergraduate system included or documented workflows for:

- Patient registration and record management
- Appointment handling and hospital administration
- User sign-in and role-based access
- Database-backed operations and record retrieval
- Integration concepts for storing and presenting image-classification predictions

The dissertation contains requirements analysis, design diagrams, implementation examples, testing and system documentation.

## Machine-learning research component

The dissertation describes experiments in using **ML.NET AutoML to classify chest X-rays for pneumonia detection**. It discusses dataset selection, training, prediction and integration with the hospital application.

A final two-class experiment reported approximately **97% classification accuracy** in the dissertation. This is a historical, project-reported experimental result, **not independently verified clinical performance**. It should not be interpreted as evidence of diagnostic reliability or suitability for deployment in a healthcare setting.

### Availability of implementation

The original development repository is kept private. Its currently available source-code snapshot **does not include the complete ML.NET implementation or trained model files**. The machine-learning work described here is supported by the undergraduate dissertation, which contains relevant methodology and sample integration code.

This public repository is **a project showcase and documentation summary**, not a complete runnable source-code release or a live demo.

## Architecture at a glance

```text
Web interface / MVC views
          |
 ASP.NET Core MVC application
          |
 Authentication and role-based access
          |
 Application logic / Entity Framework Core
          |
     SQL Server database

Separately documented research workflow:
Chest X-ray dataset -> ML.NET AutoML experiments -> prediction -> proposed application integration
```

*Conceptual summary of the components documented in the thesis; not a deployment diagram.*

## Skills demonstrated

- Requirements analysis and full-stack application development
- Relational database modelling and data access
- Identity, authentication and role-based access principles
- System architecture and technical documentation
- ML experimentation, dataset evaluation and integration planning
- Testing and reporting the limitations of an academic prototype

## Documentation and future showcase materials

The undergraduate dissertation is the primary record of the project. Selected system diagrams, **redacted** screenshots and short technical explanations may be published here after checking that they contain no patient information, personal data, credentials or other sensitive material.

## Academic context

Completed for the BSc Computer Science programme at **Valley View University, Ghana**, under the supervision of **Mr Francis Ronky Doh**.

---

**Disclaimer:** This was an educational research project. It is not a clinical diagnostic system, and its reported classification result has not been independently or clinically validated.
