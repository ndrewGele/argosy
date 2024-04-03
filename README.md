# Argosy

Argosy is an application for algorithmic trading using the API-driven Alpaca Brokerage.

The codebase uses the Alpaca-py SDK to communicate with the Alpaca service, but rest of the code is wrtten in R (Data Engineering, MLOps, Strategies, Backtesting, etc.).

The application is structured as a set of microservices, which can all be started with Docker Compose yaml provided by this repo. Most of the dependencies are pulled in automatically from Github's Container registry, but the **Common Code** and **Strategies** repositories will need to be added manually (via submodules, cloning, or downloading).
