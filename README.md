# Kickstarting with Excel

## Overview of Project

Up-and-coming playwright Louise, following the near-success in funding her earlier play FEVER via Kickstarter, approached "the team" for further data analysis. Curious into how similar campaigns fared in relation to launch dates and funding goals, "the team" analyzed Kickstarter data in Excel to provide Louise with a written report and visualization to help her launch her next project.

### Purpose

To utilize Kickstarter data imported into Excel for filtering, charting and graph generation to meet client's (Louise) request. Written report to follow.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Chart01](/resources/Theater_Outcomes_vs_Launch.png)

In analyzing Theater(Plays) Outcomes Based on Launch Date, it is fairly apparent that initializing funding in the May-June corridor yields a 2:1 ratio in successfully meeting Kickstarter goals vs failing. Following this "peak", there is a steady decline until year's end with December approaching a 1:1 ratio.

### Analysis of Outcomes Based on Goals

![Chart02](/resources/Outcomes_vs_Goals.png)

Analysis of Outcome Based on Funding Goals shows a near 80% success rate of meeting funding for small projects that request less than $1000. Backing requests beyond this value yield a gradual decline in success, with $15,000 to $19,999 being an intersection point. Successful outcome percentages slide further downward below 50% beyond this intersection at higher Goal values; however, inflection occurs in the $30,000 to $34,999 range leading to a plateau of near 66% success from $35,000 to $49,000. Higher goals beyond this range show a drastic drop into a minimal to zero range.

### Challenges and Difficulties Encountered

A challenge was encountered in grouping dates for Analysis of Outcomes Based on Launch Date. Even after conversion from Kickstarter's UNIX based date to a human readable one, placing these dates into a PivotChart yielded a messy table of '1's. The Excel support link on [Grouping Data](https://support.microsoft.com/en-us/office/group-or-ungroup-data-in-a-pivottable-c9d1ddd0-6580-47d1-82bc-c84a5a340725?ui=en-us&rs=en-us&ad=us) provided a quick solution in reducing and collating data into months. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1.) Setting your launch date shows to be very seasonal (northern hemisphere). The highest peak in May-June seems imply an excitement for theater goers to get out in the warmer weather and see a play.

2.) The drastic drop in success for the end of the year (December) is most likely attributed to holiday spending, where disposable income is now diverted away from entertainment.

- What can you conclude about the Outcomes based on Goals?

1.) Low goals under $1000 yielded the highest success ratio, implying a bevy of theater patrons who appreciate small budget productions. However a second "sweet-spot" of success appears in the $35,000-$44,999 range, giving credence to more robust plays, but definitely not "over-the-top" productions where positive outcomes drop to near zero.

- What are some limitations of this dataset?

1.) Number of page views per project might give a glimpse into how "well" a project is being promoted or marketed.

- What are some other possible tables and/or graphs that we could create?

1.) Looking at an overall trend by Year could help in spotting a rise or fall of a theater-going fad. Examining by Country could also give insight into who likes viewing plays the most, or at least funds them.