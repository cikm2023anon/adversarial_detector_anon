# adversarial_detector_anon

\section{XGBoost Full Experiments Results}
\label{appendix:appendix_b}

In Tables \ref{tab:xgboost_signopt_exp_table}, \ref{tab:xgboost_opt_exp_table} \ref{tab:xgboost_hsja_exp_table}, \ref{tab:xgboost_cube_exp_table}, and \ref{tab:xgboost_lt_exp_table} we can see the raw metrics of the experiments for each dataset, attack method, and norm for the XGBoost target experiments. In bold is the method or methods that achieved the highest value. Rows that fill in hyphens are cases where the adversarial sample creation process failed.

<details>
<summary>Example</summary>
  nananana
</details>
# Sign-OPT XGBoost Experiments Results


| Dataset  | New    |  Original  | OC-score  |  New   | Original | OC-score  | New   | Original  | OC-score |  New   | Original | OC-score|
|----------------|--------|------------|-----------|--------|----------|-----------|-------|-----------|----------|--------|----------|----------|
|  breast-cancer    |	0.988 |	 **<u>0.9919</u>**	|	 0.958	 |	 0.987	 |	 **<u>0.9919</u>**	 |	 0.965	 |	 **<u>0.9971</u>**	 |	 0.997	 |	 0.960	 |	**<u>0.997</u>**	 |	 **<u>0.997</u>**	 |	 0.970 |
|covtype 	 |	 **<u>1.0</u>**	 |	  **<u>1.0</u>**	|	 0.049	 |	  **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.843	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.053	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.833 |
|cod-rna 	 |	 0.743	 |	 **<u>0.7655</u>**	 |	 0.161	 |	 **<u>0.9795</u>**	 |	 0.955	 |	 0.880	 |	 **<u>0.7773</u>**	 |	 0.599	 |	 0.238	 |	 **<u>0.9808</u>**	 |	 0.936	 |	 0.889|
|diabetes 	 |	 0.672	 |	 **<u>0.855</u>**	 |	 0.730	 |	 0.707	 |	 **<u>0.8432</u>**	 |	 0.772	 |	 0.580	 |	 **<u>0.8668</u>**	 |	 0.445	 |	 0.702	 |	 **<u>0.8678</u>**	 |	 0.615|
|Fashion-MNIST 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.157	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.839	 |	 **<u>0.9999</u>**	 |	 **<u>0.9999</u>**	 |	 0.237	 |	 **<u>1.0</u>**	 |	**<u>1.0</u>**	 |	 0.908|
| ijcnn1 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.181	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.907	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.276	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.935|
| MNIST 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.327	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.945	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.434	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.960 |
| MNIST2-6 	 |	 **<u>0.9999</u>**	 |	 **<u>0.9999</u>**	 |	 0.994	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.999	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.991	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.999|
| Sensorless  |	 0.887	 |	 0.803	 |	 **<u>0.9111</u>**	 |	 0.980	 |	 0.934	 |	 **<u>0.9982</u>**	 |	 **<u>0.9709</u>**	 |	 0.939	 |	 0.887	 |	 0.997	 |	 0.987	 |	 **<u>0.9984</u>**|
| webspam |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.253	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.985	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.354	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.990|
| electricity 	 |	 0.751	 |	 **<u>0.9763</u>**	 |	 0.129	 |	 0.955	 |	 **<u>0.997</u>**	 |	 0.883	 |	 0.829	 |	 **<u>0.9661</u>**	 |	 0.300	 |	 0.970	 |	 **<u>0.9968</u>**	 |	 0.901|
| drybean 	 |	 0.942	 |	 **<u>0.9617</u>**	 |	 0.705	 |	 0.975	 |	 **<u>0.9862</u>**	 |	 0.974	 |	 **<u>0.9585</u>**	 |	 0.914	 |	 0.796	 |	 **<u>0.9868</u>**	 |	 0.955	 |	 0.967|
| adult 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.109	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.813	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.128	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.817|
| banknote 	 |	 0.968	 |	 **<u>0.99</u>**	 |	 0.768	 |	 0.970	 |	 **<u>0.9918</u>**	 |	 0.961	 |	 **<u>0.9699</u>**	 |	 0.961	 |	 0.798	 |	 **<u>0.9822</u>**	 |	 0.982	 |	 0.957 |
| gender-by-voice  |	 **<u>0.9854</u>**	 |	 0.983	 |	 0.887	 |	 **<u>0.9897</u>**	 |	 0.989	 |	 0.978	 |	 0.982	 |	 **<u>0.9964</u>**	 |	 0.960	 |	 0.990	 |	 **<u>0.9975</u>**	 |	 0.993|
| waveform 	 |	 0.540	 |	 **<u>0.5538</u>**	 |	 0.380	 |	 0.803	 |	 0.801	 |	 **<u>0.8628</u>**	 |	 0.467	 |	 **<u>0.5575</u>**	 |	 0.461	 |	 0.717	 |	 0.779	 |	 **<u>0.8665</u>**|
| wind 	 |	 0.695	 |	 **<u>0.8821</u>**	 |	 0.183	 |	 0.858	 |	 **<u>0.9414</u>**	 |	 0.730	 |	 0.526	 |	 **<u>0.7558</u>**	 |	 0.205	 |	 0.819	 |	 **<u>0.8812</u>**	 |	 0.742 |
| speech 	|	 0.990	 |	 0.915	 |	**<u>1.0</u>** 	|	 0.999	 |	 0.995	 |	 **<u>1.0</u>**	 |	 **<u>0.9943</u>**	 |	 0.965	 |	 0.967	|	 **<u>0.9987</u>**	 | 0.990	 |	 0.998  |
