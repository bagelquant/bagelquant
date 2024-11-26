## Hi there 👋

I am Yanzhong (Eric) Huang,
- 👨‍🎓 current student in the Master of Quantitative Finance program at Rzutgers Business School.
- 🎓 Master’s degree in Banking and Finance from Monash University
- 💼 three years of experience as a quantitative analyst and developer in the Fund of Funds (FoF) industry in China

✏️ [BagelQuant](https://bagelquant.com) blog is a collection of quant skills, finance knowledge, projects, programming tips, and personal experiences. 

- [Quant skills](https://bagelquant.com/quant-skills/)
  - [Econometrics](https://bagelquant.com/econometrics/)
  - [Optimization](https://bagelquant.com/optimization/)
- [Posts](https://bagelquant.com/posts/)
- [Projects](https://bagelquant.com/projects/)


## ⌨️ Projects overview

BagelQuant provides a series of projects that aim to provide a comprehensive quant research and trading platform. The projects are written in Python and are open-source.

The projects are designed to be modular and can be used independently or together. Separate the concerns of data, strategy, and execution, the projects provide a clear separation of concerns, making it easy to develop and extend the platform.

**Base projects:**

Base projects lay the foundation for the rest of the projects. They include data providers, data storage, data types, and other essential functionalities.

-  [bagel-tushare](https://github.com/bagelquant/bagel-tushare): A Python wrapper for Tushare, a Chinese financial data provider. This project offers a simple automation tool for downloading financial data from Tushare and storing it in a local MySQL database.
- (**on-going**) [bagel-datatype](https://github.com/bagelquant/bagel-datatype): A Python library for defining and manipulating financial data types. It contains data classes for financial data, such as stocks, options, and futures. The library also provides factory functions for creating financial data objects from raw data or from a `bageltushare` style MySQL database.
- (**on-going**) [bagel-eval](https://github.com/bagelquant/bagel-eval): A Python library for evaluating financial data. It includes functions for calculating financial metrics, such as moving averages, RSI, and MACD. The library also offers Matplotlib-based visualization functions for plotting financial data.

**Strategy projects:**

- (**on-going**) [bagel-bt](https://github.com/bagelquant/bagel-bt): A Python library for backtesting trading strategies. It provides a user-friendly interface for backtesting various strategies.
- (**on-going**) [bagel-factor](https://github.com/bagelquant/bagel-factor): A Python library for factor construction, evaluation, and backtesting. It includes various methods for constructing factors.
- (**on-going**) [bagel-opt-portfolio](https://github.com/bagelquant/bagel-portfolio): A Python library for portfolio optimization, featuring various portfolio optimization methods.
