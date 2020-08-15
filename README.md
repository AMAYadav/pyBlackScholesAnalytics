# pyBlackScholesAnalytics

[**pyBlackScholesAnalytics**](https://github.com/gabrielepompa88/pyBlackScholesAnalytics) is a Python package implementing analytics for Options and Option Strategies using the Black-Scholes Model for educational purposes.

# Summary

[**pyBlackScholesAnalytics**](https://github.com/gabrielepompa88/pyBlackScholesAnalytics) package is a Python package designed to implement the well known Black-Scholes model 
to evaluate price, P&L and greeks of European Options (both Plain-Vanilla and simple Equity Exotics such as Cash-or-Nothing Digital Options), as well as simple Option Strategies built on them (like Bull and Calendar Spreads).

The goal of the [**pyBlackScholesAnalytics**](https://github.com/gabrielepompa88/pyBlackScholesAnalytics) project is to reduce the gap between the coding level of a Master student and the level required for a junior Quant/Strat at an Investment Bank. We tried to achieve this goal designing a simple architecture as a playground to master financial concepts related to Options and Option Strategies using the Black-Scholes model as a _lingua franca_ together with getting the audience used to professional coding practices using the Object-Oriented paradygm.

The package has been developed as a side project of the ["IT for Business and Finance"](https://github.com/gabrielepompa88/IT-For-Business-And-Finance-2019-20) class held at the University of Siena for the Master degree in Finance during 2020.

# Contents:

The current version (0.0.1) of the package features the following modules:

- `options`: definitions for `EuropeanOption` abstract base-class as well 
as `PlainVanillaOption` and `DigitalOption` derived classes

- `portfolio`: definition of `Portfolio` class implementing analytics for portfolios of options

- `plotter`: definitions for `Plotter` abstract base-class as well 
as `OptionPlotter` and `PortfolioPlotter` derived classes

- `utils`: definition of general utility functions

- `numeric_routines`: definition of `NumericGreeks` class implementing option greeks through finite-difference methods

# Resources 

[**pyBlackScholesAnalytics**](https://github.com/gabrielepompa88/pyBlackScholesAnalytics) features several [examples](https://github.com/gabrielepompa88/pyBlackScholesAnalytics/tree/master/examples) that can be used as entry-point to explore the features of the package. 

As far as the educational purpose is concerned, I find the [**pyBlackScholesAnalytics**](https://github.com/gabrielepompa88/pyBlackScholesAnalytics) package itself important as much as the way in which its final version can be progrissevely built. For this reason, the package is complemented by a series of 4 Jupyter notebooks presenting the package step-by step in a constructive way building on the ideas of the Object-Oriented paradygm as improvements over sequential implementations of the same financial concepts:
- [
Derivatives Analytics - Introduction to Object Oriented Programming](https://github.com/gabrielepompa88/pyBlackScholesAnalytics/blob/master/Notebook_Tutorials/Derivatives_Analytics___Introduction_to_OOP.ipynb)
- [
Derivatives Analytics - Inheritance and Polymorphism](https://github.com/gabrielepompa88/pyBlackScholesAnalytics/blob/master/Notebook_Tutorials/Derivatives_Analytics___Inheritance_and_Polymorphism.ipynb)
- [Derivatives Analytics - Objects Composition](https://github.com/gabrielepompa88/pyBlackScholesAnalytics/blob/master/Notebook_Tutorials/Derivatives_Analytics___Objects_Composition.ipynb)
- [Derivatives Analytics - Options Greeks](https://github.com/gabrielepompa88/pyBlackScholesAnalytics/blob/master/Notebook_Tutorials/Derivatives_Analytics___Options_Greeks.ipynb)

Finally, YouTube video-lectures are provided for each Jupyter Notebook to better guide the reader through the material: 

- []()

# Contacts

This is the version (0.0.1) of the package, so if you have comments or suggestions you can reach Gabriele Pompa (_gabriele.pompa@gmail.com_). If you wish to contribute, please contact me through [GitHub/gabrielepompa88](https://github.com/gabrielepompa88). If you are interested but feel a bit new to Python, I can recommend the open ["IT for Business and Finance"](https://github.com/gabrielepompa88/IT-For-Business-And-Finance-2019-20) class as a reasonable starting point. 

Thank you in advance for your attention and comments.
Gabriele
