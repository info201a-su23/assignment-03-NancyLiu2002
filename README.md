# A2: U.S. COVID Trends

## Overview
In many ways, we have come to understand the gravity and trends in the COVID-19 pandemic through data. Regardless of media source, people are consuming more epidemiological information than ever, primarily through reported figures, charts, and maps.

This assignment is your opportunity to work directly with the same data used by the [New York Times](https://github.com/nytimes/covid-19-data/). While the analysis is guided through a series of questions, it is your opportunity to use programming skills to ask more detailed questions about the pandemic.

## Getting Started
You should start this assignment by opening up the `analysis.R` script. The script will guide you through an initial analysis of the data.

* **Coding prompts.** Complete the coding prompts in `analysis.R`. You MUST use the `dplyr` package.

* **Reflection prompts.** Throughout `analysis.R`, there are prompts labeled `"Reflection"`. Please write at least 1-3 sentences for each of these prompts below in this `README.md` file. As appropriate, provide evidence, give justification for your opinions, or genuinely reflect on your views. Please strive for concise, clear, and interesting writing.

## Reflection 1
Before actually calculating the total number of COVID cases and deaths, record your guesses for the following questions.

Guess: How many total COVID cases do you think there have been in the U.S.?

I think there have been one million COVID cases in the U.S.

Guess: How many total COVID-related deaths do you think there have been in the U.S.?

I think there have been ten thousands COVID-related deaths in the U.S.

Guess: Which state do you think has the highest number of COVID cases, and which state do you think has the lowest?

I think New York has highest number of COVID cases and Alaska has the lowest number of COVID cases.

## Reflection 2
Did the number of COVID cases and deaths surprise you? Why or why not? What about the states with the highest and lowest number of cases? How did your guesses line up with the actual results? Answer in at least 1-3 sentences

I was completely surprised by the number of COVID cases and deaths because the value is much higher than my prediction, which also enhanced my worries about the situation of public health. The state with the highest number of cases is California, which is considerable due to its large population. For the state with the lowest number of cases, I didn't have an overall understanding of different U.S states.

## Reflection 3
Which county has the highest number of cases in the state of Washington, and does it surprise you? Why or why not? (You may need to google this county to learn about it) Answer at least in 1-3 sentences

King county has the highest number of cases in the state of Washington. And, this result does not surprised me a lot since I already know the it is the largest county with great population.

## Reflection 4
Why are there so many observations (counties) in the variable `lowest_deaths_in_each_state`? That is, wouldn't you expect the number to be around 50? Why is the number greater than 50? Answer in at least 1-3 sentences

The variable `lowest_deaths_in_each_state` selects the county with lowest number of COVID-related deaths in each states. The number greater than 50 might be caused by multiple counties having the exact same lowest number of COVID-related death, which can lead to multiple observations.  

## Reflection 5
What do you think about the number and scale of the inconsistencies in the data? Does the fact that there are inconsistencies mean that people should not use this data? Why or why not? Answer in at least 1-3 sentences

It's no surprisingly to have the number and scale of the inconsistencies because there are actually a very large scale to collect the COVID-related data from counties, states to the whole country. However, I don't think people should give up using this data. Compared with the large size of the data, the scale of the inconsistencies would not affect a lot for people to see the overall trends of COVID-19.

## Reflection 6
Why were you interested in this particular question? Were you able to answer your question with code? What did you learn? Answer in at least 1-3 sentences

The question I interested in with is the median number of COVID cases in the U.S. by the most recent time. Unlike the mean (average) value that can be affected the extreme high or low values, the median can provide me a clear insight on the central tendency of the typical number of COVID cases recently.

## Reflection 7
What, if anything, made you curious about this COVID analysis? What, if anything, surprised you? What might you do the same or differently on your next data wrangling project? Answer in at least 1-3 sentences

I was curious about the widespread of COVID-19 in different states of the U.S. It is very surprising to see horrible speed of how this virus changed by the time and affected every corner of the country. In the next data wrangling project, I am looking forward to manipulate the provided data by using different functions and trying to see other trends of the Covid cases in one specific location or time. 
