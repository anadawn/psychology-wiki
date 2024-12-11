# Definition of Parametric and Non-Parametric Statistics
Statistics is an Independent branch and its use is highly prevalent in all the fields of knowledge. Many methods and techniques are used in
statistics. These have been grouped under `parametric` and `non-parametric statistics`.

> *Statistical tests which are not based on a normal distribution of data or on any other assumption are also known as `distribution-free tests`
> and the data are generally ranked or grouped. Examples include the `chi-square test` and `Spearman’s rank correlation coefficient`.*

The first meaning of non-parametric covers techniques that do not rely on data belonging to any particular distribution. These include, among others:

- **Distribution free methods:** This means that there are no assumptions that the data have been drawn from a normally distributed population.
This consists of `non-parametric statistical models`, `inference` and `statistical tests`.

- **Non-parametric statistics:** In this the statistics is based on the ranks of observations and do not depend on any distribution of the population.

- **No assumption of a structure of a model:**  In non-parametric statistics, the techniques  do not assume that the structure of a model is fixed.
In this, the individual variables are typically assumed to belong to `parametric distributions`, and assumptions about the types of connections
among variables are also made. These techniques include, among others:

    - Non-parametric regression
    - Non-parametric hierarchical Bayesian models.

    > *In `non-parametric regression`, the structure of the relationship is treated non- parametrically.*

    > *In regard to the `Bayesian models`, these are based on the `Dirichlet process`, which allows the number of latent variables to grow as
    > necessary to fit the data.  In this the individual variables however  follow `parametric distributions` and even the process controlling the
    > rate of growth of latent variables follows a `parametric distribution`.*

- The assumptions of a `classical` or `standard tests` are not applied to `non-parametric tests`.

## Parametric tests
Parametric tests normally involve data expressed in absolute numbers or values rather than ranks.

> *An example is `The Student’s t-test`.*

The parametric statistical test operates  under certain conditions.  Since these conditions are not ordinarily tested,  they are assumed to
hold valid. The meaningfulness of the results of a parametric test depends on the validity of the assumption. Proper interpretation of parametric
test based on normal distribution also assumes that the scene being analysed results from measurement in at least an interval scale.

> *Let us try to understand the term population.  **Population refers to the  entire group of people  which a researcher intends to understand in
> regard to a phenomenon.***

The study is generally conducted on a sample of the  said population and the obtained results are then applied to the larger population from
which the sample was selected. Tests like `t`, `z`, and `F` are called `parametrical statistical tests`.

- **T-tests:** A T-test is used to determine if the scores of two groups differ on a single variable. A t-test is designed to test for the
differences in mean scores.

    > *For instance, you could use t-test to determine whether writing ability differs among students in two classrooms.**

It may be mentioned here that the parametric tests, namely, `t-test` and `F-test`,  are considered to be quite robust and are appropriate even when
some assumptions are not met. Parametric tests are useful as these tests are most powerful for testing the significance or trustworthiness of the
computed sample statistics.

However, their use is based upon certain assumptions. These assumptions are based on the nature of the population distribution and on the way the
type of scale is used to quantify the data measures. Let us try to understand what is a scale and its types.

There  are four types of scales used in measurement:
- Nominal scale
- Ordinal scale
- Interval scale
- Ratio scale.

- **Nominal scale:** deals with nominal data or classified data such as for example the population divided into males and females.
There is no ordering of the data in that it has no meaning when we say male > female.  These data are also given arbitrary labels
such as `m / f`  and `1 /10` .  These are also called as `categorical scale` , that is these are scales  with values that are in terms of categories
`(i.e. they are names rather than numbers)`.

- **Ordinal scale:** deals with interval data.  These are in certain order but the differences between values are not important.

    > *For example, degree of satisfaction ranging in a 5 point scale of 1 to 5, with 1 indicating least satisfaction and 5 indicating high
    > satisfaction.*

- **Interval scale:** deals with ordered data with interval.  This is a constant scale but has no natural zero.  Differences do make sense .
    > *Example of this kind of data includes for instance temperature in Centigrade or Fahrenheit. The dates in a calendar.  Interval scale
    >  possesses two out of three important requirements of a good measurement scale, that is,  magnitude and equal intervals but lacks the real
    > or absolute zero point.*

- **Ratio scale:** deals with ordered, constant scale with a natural zero.
  > *Example of this type of data include for instance:*
  > - *Height*
  > - *Age*
  > - *Weight*
  > - *Length etc.*

The sample with small number of items are treated with non-parametric statistics because of the absence of normal distribution

> *e.g. if our sample size is 30 or less; (N ≤30). It can be used even for nominal data along with the ordinal data.*

A non-parametric statistical test is based on model that specifies only very general conditions and none regarding the specific form of the
distribution from which the sample was drawn. Certain assumptions are associated with most non-parametric statistical tests, namely that the
observation are independent, perhaps that variable under study had underlying continuity, but these assumptions are fewer and weaker than those
associated with parametric tests. More over as we shall see, non-parametric procedures often test different hypotheses about population than do
parametric procedures.

Finally, unlike parametric tests, there are non-parametric procedures that may be applied appropriately to data measured in an ordinal scale,
or in a nominal scale or categorical scale. Non-parametric statistics deals with  small sample sizes.

Non-parametric statistics are assumption free meaning these are not bound by any assumptions. Non-parametric statistics are user friendly compared
with parametric statistics and economical in time. We have learnt that parametric tests are generally quite robust and are useful even when some
of their mathematical assumptions are violated.

However, these tests are used only with the data based upon ratio or interval measurements. In case of counted or ranked data, we make use
of non-parametric tests. It is argued that non-parametric tests have greater merit because their validity is not based upon assumptions about
the nature of the population distribution, assumptions that are so frequently ignored or violated by researchers using parametric tests.
It may be noted that non-parametric tests are less precise and have less power than the parametric tests.
