 HR Presentation

# Constraints

## 20 minutes

## Quarto Doc Okay

# Structure

## 0. Introduce Self

### Education

#### 0.1. Engineering (Electronic)

##### What I learned

###### Not to be afraid of algebra

###### Ideal types, complexity

###### Signal processing

###### Technical pragmatism

###### Matlab, C/C++

###### That I didn't want to do this as a career

#### 0.2. Masters: Critical Theory (= Marxism + Money + Cognitive Dissonance)

##### What I learned

###### Social sciences aren't like other sciences

###### Social theories as faiths

#### 0.3. PhD: Sociology (Quantitative) + Geography (Human): Health and Labour market reform

##### Quant Sociology in a qual social science department

##### Learnt R here

###### Similarity with Matlab, C, C++ etc

###### Overcompensating: R scares economists

##### Lexis surfaces first discovered here

###### Motivating question: How did pension ages accidentally become generous?

###### Motivation question: is incapacity benefit/ESA a hidden early retirement benefit?

#### 0.4. Codeclan

##### 16 week software development

##### Python, Java, Javascript, HTML, CSS, SQL

##### Front End, Back End, Full Stack

##### Agile/Kanban

##### Test-driven development

##### Currently week 13 (of 16)

### Employment

#### Academic

##### Qualitative interviewer

##### Systematic reviewer

##### Health economist

##### Research fellow

###### Main role: Urban Segregation

###### Side: Demographic visualisation as applied to public health and related issues

* Comparative mortality (Scottish disadvantage)

* Segregation in driving/vehicle access

* Fertility (international)

* Criminology

* Cause-specific mortality

  + APC

  + Deaths of despair

#### Non-academic

##### NHS Health Scotland

###### Continuation of earlier health-related research

###### Causes of UK's stalling mortality

###### Covid

* Early to notice warning signs

##### Public Health Scotland

###### Vested 1 April 2020

###### Covid guidance cell

* Supporting SG led sectoral guidance

* Rapid (for public sector) turnarounds

* Implemented lean-agile approaches

###### Post-covid

* ???

* Middle-manager grade without middle-manager responsibilities

* ???

### Interests, preoccupations, personality and attributes

#### Lateral thinking

#### Holistic thinking

#### Spelling out logical conclusions/implications

#### Middle-ranged theorising

##### Not deductive or inductive, but abductive

##### Generative coupling of theory and evidence

#### Visualisation

##### Representing relationships

##### Seeing and understanding data

##### The Lexis Surface

#### Empiricism

##### Seeking verification and falsification

##### Hoping to be precise enough to be completely wrong

## 1. The Lexis Surface

### Is a map

### What is a map?

#### Mathematical sense

##### 1-1 translation process

##### (See also lambda functions, functional programming etc)

##### Grammar of Graphics

#### Common sense

##### Examples

###### Example

###### Example

###### Example

##### What's in common?

#### Mathematical treatment of the common sense

##### Show z as a function of x and y

##### z ~ f(x, y)

##### x, y are both continuous, and the same unit

### Is a map of time, just as standard maps are maps of space

#### Instead of latitude: time (t)

##### Or birth cohort

#### Instead of longitude: age (x)

#### Instead of elevation...

##### Number of deaths

##### Death rate

##### Log of death rate

##### Ratio between two populations

##### Log difference between two populations

##### Population size

##### Fertility rate

##### Cumulative fertility rate

##### Crime rate

### Examples

#### Standard LP

##### Contours

##### Colours

##### Elevation

#### Alternative LPs

##### d(mx)/d(t)

##### male-female

##### Scotland - rUK

#### Model-based LPs

##### Observed - Expected

## 2. NI Example

### Origins

#### Curiosity

#### Comparison between male and female young adult death rates

### Questions

#### When did the male comparative excess begin?

##### approx year?

##### Which age range?

### Inferences

#### An excess male young adult mortality began in early 1970s

#### Continued for many decades

#### Attenuated over time

#### Likely cause: 'The Troubles'

### Formalisation

#### Visual/intuitive impression of an 'excess' emerging for males

#### Excess compared to what?

##### Females

###### But there's (almost) always a female excess

##### Males before

###### But there's also a trend/drift towards (usually) improving mortality rates over time

#### Need to model the counterfactual

##### What WOULD have happened to male mortality rates if what had happened hadn't happened?

#### Defining 'what happened'

##### A force of mortality multiplier which began some time in the 1970s, was most keenly felt by older teens/young adults, and whose intensity fell over time

#### Approach taken

##### Counterfactual

###### Age-specific random-walk-with-drift

##### Treatment/Exposure

###### Time/age-varying mortality multiplier

###### interaction with age

###### exponential decay after initial/peak year

#### Results

##### Modelled compared with observed

##### Estimated excess deaths

##### Comparison with more studiously recorded estimates

### Conclusion

#### Exploratory analysis with Lexis surface

#### Informal model

#### Formalisation

#### Use of Lexis surface in assessing model

#### New insight (alas, as yet unpublished...)

## 3. Plotly/Shiny

### Grand Tours and Tomography

#### Lexis surfaces

##### Age schedules matter

##### Period schedules matter

##### Cohort schedules matter

#### Grand Tours

##### Select a point on the surface, get the three schedules

### When?

#### 2 1/2 week break before start of NHS job (was hoping for six weeks)

#### Three apps in 2 1/2 weeks

#### Written in a crazed fugue state... the opposite of maintainable code :(

### What?

#### Link to app

### How?

#### R -> Shiny -> Plotly

#### Hoverover and click-on events in main image, listened to and generative of schedule plots

## 4. R and Friends

### R and Python

#### Copy each others' homework

#### R: A programming language written by madmen (Engineers)

##### Using more than we can know

###### Back-level

* Fortran

* C

* C++

###### Front-end

* Javascript

* HTML

* CSS

##### Functional programming

###### Great

##### OOP

###### Weird and Wild

##### Testing/TDD

###### Doable

###### An Afterthought

##### Interrogative/exploratory
 
'REPL' as default

##### Tidyverse

###### A new dialect

###### R's Esperanto moment?

#### Python: Tech Software 'glue'?

### Truce or Entente Cordial?

#### RStudio -> Posit

#### RMarkdown -> Quarto

#### Reticulate

##### Code chunk blending

#### Shiny for Python

#### Also Dash (Plotly)

### The Pizza and Beer 'Rule'?

#### This event: exception to the 'rule'

#### Suggests the treaty above likely drawn on unequal terms

### Importance of pragmatism

#### If it works, it works

#### Whatever does the job

#### Language blending already more common than we realise
