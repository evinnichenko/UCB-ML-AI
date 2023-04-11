# UCB-ML-Practical-5.1

Repo containing my take on Practical Assignment 5.1 from UCB ML/AI course. See Readme for short report, or the attached `Notebook.ipynb` file for all the details.

## Short report on findings

### Part 1: cleaning data

For data cleaning, I did two things: removed the "car" column since it was 99.1% filled with `NaN` and wasn't used anywhere, and filled the 794 `NaN` values in several other columns with 0s, since it was likely that they were meant as such. In case they were not, I redid the notebook in the background with dropping affected empty rows, and the results didn't change much due to low number of affected rows.

### Part 2: Bar coupons

What I noriced is that people who accept bar coupons are usually the ones who go there at least once a month, don't have a lot of income, and belong to younger population.

### Part 3: Independent study (takeout)

Here distribution is surprisingly even. The only notable trends I managed to find are that:
* There is a surprising gap between people who never order for takeout (who also accept the most coupons) and people who do so rarely
* Obvious (and universal) trend for long-term (1 day) coupons
* Interesting 10% peak in acceptance for widowed people

Everything else is surprisingly stable, acceptance rates deviating within 2-3% for each category.
