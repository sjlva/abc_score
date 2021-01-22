---
# An instance of the Blank widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 15

title: Info
subtitle:

design:
  columns: "1"
  background:
    image: headers/bubbles-wide.jpg
    image_darken: 0.6
    image_parallax: true
    image_position: center
    image_size: cover
    text_color_light: true
  spacing:
    padding: ["20px", "0", "20px", "0"]
---

{{% alert note %}}
**When to use?**

At admission in the emergency department, to stratify the in-hospital mortality risk of patients with COVID-19 
{{% /alert %}}

{{% alert note %}}
**How was it developed and validated?**

Based in a cohort of xxx patients from xx hospitals, from xx cities in Brazil, following strict methodological criteria (TRIPOD checklist and PROBAST). 
{{% /alert %}}

{{% alert note %}}
 **Why to use?**

   + It is easily calculated at bedside at admission.
   + It identifies four categories at increasing risk of death with a high level of accuracy, which outperformed other existing scores.
  + It may help healthcare practitioners to better identify patients with higher risk of mortality, to inform early interventions and the need of repetitive assessments to reduce the risk of death.
{{% /alert %}}

{{% alert note %}}
 **How it should be used?**

Only inhospital patients, through the use of variables easily accessible at admission.

{{% /alert %}}

{{% alert note %}}

**How it should not be used?**

  + It should not be considered a medical device.
  + It must not be interpreted as patients from low risk group may be discharged for home treatment.
  + It was validated in a cohort of Brazilian patients, and it should not be adopted for routine clinical use in other settings until it has been appropriately externally validated in those settings.
    
{{% /alert %}}

{{% alert %}}
||Variable|ABC2-SPO2 Score|
|--|--|--|
|**A**| **A**ge (years)||
|| <60| 0 |
|| 60 - 69| 1 |
|| 70 - 79| 3 |
|| >= 80| 5 |
|**B**|**B**lood urea nitrogen (mg/dL)* | |
|| < 42| 0 |
|| >= 42| 3 |
|**C2**|**C**omorbidities | |
|| 0 - 1| 0 |
|| >= 2| 1 |
||**C** reactive protein (mg/L)| |
|| < 100| 0 |
|| >= 100| 1 |
|**S**|**S**F ratio (%)|
||> 315|0|
||235.1 - 315.0|1|
||150.1 - 235 |3|
||<= 150|6|
|**P**|**P**latelet count (x109/L)||
||> 150|0|
||100 - 150|1|
||< 100|2|
|**H**|**H**earth rate (bpm)||
||<= 90|0|
||91 - 30|1|
||>= 131|2|

{{% /alert %}}