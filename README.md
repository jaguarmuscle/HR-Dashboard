# HR-Dashboard
This project presents an **HR Insights Dashboard** developed using **Tableau Public**, focusing on visualizing and analyzing employee lifecycle metrics — primarily **hires** and **terminations**. The dashboard allows for deep insights into workforce trends and supports data-driven HR decision-making.




## 📊 Overview

# HR Dashboard - Tableau Public

## 🧰 Tools Used

- **Tableau Public**: For data visualization and dashboard creation
- **Excel / CSV**: Dummy HR data for employee records

## 📁 Data Description

The dataset used in this dashboard includes dummy records of employees with the following attributes:

- Employee ID
- Hire Date
- Termination Date
- Gender
- Age
- Age Group
- Education Level
- State
- Country
- Salary

## 📌 Key Features

The dashboard is interactive and enables stakeholders to explore employee data across several dimensions. It includes the following drill-down capabilities:

- 📅 **Hired vs Terminated Employees**: Timeline visualizations to track employee onboarding and attrition.
- 👤 **Demographics Breakdown**:
  - By **Age** and **Age Group**
  - By **Gender**
  - By **Education Level**
- 🌍 **Geographic Distribution**:
  - State-wise and Country-wise views of employee counts
- 💰 **Salary Analysis**:
  - Comparative view of salary distribution against age and age groups

## 🔍 Insights & Findings

From the dashboard visualizations, the following insights were observed:

- 📈 **Hiring Trends**: A noticeable increase in hiring in the age range of **25–35**, especially among individuals with a **Bachelor's degree**.
- ❌ **Termination Rates**: Higher termination rates were observed in specific states, indicating possible regional workforce challenges.
- 🧑‍🤝‍🧑 **Gender Distribution**: A fairly balanced distribution across genders with slightly more hires among males in technical roles.
- 💵 **Salary vs Age**: Salary tends to increase with age, with notable growth in the **35–50** age group, indicating retention of experienced staff.
- 🌐 **Geographical Insight**: States with metro cities show higher hiring and salary ranges compared to rural counterparts.

## 🔗 Dashboard Link

👉 [**Click here to view the live HR Dashboard on Tableau Public**](https://public.tableau.com/views/HRDashboard_17459219512970/HRSummary?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## 🌐 Embed Preview

You can also embed the dashboard using the code snippet below (ideal for blogs or websites):

```html
<div class='tableauPlaceholder' id='viz1745922359034' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='HR Summary ' src='https://public.tableau.com/static/images/HR/HRDashboard_17459219512970/HRSummary/1_rss.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='HRDashboard_17459219512970/HRSummary' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/HR/HRDashboard_17459219512970/HRSummary/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-GB' />
  </object>
</div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1745922359034');
  var vizElement = divElement.getElementsByTagName('object')[0];
  if (divElement.offsetWidth > 800) {
    vizElement.style.width='1400px';vizElement.style.height='827px';
  } else if (divElement.offsetWidth > 500) {
    vizElement.style.width='1400px';vizElement.style.height='827px';
  } else {
    vizElement.style.width='100%';vizElement.style.height='4077px';
  }
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
