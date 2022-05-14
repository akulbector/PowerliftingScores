# PowerliftingStrengthScores
Fair ways to compare strength regardless of bodyweight

It's common knowledge that the heavier you are the more you can lift. Hench squatting 500lbs at 120lbs bodyweight is more impressive than squatting 500lbs at 220lbs bodyweight. Hence the broscience method to correct this is to use "relative bodyweight". However, the data shows this is a terrible metric.

In R I compare relative bodyweight scores, Wilks, and 2 new scores whose parameters are trained from the data. One score is based on a log log or allometric model. The other score is based on a simple linear model with the addition of varying variance rather than traditionally assumed constant variance.
