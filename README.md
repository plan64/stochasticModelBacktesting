# stochasticModelBacktesting
Educational code: Is a specified stochastic model compatible with observed historic stock prices?


Backtesting is the testing of a predictive model on historic observations. Are, in a statistical sense, the observed historic samples likely under the assumption that the model has been chosen appropriately?
Being an integral part of the development of financial market models and risk measurement, backtesting plays a key role in operations of major investment firms. Its role has been institutionalized within the Basel III regulatory guidance of the Basel Committee on Banking Supervision (https://www.bis.org/publ/bcbs22.htm), which contains a summary of practices how to validate and test internal models.

This repo illustrates the backtesting methodology for educational purpose. It orients itself at [A Sound Basel III Compliant Framework for Backtesting Credit Exposure Models](http://dx.doi.org/10.2139/ssrn.2264620).

Content:

* modelBacktesting_standardRiskFactor.ipynb: Introductory notebook, presenting the basic methods of stochastic model testing and some common limitations and errors.

* modelBacktesting_riskFactorWith4Moments.ipynb: In recent years market-implied models that predict moments of the distribution of returns from current option market data have gained popularity. This notebook builds introduces a basic backtesting methodology for moment-based models. The notebook builds on modelBacktesting_standardRiskFactor.ipynb.

Author: Oleg Szehr, IDSIA, Switzerland, oleg.szehr@idsia.ch