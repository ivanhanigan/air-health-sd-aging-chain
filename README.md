# air-health-sd-aging-chain

A system dynamics model using aging chain stock-flow framework to estimate disease burden attributable to air pollution. Takes PM2.5 emissions data and reduction scenarios as inputs to calculate attributable premature mortalities across population cohorts.

## Background

This demonstration model was originally prepared for the Modelling and Simulation Society of Australia and New Zealand (MODSIM) conference in 2019. It explores the use of system dynamics approaches for environmental health impact assessment, building on aging chain methodologies.

## Key Findings

While manipulating life-tables as state transition probability matrices (Leslie matrices) as implemented in [iomlifetR](https://github.com/richardbroome2002/iomlifetR) is simpler, system dynamics models offer distinct advantages:

### Strengths of SD Approach
- **Greater flexibility** to explore interactions and lags
- **Well suited to collaborative conceptual modelling**: drivers and feedbacks
- **What-If scenarios**: Policy intervention experiments in silico
- **Escaping the complexity dilemma** (Newell and Proust 2017)
- **Quantifying sensitivities** based on many simulation runs

### Trade-offs
Many other modeling tools are available, each with different strengths for specific applications.

## Co-Authors
- Steven vander Hoorn
- Barry Newell

## License

MIT

## Software requirements

[https://vensim.com/free-download/](https://vensim.com/free-download/)

## Related Projects
- [iomlifetR](https://github.com/richardbroome2002/iomlifetR) - Life-table based approach using Leslie matrices
- [air-health-sws-r-targets](https://github.com/YOUR_USERNAME/air-health-sws-r-targets) - Pipeline for environmental health impact assessment