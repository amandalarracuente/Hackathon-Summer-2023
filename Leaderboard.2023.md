<!-- Edit to set working directory-->
<!-- Get libraries situated-->
<!-- update manifest, formatted in the following way:
 "team number"  "division"  "captain"   "Your github handle"    "members"   "Display pseudonym for rankings"    "e-mails"   "match?"    "size"  "Done?"-->
<!--Leaderboard setup-->

# Leaderboard for GIDS Biomedical Data Hackathon 2023

-   **time stamp:** “11 August, 2023 20:05:35”

<!--Read in list of github handles, retrieve predictions, score-->

| pseudonym | TP  | TN    | FP   | FN   |     MCC |
|:----------|:----|:------|:-----|:-----|--------:|
| TEST      | 342 | 15688 | 2374 | 2550 | -0.0135 |
| FLY       | 342 | 15688 | 2374 | 2550 | -0.0135 |

\****Confusion matrix categories:***

-   **TP**: True positives

-   **TN**: True negatives

-   **FP**: False positives

-   **FN**: False negatives

**MCC**: Matthews Correlation Coefficient of submitted predictions
(closer to 1 is better).

**readme_ok**: was there a README.md publicly available for your forked
repo ? (If false, then the repo hasn’t been created yet or the handle is
incorrect)

**message**: Error message if predictions couldn’t be found or parsed.

-   If your team isn’t included at all here, we may not have your github
    handle yet, or there may be an issue with your registration. Please
    open an issue or email the organizers.

<!-- Get threshold for better than random guessing-->
