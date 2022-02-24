# Krafthack2022
This is a repo to kickstart Sopra Steria and friends' effort in the Krafthack2022 March 7-8th.

## Background information
This is copied/pasted from the Organizers page, but kept for convenience. 

Norway has been called the “Green Battery” of Europe, with 90% of Norway’s total power production coming from hydropower.

Of the nearly 1 700 hydropower plants in production, one plant stands out – Kvilldal. Norway’s largest plant, it is a marvel of nature and engineering, with four turbines taking over 500 meters of water head and converting it to electrical energy. The plant is located 1.5 km inside the mountain, making access (physical and internet!) and monitoring uniquely complex.

In this hackathon, we invite innovative thinkers to put their expertise to the test and share how they would employ data science to support monitoring of complex equipment.

### About the case

 Water flow dynamics are challenging, particularly when you need to regulate 538 meters of water and simultaneously consider the needs from the power market.

Kvilldal is equipped with four Francis turbines, which are fundamental to generating over 3 000 GWh of energy every single year. These turbines are subject to an ever-changing environment with complex load requirements, as they need to start, stop, and adjust to varying water conditions. These changing loads result in stresses on the structure, and it is vital to monitor the turbine to minimize forces on the turbine components and maintain a high level of safety.

### About the dataset

 In this challenge, Statkraft will share a real data set collected from one of the turbines installed in the Kvilldal plant. The turbine is equipped with multiple sensors, including strain gauges, with supporting operational data (power, speed...).

The dataset will be provided in a table format and made available as CSV files (or other tabular equivalent). The dataset will be pre-processed to accommodate for known data errors (e.g. lost connectivity, sensor reliability) to allow attendees to focus on the modeling rather than data preparation.

Key words:

* Flow dynamics
* Francis turbine – 30 tons, 4,2 meters round with a capacity of 320 MW
* Sensor data – pressure in waterway, strain gauges, temperatures and vibration data for the turbine environment
* Load conditions – power, current, guide vane opening and rotational speed


## Hackathon Expectations

### Overview

In this hackathon, we will review a use case of failure detection in a hydropower facility. The goal is to use sensor data to identify and detect deviations, such as bolt fatigue. You will be training models on historic data, and make predictions on a new stream.

### Outcome

This is an opportunity to familiarize yourself with end-to-end unsupervised machine learning on a real data set.

### Evaluation

Participants will be challenged to present potential solutions to monitoring and detecting deviations from normal behaviour. The solutions, including algorithms and source code, will be shared with the judging committee for evaluation. Teams can use libraries, frameworks, or open-source code in their projects, but the usage of third-party commercial tools is discouraged.

The intent of the hackathon is to further learning across the industry. Hackathon teams should expect that solutions will be shared either partially or in their entirety. All teams should consider this when submitting their solutions.

### Judging criteria

The solutions will be judged according to model accuracy, design creativity, and real-world application. The judging committee will assess the following:

* Innovation & Cleverness - How technically impressive was the solution?

* Design – Did the team consider the user experience of the solution?

* Model accuracy – How well does the solution work on a new data set?

The jury will consist of experts from both discipline experts and data science.
