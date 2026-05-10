# Aviation Accident Analysis
# Aviation Accident Analysis
**Project Overview**

This project analyzes aviation accident data from 1948–2023 to evaluate aircraft safety performance across manufacturers and airplane models. The analysis was conducted from the perspective of a consulting firm advising an airline/aircraft insurer interested in identifying aircraft associated with:

1. ower rates of total aircraft destruction,
2. lower likelihood of serious or fatal passenger injuries,
3. and operational factors associated with accident severity.

The project focuses exclusively on:

professionally manufactured airplanes,
and aircraft potentially still active today.

To reflect realistic aircraft operational lifespans, only accidents from 1983 onward were included in the final analysis.


**Business Problem**

The client seeks evidence-based recommendations regarding:

1. Which aircraft manufacturers and airplane models exhibit the strongest passenger safety outcomes.
2. Which aircraft demonstrate lower probabilities of total destruction during accidents.
3. Which operational or environmental factors are associated with increased accident severity.

The client also requested separate evaluations for:

1. smaller airplanes,
2. and larger passenger airplanes.

Aircraft were categorized using a passenger threshold of 20 occupants.

**Dataset**
The primary dataset contains information on:

aircraft manufacturers and models,
injury outcomes,
aircraft damage severity,
weather conditions,
flight phases,
engine types,
and operational characteristics.

**Data Cleaning and Preprocessing**

Several preprocessing steps were performed to improve data quality and analytical reliability.

*Key Cleaning Steps*
Standardized column naming conventions
Converted date columns to datetime format
Removed rows with critical missing values
Standardized manufacturer and model naming inconsistencies
Removed amateur-built aircraft
Filtered for airplane category only
Filtered accidents from 1983 onward
Removed sparse columns with excessive missing data
Applied minimum sample-size thresholds for statistical robustness

**Feature Engineering**

Several derived variables were created to support safety analysis.

total_occupants, serious_fatal_injury_fraction, fatality_rate, destroyed, plane_type, aircraft_size

**Exploratory Data Analysis (EDA)**

The project explored:

injury severity patterns,
aircraft destruction rates,
manufacturer-level safety performance,
airplane-model safety performance,
and operational factors associated with accident outcomes.


**Visualizations Included**

Bar plots
Violin plots
Strip plots
Distribution analyses
Comparative manufacturer safety charts
Airplane-type safety comparisons

**Key Findings**
*Manufacturer Safety*

Several manufacturers consistently demonstrated:

low serious/fatal injury fractions,
and low aircraft destruction rates.

Large commercial aircraft manufacturers generally exhibited:

lower injury severity,
lower variability,
and lower destruction rates

compared to smaller general aviation aircraft.

*Airplane Type Safety*

Specific airplane models often performed differently even within the same manufacturer, highlighting the importance of model-level analysis.

Some airplane types demonstrated:

consistently low injury fractions,
and stable accident outcome distributions.

*Operational Factors*

The analysis suggested that accident severity may be influenced by:

weather conditions,
phase of flight,
engine configuration,
and aircraft size.

Accidents occurring during certain flight phases and under adverse weather conditions tended to produce more severe outcomes.



