---
# Do not edit the text between these lines!
layout: default
---
<img src="static/imgs/logo.png" width="250">

# Notes on Notes

## Summary of Analysis

For this project, we analyzed whether COMP110 should offer extra credit for students who submit handwritten notes at the end of the semester. The goal of this idea was to encourage active listening, improve student understanding, and potentially reduce overall TA workload by lowering the number of office hour visits students need.

To test this idea, we used survey data from two COMP110 survey files. We combined both datasets, selected the columns most relevant to our idea, and analyzed three variables:

- `own_notes`: how often students keep their own notes
- `understanding`: how well students feel they understand course material
- `oh_visits`: how often students visit office hours for help

We created three visualizations: a histogram of note-taking habits, a line graph comparing note-taking with understanding, and a line graph comparing note-taking with office hour visits.

## Figure 1: Distribution of Student Note-Taking

<img src="static/imgs/Histogram EX09.png" width="500">

The histogram shows that many students already report moderate to high levels of note-taking. This suggests that note-taking is already common in COMP110, so offering extra credit for notes may not dramatically change student behavior.

## Figure 2: Note-Taking and Understanding

<img src="static/imgs/EX09 Understanding.png" width="500">

This graph does not show a clear positive relationship between note-taking and understanding. In fact, understanding slightly decreases as note-taking increases before rising slightly again at the highest note-taking levels. One possible explanation is that students with more prior coding experience may not feel the need to take many notes but still understand the material well. Less experienced students may take more notes because they are trying harder to keep up, but they may still report lower understanding.

## Figure 3: Note-Taking and Office Hour Visits

<img src="static/imgs/EX09 oh_visits.png" width="500">

This graph also does not clearly support the original idea. Students who report taking more notes do not consistently report fewer office hour visits. Office hour visits increase up to a certain level of note-taking and then level off. This may again be influenced by prior experience, since newer students may both take more notes and seek more help.

## Conclusion

Our analysis, bolstered by our three figures, was created to determine whether offering extra credit for handwritten notes would improve student understanding and engagement and reduce reliance on office hours and TAs. Based on the data, the results are inconclusive and do not clearly support the original idea.

The histogram of own_notes shows that many students already report moderate to high levels of note-taking, suggesting that note-taking is already a frequent behavior in the course. This indicates that an extra credit incentive may have a limited impact, since a large portion of students are already doing so.

The relationship between own_notes and understanding does not show a clear positive trend. In fact, understanding appears to slightly decrease as note-taking increases, then takes a small climb toward the upper bound. However, this result is likely influenced by the fact that many students in COMP110 may already have prior coding experience. More experienced students may not feel the need to take notes because they are already familiar with the material, yet they still report high levels of understanding. At the same time, less experienced students may take more notes as they try to keep up with new concepts, but still report lower understanding. This dynamic can create a misleading negative relationship between note-taking and understanding.

A similar pattern appears when comparing own_notes with office hour visits. Students who report higher note-taking do not consistently visit office hours less often. It is a single peaked dataset with the median around 4/7 for own_notes. This could again be explained by experience level, where newer students both take more notes and seek more help, while experienced students do neither as frequently.

Overall, the data does not provide strong evidence that incentivizing handwritten notes alone would improve learning outcomes or reduce TA workload. A potential downside of this idea is that it could increase grading responsibilities for instructors or TAs without producing meaningful improvements. We also realised it could in theory favor one study method over others.

To improve this analysis, future data collection should take prior experience into account, such as separating students based on their coding background. This would allow for a more accurate comparison of how note-taking impacts learning for beginners versus experienced students. 

In conclusion, while note-taking is an important study strategy, the current data suggests that incentivizing handwritten notes may not be the most effective way to improve student outcomes. A more targeted approach that accounts for differences in student experience would likely produce more meaningful improvements.