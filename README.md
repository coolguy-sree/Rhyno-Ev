# Tutorial: Rhyno-Ev

The Rhyno-Ev project is a website designed to showcase their **electric scooters**.
It allows visitors to *browse available models*, view detailed technical *specifications* presented in clear tables, find *contact information*, and navigate the site easily using consistent navigation bars at the *top and bottom* of every page, all tied together with a *unified visual style*.


## Visual Overview

```mermaid
flowchart TD
    A0["Site Navigation
"]
    A1["Site Footer
"]
    A2["Base Page Structure
"]
    A3["Global Stylesheet
"]
    A4["Product Detail Page Template
"]
    A5["Product Listing
"]
    A6["Specification Tables
"]
    A7["Contact Information Block
"]
    A2 -- "Includes" --> A0
    A2 -- "Includes" --> A1
    A2 -- "Applies Styles" --> A3
    A5 -- "Uses Structure" --> A2
    A5 -- "Links to Details" --> A4
    A4 -- "Includes" --> A6
    A2 -- "Includes Content" --> A7
    A6 -- "Styled by" --> A3
```

