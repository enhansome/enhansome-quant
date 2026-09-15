# Awesome Quant with stars

A curated list of insanely awesome libraries, packages and resources for Quants (Quantitative Finance).

[![](https://awesome.re/badge.svg)](https://awesome.re)

## Contents

* [Numerical Libraries & Data Structures](#numerical-libraries--data-structures)
* [Financial Instruments & Pricing](#financial-instruments--pricing)
* [Technical Indicators](#technical-indicators)
* [Trading & Backtesting](#trading--backtesting)
* [Portfolio Optimization & Risk Analysis](#portfolio-optimization--risk-analysis)
* [Factor Analysis](#factor-analysis)
* [Sentiment Analysis & Alternative Data](#sentiment-analysis--alternative-data)
* [Time Series Analysis](#time-series-analysis)
* [Market Data & Data Sources](#market-data--data-sources)
* [Prediction Markets](#prediction-markets)
* [Calendars & Market Hours](#calendars--market-hours)
* [Visualization](#visualization)
* [Excel & Spreadsheet Integration](#excel--spreadsheet-integration)
* [Quant Research Environments](#quant-research-environments)
* [Cross-Language Frameworks](#cross-language-frameworks)
* [Reproducing Works, Training & Books](#reproducing-works-training--books)
* [Commercial & Proprietary Services](#commercial--proprietary-services)
* [Historical & Archived Projects](#historical--archived-projects)
* [Related Lists](#related-lists)

## Numerical Libraries & Data Structures

* [pandas](https://pandas.pydata.org) - `Python` - pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language. [GitHub](https://github.com/pandas-dev/pandas) ⭐ 49,733 | 🐛 2,719 | 🌐 Python | 📅 2026-09-15
* [polars](https://docs.pola.rs/) - `Python` - Polars is a blazingly fast DataFrame library for manipulating structured data. [GitHub](https://github.com/pola-rs/polars) ⭐ 39,731 | 🐛 2,894 | 🌐 Rust | 📅 2026-09-15
* [numpy](https://numpy.org/) - `Python` - NumPy is the fundamental package for scientific computing with Python. [GitHub](https://github.com/numpy/numpy) ⭐ 32,747 | 🐛 2,299 | 🌐 Python | 📅 2026-09-15
* [scipy](https://scipy.org/) - `Python` - SciPy (pronounced “Sigh Pie”) is a Python-based ecosystem of open-source software for mathematics, science, and engineering. [GitHub](https://github.com/scipy/scipy) ⭐ 15,016 | 🐛 1,836 | 🌐 Python | 📅 2026-09-15
* [sympy](https://www.sympy.org/) - `Python` - SymPy is a Python library for symbolic mathematics. [GitHub](https://github.com/sympy/sympy) ⭐ 14,941 | 🐛 5,998 | 🌐 Python | 📅 2026-09-14
* [pymc3](https://docs.pymc.io/) - `Python` - Probabilistic Programming in Python: Bayesian Modeling and Probabilistic Machine Learning with Theano. [GitHub](https://github.com/pymc-devs/pymc) ⭐ 9,752 | 🐛 502 | 🌐 Python | 📅 2026-09-14
* [data.table](https://github.com/Rdatatable/data.table) ⭐ 3,918 | 🐛 984 | 🌐 R | 📅 2026-09-10 - `R` - Extension of data.frame: Fast aggregation of large data (e.g. 100GB in RAM), fast ordered joins, fast add/modify/delete of columns by group using no copies at all, list columns and a fast file reader (fread). Offers a natural and flexible syntax, for faster development.
* [ArcticDB](https://github.com/man-group/ArcticDB) ⭐ 2,509 | 🐛 338 | 🌐 C++ | 📅 2026-09-15 - `Python` - High performance datastore for time series and tick data.
* [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl) ⭐ 1,832 | 🐛 161 | 🌐 Julia | 📅 2026-09-12 - `Julia` - In-memory tabular data in Julia.
* [quantdsl](https://github.com/johnbywater/quantdsl) ⭐ 384 | 🐛 4 | 🌐 Python | 📅 2018-04-14 - `Python` - Domain specific language for quantitative analytics in finance and trading.
* [xts](https://github.com/joshuaulrich/xts) ⭐ 224 | 🐛 72 | 🌐 R | 📅 2026-09-08 - `R` - eXtensible Time Series: Provide for uniform handling of R's different time-based data classes by extending zoo, maximizing native format information preservation and allowing for user level customization and extension, while simplifying cross-class interoperability.
* [jacobian](https://github.com/morluto/jacobian) ⭐ 194 | 🐛 124 | 🌐 Python | 📅 2026-09-15 - `Python` `MCP` - Exact computation and conjecture testing across polynomial maps, linear algebra, and graph algorithms for agent-driven mathematical research.
* [modelx](https://docs.modelx.io/) - `Python` - Python reimagination of spreadsheets as formula-centric objects that are interoperable with pandas. [GitHub](https://github.com/fumitoh/modelx) ⭐ 134 | 🐛 37 | 🌐 Python | 📅 2026-09-05
* [Temporal.jl](https://github.com/JTAmos/Temporal.jl) ⭐ 101 | 🐛 15 | 🌐 Julia | 📅 2023-03-03 - `Julia` - Flexible and efficient time series class & methods.
* [TSFrames.jl](https://github.com/xKDR/TSFrames.jl) ⭐ 101 | 🐛 53 | 🌐 Julia | 📅 2024-06-18 - `Julia` - Handle timeseries data on top of the powerful and mature DataFrames.jl.
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

* [gs-quant](https://github.com/goldmansachs/gs-quant) ⭐ 12,963 | 🐛 73 | 🌐 Python | 📅 2026-09-14 - `Python` - Python toolkit for quantitative finance.
* [tf-quant-finance](https://github.com/google/tf-quant-finance) ⭐ 5,502 | 🐛 42 | 🌐 Python | 📅 2026-08-06 - `Python` - High-performance TensorFlow library for quantitative finance.
* [FinancePy](https://github.com/domokane/FinancePy) ⭐ 3,149 | 🐛 58 | 🌐 Jupyter Notebook | 📅 2026-09-12 - `Python` - A Python Finance Library that focuses on the pricing and risk-management of Financial Derivatives, including fixed-income, equity, FX and credit derivatives.
* [ffn](https://github.com/pmorissette/ffn) ⭐ 2,680 | 🐛 6 | 🌐 Python | 📅 2026-09-14 - `Python` - A financial function library for Python.
* [RustQuant](https://github.com/avhz/RustQuant) ⭐ 1,822 | 🐛 30 | 🌐 Rust | 📅 2026-09-12 - `Rust` - Quantitative finance library written in Rust.
* [optlib](https://github.com/dbrojas/optlib) ⭐ 1,633 | 🐛 0 | 🌐 Python | 📅 2022-11-18 - `Python` - A library for financial options pricing written in Python.
* [PyQL](https://github.com/enthought/pyql) ⭐ 1,340 | 🐛 20 | 🌐 Cython | 📅 2026-07-17 - `Python` - QuantLib's Python port.
* [finance.js](https://github.com/ebradyjobory/finance.js) ⭐ 1,271 | 🐛 31 | 🌐 JavaScript | 📅 2023-03-02 - `JavaScript` - A JavaScript library for common financial calculations.
* [QuantPy](https://github.com/jsmidt/QuantPy) ⭐ 1,058 | 🐛 17 | 🌐 Python | 📅 2023-05-25 - `Python` - A framework for quantitative finance In python.
* [vollib](https://github.com/vollib/vollib) ⭐ 1,023 | 🐛 4 | 🌐 Python | 📅 2023-06-05 - `Python` - vollib is a python library for calculating option prices, implied volatility and greeks.
* [Strata](https://strata.opengamma.io/) - `Java` - Modern open-source analytics and market risk library designed and written in Java. [GitHub](https://github.com/OpenGamma/Strata) ⭐ 964 | 🐛 91 | 🌐 Java | 📅 2026-09-07
* [Finance-Python](https://github.com/alpha-miner/Finance-Python) ⭐ 913 | 🐛 9 | 🌐 Python | 📅 2024-01-01 - `Python` - Python tools for Finance.
* [quantmod](https://cran.r-project.org/web/packages/quantmod/index.html) - `R` - Quantitative Financial Modelling Framework. [GitHub](https://github.com/joshuaulrich/quantmod) ⭐ 906 | 🐛 87 | 🌐 R | 📅 2026-07-03
* [Q-Fin](https://github.com/RomanMichaelPaolucci/Q-Fin) ⭐ 661 | 🐛 1 | 🌐 Python | 📅 2023-10-31 - `Python` - A Python library for mathematical finance.
* [Quantsbin](https://github.com/quantsbin/Quantsbin) ⭐ 651 | 🐛 3 | 🌐 Python | 📅 2023-07-06 - `Python` - Tools for pricing and plotting of vanilla option prices, greeks and various other analysis around them.
* [pysabr](https://github.com/ynouri/pysabr) ⭐ 625 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2022-04-21 - `Python` - SABR model Python implementation.
* [finmath.net](https://www.finmath.net/) - `Java` - Java library with algorithms and methodologies related to mathematical finance. [GitHub](https://github.com/finmath/finmath-lib) ⭐ 582 | 🐛 8 | 🌐 Java | 📅 2026-08-29
* [optionlab](https://github.com/rgaveiga/optionlab) ⭐ 568 | 🐛 6 | 🌐 Python | 📅 2026-09-09 - `Python` - A Python library for evaluating option trading strategies.
* [financial-engineering](https://github.com/federicomariamassari/financial-engineering) ⭐ 547 | 🐛 0 | 🌐 Python | 📅 2017-11-20 - `Python` - Applications of Monte Carlo methods to financial engineering projects, in Python.
* [pynance](https://github.com/GriffinAustin/pynance) ⭐ 478 | 🐛 8 | 🌐 Python | 📅 2021-02-03 - `Python` - Lightweight Python library for assembling and analyzing financial data.
* [py\_vollib](https://github.com/vollib/py_vollib) ⭐ 434 | 🐛 1 | 🌐 Python | 📅 2026-05-29 - `Python` - vollib Python implementation.
* [tia](https://github.com/bpsmith/tia) ⭐ 427 | 🐛 41 | 🌐 Python | 📅 2023-02-15 - `Python` - Toolkit for integration and analysis.
* [QuantMath](https://github.com/MarcusRainbow/QuantMath) ⭐ 409 | 🐛 21 | 🌐 Rust | 📅 2023-06-16 - `Rust` - Financial maths library for risk-neutral pricing and risk.
* [willowtree](https://github.com/federicomariamassari/willowtree) ⭐ 384 | 🐛 1 | 🌐 Python | 📅 2018-07-14 - `Python` - Robust and flexible Python implementation of the willow tree lattice for derivatives pricing.
* [rateslib](https://github.com/attack68/rateslib) ⭐ 358 | 🐛 24 | 📅 2026-05-20 - `Python` - A fixed income library for pricing bonds and bond futures, and derivatives such as IRS, cross-currency and FX swaps.
* [finoptions](https://github.com/bbcho/finoptions-dev) ⭐ 300 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-02-01 - `Python` - Complete python implementation of R package fOptions with partial implementation of fExoticOptions for pricing various options.
* [StochVolModels](https://github.com/ArturSepp/StochVolModels) ⭐ 236 | 🐛 0 | 🌐 Python | 📅 2026-09-14 - `Python` - Pricing analytics and Monte Carlo simulation for stochastic volatility models, including the log-normal SV model and the Heston model.
* [quantcomponents](https://github.com/lsgro/quantcomponents) ⭐ 169 | 🐛 4 | 🌐 Java | 📅 2018-07-28 - `Java` - Free Java components for Quantitative Finance and Algorithmic Trading.
* [JQuantLib](https://github.com/frgomes/jquantlib) ⭐ 155 | 🐛 8 | 🌐 Java | 📅 2016-03-14 - `Java` - JQuantLib is a free, open-source, comprehensive framework for quantitative finance, written in 100% Java.
* [fypy](https://github.com/jkirkby3/fypy) ⭐ 147 | 🐛 2 | 🌐 Python | 📅 2025-02-27 - `Python` - Vanilla and exotic option pricing library to support quantitative R\&D. Focus on pricing interesting/useful models and contracts (including and beyond Black-Scholes), as well as calibration of financial models to market data.
* [QuantLib.jl](https://github.com/pazzo83/QuantLib.jl) ⭐ 144 | 🐛 10 | 🌐 Julia | 📅 2020-02-18 - `Julia` - Quantlib implementation in pure Julia.
* [quantfin](https://github.com/boundedvariation/quantfin) ⭐ 140 | 🐛 0 | 🌐 Haskell | 📅 2019-04-06 - `Haskell` - quant finance in pure haskell.
* [RQuantLib](https://github.com/eddelbuettel/rquantlib) ⭐ 136 | 🐛 9 | 🌐 C++ | 📅 2026-07-26 - `R` - RQuantLib connects GNU R with QuantLib.
* [Kelly-Criterion](https://github.com/deltaray-io/kelly-criterion) ⭐ 116 | 🐛 4 | 🌐 Python | 📅 2022-12-08 - `Python` - Kelly Criterion implemented in Python to size portfolios based on J. L. Kelly Jr's formula.
* [Intrinsic-Value-Calculator](https://github.com/akashaero/Intrinsic-Value-Calculator) ⭐ 98 | 🐛 1 | 🌐 Python | 📅 2025-07-02 - `Python` - A Python tool for quick calculations of a stock's fair value using Discounted Cash Flow analysis.
* [Miletus.jl](https://github.com/JuliaComputing/Miletus.jl) ⭐ 93 | 🐛 5 | 🌐 Julia | 📅 2025-12-09 - `Julia` - A financial contract definition, modeling language, and valuation framework.
* [AbsBox](https://github.com/yellowbean/AbsBox) ⭐ 71 | 🐛 10 | 🌐 Python | 📅 2026-08-23 - `Python` - A Python based library to model cashflow for structured product like Asset-backed securities (ABS) and Mortgage-backed securities (MBS).
* [R-fixedincome](https://github.com/wilsonfreitas/R-fixedincome) ⭐ 64 | 🐛 16 | 🌐 R | 📅 2025-05-10 - `R` - Fixed income tools for R.
* [QuantScale](https://github.com/choucrifahed/quantscale) ⭐ 51 | 🐛 0 | 🌐 Scala | 📅 2014-02-06 - `Scala` - Scala Quantitative Finance Library.
* [Pyderivatives](https://github.com/Julian-Beatty/Pyderivatives) ⭐ 48 | 🐛 0 | 🌐 HTML | 📅 2026-07-22 - `Python` - Toolkit for option pricing, implied volatility surfaces, risk-neutral densities, and pricing kernel surfaces with support for advanced models including Heston, Kou, and Bates.
* [Haxcel](https://github.com/MarcusRainbow/Haxcel) ⭐ 38 | 🐛 0 | 🌐 Rust | 📅 2022-09-13 - `Haskell` - Excel Addin for Haskell.
* [derivmkts](https://cran.r-project.org/web/packages/derivmkts/index.html) - `R` - Functions and R Code to Accompany Derivatives Markets. [GitHub](https://github.com/rmcd1024/derivmkts) ⭐ 37 | 🐛 9 | 🌐 HTML | 📅 2026-02-12
* [r-quant](https://github.com/artyyouth/r-quant) ⭐ 35 | 🐛 0 | 🌐 R | 📅 2014-02-19 - `R` - R code for quantitative analysis in finance.
* [quantra](https://github.com/joseprupi/quantraserver) ⭐ 29 | 🐛 8 | 🌐 C++ | 📅 2026-08-05 - `Python` - High-performance pricing engine built on QuantLib. It exposes QuantLib's functionality through gRPC and REST APIs, enabling distributed computations with FlatBuffers serialization.
* [FinCal](https://github.com/felixfan/FinCal) ⭐ 25 | 🐛 0 | 🌐 R | 📅 2025-10-30 - `R` - Package for time value of money calculation, time series analysis and computational finance.
* [vanilla-option-pricers](https://github.com/ArturSepp/VanillaOptionPricers) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2026-09-14 - `Python` - Fast, vectorised Black-Scholes-Merton and Bachelier pricers and implied volatility fitters, including inverse options for crypto derivatives.
* [pypme](https://github.com/ymyke/pypme) ⭐ 14 | 🐛 4 | 🌐 Python | 📅 2026-01-16 - `Python` - PME (Public Market Equivalent) calculation.
* [fmbasics](https://github.com/imanuelcostigan/fmbasics) ⭐ 12 | 🐛 7 | 🌐 R | 📅 2022-02-01 - `R` - Financial Market Building Blocks.
* [QuantOracle](https://github.com/QuantOracledev/quantoracle) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-15 - `Python` - Free quant finance API with 63 deterministic endpoints + 15 free interactive calculators at [quantoracle.dev](https://quantoracle.dev). Options pricing with full Greeks, Monte Carlo, Kelly, VaR, Sharpe, CAGR, crypto liquidation, impermanent loss, plus live crypto volatility/funding data and 24/7 position monitoring with webhook alerts. 1,000 free calls/day, no API key.
* [Scala Quant](https://github.com/frankcash/Scala-Quant) ⭐ 10 | 🐛 1 | 🌐 Scala | 📅 2017-05-06 - `Scala` - Scala library for working with stock data from IFTTT recipes or Google Finance.
* [credule](https://github.com/blenezet/credule) ⭐ 7 | 🐛 1 | 🌐 HTML | 📅 2015-08-05 - `R` - Credit Default Swap Functions.
* [flashalpha](https://github.com/FlashAlpha-lab/flashalpha-python) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-09-09 - `Python` - Python client for the FlashAlpha options analytics API.
* [options.studies](https://github.com/taylorizing/options.studies) ⭐ 6 | 🐛 0 | 🌐 R | 📅 2015-12-17 - `R` - options trading studies functions for use with options.data package and shiny.
* [Ffinar](https://github.com/MarcusRainbow/Ffinar) ⭐ 5 | 🐛 0 | 🌐 Haskell | 📅 2022-03-05 - `Haskell` - A financial maths library in Haskell.
* [mortgagemath](https://github.com/murraystokely/mortgagemath) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-08-24 - `Python` - Cent-accurate mortgage amortization schedules with Decimal arithmetic and published-source validation across six countries.
* [QoX](https://github.com/bboutelje/qox-python-samples) ⭐ 4 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-07-20 - `Python` - Finite difference pricing library written in Rust.
* [BDE Score](https://github.com/hbhqq9/bde-score) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2026-08-01 - `Python` - Multi-factor quantitative stock analysis MCP server for US, HK, and CN A-share markets. Transparent 0-100 scoring from 40+ indicators. Listed on Official MCP Registry.
* [implied-expectations](https://github.com/Keenan-ux/implied-expectations) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-07-02 - `Python` - Reverse DCF that solves for the revenue growth, duration, and operating margin a stock price implies, from SEC EDGAR fundamentals.
* [hagan-sabr](https://github.com/moshejs/hagan-sabr) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - SABR stochastic-volatility model (Hagan 2002 lognormal/normal expansions, Obłój correction, smile calibration); zero dependencies, matches QuantLib's sabrVolatility to 1e-9.
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
* [DRIP](https://lakshmidrip.github.io/DRIP/) - `Java` - Fixed Income, Asset Allocation, Transaction Cost Analysis, XVA Metrics Libraries.

## Technical Indicators

* [TA-Lib Python](https://github.com/TA-Lib/ta-lib-python) ⭐ 12,246 | 🐛 137 | 🌐 Cython | 📅 2026-09-14 - `Python` - Python wrapper for TA-Lib (<https://ta-lib.org/>).
* [ta](https://github.com/bukosabino/ta) ⭐ 5,222 | 🐛 158 | 🌐 Jupyter Notebook | 📅 2026-03-18 - `Python` - Technical Analysis Library using Pandas (Python).
* [ta4j](https://github.com/ta4j/ta4j) ⭐ 2,488 | 🐛 14 | 🌐 Java | 📅 2026-09-15 - `Java` - A Java library for technical analysis.
* [IndicatorGo](https://github.com/cinar/indicator) ⭐ 1,759 | 🐛 37 | 🌐 Go | 📅 2026-09-14 - `Golang` - IndicatorGo is a Golang module providing various stock technical analysis indicators, strategies, and a backtest framework for trading.
* [pandas\_talib](https://github.com/femtotrader/pandas_talib) ⭐ 784 | 🐛 15 | 🌐 Python | 📅 2018-05-30 - `Python` - A Python Pandas implementation of technical analysis indicators.
* [talipp](https://github.com/nardew/talipp) ⭐ 537 | 🐛 31 | 🌐 Python | 📅 2025-09-09 - `Python` - Incremental technical analysis library for Python.
* [bta-lib](https://github.com/mementum/bta-lib) ⭐ 502 | 🐛 23 | 🌐 Python | 📅 2022-01-25 - `Python` - Technical Analysis library in pandas for backtesting algotrading and quantitative analysis.
* [lppls](https://github.com/Boulder-Investment-Technologies/lppls) ⭐ 477 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2026-05-30 - `Python` - A Python module for fitting the [Log-Periodic Power Law Singularity (LPPLS)](https://en.wikipedia.org/wiki/Didier_Sornette#The_JLS_and_LPPLS_models) model.
* [IndicatorTS](https://github.com/cinar/indicatorts) ⭐ 473 | 🐛 30 | 🌐 TypeScript | 📅 2026-09-10 - `JavaScript` - Indicator is a TypeScript module providing various stock technical analysis indicators, strategies, and a backtest framework for trading.
* [TTR](https://github.com/joshuaulrich/TTR) ⭐ 349 | 🐛 32 | 🌐 R | 📅 2026-02-28 - `R` - Technical Trading Rules.
* [Indicators.jl](https://github.com/JTAmos/Indicators.jl) ⭐ 228 | 🐛 19 | 🌐 Julia | 📅 2022-12-06 - `Julia` - Financial market technical analysis & indicators on top of Temporal.
* [streaming\_indicators](https://github.com/mr-easy/streaming_indicators) ⭐ 154 | 🐛 0 | 🌐 Python | 📅 2025-04-27 - `Python` - A python library for computing technical analysis indicators on streaming data.
* [MarketTechnicals.jl](https://github.com/JuliaQuant/MarketTechnicals.jl) ⭐ 131 | 🐛 19 | 🌐 Julia | 📅 2021-11-05 - `Julia` - Technical analysis of financial time series on top of TimeSeries.
* [TradeAggregation](https://github.com/MathisWellmann/trade_aggregation-rs) ⭐ 120 | 🐛 2 | 🌐 Rust | 📅 2026-02-05 - `Rust` - Aggregate trades into user-defined candles using information driven rules.
* [Tulipy](https://github.com/cirla/tulipy) ⭐ 93 | 🐛 0 | 📅 2019-04-11 - `Python` - Financial Technical Analysis Indicator Library (Python bindings for [tulipindicators](https://github.com/TulipCharts/tulipindicators) ⭐ 944 | 🐛 35 | 🌐 C | 📅 2024-02-02).
* [orderflow](https://github.com/tiagosiebler/orderflow) ⭐ 83 | 🐛 6 | 🌐 TypeScript | 📅 2025-03-31 - `JavaScript` - Orderflow trade aggregator for building Footprint Candles from exchange websocket data.
* [SlidingFeatures](https://github.com/MathisWellmann/sliding_features-rs) ⭐ 80 | 🐛 0 | 🌐 Rust | 📅 2026-06-29 - `Rust` - Chainable tree-like sliding windows for signal processing and technical analysis.
* [Wickra](https://github.com/wickra-lib/wickra) ⭐ 55 | 🐛 0 | 🌐 Rust | 📅 2026-09-15 - `Rust` `Python` `JavaScript` `C++` `C#` `Golang` `Java` `R` - Streaming-first technical-analysis library with a Rust core: 514 indicators updating in O(1) per tick, with bit-exact batch-vs-streaming results.
* [TALib.jl](https://github.com/femtotrader/TALib.jl) ⭐ 53 | 🐛 15 | 🌐 Julia | 📅 2017-08-22 - `Julia` - A Julia wrapper for TA-Lib.
* [OnlineTechnicalIndicators.jl](https://github.com/femtotrader/OnlineTechnicalIndicators.jl) ⭐ 35 | 🐛 0 | 🌐 Julia | 📅 2026-09-07 - `Julia` - Julia Technical Analysis Indicators via online algorithms.
* [fin-primitives](https://github.com/Mattbusel/fin-primitives) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2026-03-23 - `Rust` - Financial market primitives in Rust: Price/Quantity/Symbol newtypes, BTreeMap order book, OHLCV aggregation, SMA/EMA/RSI indicators, position ledger with PnL, and composable risk monitor.
* [QuantWave](https://github.com/lavs9/quantwave) ⭐ 12 | 🐛 2 | 🌐 Rust | 📅 2026-09-15 - `Python` `Rust` `Polars` - Polars-native technical analysis and backtesting with bit-identical batch and streaming parity, plus an agent skill for consistent research-to-live strategy code.
* [TechnicalIndicatorCharts.jl](https://github.com/g-gundam/TechnicalIndicatorCharts.jl) ⭐ 8 | 🐛 0 | 🌐 Julia | 📅 2026-08-08 - `Julia` - Visualize OnlineTechnicalIndicators.jl using LightweightCharts.jl.
* [wickworks](https://github.com/psyb0t/docker-wickworks) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-09-05 - `REST` `MCP` - Stateless OHLC analyzer: POST bars and requested indicators, get back RSI/MACD/Bollinger/ADX/ATR/VWAP/Ichimoku plus smart-money-concept primitives (order blocks, FVGs, BOS/CHoCH, swing structure). No database, no AI signals.

## Trading & Backtesting

* [freqtrade](https://github.com/freqtrade/freqtrade) ⭐ 54,418 | 🐛 30 | 🌐 Python | 📅 2026-09-15 - `Python` - Free, open source crypto trading bot.

* [Qlib](https://github.com/microsoft/qlib) ⭐ 48,581 | 🐛 478 | 🌐 Python | 📅 2026-09-02 - `Python` - An AI-oriented Quantitative Investment Platform by Microsoft. Full ML pipeline of data processing, model training, back-testing; and covers the entire chain of quantitative investment: alpha seeking, risk modeling, portfolio optimization, and order execution.

* [vnpy](https://github.com/vnpy/vnpy) ⭐ 45,395 | 🐛 25 | 🌐 Python | 📅 2026-09-13 - `Python` - VeighNa is a Python-based open source quantitative trading system development framework.

* [ccxt](https://github.com/ccxt/ccxt) ⭐ 44,002 | 🐛 727 | 🌐 Rust | 📅 2026-09-15 - `JavaScript` `Python` `PHP` - A JavaScript / Python / PHP cryptocurrency trading API with support for more than 100 bitcoin/altcoin exchanges.

* [Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) ⭐ 33,480 | 🐛 25 | 🌐 Python | 📅 2026-09-14 - `Python` - Natural-language multi-agent finance research agent with 29 swarm presets, 70 skills, and 28 auto-discovered tools; 7 backtest engines covering A-shares/US/Crypto/Futures/Forex/Options plus a cross-market CompositeEngine with shared capital pool; 5-source auto-fallback data layer (tushare/okx/yfinance/akshare/ccxt); 17-tool MCP server; includes trade-journal behavioral diagnostics for 同花顺/东财/富途 exports.

* [nautilus\_trader](https://github.com/nautechsystems/nautilus_trader) ⭐ 28,971 | 🐛 131 | 🌐 Rust | 📅 2026-09-15 - `Python` `Rust` - A high-performance algorithmic trading platform and event-driven backtester.

* [backtrader](https://github.com/mementum/backtrader) ⭐ 23,258 | 🐛 63 | 🌐 Python | 📅 2024-08-19 - `Python` - Python Backtesting library for trading strategies.

* [Lean](https://github.com/QuantConnect/Lean) ⭐ 21,639 | 🐛 251 | 🌐 C# | 📅 2026-09-14 - `Python` `C#` - Lean Algorithmic Trading Engine by QuantConnect (Python, C#).

* [QuantConnect](https://github.com/QuantConnect/Lean) ⭐ 21,639 | 🐛 251 | 🌐 C# | 📅 2026-09-14 - `CSharp` - Lean Engine is an open-source fully managed C# algorithmic trading engine built for desktop and cloud usage.

* [machine-learning-for-trading](https://github.com/stefan-jansen/machine-learning-for-trading) ⭐ 20,904 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2026-09-15 - `Python` - Code and resources for Machine Learning for Algorithmic Trading.

* [zipline](https://github.com/quantopian/zipline) ⭐ 20,095 | 🐛 368 | 🌐 Python | 📅 2024-02-13 - `Python` - Pythonic algorithmic trading library.

* [FinRL](https://github.com/AI4Finance-Foundation/FinRL) ⭐ 16,287 | 🐛 312 | 🌐 Jupyter Notebook | 📅 2026-07-13 - `Python` - A Deep Reinforcement Learning Library for Automated Trading in Quantitative Finance. NeurIPS 2020.

* [QUANTAXIS](https://github.com/yutiansut/quantaxis) ⭐ 11,194 | 🐛 240 | 🌐 Python | 📅 2026-09-01 - `Matlab` - Integrated Quantitative Toolbox with Matlab.

* [StockSharp](https://github.com/StockSharp/StockSharp) ⭐ 10,752 | 🐛 3 | 🌐 C# | 📅 2026-09-15 - `CSharp` - Algorithmic trading and quantitative trading open source platform to develop trading robots (stock markets, forex, crypto, bitcoins, and options).

* [vectorbt](https://github.com/polakowo/vectorbt) ⭐ 9,097 | 🐛 140 | 🌐 Python | 📅 2026-08-02 - `Python` - Find your trading edge, using a powerful toolkit for backtesting, algorithmic trading, and research.

* [jesse](https://github.com/jesse-ai/jesse) ⭐ 8,517 | 🐛 16 | 🌐 Python | 📅 2026-09-14 - `Python` - An advanced crypto trading bot written in Python.

* [quantstats](https://github.com/ranaroussi/quantstats) ⭐ 7,636 | 🐛 33 | 🌐 Python | 📅 2026-07-20 - `Python` - Portfolio analytics for quants, written in Python.

* [rqalpha](https://github.com/ricequant/rqalpha) ⭐ 6,769 | 🐛 32 | 🌐 Python | 📅 2026-09-08 - `Python` - A extendable, replaceable Python algorithmic backtest && trading framework supporting multiple securities.

* [OctoBot](https://github.com/Drakkar-Software/OctoBot) ⭐ 6,576 | 🐛 168 | 🌐 Python | 📅 2026-09-15 - `Python` - Open source cryptocurrency trading bot for high frequency, arbitrage, TA and social trading with an advanced web interface.

* [hftbacktest](https://github.com/nkaz001/hftbacktest) ⭐ 4,690 | 🐛 17 | 🌐 Rust | 📅 2025-12-23 - `Python` - A high-frequency trading and market-making backtesting tool accounts for limit orders, queue positions, and latencies, utilizing full tick data for trades and order books.

* [zvt](https://github.com/zvtvz/zvt) ⭐ 4,304 | 🐛 22 | 🌐 Python | 📅 2026-07-01 - `Python` - the project using sql, pandas to provide an uniform and extendable way to record data, computing factors, select securities, backtesting, realtime trading and it could show all of them in clearly charts in realtime.

* [finmarketpy](https://github.com/cuemacro/finmarketpy) ⭐ 3,806 | 🐛 43 | 🌐 Python | 📅 2026-04-16 - `Python` - Python library for backtesting trading strategies and analyzing financial markets.

* [PyBroker](https://github.com/edtechre/pybroker) ⭐ 3,541 | 🐛 7 | 🌐 Python | 📅 2026-09-14 - `Python` - Algorithmic Trading with Machine Learning.

* [pysystemtrade](https://github.com/pst-group/pysystemtrade) ⭐ 3,513 | 🐛 35 | 🌐 Python | 📅 2026-07-18 - `Python` - pysystemtrade is the open source version of Robert Carver's backtesting and trading engine that implements systems according to the framework outlined in his book "Systematic Trading", which is further developed on his blog.

* [Hikyuu](https://github.com/fasiondog/hikyuu) ⭐ 3,504 | 🐛 4 | 🌐 C++ | 📅 2026-09-12 - `Python` `C++` - A base on Python/C++ open source high-performance quant framework for faster analysis and backtesting, contains the complete trading system components for reuse and combination.

* [Hikyuu](https://github.com/fasiondog/hikyuu) ⭐ 3,504 | 🐛 4 | 🌐 C++ | 📅 2026-09-12 - `Python` `C++` - A base on Python/C++ open source high-performance quant framework for faster analysis and backtesting, contains the complete trading system components for reuse and combination. You can use python or c++ freely.

* [algorithmic-trading-with-python](https://github.com/chrisconlan/algorithmic-trading-with-python) ⭐ 3,485 | 🐛 6 | 🌐 Python | 📅 2021-06-01 - `Python` - Free `pandas` and `scikit-learn` resources for trading simulation, backtesting, and machine learning on financial data.

* [QSTrader](https://github.com/mhallsmoore/qstrader) ⭐ 3,463 | 🐛 16 | 🌐 Python | 📅 2024-06-30 - `Python` - QSTrader backtesting simulation engine.

* [bt](https://github.com/pmorissette/bt) ⭐ 2,983 | 🐛 13 | 🌐 Python | 📅 2026-09-14 - `Python` - Flexible Backtesting for Python.

* [Blankly](https://github.com/Blankly-Finance/Blankly) ⭐ 2,475 | 🐛 39 | 🌐 Python | 📅 2024-12-30 - `Python` - Fully integrated backtesting, paper trading, and live deployment.

* [bulbea](https://github.com/achillesrasquinha/bulbea) ⭐ 2,331 | 🐛 37 | 🌐 Python | 📅 2021-01-17 - `Python` - Deep Learning based Python Library for Stock Market Prediction and Modelling.

* [Barter](https://github.com/barter-rs/barter-rs) ⭐ 2,287 | 🐛 89 | 🌐 Rust | 📅 2026-08-24 - `Rust` - Open-source Rust framework for building event-driven live-trading & backtesting systems.

* [Investing algorithm framework](https://github.com/coding-kitties/investing-algorithm-framework) ⭐ 2,070 | 🐛 77 | 🌐 Python | 📅 2026-09-11 - `Python` - Framework for developing, backtesting, and deploying automated trading algorithms.

* [Lumibot](https://github.com/Lumiwealth/lumibot) ⭐ 2,063 | 🐛 91 | 🌐 Python | 📅 2026-09-14 - `Python` - Algorithmic trading framework where the same code runs for backtesting and live trading across stocks, options, crypto, futures, and forex with multiple brokers including Alpaca, Interactive Brokers, Tradier, and Schwab.

* [zipline-reloaded](https://github.com/stefan-jansen/zipline-reloaded) ⭐ 1,939 | 🐛 44 | 🌐 Python | 📅 2026-01-06 - `Python` - Zipline, a Pythonic Algorithmic Trading Library.

* [Intelligent Trading Bot](https://github.com/asavinov/intelligent-trading-bot) ⭐ 1,874 | 🐛 46 | 🌐 Python | 📅 2026-08-30 - `Python` - Automatically generating signals and trading based on machine learning and feature engineering.

* [fastquant](https://github.com/enzoampil/fastquant) ⭐ 1,756 | 🐛 82 | 🌐 Jupyter Notebook | 📅 2023-09-15 - `Python` - fastquant allows you to easily backtest investment strategies with as few as 3 lines of python code.

* [AlphaPy](https://github.com/ScottfreeLLC/AlphaPy) ⭐ 1,752 | 🐛 19 | 🌐 Python | 📅 2025-08-24 - `Python` - Automated Machine Learning \[AutoML] with Python, scikit-learn, Keras, XGBoost, LightGBM, and CatBoost.

* [PandoraTrader](https://github.com/pegasusTrader/PandoraTrader) ⭐ 1,469 | 🐛 8 | 🌐 C++ | 📅 2025-10-18 - `CPP` - A C++ CTP trading framework, with very clear logic.

* [tda-api](https://github.com/alexgolec/tda-api) ⭐ 1,324 | 🐛 39 | 🌐 Python | 📅 2024-06-16 - `Python` - Gather data and trade equities, options, and ETFs via TDAmeritrade.

* [qf-lib](https://github.com/quarkfin/qf-lib) ⭐ 967 | 🐛 13 | 🌐 Python | 📅 2026-08-31 - `Python` - QF-Lib is a Python library that provides high quality tools for quantitative finance.

* [basana](https://github.com/gbeced/basana) ⭐ 866 | 🐛 1 | 🌐 Python | 📅 2026-08-09 - `Python` - A Python async and event driven framework for algorithmic trading, with a focus on crypto currencies.

* [aat](https://github.com/AsyncAlgoTrading/aat) ⭐ 834 | 🐛 1 | 🌐 C++ | 📅 2026-07-27 - `Python` - Async Algorithmic Trading Engine.

* [Quantdom](https://github.com/constverum/Quantdom) ⭐ 772 | 🐛 11 | 🌐 Python | 📅 2022-07-06 - `Python` - Python-based framework for backtesting trading strategies & analyzing financial markets \[GUI :neckbeard:.]

* [PRISM-INSIGHT](https://github.com/dragon1086/prism-insight) ⭐ 743 | 🐛 9 | 🌐 Python | 📅 2026-09-15 - `Python` - AI-powered stock analysis system with 13 specialized agents, automated trading via KIS API, supporting Korean & US markets.

* [pylivetrader](https://github.com/alpacahq/pylivetrader) ⭐ 685 | 🐛 22 | 🌐 Python | 📅 2022-10-04 - `Python` - zipline-compatible live trading library.

* [TradeFrame](https://github.com/rburkholder/trade-frame) ⭐ 677 | 🐛 3 | 🌐 C++ | 📅 2026-09-13 - `CPP` - C++ 17 based framework/library (with sample applications) for testing options based automated trading ideas using DTN IQ real time data feed and Interactive Brokers (TWS API) for trade execution. Comes with built-in [Option Greeks/IV](https://github.com/rburkholder/trade-frame/tree/master/lib/TFOptions) ⭐ 677 | 🐛 3 | 🌐 C++ | 📅 2026-09-13 calculation library.

* [qis](https://github.com/ArturSepp/QuantInvestStrats) ⭐ 633 | 🐛 1 | 🌐 Python | 📅 2026-09-14 - `Python` - Performance analytics, portfolio backtesting, risk analysis, and factsheet reporting.

* [fast-trade](https://github.com/jrmeier/fast-trade) ⭐ 594 | 🐛 5 | 🌐 Python | 📅 2026-09-14 - `Python` - A library built with backtest portability and performance in mind for backtest trading strategies.

* [Tai](https://github.com/fremantle-industries/tai) ⭐ 498 | 🐛 11 | 🌐 Elixir | 📅 2024-12-07 - `Elixir/Erlang` - Open Source composable, real time, market data and trade execution toolkit.

* [QuantSoftware Toolkit](https://github.com/QuantSoftware/QuantSoftwareToolkit) ⭐ 480 | 🐛 24 | 🌐 HTML | 📅 2017-10-02 - `Python` - Python-based open source software framework designed to support portfolio construction and management.

* [the0](https://github.com/alexanderwanyoike/the0) ⭐ 432 | 🐛 14 | 🌐 TypeScript | 📅 2026-09-01 - `Python` - Self-hosted execution engine for algorithmic trading bots. Write strategies in Python, TypeScript, Rust, C++, C#, Scala, or Haskell and deploy with one command. Each bot runs in an isolated container with scheduled or streaming execution.

* [pyqstrat](https://github.com/abbass2/pyqstrat) ⭐ 372 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2023-11-05 - `Python` - A fast, extensible, transparent python library for backtesting quantitative strategies.

* [quantstrat](https://github.com/braverock/quantstrat) ⭐ 310 | 🐛 51 | 🌐 R | 📅 2023-09-14 - `R` - Transaction-oriented infrastructure for constructing trading systems and simulation. Provides support for multi-asset class and multi-currency portfolios for backtesting and other financial research.

* [pinkfish](https://github.com/fja05680/pinkfish) ⭐ 306 | 🐛 5 | 🌐 Python | 📅 2026-09-07 - `Python` - A backtester and spreadsheet library for security analysis.

* [moonshot](https://github.com/quantrocket-llc/moonshot) ⭐ 277 | 🐛 0 | 🌐 Python | 📅 2026-07-30 - `Python` - Vectorized backtester and trading engine for QuantRocket based on Pandas.

* [Trading Strategy](https://github.com/tradingstrategy-ai/getting-started) ⭐ 249 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2026-09-13 - `Python` - TradingStrategy.ai is a market data, backtesting, live trading and investor management framework for decentralised finance.

* [Jiji](https://github.com/unageanu/jiji2) ⭐ 249 | 🐛 30 | 🌐 JavaScript | 📅 2021-04-30 - `Ruby` - Open Source Forex algorithmic trading framework using OANDA REST API.

* [StrateQueue](https://github.com/StrateQueue/StrateQueue) ⭐ 213 | 🐛 17 | 🌐 Python | 📅 2026-05-19 - `Python` - An open‑source, broker‑agnostic Python library that lets you seamlessly deploy strategies from any major backtesting engine to live (or paper) trading with zero code changes and built‑in safety controls.

* [PROJ\_Option\_Pricing\_Matlab](https://github.com/jkirkby3/PROJ_Option_Pricing_Matlab) ⭐ 211 | 🐛 1 | 🌐 MATLAB | 📅 2024-11-19 - `Matlab` - Quant Option Pricing - Exotic/Vanilla: Barrier, Asian, European, American, Parisian, Lookback, Cliquet, Variance Swap, Swing, Forward Starting, Step, Fader.

* [PyLOB](https://github.com/DrAshBooth/PyLOB) ⭐ 203 | 🐛 0 | 🌐 Python | 📅 2026-08-14 - `Python` - Fully functioning fast Limit Order Book written in Python.

* [AgentQuant](https://github.com/OnePunchMonk/AgentQuant) ⭐ 199 | 🐛 18 | 🌐 Python | 📅 2026-09-14 - `Python` - Trading-strategy research framework with iterative proposal generation, backtesting, SQLite memory, holdout evaluation, walk-forward experiments, and experimental genetic-algorithm and differential-evolution optimizers.

* [backtrader (cloudQuant fork)](https://github.com/cloudQuant/backtrader) ⭐ 177 | 🐛 0 | 🌐 Python | 📅 2026-09-14 - `Python` - Actively maintained, high-performance backtesting and live trading framework with AI-assisted strategy tooling (MCP server, skills, agent, web platform). Fork of backtrader.

* [TradeSight](https://github.com/rmbell09-lang/tradesight) ⭐ 170 | 🐛 7 | 🌐 Python | 📅 2026-07-15 - `Python` - Self-hosted AI trading platform with strategy evolution, technical analysis, backtesting, and paper trading via Alpaca.

* [pytrendseries](https://github.com/rafa-rod/pytrendseries) ⭐ 168 | 🐛 0 | 🌐 Python | 📅 2026-05-30 - `Python` - Detect trend in time series, drawdown, drawdown within a constant look-back window , maximum drawdown, time underwater.

* [Strategems.jl](https://github.com/JTAmos/Strategems.jl) ⭐ 167 | 🐛 14 | 🌐 Julia | 📅 2021-04-06 - `Julia` - Quantitative systematic trading strategy development and backtesting.

* [OrderMatchingEngine](https://github.com/PIYUSH-KUMAR1809/order-matching-engine) ⭐ 163 | 🐛 0 | 🌐 C++ | 📅 2026-09-08 - `CPP` - A production-grade, lock-free, high-frequency trading matching engine achieving 150M+ orders/sec.

* [Workbench](https://github.com/fremantle-industries/workbench) ⭐ 122 | 🐛 27 | 🌐 Elixir | 📅 2023-03-06 - `Elixir/Erlang` - From Idea to Execution - Manage your trading operation across a globally distributed cluster.

* [blotter](https://github.com/braverock/blotter) ⭐ 116 | 🐛 30 | 🌐 R | 📅 2024-12-14 - `R` - Transaction infrastructure for defining instruments, transactions, portfolios and accounts for trading systems and simulation. Provides portfolio support for multi-asset class and multi-currency portfolios. Actively maintained and developed.

* [NowTrade](https://github.com/edouardpoitras/NowTrade) ⭐ 103 | 🐛 8 | 🌐 Python | 📅 2017-02-08 - `Python` - Python library for backtesting technical/mechanical strategies in the stock and currency markets.

* [NexusFix](https://github.com/StratCraftsAI/NexusFix) ⭐ 99 | 🐛 5 | 🌐 C++ | 📅 2026-07-21 - `CPP` - C++23 FIX protocol engine with zero-copy parsing and SIMD acceleration, 3x faster than QuickFIX.

* [algobroker](https://github.com/joequant/algobroker) ⭐ 96 | 🐛 0 | 🌐 Python | 📅 2016-03-31 - `Python` - This is an execution engine for algo trading.

* [QTradeX-Algo-Trading-SDK](https://github.com/squidKid-deluxe/QTradeX-Algo-Trading-SDK) ⭐ 85 | 🐛 5 | 🌐 Python | 📅 2026-07-30 - `Python` - AI-powered SDK featuring algorithmic trading, backtesting, deployment on 100+ exchanges, and multiple optimization engines.

* [rust\_bt](https://github.com/jensnesten/rust_bt) ⭐ 83 | 🐛 1 | 🌐 Rust | 📅 2026-01-05 - `Python` - A high performance, low-latency backtesting engine for testing quantitative trading strategies on historical and live data in Rust.

* [SHORTLIST](https://github.com/zc6503204-collab/stock-strategy-dashboard) ⭐ 82 | 🐛 4 | 🌐 Python | 📅 2026-09-10 - `Python` - Local-first macOS workbench for A-share and US stock strategy screening, paper trading, position sizing, and risk alerts with read-only broker integrations.

* [LFEST](https://github.com/MathisWellmann/lfest-rs) ⭐ 82 | 🐛 0 | 🌐 Rust | 📅 2026-09-04 - `Rust` - Simulated perpetual futures exchange to trade your strategy against.

* [quantitative](https://github.com/jeffrey-liang/quantitative) ⭐ 66 | 🐛 0 | 🌐 Python | 📅 2019-03-03 - `Python` - Quantitative finance, and backtesting library.

* [Orallexa](https://github.com/alex-jb/orallexa-ai-trading-agent) ⭐ 65 | 🐛 5 | 🌐 Python | 📅 2026-07-12 - `Python` - AI trading operating system with 9 ML models (RF, XGBoost, EMAformer, MOIRAI-2, Chronos-2, DDPM, PPO RL, GNN, LR) ranked by Sharpe ratio, Claude AI synthesis with dual-tier routing (\~$0.003/analysis), real-time Next.js dashboard, Alpaca paper trading, and 277 automated tests.

* [Prop](https://github.com/fremantle-industries/prop) ⭐ 57 | 🐛 25 | 🌐 Elixir | 📅 2023-03-06 - `Elixir/Erlang` - An open and opinionated trading platform using productive & familiar open source libraries and tools for strategy research, execution and operation.

* [TDAmeritrade.DotNetCore](https://github.com/NVentimiglia/TDAmeritrade.DotNetCore) ⭐ 56 | 🐛 5 | 🌐 C# | 📅 2023-03-10 - `CSharp` - Free, open-source .NET Client for the TD Ameritrade Trading Platform. Helps developers integrate TD Ameritrade API into custom trading solutions.

* [Gunbot Quant](https://github.com/GuntharDeNiro/gunbot-quant) ⭐ 55 | 🐛 2 | 🌐 JavaScript | 📅 2025-08-19 - `Python` - Toolkit for quantitative trading analysis. It integrates an advanced market screener, a multi-strategy, multi-asset backtesting engine. Use with built-in GUI or through CLI.

* [aurumq-rl](https://github.com/yupoet/aurumq-rl) ⭐ 50 | 🐛 18 | 🌐 Python | 📅 2026-07-24 - `Python` - Reinforcement learning stock-selection framework for the China A-share market with multi-source factor input (alpha101 + main-force flow + hot-money seats + northbound + institutional + fundamentals), board-aware price limits, and ONNX CPU inference.

* [binary-martingale](https://github.com/metaperl/binary-martingale) ⭐ 48 | 🐛 1 | 🌐 Python | 📅 2017-10-16 - `Python` - Computer program to automatically trade binary options martingale style.

* [OctoBot Script](https://github.com/Drakkar-Software/OctoBot-Script) ⭐ 47 | 🐛 10 | 🌐 TypeScript | 📅 2026-09-13 - `Python` - A quant framework to create cryptocurrencies strategies - from backtesting to optimization to livetrading.

* [DeepAlpha](https://deepalphabot.com) - `Python` - AI crypto trading bot for Bybit with 70.9% walk-forward validated accuracy on out-of-sample data, LightGBM + XGBoost ensemble with 72 ML features. [GitHub](https://github.com/stefanoviana/deepalpha) ⭐ 46 | 🐛 17 | 🌐 Python | 📅 2026-05-12

* [jquantstats](https://github.com/Jebel-Quant/jquantstats) ⭐ 44 | 🐛 0 | 🌐 Python | 📅 2026-09-15 - `Python` - Modern variation of quantstats, with additional features and performance improvements.

* [Algo-Trading-Skills](https://github.com/HimanshuJ16/Algo-Trading-Skills) ⭐ 43 | 🐛 0 | 🌐 Python | 📅 2026-09-14 - `Python` `AI` `Agent-Skills` - Library of 501 agentskills.io-format skills giving AI coding agents trading-infrastructure playbooks for order idempotency, look-ahead-bias elimination, kill switches, execution algorithms and point-in-time data, each with a standalone Python reference implementation and its own unittest suite.

* [TradeClaw](https://github.com/naimkatiman/tradeclaw) ⭐ 42 | 🐛 10 | 🌐 TypeScript | 📅 2026-09-15 - `Node.js` `TypeScript` - Open-source self-hosted AI trading signal platform. Generates buy/sell signals using RSI, MACD, EMA, Bollinger Bands for forex, crypto and commodities. Deployable via Docker Compose. ([Demo](https://tradeclaw.win/dashboard))

* [PythonTradingFramework](https://github.com/JustinGuese/python_tradingbot_framework) ⭐ 39 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-09-08 - `Python` - Python algorithmic trading bot framework for Kubernetes: backtesting, hyperparameter optimization, 150+ technical analysis indicators (RSI, MACD, Bollinger Bands, ADX), portfolio management, PostgreSQL integration, Helm deployment, CronJob scheduling. Minimal overhead, production-ready, Yahoo Finance data.

* [Inalpha](https://github.com/mirror29/inalpha) ⭐ 38 | 🐛 27 | 🌐 Python | 📅 2026-09-01 - `Python` `TypeScript` - Conversational multi-agent quant framework where agents rank currently-effective factors for entry timing (time-series rank IC), write complete strategy code that passes sandboxed audit before backtesting, and evolve strategies under multi-objective fitness; every order requires machine approval and the LLM never has a direct order path.

* [TraderHarness](https://github.com/HephaestLab/TraderHarness) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2026-08-22 - `Python` - Contamination-resistant A-share backtesting environment for LLM trading agents with point-in-time masking, entity/date anonymization, fingerprinted replay, and trajectory (SFT) export.

* [purgedcv](https://github.com/eslazarev/purged-cross-validation) ⭐ 33 | 🐛 2 | 🌐 Python | 📅 2026-09-04 - `Python` - scikit-learn-compatible purged, group-purged, and combinatorial purged (CPCV) cross-validation, walk-forward splitting, and backtest-overfitting statistics (deflated and probabilistic Sharpe ratios, PBO, minimum backtest length) to prevent leakage and overfitting when backtesting trading strategies.

* [ib\_nope](https://github.com/ajhpark/ib_nope) ⭐ 33 | 🐛 4 | 🌐 Python | 📅 2021-04-22 - `Python` - Automated trading system for NOPE strategy over IBKR TWS.

* [Manifold-BT](https://github.com/manifoldbt/manifoldbt) ⭐ 31 | 🐛 3 | 🌐 Python | 📅 2026-09-14 - `Python` `Rust` - High-performance Rust-powered backtesting engine for quantitative research with parameter sweeps, walk-forward and Monte Carlo.

* [Lucky.jl](https://github.com/oliviermilla/Lucky.jl) ⭐ 29 | 🐛 4 | 🌐 Julia | 📅 2026-06-25 - `Julia` - Modular, asynchronous trading engine in pure Julia.

* [mt5-httpapi](https://github.com/psyb0t/mt5-httpapi) ⭐ 27 | 🐛 4 | 🌐 Python | 📅 2026-09-10 - `Python` `REST` `MCP` - MetaTrader 5 in a Windows VM (Docker + QEMU/KVM) over REST and MCP: market data, order/position/history management for automated trading and bots, the strategy-tester (backtesting) API, and server-side indicators (RSI/MACD/Bollinger/ADX/VWAP/Ichimoku, order blocks, FVGs). Multi-broker, multi-account.

* [TrendFollowingSystems](https://github.com/ArturSepp/TrendFollowingSystems) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2026-09-14 - `Python` - Closed-form expected returns, Sharpe ratios, and skewness of trend-following systems, with complete implementations and multi-decade futures backtests.

* [DepthSight](https://github.com/depthsight-pro/depthsight) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2026-09-13 - `Python` `TypeScript` - Self-hosted visual algo-trading platform featuring a drag-and-drop strategy builder, an AI co-pilot, and integrated billing.

* [VARRD](https://github.com/varrdinc/varrd) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2026-08-31 - `Python` - AI-powered trading edge discovery platform that validates trading ideas with event studies, statistical tests, and real market data. Web app, MCP server, CLI (`pip install varrd`), and Python SDK.

* [pyhood](https://github.com/jamestford/pyhood) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2026-09-14 - `Python` - Robinhood API client for unattended automation: after the first approved login, sessions renew from a stored refresh token with no password or device approval prompt. Covers stocks, equity and index options with Greeks, futures, IRA accounts, and the official Crypto Trading API.

* [Fastback.jl](https://github.com/rbeeli/Fastback.jl) ⭐ 21 | 🐛 1 | 🌐 Julia | 📅 2026-09-05 - `Julia` - Blazing fast Julia backtester.

* [income-desk](https://github.com/nitinblue/income-desk) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2026-09-15 - `Python` - Systematic options trading intelligence for small accounts with desk-based portfolio management, pre-trade validation, and multi-broker consolidation.

* [zipline-extensions](https://github.com/quantrocket-llc/zipline-extensions) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2020-04-17 - `Python` - Zipline extensions and adapters for QuantRocket.

* [QTradeX-AI-Agents](https://github.com/squidKid-deluxe/QTradeX-AI-Agents) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2025-05-25 - `Python` - Example strategies for the QTradeX platfrom.

* [orderbook](https://github.com/intrepidkarthi/orderbook) ⭐ 16 | 🐛 7 | 🌐 Go | 📅 2026-09-01 - `Go` `WebAssembly` - Embeddable limit order book and matching engine with integer-exact pricing, a single-writer core and write-ahead-log crash recovery, plus a microstructure research harness whose order-flow-imbalance, Kyle's lambda and CVD studies are measured against simulator ground truth.

* [antback](https://github.com/ts-kontakt/antback) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2026-08-16 - `Python` - A lightweight, event-loop-style backtest engine that allows a function-driven imperative style using efficient stateful helper functions and data containers.

* [AI Quant Agents](https://github.com/demandai/ai-quant-agents) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2026-03-24 - `Python` - Multi-agent LLM trading analysis where 12 AI agents (analysts, debaters, risk manager) debate stock picks in real-time, supporting US equities and China A-shares.

* [backtest-bias](https://github.com/Finance-broski/backtest-bias) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-09-14 - `Python` - Checks whether backtest price data is survivor-only: dead-name detection, measured bias benchmarks, CI integrity gates.

* [VerumTrade](https://github.com/muye1202/VerumTrade) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-06-29 - `Python` - A reasoning & decision-trace visible Multi-agent LLM trading-research framework where bull/bear analysts debate each ticker and every decision cites the evidence it rests on.

* [Planar.jl](https://github.com/BubbleParticles/Planar.jl) ⭐ 11 | 🐛 1 | 🌐 Julia | 📅 2026-09-13 - `Julia` - Trading framework built around CCXT with Zarr-backed OHLCV persistence, contiguity-checked data feeds, isolated-margin position management, and a loop-based backtester sharing strategy code across simulation, paper, and live modes.

* [TolmachЁv Netcode SDK](https://github.com/billionerleha-111/Tolmachev-Netcode-SDK) ⭐ 11 | 🐛 0 | 📅 2026-08-09 - `CPP` - Enterprise-grade deterministic state synchronization engine for MFT gateways and statistical arbitrage. Eliminates microsecond deltas locking order books via topological mathematics. Throughput >41.5M TPS, physical RTT 24.175 ns, atomic validation (0 CPU load). [Website](https://tuhct-sdk.store)

* [orderflow-metrics](https://github.com/twowaymind/orderflow-metrics) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-15 - `TypeScript` `Python` - Dependency-free market-microstructure metrics: order-flow imbalance (OFI), VPIN, information-driven bars, realized volatility / covariance / beta, market impact, Kyle's lambda, trade-sign classification, and limit-order-book reconstruction. Same API in TypeScript (npm) and Python (PyPI).

* [Crypto Pump Scanner](https://github.com/stefanoviana/crypto-pump-scanner) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-04-27 - `Python` - Bybit perpetual-futures trading bot with volume-spike detection, new-listing monitoring, staged take profits, and trailing stops.

* [ERN-WO Options Backtester](https://github.com/Javier-Garzo/ern-wo-options-backtester) ⭐ 8 | 🐛 0 | 🌐 Java | 📅 2026-08-16 - `Java` `Spring Boot` - Streaming backtesting engine for short-duration index options with conservative five-minute execution modeling and reproducible Early Retirement Now and WealthyOption strategy replication results.

* [quantify](https://github.com/Zhanghanser/quantify) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2026-06-30 - `Python` - Binance-style trading terminal with multi-strategy backtesting and a real-time, signal-only decision desk for crypto, A-shares, and US stocks.

* [AlgoVault](https://github.com/AlgoVaultLabs/crypto-quant-signal-mcp) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-15 - `TypeScript` - MCP server returning composite crypto trade verdicts (direction, confidence, regime) across 5 perpetual-futures venues, with cross-venue funding-rate arbitrage and an on-chain Merkle-verified track record. Free tier.

* [mx-trader-bridge](https://github.com/27dream/mx-trader-bridge) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-07-07 - `Python` - AI auto-trading bridge for East Money's miaoxiang (妙想) China A-share simulation platform; BYOK multi-LLM (OpenAI/DeepSeek/Moonshot/GLM/Qwen) decision brain → automated order placement via miaoxiang API, with daily cron review and weekly AI reflection.

* [YABTE](https://github.com/bsdz/yabte) ⭐ 7 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-02-15 - `Python` - Yet Another (Python) BackTesting Engine.

* [tw-stock-radar](https://github.com/carsonchou/tw-stock-radar) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-07-05 - `Python` - AI-powered Taiwan stock scanner for all 1,900+ TWSE/TPEX listed stocks; chips module (T86 institutional net buy/sell + TDCC 16-tier retail distribution), 13 technical indicators scored 0–100, ATR Chandelier signals with TP1/TP2, dark three.js HUD dashboard. 100% free open data, \~110 unit tests, no API key required.

* [ShowMe](https://github.com/nazmiefearmutcu/showMe) ⭐ 6 | 🐛 14 | 🌐 Python | 📅 2026-08-01 - `Python` `Rust` `TypeScript` - Open-source native macOS market cockpit. 12-timeframe consensus scan across 3370 symbols (crypto + equity + ETF + FX + commodity + bond), 23 technical indicators with per-market calibration, real WebSocket streaming. Tauri shell + Python sidecar (FastAPI) + React UI; 110+ exchanges via ccxt.

* [Dive Into Crypto](https://github.com/nazmiefearmutcu/dive-into-crypto) ⭐ 6 | 🐛 0 | 🌐 Kotlin | 📅 2026-07-27 - `Python` `Kotlin` - Binance perpetual-futures scanner with technical-indicator consensus, multi-timeframe analysis, and desktop and Android interfaces.

* [flashalpha-fill-simulator](https://github.com/FlashAlpha-lab/flashalpha-fill-simulator) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-08-26 - `Python` - Realistic limit-order fill simulator for options credit/debit spreads with post-and-wait limits, stale-quote guards, deterministic same-bar tiebreaks, and a patient-then-cross exit; engine-agnostic and zero runtime dependencies.

* [JIT-Optimization-Engine](https://github.com/cloudsealed/JIT-Optimization-Engine) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-08-09 - `Python` - High-performance analytical core using LLVM JIT (Numba) to process large-scale telemetry for quant diagnostics.

* [backtester-mcp](https://pypi.org/project/backtester-mcp/) - `Python` - Local-first backtesting engine with built-in overfitting checks (PBO, deflated Sharpe, bootstrap CI, walk-forward) and a native MCP server for AI agents. [GitHub](https://github.com/bcosm/backtester-mcp) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-04-17

* [honest-signals](https://github.com/MarvinRey7879/honest-signals) ⭐ 2 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-07-18 - `Python` - Scores detected chart patterns against the pattern-free baseline for the same market, timeframe and horizon, reporting lift with cluster-robust confidence intervals instead of a hit rate against 50%.

* [autonomous-audit](https://pypi.org/project/autonomous-audit/) - `Python` - Tamper-evident SHA-256 hash-chain audit log and human-readable report for AI trading-agent decisions; read-only, offline, and dependency-free (Python standard library only). [GitHub](https://github.com/Autonomous-Asset-Management-Agents/autonomous_/tree/main/packages/autonomous-audit) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-09-14

* [binance-fix-connector-python](https://github.com/AlexanderMerkel/binance-fix-connector-python) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-05-26 - `Python` - Async Python connector for Binance Spot FIX sessions with Order Entry, Market Data, and Drop Copy support.

* [Sextant](https://github.com/raphaub-hub/SEXTANT) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-04-05 - `Python` - Local event-driven backtesting engine with no-code strategy builder and FRED vintage, ALFRED, yFinance support.

* [mkt-alerts](https://github.com/dzianisv/mkt-alerts) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-23 - `TypeScript` - Self-hosted market-alert daemon: price, RSI/MACD/SMA conditions, and full Pine Script v5 custom indicators evaluated off-TradingView, on crypto (Coinbase) and stocks (Yahoo Finance) with no API key, delivered via ntfy push, email, or Telegram.

* [capitalcom-cli](https://github.com/SimonTarara62/capitalcom-cli) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2026-06-16 - `Python` - Unofficial CLI and async SDK for the Capital.com broker API: market data, guarded order execution, and real-time streaming.

* [FinClaw](https://github.com/IlyasFardaouix/finclaw) ⭐ 1 | 🐛 0 | 📅 2026-03-17 - `Python` - Community fork of NeuZhou's quantitative finance toolkit with backtesting, paper trading, and command-line tools.

* [NoEdge-Bench](https://github.com/nexusfinancial-dev/noedge-bench) ⭐ 1 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-07 - `Python` - Reproducible negative-result benchmark: no model beats a memoryless synthetic binary-options feed (AUC ≈ 0.50), with permutation-null tests and a look-ahead-leak case study.

* [exitkit](https://github.com/charlieyanhx/exitkit) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-11 - `Python` - Catalogue of twenty-seven position-exit policies (stop-loss, take-profit, time, volatility, signal-reversal and convergence) behind one interface, with a drop-in adapter for backtesting.py.

* [lesson-book](https://github.com/holdout-labs/lesson-book) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-08 - `Python` - Local-first deterministic tuition memory for traders: pattern-matched reminders, no LLM, overridable rule tables.

* [cl-lp-rotation-scanner](https://github.com/donnywin85/cl-lp-rotation-scanner) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-21 - `Python` - Estimates fees and impermanent loss for concentrated-liquidity pools whose volatile assets can be hedged, then backtests whether rotating capital among pools outperforms remaining in one pool. It does not execute trades or manage liquidity.

* [midas-core](https://github.com/w2ur/midas-core) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-09-10 - `Python` - Multi-agent paper-trading framework where LLM agents author orders and a separate broker process enforces fifteen fill-time safety rails; each fill is stamped with the git commit it executed against for reproducibility.

* [rulelint](https://github.com/momoddo/rulelint) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-11 - `Python` - Linter for mechanical trading-rule conditions: replays every condition over historical bars to catch look-ahead levels, dead branches that can never fire, and regime-drifted absolute thresholds before you trust a backtest.

* [falsification-ledger](https://github.com/holdout-labs/falsification-ledger) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-08 - `Python` - Hash-chained pre-registration and falsification ledger for research claims: write down what evidence would kill your claim before seeing the data; append-only JSONL with a sha256 chain (`fl verify` detects any edit), Wilson-CI hit-rate vs the random baseline, fail-closed falsification report contracts. [PyPI](https://pypi.org/project/falsification-ledger/)

* [ibkr-httpapi](https://github.com/psyb0t/ibkr-httpapi) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-01 - `Python` `REST` `MCP` - Interactive Brokers over REST and MCP (FastAPI + ib\_async over a Linux-native IB Gateway): market data (quotes, historical bars) plus order/position/execution management for automated trading across stocks, options, futures, forex, crypto and CFDs.

* [Backtesting.py](https://kernc.github.io/backtesting.py/) - `Python` - Backtest trading strategies in Python.

* [finlab](https://pypi.org/project/finlab/) - `Python` - Python package for Taiwan stock market data, factor research, and vectorized backtesting with pandas-style strategy definitions.

* [backtest](https://cran.r-project.org/web/packages/backtest/index.html) - `R` - Exploring Portfolio-Based Conjectures About Financial Instruments.

* [pa](https://cran.r-project.org/web/packages/pa/index.html) - `R` - Performance Attribution for Equity Portfolios.

* [QuantTools](https://quanttools.bitbucket.io/_site/index.html) - `R` - Enhanced Quantitative Trading Modelling.

## Portfolio Optimization & Risk Analysis

* [Ghostfolio](https://github.com/ghostfolio/ghostfolio) ⭐ 9,298 | 🐛 315 | 🌐 TypeScript | 📅 2026-09-14 - `JavaScript` - Wealth management software to keep track of financial assets like stocks, ETFs or cryptocurrencies and make solid, data-driven investment decisions.
* [pyfolio](https://github.com/quantopian/pyfolio) ⭐ 6,422 | 🐛 166 | 🌐 Jupyter Notebook | 📅 2023-12-23 - `Python` - Portfolio and risk analytics in Python.
* [PyPortfolioOpt](https://github.com/PyPortfolio/PyPortfolioOpt) ⭐ 6,029 | 🐛 113 | 🌐 Jupyter Notebook | 📅 2026-07-07 - `Python` - Financial portfolio optimization in python, including classical efficient frontier and advanced methods.
* [mlfinlab](https://github.com/hudson-and-thames/mlfinlab) ⭐ 4,924 | 🐛 49 | 🌐 Python | 📅 2023-10-02 - `Python` - Implementations regarding "Advances in Financial Machine Learning" by Marcos Lopez de Prado. (Feature Engineering, Financial Data Structures, Meta-Labeling).
* [Riskfolio-Lib](https://github.com/dcajasn/Riskfolio-Lib) ⭐ 4,496 | 🐛 18 | 🌐 C++ | 📅 2026-08-18 - `Python` - Portfolio Optimization and Quantitative Strategic Asset Allocation in Python.
* [Eiten](https://github.com/tradytics/eiten) ⭐ 3,298 | 🐛 18 | 🌐 Python | 📅 2022-07-30 - `Python` - Eiten is an open source toolkit by Tradytics that implements various statistical and algorithmic investing strategies such as Eigen Portfolios, Minimum Variance Portfolios, Maximum Sharpe Ratio Portfolios, and Genetic Algorithms based Portfolios.
* [skfolio](https://github.com/skfolio/skfolio) ⭐ 2,402 | 🐛 38 | 🌐 Python | 📅 2026-09-15 - `Python` - Python library for portfolio optimization built on top of scikit-learn. It provides a unified interface and sklearn compatible tools to build, tune and cross-validate portfolio models.
* [FinQuant](https://github.com/fmilthaler/FinQuant) ⭐ 1,822 | 🐛 18 | 🌐 Python | 📅 2023-11-04 - `Python` - A program for financial portfolio management, analysis and optimization.
* [empyrical](https://github.com/quantopian/empyrical) ⭐ 1,511 | 🐛 37 | 🌐 Python | 📅 2024-07-26 - `Python` - Common financial risk and performance metrics.
* [fecon235](https://github.com/rsvp/fecon235) ⭐ 1,278 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2023-01-20 - `Python` - Computational tools for financial economics include: Gaussian Mixture model of leptokurtotic risk, adaptive Boltzmann portfolios.
* [DeepDow](https://github.com/jankrepl/deepdow) ⭐ 1,182 | 🐛 27 | 🌐 Python | 📅 2024-01-24 - `Python` - Portfolio optimization with deep learning.
* [EigenLedger](https://github.com/santoshlite/EigenLedger) ⭐ 1,081 | 🐛 6 | 🌐 Python | 📅 2025-09-14 - `Python` - Portfolio backtesting, optimization, and risk and performance analysis.
* [universal-portfolios](https://github.com/Marigold/universal-portfolios) ⭐ 861 | 🐛 34 | 🌐 Jupyter Notebook | 📅 2026-07-31 - `Python` - Collection of algorithms for online portfolio selection.
* [pyfolio-reloaded](https://github.com/stefan-jansen/pyfolio-reloaded) ⭐ 613 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2025-12-15 - `Python` - Portfolio and risk analytics in Python. [pyfolio](https://github.com/quantopian/pyfolio) ⭐ 6,422 | 🐛 166 | 🌐 Jupyter Notebook | 📅 2023-12-23 fork.
* [riskparity.py](https://github.com/convexfi/riskparity.py) ⭐ 326 | 🐛 7 | 🌐 Python | 📅 2026-08-31 - `Python` - Fast and scalable design of risk parity portfolios.
* [fortitudo.tech](https://github.com/fortitudo-tech/fortitudo.tech) ⭐ 310 | 🐛 1 | 🌐 Python | 📅 2026-08-20 - `Python` - Conditional Value-at-Risk (CVaR) portfolio optimization and Entropy Pooling views / stress-testing in Python.
* [PerformanceAnalytics](https://github.com/braverock/PerformanceAnalytics) ⭐ 239 | 🐛 6 | 🌐 R | 📅 2026-04-13 - `R` - Econometric tools for performance and risk analysis.
* [portfolio-allocation](https://github.com/lequant40/portfolio_allocation_js) ⭐ 187 | 🐛 3 | 🌐 JavaScript | 📅 2023-03-03 - `JavaScript` - PortfolioAllocation is a JavaScript library designed to help constructing financial portfolios made of several assets: bonds, commodities, cryptocurrencies, currencies, exchange traded funds (ETFs), mutual funds, stocks...
* [visualize-wealth](https://github.com/benjaminmgross/visualize-wealth) ⭐ 150 | 🐛 0 | 🌐 Python | 📅 2015-06-10 - `Python` - Portfolio construction and quantitative analysis.
* [riskParityPortfolio](https://github.com/dppalomar/riskParityPortfolio) ⭐ 122 | 🐛 9 | 🌐 R | 📅 2022-11-15 - `R` - Blazingly fast design of risk parity portfolios.
* [empyrical-reloaded](https://github.com/stefan-jansen/empyrical-reloaded) ⭐ 121 | 🐛 7 | 🌐 Python | 📅 2025-12-12 - `Python` - Common financial risk and performance metrics. [empyrical](https://github.com/quantopian/empyrical) ⭐ 1,511 | 🐛 37 | 🌐 Python | 📅 2024-07-26 fork.
* [VisualPortfolio](https://github.com/wegamekinglc/VisualPortfolio) ⭐ 107 | 🐛 0 | 🌐 Python | 📅 2017-02-28 - `Python` - This tool is used to visualize the performance of a portfolio.
* [PortfolioAnalytics](https://github.com/braverock/PortfolioAnalytics) ⭐ 106 | 🐛 12 | 🌐 PostScript | 📅 2026-07-24 - `R` - Portfolio Analysis, Including Numerical Methods for Optimizationof Portfolios.
* [OptimalPortfolios](https://github.com/ArturSepp/OptimalPortfolios) ⭐ 94 | 🐛 0 | 🌐 Python | 📅 2026-09-14 - `Python` - Optimisation analytics for constructing and backtesting optimal multi-asset portfolios: covariance estimation, rolling optimisation, and performance reporting in one pipeline.
* [AutoHypothesis](https://github.com/arteemg/AutoHypothesis) ⭐ 73 | 🐛 0 | 🌐 Python | 📅 2026-04-29 - `Python` - An agentic framework that mimics the real quant trading pipeline to find alpha: economic hypothesis, in-sample iteration, and out-of-sample validation.
* [sparseIndexTracking](https://github.com/dppalomar/sparseIndexTracking) ⭐ 59 | 🐛 3 | 🌐 HTML | 📅 2023-05-28 - `R` - Portfolio design to track an index.
* [risktools](https://github.com/bbcho/risktools-dev) ⭐ 43 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2026-08-30 - `Python` - Risk tools for use within the crude and crude products trading space with partial implementation of R's PerformanceAnalytics.
* [factorlasso](https://github.com/ArturSepp/factorlasso) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2026-09-14 - `Python` - Sparse multi-asset factor models with cell-level sign constraints, prior-centred shrinkage, and hierarchical clustering group LASSO (HCGL); scikit-learn compatible.
* [QuantLibRisks](https://github.com/auto-differentiation/QuantLib-Risks-Py) ⭐ 21 | 🐛 5 | 🌐 Python | 📅 2026-04-02 - `Python` - Fast risks with QuantLib.
* [XAD](https://github.com/auto-differentiation/xad-py) ⭐ 20 | 🐛 12 | 🌐 Python | 📅 2026-04-02 - `Python` - Automatic Differentation (AAD) Library.
* [portfolio](https://github.com/dgerlanc/portfolio) ⭐ 17 | 🐛 0 | 🌐 R | 📅 2024-08-19 - `R` - Analysing equity portfolios.
* [RiskPerf.jl](https://github.com/rbeeli/RiskPerf.jl) ⭐ 17 | 🐛 0 | 🌐 Julia | 📅 2026-09-05 - `Julia` - Quantitative risk and performance analysis package for financial time series powered by the Julia language.
* [OnlinePortfolioAnalytics.jl](https://github.com/femtotrader/OnlinePortfolioAnalytics.jl) ⭐ 15 | 🐛 0 | 🌐 Julia | 📅 2026-09-07 - `Julia` - A Julia quantitative portfolio analytics (risk / performance) via online algorithms.
* [goal-based-allocation](https://github.com/ArturSepp/GoalBasedAllocation) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2026-09-14 - `Python` - Dynamic mean-variance portfolio allocation under regime-switching jump-diffusions with wealth floors, solved analytically via Laplace transforms.
* [etfray](https://github.com/alwank/etfray) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-06-01 - `Python` - Terminal-based ETF research and portfolio analytics application for holdings, exposure, concentration, margin, and risk workflows.
* [quantitative-finance-tools](https://github.com/omichauhan-lgtm/quantitative-finance-tools) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-12-13 - `Python` - Library for portfolio optimization (MVO) and rigorous risk metrics (VaR/CVaR).
* [fincore](https://github.com/cloudQuant/fincore) ⭐ 4 | 🐛 8 | 🌐 Python | 📅 2026-09-01 - `Python` - Quantitative performance and risk analytics with 150+ metrics, portfolio optimization, Monte Carlo simulation, and attribution; actively maintained successor to [empyrical](https://github.com/quantopian/empyrical) ⭐ 1,511 | 🐛 37 | 🌐 Python | 📅 2024-07-26/[pyfolio](https://github.com/quantopian/pyfolio) ⭐ 6,422 | 🐛 166 | 🌐 Jupyter Notebook | 📅 2023-12-23.
* [rebalance](https://github.com/cjroth/rebalance) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-02 - `JavaScript` - Interactive portfolio rebalancing tool that imports brokerage CSV data, sets target allocations, and generates trade instructions.
* [Multi-Axis Robust Portfolio Optimization](https://github.com/Viraj-Nigwekar/multi-axis-robust-portfolio-optimization) ⭐ 2 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-07-31 - `Python` - Portfolio optimization framework combining covariance shrinkage, bootstrap aggregation, and parametric scenario modeling, with reproducible notebooks and an accompanying SSRN paper.
* [riskkit](https://github.com/HasibVortex369/riskkit) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-07-02 - `Python` - Framework-agnostic risk-management toolkit for systematic trading — position sizing, drawdown control, a composable stop engine, correlation limits, and portfolio exposure caps, with adapters for backtesting.py, freqtrade, and vectorbt.
* [finance](https://pypi.org/project/finance/) - `Python` - Financial Risk Calculations. Optimized for ease of use through class construction and operator overload.
* [qfrm](https://pypi.org/project/qfrm/) - `Python` - Quantitative Financial Risk Management: awesome OOP tools for measuring, managing and visualizing risk of financial instruments and portfolios. (Last updated: 2015-12-12).
* [Prop Trader Compass](https://otto-ships.github.io/prop-trader-compass/) - `Python` - Interactive risk and payout calculator for Futures and CFD traders; features one-time fee firm comparisons.

## Factor Analysis

* [alphalens](https://github.com/quantopian/alphalens) ⭐ 4,447 | 🐛 50 | 🌐 Jupyter Notebook | 📅 2024-02-12 - `Python` - Performance analysis of predictive alpha factors.

* [Spectre](https://github.com/Heerozh/spectre) ⭐ 824 | 🐛 10 | 🌐 Python | 📅 2025-04-15 - `Python` - GPU-accelerated Factors analysis library and Backtester.

* [alphalens-reloaded](https://github.com/stefan-jansen/alphalens-reloaded) ⭐ 648 | 🐛 14 | 🌐 Python | 📅 2025-12-15 - `Python` - Performance analysis of predictive (alpha) stock factors.

* [QuantGPT](https://github.com/Miasyster/QuantGPT) ⭐ 469 | 🐛 5 | 🌐 Python | 📅 2026-05-20 - `Python` - Agent-driven A-share factor research engine with 8 MCP tools covering hypothesis design, backtesting, scoring, and anti-overfit detection.

* [Alpha Skills](https://github.com/VernonOY/alpha-skills) ⭐ 109 | 🐛 0 | 📅 2026-04-14 - `Python` - AI skills for quantitative factor research: discover, evaluate, mine, backtest, and monitor factors through any AI coding assistant. Supports A-share, HK, and US markets.

* [FactorAnalytics](https://github.com/braverock/FactorAnalytics) ⭐ 85 | 🐛 24 | 🌐 R | 📅 2024-12-12 - `R` - The FactorAnalytics package contains fitting and analysis methods for the three main types of factor models used in conjunction with portfolio construction, optimization and risk management, namely fundamental factor models, time series factor models and statistical factor models.

* [ml-quant-trading](https://github.com/initial-d/ml-quant-trading) ⭐ 84 | 🐛 4 | 🌐 Python | 📅 2026-09-08 - `Python` - PyTorch research stack for multi-factor analysis, bias correction, portfolio optimization, and reproducible backtesting.

* [Expected Returns](https://github.com/JustinMShea/ExpectedReturns) ⭐ 58 | 🐛 14 | 🌐 HTML | 📅 2025-08-12 - `R` - Solutions for enhancing portfolio diversification and replications of seminal papers with R, most of which are discussed in one of the best investment references of the recent decade, Expected Returns: An Investors Guide to Harvesting Market Rewards by Antti Ilmanen.

* [covFactorModel](https://github.com/dppalomar/covFactorModel) ⭐ 39 | 🐛 0 | 🌐 R | 📅 2019-03-25 - `R` - Covariance matrix estimation via factor models.

* [quant-lab-alpha](https://github.com/husainm97/quant-lab-alpha) ⭐ 36 | 🐛 2 | 🌐 Python | 📅 2026-05-17 - `Python` - Open-source investment analytics platform bridging academic research and retail finance.

* [Lacuna](https://github.com/eyenoticeall/Lacuna) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2026-08-31 - `Python` `Rust` - Engine-agnostic quantitative research validation for detecting leakage, overfitting, fragile results, unrealistic costs, and missing point-in-time evidence.

* [Perception-XAlpha Lite](https://github.com/xuxingjiankr-cpu/perception-xalpha-lite) ⭐ 2 | 🐛 6 | 🌐 Python | 📅 2026-09-14 - `Python` - Backtest-overfitting audit for factor research: CSCV probability of backtest overfitting, deflated Sharpe against the declared trial count, White's Reality Check, point-in-time universe membership and disclosure-date alignment. Ships a worked example in which 24 pure-noise series produce a 1.11 Sharpe and the audit says so.

* [DUEL](https://github.com/duelstocks/duel-algorithm) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-09-08 - `Python` `SEC EDGAR` - Open-source algorithm that scores two US-listed companies against each other on 8 fundamentals computed directly from SEC EDGAR XBRL data (10-K/10-Q); live comparison tool at duelstocks.com.

* [factor-qc](https://github.com/holdout-labs/factor-qc) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-08 - `Python` - Fail-closed quality gate for backtests and factor evidence: DSR/PBO/haircut/MinTRL plus a probability-calibration companion gate.

* [lookahead-free](https://github.com/holdout-labs/lookahead-free) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-08 - `Python` - Verifiable look-ahead freedom for the value-independent fragment of data pipelines, with a heuristic companion scanner for research code.

* [pit-release-gate](https://github.com/MaxWellApexLab/pit-release-gate) ⭐ 0 | 🐛 7 | 🌐 Python | 📅 2026-09-14 - `Python` - Screens cross-sectional signals for incomplete-cross-section leakage from staggered data arrival and grades per-signal release timing; ships a known-ground-truth demo reproducing its method papers.

## Sentiment Analysis & Alternative Data

* [Asset News Sentiment Analyzer](https://github.com/KVignesh122/AssetNewsSentimentAnalyzer) ⭐ 198 | 🐛 0 | 🌐 Python | 📅 2026-07-15 - `Python` - Sentiment analysis and report generation package for financial assets and securities utilizing GPT models.
* [CoWorker Fin-Agent](https://github.com/ZiwayZhao/agent-coworker) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-04-04 - `Python` - LLM-powered A-share stock analysis via P2P agent collaboration. Technical analysis (MA60, volume-price patterns, golden eye), deep research reports using proprietary methodology, and market state summaries. Analysis logic stays private via Skill-as-API protocol.
* [StockKit](https://stockkit.net/) - `TypeScript` - Free AI-powered stock research reports for US, China & HK using Claude Opus and multi-model AI with 20+ technical indicators. [GitHub](https://github.com/kentmswood-ui/stockkit) ⭐ 2 | 🐛 0 | 📅 2026-05-07
* [AlphaAI](https://alphai.io/developers) - `Python` - Pre-analyzed financial news via REST API and MCP for AI agents: per-ticker impact and sentiment, a category, and a 1-10 relevance score on every story, plus structured SEC Form 4 insider data. Free tier, no card. [GitHub](https://github.com/makeev/alphai-mcp) ⭐ 2 | 🐛 0 | 📅 2026-09-13
* [Social Stock Sentiment API](https://api.adanos.org/docs) - `Python` - REST API analyzing Reddit and X/Twitter for stock mentions and sentiment, providing buzz scores, trending stocks, and AI-generated trend explanations.

## Time Series Analysis

* [Facebook Prophet](https://github.com/facebook/prophet) ⭐ 20,402 | 🐛 454 | 🌐 Python | 📅 2026-08-27 - `Python` - Tool for producing high quality forecasts for time series data that has multiple seasonality with linear or non-linear growth.
* [statsmodels](https://www.statsmodels.org/stable/) - `Python` - Python module that allows users to explore data, estimate statistical models, and perform statistical tests. [GitHub](https://github.com/statsmodels/statsmodels) ⭐ 11,623 | 🐛 2,815 | 🌐 Python | 📅 2026-09-15
* [tsfresh](https://github.com/blue-yonder/tsfresh) ⭐ 9,424 | 🐛 74 | 🌐 Jupyter Notebook | 📅 2026-07-06 - `Python` - Automatic extraction of relevant features from time series.
* [gluon-ts](https://github.com/awslabs/gluonts) ⭐ 5,235 | 🐛 482 | 🌐 Python | 📅 2026-07-31 - `Python` - vProbabilistic time series modeling in Python.
* [PyFlux](https://github.com/RJT1990/pyflux) ⭐ 2,135 | 🐛 93 | 🌐 Python | 📅 2023-10-24 - `Python` - Python library for timeseries modelling and inference (frequentist and Bayesian) on models.
* [pmdarima](https://github.com/alkaline-ml/pmdarima) ⭐ 1,735 | 🐛 65 | 🌐 Python | 📅 2025-11-17 - `Python` - A statistical library designed to fill the void in Python's time series analysis capabilities, including the equivalent of R's auto.arima function.
* [ARCH](https://github.com/bashtage/arch) ⭐ 1,567 | 🐛 51 | 🌐 Python | 📅 2026-09-14 - `Python` - ARCH models in Python.
* [functime](https://github.com/functime-org/functime) ⭐ 1,185 | 🐛 56 | 🌐 Python | 📅 2026-05-03 - `Python` - Time-series machine learning at scale. Built with Polars for embarrassingly parallel feature extraction and forecasts on panel data.
* [tidyquant](https://github.com/business-science/tidyquant) ⭐ 914 | 🐛 95 | 🌐 R | 📅 2026-09-01 - `R` - Bringing financial analysis to the tidyverse.
* [tsmoothie](https://github.com/cerlymarco/tsmoothie) ⭐ 770 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-11-23 - `Python` - A python library for time-series smoothing and outlier detection in a vectorized way.
* [timetk](https://github.com/business-science/timetk) ⭐ 644 | 🐛 43 | 🌐 R | 📅 2025-08-29 - `R` - A toolkit for working with time series in R.
* [matrixprofile](https://github.com/matrix-profile-foundation/matrixprofile) ⭐ 384 | 🐛 31 | 🌐 Python | 📅 2023-11-29 - `R` - Time series data mining library built on top of the novel Matrix Profile data structure and algorithms.
* [TimeSeries.jl](https://github.com/JuliaStats/TimeSeries.jl) ⭐ 370 | 🐛 48 | 🌐 Julia | 📅 2026-03-30 - `Julia` - Time series toolkit for Julia.
* [tidypredict](https://tidypredict.tidymodels.org/) - `R` - Run predictions inside the database. [GitHub](https://github.com/tidymodels/tidypredict) ⭐ 264 | 🐛 5 | 🌐 R | 📅 2026-09-09
* [PineForge](https://github.com/pineforge-4pass/pineforge-engine) ⭐ 188 | 🐛 6 | 🌐 C++ | 📅 2026-09-15 - `C++` - Deterministic offline PineScript v6 → C++ backtest runtime, validated trade-for-trade against TradingView (245/246 strict, 0 engine bugs). Runs locally via Docker and is drivable by AI agents through a bundled MCP server.
* [tibbletime](https://github.com/business-science/tibbletime) ⭐ 176 | 🐛 0 | 🌐 R | 📅 2024-12-03 - `R` - Built on top of the tidyverse, tibbletime is an extension that allows for the creation of time aware tibbles through the setting of a time index.
* [garchmodels](https://github.com/AlbertoAlmuinha/garchmodels) ⭐ 37 | 🐛 6 | 🌐 R | 📅 2022-08-11 - `R` - A parsnip backend for GARCH models.
* [rugarch](https://github.com/alexiosg/rugarch) ⭐ 32 | 🐛 1 | 🌐 R | 📅 2026-07-18 - `R` - Univariate GARCH Models.
* [rmgarch](https://github.com/alexiosg/rmgarch) ⭐ 18 | 🐛 3 | 🌐 R | 📅 2026-09-11 - `R` - Multivariate GARCH Models.
* [OmniOracle](https://github.com/cesabici-bit/omni-oracle) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2026-03-23 - `Python` - Automatic discovery of non-trivial statistical relationships across 500+ time series from FRED, World Bank, EIA, and NOAA using mutual information screening, lagged MI directional testing, and FDR correction.
* [TimeFrames.jl](https://github.com/femtotrader/TimeFrames.jl) ⭐ 5 | 🐛 15 | 🌐 Julia | 📅 2026-06-22 - `Julia` - A Julia library that defines TimeFrame (essentially for resampling TimeSeries).
* [etf-pattern-match-pybind11](https://github.com/redamancy231-create/etf-pattern-match-pybind11) ⭐ 4 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-15 - `Python` `C++` - High-performance ETF pattern matching via DTW with cosine pre-filtering. 43× DTW and 58× pattern-match speedup over pure Python using pybind11/C++20. Includes Jupyter notebook with full algorithm walkthrough.
* [wasserstein-btc](https://github.com/AccursedGalaxy/wasserstein-btc) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2026-06-04 - `Python` - Distributional forecasting of crypto log-returns by tangent-space geodesic extrapolation on the 2-Wasserstein manifold (quantile-function coordinates). Walk-forward CRPS evaluation over 6.75 years across 4 assets × 3 horizons; benchmarked against classical baselines (Static / RW-Drift / HS-Bootstrap / GARCH-N / GARCH-t / GJR-GARCH-t) and a named-econometric panel (HAR-RV, CAViaR-SAV, Markov-switching Normal, FIGARCH, AR(1) Stochastic Volatility, bivariate VAR+GARCH). [Live dashboard](https://accursedgalaxy.github.io/wasserstein-btc/).
* [tseries](https://cran.r-project.org/web/packages/tseries/index.html) - `R` - Time Series Analysis and Computational Finance.
* [fGarch](https://cran.r-project.org/web/packages/fGarch/index.html) - `R` - Rmetrics - Autoregressive Conditional Heteroskedastic Modelling.
* [timeSeries](https://cran.r-project.org/web/packages/timeSeries/index.html) - `R` - Rmetrics - Financial Time Series Objects.

## Market Data & Data Sources

* [OpenBB](https://github.com/OpenBB-finance/OpenBB) ⭐ 73,031 | 🐛 115 | 🌐 Python | 📅 2026-09-14 - `Python` - Open-source financial data platform with extensible provider integrations, a Python interface, a command-line interface, and a local REST API.
* [Fincept Terminal](https://github.com/Fincept-Corporation/FinceptTerminal) ⭐ 31,656 | 🐛 4 | 🌐 C++ | 📅 2026-09-08 - `Python` - Advance Data Based A.I Terminal for all Types of Financial Asset Research.
* [yfinance](https://github.com/ranaroussi/yfinance) ⭐ 25,249 | 🐛 107 | 🌐 Python | 📅 2026-09-13 - `Python` - Yahoo! Finance market data downloader (+faster Pandas Datareader).
* [akshare](https://github.com/akfamily/akshare) ⭐ 22,589 | 🐛 8 | 🌐 Python | 📅 2026-09-09 - `Python` - AkShare is an elegant and simple financial data interface library for Python, built for human beings! <https://akshare.readthedocs.io>.
* [FinanceDatabase](https://github.com/JerBouma/FinanceDatabase) ⭐ 9,116 | 🐛 4 | 🌐 Python | 📅 2026-09-13 - `Python` - This is a database of 300.000+ symbols containing Equities, ETFs, Funds, Indices, Currencies, Cryptocurrencies and Money Markets.
* [FinanceToolkit](https://github.com/JerBouma/FinanceToolkit) ⭐ 5,342 | 🐛 10 | 🌐 Python | 📅 2026-09-10 - `Python` - Toolkit with 200+ financial metrics including 80+ financial ratios, 30+ technical indicators, 20+ risk and performance metrics and 50+ macro indicators which pulls from Financial Modeling Prep, Yahoo Finance, OECD, GMBD and more.
* [alpha\_vantage](https://github.com/RomelTorres/alpha_vantage) ⭐ 4,917 | 🐛 3 | 🌐 Python | 📅 2026-07-26 - `Python` - A python wrapper for Alpha Vantage API for financial data.
* [pandas-datareader](https://github.com/pydata/pandas-datareader) ⭐ 3,269 | 🐛 147 | 🌐 Python | 📅 2026-07-21 - `Python` - Python module to get data from various sources (Google Finance, Yahoo Finance, FRED, OECD, Fama/French, World Bank, Eurostat...) into Pandas datastructures such as DataFrame, Panel with a caching mechanism.
* [edgartools](https://github.com/dgunning/edgartools) ⭐ 2,718 | 🐛 31 | 🌐 Python | 📅 2026-09-11 - `Python` - AI-native SEC EDGAR library with XBRL financials, clean text extraction, 17+ typed forms, and pandas DataFrames.
* [findatapy](https://github.com/cuemacro/findatapy) ⭐ 2,123 | 🐛 28 | 🌐 Python | 📅 2026-07-02 - `Python` - Python library to download market data via Bloomberg, Quandl, Yahoo etc.
* [investpy](https://github.com/alvarobartt/investpy) ⭐ 1,856 | 🐛 244 | 🌐 Python | 📅 2026-04-13 - `Python` - Financial Data Extraction from Investing.com with Python! <https://investpy.readthedocs.io/>.
* [wallstreet](https://github.com/mcdallas/wallstreet) ⭐ 1,695 | 🐛 18 | 🌐 Python | 📅 2024-07-06 - `Python` - Real time stock and option data.
* [FinanceDataReader](https://github.com/FinanceData/FinanceDataReader) ⭐ 1,542 | 🐛 53 | 🌐 Python | 📅 2026-05-13 - `Python` - Open Source Financial data reader for U.S, Korean, Japanese, Chinese, Vietnamese Stocks.
* [yahoo-finance](https://github.com/yahoo-finance/yahoo-finance) ⭐ 1,446 | 🐛 88 | 🌐 Python | 📅 2023-12-25 - `Python` - Python module to get stock data from Yahoo! Finance.
* [yahooquery](https://github.com/dpguthrie/yahooquery) ⭐ 920 | 🐛 81 | 🌐 Python | 📅 2025-05-15 - `Python` - Python interface for retrieving data through unofficial Yahoo Finance API.
* [nsetools](https://github.com/vsjha18/nsetools) ⭐ 907 | 🐛 2 | 🌐 Python | 📅 2025-03-18 - `Python` - Python library for extracting real-time data from National Stock Exchange (India).
* [googlefinance](https://github.com/hongtaocai/googlefinance) ⭐ 832 | 🐛 32 | 🌐 Python | 📅 2018-09-23 - `Python` - Python module to get real-time stock data from Google Finance API.
* [defeatbeta-api](https://github.com/defeat-beta/defeatbeta-api) ⭐ 747 | 🐛 9 | 🌐 Python | 📅 2026-09-15 - `Python` - An open-source alternative to Yahoo Finance's market data APIs with higher reliability.
* [jugaad-data](https://github.com/jugaad-py/jugaad-data) ⭐ 572 | 🐛 27 | 🌐 Python | 📅 2026-08-25 - `Python` - Download historical and live stock data from NSE (National Stock Exchange of India), BSE, and RBI.
* [datamule-python](https://github.com/john-friedman/datamule-python) ⭐ 557 | 🐛 15 | 🌐 Python | 📅 2026-08-14 - `Python` - A package to work with SEC data. Incorporates datamule endpoints.
* [finagg](https://github.com/theOGognf/finagg) ⭐ 542 | 🐛 0 | 🌐 Python | 📅 2026-03-22 - `Python` - finagg is a Python package that provides implementations of popular and free financial APIs, tools for aggregating historical data from those APIs into SQL databases, and tools for transforming aggregated data into features useful for analysis and AI/ML.
* [Trading Strategy](https://github.com/tradingstrategy-ai/trading-strategy/) ⭐ 378 | 🐛 11 | 🌐 Python | 📅 2026-09-04 - `Python` - download price data for decentralised exchanges and lending protocols (DeFi).
* [tiingo](https://github.com/hydrosquall/tiingo-python) ⭐ 319 | 🐛 35 | 🌐 Python | 📅 2025-12-14 - `Python` - Python interface for daily composite prices/OHLC/Volume + Real-time News Feeds, powered by the Tiingo Data Platform.
* [pdblp](https://github.com/matthewgilbert/pdblp) ⭐ 257 | 🐛 38 | 🌐 Python | 📅 2024-12-14 - `Python` - A simple interface to integrate pandas and the Bloomberg Open API.
* [FRB](https://github.com/avelkoski/FRB) ⭐ 181 | 🐛 9 | 🌐 Python | 📅 2023-07-07 - `Python` - Python Client for FRED® API.
* [Rblpapi](https://github.com/Rblp/Rblpapi) ⭐ 177 | 🐛 39 | 🌐 C++ | 📅 2026-08-02 - `R` - An R Interface to 'Bloomberg' is provided via the 'Blp API'.
* [yliveticker](https://github.com/yahoofinancelive/yliveticker) ⭐ 173 | 🐛 0 | 🌐 Python | 📅 2026-03-28 - `Python` - Live stream of market data from Yahoo Finance websocket.
* [MarketData.jl](https://github.com/JuliaQuant/MarketData.jl) ⭐ 165 | 🐛 11 | 🌐 Julia | 📅 2026-03-30 - `Julia` - Time series market data.
* [pandas-finance](https://github.com/davidastephens/pandas-finance) ⭐ 160 | 🐛 5 | 🌐 Python | 📅 2025-03-07 - `Python` - High level API for access to and analysis of financial data.
* [tardis-python](https://github.com/tardis-dev/tardis-python) ⭐ 148 | 🐛 0 | 🌐 Python | 📅 2026-08-23 - `Python` - Python interface for Tardis.dev high frequency crypto market data.
* [pandaSDMX](https://github.com/dr-leo/pandaSDMX) ⭐ 134 | 🐛 21 | 🌐 Python | 📅 2023-12-28 - `Python` - Python package that implements SDMX 2.1 (ISO 17369:2013), a format for exchange of statistical data and metadata used by national statistical agencies, central banks, and international organisations.
* [python-bcb](https://github.com/wilsonfreitas/python-bcb) ⭐ 127 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2026-07-27 - `Python` - Python interface to Brazilian Central Bank web services.
* [finsymbols](https://github.com/skillachie/finsymbols) ⭐ 123 | 🐛 10 | 🌐 Python | 📅 2019-11-10 - `Python` - Obtains stock symbols and relating information for SP500, AMEX, NYSE, and NASDAQ.
* [market-prices](https://github.com/maread99/market_prices) ⭐ 106 | 🐛 10 | 🌐 Python | 📅 2026-09-15 - `Python` - Create meaningful OHLCV datasets from knowledge of [exchange-calendars](https://github.com/gerrymanoim/exchange_calendars) ⭐ 667 | 🐛 27 | 🌐 Python | 📅 2026-09-15 (works out-the-box with data from Yahoo Finance).
* [rb3](https://github.com/ropensci/rb3) ⭐ 103 | 🐛 24 | 🌐 R | 📅 2026-09-14 - `R` - A bunch of downloaders and parsers for data delivered from B3.
* [rbcb](https://github.com/wilsonfreitas/rbcb) ⭐ 98 | 🐛 10 | 🌐 R | 📅 2024-01-23 - `R` - R interface to Brazilian Central Bank web services.
* [ccy](https://github.com/quantmind/ccy) ⭐ 97 | 🐛 5 | 🌐 Python | 📅 2026-04-25 - `Python` - Python module for currencies.
* [lake-api](https://github.com/crypto-lake/lake-api) ⭐ 77 | 🐛 3 | 🌐 Python | 📅 2025-11-02 - `Python` - Python interface for Crypto Lake high frequency crypto market data.
* [finalytics](https://github.com/Nnamdi-sys/finalytics) ⭐ 75 | 🐛 2 | 🌐 Rust | 📅 2026-05-01 - `Rust` - A rust library for financial data analysis.
* [cif](https://github.com/LenkaV/CIF) ⭐ 66 | 🐛 10 | 🌐 Python | 📅 2022-06-18 - `Python` - Python package that include few composite indicators, which summarize multidimensional relationships between individual economic indicators.
* [tessa](https://github.com/ymyke/tessa) ⭐ 54 | 🐛 1 | 🌐 Python | 📅 2026-04-09 - `Python` - simple, hassle-free access to price information of financial assets (currently based on yfinance and pycoingecko), including search and a symbol class.
* [pybbg](https://github.com/bpsmith/pybbg) ⭐ 53 | 🐛 2 | 🌐 Python | 📅 2015-01-20 - `Python` - Python interface to Bloomberg COM APIs.
* [stock\_extractor](https://github.com/ZachLiuGIS/stock_extractor) ⭐ 52 | 🐛 4 | 🌐 Python | 📅 2022-12-26 - `Python` - General Purpose Stock Extractors from Online Resources.
* [PENDAX](https://github.com/CompendiumFi/PENDAX-SDK) ⭐ 50 | 🐛 1 | 📅 2024-05-09 - `JavaScript` - Javascript SDK for Trading/Data API and Websockets for FTX, FTXUS, OKX, Bybit, & More.
* [pricehub](https://github.com/eslazarev/pricehub) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2026-06-17 - `Python` - Unified package for collecting OHLC prices from Binance, Bybit, Coinbase, OKX, Kraken, KuCoin, and Bitget (spot & futures) into a DataFrame, with flexible timestamp inputs and a wide range of intervals.
* [cn\_stock\_src](https://github.com/jealous/cn_stock_src) ⭐ 34 | 🐛 0 | 🌐 HTML | 📅 2016-11-09 - `Python` - Utility for retrieving basic China stock data from different sources.
* [Stockex](https://github.com/cttn/Stockex) ⭐ 33 | 🐛 2 | 🌐 Python | 📅 2023-05-22 - `Python` - Python wrapper for Yahoo! Finance API.
* [CryptoExchangeAPIs.jl](https://github.com/bhftbootcamp/CryptoExchangeAPIs.jl) ⭐ 30 | 🐛 2 | 🌐 Julia | 📅 2026-07-06 - `Julia` - A Julia library for cryptocurrency exchange APIs.
* [GetTDData](https://github.com/msperlin/GetTDData) ⭐ 28 | 🐛 0 | 🌐 R | 📅 2026-09-10 - `R` - Downloads and aggregates data for Brazilian government issued bonds directly from the website of Tesouro Direto.
* [tidyfinance](https://github.com/tidy-finance/r-tidyfinance) ⭐ 27 | 🐛 3 | 🌐 R | 📅 2026-09-15 - `R` - Tidy Finance helper functions to download financial data and process the raw data into a structured Format (tidy data), including.
* [CcyConv.jl](https://github.com/bhftbootcamp/CcyConv.jl) ⭐ 25 | 🐛 0 | 🌐 Julia | 📅 2026-07-03 - `Julia` - Currency conversion library for Julia.
* [SwapAPI](https://github.com/swap-api/swap-api) ⭐ 22 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-03 - `Python` - Free DEX aggregator API returning executable swap calldata across 46 EVM chains. No API key required.
* [pystlouisfed](https://github.com/TomasKoutek/pystlouisfed) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2024-01-09 - `Python` - Python client for Federal Reserve Bank of St. Louis API - FRED, ALFRED, GeoFRED and FRASER.
* [simfinapi](https://github.com/matthiasgomolka/simfinapi) ⭐ 21 | 🐛 9 | 🌐 R | 📅 2025-08-13 - `R` - Makes 'SimFin' data (<https://www.simfin.com/>) easily accessible in R.
* [Chart Library](https://github.com/grahammccain/chart-library-mcp) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-09-10 - `Python` - Historical chart pattern similarity search API. 24M+ pre-computed embeddings across 15K+ symbols and 10 years of data using pgvector. Returns forward returns, regime analysis, and pattern detection. Also available as MCP server. [Website](https://chartlibrary.io)
* [BloombergFetch](https://github.com/ArturSepp/BloombergFetch) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2026-09-14 - `Python` - Bloomberg Desktop API data (prices, implied volatilities, fundamentals) as pandas DataFrames via blpapi.
* [td](https://github.com/eddelbuettel/td) ⭐ 19 | 🐛 0 | 🌐 R | 📅 2026-09-13 - `R` - Interfaces the 'twelvedata' API for stocks and (digital and standard) currencies.
* [exchange](https://github.com/akarat/exchange) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2015-07-07 - `Python` - Get current exchange rate.
* [edinet-mcp](https://github.com/ajtgjmdjp/edinet-mcp) ⭐ 18 | 🐛 7 | 🌐 Python | 📅 2026-09-14 - `Python` - Parse Japanese XBRL financial statements from EDINET with 161 normalized labels, 26 financial metrics, and multi-company screening.
* [yql-finance](https://github.com/slawek87/yql-finance) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2015-08-29 - `Python` - yql-finance is simple and fast. API returns stock closing prices for current period of time and current stock ticker (i.e. APPL, GOOGL).
* [ticks](https://github.com/jamescnowell/ticks) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2016-01-08 - `Python` - Simple command line tool to get stock ticker data.
* [fin-stream](https://github.com/Mattbusel/fin-stream) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2026-03-23 - `Rust` - Real-time market data streaming in Rust: lock-free SPSC ring buffer, 100K+ ticks/second ingestion, multi-timeframe OHLCV construction, and Lorentz transforms on financial time series.
* [estat-mcp](https://github.com/ajtgjmdjp/estat-mcp) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2026-08-23 - `Python` - Access Japanese government statistics (e-Stat) covering population, GDP, CPI, labor, and trade data with MCP integration and Polars export.
* [BTC Orderbook Microstructure Research](https://github.com/mznowhere/btc-orderbook-research) ⭐ 9 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-04-21 - `Jupyter Notebook` - statistical analysis of Binance BTC/USDT orderbook: OBI, CVD, spread.
* [yfinanceapi](https://github.com/Karthik005/yfinance-api) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2020-05-26 - `Python` - Finance API for Python.
* [fsynth](https://github.com/welcra/fsynth) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-08-29 - `Python` - Python library for high-fidelity unlimited synthetic financial data generation using Heston Stochastic Volatility and Merton Jump Diffusion.
* [Cambio Uruguay](https://cambio-uruguay.com) - `TypeScript` `REST` `MCP` - Collectors and public API for Uruguayan retail buy/sell exchange rates and historical series by source and quote type. [GitHub](https://github.com/eduair94/cambio-uruguay) ⭐ 7 | 🐛 5 | 🌐 TypeScript | 📅 2026-09-15
* [OpenChainBench](https://openchainbench.com) - `Go` `TypeScript` - Open benchmark harnesses for blockchain RPC latency, perpetual-market execution costs and funding, bridge quotes, and oracle price deviations. [GitHub](https://github.com/ChainBench/OpenChainBench) ⭐ 7 | 🐛 12 | 🌐 Go | 📅 2026-09-15
* [financekit-mcp](https://github.com/vdalhambra/financekit-mcp) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-04-17 - `Python` - MCP server (Model Context Protocol) exposing 17 tools for AI agents to perform quantitative analysis: real-time stock quotes, full technical analysis (RSI, MACD, Bollinger, ADX, Stochastic, ATR, OBV + pattern detection with structured verdicts), crypto prices via CoinGecko, risk metrics (VaR, Sharpe, Sortino, Beta, Max Drawdown), correlation matrix, options chains, earnings calendar, sector rotation, and portfolio analysis. Works with Claude Desktop, Cursor, Windsurf. No API keys for core tools. FastMCP 3.2.
* [The Stall](https://github.com/thebrierfox/the-stall) ⭐ 7 | 🐛 5 | 🌐 JavaScript | 📅 2026-09-14 - `JavaScript` `MCP` - Self-hostable data and analytics service with equity technical indicators, multi-chain portfolio valuation, market-data adapters, and MCP interfaces.
* [tdnet-disclosure-mcp](https://github.com/ajtgjmdjp/tdnet-disclosure-mcp) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-08-23 - `Python` - Access Japanese timely disclosures (TDNet) via MCP. Retrieve earnings, dividends, forecasts, buybacks, and other filings for 4,000+ listed companies. No API key required.
* [swiss-finance-data](https://github.com/EMen11/swiss-finance-data) ⭐ 5 | 🐛 5 | 🌐 HTML | 📅 2026-04-13 - `Python` - Python package for Swiss financial data (SNB Policy Rate, SARON, CHF FX rates, CPI, SMI equities, Confederation bond yields) from official SNB sources.
* [coinpulse](https://github.com/soutone/coinpulse-python) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-01-09 - `Python` - Python SDK for cryptocurrency portfolio tracking with real-time prices, P/L calculations, and price alerts. Free tier available.
* [disclosure-alpha](https://github.com/alwank/disclosure-alpha) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-06-30 - `Python` - Deterministic SEC filing analytics for 10-K/10-Q: section extraction, tone and boilerplate metrics, year-over-year diff, and reproducible disclosure risk scores. CLI, Python SDK, HTTP panel screener, and MCP — no LLM required.
* [bigtech-ai-stakes](https://github.com/YichengYang-Ethan/bigtech-ai-stakes) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-05-09 - `Python` - Open dataset of U.S. public-company equity stakes in Anthropic and OpenAI from primary 10-K / 10-Q / 8-K filings, court records, and press releases. Each row tagged with a confidence flag (V verified, P probable, S speculative).
* [OnlineResamplers.jl](https://github.com/femtotrader/OnlineResamplers.jl) ⭐ 3 | 🐛 2 | 🌐 Julia | 📅 2026-04-20 - `Julia` - High-performance Julia package for real-time resampling of financial market data.
* [Horus Flow](https://github.com/horustechltd/horus-flow-mcp) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-09-04 - `Python` - Order-flow analytics with order-book imbalance and rolling trade-delta calculations, plus an MCP interface.
* [AlphaSMO](https://github.com/alphasmo/alphasmo-tools) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-12 - `TypeScript` - CLI + MCP server for SEC 13F institutional holdings, Form 4 insider trading, and smart money convergence signals (tickers where hedge funds and company insiders are both buying). Free anonymous tier, no signup required.
* [yfi](https://github.com/nickelkr/yfi) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2016-02-12 - `Python` - Yahoo! YQL library.
* [twmarketdata](https://pypi.org/project/twmarketdata/) - `Python` - Client for Taiwan market data with local disclosure-date filtering, replay diagnostics and missing-session detection. [GitHub](https://github.com/TW-Market-Data/twmarketdata) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-08-29
* [SECfinAPI](https://www.secfinapi.com) - `TypeScript` - Standardized SEC EDGAR financials (income statement, balance sheet, cash flow, 40+ ratios) for \~19,000 US public companies, normalized from XBRL. REST API + MCP server for Claude/Cursor. Free tier. [GitHub](https://github.com/michalperni11-gif/secfinapi-mcp) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-03
* [bbgbridge](https://github.com/ran404/bbgbridge) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2020-01-07 - `Python` - Easy to use Bloomberg Desktop API wrapper for Python.
* [oilpriceapi](https://github.com/OilpriceAPI/python-sdk) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2026-09-13 - `Python` - Commodity-price API client with local moving averages, RSI, MACD, Bollinger Bands and ATR calculations on supplied data.
* [edgar-sec](https://github.com/toros-dev/edgar-sec) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2026-09-04 - `Python` - EDGAR Financial data API with preprocessed dataclass outputs.
* [itch-book](https://github.com/groovg/itch-book) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2026-09-07 - `Python` - NASDAQ TotalView-ITCH 5.0 day files to Parquet: BBO, trades, order-by-order messages with the resting side already resolved, and MBP depth; downloads and verifies the free emi.nasdaq.com samples.
* [treasury-fiscaldata](https://github.com/moshejs/treasury-fiscaldata) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - Typed client for the US Treasury FiscalData API (debt, average interest rates, exchange rates) with pagination and filtering; no API key required.
* [edgar-geo-revenue](https://pypi.org/project/edgar-geo-revenue/) - `Python` - Extract geographic revenue breakdowns from SEC EDGAR 10-K filings with no API key. [GitHub](https://github.com/Metricshour/edgar-geo-revenue) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-09-04
* [buried-events-parser](https://github.com/jaablon/buried-events-parser) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-06-19 - `Python` - FilingFirehose’s standalone SEC 8-K HTML parser using regex rules to flag possible discrepancies between reported item codes and filing text.
* [veroq-python](https://github.com/Veroq-ai/veroq-python) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-03-31 - `Python` - Financial intelligence API with verified market data, trading signals, sentiment analysis, and fact-checking across 1,061+ tickers. [PyPI](https://pypi.org/project/veroq/)
* [AgentServices](https://github.com/vbkotecha/agentservices-api) ⭐ 1 | 🐛 2 | 🌐 Python | 📅 2026-09-06 - `Python` - API server for crypto and market data with technical indicators, on-chain analytics, and MCP access; includes x402 payment support for hosted endpoints.
* [Dividend Data Toolkit](https://github.com/holaclea/dividend-data-toolkit) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-11 - `Python` `Data` - Dated SCHD payment and holdings snapshots with source URLs, data dictionaries, and Python tools for split-aware dividend windows and ETF company-exposure checks. [Website](https://dividendsteps.com/)
* [Market Brief](https://github.com/beepboop2025/market-brief) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-13 - `Python` `JavaScript` - Source-linked money-market, capital-market, and liquidity briefs with local snapshot comparisons and explicit missing-data states.
* [ashare-data-immunity](https://github.com/holdout-labs/ashare-data-immunity) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-08 - `Python` - A-share daily-bar data immunity: cleaning, board-aware price limits (ST date-aware), suspensions, audits, SHA-256 snapshots and evidence-tracked repair.
* [pit-adjuster](https://github.com/holdout-labs/pit-adjuster) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-08 - `Python` - Point-in-time fixed-basis back-adjustment for A-share daily prices: corporate-action factor chains, convention-drift detection, snapshot-equivalence gates and a full-window drift checker.
* [perp-funding-collector](https://github.com/donnywin85/perp-funding-collector) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-21 - `Python` - Collects and stores funding-rate snapshots from five decentralized perpetual-futures exchanges, normalizing rates hourly and flagging markets with less than $2 million in open interest. Intended for historical analysis and cross-venue comparisons; it does not trade.
* [treasurydirect](https://github.com/moshejs/treasurydirect) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - Zero-dependency client for the US TreasuryDirect API: auction results, upcoming auctions, CUSIP lookups, and Debt to the Penny; no API key required.
* [newyorkfed](https://github.com/moshejs/newyorkfed) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - Client for the NY Fed Markets Data API: SOFR/EFFR/OBFR reference rates, SOFR averages and index, and SOMA holdings; no API key required.
* [commitments-of-traders](https://github.com/moshejs/commitments-of-traders) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - Client for the CFTC Commitments of Traders reports (Legacy, Disaggregated, TFF; futures-only and combined) via the official Socrata API.
* [The Gold Barometer](https://github.com/thegoldbarometer/data) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-14 - `Python` - Daily gold buying-conditions score (0-100), free JSON API and CC BY dataset back to 1971.
* [filingrail-mcp](https://pypi.org/project/filingrail-mcp/) - `Python` `MCP` - MCP server and Python SDK for a SEC EDGAR REST API covering XBRL fundamentals, Form 4 insider trades, 8-K events, 13F holdings and filings, where every record carries the source sec.gov filing URL it came from. [GitHub](https://github.com/adamhudson777/filingrail-mcp) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-11
* [edgar-traps](https://pypi.org/project/edgar-traps/) - `Python` - Checks that catch nine silent failure modes in SEC filing data, from Form 4 filings that are about a different issuer to 13F-NT counted as a position report, each documented with the incident that found it. [GitHub](https://github.com/researchaiexe-stack/edgar-traps) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-13
* [Helium MCP](https://heliumtrades.com/mcp-page/) - `Python` - Live stock/ETF/crypto data with AI-generated bull/bear cases and price forecasts, proprietary ML options pricing with probability ITM and fair value, and news bias scoring across 5,000+ sources. Available as MCP server or API. Free tier: 50 queries, no signup.
* [chinesestockapi](https://pypi.org/project/chinesestockapi/) - `Python` - Python API to get Chinese stock price. (Last updated: 2015-03-21).
* [tushare](https://pypi.org/project/tushare/) - `Python` - A utility for crawling historical and Real-time Quotes data of China stocks. (Last updated: 2024-08-27).
* [edinetdb](https://edinetdb.com/) - `Python` - Free API and MCP server for Japanese company financials. Normalizes EDINET XBRL across JP-GAAP, IFRS, and US-GAAP for 3,800+ listed companies with 90 metrics, screening, and securities report text.
* [bronto-python](https://pypi.org/project/bronto-python/) - `Python` - Bronto API Integration for Python.
* [metatrader5](https://pypi.org/project/metatrader5/) - `Python` - API Connector to MetaTrader 5 Terminal. (Last updated: 2026-02-20).
* [fedfred](https://nikhilxsunder.github.io/fedfred/) - `Python` - FRED & GeoFRED Economic data API with preprocessed dataframe output in pandas/geopandas, polars/polars\_st, and dask dataframes/geodataframes.
* [uk-sic-codes](https://pypi.org/project/uk-sic-codes/) - `Python` - UK SIC 2007 industry classification code lookup, search, and validation. 731 codes, 21 sections.
* [uk-company-number](https://pypi.org/project/uk-company-number/) - `Python` - Validate, format, and identify UK Companies House company numbers. Supports all 27 prefixes.
* [IBrokers](https://cran.r-project.org/web/packages/IBrokers/index.html) - `R` - Provides native R access to Interactive Brokers Trader Workstation API.

## Prediction Markets

* [pmxt](https://github.com/pmxt-dev/pmxt) ⭐ 2,152 | 🐛 1,297 | 🌐 TypeScript | 📅 2026-07-18 - `Python` `JavaScript` - The CCXT for prediction markets. A unified API for trading on Polymarket, Kalshi, and more.
* [Oracle3](https://github.com/YichengYang-Ethan/oracle3) ⭐ 255 | 🐛 18 | 🌐 Python | 📅 2026-05-08 - `Python` - Autonomous trading agent for Kalshi, Polymarket, and Solana — Wang Transform pricing (calibrated on 291k resolved contracts) drives eight constraint-based arbitrage strategies and Kelly-sized model trades.
* [Live Tennis API](https://livetennisapi.com) - `REST` `WebSocket` `MCP` - Real-time tennis scores, serving and break-point state, and model win probabilities for pricing tennis event markets, plus H2H, rankings and a 1968-2022 point-by-point archive; free tier. [GitHub](https://github.com/livetennisapi/livetennisapi-mcp) ⭐ 159 | 🐛 3 | 🌐 TypeScript | 📅 2026-09-14
* [polymm](https://github.com/kachence/polymm) ⭐ 95 | 🐛 1 | 🌐 Python | 📅 2026-08-16 - `Python` `Polymarket` - Market-making and arbitrage bot for Polymarket sports and esports markets, pricing from de-vigged sportsbook odds.
* [polymarket-whales](https://github.com/al1enjesus/polymarket-whales) ⭐ 63 | 🐛 10 | 🌐 Python | 📅 2026-03-20 - `Python` - Real-time whale trade tracker for Polymarket — terminal alerts + Telegram notifications when large orders hit the book.
* [prediction-market-maker](https://github.com/octavi42/prediction-market-maker) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2026-04-10 - `Python` - Open-source market-making strategy that placed #2 in Paradigm's prediction market challenge, with full strategy evolution and analysis.
* [marketlens](https://github.com/marketlenstrade/marketlens-python) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2026-09-12 - `Python` `MCP` - Tick-level Polymarket order book history with replay and a backtesting engine simulating queue priority, latency, and slippage.
* [PolyMind](https://polyminds.netlify.app/) - `Python` - Real-time Polymarket trading alerts with multi-AI analysis (Groq, Claude, Gemini). Track whale bets, volume spikes, coordinated wallets, and 12 signal types. Free tier available. [GitHub](https://github.com/samirasadov28-code/PolyMind) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2026-06-18
* [polymarket-bot-lab](https://github.com/oraclemangle/polymarket-bot-lab) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-07-29 - `Python` - Open-sourced research lab of 11 candidate Polymarket trading bots (weather, sports, longshot fades, maker, whale-flow) with a shared CLOB/backtest framework, ADR decision log, and honest paper/live results. Companion free dataset: [polymarket-canary-tape](https://huggingface.co/datasets/oraclemangle/polymarket-canary-tape) (300M+ events, CC-BY-4.0).
* [QuantRank500](https://github.com/RusUsf/quantrank500) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-15 - `Python` - Open-source public record of stock predictions: commit-reveal before the open, automatic settlement against exchange data, tamper-evident hash-chained ledger. Live at [quantrank500.com](https://quantrank500.com).
* [outcometick](https://outcometick.com) - `Python` `JavaScript` - Tick-level history for Polymarket and Predict.fun crypto Up/Down markets, including the full-precision Chainlink settlement feeds and each market's strike and settled outcome, with a sandboxed runner that replays a submitted strategy against the same archive. [GitHub](https://github.com/outcometick/outcometick-sdk-ts) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-13

## Calendars & Market Hours

* [pandas\_market\_calendars](https://github.com/rsheftel/pandas_market_calendars) ⭐ 997 | 🐛 21 | 🌐 Python | 📅 2026-07-12 - `Python` - Exchange calendars to use with pandas for trading applications.
* [exchange\_calendars](https://github.com/gerrymanoim/exchange_calendars) ⭐ 667 | 🐛 27 | 🌐 Python | 📅 2026-09-15 - `Python` - Stock Exchange Trading Calendars.
* [bizdays](https://github.com/wilsonfreitas/python-bizdays) ⭐ 95 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2026-04-13 - `Python` - Business days calculations and utilities.
* [bizdays](https://github.com/wilsonfreitas/R-bizdays) ⭐ 58 | 🐛 12 | 🌐 R | 📅 2025-01-08 - `R` - Business days calculations and utilities.
* [sifma-holidays](https://github.com/moshejs/sifma-holidays) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - US bond-market (SIFMA) holidays, early closes, and T+1 settlement-date math; zero dependencies.
* [us-equity-market-calendar](https://github.com/moshejs/us-equity-market-calendar) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - NYSE/NASDAQ trading calendar: holidays, 1pm early closes, trading-day navigation, and DST-aware is-market-open; zero dependencies.
* [fx-value-date](https://github.com/moshejs/fx-value-date) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-16 - `TypeScript` - FX spot/forward value-date calculation across two currency holiday calendars, with the USD-lag and end-of-month rules; zero dependencies.
* [timeDate](https://cran.r-project.org/web/packages/timeDate/index.html) - `R` - Chronological and Calendar Objects.

## Visualization

* [D-Tale](https://github.com/man-group/dtale) ⭐ 5,225 | 🐛 71 | 🌐 TypeScript | 📅 2026-07-24 - `Python` - Visualizer for pandas dataframes and xarray datasets.
* [mplfinance](https://github.com/matplotlib/mplfinance) ⭐ 4,433 | 🐛 176 | 🌐 Python | 📅 2024-08-08 - `Python` - matplotlib utilities for the visualization, and visual analysis, of financial data.
* [finvizfinance](https://github.com/lit26/finvizfinance) ⭐ 1,679 | 🐛 2 | 🌐 Python | 📅 2026-08-29 - `Python` - Finviz analysis python library.
* [finplot](https://github.com/highfestiva/finplot) ⭐ 1,183 | 🐛 36 | 🌐 Python | 📅 2026-03-30 - `Python` - Performant and effortless finance plotting for Python.
* [dxcharts-lite](https://github.com/devexperts/dxcharts-lite) ⭐ 101 | 🐛 12 | 🌐 TypeScript | 📅 2026-09-02 - `JavaScript` - Flexible financial charting library based on HTML5 canvas.
* [market-analy](https://github.com/maread99/market_analy) ⭐ 80 | 🐛 3 | 🌐 Python | 📅 2026-09-14 - `Python` - Analysis and interactive charting using [market-prices](https://github.com/maread99/market_prices) ⭐ 106 | 🐛 10 | 🌐 Python | 📅 2026-09-15 and bqplot.
* [LightweightCharts.jl](https://github.com/bhftbootcamp/LightweightCharts.jl) ⭐ 56 | 🐛 3 | 🌐 Julia | 📅 2026-08-19 - `Julia` - Julia wrapper for Lightweight Charts™ by TradingView.
* [Exeria Charts](https://github.com/efixdata/exeria-charts) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-19 - `JavaScript` - High-performance, native Canvas/WebGL financial charting library for self-hosted applications without iframe limits.
* [MyLinedChart](https://mylinedchart.com) - `Desktop` - Technical-analysis charting app for Interactive Brokers (IBKR) that exports drawings, notes, indicators and OHLCV as JSON/XLSX/CSV, and exposes chart context to AI agents over MCP.

## Excel & Spreadsheet Integration

* [xlsxwriter](https://xlsxwriter.readthedocs.io/) - `Python` - Write files in the Excel 2007+ XLSX file format. [GitHub](https://github.com/jmcnamara/XlsxWriter) ⭐ 3,972 | 🐛 30 | 🌐 Python | 📅 2026-08-04
* [xlwings](https://www.xlwings.org/) - `Python` - Make Excel fly with Python. [GitHub](https://github.com/xlwings/xlwings) ⭐ 3,404 | 🐛 396 | 🌐 Python | 📅 2026-09-14
* [xlrd](https://github.com/python-excel/xlrd) ⭐ 2,206 | 🐛 3 | 🌐 Python | 📅 2026-07-15 - `Python` - Library for developers to extract data from Microsoft Excel spreadsheet files.
* [xlloop](https://xlloop.sourceforge.net/) - `Python` - XLLoop is an open source framework for implementing Excel user-defined functions (UDFs) on a centralised server (a function server). [GitHub](https://github.com/poidasmith/xlloop) ⭐ 110 | 🐛 26 | 🌐 Java | 📅 2019-11-18
* [Bilig](https://github.com/proompteng/bilig) ⭐ 36 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-14 - `TypeScript` - Formula WorkPaper and XLSX recalculation runtime for Node.js services and agent tools.
* [openpyxl](https://openpyxl.readthedocs.io/en/latest/) - `Python` - Read/Write Excel 2007 xlsx/xlsm files.
* [expy](https://bnikolic.co.uk/expy/expy.html) - `Python` - The ExPy add-in allows easy use of Python directly from within an Microsoft Excel spreadsheet, both to execute arbitrary code and to define new Excel functions.
* [pyxll](https://www.pyxll.com) - `Python` - PyXLL is an Excel add-in that enables you to extend Excel using nothing but Python code.

## Quant Research Environments

* [TradingAgents](https://github.com/TauricResearch/TradingAgents) ⭐ 106,513 | 🐛 347 | 🌐 Python | 📅 2026-09-15 - `Python` `LLM` - Multi-agent financial research framework combining fundamental, technical, news, and sentiment analysis with structured investment debates and risk assessment.
* [Jupyter Quant](https://github.com/quantbelt/jupyter-quant) ⭐ 248 | 🐛 9 | 🌐 Shell | 📅 2026-09-15 - `Python` - A dockerized Jupyter quant research environment with preloaded tools for quant analysis, statsmodels, pymc, arch, py\_vollib, zipline-reloaded, PyPortfolioOpt, etc.
* [dsh-quant](https://github.com/pengpengyi92/dsh-quant) ⭐ 38 | 🐛 20 | 🌐 TypeScript | 📅 2026-09-04 - `TypeScript` `DeepSeek Harness` - Agent-native quantitative research toolkit for DeepSeek Harness: 46 tools across data, alpha, ML, risk, execution and ecosystem domains, with an end-to-end research pipeline.
* [Nova-TradingAgent](https://github.com/rufeng0411/Nova-TradingAgent) ⭐ 26 | 🐛 6 | 🌐 Python | 📅 2026-09-10 - `Python` `A-shares` - Self-hosted 15-agent research desk (debate graph, optional Tushare L2 and Qlib). Does not place trades.
* [QFO Quant Platform](https://www.qfo-quant-platform.com/) - `Python` `React` `A-shares` - Local-first quantitative research and backtesting platform with data synchronization, multi-asset screening, factor analysis, portfolio optimization, risk analysis, and optional LLM-assisted news analysis. [GitHub](https://github.com/yeh2017/QFO-Quant-Platform) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2026-09-05

## Cross-Language Frameworks

* [QuantLib](https://github.com/lballabio/QuantLib) ⭐ 7,615 | 🐛 51 | 🌐 C++ | 📅 2026-09-15 - The QuantLib project is aimed at providing a comprehensive software framework for quantitative finance.
  * [PyQL](https://github.com/enthought/pyql) ⭐ 1,340 | 🐛 20 | 🌐 Cython | 📅 2026-07-17 - Python port.
  * XAD - Automatic Differentiation (AAD) Library in [Python](https://pypi.org/project/xad/) and [C++](https://github.com/auto-differentiation/xad/) ⭐ 428 | 🐛 4 | 🌐 C++ | 📅 2026-09-08
  * [QLNet](https://github.com/amaggiulli/qlnet) ⭐ 427 | 🐛 2 | 🌐 C# | 📅 2026-09-11 - .Net port.
  * [JQuantLib](https://github.com/frgomes/jquantlib) ⭐ 155 | 🐛 8 | 🌐 Java | 📅 2016-03-14 - Java port.
  * [QuantLib.jl](https://github.com/pazzo83/QuantLib.jl) ⭐ 144 | 🐛 10 | 🌐 Julia | 📅 2020-02-18 - Julia port.
  * [RQuantLib](https://github.com/eddelbuettel/rquantlib) ⭐ 136 | 🐛 9 | 🌐 C++ | 📅 2026-07-26 - R port.
  * QuantLibRisks - Fast risks with QuantLib in [Python](https://pypi.org/project/QuantLib-Risks/) and [C++](https://github.com/auto-differentiation/QuantLibAAD) ⭐ 42 | 🐛 2 | 🌐 C++ | 📅 2026-06-12
  * [QuantLibAddin](https://www.quantlib.org/quantlibaddin/) - Excel support.
  * [QuantLibXL](https://www.quantlib.org/quantlibxl/) - Excel support.
  * [QuantLib-Python Documentation](https://quantlib-python-docs.readthedocs.io/) - Documentation for the Python bindings for the QuantLib library.
* [TA-Lib](https://ta-lib.org) - perform technical analysis of financial market data. [GitHub](https://github.com/TA-Lib/ta-lib) ⭐ 1,676 | 🐛 21 | 🌐 Java | 📅 2026-09-15
  * [ta-lib-python](https://github.com/TA-Lib/ta-lib-python) ⭐ 12,246 | 🐛 137 | 🌐 Cython | 📅 2026-09-14
  * [ta-lib](https://github.com/TA-Lib/ta-lib) ⭐ 1,676 | 🐛 21 | 🌐 Java | 📅 2026-09-15
* [PineTS](https://github.com/LuxAlgo/PineTS) ⭐ 626 | 🐛 43 | 🌐 TypeScript | 📅 2026-09-14 - `TypeScript` `JavaScript` `Pine Script` - Open-source transpiler and runtime that executes Pine Script logic in Node.js and the browser with 1:1 syntax compatibility, for running indicators and strategies on your own infrastructure.
* [XAD](https://github.com/auto-differentiation/xad) ⭐ 428 | 🐛 4 | 🌐 C++ | 📅 2026-09-08 - Automatic Differentation (AAD) Library.
* [godzilla.dev](https://godzilla.dev) - `C++` `Python` - Open-source framework for crypto quant trading, funding rate arbitrage and ultra-low-latency market making. [GitHub](https://github.com/godzilla-foundation/godzilla-community) ⭐ 372 | 🐛 2 | 🌐 C++ | 📅 2026-08-11
* [RunMat](https://runmat.com/) - `Rust` - Runtime for MATLAB-syntax array math with automatic CPU/GPU execution and fused kernels for quantitative simulations. [GitHub](https://github.com/runmat-org/runmat) ⭐ 255 | 🐛 25 | 🌐 Rust | 📅 2026-09-10
* [QuantLibAAD](https://github.com/auto-differentiation/QuantLibAAD) ⭐ 42 | 🐛 2 | 🌐 C++ | 📅 2026-06-12 - Fast risks with QuantLib in C++.

## Reproducing Works, Training & Books

* [python-training](https://github.com/jpmorganchase/python-training) ⭐ 14,085 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-24 - J.P. Morgan's Python training for business analysts and traders.
* [Finance](https://github.com/shashankvemuri/Finance) ⭐ 4,264 | 🐛 3 | 🌐 Python | 📅 2026-09-12 - 150+ quantitative finance Python programs to help you gather, manipulate, and analyze stock market data.
* [algorithmic-trading-with-python](https://github.com/chrisconlan/algorithmic-trading-with-python) ⭐ 3,485 | 🐛 6 | 🌐 Python | 📅 2021-06-01 - Source code for Algorithmic Trading with Python (2020) by Chris Conlan.
* [ML\_Finance\_Codes](https://github.com/mfrdixon/ML_Finance_Codes) ⭐ 2,663 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2020-06-13 - Machine Learning in Finance: From Theory to Practice Book.
* [py4fi2nd](https://github.com/yhilpisch/py4fi2nd) ⭐ 2,268 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2025-06-06 - Jupyter Notebooks and code for Python for Finance (2nd ed., O'Reilly) by Yves Hilpisch.
* [MEDIUM\_NoteBook](https://github.com/cerlymarco/MEDIUM_NoteBook) ⭐ 2,145 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2024-09-22 - Repository containing notebooks of [cerlymarco](https://github.com/cerlymarco)'s posts on Medium.
* [Stock\_Analysis\_For\_Quant](https://github.com/LastAncientOne/Stock_Analysis_For_Quant) ⭐ 2,060 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-05-04 - Different Types of Stock Analysis in Excel, Matlab, Power BI, Python, R, and Tableau.
* [volatility-trading](https://github.com/jasonstrimpel/volatility-trading) ⭐ 1,954 | 🐛 4 | 🌐 Python | 📅 2024-10-21 - A complete set of volatility estimators based on Euan Sinclair's Volatility Trading.
* [Hands-On Machine Learning for Algorithmic Trading](https://github.com/packtpublishing/hands-on-machine-learning-for-algorithmic-trading) ⭐ 1,925 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2023-01-18 - Hands-On Machine Learning for Algorithmic Trading, published by Packt.
* [Deep Learning Machine Learning Stock](https://github.com/LastAncientOne/Deep_Learning_Machine_Learning_Stock) ⭐ 1,789 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2024-03-01 - Deep Learning and Machine Learning stocks represent a promising long-term or short-term opportunity for investors and traders.
* [Machine Learning Asset Management](https://github.com/firmai/machine-learning-asset-management) ⭐ 1,751 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2021-12-17 - Machine Learning in Asset Management (by @firmai).
* [fecon235](https://github.com/rsvp/fecon235) ⭐ 1,278 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2023-01-20 - Open source project for software tools in financial economics. Many jupyter notebook to verify theoretical ideas and practical methods interactively.
* [QuantFinanceBook](https://github.com/LechGrzelak/QuantFinanceBook) ⭐ 960 | 🐛 3 | 🌐 Python | 📅 2025-04-14 - Quantitative Finance book.
* [Computational-Finance-Course](https://github.com/LechGrzelak/Computational-Finance-Course) ⭐ 909 | 🐛 0 | 🌐 Python | 📅 2024-03-01 - Materials for the course of Computational Finance.
* [AFML](https://github.com/boyboi86/AFML) ⭐ 872 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-09-05 - All the answers for exercises from Advances in Financial Machine Learning by Dr Marco Lopez de Parodo.
* [py4at](https://github.com/yhilpisch/py4at) ⭐ 853 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2023-10-09 - Jupyter Notebooks and code for the book Python for Algorithmic Trading (O'Reilly) by Yves Hilpisch.
* [Python\_Option\_Pricing](https://github.com/dedwards25/Python_Option_Pricing) ⭐ 850 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2025-05-13 - An library to price financial options written in Python. Includes: Black Scholes, Black 76, Implied Volatility, American, European, Asian, Spread Options.
* [FinanceHub](https://github.com/Finance-Hub/FinanceHub) ⭐ 801 | 🐛 4 | 🌐 Python | 📅 2024-05-28 - Resources for Quantitative Finance.
* [Python-for-Finance-Cookbook](https://github.com/PacktPublishing/Python-for-Finance-Cookbook) ⭐ 801 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-03-02 - Python for Finance Cookbook, published by Packt.
* [dx](https://github.com/yhilpisch/dx) ⭐ 767 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-04-05 - DX Analytics | Financial and Derivatives Analytics with Python.
* [Machine-Learning-for-Asset-Managers](https://github.com/emoen/Machine-Learning-for-Asset-Managers) ⭐ 665 | 🐛 2 | 🌐 Python | 📅 2026-02-11 - Implementation of code snippets, exercises and application to live data from Machine Learning for Asset Managers (Elements in Quantitative Finance) written by Prof. Marcos López de Prado.
* [dawp](https://github.com/yhilpisch/dawp) ⭐ 640 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-02-22 - Jupyter Notebooks and code for Derivatives Analytics with Python (Wiley Finance) by Yves Hilpisch.
* [QuantFinance](https://github.com/PythonCharmers/QuantFinance) ⭐ 618 | 🐛 14 | 🌐 Jupyter Notebook | 📅 2025-09-02 - Training materials in quantitative finance.
* [Derman Papers](https://github.com/MarcosCarreira/DermanPapers) ⭐ 530 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2017-10-21 - Notebooks that replicate original quantitative finance papers from Emanuel Derman.
* [systematictradingexamples](https://github.com/robcarver17/systematictradingexamples) ⭐ 490 | 🐛 0 | 🌐 Python | 📅 2020-07-22 - `Python` - Code examples for Robert Carver's [Systematic Trading](https://www.harriman-house.com/authors/robert-carver/systematic-trading/9780857194459).
* [quant](https://github.com/paulperry/quant) ⭐ 454 | 🐛 0 | 🌐 Python | 📅 2015-07-14 - Quantitative Finance and Algorithmic Trading exhaust; mostly ipython notebooks based on Quantopian, Zipline, or Pandas.
* [Goldman Sachs Quantitative Strategies Research Notes](https://github.com/s0ap/gs-quantitative-strategies-research-notes) ⭐ 442 | 🐛 0 | 📅 2025-11-17 - `Papers` `Derivatives` - Collection of 1990s research papers on derivatives pricing, volatility modeling, hedging, and model risk.
* [aiif](https://github.com/yhilpisch/aiif) ⭐ 399 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2024-01-14 - Jupyter Notebooks and code for the book Artificial Intelligence in Finance (O'Reilly) by Yves Hilpisch.
* [pysystemtrade\_examples](https://github.com/robcarver17/pysystemtrade_examples) ⭐ 281 | 🐛 1 | 🌐 Python | 📅 2018-02-21 - Examples using pysystemtrade for Robert Carver's [blog](https://qoppac.blogspot.com/).
* [Technical Analysis and Feature Engineering](https://github.com/jo-cho/Technical_Analysis_and_Feature_Engineering) ⭐ 203 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-02-16 - Feature Engineering and Feature Importance of Machine Learning in Financial Market.
* [Quant-Finance-With-Python-Code](https://github.com/lingyixu/Quant-Finance-With-Python-Code) ⭐ 185 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-01-15 - Repo for code examples in Quantitative Finance with Python by Chris Kelliher.
* [IPythonScripts](https://github.com/mgroncki/IPythonScripts) ⭐ 179 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-02-28 - Tutorials about Quantitative Finance in Python and QuantLib: Pricing, xVAs, Hedging, Portfolio Optimisation, Machine Learning and Deep Learning.
* [Autoencoder-Asset-Pricing-Models](https://github.com/RichardS0268/Autoencoder-Asset-Pricing-Models) ⭐ 150 | 🐛 2 | 🌐 Python | 📅 2025-08-17 - Reimplementation of Autoencoder Asset Pricing Models ([GKX, 2019](https://www.aqr.com/Insights/Research/Working-Paper/Autoencoder-Asset-Pricing-Models)).
* [Differential Machine Learning and Axes that matter by Brian Huge and Antoine Savine](https://github.com/differential-machine-learning/notebooks) ⭐ 149 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2022-10-05 - Implement, demonstrate, reproduce and extend the results of the Risk articles 'Differential Machine Learning' (2020) and 'PCA with a Difference' (2021) by Huge and Savine, and cover implementation details left out from the papers.
* [rough\_bergomi](https://github.com/rmcrkd/rough_bergomi) ⭐ 144 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-09-17 - A Python implementation of the rough Bergomi model.
* [book\_irds3](https://github.com/attack68/book_irds3) ⭐ 125 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2022-10-29 - Code repository for Pricing and Trading Interest Rate Derivatives.
* [Value Investing Studies](https://github.com/euclidjda/value-investing-studies) ⭐ 96 | 🐛 1 | 🌐 R | 📅 2021-10-26 - A collection of data analysis studies that examine the performance and characteristics of value investing over long periods of time.
* [RoughVolatilityWorkshop](https://github.com/jgatheral/RoughVolatilityWorkshop) ⭐ 74 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-09-06 - 2024 QuantMind's Rough Volatility Workshop lectures.
* [modelos\_vol\_derivativos](https://github.com/ysaporito/modelos_vol_derivativos) ⭐ 59 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-08-19 - "Modelos de Volatilidade para Derivativos" book's Jupyter notebooks.
* [101\_formulaic\_alphas](https://github.com/ram-ki/101_formulaic_alphas) ⭐ 51 | 🐛 0 | 🌐 Python | 📅 2022-07-11 - Implementation of [101 formulaic alphas](https://arxiv.org/abs/1601.00991) using qstrader.
* [QuantFinanceTraining](https://github.com/JoaoJungblut/QuantFinanceTraining) ⭐ 44 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-02-20 - This repository contains codes that were executed during my training in the CQF (Certificate in Quantitative Finance). The codes are organized by class, facilitating navigation and reference.
* [NMOF](https://github.com/enricoschumann/NMOF) ⭐ 39 | 🐛 0 | 🌐 R | 📅 2026-08-20 - Functions, examples and data from the first and the second edition of "Numerical Methods and Optimization in Finance" by M. Gilli, D. Maringer and E. Schumann (2019, ISBN:978-0128150658).
* [AlgoTradingLib](https://github.com/usdaud/algotradinglib.github.io) ⭐ 32 | 🐛 0 | 🌐 HTML | 📅 2026-03-28 - A catalog of algorithmic trading libraries, frameworks, strategies, and educational materials.
* [financialnoob-misc](https://github.com/financialnoob/misc) ⭐ 28 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-08-26 - Codes from @financialnoob's posts.
* [Portfolio Optimization Book](https://portfoliooptimizationbook.com/) - Prof. Daniel Palomar's Portfolio Optimization Book. [GitHub](https://github.com/dppalomar/pob) ⭐ 26 | 🐛 1 | 🌐 R | 📅 2025-02-17
* [MesoSim Options Trading Strategy Library](https://github.com/deltaray-io/strategy-library) ⭐ 21 | 🐛 0 | 📅 2026-09-08 - Free and public Options Trading strategy library for MesoSim.
* [frh-fx](https://github.com/rmcrkd/frh-fx) ⭐ 14 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-05-24 - A python implementation of the fast-reversion Heston model of Mechkov for FX purposes.
* [Special-Relativity-in-Financial-Modeling](https://github.com/Mattbusel/Special-Relativity-in-Financial-Modeling) ⭐ 13 | 🐛 0 | 🌐 C++ | 📅 2026-03-23 - C++20 implementation of special-relativistic geometry applied to OHLCV data: Lorentz factors, spacetime intervals, Christoffel symbols, and geodesic deviation signals from live market data. DOI: 10.5281/zenodo.18639919.
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

* [Massive](https://massive.com/) - Financial market data API with a permanent free personal-use tier offering two years of US stock history, end-of-day prices, and reference data at five requests per minute, with no credit card required. [GitHub](https://github.com/massive-com/client-python) ⭐ 1,504 | 🐛 24 | 🌐 Python | 📅 2026-07-09

* [London Strategic Edge](https://londonstrategicedge.com/data/) - `Python` - Free market and economic data with up to 10 databank downloads per hour of one million rows each, subject to a shared monthly bandwidth allowance, without a credit card. [GitHub](https://github.com/londonstrategicedge/lse-data) ⭐ 254 | 🐛 5 | 🌐 Python | 📅 2026-08-02

* [Financial Data](https://financialdata.net/) - Financial data API with a free personal-use plan allowing 300 requests per day for symbol lists and selected market data, including historical commodity and OTC prices. [GitHub](https://github.com/financialdatanet/fdnpy) ⭐ 50 | 🐛 0 | 🌐 Python | 📅 2026-09-08

* [Trends MCP](https://www.trendsmcp.ai/) - `MCP` `REST` - Search, social, commerce, and news-sentiment data for alternative-data research, with a permanent free tier of 100 requests/month, 90 days of history, and top-10 trend boards delayed 24 hours. [GitHub](https://github.com/trendsmcp-ai/Trends-MCP) ⭐ 38 | 🐛 3 | 🌐 Python | 📅 2026-08-29

* [EarningsCall](https://earningscall.biz) - `Python` - Public earnings-call transcripts and an earnings calendar readable without an account, with paid API access for programmatic transcripts, audio and slide decks. [GitHub](https://github.com/EarningsCall/earningscall-python) ⭐ 35 | 🐛 4 | 🌐 Python | 📅 2026-07-21

* [CoinPaprika](https://coinpaprika.com/api/) - `Python` - Cryptocurrency market data API with 20,000 free calls per month for personal use, including one year of daily price history, without an API key. [GitHub](https://github.com/coinpaprika/coinpaprika-api-python-client) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2026-08-06

* [DexPaprika](https://dexpaprika.com/) - `Python` - DEX pool, token and OHLCV data API with 50,000 free monthly credits without signup and up to 60-second data delays. [GitHub](https://github.com/coinpaprika/dexpaprika-sdk-python) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-09-14

* [FXMacroData](https://fxmacrodata.com/) - `Python` - Macroeconomic release data with permanent free access to USD announcements covering the latest 90 days at 100 requests per day without an API key or payment information. [GitHub](https://github.com/fxmacrodata/fxmacrodata) ⭐ 9 | 🐛 3 | 🌐 Python | 📅 2026-09-14

* [0xArchive](https://0xarchive.io) - Hyperliquid and Lighter market data through REST, WebSocket and replay, with a permanent free tier offering 50,000 credits per month, 15 requests per second and the most recent 30 days of history without a credit card. [GitHub](https://github.com/0xArchiveIO/sdk-python) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2026-09-14

* [Korea Stock Data](https://aikstockdata.com/) - `Data` - Free Korean equity settled closes with 250 trading days of per-stock history, DART filings and earnings as JSON/CSV, without signup, an API key or request quotas. [GitHub](https://github.com/na77tech-creator/aikstockdata) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-15

* [PreReason](https://www.prereason.com) - `JavaScript` - Bitcoin and macroeconomic market briefings through REST and MCP, with a permanent free tier of six briefings, 30-day history, 60 requests per hour and 500 per day, without a credit card. [GitHub](https://github.com/PreReason/mcp) ⭐ 5 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-19

* [FinSignals](https://finsignals.ai) - `Python` - Financial-text classification API for sentiment, directionality, quality, post type, relevance, confidence, and sarcasm, with 1,000 free credits per month and no credit card required. [GitHub](https://github.com/finsignals/finsignals-python) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-04-11

* [Tradevo Data](https://tradevodata.com) - `Python` - Point-in-time US equity fundamentals from SEC EDGAR with filing dates and restatement flags; free API access includes 250 requests per day without a credit card, and a 40-company CC0 annual dataset is available without signup. [GitHub](https://github.com/christianpichichero-max/pit-fundamentals) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-09-09

* [Earnings Feed](https://earningsfeed.com/api) - SEC filings, insider transactions, and institutional holdings API with a permanent free tier of 5,000 requests per month and 15 requests per minute, without a credit card. [GitHub](https://github.com/earningsfeed/earningsfeed-python) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-12-25

* [finlight](https://finlight.me) - `Python` `TypeScript` - Financial and geopolitical news API with a permanent free REST tier of 5,000 requests per month, a 12-hour delay and one month of history, without a credit card. [GitHub](https://github.com/jubeiargh/finlight-client-py) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-08-16

* [brapi.dev](https://brapi.dev/) - Brazilian market data API with a free tier of 15,000 requests per month and up to three months of price history, plus four stocks accessible without an account. [GitHub](https://github.com/brapi-dev/brapi-python) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2026-09-11

* [UniRateAPI](https://unirateapi.com) - `Python` - Currency exchange rates, conversion and VAT data with a permanent free tier of 200 requests per day and no credit card; historical data require a paid plan. [GitHub](https://github.com/UniRate-API/unirate-api-python) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-07-08

* [Tessera](https://tesseralytics.dev) - `Python` - Hyperliquid order-flow-enriched minute OHLCV with a permanent free tier covering BTC, ETH, SOL and HYPE over the trailing month, with unlimited Parquet downloads and no credit card. [GitHub](https://github.com/tesseralytics/python-client) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2026-09-11

* [Factor Weave](https://factorweave.com/) - `Python` `TypeScript` `R` - Factor data and cosine-similarity screening with a permanent free API tier of 250 calls per day, daily factor rankings and market-context snapshots, without a credit card. [GitHub](https://github.com/Blazing-Customs/factorweave-tools) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2026-06-05

* [AlphaForge](https://alforgelabs.com) - `Python` - Proprietary local backtesting and optimization CLI with a permanent free plan requiring no registration, limited to historical data through 2023-12-31; Pine Script export requires a paid plan. [GitHub](https://github.com/alforge-labs/alpha-forge-mcp) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-07-21

* [SiftingIO](https://sifting.io) - `Python` - Market data over REST and WebSocket with a permanent free non-commercial tier per market: 10,000 monthly REST calls, 60 requests per minute, five streaming symbols and one month of history, without a credit card. [GitHub](https://github.com/SiftingIO/sdk-python) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-08-02

* [Agent Toolbelt](https://www.agenttoolbelt.live) - Stock-research and portfolio-review API with 250 free calls per month without payment information. [GitHub](https://github.com/marras0914/agent-toolbelt) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-21

* [Quant Data](https://quantdata.uk/mcp) - `Data` - Market statistics and options-positioning analytics with free public max-pain and GEX pages and 10 API calls per UTC day using an email-only key, without payment information. [GitHub](https://github.com/celineycn/quantdata-plugin) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-08-18

* [Korean Market Data](https://kexportstars.com/tools/) - `Data` - Free Korean investor-flow and sector-index datasets in English CSV/JSON, updated each trading day under CC BY 4.0 without signup. [GitHub](https://github.com/james-brand/korea-market-data) ⭐ 0 | 🐛 0 | 📅 2026-09-15

* [FillBench](https://fillbench.com) - Free crypto-exchange API latency benchmarks with p50/p95/p99 measurements, separate TLS timing and downloadable CC BY datasets. [GitHub](https://github.com/sircharli3/fillbench-data) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-09-15

* [invinoveritas](https://api.babyblueviper.com) - `Python` - Agent-verification platform with EdgeProof backtest diagnostics using Deflated Sharpe, permutation tests, and out-of-sample decay, offering five free checks per day without signup or payment information. [GitHub](https://github.com/trustless-ai/agent-contracts-examples) ⭐ 0 | 🐛 0 | 🌐 Solidity | 📅 2026-09-04

* [Frostbyte](https://agent-gateway-kappa.vercel.app) - Hosted API gateway providing cryptocurrency price data, with a permanent free allowance of 50 requests per day without signup or payment information. [GitHub](https://github.com/Robocular/frostbyte-api) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-05

* [GitDealFlow](https://gitdealflow.com) - Alternative-data research on private companies using GitHub commit velocity and contributor growth, with a permanently free weekly digest covering five startups and basic MCP read tools. [GitHub](https://github.com/kindrat86/vc-deal-flow-signal) ⭐ 0 | 🐛 19 | 🌐 TypeScript | 📅 2026-09-13

* [AlphaAssay](https://alphaassay.com) - `REST` - Trading-signal validation service with a free browser-based Deflated Sharpe Ratio calculator requiring no account, alongside paid backtest validation and forensics. [GitHub](https://github.com/alphaassay/mcp) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-29

* [AtlasYield](https://atlasyield.club) - DeFi vault scores across 16 factors, with a free read-only API requiring no signup and limited to 60 requests per minute per IP. [GitHub](https://github.com/gveshk/atlasyield-score-history) ⭐ 0 | 🐛 0 | 📅 2026-09-12

* [Wealthville](https://wealthville.net) - `REST` `MCP` - DeFi liquidity-pool scores and outcome-labeled signals through a free keyless API limited to 60 requests per minute per IP, with attribution required. [GitHub](https://github.com/amitesh-m/wealthville-integrations) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-30

* [Shingou](https://shingou.io) - `REST` `MCP` - Hourly crypto news sentiment and typed market events (hack, regulation, listing, delisting, legal) for 30 pairs, served as point-in-time buckets whose SHA-256 hash is committed to a public append-only log at publish time, so a backtester can check the history was never rewritten. Paid plans are $24, $79 and $249 a month before VAT; the permanent free tier is 1,000 requests a day with BTC, ETH and SOL live, the other 27 pairs delayed 24h, 1 day of history depth, no card, non-commercial use. [GitHub](https://github.com/shingou-io/shingou-integrations) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-02

* [FXNewsBias](https://fxnewsbias.com) - `Python` `REST` - Forex news sentiment with a permanent free API allowing 25 requests per day, one three-hour cycle of delay and non-commercial use with attribution; no credit card or historical API series. [PyPI](https://pypi.org/project/fxnewsbias/) [GitHub](https://github.com/EARNOVAGAMING/fxnewsbias-python) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-28

* [TickerLayer](https://tickerlayer.com) - Derived, indicative multi-asset market data through REST, WebSocket, and MCP, with a permanent free tier of 3,000 REST requests per month and no credit card required. [Docs](https://tickerlayer.com/docs) [GitHub](https://github.com/TickerLayer/agent-plugin) ⭐ 0 | 🐛 0 | 📅 2026-08-07

* [Wiseek Filing Impact](https://wiseek.ai/datasets/) - Monthly statistics relating proprietary SEC-filing importance scores to next-session excess stock moves, with per-event data, reproduction metadata, and a CC BY 4.0 license. [GitHub](https://github.com/WiseekAI/wiseek-datasets) ⭐ 0 | 🐛 0 | 📅 2026-09-12

* [Backtesting Arena](https://tradingstrategies.work/api) - `TypeScript` - Bitcoin cycle scores and market-state indicators through four free public API endpoints requiring no account or key, with responses cached for 5–60 minutes. [GitHub](https://github.com/Schoasch/skill-backtesting-arena) ⭐ 0 | 🐛 0 | 📅 2026-09-14

* [SimpleFunctions](https://simplefunctions.dev/) - `REST` `CLI` `MCP` - Hosted Kalshi and Polymarket data and analysis service with a free tier of 1,000 requests/month and 60 requests/minute, without payment information.

* [AxionQuant](https://axionquant.com) - Financial data API for quantitative research, with a permanent free tier of 1,000 monthly API calls and one year of historical data, without a credit card. [PyPI](https://pypi.org/project/axionquant-sdk/)

* [Prop Firm Risk Calculator](https://prop-firm-risk-calculator.vercel.app) - Free web app for position sizing, stop-loss and max-drawdown on funded accounts, with real tick/pip values for futures, forex, crypto and gold.

* [RektCalc](https://rektcalc.com) - Free web app for crypto liquidation price, position sizing, PnL and funding-rate calculations across major exchanges, with documented formulas on the site's Learn hub.

* [TradeMux](https://www.trademux.io/) - Forex trading and market-data gateway for MetaTrader 4/5 and OANDA, with a free plan for one account, 500 OHLC requests and 100 trades per month, without a credit card.

* [DayTradingBench](https://daytradingbench.com) - Live autonomous benchmark that evaluates LLM trading performance on DAX and Nasdaq indices using identical strategies and real-time market data. API access available.

* [CoinTester](https://cointester.io) - No-code cryptocurrency strategy builder with technical indicators and unlimited free historical backtests, without a credit card.

* [StockAInsights](https://stockainsights.com) - SEC financial-statement analysis and API with a permanent free account covering five selected stocks and five years of data, without payment information.

* [bolsai](https://usebolsai.com) - Brazilian stock and FII data API with fundamentals, prices, dividends, financial statements, and macroeconomic data, offering 200 free requests per day without a credit card.

* [Teses da Bolsa](https://tesesdabolsa.com) - Brazilian stock and FII analysis with free essential fundamentals, one year of price history, Bazin and Graham valuations, and the latest CVM statements, without a credit card.

* [13F Insight](https://13finsight.com/) - Institutional holdings research with a free tier offering one year of holdings history and five AI questions per day, without a credit card.

* [PortfolioSavvy](https://portfoliosavvy.com/) - Public SEC ownership research web app for exploring 13F portfolios, insider activity, Schedule 13D/G filings, company facts, and latest filing workflows.

* [EDGAR Events](https://edgarevents.com) - `REST` - SEC filing events as typed JSON: 8-K item codes with materiality flags, SC 13D/13G activist stakes (holder, target, percent of class), merger forms, and S-1/424B IPO filings, polled over REST or pushed via HMAC-signed webhooks, sourced from data.sec.gov.

* [FilingPulse](https://filingpulse.io) - `REST` `MCP` - Real-time SEC EDGAR filings normalized to one JSON schema: Form 4 insider trades, 8-K corporate events, and S-1/IPO registrations, delivered via REST, HMAC-signed webhooks, and a hosted MCP server, with a permanent free tier (2,500 req/mo, full schema).

* [Filings Flow](https://filingsflow.com) - Free SEC 13F research web app covering 11,700+ institutional managers and 208,000+ filings from 2019 onward. Quarter-over-quarter position changes with share-based thresholds, confidential-treatment reveals badged, per-filing links to the EDGAR source document, and Excel export on every table. No account required.

* [SaxoOpenAPI](https://www.developer.saxo/) - Saxo Bank financial data API.

* [RTPR](https://rtpr.io) - Financial press-release platform covering Business Wire, PR Newswire, GlobeNewswire, and AccessWire, with a permanent free Wire dashboard delayed five minutes and no credit card required.

* [Nasdaq Data Link](https://data.nasdaq.com/tools/full-list) - Financial data API with support for R, Python, Excel, Ruby, and many other languages (formerly Quandl).

* [Portfolio Optimizer](https://portfoliooptimizer.io/) - Portfolio analysis and optimization API with anonymous free access to selected endpoints for up to 20 assets, subject to a shared one-request-per-second limit.

* [Reddit WallstreetBets API](https://tradestie.com/apps/reddit/api/) - Free WallstreetBets ticker mentions and sentiment API with historical date queries and a limit of 20 requests per minute per IP, without an API key.

* [Telonex](https://telonex.io) - Prediction-market data service with free market metadata and tag datasets without an account, while tick-level data requires paid access after five trial file downloads.

* [ValueRay](https://www.valueray.com/api) - Technical, quantitative and sentiment data for stocks and ETFs with risk metrics, peer percentiles and market regime signals. Optimized for AI/LLM agents.

* [VantageGrid](https://vantagegrid.pro/) - Trade-review workspace with a permanent free tier for 25 trades per month, CSV imports and P\&L, win-rate and R-multiple analytics without payment information.

* [VertData](https://vertdata.com) - Institutional-grade financial intelligence platform. Track 43K+ congressional trades (STOCK Act), SEC insider Form 4 filings, 25 superinvestor 13F portfolios, CFTC futures positioning, ARK ETF holdings, and short interest — all scored by AI for signal strength.

* [KeepRule](https://keeprule.com/en) - Investment decision frameworks with a permanently free library of investor principles and scenarios covering valuation, position sizing and risk discipline.

* [ML-Quant](https://www.ml-quant.com/) - Top Quant resources like ArXiv (sanity), SSRN, RePec, Journals, Podcasts, Videos, and Blogs.

* [RealMarketAPI](https://realmarketapi.com/en-US) - Market-data service with a free REST tier of 5,000 requests per month for six symbols and M1, M5, and H1 timeframes, without a credit card.

* [Sharpe](https://www.sharpe.ai/) - Cryptocurrency research terminal with free access without signup and a personal API tier allowing 10,000 requests per month and 30 requests per minute.

* [Webb Database](https://webb-database.com/) - Aggregates public financial data from HKEX, the SFC, the Hong Law Society, UK Companies House and other sources, has searchable datasets on listed companies, many in machine-readable formats.

* [Clear Street API](https://docs.clearstreet.com/) - REST API for US equities & options: reference & fundamental data, multi-year financial statements, corporate events, analyst consensus, a screener, and order execution.

* [Finterm](https://finterm.xyz) - `TypeScript` - Browser-based, keyboard-first financial terminal. No public GitHub repo (closed source).

* [Coinugget](https://coinugget.com) - Real-time RSI signals, price action, and volume spikes dashboard across multiple exchanges. Free, no sign-up required.

* [Stingray](https://stingray.fi/) - Trading strategy builder that turns plain-English market ideas into inspectable rules, backtests them against historical data, and monitors matching live conditions.

* [NeuPortal](https://neuportal.ai) - AI forecasting-accountability lab: every forecast is locked pre-event, Bitcoin-timestamped (OpenTimestamps), and Brier-scored against prediction markets in public.

* [Market Posture Daily](https://marketpd.com) - Daily trend, momentum, correlation and risk analytics with a permanently free stock and ETF terminal, while API exports and cointegration screening require paid access.

* [FirmTape](https://firmtape.com) - `Data` `MCP` - SPX dealer-positioning analytics with a permanently free historical session archive without an account, plus paid live data and backtesting.

* [Katana](https://katanascreener.com) - Free Japan stock screener built on EDINET filings. 160+ fundamentals, custom formula metrics, Graham/Piotroski/Kiyohara presets. No sign-up.

* [Disclosed Capitol](https://www.disclosedcapitol.com/trades) - Free congressional trade disclosures, politician profiles and performance statistics, with paid API access beyond one-time starter credits.

* [TickerAll](https://tickerall.com) - Hosted MT4 and MT5 broker API with historical candles, real-time tick streaming, and a permanent free tier for five demo broker accounts and unlimited demo orders, without a credit card; live-account automation is paid. [Docs](https://tickerall.com/docs)

* [Algorier](https://algorier.com) - `AI` `Vibe-Trading` - Natural-language trading-strategy builder with backtesting and forward testing; a permanent free tier includes five backtests and 40 assistant messages per month without payment details, while live trading requires a paid plan.

* [SPZCO](https://spzco.com) - Stock research terminal with free access to facts, standard ratios, universe-wide screening, 13F top holdings, three saved portfolios, a 25-name watchlist and three-year backtests; Pro adds valuation and full portfolio analytics.

* [Futures Clock](https://futuresclock.com/en/) - `Web` `JSON` - Free live open/closed clock and reference for 69 futures products across 14 exchanges with DST-aware session windows, night sessions, 2026 holiday calendars, contract specifications sourced from official exchange publications, bilingual EN/ZH, and an open CORS JSON endpoint.

* [EIDEX](https://eidex.io/screener) - Cross-chain swap and bridge route comparison that queries exchange providers for a given pair and amount and ranks the routes by output, with rate, fees, ETA and price impact per route; free to use with no account, no API key and no added fee. [Docs](https://eidex.io/docs)

* [CoinBeacon](https://coinbeacon.io) - Cryptocurrency market alerts, screeners, and funding-rate, liquidation, and chart-pattern boards, with a permanent free tier of five active alerts and ten notifications per day without a credit card; public research boards require no account.

* [Dados B3](https://dadosb3.com) - `REST/MCP` - Brazilian company and real-estate fund fundamentals with public calculation methodology and a permanent free API tier of 200 requests per day without a credit card.

## Historical & Archived Projects

* [pyalgotrade](https://github.com/gbeced/pyalgotrade) ⚠️ Archived - `Python` `Historical` - Archived event-driven trading library retained for studying its original backtesting broker and order-execution models.
* [catalyst](https://github.com/scrtlabs/catalyst) ⚠️ Archived - `Python` `Historical` - Archived crypto-asset trading engine preserving an early adaptation of Zipline for exchange backtesting and live execution.
* [qtpylib](https://github.com/ranaroussi/qtpylib) ⚠️ Archived - `Python` `Historical` - Archived trading framework retained for studying shared market-data capture and multiple-strategy execution using ZeroMQ.
* [pytdx](https://github.com/rainx/pytdx) ⚠️ Archived - `Python` `Historical` - Archived [protocol implementation](https://github.com/rainx/pytdx/tree/master) ⚠️ Archived retained for studying TongDaXin binary market-data protocols and local quotation-file formats.
* [AutoTrader](https://github.com/kieran-mackle/AutoTrader) ⚠️ Archived - `Python` `Historical` - Archived trading framework retained as a reference for virtual-broker order simulation and backtesting.
* [fooltrader](https://github.com/foolcage/fooltrader) ⭐ 1,198 | 🐛 6 | 🌐 Python | 📅 2023-05-22 - `Python` `Historical` - Archived big-data quantitative-analysis and trading system retained as an early unified market-data and backtesting framework.
* [Kelp](https://github.com/stellar-deprecated/kelp) ⚠️ Archived - `Go` `Historical` - Archived Stellar DEX trading bot retained for studying configurable market-making and order-book mirroring.
* [xlwt](https://github.com/python-excel/xlwt) ⚠️ Archived - `Python` `Historical` - Archived Excel writer retained for studying legacy BIFF/XLS workbook encoding used in spreadsheet-based financial workflows.
* [pybacktest](https://github.com/ematvey/pybacktest) ⭐ 822 | 🐛 17 | 🌐 Python | 📅 2021-11-11 - `Python` `Historical` - Unmaintained vectorized pandas backtesting framework retained as an early research-oriented design.
* [TuneTA](https://github.com/jmrichardson/tuneta) ⚠️ Archived - `Python` `Historical` - Archived research implementation of technical-indicator selection using distance correlation, clustered parameter tuning, and feature pruning.
* [pipeline-live](https://github.com/alpacahq/pipeline-live) ⭐ 205 | 🐛 15 | 🌐 Python | 📅 2023-07-25 - `Python` `Historical` - Deprecated Zipline Pipeline extension retained as an early reference for pipeline-based live trading.
* [dynts](https://github.com/quantmind/dynts) ⚠️ Archived - `Python` `Historical` - Archived reference implementation of a financial time-series expression language with NumPy and R backends.
* [Rbitcoin](https://github.com/jangorecki/Rbitcoin) ⚠️ Archived - `R` `Historical` - Archived toolkit retained as an early reference for cryptocurrency wallet valuation, cross-currency conversion, and historical balance tracking.
* [GetHFData](https://github.com/msperlin/GetHFData) ⚠️ Archived - `R` `Historical` - Archived reference implementation for parsing and aggregating local Bovespa tick and order files after public FTP access ended.

## Related Lists

* [awesome-sec-filings](https://github.com/vibeyclaw/awesome-sec-filings) ⭐ 40 | 🐛 9 | 📅 2026-07-04 - A curated list of tools, data sources, libraries, and resources for working with SEC filings (13F, 10-K, 10-Q, 8-K).
* [CONVEXFI](https://github.com/convexfi) - Official GitHub organization for the convex research group at the Hong Kong University of Science and Technology (HKUST).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-15._
