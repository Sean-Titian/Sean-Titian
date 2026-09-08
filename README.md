<p align="center">
  <img src="./assets/profile-header.svg" alt="Zishen (Sean) Tian — build carefully, ship clearly" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/Sean-Titian?tab=repositories">Projects</a>
  ·
  <a href="https://github.com/Sean-Titian?tab=stars">Learning shelf</a>
  ·
  <a href="https://www.linkedin.com/in/zishen-tian-a14318320/">LinkedIn</a>
</p>

## Hello, I'm Sean (Zishen) Tian.

I am building toward **Applied / Product Data Science with strong ML Engineering skills**. I care about the full path from a product question to a trustworthy decision: define the metric, validate the data, model the uncertainty, test the intervention, and ship a reproducible system.

I am pursuing an M.S. in Spatial Economics and Data Analysis at the University of Southern
California (expected 2027), bringing an econometrics lens to product experimentation and applied
machine learning.

### Selected work

Each case study is rebuilt from my own analysis and excludes private course material, restricted
data, and unverifiable claims. Projects are linked only after passing a reality, license,
reproducibility, and documentation review.

<!-- PROFILE:PROJECTS:START -->
- **[Conversion Intelligence](https://github.com/Sean-Titian/conversion-intelligence)** — acquisition scoring with a prediction-time contract: mean AP 0.133 against a 3.2% base rate and 5.25× lift at the top 5%. A synthetic-only Spark SQL/PySpark extension enforces event- and availability-time cutoffs and one row per score request, with exact Spark/Pandas parity on its deterministic fixture. The higher-scoring full-session model remains a retrospective upper bound because its final page count is unavailable at the acquisition-time decision.
- **[Lifecycle Email Experimentation](https://github.com/Sean-Titian/lifecycle-email-experimentation)** — a messaging case study that separates a limited retrospective source audit from a public-safe synthetic implementation with fixed windows, multiplicity correction, a pre-treatment negative control, and guardrails. Only 1 of 24 source funding-snapshot differences survived correction (+0.311 pp; adjusted p ≈ 0.011); no cadence winner was supported.
- **[Review Sentiment Reliability](https://github.com/Sean-Titian/review-sentiment-reliability)** — a clean-room, synthetic-only reliability study for a rating-derived text proxy. Contract 2.0 enforces leakage-aware group/time evaluation, repeated null controls, serving stress, and train/serve parity. Because rating defines the target, the model may be redundant when ratings are visible; it makes no real-data, causal, or production-value claim.
<!-- PROFILE:PROJECTS:END -->

### How I work

| Frame the decision | Separate prediction from causality | Build for review |
| :--- | :--- | :--- |
| Start with the user, metric, prediction time, and cost of error. | Use observational models for ranking; use experiments for intervention claims. | Add data contracts, tests, CI, model cards, and honest limitations. |

### T-shaped direction

| Depth I am developing | Breadth I am building | Long-term direction |
| :--- | :--- | :--- |
| Experimentation · Causal inference · Applied ML | SQL · PySpark · MLOps · Cloud · LLM systems | Applied / Product Data Scientist → Applied Scientist / ML Scientist |

I treat this as a roadmap, not a wall of skill badges. A technology appears as a demonstrated strength only after a project makes the design choices, limitations, and evidence visible.

### Evidence shipped, learning next

SQL/PySpark has moved from roadmap to public project evidence through the Conversion pipeline above and its dedicated Spark parity CI. This proves controlled transformation correctness—not production scale, online serving, or improved real-world model performance.

Next I am extending Lifecycle Email's existing public-safe synthetic workflow toward its full prospective design: stratified factorial assignment with a concurrent holdout, aligned 14-day follow-up, sample-ratio and contamination checks, multiplicity-aware decision rules, and non-inferiority customer-harm guardrails.

<p align="center">
  <sub>Measure carefully · Build responsibly · Improve in public</sub>
</p>
