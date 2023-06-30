# ELM_Stock_Prediction

A project focusing on ELM (Extreme Learning Machine) stock prediction.

The ELM has been regularized in a fashion novel to the literature. This involves using an `L2` regularization plus a residual, inspired by the well-known Theta model, but presented in a more generalized form. This approach also considers the minimization of both RMS (Root Mean Square) error and the correlation between the target and prediction. 

The Theta-model-type residual yields a model that is most stable and capable in the extrapolation regime, while the correlation-type regularization helps in reducing the temporal oscillation in the predictions. 

The system has proved to be highly effective on Forex and high-speed trading where it finds highly nonlinear interactions at the speed of a simple linear regression.


## Author

This project is authored by Antonio Di Cecco, created on 29/06/2023.

## License

This project is licensed under a [Creative Commons Attribution-NonCommercial-NoDerivs 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/).

[![License: CC BY-NC-ND 4.0](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

This code is available for use with reference to the author. However, it may not be used for commercial purposes or resold.


