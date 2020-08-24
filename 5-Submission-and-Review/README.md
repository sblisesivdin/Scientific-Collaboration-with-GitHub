# Submission and Review

Submission and Review of the prepared manuscript is the very important part of the process. To select a proper joural is one of the important things. For a multi-author study which is totally done remotely, one can ask the opinion of a senior researcher, otherwise a democtratic voting process will be the logical choice.

# Journal voting

For the voting, the most important thing will be to hide the votes of people from others. For this **corresponding author will take the responsibility of collecting votes and then announce**

Therefore, when the manuscript is finished, the following scheme which is simply a Borda Voting count (Saari, 1985) can be suggested to follow:

1. Corresponding author will announce a call for suggesting journal names. There must be a deadline for this process (1 week is more than enough).
2. For example, total of 7 journals are suggested by authors. All suggested journal names will be announced to authors by corresponding author like:

| No: | Journal Name | Author 1 | Author 2 | Author 3 |
| --- | ------------ | -------- | -------- | -------- |
| 1   | Journal 1    |          |          |          |
| 2   | Journal 2    |          |          |          |
| 3   | Journal 3    |          |          |          |
| 4   | Journal 4    |          |          |          |
| 5   | Journal 5    |          |          |          |
| 6   | Journal 6    |          |          |          |
| 7   | Journal 7    |          |          |          |

and **weighted** votes will be requested. For 7 journals, authors will give each journal a vote from 1 to 7 (each will be used once). At the end, corresponding author will use his/her vote.

3. After getting votes, corresponding author will announce the total votes:

| No: | Journal Name | Author 1 | Author 2 | Author 3 | TOTAL |
| --- | ------------ | -------- | -------- | -------- | ----- |
| 1   | Journal 1    |     7    |    6     |    7     |  20   |
| 2   | Journal 2    |     4    |    4     |    6     |  14   |
| 3   | Journal 3    |     3    |    2     |    4     |   9   |
| 4   | Journal 4    |     6    |    5     |    2     |  13   |
| 5   | Journal 5    |     1    |    1     |    3     |   5   |
| 6   | Journal 6    |     2    |    3     |    1     |   6   |
| 7   | Journal 7    |     5    |    7     |    5     |  17   |

Therefore, corresponding author will submit the manuscript firstly to Journal 1. If it will be rejected from Journal 1, then it will be submitted to Journal 7. Then (hopefully not) Journal2, 4, 3, 6 and lastly 5.

**NOTE:** Here, all authors have been accepted to have one vote. For a more technocratic way for voting, commit counts or line change counts can be used to determine weights of each vote.

## Submission and review

After determining the journal to submit, corresponding author can prepare the files for submission and put it in a new folder under here.

```
/5-Submission-and-Review
  1-1-Journal1-FirstSubmit-May2020
    manuscript.docx
    fig1.eps
    fig2.eps
    table1.docx
    cover_letter.docx
    ...
```

If a review request come from the journal, a second folder can be opened as:

```
/5-Submission-and-Review
  1-1-Journal1-FirstSubmit-May2020
    manuscript.docx
    fig1.eps
    fig2.eps
    table1.docx
    cover_letter.docx
    ...
  1-2-Journal1-MajorReview-Sep2020
    manuscript.docx
    manuscript_corrections.docx
    rebuttal_letter.md
    fig1.eps
    fig2_corrected.eps
    table1.docx
    cover_letter.docx
    ...
```

For our scenario, let's we had a bad day and our manuscript was rejected from Journal 1. We will submit it to Journal 7, as it was our second choice.

```
/5-Submission-and-Review
  1-1-Journal1-FirstSubmit-May2020
    manuscript.docx
    fig1.eps
    fig2.eps
    table1.docx
    cover_letter.docx
    ...
  1-2-Journal1-MajorReview-Sep2020
    manuscript.docx
    manuscript_corrections.docx
    rebuttal_letter.md
    fig1.eps
    fig2_corrected.eps
    table1.docx
    cover_letter.docx
    ...
  2-1-Journal7-FirstSubmit-Dec2020
    manuscript.docx
    fig1.eps
    fig2.eps
    table1.docx
    cover_letter.docx
    ...
```

So the process can be carried on like this.

Rebuttals can be written in MD files or again can be arranged as Google Docs, simple doc files, rtf files, anything can be tried. It is better to use GitHub as much as possible. However, cloud collaboration tools can also be used because of higher flexibity they offer (equation editor, review pane, including figures inside document etc...).


# References
* Saari, D.G., 1985. The Optimal Ranking Method in the Borda Count.

