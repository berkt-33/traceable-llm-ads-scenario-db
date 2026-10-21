# LLMs Propose, Code Decides: A Traceable Scenario Database for Scenario-Based Testing of Automated Driving

**Berkay Taştan** · October 2026 · long version

**Read the paper:** [PDF](paper.pdf) · [on GitHub](paper.md)

Scenario-based testing of automated driving systems depends on scenario databases that reject
broken files, merge duplicates, explain what each scenario tests and show which required test
cases are missing. A recent survey names an LLM-assisted scenario database as an open problem.
This paper presents one in which LLMs propose and deterministic code decides: every acceptance,
rejection, merge and coverage count comes from rules, simulation and closed predicates, and every
LLM call is recorded. It is evaluated on up to 2 484 scenarios against Euro NCAP and UN R157
test protocols, with a fault-injection benchmark for the quality gate, generation for coverage
gaps, systems under test in simulation, and a small model fine-tuned on simulation-verified
examples.

## Citation

> B. Taştan. LLMs Propose, Code Decides: A Traceable Scenario Database for Scenario-Based
> Testing of Automated Driving. 2026.

See also [`CITATION.cff`](CITATION.cff).

## License

The paper and its figures are licensed under
[Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).
