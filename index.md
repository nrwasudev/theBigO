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

<img src="/static/imgs/Histogram EX09.png" width="500">

The histogram shows that many students already report moderate to high levels of note-taking. This suggests that note-taking is already common in COMP110, so offering extra credit for notes may not dramatically change student behavior.

## Figure 2: Note-Taking and Understanding

<img src="static/imgs/EX09 Understanding.png" width="500">

This graph does not show a clear positive relationship between note-taking and understanding. In fact, understanding slightly decreases as note-taking increases before rising slightly again at the highest note-taking levels. One possible explanation is that students with more prior coding experience may not feel the need to take many notes but still understand the material well. Less experienced students may take more notes because they are trying harder to keep up, but they may still report lower understanding.

## Figure 3: Note-Taking and Office Hour Visits

<img src="static/imgs/EX09 oh_visits.png" width="500">

This graph also does not clearly support the original idea. Students who report taking more notes do not consistently report fewer office hour visits. Office hour visits increase up to a certain level of note-taking and then level off. This may again be influenced by prior experience, since newer students may both take more notes and seek more help.

## Conclusion

Overall, our analysis is inconclusive and does not clearly support offering extra credit specifically for handwritten notes. The data shows that note-taking is already common, and higher note-taking does not clearly align with higher understanding or fewer office hour visits.

A major limitation is that the analysis does not account for prior coding experience. Experienced coders may take fewer notes because they already know much of the material, while newer coders may take more notes because they are struggling. This could skew the relationship between note-taking and understanding.

The main downside of implementing this idea is that it could increase grading work for instructors and TAs without clearly improving student outcomes. It could also favor handwritten note-taking over other valid study methods, such as typed notes, practice problems, or coding examples.

In the future, COMP110 could collect more targeted data by comparing note-taking habits across students with different levels of prior coding experience. A better course improvement might focus on broader active learning strategies rather than only incentivizing handwritten notes.