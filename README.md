# Awesome Quant with stars

A curated list of insanely awesome libraries, packages and resources for Quants (Quantitative Finance).

[![](https://awesome.re/badge.svg)](https://awesome.re)

## Contents

* [Numerical Libraries & Data Structures](#numerical-libraries-data-structures)
* [Financial Instruments & Pricing](#financial-instruments-pricing)
* [Technical Indicators](#technical-indicators)
* [Trading & Backtesting](#trading-backtesting)
* [Portfolio Optimization & Risk Analysis](#portfolio-optimization-risk-analysis)
* [Factor Analysis](#factor-analysis)
* [Sentiment Analysis & Alternative Data](#sentiment-analysis-alternative-data)
* [Time Series Analysis](#time-series-analysis)
* [Market Data & Data Sources](#market-data--data-sources)
* [Prediction Markets](#prediction-markets)
* [Calendars & Market Hours](#calendars-market-hours)
* [Visualization](#visualization)
* [Excel & Spreadsheet Integration](#excel-spreadsheet-integration)
* [Quant Research Environments](#quant-research-environments)
* [Cross-Language Frameworks](#cross-language-frameworks)
* [Reproducing Works, Training & Books](#reproducing-works-training-books)
* [Commercial & Proprietary Services](#commercial-proprietary-services)
* [Related Lists](#related-lists)

## Numerical Libraries & Data Structures

* [pandas](https://pandas.pydata.org) - `Python` - pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language. [GitHub](https://github.com/pandas-dev/pandas) ⭐ 49,587 | 🐛 2,757 | 🌐 Python | 📅 2026-08-29
* [polars](https://docs.pola.rs/) - `Python` - Polars is a blazingly fast DataFrame library for manipulating structured data. [GitHub](https://github.com/pola-rs/polars) ⭐ 39,536 | 🐛 2,870 | 🌐 Rust | 📅 2026-08-28
* [numpy](https://www.numpy.org) - `Python` - NumPy is the fundamental package for scientific computing with Python. [GitHub](https://github.com/numpy/numpy) ⭐ 32,622 | 🐛 2,341 | 🌐 Python | 📅 2026-08-28
* [scipy](https://www.scipy.org) - `Python` - SciPy (pronounced “Sigh Pie”) is a Python-based ecosystem of open-source software for mathematics, science, and engineering. [GitHub](https://github.com/scipy/scipy) ⭐ 14,963 | 🐛 1,835 | 🌐 Python | 📅 2026-08-28
* [sympy](https://www.sympy.org/) - `Python` - SymPy is a Python library for symbolic mathematics. [GitHub](https://github.com/sympy/sympy) ⭐ 14,896 | 🐛 5,963 | 🌐 Python | 📅 2026-08-27
* [pymc3](https://docs.pymc.io/) - `Python` - Probabilistic Programming in Python: Bayesian Modeling and Probabilistic Machine Learning with Theano. [GitHub](https://github.com/pymc-devs/pymc) ⭐ 9,728 | 🐛 491 | 🌐 Python | 📅 2026-08-24
* [data.table](https://github.com/Rdatatable/data.table) ⭐ 3,914 | 🐛 983 | 🌐 R | 📅 2026-08-27 - `R` - Extension of data.frame: Fast aggregation of large data (e.g. 100GB in RAM), fast ordered joins, fast add/modify/delete of columns by group using no copies at all, list columns and a fast file reader (fread). Offers a natural and flexible syntax, for faster development.
* [ArcticDB](https://github.com/man-group/ArcticDB) ⭐ 2,495 | 🐛 329 | 🌐 C++ | 📅 2026-08-28 - `Python` - High performance datastore for time series and tick data.
* [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl) ⭐ 1,831 | 🐛 160 | 🌐 Julia | 📅 2026-08-23 - `Julia` - In-memory tabular data in Julia.
* [quantdsl](https://github.com/johnbywater/quantdsl) ⭐ 384 | 🐛 4 | 🌐 Python | 📅 2018-04-14 - `Python` - Domain specific language for quantitative analytics in finance and trading.
* [xts](https://github.com/joshuaulrich/xts) ⭐ 224 | 🐛 74 | 🌐 R | 📅 2026-02-28 - `R` - eXtensible Time Series: Provide for uniform handling of R's different time-based data classes by extending zoo, maximizing native format information preservation and allowing for user level customization and extension, while simplifying cross-class interoperability.
* [modelx](https://docs.modelx.io/) - `Python` - Python reimagination of spreadsheets as formula-centric objects that are interoperable with pandas. [GitHub](https://github.com/fumitoh/modelx) ⭐ 134 | 🐛 38 | 🌐 Python | 📅 2026-08-28
* [Temporal.jl](https://github.com/dysonance/Temporal.jl) ⭐ 101 | 🐛 15 | 🌐 Julia | 📅 2023-03-03 - `Julia` - Flexible and efficient time series class & methods.
* [TSFrames.jl](https://github.com/xKDR/TSFrames.jl) ⭐ 101 | 🐛 53 | 🌐 Julia | 📅 2024-06-18 - `Julia` - Handle timeseries data on top of the powerful and mature DataFrames.jl.
* [jacobian](https://github.com/morluto/jacobian) ⭐ 80 | 🐛 288 | 🌐 Python | 📅 2026-08-29 - `Python` `MCP` - Exact computation and conjecture testing across polynomial maps, linear algebra, and graph algorithms for agent-driven mathematical research.
* [TimeArrays.jl](https://github.com/bhftbootcamp/TimeArrays.jl) ⭐ 40 | 🐛 0 | 🌐 Julia | 📅 2026-07-03 - `Julia` - Time series handling for Julia.
* [sparseEigen](https://github.com/dppalomar/sparseEigen) ⭐ 13 | 🐛 2 | 🌐 R | 📅 2018-12-22 - `R` - Sparse principal component analysis.
* [CRNG](https://github.com/brotto/crng) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-04-12 - `Python` - Contingency Random Number Generator that produces random numbers with real financial market statistical signatures (fat tails, volatility clustering, kurtosis). Matches 86% of real market metrics vs 14% for NumPy.
* [statistics](https://docs.python.org/3/library/statistics.html) - `Python` - Builtin Python library for all basic statistical calculations.
* [TSdbi](http://tsdbi.r-forge.r-project.org/) - `R` - Provides a common interface to time series databases.
* [tseries](https://cran.r-project.org/web/packages/tseries/index.html) - `R` - Time Series Analysis and Computational Finance.
* [zoo](https://cran.r-project.org/web/packages/zoo/index.html) - `R` - S3 Infrastructure for Regular and Irregular Time Series (Z's Ordered Observations).
* [tis](https://cran.r-project.org/web/packages/tis/index.html) - `R` - Functions and S3 classes for time indexes and time indexed series, which are compatible with FAME frequencies.
* [tfplot](https://cran.r-project.org/web/packages/tfplot/index.html) - `R` - Utilities for simple manipulation and quick plotting of time series data.
* [tframe](https://cran.r-project.org/web/packages/tframe/index.html) - `R` - A kernel of functions for programming time series methods in a way that is relatively independently of the representation of time.

## Financial Instruments & Pricing

* [gs-quant](https://github.com/goldmansachs/gs-quant) ⭐ 12,793 | 🐛 69 | 🌐 Python | 📅 2026-08-26 - `Python` - Python toolkit for quantitative finance.
* [tf-quant-finance](https://github.com/google/tf-quant-finance) ⭐ 5,486 | 🐛 42 | 🌐 Python | 📅 2026-08-06 - `Python` - High-performance TensorFlow library for quantitative finance.
* [FinancePy](https://github.com/domokane/FinancePy) ⭐ 3,115 | 🐛 50 | 🌐 Jupyter Notebook | 📅 2026-08-22 - `Python` - A Python Finance Library that focuses on the pricing and risk-management of Financial Derivatives, including fixed-income, equity, FX and credit derivatives.
* [ffn](https://github.com/pmorissette/ffn) ⭐ 2,637 | 🐛 11 | 🌐 Python | 📅 2026-08-13 - `Python` - A financial function library for Python.
* [RustQuant](https://github.com/avhz/RustQuant) ⭐ 1,814 | 🐛 34 | 🌐 Rust | 📅 2026-01-14 - `Rust` - Quantitative finance library written in Rust.
* [optlib](https://github.com/dbrojas/optlib) ⭐ 1,630 | 🐛 0 | 🌐 Python | 📅 2022-11-18 - `Python` - A library for financial options pricing written in Python.
* [PyQL](https://github.com/enthought/pyql) ⭐ 1,336 | 🐛 20 | 🌐 Cython | 📅 2026-07-17 - `Python` - QuantLib's Python port.
* [finance.js](https://github.com/ebradyjobory/finance.js) ⭐ 1,271 | 🐛 31 | 🌐 JavaScript | 📅 2023-03-02 - `JavaScript` - A JavaScript library for common financial calculations.
* [QuantPy](https://github.com/jsmidt/QuantPy) ⭐ 1,051 | 🐛 17 | 🌐 Python | 📅 2023-05-25 - `Python` - A framework for quantitative finance In python.
* [vollib](https://github.com/vollib/vollib) ⭐ 1,016 | 🐛 4 | 🌐 Python | 📅 2023-06-05 - `Python` - vollib is a python library for calculating option prices, implied volatility and greeks.
* [Strata](http://strata.opengamma.io/) - `Java` - Modern open-source analytics and market risk library designed and written in Java. [GitHub](https://github.com/OpenGamma/Strata) ⭐ 956 | 🐛 91 | 🌐 Java | 📅 2026-08-25
* [Finance-Python](https://github.com/alpha-miner/Finance-Python) ⭐ 911 | 🐛 9 | 🌐 Python | 📅 2024-01-01 - `Python` - Python tools for Finance.
* [quantmod](https://cran.r-project.org/web/packages/quantmod/index.html) - `R` - Quantitative Financial Modelling Framework. [GitHub](https://github.com/joshuaulrich/quantmod) ⭐ 906 | 🐛 87 | 🌐 R | 📅 2026-07-03
* [Q-Fin](https://github.com/RomanMichaelPaolucci/Q-Fin) ⭐ 652 | 🐛 1 | 🌐 Python | 📅 2023-10-31 - `Python` - A Python library for mathematical finance.
* [Quantsbin](https://github.com/quantsbin/Quantsbin) ⭐ 649 | 🐛 3 | 🌐 Python | 📅 2023-07-06 - `Python` - Tools for pricing and plotting of vanilla option prices, greeks and various other analysis around them.
* [pysabr](https://github.com/ynouri/pysabr) ⭐ 623 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2022-04-21 - `Python` - SABR model Python implementation.
* [finmath.net](http://finmath.net) - `Java` - Java library with algorithms and methodologies related to mathematical finance. [GitHub](https://github.com/finmath/finmath-lib) ⭐ 581 | 🐛 8 | 🌐 Java | 📅 2026-06-09
* [optionlab](https://github.com/rgaveiga/optionlab) ⭐ 563 | 🐛 6 | 🌐 Python | 📅 2026-08-10 - `Python` - A Python library for evaluating option trading strategies.
* [financial-engineering](https://github.com/federicomariamassari/financial-engineering) ⭐ 543 | 🐛 0 | 🌐 Python | 📅 2017-11-20 - `Python` - Applications of Monte Carlo methods to financial engineering projects, in Python.
* [pynance](https://github.com/GriffinAustin/pynance) ⭐ 474 | 🐛 8 | 🌐 Python | 📅 2021-02-03 - `Python` - Lightweight Python library for assembling and analyzing financial data.
* [tia](https://github.com/bpsmith/tia) ⭐ 428 | 🐛 41 | 🌐 Python | 📅 2023-02-15 - `Python` - Toolkit for integration and analysis.
* [py\_vollib](https://github.com/vollib/py_vollib) ⭐ 427 | 🐛 1 | 🌐 Python | 📅 2026-05-29 - `Python` - vollib Python implementation.
* [QuantMath](https://github.com/MarcusRainbow/QuantMath) ⭐ 408 | 🐛 21 | 🌐 Rust | 📅 2023-06-16 - `Rust` - Financial maths library for risk-neutral pricing and risk.
* [willowtree](https://github.com/federicomariamassari/willowtree) ⭐ 381 | 🐛 1 | 🌐 Python | 📅 2018-07-14 - `Python` - Robust and flexible Python implementation of the willow tree lattice for derivatives pricing.
* [rateslib](https://github.com/attack68/rateslib) ⭐ 353 | 🐛 29 | 📅 2026-05-20 - `Python` - A fixed income library for pricing bonds and bond futures, and derivatives such as IRS, cross-currency and FX swaps.
* [pyfin](https://github.com/opendoor-labs/pyfin) ⚠️ Archived - `Python` - Basic options pricing in Python. *ARCHIVED*.
* [finoptions](https://github.com/bbcho/finoptions-dev) ⭐ 299 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-02-01 - `Python` - Complete python implementation of R package fOptions with partial implementation of fExoticOptions for pricing various options.
* [StochVolModels](https://github.com/ArturSepp/StochVolModels) ⭐ 234 | 🐛 0 | 🌐 Python | 📅 2026-08-28 - `Python` - Pricing analytics and Monte Carlo simulation for stochastic volatility models, including the log-normal SV model and the Heston model.
* [quantcomponents](https://github.com/lsgro/quantcomponents) ⭐ 169 | 🐛 4 | 🌐 Java | 📅 2018-07-28 - `Java` - Free Java components for Quantitative Finance and Algorithmic Trading.
* [JQuantLib](https://github.com/frgomes/jquantlib) ⭐ 155 | 🐛 8 | 🌐 Java | 📅 2016-03-14 - `Java` - JQuantLib is a free, open-source, comprehensive framework for quantitative finance, written in 100% Java.
* [fypy](https://github.com/jkirkby3/fypy) ⭐ 146 | 🐛 2 | 🌐 Python | 📅 2025-02-27 - `Python` - Vanilla and exotic option pricing library to support quantitative R\&D. Focus on pricing interesting/useful models and contracts (including and beyond Black-Scholes), as well as calibration of financial models to market data.
* [QuantLib.jl](https://github.com/pazzo83/QuantLib.jl) ⭐ 144 | 🐛 10 | 🌐 Julia | 📅 2020-02-18 - `Julia` - Quantlib implementation in pure Julia.
* [quantfin](https://github.com/boundedvariation/quantfin) ⭐ 139 | 🐛 0 | 🌐 Haskell | 📅 2019-04-06 - `Haskell` - quant finance in pure haskell.
* [RQuantLib](https://github.com/eddelbuettel/rquantlib) ⭐ 136 | 🐛 9 | 🌐 C++ | 📅 2026-07-26 - `R` - RQuantLib connects GNU R with QuantLib.
* [Kelly-Criterion](https://github.com/deltaray-io/kelly-criterion) ⭐ 116 | 🐛 4 | 🌐 Python | 📅 2022-12-08 - `Python` - Kelly Criterion implemented in Python to size portfolios based on J. L. Kelly Jr's formula.
* [Intrinsic-Value-Calculator](https://github.com/akashaero/Intrinsic-Value-Calculator) ⭐ 96 | 🐛 1 | 🌐 Python | 📅 2025-07-02 - `Python` - A Python tool for quick calculations of a stock's fair value using Discounted Cash Flow analysis.
* [Miletus.jl](https://github.com/JuliaComputing/Miletus.jl) ⭐ 93 | 🐛 5 | 🌐 Julia | 📅 2025-12-09 - `Julia` - A financial contract definition, modeling language, and valuation framework.
* [AbsBox](https://github.com/yellowbean/AbsBox) ⭐ 71 | 🐛 10 | 🌐 Python | 📅 2026-08-23 - `Python` - A Python based library to model cashflow for structured product like Asset-backed securities (ABS) and Mortgage-backed securities (MBS).
* [R-fixedincome](https://github.com/wilsonfreitas/R-fixedincome) ⭐ 64 | 🐛 16 | 🌐 R | 📅 2025-05-10 - `R` - Fixed income tools for R.
* [QuantScale](https://github.com/choucrifahed/quantscale) ⭐ 51 | 🐛 0 | 🌐 Scala | 📅 2014-02-06 - `Scala` - Scala Quantitative Finance Library.
* [Pyderivatives](https://github.com/Julian-Beatty/Pyderivatives) ⭐ 42 | 🐛 0 | 🌐 HTML | 📅 2026-07-22 - `Python` - Toolkit for option pricing, implied volatility surfaces, risk-neutral densities, and pricing kernel surfaces with support for advanced models including Heston, Kou, and Bates.
* [Ito.jl](https://github.com/aviks/Ito.jl) ⚠️ Archived - `Julia` - A Julia package for quantitative finance.
* [Haxcel](https://github.com/MarcusRainbow/Haxcel) ⭐ 38 | 🐛 0 | 🌐 Rust | 📅 2022-09-13 - `Haskell` - Excel Addin for Haskell.
* [derivmkts](https://cran.r-project.org/web/packages/derivmkts/index.html) - `R` - Functions and R Code to Accompany Derivatives Markets. [GitHub](https://github.com/rmcd1024/derivmkts) ⭐ 37 | 🐛 9 | 🌐 HTML | 📅 2026-02-12
* [r-quant](https://github.com/artyyouth/r-quant) ⭐ 35 | 🐛 0 | 🌐 R | 📅 2014-02-19 - `R` - R code for quantitative analysis in finance.
* [quantra](https://github.com/joseprupi/quantraserver) ⭐ 29 | 🐛 8 | 🌐 C++ | 📅 2026-08-05 - `Python` - High-performance pricing engine built on QuantLib. It exposes QuantLib's functionality through gRPC and REST APIs, enabling distributed computations with FlatBuffers serialization.
* [FinCal](https://github.com/felixfan/FinCal) ⭐ 25 | 🐛 0 | 🌐 R | 📅 2025-10-30 - `R` - Package for time value of money calculation, time series analysis and computational finance.
* [vanilla-option-pricers](https://github.com/ArturSepp/VanillaOptionPricers) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2026-08-28 - `Python` - Fast, vectorised Black-Scholes-Merton and Bachelier pricers and implied volatility fitters, including inverse options for crypto derivatives.
* [pypme](https://github.com/ymyke/pypme) ⭐ 14 | 🐛 4 | 🌐 Python | 📅 2026-01-16 - `Python` - PME (Public Market Equivalent) calculation.
* [fmbasics](https://github.com/imanuelcostigan/fmbasics) ⭐ 12 | 🐛 7 | 🌐 R | 📅 2022-02-01 - `R` - Financial Market Building Blocks.
* [QuantOracle](https://github.com/QuantOracledev/quantoracle) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-19 - `Python` - Free quant finance API with 63 deterministic endpoints + 15 free interactive calculators at [quantoracle.dev](https://quantoracle.dev). Options pricing with full Greeks, Monte Carlo, Kelly, VaR, Sharpe, CAGR, crypto liquidation, impermanent loss, plus live crypto volatility/funding data and 24/7 position monitoring with webhook alerts. 1,000 free calls/day, no API key.
* [Scala Quant](https://github.com/frankcash/Scala-Quant) ⭐ 10 | 🐛 1 | 🌐 Scala | 📅 2017-05-06 - `Scala` - Scala library for working with stock data from IFTTT recipes or Google Finance.
* [credule](https://github.com/blenezet/credule) ⭐ 7 | 🐛 1 | 🌐 HTML | 📅 2015-08-05 - `R` - Credit Default Swap Functions.
* [options.studies](https://github.com/taylorizing/options.studies) ⭐ 6 | 🐛 0 | 🌐 R | 📅 2015-12-17 - `R` - options trading studies functions for use with options.data package and shiny.
* [flashalpha](https://github.com/FlashAlpha-lab/flashalpha-python) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-08-26 - `Python` - Python client for the FlashAlpha options analytics API.
* [Ffinar](https://github.com/MarcusRainbow/Ffinar) ⭐ 5 | 🐛 0 | 🌐 Haskell | 📅 2022-03-05 - `Haskell` - A financial maths library in Haskell.
* [mortgagemath](https://github.com/murraystokely/mortgagemath) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-08-24 - `Python` - Cent-accurate mortgage amortization schedules with Decimal arithmetic and published-source validation across six countries.
* [QoX](https://github.com/bboutelje/qox-python-samples) ⭐ 4 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-07-20 - `Python` - Finite difference pricing library written in Rust.
* [BDE Score](https://github.com/hbhqq9/bde-score) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2026-08-01 - `Python` - Multi-factor quantitative stock analysis MCP server for US, HK, and CN A-share markets. Transparent 0-100 scoring from 40+ indicators. Listed on Official MCP Registry.
* [hagan-sabr](https://github.com/moshejs/hagan-sabr) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - SABR stochastic-volatility model (Hagan 2002 lognormal/normal expansions, Obłój correction, smile calibration); zero dependencies, matches QuantLib's sabrVolatility to 1e-9.
* [implied-expectations](https://github.com/Keenan-ux/implied-expectations) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-02 - `Python` - Reverse DCF that solves for the revenue growth, duration, and operating margin a stock price implies, from SEC EDGAR fundamentals.
* [svi-vol-surface](https://github.com/moshejs/svi-vol-surface) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - Gatheral SVI volatility surface (raw/natural/jump-wings), butterfly and calendar arbitrage checks, slice calibration; zero dependencies.
* [compounded-sofr](https://github.com/moshejs/compounded-sofr) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - SOFR compounding-in-arrears per ARRC/ISDA conventions (lookback, observation shift, lockout) and the SOFR Index method; reproduces the NY Fed's published averages.
* [day-count-conventions](https://github.com/moshejs/day-count) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - ISDA 2006 day-count conventions (30/360 family, ACT/360, ACT/365F, ACT/ACT ISDA and ICMA); zero dependencies.
* [tips-index-ratio](https://github.com/moshejs/tips-index-ratio) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - US TIPS inflation math per 31 CFR 356 Appendix B (reference-CPI interpolation, index ratios); reproduces TreasuryDirect's published values.
* [32nds](https://github.com/moshejs/32nds) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - US Treasury price quote math: parse and format 32nds quotes (105-16+), ticks, and basis points; zero dependencies.
* [Rmetrics](https://www.rmetrics.org) - `R` - The premier open source software solution for teaching and training quantitative finance.
  * [fAsianOptions](https://cran.r-project.org/web/packages/fAsianOptions/index.html) - EBM and Asian Option Valuation.
  * [fAssets](https://cran.r-project.org/web/packages/fAssets/index.html) - Analysing and Modelling Financial Assets.
  * [fBasics](https://cran.r-project.org/web/packages/fBasics/index.html) - Markets and Basic Statistics.
  * [fBonds](https://cran.r-project.org/web/packages/fBonds/index.html) - Bonds and Interest Rate Models.
  * [fExoticOptions](https://cran.r-project.org/web/packages/fExoticOptions/index.html) - Exotic Option Valuation.
  * [fOptions](https://cran.r-project.org/web/packages/fOptions/index.html) - Pricing and Evaluating Basic Options.
  * [fPortfolio](https://cran.r-project.org/web/packages/fPortfolio/index.html) - Portfolio Selection and Optimization.
* [sde](https://cran.r-project.org/web/packages/sde/index.html) - `R` - Simulation and Inference for Stochastic Differential Equations.
* [YieldCurve](https://cran.r-project.org/web/packages/YieldCurve/index.html) - `R` - Modelling and estimation of the yield curve.
* [SmithWilsonYieldCurve](https://cran.r-project.org/web/packages/SmithWilsonYieldCurve/index.html) - `R` - Constructs a yield curve by the Smith-Wilson method from a table of LIBOR and SWAP rates.
* [ycinterextra](https://cran.r-project.org/web/packages/ycinterextra/index.html) - `R` - Yield curve or zero-coupon prices interpolation and extrapolation.
* [AmericanCallOpt](https://cran.r-project.org/web/packages/AmericanCallOpt/index.html) - `R` - This package includes pricing function for selected American call options with underlying assets that generate payouts.
* [VarSwapPrice](https://cran.r-project.org/web/packages/VarSwapPrice/index.html) - `R` - Pricing a variance swap on an equity index.
* [RND](https://cran.r-project.org/web/packages/RND/index.html) - `R` - Risk Neutral Density Extraction Package.
* [LSMonteCarlo](https://cran.r-project.org/web/packages/LSMonteCarlo/index.html) - `R` - American options pricing with Least Squares Monte Carlo method.
* [OptHedging](https://cran.r-project.org/web/packages/OptHedging/index.html) - `R` - Estimation of value and hedging strategy of call and put options.
* [tvm](https://cran.r-project.org/web/packages/tvm/index.html) - `R` - Time Value of Money Functions.
* [OptionPricing](https://cran.r-project.org/web/packages/OptionPricing/index.html) - `R` - Option Pricing with Efficient Simulation Algorithms.
* [DRIP](https://lakshmidrip.github.io/DRIP) - `Java` - Fixed Income, Asset Allocation, Transaction Cost Analysis, XVA Metrics Libraries.

## Technical Indicators

* [TA-Lib](https://github.com/mrjbq7/ta-lib) ⭐ 12,218 | 🐛 137 | 🌐 Cython | 📅 2026-07-29 - `Python` - Python wrapper for TA-Lib (<http://ta-lib.org/>).
* [ta](https://github.com/bukosabino/ta) ⭐ 5,180 | 🐛 157 | 🌐 Jupyter Notebook | 📅 2026-03-18 - `Python` - Technical Analysis Library using Pandas (Python).
* [ta4j](https://github.com/ta4j/ta4j) ⭐ 2,484 | 🐛 20 | 🌐 Java | 📅 2026-08-28 - `Java` - A Java library for technical analysis.
* [finta](https://github.com/peerchemist/finta) ⚠️ Archived - `Python` - Common financial technical analysis indicators implemented in Pandas.
* [IndicatorGo](https://github.com/cinar/indicator) ⭐ 1,496 | 🐛 38 | 🌐 Go | 📅 2026-08-24 - `Golang` - IndicatorGo is a Golang module providing various stock technical analysis indicators, strategies, and a backtest framework for trading.
* [pandas\_talib](https://github.com/femtotrader/pandas_talib) ⭐ 787 | 🐛 15 | 🌐 Python | 📅 2018-05-30 - `Python` - A Python Pandas implementation of technical analysis indicators.
* [talipp](https://github.com/nardew/talipp) ⭐ 536 | 🐛 31 | 🌐 Python | 📅 2025-09-09 - `Python` - Incremental technical analysis library for Python.
* [bta-lib](https://github.com/mementum/bta-lib) ⭐ 502 | 🐛 23 | 🌐 Python | 📅 2022-01-25 - `Python` - Technical Analysis library in pandas for backtesting algotrading and quantitative analysis.
* [lppls](https://github.com/Boulder-Investment-Technologies/lppls) ⭐ 474 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2026-05-30 - `Python` - A Python module for fitting the [Log-Periodic Power Law Singularity (LPPLS)](https://en.wikipedia.org/wiki/Didier_Sornette#The_JLS_and_LPPLS_models) model.
* [IndicatorTS](https://github.com/cinar/indicatorts) ⭐ 468 | 🐛 37 | 🌐 TypeScript | 📅 2026-08-20 - `JavaScript` - Indicator is a TypeScript module providing various stock technical analysis indicators, strategies, and a backtest framework for trading.
* [TuneTA](https://github.com/jmrichardson/tuneta) ⚠️ Archived - `Python` - TuneTA optimizes technical indicators using a distance correlation measure to a user defined target feature such as next day return.
* [TTR](https://github.com/joshuaulrich/TTR) ⭐ 349 | 🐛 32 | 🌐 R | 📅 2026-02-28 - `R` - Technical Trading Rules.
* [Indicators.jl](https://github.com/dysonance/Indicators.jl) ⭐ 227 | 🐛 19 | 🌐 Julia | 📅 2022-12-06 - `Julia` - Financial market technical analysis & indicators on top of Temporal.
* [streaming\_indicators](https://github.com/mr-easy/streaming_indicators) ⭐ 153 | 🐛 0 | 🌐 Python | 📅 2025-04-27 - `Python` - A python library for computing technical analysis indicators on streaming data.
* [MarketTechnicals.jl](https://github.com/JuliaQuant/MarketTechnicals.jl) ⭐ 131 | 🐛 19 | 🌐 Julia | 📅 2021-11-05 - `Julia` - Technical analysis of financial time series on top of TimeSeries.
* [TradeAggregation](https://github.com/MathisWellmann/trade_aggregation-rs) ⭐ 119 | 🐛 2 | 🌐 Rust | 📅 2026-02-05 - `Rust` - Aggregate trades into user-defined candles using information driven rules.
* [Tulipy](https://github.com/cirla/tulipy) ⭐ 93 | 🐛 0 | 📅 2019-04-11 - `Python` - Financial Technical Analysis Indicator Library (Python bindings for [tulipindicators](https://github.com/TulipCharts/tulipindicators) ⭐ 942 | 🐛 35 | 🌐 C | 📅 2024-02-02).
* [orderflow](https://github.com/focus1691/orderflow) ⭐ 81 | 🐛 6 | 🌐 TypeScript | 📅 2025-03-31 - `JavaScript` - Orderflow trade aggregator for building Footprint Candles from exchange websocket data.
* [SlidingFeatures](https://github.com/MathisWellmann/sliding_features-rs) ⭐ 78 | 🐛 0 | 🌐 Rust | 📅 2026-06-29 - `Rust` - Chainable tree-like sliding windows for signal processing and technical analysis.
* [TALib.jl](https://github.com/femtotrader/TALib.jl) ⭐ 53 | 🐛 15 | 🌐 Julia | 📅 2017-08-22 - `Julia` - A Julia wrapper for TA-Lib.
* [Wickra](https://github.com/wickra-lib/wickra) ⭐ 50 | 🐛 0 | 🌐 Rust | 📅 2026-08-28 - `Rust` `Python` `JavaScript` `C++` `C#` `Golang` `Java` `R` - Streaming-first technical-analysis library with a Rust core: 514 indicators updating in O(1) per tick, with bit-exact batch-vs-streaming results.
* [OnlineTechnicalIndicators.jl](https://github.com/femtotrader/OnlineTechnicalIndicators.jl) ⭐ 34 | 🐛 2 | 🌐 Julia | 📅 2026-06-22 - `Julia` - Julia Technical Analysis Indicators via online algorithms.
* [fin-primitives](https://github.com/Mattbusel/fin-primitives) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2026-03-23 - `Rust` - Financial market primitives in Rust: Price/Quantity/Symbol newtypes, BTreeMap order book, OHLCV aggregation, SMA/EMA/RSI indicators, position ledger with PnL, and composable risk monitor.
* [QuantWave](https://github.com/lavs9/quantwave) ⭐ 12 | 🐛 2 | 🌐 Rust | 📅 2026-08-25 - `Python` `Rust` `Polars` - Polars-native technical analysis and backtesting with bit-identical batch and streaming parity, plus an agent skill for consistent research-to-live strategy code.
* [TechnicalIndicatorCharts.jl](https://github.com/g-gundam/TechnicalIndicatorCharts.jl) ⭐ 8 | 🐛 0 | 🌐 Julia | 📅 2026-08-08 - `Julia` - Visualize OnlineTechnicalIndicators.jl using LightweightCharts.jl.
* [wickworks](https://github.com/psyb0t/docker-wickworks) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-08-01 - `REST` `MCP` - Stateless OHLC analyzer: POST bars and requested indicators, get back RSI/MACD/Bollinger/ADX/ATR/VWAP/Ichimoku plus smart-money-concept primitives (order blocks, FVGs, BOS/CHoCH, swing structure). No database, no AI signals.

## Trading & Backtesting

* [freqtrade](https://github.com/freqtrade/freqtrade) ⭐ 53,782 | 🐛 35 | 🌐 Python | 📅 2026-08-27 - `Python` - Free, open source crypto trading bot.

* [Qlib](https://github.com/microsoft/qlib) ⭐ 48,019 | 🐛 469 | 🌐 Python | 📅 2026-07-23 - `Python` - An AI-oriented Quantitative Investment Platform by Microsoft. Full ML pipeline of data processing, model training, back-testing; and covers the entire chain of quantitative investment: alpha seeking, risk modeling, portfolio optimization, and order execution.

* [vnpy](https://github.com/vnpy/vnpy) ⭐ 44,830 | 🐛 32 | 🌐 Python | 📅 2026-08-28 - `Python` - VeighNa is a Python-based open source quantitative trading system development framework.

* [ccxt](https://github.com/ccxt/ccxt) ⭐ 43,785 | 🐛 828 | 🌐 Python | 📅 2026-08-28 - `JavaScript` `Python` `PHP` - A JavaScript / Python / PHP cryptocurrency trading API with support for more than 100 bitcoin/altcoin exchanges.

* [Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) ⭐ 31,986 | 🐛 29 | 🌐 Python | 📅 2026-08-28 - `Python` - Natural-language multi-agent finance research agent with 29 swarm presets, 70 skills, and 28 auto-discovered tools; 7 backtest engines covering A-shares/US/Crypto/Futures/Forex/Options plus a cross-market CompositeEngine with shared capital pool; 5-source auto-fallback data layer (tushare/okx/yfinance/akshare/ccxt); 17-tool MCP server; includes trade-journal behavioral diagnostics for 同花顺/东财/富途 exports.

* [nautilus\_trader](https://github.com/nautechsystems/nautilus_trader) ⭐ 28,038 | 🐛 113 | 🌐 Rust | 📅 2026-08-29 - `Python` `Rust` - A high-performance algorithmic trading platform and event-driven backtester.

* [backtrader](https://github.com/backtrader/backtrader) ⭐ 23,012 | 🐛 63 | 🌐 Python | 📅 2024-08-19 - `Python` - Python Backtesting library for trading strategies.

* [Lean](https://github.com/QuantConnect/Lean) ⭐ 21,390 | 🐛 258 | 🌐 C# | 📅 2026-08-28 - `Python` `C#` - Lean Algorithmic Trading Engine by QuantConnect (Python, C#).

* [QuantConnect](https://github.com/QuantConnect/Lean) ⭐ 21,390 | 🐛 258 | 🌐 C# | 📅 2026-08-28 - `CSharp` - Lean Engine is an open-source fully managed C# algorithmic trading engine built for desktop and cloud usage.

* [machine-learning-for-trading](https://github.com/stefan-jansen/machine-learning-for-trading) ⭐ 20,710 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2026-08-28 - `Python` - Code and resources for Machine Learning for Algorithmic Trading.

* [zipline](https://github.com/quantopian/zipline) ⭐ 20,072 | 🐛 370 | 🌐 Python | 📅 2024-02-13 - `Python` - Pythonic algorithmic trading library.

* [FinRL-Library](https://github.com/AI4Finance-LLC/FinRL-Library) ⭐ 16,130 | 🐛 310 | 🌐 Jupyter Notebook | 📅 2026-07-13 - `Python` - A Deep Reinforcement Learning Library for Automated Trading in Quantitative Finance. NeurIPS 2020.

* [QUANTAXIS](https://github.com/yutiansut/quantaxis) ⭐ 11,055 | 🐛 239 | 🌐 Python | 📅 2026-02-28 - `Matlab` - Integrated Quantitative Toolbox with Matlab.

* [StockSharp](https://github.com/StockSharp/StockSharp) ⭐ 10,658 | 🐛 2 | 🌐 C# | 📅 2026-08-28 - `CSharp` - Algorithmic trading and quantitative trading open source platform to develop trading robots (stock markets, forex, crypto, bitcoins, and options).

* [Stock-Prediction-Models](https://github.com/huseinzol05/Stock-Prediction-Models) ⚠️ Archived - `Python` - Gathers machine learning and deep learning models for Stock forecasting including trading bots and simulations.

* [vectorbt](https://github.com/polakowo/vectorbt) ⭐ 8,891 | 🐛 138 | 🌐 Python | 📅 2026-08-02 - `Python` - Find your trading edge, using a powerful toolkit for backtesting, algorithmic trading, and research.

* [jesse](https://github.com/jesse-ai/jesse) ⭐ 8,391 | 🐛 16 | 🌐 Python | 📅 2026-08-27 - `Python` - An advanced crypto trading bot written in Python.

* [quantstats](https://github.com/ranaroussi/quantstats) ⭐ 7,598 | 🐛 31 | 🌐 Python | 📅 2026-07-20 - `Python` - Portfolio analytics for quants, written in Python.

* [rqalpha](https://github.com/ricequant/rqalpha) ⭐ 6,731 | 🐛 31 | 🌐 Python | 📅 2026-08-28 - `Python` - A extendable, replaceable Python algorithmic backtest && trading framework supporting multiple securities.

* [OctoBot](https://github.com/Drakkar-Software/OctoBot) ⭐ 6,483 | 🐛 165 | 🌐 Python | 📅 2026-08-28 - `Python` - Open source cryptocurrency trading bot for high frequency, arbitrage, TA and social trading with an advanced web interface.

* [pyalgotrade](https://github.com/gbeced/pyalgotrade) ⚠️ Archived - `Python` - Python Algorithmic Trading Library.

* [hftbacktest](https://github.com/nkaz001/hftbacktest) ⭐ 4,551 | 🐛 16 | 🌐 Rust | 📅 2025-12-23 - `Python` - A high-frequency trading and market-making backtesting tool accounts for limit orders, queue positions, and latencies, utilizing full tick data for trades and order books.

* [zvt](https://github.com/zvtvz/zvt) ⭐ 4,288 | 🐛 22 | 🌐 Python | 📅 2026-07-01 - `Python` - the project using sql, pandas to provide an uniform and extendable way to record data, computing factors, select securities, backtesting, realtime trading and it could show all of them in clearly charts in realtime.

* [finmarketpy](https://github.com/cuemacro/finmarketpy) ⭐ 3,806 | 🐛 38 | 🌐 Python | 📅 2026-04-16 - `Python` - Python library for backtesting trading strategies and analyzing financial markets.

* [PyBroker](https://github.com/edtechre/pybroker) ⭐ 3,519 | 🐛 0 | 🌐 Python | 📅 2026-08-28 - `Python` - Algorithmic Trading with Machine Learning.

* [pysystemtrade](https://github.com/robcarver17/pysystemtrade) ⭐ 3,490 | 🐛 31 | 🌐 Python | 📅 2026-07-18 - `Python` - pysystemtrade is the open source version of Robert Carver's backtesting and trading engine that implements systems according to the framework outlined in his book "Systematic Trading", which is further developed on his [blog](https://qoppac.blogspot.com/).

* [algorithmic-trading-with-python](https://github.com/chrisconlan/algorithmic-trading-with-python) ⭐ 3,480 | 🐛 6 | 🌐 Python | 📅 2021-06-01 - `Python` - Free `pandas` and `scikit-learn` resources for trading simulation, backtesting, and machine learning on financial data.

* [Hikyuu](https://github.com/fasiondog/hikyuu) ⭐ 3,472 | 🐛 5 | 🌐 C++ | 📅 2026-08-28 - `Python` `C++` - A base on Python/C++ open source high-performance quant framework for faster analysis and backtesting, contains the complete trading system components for reuse and combination.

* [Hikyuu](https://github.com/fasiondog/hikyuu) ⭐ 3,472 | 🐛 5 | 🌐 C++ | 📅 2026-08-28 - `Python` `C++` - A base on Python/C++ open source high-performance quant framework for faster analysis and backtesting, contains the complete trading system components for reuse and combination. You can use python or c++ freely.

* [QSTrader](https://github.com/mhallsmoore/qstrader) ⭐ 3,449 | 🐛 18 | 🌐 Python | 📅 2024-06-30 - `Python` - QSTrader backtesting simulation engine.

* [bt](https://github.com/pmorissette/bt) ⭐ 2,971 | 🐛 87 | 🌐 Python | 📅 2026-08-07 - `Python` - Flexible Backtesting for Python.

* [catalyst](https://github.com/enigmampc/catalyst) ⚠️ Archived - `Python` - An Algorithmic Trading Library for Crypto-Assets in Python.

* [Blankly](https://github.com/Blankly-Finance/Blankly) ⭐ 2,468 | 🐛 39 | 🌐 Python | 📅 2024-12-30 - `Python` - Fully integrated backtesting, paper trading, and live deployment.

* [bulbea](https://github.com/achillesrasquinha/bulbea) ⭐ 2,323 | 🐛 37 | 🌐 Python | 📅 2021-01-17 - `Python` - Deep Learning based Python Library for Stock Market Prediction and Modelling.

* [qtpylib](https://github.com/ranaroussi/qtpylib) ⚠️ Archived - `Python` - QTPyLib, Pythonic Algorithmic Trading <http://qtpylib.io>.

* [Barter](https://github.com/barter-rs/barter-rs) ⭐ 2,244 | 🐛 89 | 🌐 Rust | 📅 2026-08-24 - `Rust` - Open-source Rust framework for building event-driven live-trading & backtesting systems.

* [Lumibot](https://github.com/Lumiwealth/lumibot) ⭐ 2,006 | 🐛 84 | 🌐 Python | 📅 2026-08-29 - `Python` - Algorithmic trading framework where the same code runs for backtesting and live trading across stocks, options, crypto, futures, and forex with multiple brokers including Alpaca, Interactive Brokers, Tradier, and Schwab.

* [Investing algorithm framework](https://github.com/coding-kitties/investing-algorithm-framework) ⭐ 1,988 | 🐛 70 | 🌐 Python | 📅 2026-08-28 - `Python` - Framework for developing, backtesting, and deploying automated trading algorithms.

* [zipline-reloaded](https://github.com/stefan-jansen/zipline-reloaded) ⭐ 1,930 | 🐛 44 | 🌐 Python | 📅 2026-01-06 - `Python` - Zipline, a Pythonic Algorithmic Trading Library.

* [Intelligent Trading Bot](https://github.com/asavinov/intelligent-trading-bot) ⭐ 1,860 | 🐛 47 | 🌐 Python | 📅 2026-08-11 - `Python` - Automatically generating signals and trading based on machine learning and feature engineering.

* [fastquant](https://github.com/enzoampil/fastquant) ⭐ 1,754 | 🐛 82 | 🌐 Jupyter Notebook | 📅 2023-09-15 - `Python` - fastquant allows you to easily backtest investment strategies with as few as 3 lines of python code.

* [AlphaPy](https://github.com/ScottfreeLLC/AlphaPy) ⭐ 1,745 | 🐛 19 | 🌐 Python | 📅 2025-08-24 - `Python` - Automated Machine Learning \[AutoML] with Python, scikit-learn, Keras, XGBoost, LightGBM, and CatBoost.

* [PandoraTrader](https://github.com/pegasusTrader/PandoraTrader) ⭐ 1,461 | 🐛 8 | 🌐 C++ | 📅 2025-10-18 - `CPP` - A C++ CTP trading framework, with very clear logic.

* [tda-api](https://github.com/alexgolec/tda-api) ⭐ 1,323 | 🐛 39 | 🌐 Python | 📅 2024-06-16 - `Python` - Gather data and trade equities, options, and ETFs via TDAmeritrade.

* [AutoTrader](https://github.com/kieran-mackle/AutoTrader) ⚠️ Archived - `Python` - A Python-based development platform for automated trading systems - from backtesting to optimization to livetrading.

* [fooltrader](https://github.com/foolcage/fooltrader) ⭐ 1,198 | 🐛 6 | 🌐 Python | 📅 2023-05-22 - `Python` - the project using big-data technology to provide an uniform way to analyze the whole market.

* [Kelp](https://github.com/stellar/kelp) ⚠️ Archived - `Golang` - Kelp is an open-source Golang algorithmic cryptocurrency trading bot that runs on centralized exchanges and Stellar DEX (command-line usage and desktop GUI).

* [qf-lib](https://github.com/quarkfin/qf-lib) ⭐ 956 | 🐛 12 | 🌐 Python | 📅 2026-08-24 - `Python` - QF-Lib is a Python library that provides high quality tools for quantitative finance.

* [basana](https://github.com/gbeced/basana) ⭐ 861 | 🐛 1 | 🌐 Python | 📅 2026-08-09 - `Python` - A Python async and event driven framework for algorithmic trading, with a focus on crypto currencies.

* [aat](https://github.com/timkpaine/aat) ⭐ 831 | 🐛 1 | 🌐 C++ | 📅 2026-07-27 - `Python` - Async Algorithmic Trading Engine.

* [pybacktest](https://github.com/ematvey/pybacktest) ⭐ 822 | 🐛 17 | 🌐 Python | 📅 2021-11-11 - `Python` - Vectorized backtesting framework in Python / pandas, designed to make your backtesting easier.

* [Quantdom](https://github.com/constverum/Quantdom) ⭐ 773 | 🐛 11 | 🌐 Python | 📅 2022-07-06 - `Python` - Python-based framework for backtesting trading strategies & analyzing financial markets \[GUI :neckbeard:.]

* [PRISM-INSIGHT](https://github.com/dragon1086/prism-insight) ⭐ 727 | 🐛 6 | 🌐 Python | 📅 2026-08-29 - `Python` - AI-powered stock analysis system with 13 specialized agents, automated trading via KIS API, supporting Korean & US markets.

* [pylivetrader](https://github.com/alpacahq/pylivetrader) ⭐ 685 | 🐛 20 | 🌐 Python | 📅 2022-10-04 - `Python` - zipline-compatible live trading library.

* [TradeFrame](https://github.com/rburkholder/trade-frame) ⭐ 674 | 🐛 3 | 🌐 C++ | 📅 2026-08-14 - `CPP` - C++ 17 based framework/library (with sample applications) for testing options based automated trading ideas using DTN IQ real time data feed and Interactive Brokers (TWS API) for trade execution. Comes with built-in [Option Greeks/IV](https://github.com/rburkholder/trade-frame/tree/master/lib/TFOptions) ⭐ 674 | 🐛 3 | 🌐 C++ | 📅 2026-08-14 calculation library.

* [fast-trade](https://github.com/jrmeier/fast-trade) ⭐ 588 | 🐛 3 | 🌐 Python | 📅 2026-08-22 - `Python` - A library built with backtest portability and performance in mind for backtest trading strategies.

* [Tai](https://github.com/fremantle-capital/tai) ⭐ 498 | 🐛 11 | 🌐 Elixir | 📅 2024-12-07 - `Elixir/Erlang` - Open Source composable, real time, market data and trade execution toolkit.

* [QuantSoftware Toolkit](https://github.com/QuantSoftware/QuantSoftwareToolkit) ⭐ 480 | 🐛 24 | 🌐 HTML | 📅 2017-10-02 - `Python` - Python-based open source software framework designed to support portfolio construction and management.

* [the0](https://github.com/alexanderwanyoike/the0) ⭐ 391 | 🐛 11 | 🌐 TypeScript | 📅 2026-08-13 - `Python` - Self-hosted execution engine for algorithmic trading bots. Write strategies in Python, TypeScript, Rust, C++, C#, Scala, or Haskell and deploy with one command. Each bot runs in an isolated container with scheduled or streaming execution.

* [pyqstrat](https://github.com/abbass2/pyqstrat) ⭐ 372 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2023-11-05 - `Python` - A fast, extensible, transparent python library for backtesting quantitative strategies.

* [quantstrat](https://github.com/braverock/quantstrat) ⭐ 310 | 🐛 51 | 🌐 R | 📅 2023-09-14 - `R` - Transaction-oriented infrastructure for constructing trading systems and simulation. Provides support for multi-asset class and multi-currency portfolios for backtesting and other financial research.

* [pinkfish](https://github.com/fja05680/pinkfish) ⭐ 305 | 🐛 4 | 🌐 Python | 📅 2026-08-17 - `Python` - A backtester and spreadsheet library for security analysis.

* [moonshot](https://github.com/quantrocket-llc/moonshot) ⭐ 274 | 🐛 0 | 🌐 Python | 📅 2026-07-30 - `Python` - Vectorized backtester and trading engine for QuantRocket based on Pandas.

* [Jiji](https://github.com/unageanu/jiji2) ⭐ 249 | 🐛 30 | 🌐 JavaScript | 📅 2021-04-30 - `Ruby` - Open Source Forex algorithmic trading framework using OANDA REST API.

* [Trading Strategy](https://github.com/tradingstrategy-ai/getting-started) ⭐ 245 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2026-08-21 - `Python` - TradingStrategy.ai is a market data, backtesting, live trading and investor management framework for decentralised finance.

* [analyzer](https://github.com/llazzaro/analyzer) ⚠️ Archived - `Python` - Python framework for real-time financial and backtesting trading strategies.

* [StrateQueue](https://github.com/StrateQueue/StrateQueue) ⭐ 212 | 🐛 17 | 🌐 Python | 📅 2026-05-19 - `Python` - An open‑source, broker‑agnostic Python library that lets you seamlessly deploy strategies from any major backtesting engine to live (or paper) trading with zero code changes and built‑in safety controls.

* [PROJ\_Option\_Pricing\_Matlab](https://github.com/jkirkby3/PROJ_Option_Pricing_Matlab) ⭐ 209 | 🐛 1 | 🌐 MATLAB | 📅 2024-11-19 - `Matlab` - Quant Option Pricing - Exotic/Vanilla: Barrier, Asian, European, American, Parisian, Lookback, Cliquet, Variance Swap, Swing, Forward Starting, Step, Fader.

* [pipeline-live](https://github.com/alpacahq/pipeline-live) ⭐ 205 | 🐛 15 | 🌐 Python | 📅 2023-07-25 - `Python` - zipline's pipeline capability with IEX for live trading.

* [PyLOB](https://github.com/DrAshBooth/PyLOB) ⭐ 203 | 🐛 0 | 🌐 Python | 📅 2026-08-14 - `Python` - Fully functioning fast Limit Order Book written in Python.

* [pytrendseries](https://github.com/rafa-rod/pytrendseries) ⭐ 168 | 🐛 0 | 🌐 Python | 📅 2026-05-30 - `Python` - Detect trend in time series, drawdown, drawdown within a constant look-back window , maximum drawdown, time underwater.

* [TradeSight](https://github.com/rmbell09-lang/tradesight) ⭐ 167 | 🐛 7 | 🌐 Python | 📅 2026-07-15 - `Python` - Self-hosted AI trading platform with strategy evolution, technical analysis, backtesting, and paper trading via Alpaca.

* [Strategems.jl](https://github.com/dysonance/Strategems.jl) ⭐ 167 | 🐛 14 | 🌐 Julia | 📅 2021-04-06 - `Julia` - Quantitative systematic trading strategy development and backtesting.

* [OrderMatchingEngine](https://github.com/PIYUSH-KUMAR1809/order-matching-engine) ⭐ 159 | 🐛 1 | 🌐 C++ | 📅 2026-01-11 - `CPP` - A production-grade, lock-free, high-frequency trading matching engine achieving 150M+ orders/sec.

* [backtrader (cloudQuant fork)](https://github.com/cloudQuant/backtrader) ⭐ 158 | 🐛 0 | 🌐 Python | 📅 2026-08-22 - `Python` - Actively maintained, high-performance backtesting and live trading framework with AI-assisted strategy tooling (MCP server, skills, agent, web platform). [backtrader](https://github.com/backtrader/backtrader) ⭐ 23,012 | 🐛 63 | 🌐 Python | 📅 2024-08-19 fork.

* [FAIG](https://github.com/tg12/FAIG) ⚠️ Archived - `Python` - Fully automated trading bot for the IG Index platform (spread betting and CFDs), supporting demo and live accounts.

* [Workbench](https://github.com/fremantle-industries/workbench) ⭐ 122 | 🐛 27 | 🌐 Elixir | 📅 2023-03-06 - `Elixir/Erlang` - From Idea to Execution - Manage your trading operation across a globally distributed cluster.

* [blotter](https://github.com/braverock/blotter) ⭐ 116 | 🐛 30 | 🌐 R | 📅 2024-12-14 - `R` - Transaction infrastructure for defining instruments, transactions, portfolios and accounts for trading systems and simulation. Provides portfolio support for multi-asset class and multi-currency portfolios. Actively maintained and developed.

* [NowTrade](https://github.com/edouardpoitras/NowTrade) ⭐ 103 | 🐛 8 | 🌐 Python | 📅 2017-02-08 - `Python` - Python library for backtesting technical/mechanical strategies in the stock and currency markets.

* [NexusFix](https://github.com/SilverstreamsAI/NexusFix) ⭐ 98 | 🐛 5 | 🌐 C++ | 📅 2026-07-21 - `CPP` - C++23 FIX protocol engine with zero-copy parsing and SIMD acceleration, 3x faster than QuickFIX.

* [algobroker](https://github.com/joequant/algobroker) ⭐ 96 | 🐛 0 | 🌐 Python | 📅 2016-03-31 - `Python` - This is an execution engine for algo trading.

* [QTradeX-Algo-Trading-SDK](https://github.com/squidKid-deluxe/QTradeX-Algo-Trading-SDK) ⭐ 84 | 🐛 5 | 🌐 Python | 📅 2026-07-30 - `Python` - AI-powered SDK featuring algorithmic trading, backtesting, deployment on 100+ exchanges, and multiple optimization engines.

* [rust\_bt](https://github.com/jensnesten/rust_bt) ⭐ 82 | 🐛 1 | 🌐 Rust | 📅 2026-01-05 - `Python` - A high performance, low-latency backtesting engine for testing quantitative trading strategies on historical and live data in Rust.

* [LFEST](https://github.com/MathisWellmann/lfest-rs) ⭐ 82 | 🐛 0 | 🌐 Rust | 📅 2026-08-23 - `Rust` - Simulated perpetual futures exchange to trade your strategy against.

* [quantitative](https://github.com/jeffrey-liang/quantitative) ⭐ 67 | 🐛 0 | 🌐 Python | 📅 2019-03-03 - `Python` - Quantitative finance, and backtesting library.

* [Orallexa](https://github.com/alex-jb/orallexa-ai-trading-agent) ⭐ 65 | 🐛 4 | 🌐 Python | 📅 2026-07-12 - `Python` - AI trading operating system with 9 ML models (RF, XGBoost, EMAformer, MOIRAI-2, Chronos-2, DDPM, PPO RL, GNN, LR) ranked by Sharpe ratio, Claude AI synthesis with dual-tier routing (\~$0.003/analysis), real-time Next.js dashboard, Alpaca paper trading, and 277 automated tests.

* [pythalesians](https://github.com/thalesians/pythalesians) ⭐ 63 | 🐛 1 | 📅 2016-09-23 - `Python` - Python library to backtest trading strategies, plot charts, seamlessly download market data, analyze market patterns etc.

* [Prop](https://github.com/fremantle-industries/prop) ⭐ 57 | 🐛 25 | 🌐 Elixir | 📅 2023-03-06 - `Elixir/Erlang` - An open and opinionated trading platform using productive & familiar open source libraries and tools for strategy research, execution and operation.

* [TDAmeritrade.DotNetCore](https://github.com/NVentimiglia/TDAmeritrade.DotNetCore) ⭐ 56 | 🐛 5 | 🌐 C# | 📅 2023-03-10 - `CSharp` - Free, open-source .NET Client for the TD Ameritrade Trading Platform. Helps developers integrate TD Ameritrade API into custom trading solutions.

* [Gunbot Quant](https://github.com/GuntharDeNiro/gunbot-quant) ⭐ 54 | 🐛 2 | 🌐 JavaScript | 📅 2025-08-19 - `Python` - Toolkit for quantitative trading analysis. It integrates an advanced market screener, a multi-strategy, multi-asset backtesting engine. Use with built-in GUI or through CLI.

* [binary-martingale](https://github.com/metaperl/binary-martingale) ⭐ 48 | 🐛 1 | 🌐 Python | 📅 2017-10-16 - `Python` - Computer program to automatically trade binary options martingale style.

* [OctoBot Script](https://github.com/Drakkar-Software/OctoBot-Script) ⭐ 47 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-12 - `Python` - A quant framework to create cryptocurrencies strategies - from backtesting to optimization to livetrading.

* [aurumq-rl](https://github.com/yupoet/aurumq-rl) ⭐ 44 | 🐛 17 | 🌐 Python | 📅 2026-07-24 - `Python` - Reinforcement learning stock-selection framework for the China A-share market with multi-source factor input (alpha101 + main-force flow + hot-money seats + northbound + institutional + fundamentals), board-aware price limits, and ONNX CPU inference.

* [jquantstats](https://github.com/Jebel-Quant/jquantstats) ⭐ 43 | 🐛 3 | 🌐 Python | 📅 2026-08-28 - `Python` - Modern variation of quantstats, with additional features and performance improvements.

* [DeepAlpha](https://deepalphabot.com) - `Python` - AI crypto trading bot for Bybit with 70.9% walk-forward validated accuracy on out-of-sample data, LightGBM + XGBoost ensemble with 72 ML features. [GitHub](https://github.com/stefanoviana/deepalpha) ⭐ 41 | 🐛 17 | 🌐 Python | 📅 2026-05-12

* [TradeClaw](https://github.com/naimkatiman/tradeclaw) ⭐ 40 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-29 - `Node.js` `TypeScript` - Open-source self-hosted AI trading signal platform. Generates buy/sell signals using RSI, MACD, EMA, Bollinger Bands for forex, crypto and commodities. Deployable via Docker Compose. ([Demo](https://tradeclaw.win/dashboard))

* [PythonTradingFramework](https://github.com/JustinGuese/python_tradingbot_framework) ⭐ 35 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-25 - `Python` - Python algorithmic trading bot framework for Kubernetes: backtesting, hyperparameter optimization, 150+ technical analysis indicators (RSI, MACD, Bollinger Bands, ADX), portfolio management, PostgreSQL integration, Helm deployment, CronJob scheduling. Minimal overhead, production-ready, Yahoo Finance data.

* [ib\_nope](https://github.com/ajhpark/ib_nope) ⭐ 33 | 🐛 4 | 🌐 Python | 📅 2021-04-22 - `Python` - Automated trading system for NOPE strategy over IBKR TWS.

* [Inalpha](https://github.com/mirror29/inalpha) ⭐ 32 | 🐛 25 | 🌐 Python | 📅 2026-08-28 - `Python` `TypeScript` - Conversational multi-agent quant framework where agents rank currently-effective factors for entry timing (time-series rank IC), write complete strategy code that passes sandboxed audit before backtesting, and evolve strategies under multi-objective fitness; every order requires machine approval and the LLM never has a direct order path.

* [FinClaw](https://github.com/NeuZhou/finclaw) ⭐ 30 | 🐛 1 | 📅 2026-04-18 - `Python` - AI-powered financial intelligence engine with 8 master strategies across US, CN, and HK markets. Multi-agent architecture with +29.1% annual alpha. 227 tests.

* [TraderHarness](https://github.com/HephaestLab/TraderHarness) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2026-08-22 - `Python` - Contamination-resistant A-share backtesting environment for LLM trading agents with point-in-time masking, entity/date anonymization, fingerprinted replay, and trajectory (SFT) export.

* [Lucky.jl](https://github.com/oliviermilla/Lucky.jl) ⭐ 29 | 🐛 4 | 🌐 Julia | 📅 2026-06-25 - `Julia` - Modular, asynchronous trading engine in pure Julia.

* [purgedcv](https://github.com/eslazarev/purged-cross-validation) ⭐ 28 | 🐛 1 | 🌐 Python | 📅 2026-08-28 - `Python` - scikit-learn-compatible purged, group-purged, and combinatorial purged (CPCV) cross-validation, walk-forward splitting, and backtest-overfitting statistics (deflated and probabilistic Sharpe ratios, PBO, minimum backtest length) to prevent leakage and overfitting when backtesting trading strategies.

* [Manifold-BT](https://github.com/manifoldbt/manifoldbt) ⭐ 26 | 🐛 2 | 🌐 Python | 📅 2026-08-28 - `Python` `Rust` - High-performance Rust-powered backtesting engine for quantitative research with parameter sweeps, walk-forward and Monte Carlo.

* [mt5-httpapi](https://github.com/psyb0t/mt5-httpapi) ⭐ 26 | 🐛 5 | 🌐 Python | 📅 2026-08-25 - `Python` `REST` `MCP` - MetaTrader 5 in a Windows VM (Docker + QEMU/KVM) over REST and MCP: market data, order/position/history management for automated trading and bots, the strategy-tester (backtesting) API, and server-side indicators (RSI/MACD/Bollinger/ADX/VWAP/Ichimoku, order blocks, FVGs). Multi-broker, multi-account.

* [VARRD](https://github.com/augiemazza/varrd) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2026-08-27 - `Python` - AI-powered trading edge discovery platform that validates trading ideas with event studies, statistical tests, and real market data. Web app, MCP server, CLI (`pip install varrd`), and Python SDK.

* [TrendFollowingSystems](https://github.com/ArturSepp/TrendFollowingSystems) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2026-08-28 - `Python` - Closed-form expected returns, Sharpe ratios, and skewness of trend-following systems, with complete implementations and multi-decade futures backtests.

* [Fastback.jl](https://github.com/rbeeli/Fastback.jl) ⭐ 21 | 🐛 1 | 🌐 Julia | 📅 2026-05-05 - `Julia` - Blazing fast Julia backtester.

* [DepthSight](https://github.com/depthsight-pro/depthsight) ⭐ 20 | 🐛 31 | 🌐 Python | 📅 2026-07-20 - `Python` `TypeScript` - Self-hosted visual algo-trading platform featuring a drag-and-drop strategy builder, an AI co-pilot, and integrated billing.

* [pyhood](https://github.com/jamestford/pyhood) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2026-08-24 - `Python` - Robinhood API client for unattended automation: after the first approved login, sessions renew from a stored refresh token with no password or device approval prompt. Covers stocks, equity and index options with Greeks, futures, IRA accounts, and the official Crypto Trading API.

* [zipline-extensions](https://github.com/quantrocket-llc/zipline-extensions) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2020-04-17 - `Python` - Zipline extensions and adapters for QuantRocket.

* [QTradeX-AI-Agents](https://github.com/squidKid-deluxe/QTradeX-AI-Agents) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2025-05-25 - `Python` - Example strategies for the QTradeX platfrom.

* [income-desk](https://github.com/nitinblue/income-desk) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2026-08-28 - `Python` - Systematic options trading intelligence for small accounts with desk-based portfolio management, pre-trade validation, and multi-broker consolidation.

* [antback](https://github.com/ts-kontakt/antback) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2026-08-16 - `Python` - A lightweight, event-loop-style backtest engine that allows a function-driven imperative style using efficient stateful helper functions and data containers.

* [AI Quant Agents](https://github.com/demandai/ai-quant-agents) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2026-03-24 - `Python` - Multi-agent LLM trading analysis where 12 AI agents (analysts, debaters, risk manager) debate stock picks in real-time, supporting US equities and China A-shares.

* [orderbook](https://github.com/intrepidkarthi/orderbook) ⭐ 14 | 🐛 6 | 🌐 Go | 📅 2026-08-26 - `Go` `WebAssembly` - Embeddable limit order book and matching engine with integer-exact pricing, a single-writer core and write-ahead-log crash recovery, plus a microstructure research harness whose order-flow-imbalance, Kyle's lambda and CVD studies are measured against simulator ground truth.

* [VerumTrade](https://github.com/muye1202/VerumTrade) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-06-29 - `Python` - A reasoning & decision-trace visible Multi-agent LLM trading-research framework where bull/bear analysts debate each ticker and every decision cites the evidence it rests on.

* [backtest-bias](https://github.com/Finance-broski/backtest-bias) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-08-13 - `Python` - Checks whether backtest price data is survivor-only: dead-name detection, measured bias benchmarks, CI integrity gates.

* [TolmachЁv Netcode SDK](https://github.com/billionerleha-111/Tolmachev-Netcode-SDK) ⭐ 11 | 🐛 0 | 📅 2026-08-09 - `CPP` - Enterprise-grade deterministic state synchronization engine for MFT gateways and statistical arbitrage. Eliminates microsecond deltas locking order books via topological mathematics. Throughput >41.5M TPS, physical RTT 24.175 ns, atomic validation (0 CPU load). [Website](https://tuhct-sdk.store)

* [ERN-WO Options Backtester](https://github.com/Javier-Garzo/ern-wo-options-backtester) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2026-08-16 - `Java` `Spring Boot` - Streaming backtesting engine for short-duration index options with conservative five-minute execution modeling and reproducible Early Retirement Now and WealthyOption strategy replication results.

* [AlgoVault](https://github.com/AlgoVaultLabs/crypto-quant-signal-mcp) ⭐ 7 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-29 - `TypeScript` - MCP server returning composite crypto trade verdicts (direction, confidence, regime) across 5 perpetual-futures venues, with cross-venue funding-rate arbitrage and an on-chain Merkle-verified track record. Free tier.

* [mx-trader-bridge](https://github.com/27dream/mx-trader-bridge) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-07-07 - `Python` - AI auto-trading bridge for East Money's miaoxiang (妙想) China A-share simulation platform; BYOK multi-LLM (OpenAI/DeepSeek/Moonshot/GLM/Qwen) decision brain → automated order placement via miaoxiang API, with daily cron review and weekly AI reflection.

* [YABTE](https://github.com/bsdz/yabte) ⭐ 7 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-02-15 - `Python` - Yet Another (Python) BackTesting Engine.

* [quantify](https://github.com/Zhanghanser/quantify) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-06-30 - `Python` - Binance-style trading terminal with multi-strategy backtesting and a real-time, signal-only decision desk for crypto, A-shares, and US stocks.

* [tw-stock-radar](https://github.com/carsonchou/tw-stock-radar) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-07-05 - `Python` - AI-powered Taiwan stock scanner for all 1,900+ TWSE/TPEX listed stocks; chips module (T86 institutional net buy/sell + TDCC 16-tier retail distribution), 13 technical indicators scored 0–100, ATR Chandelier signals with TP1/TP2, dark three.js HUD dashboard. 100% free open data, \~110 unit tests, no API key required.

* [ShowMe](https://github.com/nazmiefearmutcu/showMe) ⭐ 5 | 🐛 14 | 🌐 Python | 📅 2026-08-01 - `Python` `Rust` `TypeScript` - Open-source native macOS market cockpit. 12-timeframe consensus scan across 3370 symbols (crypto + equity + ETF + FX + commodity + bond), 23 technical indicators with per-market calibration, real WebSocket streaming. Tauri shell + Python sidecar (FastAPI) + React UI; 110+ exchanges via ccxt.

* [flashalpha-fill-simulator](https://github.com/FlashAlpha-lab/flashalpha-fill-simulator) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-08-26 - `Python` - Realistic limit-order fill simulator for options credit/debit spreads with post-and-wait limits, stale-quote guards, deterministic same-bar tiebreaks, and a patient-then-cross exit; engine-agnostic and zero runtime dependencies.

* [JIT-Optimization-Engine](https://github.com/cloudsealed/JIT-Optimization-Engine) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-08-09 - `Python` - High-performance analytical core using LLVM JIT (Numba) to process large-scale telemetry for quant diagnostics.

* [backtester-mcp](https://pypi.org/project/backtester-mcp/) - `Python` - Local-first backtesting engine with built-in overfitting checks (PBO, deflated Sharpe, bootstrap CI, walk-forward) and a native MCP server for AI agents. [GitHub](https://github.com/bcosm/backtester-mcp) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-04-17

* [TBV1](https://github.com/nazmiefearmutcu/TRADING-BOT) ⭐ 4 | 🐛 0 | 🌐 Kotlin | 📅 2026-07-27 - `Python` - Crypto perpetual-futures bot with a 7-tab web dashboard and a 15-indicator consensus engine voting across 12 timeframes (1m → 1d). Paper-mode by default. Includes packaged macOS reference build and Windows distribution.

* [honest-signals](https://github.com/MarvinRey7879/honest-signals) ⭐ 2 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-07-18 - `Python` - Scores detected chart patterns against the pattern-free baseline for the same market, timeframe and horizon, reporting lift with cluster-robust confidence intervals instead of a hit rate against 50%.

* [binance-fix-connector-python](https://github.com/AlexanderMerkel/binance-fix-connector-python) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-05-26 - `Python` - Async Python connector for Binance Spot FIX sessions with Order Entry, Market Data, and Drop Copy support.

* [Sextant](https://github.com/raphaub-hub/SEXTANT) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-04-05 - `Python` - Local event-driven backtesting engine with no-code strategy builder and FRED vintage, ALFRED, yFinance support.

* [alpha-forge-mcp](https://github.com/alforge-labs/alpha-forge-mcp) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-07-21 - `Python` - MCP server wrapping the AlphaForge CLI for AI-agent-native backtesting, Optuna TPE optimization, and walk-forward testing of trading strategies from Claude Desktop, Cursor, or Claude Code.

* [capitalcom-cli](https://github.com/SimonTarara62/capitalcom-cli) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2026-06-16 - `Python` - Unofficial CLI and async SDK for the Capital.com broker API: market data, guarded order execution, and real-time streaming.

* [autonomous-audit](https://pypi.org/project/autonomous-audit/) - `Python` - Tamper-evident SHA-256 hash-chain audit log and human-readable report for AI trading-agent decisions; read-only, offline, and dependency-free (Python standard library only). [GitHub](https://github.com/Autonomous-Asset-Management-Agents/autonomous_/tree/main/packages/autonomous-audit) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-08-28

* [NoEdge-Bench](https://github.com/nexusfinancial-dev/noedge-bench) ⭐ 1 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-07 - `Python` - Reproducible negative-result benchmark: no model beats a memoryless synthetic binary-options feed (AUC ≈ 0.50), with permutation-null tests and a look-ahead-leak case study.

* [midas-core](https://github.com/w2ur/midas-core) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-21 - `Python` - Multi-agent paper-trading framework where LLM agents author orders and a separate broker process enforces fifteen fill-time safety rails; each fill is stamped with the git commit it executed against for reproducibility.

* [mkt-alerts](https://github.com/dzianisv/mkt-alerts) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-23 - `TypeScript` - Self-hosted market-alert daemon: price, RSI/MACD/SMA conditions, and full Pine Script v5 custom indicators evaluated off-TradingView, on crypto (Coinbase) and stocks (Yahoo Finance) with no API key, delivered via ntfy push, email, or Telegram.

* [rulelint](https://github.com/momoddo/rulelint) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-11 - `Python` - Linter for mechanical trading-rule conditions: replays every condition over historical bars to catch look-ahead levels, dead branches that can never fire, and regime-drifted absolute thresholds before you trust a backtest.

* [ibkr-httpapi](https://github.com/psyb0t/ibkr-httpapi) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-01 - `Python` `REST` `MCP` - Interactive Brokers over REST and MCP (FastAPI + ib\_async over a Linux-native IB Gateway): market data (quotes, historical bars) plus order/position/execution management for automated trading across stocks, options, futures, forex, crypto and CFDs.

* [Backtesting.py](https://kernc.github.io/backtesting.py/) - `Python` - Backtest trading strategies in Python.

* [finlab](https://pypi.org/project/finlab/) - `Python` - Python package for Taiwan stock market data, factor research, and vectorized backtesting with pandas-style strategy definitions.

* [backtest](https://cran.r-project.org/web/packages/backtest/index.html) - `R` - Exploring Portfolio-Based Conjectures About Financial Instruments.

* [pa](https://cran.r-project.org/web/packages/pa/index.html) - `R` - Performance Attribution for Equity Portfolios.

* [QuantTools](https://quanttools.bitbucket.io/_site/index.html) - `R` - Enhanced Quantitative Trading Modelling.

## Portfolio Optimization & Risk Analysis

* [Ghostfolio](https://github.com/ghostfolio/ghostfolio) ⭐ 9,205 | 🐛 291 | 🌐 TypeScript | 📅 2026-08-28 - `JavaScript` - Wealth management software to keep track of financial assets like stocks, ETFs or cryptocurrencies and make solid, data-driven investment decisions.
* [pyfolio](https://github.com/quantopian/pyfolio) ⭐ 6,410 | 🐛 166 | 🌐 Jupyter Notebook | 📅 2023-12-23 - `Python` - Portfolio and risk analytics in Python.
* [PyPortfolioOpt](https://github.com/robertmartin8/PyPortfolioOpt) ⭐ 5,993 | 🐛 112 | 🌐 Jupyter Notebook | 📅 2026-07-07 - `Python` - Financial portfolio optimization in python, including classical efficient frontier and advanced methods.
* [mlfinlab](https://github.com/hudson-and-thames/mlfinlab) ⭐ 4,915 | 🐛 49 | 🌐 Python | 📅 2023-10-02 - `Python` - Implementations regarding "Advances in Financial Machine Learning" by Marcos Lopez de Prado. (Feature Engineering, Financial Data Structures, Meta-Labeling).
* [Riskfolio-Lib](https://github.com/dcajasn/Riskfolio-Lib) ⭐ 4,469 | 🐛 6 | 🌐 C++ | 📅 2026-08-18 - `Python` - Portfolio Optimization and Quantitative Strategic Asset Allocation in Python.
* [Eiten](https://github.com/tradytics/eiten) ⭐ 3,291 | 🐛 18 | 🌐 Python | 📅 2022-07-30 - `Python` - Eiten is an open source toolkit by Tradytics that implements various statistical and algorithmic investing strategies such as Eigen Portfolios, Minimum Variance Portfolios, Maximum Sharpe Ratio Portfolios, and Genetic Algorithms based Portfolios.
* [skfolio](https://github.com/skfolio/skfolio) ⭐ 2,302 | 🐛 27 | 🌐 Python | 📅 2026-08-25 - `Python` - Python library for portfolio optimization built on top of scikit-learn. It provides a unified interface and sklearn compatible tools to build, tune and cross-validate portfolio models.
* [FinQuant](https://github.com/fmilthaler/FinQuant) ⭐ 1,817 | 🐛 18 | 🌐 Python | 📅 2023-11-04 - `Python` - A program for financial portfolio management, analysis and optimization.
* [empyrical](https://github.com/quantopian/empyrical) ⭐ 1,509 | 🐛 37 | 🌐 Python | 📅 2024-07-26 - `Python` - Common financial risk and performance metrics.
* [fecon235](https://github.com/rsvp/fecon235) ⭐ 1,276 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2023-01-20 - `Python` - Computational tools for financial economics include: Gaussian Mixture model of leptokurtotic risk, adaptive Boltzmann portfolios.
* [DeepDow](https://github.com/jankrepl/deepdow) ⭐ 1,181 | 🐛 27 | 🌐 Python | 📅 2024-01-24 - `Python` - Portfolio optimization with deep learning.
* [Empyrial](https://github.com/ssantoshp/Empyrial) ⭐ 1,081 | 🐛 6 | 🌐 Python | 📅 2025-09-14 - `Python` - Portfolio's risk and performance analytics and returns predictions.
* [universal-portfolios](https://github.com/Marigold/universal-portfolios) ⭐ 858 | 🐛 33 | 🌐 Jupyter Notebook | 📅 2026-07-31 - `Python` - Collection of algorithms for online portfolio selection.
* [pyfolio-reloaded](https://github.com/stefan-jansen/pyfolio-reloaded) ⭐ 611 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2025-12-15 - `Python` - Portfolio and risk analytics in Python. [pyfolio](https://github.com/quantopian/pyfolio) ⭐ 6,410 | 🐛 166 | 🌐 Jupyter Notebook | 📅 2023-12-23 fork.
* [riskparity.py](https://github.com/dppalomar/riskparity.py) ⭐ 326 | 🐛 7 | 🌐 Python | 📅 2025-12-02 - `Python` - fast and scalable design of risk parity portfolios with TensorFlow 2.0.
* [fortitudo.tech](https://github.com/fortitudo-tech/fortitudo.tech) ⭐ 306 | 🐛 1 | 🌐 Python | 📅 2026-08-20 - `Python` - Conditional Value-at-Risk (CVaR) portfolio optimization and Entropy Pooling views / stress-testing in Python.
* [PerformanceAnalytics](https://github.com/braverock/PerformanceAnalytics) ⭐ 239 | 🐛 6 | 🌐 R | 📅 2026-04-13 - `R` - Econometric tools for performance and risk analysis.
* [portfolio-allocation](https://github.com/lequant40/portfolio_allocation_js) ⭐ 187 | 🐛 3 | 🌐 JavaScript | 📅 2023-03-03 - `JavaScript` - PortfolioAllocation is a JavaScript library designed to help constructing financial portfolios made of several assets: bonds, commodities, cryptocurrencies, currencies, exchange traded funds (ETFs), mutual funds, stocks...
* [visualize-wealth](https://github.com/benjaminmgross/visualize-wealth) ⭐ 150 | 🐛 0 | 🌐 Python | 📅 2015-06-10 - `Python` - Portfolio construction and quantitative analysis.
* [riskParityPortfolio](https://github.com/dppalomar/riskParityPortfolio) ⭐ 122 | 🐛 9 | 🌐 R | 📅 2022-11-15 - `R` - Blazingly fast design of risk parity portfolios.
* [empyrical-reloaded](https://github.com/stefan-jansen/empyrical-reloaded) ⭐ 121 | 🐛 6 | 🌐 Python | 📅 2025-12-12 - `Python` - Common financial risk and performance metrics. [empyrical](https://github.com/quantopian/empyrical) ⭐ 1,509 | 🐛 37 | 🌐 Python | 📅 2024-07-26 fork.
* [VisualPortfolio](https://github.com/wegamekinglc/VisualPortfolio) ⭐ 107 | 🐛 0 | 🌐 Python | 📅 2017-02-28 - `Python` - This tool is used to visualize the performance of a portfolio.
* [PortfolioAnalytics](https://github.com/braverock/PortfolioAnalytics) ⭐ 106 | 🐛 7 | 🌐 PostScript | 📅 2026-07-24 - `R` - Portfolio Analysis, Including Numerical Methods for Optimizationof Portfolios.
* [OptimalPortfolios](https://github.com/ArturSepp/OptimalPortfolios) ⭐ 93 | 🐛 2 | 🌐 Python | 📅 2026-08-28 - `Python` - Optimisation analytics for constructing and backtesting optimal multi-asset portfolios: covariance estimation, rolling optimisation, and performance reporting in one pipeline.
* [AutoHypothesis](https://github.com/arteemg/AutoHypothesis) ⭐ 71 | 🐛 0 | 🌐 Python | 📅 2026-04-29 - `Python` - An agentic framework that mimics the real quant trading pipeline to find alpha: economic hypothesis, in-sample iteration, and out-of-sample validation.
* [sparseIndexTracking](https://github.com/dppalomar/sparseIndexTracking) ⭐ 59 | 🐛 3 | 🌐 HTML | 📅 2023-05-28 - `R` - Portfolio design to track an index.
* [risktools](https://github.com/bbcho/risktools-dev) ⭐ 43 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2026-02-11 - `Python` - Risk tools for use within the crude and crude products trading space with partial implementation of R's PerformanceAnalytics.
* [factorlasso](https://github.com/ArturSepp/factorlasso) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2026-08-28 - `Python` - Sparse multi-asset factor models with cell-level sign constraints, prior-centred shrinkage, and hierarchical clustering group LASSO (HCGL); scikit-learn compatible.
* [QuantLibRisks](https://github.com/auto-differentiation/QuantLib-Risks-Py) ⭐ 21 | 🐛 5 | 🌐 Python | 📅 2026-04-02 - `Python` - Fast risks with QuantLib.
* [XAD](https://github.com/auto-differentiation/xad-py) ⭐ 20 | 🐛 12 | 🌐 Python | 📅 2026-04-02 - `Python` - Automatic Differentation (AAD) Library.
* [portfolio](https://github.com/dgerlanc/portfolio) ⭐ 17 | 🐛 0 | 🌐 R | 📅 2024-08-19 - `R` - Analysing equity portfolios.
* [RiskPerf.jl](https://github.com/rbeeli/RiskPerf.jl) ⭐ 16 | 🐛 0 | 🌐 Julia | 📅 2026-07-30 - `Julia` - Quantitative risk and performance analysis package for financial time series powered by the Julia language.
* [OnlinePortfolioAnalytics.jl](https://github.com/femtotrader/OnlinePortfolioAnalytics.jl) ⭐ 15 | 🐛 2 | 🌐 Julia | 📅 2026-06-22 - `Julia` - A Julia quantitative portfolio analytics (risk / performance) via online algorithms.
* [goal-based-allocation](https://github.com/ArturSepp/GoalBasedAllocation) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-08-28 - `Python` - Dynamic mean-variance portfolio allocation under regime-switching jump-diffusions with wealth floors, solved analytically via Laplace transforms.
* [etfray](https://github.com/alwank/etfray) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-06-01 - `Python` - Terminal-based ETF research and portfolio analytics application for holdings, exposure, concentration, margin, and risk workflows.
* [quantitative-finance-tools](https://github.com/omichauhan-lgtm/quantitative-finance-tools) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-12-13 - `Python` - Library for portfolio optimization (MVO) and rigorous risk metrics (VaR/CVaR).
* [fincore](https://github.com/cloudQuant/fincore) ⭐ 4 | 🐛 8 | 🌐 Python | 📅 2026-08-26 - `Python` - Quantitative performance and risk analytics with 150+ metrics, portfolio optimization, Monte Carlo simulation, and attribution; actively maintained successor to [empyrical](https://github.com/quantopian/empyrical) ⭐ 1,509 | 🐛 37 | 🌐 Python | 📅 2024-07-26/[pyfolio](https://github.com/quantopian/pyfolio) ⭐ 6,410 | 🐛 166 | 🌐 Jupyter Notebook | 📅 2023-12-23.
* [rebalance](https://github.com/cjroth/rebalance) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-02 - `JavaScript` - Interactive portfolio rebalancing tool that imports brokerage CSV data, sets target allocations, and generates trade instructions.
* [Multi-Axis Robust Portfolio Optimization](https://github.com/Viraj-Nigwekar/multi-axis-robust-portfolio-optimization) ⭐ 2 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-07-31 - `Python` - Portfolio optimization framework combining covariance shrinkage, bootstrap aggregation, and parametric scenario modeling, with reproducible notebooks and an accompanying SSRN paper.
* [riskkit](https://github.com/HasibVortex369/riskkit) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-07-02 - `Python` - Framework-agnostic risk-management toolkit for systematic trading — position sizing, drawdown control, a composable stop engine, correlation limits, and portfolio exposure caps, with adapters for backtesting.py, freqtrade, and vectorbt.
* [finance](https://pypi.org/project/finance/) - `Python` - Financial Risk Calculations. Optimized for ease of use through class construction and operator overload.
* [qfrm](https://pypi.org/project/qfrm/) - `Python` - Quantitative Financial Risk Management: awesome OOP tools for measuring, managing and visualizing risk of financial instruments and portfolios. (Last updated: 2015-12-12).
* [Prop Trader Compass](https://otto-ships.github.io/prop-trader-compass/) - `Python` - Interactive risk and payout calculator for Futures and CFD traders; features one-time fee firm comparisons.

## Factor Analysis

* [alphalens](https://github.com/quantopian/alphalens) ⭐ 4,434 | 🐛 50 | 🌐 Jupyter Notebook | 📅 2024-02-12 - `Python` - Performance analysis of predictive alpha factors.
* [Spectre](https://github.com/Heerozh/spectre) ⭐ 822 | 🐛 10 | 🌐 Python | 📅 2025-04-15 - `Python` - GPU-accelerated Factors analysis library and Backtester.
* [alphalens-reloaded](https://github.com/stefan-jansen/alphalens-reloaded) ⭐ 638 | 🐛 14 | 🌐 Python | 📅 2025-12-15 - `Python` - Performance analysis of predictive (alpha) stock factors.
* [QuantGPT](https://github.com/Miasyster/QuantGPT) ⭐ 456 | 🐛 4 | 🌐 Python | 📅 2026-05-20 - `Python` - Agent-driven A-share factor research engine with 8 MCP tools covering hypothesis design, backtesting, scoring, and anti-overfit detection.
* [Alpha Skills](https://github.com/VernonOY/alpha-skills) ⭐ 99 | 🐛 0 | 📅 2026-04-14 - `Python` - AI skills for quantitative factor research: discover, evaluate, mine, backtest, and monitor factors through any AI coding assistant. Supports A-share, HK, and US markets.
* [FactorAnalytics](https://github.com/braverock/FactorAnalytics) ⭐ 86 | 🐛 24 | 🌐 R | 📅 2024-12-12 - `R` - The FactorAnalytics package contains fitting and analysis methods for the three main types of factor models used in conjunction with portfolio construction, optimization and risk management, namely fundamental factor models, time series factor models and statistical factor models.
* [ml-quant-trading](https://github.com/initial-d/ml-quant-trading) ⭐ 80 | 🐛 4 | 🌐 Python | 📅 2026-08-26 - `Python` - PyTorch research stack for multi-factor analysis, bias correction, portfolio optimization, and reproducible backtesting.
* [Expected Returns](https://github.com/JustinMShea/ExpectedReturns) ⭐ 58 | 🐛 14 | 🌐 HTML | 📅 2025-08-12 - `R` - Solutions for enhancing portfolio diversification and replications of seminal papers with R, most of which are discussed in one of the best investment references of the recent decade, Expected Returns: An Investors Guide to Harvesting Market Rewards by Antti Ilmanen.
* [covFactorModel](https://github.com/dppalomar/covFactorModel) ⭐ 39 | 🐛 0 | 🌐 R | 📅 2019-03-25 - `R` - Covariance matrix estimation via factor models.
* [quant-lab-alpha](https://github.com/husainm97/quant-lab-alpha) ⭐ 35 | 🐛 2 | 🌐 Python | 📅 2026-05-17 - `Python` - Open-source investment analytics platform bridging academic research and retail finance.
* [Perception-XAlpha Lite](https://github.com/xuxingjiankr-cpu/perception-xalpha-lite) ⭐ 2 | 🐛 7 | 🌐 Python | 📅 2026-08-24 - `Python` - Backtest-overfitting audit for factor research: CSCV probability of backtest overfitting, deflated Sharpe against the declared trial count, White's Reality Check, point-in-time universe membership and disclosure-date alignment. Ships a worked example in which 24 pure-noise series produce a 1.11 Sharpe and the audit says so.
* [pit-release-gate](https://github.com/MaxWellApexLab/pit-release-gate) ⭐ 0 | 🐛 9 | 🌐 Python | 📅 2026-08-17 - `Python` - Screens cross-sectional signals for incomplete-cross-section leakage from staggered data arrival and grades per-signal release timing; ships a known-ground-truth demo reproducing its method papers.

## Sentiment Analysis & Alternative Data

* [Asset News Sentiment Analyzer](https://github.com/KVignesh122/AssetNewsSentimentAnalyzer) ⭐ 198 | 🐛 0 | 🌐 Python | 📅 2026-07-15 - `Python` - Sentiment analysis and report generation package for financial assets and securities utilizing GPT models.
* [CoWorker Fin-Agent](https://github.com/ZiwayZhao/agent-coworker) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2026-04-04 - `Python` - LLM-powered A-share stock analysis via P2P agent collaboration. Technical analysis (MA60, volume-price patterns, golden eye), deep research reports using proprietary methodology, and market state summaries. Analysis logic stays private via Skill-as-API protocol.
* [StockKit](https://stockkit.net/) - `TypeScript` - Free AI-powered stock research reports for US, China & HK using Claude Opus and multi-model AI with 20+ technical indicators. [GitHub](https://github.com/kentmswood-ui/stockkit) ⭐ 2 | 🐛 0 | 📅 2026-05-07
* [AlphaAI](https://alphai.io/developers) - `Python` - Pre-analyzed financial news via REST API and MCP for AI agents: per-ticker impact and sentiment, a category, and a 1-10 relevance score on every story, plus structured SEC Form 4 insider data. Free tier, no card. [GitHub](https://github.com/makeev/alphai-mcp) ⭐ 2 | 🐛 0 | 📅 2026-08-15
* [Social Stock Sentiment API](https://api.adanos.org/docs) - `Python` - REST API analyzing Reddit and X/Twitter for stock mentions and sentiment, providing buzz scores, trending stocks, and AI-generated trend explanations.

## Time Series Analysis

* [Facebook Prophet](https://github.com/facebook/prophet) ⭐ 20,379 | 🐛 452 | 🌐 Python | 📅 2026-08-27 - `Python` - Tool for producing high quality forecasts for time series data that has multiple seasonality with linear or non-linear growth.
* [statsmodels](http://statsmodels.sourceforge.net) - `Python` - Python module that allows users to explore data, estimate statistical models, and perform statistical tests. [GitHub](https://github.com/statsmodels/statsmodels) ⭐ 11,598 | 🐛 2,807 | 🌐 Python | 📅 2026-08-27
* [tsfresh](https://github.com/blue-yonder/tsfresh) ⭐ 9,301 | 🐛 74 | 🌐 Jupyter Notebook | 📅 2026-07-06 - `Python` - Automatic extraction of relevant features from time series.
* [gluon-ts](https://github.com/awslabs/gluon-ts) ⭐ 5,232 | 🐛 477 | 🌐 Python | 📅 2026-07-31 - `Python` - vProbabilistic time series modeling in Python.
* [PyFlux](https://github.com/RJT1990/pyflux) ⭐ 2,134 | 🐛 93 | 🌐 Python | 📅 2023-10-24 - `Python` - Python library for timeseries modelling and inference (frequentist and Bayesian) on models.
* [pmdarima](https://github.com/alkaline-ml/pmdarima) ⭐ 1,734 | 🐛 65 | 🌐 Python | 📅 2025-11-17 - `Python` - A statistical library designed to fill the void in Python's time series analysis capabilities, including the equivalent of R's auto.arima function.
* [ARCH](https://github.com/bashtage/arch) ⭐ 1,558 | 🐛 51 | 🌐 Python | 📅 2026-08-10 - `Python` - ARCH models in Python.
* [functime](https://github.com/functime-org/functime) ⭐ 1,184 | 🐛 56 | 🌐 Python | 📅 2026-05-03 - `Python` - Time-series machine learning at scale. Built with Polars for embarrassingly parallel feature extraction and forecasts on panel data.
* [tidyquant](https://github.com/business-science/tidyquant) ⭐ 914 | 🐛 95 | 🌐 R | 📅 2026-08-01 - `R` - Bringing financial analysis to the tidyverse.
* [tsmoothie](https://github.com/cerlymarco/tsmoothie) ⭐ 770 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-11-23 - `Python` - A python library for time-series smoothing and outlier detection in a vectorized way.
* [timetk](https://github.com/business-science/timetk) ⭐ 644 | 🐛 43 | 🌐 R | 📅 2025-08-29 - `R` - A toolkit for working with time series in R.
* [matrixprofile](https://github.com/matrix-profile-foundation/matrixprofile) ⭐ 384 | 🐛 31 | 🌐 Python | 📅 2023-11-29 - `R` - Time series data mining library built on top of the novel Matrix Profile data structure and algorithms.
* [TimeSeries.jl](https://github.com/JuliaStats/TimeSeries.jl) ⭐ 369 | 🐛 48 | 🌐 Julia | 📅 2026-03-30 - `Julia` - Time series toolkit for Julia.
* [PineForge](https://github.com/pineforge-4pass/pineforge-engine) ⭐ 179 | 🐛 2 | 🌐 C++ | 📅 2026-08-25 - `C++` - Deterministic offline PineScript v6 → C++ backtest runtime, validated trade-for-trade against TradingView (245/246 strict, 0 engine bugs). Runs locally via Docker and is drivable by AI agents through a bundled MCP server.
* [tibbletime](https://github.com/business-science/tibbletime) ⭐ 176 | 🐛 0 | 🌐 R | 📅 2024-12-03 - `R` - Built on top of the tidyverse, tibbletime is an extension that allows for the creation of time aware tibbles through the setting of a time index.
* [dynts](https://github.com/quantmind/dynts) ⚠️ Archived - `Python` - Python package for timeseries analysis and manipulation.
* [garchmodels](https://github.com/AlbertoAlmuinha/garchmodels) ⭐ 37 | 🐛 6 | 🌐 R | 📅 2022-08-11 - `R` - A parsnip backend for GARCH models.
* [rugarch](https://github.com/alexiosg/rugarch) ⭐ 32 | 🐛 1 | 🌐 R | 📅 2026-07-18 - `R` - Univariate GARCH Models.
* [rmgarch](https://github.com/alexiosg/rmgarch) ⭐ 18 | 🐛 3 | 🌐 R | 📅 2025-08-31 - `R` - Multivariate GARCH Models.
* [OmniOracle](https://github.com/cesabici-bit/omni-oracle) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2026-03-23 - `Python` - Automatic discovery of non-trivial statistical relationships across 500+ time series from FRED, World Bank, EIA, and NOAA using mutual information screening, lagged MI directional testing, and FDR correction.
* [TimeFrames.jl](https://github.com/femtotrader/TimeFrames.jl) ⭐ 5 | 🐛 15 | 🌐 Julia | 📅 2026-06-22 - `Julia` - A Julia library that defines TimeFrame (essentially for resampling TimeSeries).
* [etf-pattern-match-pybind11](https://github.com/redamancy231-create/etf-pattern-match-pybind11) ⭐ 4 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-15 - `Python` `C++` - High-performance ETF pattern matching via DTW with cosine pre-filtering. 43× DTW and 58× pattern-match speedup over pure Python using pybind11/C++20. Includes Jupyter notebook with full algorithm walkthrough.
* [wasserstein-btc](https://github.com/AccursedGalaxy/wasserstein-btc) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2026-06-04 - `Python` - Distributional forecasting of crypto log-returns by tangent-space geodesic extrapolation on the 2-Wasserstein manifold (quantile-function coordinates). Walk-forward CRPS evaluation over 6.75 years across 4 assets × 3 horizons; benchmarked against classical baselines (Static / RW-Drift / HS-Bootstrap / GARCH-N / GARCH-t / GJR-GARCH-t) and a named-econometric panel (HAR-RV, CAViaR-SAV, Markov-switching Normal, FIGARCH, AR(1) Stochastic Volatility, bivariate VAR+GARCH). [Live dashboard](https://accursedgalaxy.github.io/wasserstein-btc/).
* [tidypredict](https://github.com/edgararuiz/tidypredict) ⭐ 3 | 🐛 0 | 🌐 R | 📅 2021-10-07 - `R` - Run predictions inside the database <https://tidypredict.netlify.com/>.
* [tseries](https://cran.r-project.org/web/packages/tseries/index.html) - `R` - Time Series Analysis and Computational Finance.
* [fGarch](https://cran.r-project.org/web/packages/fGarch/index.html) - `R` - Rmetrics - Autoregressive Conditional Heteroskedastic Modelling.
* [timeSeries](https://cran.r-project.org/web/packages/timeSeries/index.html) - `R` - Rmetrics - Financial Time Series Objects.

## Market Data & Data Sources

* [OpenBB Terminal](https://github.com/OpenBB-finance/OpenBBTerminal) ⭐ 72,414 | 🐛 107 | 🌐 Python | 📅 2026-07-30 - `Python` - Terminal for investment research for everyone.
* [Fincept Terminal](https://github.com/Fincept-Corporation/FinceptTerminal) ⭐ 30,754 | 🐛 12 | 🌐 C++ | 📅 2026-08-20 - `Python` - Advance Data Based A.I Terminal for all Types of Financial Asset Research.
* [yfinance](https://github.com/ranaroussi/yfinance) ⭐ 25,099 | 🐛 104 | 🌐 Python | 📅 2026-08-27 - `Python` - Yahoo! Finance market data downloader (+faster Pandas Datareader).
* [akshare](https://github.com/jindaxiang/akshare) ⭐ 22,287 | 🐛 1 | 🌐 Python | 📅 2026-08-28 - `Python` - AkShare is an elegant and simple financial data interface library for Python, built for human beings! <https://akshare.readthedocs.io>.
* [FinanceDatabase](https://github.com/JerBouma/FinanceDatabase) ⭐ 8,400 | 🐛 4 | 🌐 Python | 📅 2026-08-25 - `Python` - This is a database of 300.000+ symbols containing Equities, ETFs, Funds, Indices, Currencies, Cryptocurrencies and Money Markets.
* [FinanceToolkit](https://github.com/JerBouma/FinanceToolkit) ⭐ 5,270 | 🐛 5 | 🌐 Python | 📅 2026-08-27 - `Python` - Toolkit with 200+ financial metrics including 80+ financial ratios, 30+ technical indicators, 20+ risk and performance metrics and 50+ macro indicators which pulls from Financial Modeling Prep, Yahoo Finance, OECD, GMBD and more.
* [alpha\_vantage](https://github.com/RomelTorres/alpha_vantage) ⭐ 4,900 | 🐛 3 | 🌐 Python | 📅 2026-07-26 - `Python` - A python wrapper for Alpha Vantage API for financial data.
* [pandas-datareader](https://github.com/pydata/pandas-datareader) ⭐ 3,238 | 🐛 147 | 🌐 Python | 📅 2026-07-21 - `Python` - Python module to get data from various sources (Google Finance, Yahoo Finance, FRED, OECD, Fama/French, World Bank, Eurostat...) into Pandas datastructures such as DataFrame, Panel with a caching mechanism.
* [edgartools](https://github.com/dgunning/edgartools) ⭐ 2,631 | 🐛 25 | 🌐 Python | 📅 2026-08-26 - `Python` - AI-native SEC EDGAR library with XBRL financials, clean text extraction, 17+ typed forms, and pandas DataFrames.
* [findatapy](https://github.com/cuemacro/findatapy) ⭐ 2,109 | 🐛 28 | 🌐 Python | 📅 2026-07-02 - `Python` - Python library to download market data via Bloomberg, Quandl, Yahoo etc.
* [alpaca-trade-api](https://github.com/alpacahq/alpaca-trade-api-python) ⚠️ Archived - `Python` - Python interface for retrieving real-time and historical prices from Alpaca API as well as trade execution.
* [investpy](https://github.com/alvarobartt/investpy) ⭐ 1,852 | 🐛 244 | 🌐 Python | 📅 2026-04-13 - `Python` - Financial Data Extraction from Investing.com with Python! <https://investpy.readthedocs.io/>.
* [wallstreet](https://github.com/mcdallas/wallstreet) ⭐ 1,690 | 🐛 18 | 🌐 Python | 📅 2024-07-06 - `Python` - Real time stock and option data.
* [pytdx](https://github.com/rainx/pytdx) ⚠️ Archived - `Python` - Python Interface for retrieving chinese stock realtime quote data from TongDaXin Nodes.
* [FinanceDataReader](https://github.com/FinanceData/FinanceDataReader) ⭐ 1,536 | 🐛 50 | 🌐 Python | 📅 2026-05-13 - `Python` - Open Source Financial data reader for U.S, Korean, Japanese, Chinese, Vietnamese Stocks.
* [polygon.io](https://github.com/polygon-io/client-python) ⭐ 1,502 | 🐛 24 | 🌐 Python | 📅 2026-07-09 - `Python` - A python library for Polygon.io financial data APIs.
* [yahoo-finance](https://github.com/lukaszbanasiak/yahoo-finance) ⭐ 1,445 | 🐛 88 | 🌐 Python | 📅 2023-12-25 - `Python` - Python module to get stock data from Yahoo! Finance.
* [yahooquery](https://github.com/dpguthrie/yahooquery) ⭐ 919 | 🐛 81 | 🌐 Python | 📅 2025-05-15 - `Python` - Python interface for retrieving data through unofficial Yahoo Finance API.
* [nsetools](https://github.com/vsjha18/nsetools) ⭐ 906 | 🐛 2 | 🌐 Python | 📅 2025-03-18 - `Python` - Python library for extracting real-time data from National Stock Exchange (India).
* [googlefinance](https://github.com/hongtaocai/googlefinance) ⭐ 831 | 🐛 32 | 🌐 Python | 📅 2018-09-23 - `Python` - Python module to get real-time stock data from Google Finance API.
* [defeatbeta-api](https://github.com/defeat-beta/defeatbeta-api) ⭐ 741 | 🐛 4 | 🌐 Python | 📅 2026-08-06 - `Python` - An open-source alternative to Yahoo Finance's market data APIs with higher reliability.
* [iexfinance](https://github.com/addisonlynch/iexfinance) ⚠️ Archived - `Python` - Python Interface for retrieving real-time and historical prices and equities data from The Investor's Exchange.
* [jugaad-data](https://github.com/jugaad-py/jugaad-data) ⭐ 564 | 🐛 26 | 🌐 Python | 📅 2026-08-25 - `Python` - Download historical and live stock data from NSE (National Stock Exchange of India), BSE, and RBI.
* [datamule-python](https://github.com/john-friedman/datamule-python) ⭐ 556 | 🐛 15 | 🌐 Python | 📅 2026-08-14 - `Python` - A package to work with SEC data. Incorporates datamule endpoints.
* [finagg](https://github.com/theOGognf/finagg) ⭐ 540 | 🐛 0 | 🌐 Python | 📅 2026-03-22 - `Python` - finagg is a Python package that provides implementations of popular and free financial APIs, tools for aggregating historical data from those APIs into SQL databases, and tools for transforming aggregated data into features useful for analysis and AI/ML.
* [ystockquote](https://github.com/cgoldberg/ystockquote) ⚠️ Archived - `Python` - Retrieve stock quote data from Yahoo Finance.
* [coinmarketcap](https://github.com/barnumbirr/coinmarketcap) ⚠️ Archived - `Python` - Python API for coinmarketcap.
* [pyEX](https://github.com/timkpaine/pyEX) ⚠️ Archived - `Python` - Python interface to IEX with emphasis on pandas, support for streaming data, premium data, points data (economic, rates, commodities), and technical indicators.
* [Trading Strategy](https://github.com/tradingstrategy-ai/trading-strategy/) ⭐ 377 | 🐛 11 | 🌐 Python | 📅 2026-08-10 - `Python` - download price data for decentralised exchanges and lending protocols (DeFi).
* [tiingo](https://github.com/hydrosquall/tiingo-python) ⭐ 317 | 🐛 35 | 🌐 Python | 📅 2025-12-14 - `Python` - Python interface for daily composite prices/OHLC/Volume + Real-time News Feeds, powered by the Tiingo Data Platform.
* [pdblp](https://github.com/matthewgilbert/pdblp) ⭐ 256 | 🐛 38 | 🌐 Python | 📅 2024-12-14 - `Python` - A simple interface to integrate pandas and the Bloomberg Open API.
* [lse-data](https://github.com/londonstrategicedge/lse-data) ⭐ 216 | 🐛 6 | 🌐 Python | 📅 2026-08-02 - `Python` - Live ticks over WebSocket plus historical ticks and candles for stocks, FX, crypto, commodities, indices, ETFs and futures, with options chains and greeks, economics series and government bond yields, across 118,000+ datasets. US stocks from 2003, FX from 2009, options from 2014, economics back to 1900. Free, no subscription tiers. [PyPI](https://pypi.org/project/lse-data/)
* [FRB](https://github.com/avelkoski/FRB) ⭐ 181 | 🐛 9 | 🌐 Python | 📅 2023-07-07 - `Python` - Python Client for FRED® API.
* [Rblpapi](https://github.com/Rblp/Rblpapi) ⭐ 176 | 🐛 39 | 🌐 C++ | 📅 2026-08-02 - `R` - An R Interface to 'Bloomberg' is provided via the 'Blp API'.
* [yliveticker](https://github.com/yahoofinancelive/yliveticker) ⭐ 172 | 🐛 0 | 🌐 Python | 📅 2026-03-28 - `Python` - Live stream of market data from Yahoo Finance websocket.
* [MarketData.jl](https://github.com/JuliaQuant/MarketData.jl) ⭐ 165 | 🐛 11 | 🌐 Julia | 📅 2026-03-30 - `Julia` - Time series market data.
* [pandas-finance](https://github.com/davidastephens/pandas-finance) ⭐ 160 | 🐛 5 | 🌐 Python | 📅 2025-03-07 - `Python` - High level API for access to and analysis of financial data.
* [tardis-python](https://github.com/tardis-dev/tardis-python) ⭐ 147 | 🐛 0 | 🌐 Python | 📅 2026-08-23 - `Python` - Python interface for Tardis.dev high frequency crypto market data.
* [pandaSDMX](https://github.com/dr-leo/pandaSDMX) ⭐ 134 | 🐛 21 | 🌐 Python | 📅 2023-12-28 - `Python` - Python package that implements SDMX 2.1 (ISO 17369:2013), a format for exchange of statistical data and metadata used by national statistical agencies, central banks, and international organisations.
* [python-bcb](https://github.com/wilsonfreitas/python-bcb) ⭐ 126 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2026-07-27 - `Python` - Python interface to Brazilian Central Bank web services.
* [finsymbols](https://github.com/skillachie/finsymbols) ⭐ 123 | 🐛 10 | 🌐 Python | 📅 2019-11-10 - `Python` - Obtains stock symbols and relating information for SP500, AMEX, NYSE, and NASDAQ.
* [market-prices](https://github.com/maread99/market_prices) ⭐ 105 | 🐛 10 | 🌐 Python | 📅 2026-08-14 - `Python` - Create meaningful OHLCV datasets from knowledge of [exchange-calendars](https://github.com/gerrymanoim/exchange_calendars) ⭐ 664 | 🐛 26 | 🌐 Python | 📅 2026-08-14 (works out-the-box with data from Yahoo Finance).
* [rb3](https://github.com/ropensci/rb3) ⭐ 102 | 🐛 25 | 🌐 R | 📅 2025-11-01 - `R` - A bunch of downloaders and parsers for data delivered from B3.
* [rbcb](https://github.com/wilsonfreitas/rbcb) ⭐ 98 | 🐛 10 | 🌐 R | 📅 2024-01-23 - `R` - R interface to Brazilian Central Bank web services.
* [ccy](https://github.com/lsbardel/ccy) ⭐ 97 | 🐛 5 | 🌐 Python | 📅 2026-04-25 - `Python` - Python module for currencies.
* [lake-api](https://github.com/crypto-lake/lake-api) ⭐ 76 | 🐛 3 | 🌐 Python | 📅 2025-11-02 - `Python` - Python interface for Crypto Lake high frequency crypto market data.
* [finalytics](https://github.com/Nnamdi-sys/finalytics) ⭐ 74 | 🐛 2 | 🌐 Rust | 📅 2026-05-01 - `Rust` - A rust library for financial data analysis.
* [cif](https://github.com/LenkaV/CIF) ⭐ 66 | 🐛 10 | 🌐 Python | 📅 2022-06-18 - `Python` - Python package that include few composite indicators, which summarize multidimensional relationships between individual economic indicators.
* [Rbitcoin](https://github.com/jangorecki/Rbitcoin) ⚠️ Archived - `R` - Unified markets API interface (bitstamp, kraken, btce, bitmarket).
* [inquisitor](https://github.com/econdb/inquisitor) ⚠️ Archived - `Python` - Python Interface to Econdb.com API.
* [tessa](https://github.com/ymyke/tessa) ⭐ 54 | 🐛 1 | 🌐 Python | 📅 2026-04-09 - `Python` - simple, hassle-free access to price information of financial assets (currently based on yfinance and pycoingecko), including search and a symbol class.
* [pybbg](https://github.com/bpsmith/pybbg) ⭐ 53 | 🐛 2 | 🌐 Python | 📅 2015-01-20 - `Python` - Python interface to Bloomberg COM APIs.
* [stock\_extractor](https://github.com/ZachLiuGIS/stock_extractor) ⭐ 52 | 🐛 4 | 🌐 Python | 📅 2022-12-26 - `Python` - General Purpose Stock Extractors from Online Resources.
* [PENDAX](https://github.com/CompendiumFi/PENDAX-SDK) ⭐ 50 | 🐛 1 | 📅 2024-05-09 - `JavaScript` - Javascript SDK for Trading/Data API and Websockets for FTX, FTXUS, OKX, Bybit, & More.
* [GetHFData](https://github.com/msperlin/GetHFData) ⚠️ Archived - `R` - Downloads and aggregates high frequency trading data for Brazilian instruments directly from Bovespa ftp site.
* [pricehub](https://github.com/eslazarev/pricehub) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2026-06-17 - `Python` - Unified package for collecting OHLC prices from Binance, Bybit, Coinbase, OKX, Kraken, KuCoin, and Bitget (spot & futures) into a DataFrame, with flexible timestamp inputs and a wide range of intervals.
* [after-hours](https://github.com/datawrestler/after-hours) ⚠️ Archived - `Python` - Obtain pre market and after hours stock prices for a given symbol.
* [EarningsCall](https://github.com/EarningsCall/earningscall-python) ⭐ 35 | 🐛 4 | 🌐 Python | 📅 2026-07-21 - `Python` - REST API and Python/JavaScript SDK for earnings call transcripts, audio files, and slide decks for 9,000+ public companies. Includes speaker-level data, Q\&A segmentation, and earnings calendar.
* [cn\_stock\_src](https://github.com/jealous/cn_stock_src) ⭐ 34 | 🐛 0 | 🌐 HTML | 📅 2016-11-09 - `Python` - Utility for retrieving basic China stock data from different sources.
* [Stockex](https://github.com/cttn/Stockex) ⭐ 33 | 🐛 2 | 🌐 Python | 📅 2023-05-22 - `Python` - Python wrapper for Yahoo! Finance API.
* [CryptoExchangeAPIs.jl](https://github.com/bhftbootcamp/CryptoExchangeAPIs.jl) ⭐ 30 | 🐛 2 | 🌐 Julia | 📅 2026-07-06 - `Julia` - A Julia library for cryptocurrency exchange APIs.
* [GetTDData](https://github.com/msperlin/GetTDData) ⭐ 28 | 🐛 3 | 🌐 R | 📅 2026-06-04 - `R` - Downloads and aggregates data for Brazilian government issued bonds directly from the website of Tesouro Direto.
* [tidyfinance](https://github.com/tidy-finance/r-tidyfinance) ⭐ 26 | 🐛 1 | 🌐 R | 📅 2026-08-06 - `R` - Tidy Finance helper functions to download financial data and process the raw data into a structured Format (tidy data), including.
* [CcyConv.jl](https://github.com/bhftbootcamp/CcyConv.jl) ⭐ 25 | 🐛 0 | 🌐 Julia | 📅 2026-07-03 - `Julia` - Currency conversion library for Julia.
* [SwapAPI](https://github.com/swap-api/swap-api) ⭐ 22 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-03 - `Python` - Free DEX aggregator API returning executable swap calldata across 46 EVM chains. No API key required.
* [pystlouisfed](https://github.com/TomasKoutek/pystlouisfed) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2024-01-09 - `Python` - Python client for Federal Reserve Bank of St. Louis API - FRED, ALFRED, GeoFRED and FRASER.
* [simfinapi](https://github.com/matthiasgomolka/simfinapi) ⭐ 21 | 🐛 9 | 🌐 R | 📅 2025-08-13 - `R` - Makes 'SimFin' data (<https://simfin.com/>) easily accessible in R.
* [Chart Library](https://github.com/grahammccain/chart-library-mcp) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-06-10 - `Python` - Historical chart pattern similarity search API. 24M+ pre-computed embeddings across 15K+ symbols and 10 years of data using pgvector. Returns forward returns, regime analysis, and pattern detection. Also available as MCP server. [Website](https://chartlibrary.io)
* [coinpaprika-api-python-client](https://github.com/coinpaprika/coinpaprika-api-python-client) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2026-08-06 - `Python` - Free crypto market data API client. 12,000+ coins, 350+ exchanges, tickers, OHLCV, historical prices. No API key for free tier.
* [BloombergFetch](https://github.com/ArturSepp/BloombergFetch) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2026-08-28 - `Python` - Bloomberg Desktop API data (prices, implied volatilities, fundamentals) as pandas DataFrames via blpapi.
* [td](https://github.com/eddelbuettel/td) ⭐ 19 | 🐛 0 | 🌐 R | 📅 2026-02-12 - `R` - Interfaces the 'twelvedata' API for stocks and (digital and standard) currencies.
* [exchange](https://github.com/akarat/exchange) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2015-07-07 - `Python` - Get current exchange rate.
* [edinet-mcp](https://github.com/ajtgjmdjp/edinet-mcp) ⭐ 18 | 🐛 6 | 🌐 Python | 📅 2026-08-24 - `Python` - Parse Japanese XBRL financial statements from EDINET with 161 normalized labels, 26 financial metrics, and multi-company screening.
* [yql-finance](https://github.com/slawek87/yql-finance) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2015-08-29 - `Python` - yql-finance is simple and fast. API returns stock closing prices for current period of time and current stock ticker (i.e. APPL, GOOGL).
* [ticks](https://github.com/jamescnowell/ticks) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2016-01-08 - `Python` - Simple command line tool to get stock ticker data.
* [dexpaprika-sdk-python](https://github.com/coinpaprika/dexpaprika-sdk-python) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-08-26 - `Python` - Free DEX data API client. 36 blockchains, 36M+ pools, 33M+ tokens, real-time SSE streaming, OHLCV. No API key needed.
* [fin-stream](https://github.com/Mattbusel/fin-stream) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-03-23 - `Rust` - Real-time market data streaming in Rust: lock-free SPSC ring buffer, 100K+ ticks/second ingestion, multi-timeframe OHLCV construction, and Lorentz transforms on financial time series.
* [pyhoofinance](https://github.com/innes213/pyhoofinance) ⚠️ Archived - `Python` - Rapidly queries Yahoo Finance for multiple tickers and returns typed data for analysis.
* [yfinanceapi](https://github.com/Karthik005/yfinanceapi) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2020-05-26 - `Python` - Finance API for Python.
* [FXMacroData](https://fxmacrodata.com/) - `Python` - Real-time forex macroeconomic API for all major currency pairs sourced from central bank announcements. [GitHub](https://github.com/fxmacrodata/fxmacrodata) ⭐ 9 | 🐛 3 | 🌐 Python | 📅 2026-07-15
* [estat-mcp](https://github.com/ajtgjmdjp/estat-mcp) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-08-23 - `Python` - Access Japanese government statistics (e-Stat) covering population, GDP, CPI, labor, and trade data with MCP integration and Polars export.
* [fsynth](https://github.com/welcra/fsynth) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-12-27 - `Python` - Python library for high-fidelity unlimited synthetic financial data generation using Heston Stochastic Volatility and Merton Jump Diffusion.
* [Korea Stock Data](https://github.com/na77tech-creator/aikstockdata) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-28 - `Data` - Free Korean equity data: KOSPI/KOSDAQ settled closes with 250 trading days of per-stock history, DART regulatory filings and earnings, published every trading day as JSON/CSV. No signup or API key, CORS open. OpenAPI 3.1 spec and MCP server included.
* [BTC Orderbook Microstructure Research](https://github.com/whoareunot/btc-orderbook-research) ⭐ 7 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-04-21 - `Jupyter Notebook` - statistical analysis of Binance BTC/USDT orderbook: OBI, CVD, spread.
* [OpenChainBench](https://openchainbench.com) - `Go` `TypeScript` - Continuous open-source benchmarks for blockchain RPC latency (22 EVM chains + Solana), perp DEX all-in cost (fees + funding), bridge quote fees, and oracle deviation across Chainlink/Pyth/Redstone. MIT licensed, no API key. [GitHub](https://github.com/ChainBench/OpenChainBench) ⭐ 6 | 🐛 8 | 🌐 Go | 📅 2026-08-28
* [financekit-mcp](https://github.com/vdalhambra/financekit-mcp) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-04-17 - `Python` - MCP server (Model Context Protocol) exposing 17 tools for AI agents to perform quantitative analysis: real-time stock quotes, full technical analysis (RSI, MACD, Bollinger, ADX, Stochastic, ATR, OBV + pattern detection with structured verdicts), crypto prices via CoinGecko, risk metrics (VaR, Sharpe, Sortino, Beta, Max Drawdown), correlation matrix, options chains, earnings calendar, sector rotation, and portfolio analysis. Works with Claude Desktop, Cursor, Windsurf. No API keys for core tools. FastMCP 3.2.
* [tdnet-disclosure-mcp](https://github.com/ajtgjmdjp/tdnet-disclosure-mcp) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-08-23 - `Python` - Access Japanese timely disclosures (TDNet) via MCP. Retrieve earnings, dividends, forecasts, buybacks, and other filings for 4,000+ listed companies. No API key required.
* [swiss-finance-data](https://github.com/EMen11/swiss-finance-data) ⭐ 5 | 🐛 5 | 🌐 HTML | 📅 2026-04-13 - `Python` - Python package for Swiss financial data (SNB Policy Rate, SARON, CHF FX rates, CPI, SMI equities, Confederation bond yields) from official SNB sources.
* [PreReason](https://github.com/PreReason/mcp) ⭐ 5 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-19 - `JavaScript` - Pre-analyzed Bitcoin and macro market briefings for AI agents. 17 contexts with trend signals, confidence scores, and regime classification via REST API and MCP.
* [disclosure-alpha](https://github.com/alwank/disclosure-alpha) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-06-30 - `Python` - Deterministic SEC filing analytics for 10-K/10-Q: section extraction, tone and boilerplate metrics, year-over-year diff, and reproducible disclosure risk scores. CLI, Python SDK, HTTP panel screener, and MCP — no LLM required.
* [bigtech-ai-stakes](https://github.com/YichengYang-Ethan/bigtech-ai-stakes) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-05-09 - `Python` - Open dataset of U.S. public-company equity stakes in Anthropic and OpenAI from primary 10-K / 10-Q / 8-K filings, court records, and press releases. Each row tagged with a confidence flag (V verified, P probable, S speculative).
* [coinpulse](https://github.com/soutone/coinpulse-python) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-01-09 - `Python` - Python SDK for cryptocurrency portfolio tracking with real-time prices, P/L calculations, and price alerts. Free tier available.
* [finlight](https://finlight.me) - `Python` `TypeScript` - Real-time financial and geopolitical news API with sentiment analysis and entity tagging over REST and WebSocket. [GitHub](https://github.com/jubeiargh/finlight-client-py) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-08-16
* [Tradevo Data](https://github.com/christianpichichero-max/pit-fundamentals) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-08-07 - `Python` - Point-in-time US equity fundamentals from SEC EDGAR that stamp each figure with the date it first became public and flag later restatements, so fundamental backtests avoid lookahead bias; free CC0 sample of 40 large-caps, with a paid JSON API. [Website](https://tradevodata.com)
* [OnlineResamplers.jl](https://github.com/femtotrader/OnlineResamplers.jl) ⭐ 3 | 🐛 2 | 🌐 Julia | 📅 2026-04-20 - `Julia` - High-performance Julia package for real-time resampling of financial market data.
* [Horus Flow](https://github.com/horustechltd/horus-flow-mcp) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-05-16 - `Python` - Sub-second L2 orderflow intelligence MCP server for institutional-grade market microstructure analysis.
* [AlphaSMO](https://github.com/alphasmo/alphasmo-tools) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-12 - `TypeScript` - CLI + MCP server for SEC 13F institutional holdings, Form 4 insider trading, and smart money convergence signals (tickers where hedge funds and company insiders are both buying). Free anonymous tier, no signup required.
* [yfi](https://github.com/nickelkr/yfi) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2016-02-12 - `Python` - Yahoo! YQL library.
* [unirate-api](https://github.com/UniRate-API/unirate-api-python) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-07-08 - `Python` - Client for UniRateAPI providing real-time and historical exchange rates for 170+ fiat and crypto currencies plus VAT rates, with a free tier and no credit card required.
* [SECfinAPI](https://www.secfinapi.com) - `TypeScript` - Standardized SEC EDGAR financials (income statement, balance sheet, cash flow, 40+ ratios) for \~19,000 US public companies, normalized from XBRL. REST API + MCP server for Claude/Cursor. Free tier. [GitHub](https://github.com/michalperni11-gif/secfinapi-mcp) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-03
* [bbgbridge](https://github.com/ran404/bbgbridge) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2020-01-07 - `Python` - Easy to use Bloomberg Desktop API wrapper for Python.
* [oilpriceapi](https://github.com/OilpriceAPI/python-sdk) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-08-23 - `Python` - Python SDK for real-time oil and commodity prices (WTI, Brent, Urals, natural gas, coal) with OpenBB integration.
* [tessera-api](https://github.com/tesseralytics/python-client) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-07-13 - `Python` - Official client for Tessera: order-flow-enriched OHLCV, funding-rate, and positioning datasets built from raw Hyperliquid trades, read straight into Polars or DuckDB over a REST API. [Website](https://tesseralytics.dev)
* [Factor Weave](https://factorweave.com/) - `Python` `TypeScript` `R` - Factor scores, similarity search, and leak-free + survivor-free forward-return labels across equities, ETFs, indices, FX, crypto, and futures; REST + MCP, Python/TypeScript/R SDKs, free tier. [GitHub](https://github.com/Blazing-Customs/factorweave-tools) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2026-06-05
* [treasury-fiscaldata](https://github.com/moshejs/treasury-fiscaldata) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - Typed client for the US Treasury FiscalData API (debt, average interest rates, exchange rates) with pagination and filtering; no API key required.
* [SiftingIO](https://github.com/SiftingIO/sdk-python) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-08-02 - `Python` - A python library for Sifting.io financial market data APIs & Websocket.
* [FilingFirehose](https://filingfirehose.com) - `Python` - SEC EDGAR JSON API + free Forensic risk-scoring tool: body-text-classified 8-Ks flagging buried events (\~7.3% of Item 8.01 filings), Schedule 13D/G with 21+ activist filers auto-tagged, S-3/424B5 ATM offering detection. Free Forensic risk score 0-100 per ticker grounded in cited SEC filings ([leaderboard](https://filingfirehose.com/forensic/leaderboard)). Open-source classifier at [buried-events-parser](https://github.com/jaablon/buried-events-parser) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-06-19. Also exposed as MCP server, ChatGPT GPT, and GitHub Action.
* [veroq-python](https://github.com/Veroq-api/veroq-python) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-03-31 - `Python` - Financial intelligence API with verified market data, trading signals, sentiment analysis, and fact-checking across 1,061+ tickers. [PyPI](https://pypi.org/project/veroq/)
* [AgentServices](https://agentservices.to) - `Python` - x402-paid crypto and market data API platform: 54 services, 97 endpoints, 37 MCP tools. Real-time prices, technical indicators, on-chain data, and market intelligence with on-chain USDC payments on Base. [GitHub](https://github.com/vbkotecha/aiservices-api) ⭐ 1 | 🐛 3 | 🌐 Python | 📅 2026-08-29
* [treasurydirect](https://github.com/moshejs/treasurydirect) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - Zero-dependency client for the US TreasuryDirect API: auction results, upcoming auctions, CUSIP lookups, and Debt to the Penny; no API key required.
* [newyorkfed](https://github.com/moshejs/newyorkfed) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - Client for the NY Fed Markets Data API: SOFR/EFFR/OBFR reference rates, SOFR averages and index, and SOMA holdings; no API key required.
* [commitments-of-traders](https://github.com/moshejs/commitments-of-traders) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - Client for the CFTC Commitments of Traders reports (Legacy, Disaggregated, TFF; futures-only and combined) via the official Socrata API.
* [FillBench](https://fillbench.com) - Reproducible crypto exchange REST API latency benchmarks (p50/p95/p99 and TLS connect time) measured every 2 hours from a fixed US East server. Raw data: [GitHub](https://github.com/sircharli3/fillbench-data) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-28.
* [filingrail-mcp](https://pypi.org/project/filingrail-mcp/) - `Python` `MCP` - MCP server and Python SDK for a SEC EDGAR REST API covering XBRL fundamentals, Form 4 insider trades, 8-K events, 13F holdings and filings, where every record carries the source sec.gov filing URL it came from. [GitHub](https://github.com/adamhudson777/filingrail-mcp) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-13
* [Backtesting Arena](https://tradingstrategies.work/api) - `TypeScript` - REST + MCP API for point-in-time Bitcoin cycle scoring, 22 on-chain series since 2009 (MVRV, NUPL, SOPR, Mayer, Puell), macro-regime composites and look-ahead-aware backtest validation with Deflated-Sharpe-Ratio correction across crypto, stocks, ETFs, commodities and forex. Free tier. [GitHub](https://github.com/Schoasch/skill-backtesting-arena) ⭐ 0 | 🐛 0 | 📅 2026-08-25
* [Korean Market Data](https://github.com/james-brand/korea-market-data) ⭐ 0 | 🐛 0 | 📅 2026-08-29 - `Data` - Daily foreign and institutional net flows for every KOSPI/KOSDAQ common stock plus all 44 KRX sector indices with returns and excess return vs market, in English CSV/JSON under CC BY 4.0 with a Zenodo DOI, rebuilt each trading day.
* [Helium MCP](https://heliumtrades.com/mcp-page/) - `Python` - Live stock/ETF/crypto data with AI-generated bull/bear cases and price forecasts, proprietary ML options pricing with probability ITM and fair value, and news bias scoring across 5,000+ sources. Available as MCP server or API. Free tier: 50 queries, no signup.
* [chinesestockapi](https://pypi.org/project/chinesestockapi/) - `Python` - Python API to get Chinese stock price. (Last updated: 2015-03-21).
* [tushare](https://pypi.org/project/tushare/) - `Python` - A utility for crawling historical and Real-time Quotes data of China stocks. (Last updated: 2024-08-27).
* [twmarketdata](https://pypi.org/project/twmarketdata/) - `Python` - Client for the TW Market Data API: Taiwan stock-market data (official-source, reconciled, point-in-time safe), REST + MCP server, free trial tier. <https://twmarketdata.com>.
* [edinetdb](https://edinetdb.com/) - `Python` - Free API and MCP server for Japanese company financials. Normalizes EDINET XBRL across JP-GAAP, IFRS, and US-GAAP for 3,800+ listed companies with 90 metrics, screening, and securities report text.
* [bronto-python](https://pypi.org/project/bronto-python/) - `Python` - Bronto API Integration for Python.
* [metatrader5](https://pypi.org/project/MetaTrader5/) - `Python` - API Connector to MetaTrader 5 Terminal. (Last updated: 2026-02-20).
* [Dados B3](https://dadosb3.com) - `REST/MCP` - Fundamental data API for Brazilian listed companies and real-estate funds (FIIs) on B3: ROIC, ROE, margins, point-in-time multiples, FII P/BV and dividend yield, public methodology, free tier.
* [fedfred](https://nikhilxsunder.github.io/fedfred/) - `Python` - FRED & GeoFRED Economic data API with preprocessed dataframe output in pandas/geopandas, polars/polars\_st, and dask dataframes/geodataframes.
* [edgar-sec](https://edgar-sec-dev-team.github.io/edgar-sec/) - `Python` - EDGAR Financial data API with preprocessed dataclass outputs.
* [uk-sic-codes](https://pypi.org/project/uk-sic-codes/) - `Python` - UK SIC 2007 industry classification code lookup, search, and validation. 731 codes, 21 sections.
* [uk-company-number](https://pypi.org/project/uk-company-number/) - `Python` - Validate, format, and identify UK Companies House company numbers. Supports all 27 prefixes.
* [IBrokers](https://cran.r-project.org/web/packages/IBrokers/index.html) - `R` - Provides native R access to Interactive Brokers Trader Workstation API.

## Prediction Markets

* [pmxt](https://github.com/pmxt-dev/pmxt) ⭐ 2,106 | 🐛 1,170 | 🌐 TypeScript | 📅 2026-07-18 - `Python` `JavaScript` - The CCXT for prediction markets. A unified API for trading on Polymarket, Kalshi, and more.

* [Oracle3](https://github.com/YichengYang-Ethan/oracle3) ⭐ 251 | 🐛 18 | 🌐 Python | 📅 2026-05-08 - `Python` - Autonomous trading agent for Kalshi, Polymarket, and Solana — Wang Transform pricing (calibrated on 291k resolved contracts) drives eight constraint-based arbitrage strategies and Kelly-sized model trades.

* [Live Tennis API](https://livetennisapi.com) - `REST` `WebSocket` `MCP` - Real-time tennis scores, serving and break-point state, and model win probabilities for pricing tennis event markets, plus H2H, rankings and a 1968-2022 point-by-point archive; free tier. [GitHub](https://github.com/livetennisapi/livetennisapi-mcp) ⭐ 162 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-23

* [polymm](https://github.com/kachence/polymm) ⭐ 83 | 🐛 1 | 🌐 Python | 📅 2026-08-16 - `Python` `Polymarket` - Market-making and arbitrage bot for Polymarket sports and esports markets, pricing from de-vigged sportsbook odds.

* [polymarket-whales](https://github.com/al1enjesus/polymarket-whales) ⭐ 60 | 🐛 10 | 🌐 Python | 📅 2026-03-20 - `Python` - Real-time whale trade tracker for Polymarket — terminal alerts + Telegram notifications when large orders hit the book.

* [prediction-market-maker](https://github.com/octavi42/prediction-market-maker) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2026-04-10 - `Python` - Open-source market-making strategy that placed #2 in Paradigm's prediction market challenge, with full strategy evolution and analysis.

* [marketlens](https://github.com/marketlenstrade/marketlens-python) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2026-08-18 - `Python` `MCP` - Tick-level Polymarket order book history with replay and a backtesting engine simulating queue priority, latency, and slippage.

* [PolyMind](https://polyminds.netlify.app/) - `Python` - Real-time Polymarket trading alerts with multi-AI analysis (Groq, Claude, Gemini). Track whale bets, volume spikes, coordinated wallets, and 12 signal types. Free tier available. [GitHub](https://github.com/samirasadov28-code/PolyMind) ⭐ 1 | 🐛 0 | 🌐 HTML | 📅 2026-06-18

* [polymarket-bot-lab](https://github.com/oraclemangle/polymarket-bot-lab) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-29 - `Python` - Open-sourced research lab of 11 candidate Polymarket trading bots (weather, sports, longshot fades, maker, whale-flow) with a shared CLOB/backtest framework, ADR decision log, and honest paper/live results. Companion free dataset: [polymarket-canary-tape](https://huggingface.co/datasets/oraclemangle/polymarket-canary-tape) (300M+ events, CC-BY-4.0).

* [Polymarket Scanner API](https://github.com/vesper-astrena/polymarket-scanner-api) - `Python` - Real-time arbitrage detection API for Polymarket prediction markets, scanning 12,000+ markets for mispricings.

* [SimpleFunctions](https://github.com/spfunctions/simplefunctions-cli) - `JavaScript` - Prediction market intelligence CLI for Kalshi and Polymarket. Causal thesis models, edge detection, 24/7 orderbook monitoring, what-if scenarios, and trade execution. MCP server for AI agent integration.

* [QuantRank500](https://github.com/quantrank500/quantrank500) - `Python` - Open-source public record of stock predictions: commit-reveal before the open, automatic settlement against exchange data, tamper-evident hash-chained ledger. Live at [quantrank500.com](https://quantrank500.com).

## Calendars & Market Hours

* [pandas\_market\_calendars](https://github.com/rsheftel/pandas_market_calendars) ⭐ 994 | 🐛 18 | 🌐 Python | 📅 2026-07-12 - `Python` - Exchange calendars to use with pandas for trading applications.
* [exchange\_calendars](https://github.com/gerrymanoim/exchange_calendars) ⭐ 664 | 🐛 26 | 🌐 Python | 📅 2026-08-14 - `Python` - Stock Exchange Trading Calendars.
* [bizdays](https://github.com/wilsonfreitas/python-bizdays) ⭐ 94 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2026-04-13 - `Python` - Business days calculations and utilities.
* [bizdays](https://github.com/wilsonfreitas/R-bizdays) ⭐ 58 | 🐛 12 | 🌐 R | 📅 2025-01-08 - `R` - Business days calculations and utilities.
* [sifma-holidays](https://github.com/moshejs/sifma-holidays) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - US bond-market (SIFMA) holidays, early closes, and T+1 settlement-date math; zero dependencies.
* [us-equity-market-calendar](https://github.com/moshejs/us-equity-market-calendar) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - NYSE/NASDAQ trading calendar: holidays, 1pm early closes, trading-day navigation, and DST-aware is-market-open; zero dependencies.
* [fx-value-date](https://github.com/moshejs/fx-value-date) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - FX spot/forward value-date calculation across two currency holiday calendars, with the USD-lag and end-of-month rules; zero dependencies.
* [timeDate](https://cran.r-project.org/web/packages/timeDate/index.html) - `R` - Chronological and Calendar Objects.

## Visualization

* [D-Tale](https://github.com/man-group/dtale) ⭐ 5,214 | 🐛 70 | 🌐 TypeScript | 📅 2026-07-24 - `Python` - Visualizer for pandas dataframes and xarray datasets.
* [mplfinance](https://github.com/matplotlib/mplfinance) ⭐ 4,427 | 🐛 176 | 🌐 Python | 📅 2024-08-08 - `Python` - matplotlib utilities for the visualization, and visual analysis, of financial data.
* [finvizfinance](https://github.com/lit26/finvizfinance) ⭐ 1,624 | 🐛 4 | 🌐 Python | 📅 2026-08-28 - `Python` - Finviz analysis python library.
* [finplot](https://github.com/highfestiva/finplot) ⭐ 1,180 | 🐛 36 | 🌐 Python | 📅 2026-03-30 - `Python` - Performant and effortless finance plotting for Python.
* [QuantInvestStrats](https://github.com/ArturSepp/QuantInvestStrats) ⭐ 622 | 🐛 0 | 🌐 Python | 📅 2026-08-28 - `Python` - Quantitative Investment Strategies (QIS) package implements Python analytics for visualisation of financial data, performance reporting, analysis of quantitative strategies.
* [dxcharts-lite](https://github.com/devexperts/dxcharts-lite) ⭐ 101 | 🐛 11 | 🌐 TypeScript | 📅 2026-08-20 - `JavaScript` - Flexible financial charting library based on HTML5 canvas.
* [market-analy](https://github.com/maread99/market_analy) ⭐ 80 | 🐛 3 | 🌐 Python | 📅 2026-08-27 - `Python` - Analysis and interactive charting using [market-prices](https://github.com/maread99/market_prices) ⭐ 105 | 🐛 10 | 🌐 Python | 📅 2026-08-14 and bqplot.
* [LightweightCharts.jl](https://github.com/bhftbootcamp/LightweightCharts.jl) ⭐ 56 | 🐛 3 | 🌐 Julia | 📅 2026-08-19 - `Julia` - Julia wrapper for Lightweight Charts™ by TradingView.
* [QUANTAXIS\_Webkit](https://github.com/yutiansut/QUANTAXIS_Webkit) ⚠️ Archived - `JavaScript` - An awesome visualization center based on quantaxis.
* [Exeria Charts](https://github.com/efixdata/exeria-charts) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-19 - `JavaScript` - High-performance, native Canvas/WebGL financial charting library for self-hosted applications without iframe limits.
* [MyLinedChart](https://mylinedchart.com) - `Desktop` - Technical-analysis charting app for Interactive Brokers (IBKR) that exports drawings, notes, indicators and OHLCV as JSON/XLSX/CSV, and exposes chart context to AI agents over MCP.

## Excel & Spreadsheet Integration

* [xlsxwriter](https://xlsxwriter.readthedocs.io/) - `Python` - Write files in the Excel 2007+ XLSX file format. [GitHub](https://github.com/jmcnamara/XlsxWriter) ⭐ 3,969 | 🐛 28 | 🌐 Python | 📅 2026-08-04
* [xlwings](https://www.xlwings.org/) - `Python` - Make Excel fly with Python. [GitHub](https://github.com/xlwings/xlwings) ⭐ 3,398 | 🐛 408 | 🌐 Python | 📅 2026-08-28
* [xlrd](https://github.com/python-excel/xlrd) ⭐ 2,206 | 🐛 3 | 🌐 Python | 📅 2026-07-15 - `Python` - Library for developers to extract data from Microsoft Excel spreadsheet files.
* [xlwt](https://github.com/python-excel/xlwt) ⚠️ Archived - `Python` - Library to create spreadsheet files compatible with MS Excel 97/2000/XP/2003 XLS files, on any platform.
* [xlloop](http://xlloop.sourceforge.net) - `Python` - XLLoop is an open source framework for implementing Excel user-defined functions (UDFs) on a centralised server (a function server). [GitHub](https://github.com/poidasmith/xlloop) ⭐ 110 | 🐛 26 | 🌐 Java | 📅 2019-11-18
* [Bilig](https://github.com/proompteng/bilig) ⭐ 35 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-24 - `TypeScript` - Formula WorkPaper and XLSX recalculation runtime for Node.js services and agent tools.
* [openpyxl](https://openpyxl.readthedocs.io/en/latest/) - `Python` - Read/Write Excel 2007 xlsx/xlsm files.
* [expy](http://www.bnikolic.co.uk/expy/expy.html) - `Python` - The ExPy add-in allows easy use of Python directly from within an Microsoft Excel spreadsheet, both to execute arbitrary code and to define new Excel functions.
* [pyxll](https://www.pyxll.com) - `Python` - PyXLL is an Excel add-in that enables you to extend Excel using nothing but Python code.

## Quant Research Environments

* [dsh-quant](https://github.com/pengpengyi92/dsh-quant) ⭐ 26 | 🐛 20 | 🌐 TypeScript | 📅 2026-08-28 - `TypeScript` `DeepSeek Harness` - Agent-native quantitative research toolkit for DeepSeek Harness: 46 tools across data, alpha, ML, risk, execution and ecosystem domains, with an end-to-end research pipeline.
* [Jupyter Quant](https://github.com/gnzsnz/jupyter-quant) ⭐ 22 | 🐛 0 | 🌐 Dockerfile | 📅 2024-06-14 - `Python` - A dockerized Jupyter quant research environment with preloaded tools for quant analysis, statsmodels, pymc, arch, py\_vollib, zipline-reloaded, PyPortfolioOpt, etc.

## Cross-Language Frameworks

* [QuantLib](https://github.com/lballabio/QuantLib) ⭐ 7,550 | 🐛 45 | 🌐 C++ | 📅 2026-08-28 - The QuantLib project is aimed at providing a comprehensive software framework for quantitative finance.
  * [PyQL](https://github.com/enthought/pyql) ⭐ 1,336 | 🐛 20 | 🌐 Cython | 📅 2026-07-17 - Python port.
  * [QLNet](https://github.com/amaggiulli/qlnet) ⭐ 427 | 🐛 3 | 🌐 C# | 📅 2026-08-04 - .Net port.
  * XAD - Automatic Differentiation (AAD) Library in [Python](https://pypi.org/project/xad/) and [C++](https://github.com/auto-differentiation/xad/) ⭐ 426 | 🐛 8 | 🌐 C++ | 📅 2026-07-05
  * [JQuantLib](https://github.com/frgomes/jquantlib) ⭐ 155 | 🐛 8 | 🌐 Java | 📅 2016-03-14 - Java port.
  * [QuantLib.jl](https://github.com/pazzo83/QuantLib.jl) ⭐ 144 | 🐛 10 | 🌐 Julia | 📅 2020-02-18 - Julia port.
  * [RQuantLib](https://github.com/eddelbuettel/rquantlib) ⭐ 136 | 🐛 9 | 🌐 C++ | 📅 2026-07-26 - R port.
  * QuantLibRisks - Fast risks with QuantLib in [Python](https://pypi.org/project/QuantLib-Risks/) and [C++](https://github.com/auto-differentiation/QuantLib-Risks-Cpp) ⭐ 42 | 🐛 2 | 🌐 C++ | 📅 2026-06-12
  * [QuantLibAddin](https://www.quantlib.org/quantlibaddin/) - Excel support.
  * [QuantLibXL](https://www.quantlib.org/quantlibxl/) - Excel support.
  * [QuantLib-Python Documentation](https://quantlib-python-docs.readthedocs.io/) - Documentation for the Python bindings for the QuantLib library.
* [TA-Lib](https://ta-lib.org) - perform technical analysis of financial market data. [GitHub](https://github.com/TA-Lib/ta-lib) ⭐ 1,661 | 🐛 13 | 🌐 Java | 📅 2026-08-29
  * [ta-lib-python](https://github.com/TA-Lib/ta-lib-python) ⭐ 12,218 | 🐛 137 | 🌐 Cython | 📅 2026-07-29
  * [ta-lib](https://github.com/TA-Lib/ta-lib) ⭐ 1,661 | 🐛 13 | 🌐 Java | 📅 2026-08-29
* [PineTS](https://github.com/LuxAlgo/PineTS) ⭐ 512 | 🐛 29 | 🌐 TypeScript | 📅 2026-08-29 - `TypeScript` `JavaScript` `Pine Script` - Open-source transpiler and runtime that executes Pine Script logic in Node.js and the browser with 1:1 syntax compatibility, for running indicators and strategies on your own infrastructure.
* [XAD](https://github.com/auto-differentiation/xad) ⭐ 426 | 🐛 8 | 🌐 C++ | 📅 2026-07-05 - Automatic Differentation (AAD) Library.
* [godzilla.dev](https://godzilla.dev) - `C++` `Python` - Open-source framework for crypto quant trading, funding rate arbitrage and ultra-low-latency market making. [GitHub](https://github.com/godzilla-foundation/godzilla-community) ⭐ 371 | 🐛 2 | 🌐 C++ | 📅 2026-08-11
* [RunMat](https://runmat.org) - High performance, Open Source, MATLAB syntax runtime. [GitHub](https://github.com/runmat-org/runmat) ⭐ 253 | 🐛 27 | 🌐 Rust | 📅 2026-08-28
* [RunMat](https://github.com/runmat-org/runmat) ⭐ 253 | 🐛 27 | 🌐 Rust | 📅 2026-08-28 - Rust runtime for MATLAB-syntax array math with automatic CPU/GPU execution and fused kernels for quant simulations.
* [QuantLibRisks](https://github.com/auto-differentiation/QuantLib-Risks-Cpp) ⭐ 42 | 🐛 2 | 🌐 C++ | 📅 2026-06-12 - Fast risks with QuantLib in C++.

## Reproducing Works, Training & Books

* [python-training](https://github.com/jpmorganchase/python-training) ⭐ 14,048 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-24 - J.P. Morgan's Python training for business analysts and traders.
* [Finance](https://github.com/shashankvemuri/Finance) ⭐ 4,199 | 🐛 22 | 🌐 Python | 📅 2026-03-26 - 150+ quantitative finance Python programs to help you gather, manipulate, and analyze stock market data.
* [algorithmic-trading-with-python](https://github.com/chrisconlan/algorithmic-trading-with-python) ⭐ 3,480 | 🐛 6 | 🌐 Python | 📅 2021-06-01 - Source code for Algorithmic Trading with Python (2020) by Chris Conlan.
* [ML\_Finance\_Codes](https://github.com/mfrdixon/ML_Finance_Codes) ⭐ 2,638 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2020-06-13 - Machine Learning in Finance: From Theory to Practice Book.
* [py4fi2nd](https://github.com/yhilpisch/py4fi2nd) ⭐ 2,260 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2025-06-06 - Jupyter Notebooks and code for Python for Finance (2nd ed., O'Reilly) by Yves Hilpisch.
* [MEDIUM\_NoteBook](https://github.com/cerlymarco/MEDIUM_NoteBook) ⭐ 2,144 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2024-09-22 - Repository containing notebooks of [cerlymarco](https://github.com/cerlymarco)'s posts on Medium.
* [Stock\_Analysis\_For\_Quant](https://github.com/LastAncientOne/Stock_Analysis_For_Quant) ⭐ 2,055 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-05-04 - Different Types of Stock Analysis in Excel, Matlab, Power BI, Python, R, and Tableau.
* [volatility-trading](https://github.com/jasonstrimpel/volatility-trading) ⭐ 1,947 | 🐛 4 | 🌐 Python | 📅 2024-10-21 - A complete set of volatility estimators based on Euan Sinclair's Volatility Trading.
* [Hands-On Machine Learning for Algorithmic Trading](https://github.com/packtpublishing/hands-on-machine-learning-for-algorithmic-trading) ⭐ 1,915 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2023-01-18 - Hands-On Machine Learning for Algorithmic Trading, published by Packt.
* [Deep Learning Machine Learning Stock](https://github.com/LastAncientOne/Deep-Learning-Machine-Learning-Stock) ⭐ 1,787 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2024-03-01 - Deep Learning and Machine Learning stocks represent a promising long-term or short-term opportunity for investors and traders.
* [Machine Learning Asset Management](https://github.com/firmai/machine-learning-asset-management) ⭐ 1,748 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2021-12-17 - Machine Learning in Asset Management (by @firmai).
* [Quantitative-Notebooks](https://github.com/LongOnly/Quantitative-Notebooks) ⚠️ Archived - Educational notebooks on quantitative finance, algorithmic trading, financial modelling and investment strategy.
* [fecon235](https://github.com/rsvp/fecon235) ⭐ 1,276 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2023-01-20 - Open source project for software tools in financial economics. Many jupyter notebook to verify theoretical ideas and practical methods interactively.
* [QuantFinanceBook](https://github.com/LechGrzelak/QuantFinanceBook) ⭐ 952 | 🐛 3 | 🌐 Python | 📅 2025-04-14 - Quantitative Finance book.
* [Computational-Finance-Course](https://github.com/LechGrzelak/Computational-Finance-Course) ⭐ 897 | 🐛 0 | 🌐 Python | 📅 2024-03-01 - Materials for the course of Computational Finance.
* [AFML](https://github.com/boyboi86/AFML) ⭐ 862 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-09-05 - All the answers for exercises from Advances in Financial Machine Learning by Dr Marco Lopez de Parodo.
* [Python\_Option\_Pricing](https://github.com/dedwards25/Python_Option_Pricing) ⭐ 851 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2025-05-13 - An library to price financial options written in Python. Includes: Black Scholes, Black 76, Implied Volatility, American, European, Asian, Spread Options.
* [py4at](https://github.com/yhilpisch/py4at) ⭐ 851 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2023-10-09 - Jupyter Notebooks and code for the book Python for Algorithmic Trading (O'Reilly) by Yves Hilpisch.
* [FinanceHub](https://github.com/Finance-Hub/FinanceHub) ⭐ 801 | 🐛 4 | 🌐 Python | 📅 2024-05-28 - Resources for Quantitative Finance.
* [Python-for-Finance-Cookbook](https://github.com/PacktPublishing/Python-for-Finance-Cookbook) ⭐ 799 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-03-02 - Python for Finance Cookbook, published by Packt.
* [dx](https://github.com/yhilpisch/dx) ⭐ 769 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-04-05 - DX Analytics | Financial and Derivatives Analytics with Python.
* [Machine-Learning-for-Asset-Managers](https://github.com/emoen/Machine-Learning-for-Asset-Managers) ⭐ 660 | 🐛 2 | 🌐 Python | 📅 2026-02-11 - Implementation of code snippets, exercises and application to live data from Machine Learning for Asset Managers (Elements in Quantitative Finance) written by Prof. Marcos López de Prado.
* [dawp](https://github.com/yhilpisch/dawp) ⭐ 640 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-02-22 - Jupyter Notebooks and code for Derivatives Analytics with Python (Wiley Finance) by Yves Hilpisch.
* [QuantFinance](https://github.com/PythonCharmers/QuantFinance) ⭐ 617 | 🐛 14 | 🌐 Jupyter Notebook | 📅 2025-09-02 - Training materials in quantitative finance.
* [Derman Papers](https://github.com/MarcosCarreira/DermanPapers) ⭐ 531 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2017-10-21 - Notebooks that replicate original quantitative finance papers from Emanuel Derman.
* [systematictradingexamples](https://github.com/robcarver17/systematictradingexamples) ⭐ 488 | 🐛 0 | 🌐 Python | 📅 2020-07-22 - Examples of code related to book [Systematic Trading](www.systematictrading.org) and [blog](http://qoppac.blogspot.com).
* [quant](https://github.com/paulperry/quant) ⭐ 450 | 🐛 0 | 🌐 Python | 📅 2015-07-14 - Quantitative Finance and Algorithmic Trading exhaust; mostly ipython notebooks based on Quantopian, Zipline, or Pandas.
* [aiif](https://github.com/yhilpisch/aiif) ⭐ 399 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2024-01-14 - Jupyter Notebooks and code for the book Artificial Intelligence in Finance (O'Reilly) by Yves Hilpisch.
* [pysystemtrade\_examples](https://github.com/robcarver17/pysystemtrade_examples) ⭐ 279 | 🐛 1 | 🌐 Python | 📅 2018-02-21 - Examples using pysystemtrade for Robert Carver's [blog](http://qoppac.blogspot.com).
* [Technical Analysis and Feature Engineering](https://github.com/jo-cho/Technical_Analysis_and_Feature_Engineering) ⭐ 203 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-02-16 - Feature Engineering and Feature Importance of Machine Learning in Financial Market.
* [Quant-Finance-With-Python-Code](https://github.com/lingyixu/Quant-Finance-With-Python-Code) ⭐ 184 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-01-15 - Repo for code examples in Quantitative Finance with Python by Chris Kelliher.
* [IPythonScripts](https://github.com/mgroncki/IPythonScripts) ⭐ 179 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-02-28 - Tutorials about Quantitative Finance in Python and QuantLib: Pricing, xVAs, Hedging, Portfolio Optimisation, Machine Learning and Deep Learning.
* [Differential Machine Learning and Axes that matter by Brian Huge and Antoine Savine](https://github.com/differential-machine-learning/notebooks) ⭐ 149 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2022-10-05 - Implement, demonstrate, reproduce and extend the results of the Risk articles 'Differential Machine Learning' (2020) and 'PCA with a Difference' (2021) by Huge and Savine, and cover implementation details left out from the papers.
* [Autoencoder-Asset-Pricing-Models](https://github.com/RichardS0268/Autoencoder-Asset-Pricing-Models) ⭐ 149 | 🐛 2 | 🌐 Python | 📅 2025-08-17 - Reimplementation of Autoencoder Asset Pricing Models ([GKX, 2019](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3335536)).
* [rough\_bergomi](https://github.com/ryanmccrickerd/rough_bergomi) ⭐ 144 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-09-17 - A Python implementation of the rough Bergomi model.
* [book\_irds3](https://github.com/attack68/book_irds3) ⭐ 125 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2022-10-29 - Code repository for Pricing and Trading Interest Rate Derivatives.
* [Value Investing Studies](https://github.com/euclidjda/value-investing-studies) ⭐ 97 | 🐛 1 | 🌐 R | 📅 2021-10-26 - A collection of data analysis studies that examine the performance and characteristics of value investing over long periods of time.
* [RoughVolatilityWorkshop](https://github.com/jgatheral/RoughVolatilityWorkshop) ⭐ 73 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-09-06 - 2024 QuantMind's Rough Volatility Workshop lectures.
* [modelos\_vol\_derivativos](https://github.com/ysaporito/modelos_vol_derivativos) ⭐ 59 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-08-19 - "Modelos de Volatilidade para Derivativos" book's Jupyter notebooks.
* [101\_formulaic\_alphas](https://github.com/ram-ki/101_formulaic_alphas) ⭐ 51 | 🐛 0 | 🌐 Python | 📅 2022-07-11 - Implementation of [101 formulaic alphas](https://arxiv.org/abs/1601.00991) using qstrader.
* [QuantFinanceTraining](https://github.com/JoaoJungblut/QuantFinanceTraining) ⭐ 42 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-02-20 - This repository contains codes that were executed during my training in the CQF (Certificate in Quantitative Finance). The codes are organized by class, facilitating navigation and reference.
* [NMOF](https://github.com/enricoschumann/NMOF) ⭐ 39 | 🐛 0 | 🌐 R | 📅 2026-08-20 - Functions, examples and data from the first and the second edition of "Numerical Methods and Optimization in Finance" by M. Gilli, D. Maringer and E. Schumann (2019, ISBN:978-0128150658).
* [AlgoTradingLib](https://github.com/usdaud/algotradinglib.github.io) ⭐ 33 | 🐛 0 | 🌐 HTML | 📅 2026-03-28 - A catalog of algorithmic trading libraries, frameworks, strategies, and educational materials.
* [financialnoob-misc](https://github.com/financialnoob/misc) ⭐ 28 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-08-26 - Codes from @financialnoob's posts.
* [Portfolio Optimization Book](https://portfoliooptimizationbook.com/) - Prof. Daniel Palomar's Portfolio Optimization Book. [GitHub](https://github.com/dppalomar/pob) ⭐ 27 | 🐛 1 | 🌐 R | 📅 2025-02-17
* [MesoSim Options Trading Strategy Library](https://github.com/deltaray-io/strategy-library) ⭐ 22 | 🐛 0 | 📅 2024-04-06 - Free and public Options Trading strategy library for MesoSim.
* [frh-fx](https://github.com/ryanmccrickerd/frh-fx) ⭐ 14 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-05-24 - A python implementation of the fast-reversion Heston model of Mechkov for FX purposes.
* [Special-Relativity-in-Financial-Modeling](https://github.com/Mattbusel/Special-Relativity-in-Financial-Modeling) ⭐ 12 | 🐛 0 | 🌐 C++ | 📅 2026-03-23 - C++20 implementation of special-relativistic geometry applied to OHLCV data: Lorentz factors, spacetime intervals, Christoffel symbols, and geodesic deviation signals from live market data. DOI: 10.5281/zenodo.18639919.
* [direct\_vola](https://github.com/wol-fi/direct_vola) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-05-01 - `Python` `R` - Demo code for direct Black-Scholes implied-volatility calculation from normalized call prices via the inverse-Gaussian quantile representation.
* [cipher-starter](https://github.com/cryptomotifs/cipher-starter) ⭐ 4 | 🐛 0 | 🌐 HTML | 📅 2026-04-18 — Solo crypto quant starter kit: 12 playbooks covering trading strategy, risk rails, 3-tier wallet architecture, MEV mitigation, Canadian NI 31-103 compliance, Oracle Cloud Always Free infra, and a 7-day MVP calendar for a Solana signal engine + autonomous trading bot.
* [TradeMux Snippets](https://github.com/KVignesh122/trademux-examples) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-06-05 - `Python` - Code snippets for Metatrader (MT5) forex/CFD trading and data retrieval via trademux API client.
* [Quant Sprint](https://lambdia.com/play) - `Training` `Interviews` - Free timed drill of first round quant interview questions on options and the Greeks, two sided quoting, probability and mental arithmetic.
* [QuantVault](https://quantvault.org) - `Training` `Interviews` - Quant interview prep with 391 free problems with full worked solutions, per-firm online-assessment guides, and free playable replicas of real trading-firm OAs (Optiver, SIG, IMC).
* [Wyckoff Method Course](https://arapov.trade/en/freestudying/wyckoff-method) - Free course on volume analysis and the Wyckoff method: market phases, spring/upthrust, order flow reading.
* [Auto-Differentiation Website](https://auto-differentiation.github.io/) - Background and  resources on Automatic Differentiation (AD) / Adjoint Algorithmic Differentitation (AAD).
* [QuantEcon](https://quantecon.org/) - Lecture series on economics, finance, econometrics and data science; QuantEcon.py, QuantEcon.jl, notebooks.
* [Tidy Finance](https://www.tidy-finance.org/) - An opinionated approach to empirical research in financial economics - a fully transparent, open-source code base in multiple programming languages (Python and R) to enable the reproducible implementation of financial research projects for students and practitioners.

## Commercial & Proprietary Services

* [The Stall](https://the-stall.intuitek.ai) - `JavaScript` - 277 pay-per-call tools via MCP: US stocks, crypto, DeFi analytics, Polymarket prediction markets, macro data, and sanctions screening. USDC on Base. No API key required. [GitHub](https://github.com/thebrierfox/the-stall) ⭐ 7 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-28
* [AlphaForge](https://alforgelabs.com) - `Python` - Local-first agent-native quant CLI with Optuna TPE optimization, walk-forward testing, anti-overfitting guards, and TradingView Pine v6 code generation. Free trial available. [GitHub](https://github.com/alforge-labs/alpha-forge-mcp) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-07-21
* [Quant Data](https://quantdata.uk/mcp) - `Data` - Hosted service with measured market statistics over REST and a remote MCP server: five-class day-type probabilities for the session in progress, Weis volume-wave events with pre-registered win rates on 16 years of ES 5-minute data, options max pain from open interest alone, and estimated dealer gamma (GEX). Every published number traces to a stated measurement, failures included. The max pain and GEX web pages are permanently free with no key or signup; the API allows 1 unauthenticated first-look call per source per day, and 10 calls per day with a free API key delivered by email. Sustained or unattended use requires a paid monthly subscription. [GitHub](https://github.com/celineycn/quantdata-plugin) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-08-18
* [invinoveritas/review](https://github.com/trustless-ai/agent-contracts-examples) ⭐ 0 | 🐛 1 | 🌐 Solidity | 📅 2026-08-12 - `Python` - Pre-execution governance gate for AI trading agents: a capital-scale-aware advisory verdict (approve / approve\_with\_concerns / reject) before an order is placed, via MCP server, REST, x402 (USDC), or Lightning pay-per-call. Dogfooded by a live Hyperliquid bot; verdicts are signed and recomputable against a public ledger. API: <https://api.babyblueviper.com>
* [AlphaAssay](https://alphaassay.com) - `REST` - Independent statistical assay office for trading signals and backtests: deflated Sharpe with cumulative trial accounting, probability of backtest overfitting (PBO/CPCV), leakage forensics, placebo tests against matched synthetic null worlds, and pre-registration with Merkle-anchored timestamps — deterministic, Ed25519-signed verdicts anyone can replay. Free demo; hosted API and MCP server. Methodology audit, not investment advice. [GitHub](https://github.com/alphaassay/mcp) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-29
* [AtlasYield](https://atlasyield.club) - Independent rating and allocation layer for on-chain yield: scores every DeFi vault 0-100 across 16 factors, with a public read-only scores API. [GitHub](https://github.com/gveshk/atlasyield-score-history) ⭐ 0 | 🐛 0 | 📅 2026-08-29
* [Wealthville](https://wealthville.net) - `REST` `MCP` - Liquidity-pool scoring for DeFi market making: a 0-100 score and an Enter/Hold/Exit/Reduce/Avoid verdict, with confidence calibrated per protocol, across \~68,800 Solana pools (Meteora DLMM, Orca Whirlpool, Raydium AMM/CLMM/CPMM) and 575 EVM pools on Ethereum, Arbitrum, Base, Optimism, Polygon and BSC. Outcomes are graded after impermanent loss and published as a miss-inclusive 30-day track record. Free keyless API, OpenAPI spec, and a hosted MCP server. [GitHub](https://github.com/amitesh-m/wealthville-integrations) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-30
* [Shingou](https://shingou.io) - `REST` `MCP` - Hourly crypto news sentiment and typed market events (hack, regulation, listing, delisting, legal) for 30 pairs, served as point-in-time buckets whose SHA-256 hash is committed to a public append-only log at publish time, so a backtester can check the history was never rewritten. Paid plans are $24, $79 and $249 a month before VAT; the permanent free tier is 1,000 requests a day with BTC, ETH and SOL live, the other 27 pairs delayed 24h, 1 day of history depth, no card, non-commercial use. [GitHub](https://github.com/shingou-io/shingou-integrations) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-02
* [Wiseek Filing Impact](https://wiseek.ai/datasets/) - Monthly statistics relating proprietary SEC-filing importance scores to next-session excess stock moves, with per-event data, reproduction metadata, and a CC BY 4.0 license. [GitHub](https://github.com/WiseekAI/wiseek-datasets) ⭐ 0 | 🐛 0 | 📅 2026-08-21
* [AxionQuant](https://axionquant.com) - Unified financial data API covering market prices, fundamentals, disclosures, macroeconomic, and alternative data for long-horizon research and quantitative modeling. Free tier: 1,000 monthly API calls. [PyPI](https://pypi.org/project/axionquant-sdk/)
* [Prop Firm Risk Calculator](https://prop-firm-risk-calculator.vercel.app) - Free web app for position sizing, stop-loss and max-drawdown on funded accounts, with real tick/pip values for futures, forex, crypto and gold.
* [TradeMux](https://trademux.io) - Unified forex trading API gateway to Metatrader (MT4/MT5), Oanda and cTrader.
* [Chartscout](https://chartscout.io) - Real-time cryptocurrency chart pattern detection with automated alerts across multiple exchanges.
* [DayTradingBench](https://daytradingbench.com) - Live autonomous benchmark that evaluates LLM trading performance on DAX and Nasdaq indices using identical strategies and real-time market data. API access available.
* [CoinTester](https://cointester.io) - No-code crypto backtesting platform with 100+ indicators, AI sentiment signals, and 5+ years of historical data across 1,000+ trading pairs.
* [FinSignals](https://finsignals.ai) - `Python` - Reddit-tuned NLP API classifying financial posts across 7 dimensions: sentiment, directionality, quality, post type, relevance score, author confidence, and sarcasm. Free tier available.
* [goMacro.ai](https://gomacro.ai) - AI-powered economic calendar with institutional-grade insights, bull/bear/base case scenario planning for NFP, CPI, PPI and other macro data releases.
* [StockAInsights](https://stockainsights.com) - AI-extracted financial statements API covering SEC filings including foreign filers (20-F, 6-K, 40-F), normalized quarterly and annual data from 2014+.
* [StockVektor](https://stockvektor.com) - Free stock research web app for \~1,300 US stocks with explainable quality scores (Piotroski F-Score, Altman Z-Score, Beneish M-Score, ROIC, EV/EBIT) computed from SEC EDGAR data, sector-relative metrics, insider buying clusters, 13F super-investor overlap, and activist filing (Schedule 13D/G) tracking.
* [bolsai](https://usebolsai.com) - REST API and MCP server for Brazilian stock market data (B3). Covers 350+ stocks, 400+ FIIs with fundamentals (27+ indicators), dividends, historical prices, financials, and macro indicators sourced from B3, CVM, and BCB.
* [brapi.dev](https://brapi.dev/) - Brazilian stock market data API for B3/Bovespa quotes, historical OHLCV, dividends, and fundamentals.
* [Teses da Bolsa](https://tesesdabolsa.com) - Free web app for Brazilian stock and FII fundamentalist analysis on B3. Covers 350+ stocks and 400+ FIIs with 27+ indicators (P/L, DY, ROE, P/VP), 40+ years of historical data, CVM financial statements, dividend history, fair value models, and head-to-head comparisons.
* [13F Insight](https://13finsight.com/) - Track institutional investor 13F holdings with AI-powered analysis, position change alerts, and filing summaries.
* [PortfolioSavvy](https://portfoliosavvy.com/) - Public SEC ownership research web app for exploring 13F portfolios, insider activity, Schedule 13D/G filings, company facts, and latest filing workflows.
* [Earnings Feed](https://earningsfeed.com/api) - Real-time SEC filings, insider trades, and institutional holdings API.
* [EDGAR Events](https://edgarevents.com) - `REST` - SEC filing events as typed JSON: 8-K item codes with materiality flags, SC 13D/13G activist stakes (holder, target, percent of class), merger forms, and S-1/424B IPO filings, polled over REST or pushed via HMAC-signed webhooks, sourced from data.sec.gov.
* [FilingPulse](https://filingpulse.io) - `REST` `MCP` - Real-time SEC EDGAR filings normalized to one JSON schema: Form 4 insider trades, 8-K corporate events, and S-1/IPO registrations, delivered via REST, HMAC-signed webhooks, and a hosted MCP server, with a permanent free tier (2,500 req/mo, full schema).
* [Financial Data](https://financialdata.net/) - Stock Market and Financial Data API.
* [Filings Flow](https://filingsflow.com) - Free SEC 13F research web app covering 11,700+ institutional managers and 208,000+ filings from 2019 onward. Quarter-over-quarter position changes with share-based thresholds, confidential-treatment reveals badged, per-filing links to the EDGAR source document, and Excel export on every table. No account required.
* [Frostbyte](https://agent-gateway-kappa.vercel.app) - Real-time crypto prices for 500+ tokens via REST API with free tier, DeFi swap routing and portfolio tracking.
* [SaxoOpenAPI](https://www.developer.saxo/) - Saxo Bank financial data API.
* [RTPR](https://rtpr.io) - Real-time press release API delivering news from Business Wire, PR Newswire, and GlobeNewswire with sub-500ms latency. REST and WebSocket APIs for financial applications. Python and Node.js SDKs available.
* [Nasdaq Data Link](https://data.nasdaq.com/tools/full-list) - Financial data API with support for R, Python, Excel, Ruby, and many other languages (formerly Quandl).
* [Portfolio Optimizer](https://portfoliooptimizer.io/) - Portfolio Optimizer is a Web API for portfolio analysis and optimization.
* [Reddit WallstreetBets API](https://tradestie.com/apps/reddit/api/) - Provides daily top 50 stocks from reddit (subreddit) Wallstreetbets and their sentiments via the API.
* [System R](https://systemr.ai/) - AI-native risk intelligence API for trading agents. Position sizing, risk validation, and system health in one call.
* [Telonex](https://telonex.io) - Tick-level prediction market data (trades, quotes, orderbooks, on-chain fills) via REST API and Python SDK.
* [ValueRay](https://www.valueray.com/api) - Technical, quantitative and sentiment data for stocks and ETFs with risk metrics, peer percentiles and market regime signals. Optimized for AI/LLM agents.
* [VantageGrid](https://vantagegrid.pro/) - Quantitative trade-review workspace for futures and prop-firm traders, with MFE/MAE, R-multiple, Monte Carlo, drawdown, multi-account, and playbook-compliance analytics.
* [VertData](https://vertdata.com) - Institutional-grade financial intelligence platform. Track 43K+ congressional trades (STOCK Act), SEC insider Form 4 filings, 25 superinvestor 13F portfolios, CFTC futures positioning, ARK ETF holdings, and short interest — all scored by AI for signal strength.
* [KeepRule](https://keeprule.com/) - Curated library of decision-making principles and investment wisdom from masters like Buffett and Munger, featuring mental models for better investment thinking.
* [Agent Toolbelt](https://www.agenttoolbelt.live) - AI stock-research API returning structured analysis (investment thesis, valuation verdict, insider-signal read, earnings, bull-vs-bear, moat, watchlist ranking) for US equities from Polygon/Finnhub/FMP data. Optimized for LLM agents; free tier.
* [ML-Quant](https://www.ml-quant.com/) - Top Quant resources like ArXiv (sanity), SSRN, RePec, Journals, Podcasts, Videos, and Blogs.
* [RealMarketAPI](https://realmarketapi.com/) - Provides ultra-low latency market data for gold, forex, crypto, and stocks via REST, WebSocket, and MCP—built for speed, reliability, and scale.
* [Probalytics](https://probalytics.io) - Prediction market data infrastructure for Polymarket and Kalshi, with REST API, ClickHouse SQL access, 200–500M orderbook snapshots/day at 1ms resolution, and Parquet bulk exports.
* [Sharpe](https://www.sharpe.ai/) - AI-driven crypto trading intelligence terminal for derivatives positioning, DEX flow, on-chain risk, narrative rotation, token discovery, and agent-ready market data.
* [Webb Database](https://webb-database.com/) - Aggregates public financial data from HKEX, the SFC, the Hong Law Society, UK Companies House and other sources, has searchable datasets on listed companies, many in machine-readable formats.
* [GitDealFlow](https://gitdealflow.com) - Alternative-data signal platform ranking early-stage private companies by GitHub stars-per-day, hiring velocity, and package-registry adoption. Free weekly signal report, Chrome extension overlay on Crunchbase/AngelList, and MCP server on npm for LLM agent access.
* [Clear Street API](https://docs.clearstreet.com/?utm_source=github\&utm_medium=developer\&utm_campaign=api_listings\&utm_content=awesome_quant) - REST API for US equities & options: reference & fundamental data, multi-year financial statements, corporate events, analyst consensus, a screener, and order execution.
* [Finterm](https://finterm.xyz) - `TypeScript` - Browser-based, keyboard-first financial terminal. No public GitHub repo (closed source).
* [Coinugget](https://coinugget.com) - Real-time RSI signals, price action, and volume spikes dashboard across multiple exchanges. Free, no sign-up required.
* [Stingray](https://stingray.fi/) - Trading strategy builder that turns plain-English market ideas into inspectable rules, backtests them against historical data, and monitors matching live conditions.
* [NeuPortal](https://neuportal.ai) - AI forecasting-accountability lab: every forecast is locked pre-event, Bitcoin-timestamped (OpenTimestamps), and Brier-scored against prediction markets in public.
* [Market Posture Daily](https://marketpd.com) - Daily trend, regime, momentum and relative-strength data for \~90 crypto assets and US stocks/ETFs, with a cointegration pair screener. Free terminal + JSON API.
* [Honest Backtest](https://whop.com/honest-backtest) - Independent manual code audits of trading bots and their backtests: catches unmodeled commission/slippage, signal-vs-fill price drift, and other gaps between backtested and live results.
* [StreamXLS](https://streamxls.com) - Commercial Excel RTD server for the Interactive Brokers TWS API, streaming market data, account values, positions, and orders into Excel formulas on Windows.
* [Katana](https://katanascreener.com) - Free Japan stock screener built on EDINET filings. 160+ fundamentals, custom formula metrics, Graham/Piotroski/Kiyohara presets. No sign-up.
* [Disclosed Capitol](https://www.disclosedcapitol.com/data-files/api) - US congressional and executive-branch stock trade disclosures API. STOCK Act filings plus OGE executive data (\~6,743 transactions across 106 officials), with trade-level returns and alpha. Free tier: 500 credits, no card.
* [0xArchive](https://0xarchive.io) - Real-time and historical Hyperliquid and Lighter market data through REST, WebSocket, MCP, SDKs, CLI, and replay, with a permanent free tier.
* [TickerAll](https://tickerall.com) - Hosted MetaTrader 5 & MT4 broker API (REST + WebSocket) to connect broker accounts, stream live ticks, fetch historical candles, and place or manage trades from code without a local terminal; permanent free tier with no card, real-time market data, and demo trading, with paid plans for live trading and higher limits. [Docs](https://tickerall.com/docs)

## Related Lists

* [awesome-sec-filings](https://github.com/vibeyclaw/awesome-sec-filings) ⭐ 39 | 🐛 6 | 📅 2026-07-04 - A curated list of tools, data sources, libraries, and resources for working with SEC filings (13F, 10-K, 10-Q, 8-K).
* [CONVEXFI](https://github.com/convexfi) - Official GitHub organization for the convex research group at the Hong Kong University of Science and Technology (HKUST).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
