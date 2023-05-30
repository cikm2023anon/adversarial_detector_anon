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
|covtype 	 |	 **<u>1.0</u>**	 &	  **<u>1.0</u>**	|	 0.049	 |	  **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.843	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.053	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.833 |
|cod-rna 	 |	 0.743	 &	 \underline{\textbf{0.7655}}	 &	 0.161	 &	 \underline{\textbf{0.9795}}	 &	 0.955	 &	 0.880	 &	 \underline{\textbf{0.7773}}	 &	 0.599	 &	 0.238	 &	 \underline{\textbf{0.9808}}	 &	 0.936	 &	 0.889\\
diabetes 	 &	 0.672	 &	 \underline{\textbf{0.855}}	 &	 0.730	 &	 0.707	 &	 \underline{\textbf{0.8432}}	 &	 0.772	 &	 0.580	 &	 \underline{\textbf{0.8668}}	 &	 0.445	 &	 0.702	 &	 \underline{\textbf{0.8678}}	 &	 0.615\\
Fashion-MNIST 	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.157	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.839	 &	 \underline{\textbf{0.9999}}	 &	 \underline{\textbf{0.9999}}	 &	 0.237	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.908\\
ijcnn1 	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.181	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.907	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.276	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.935\\
MNIST 	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.327	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.945	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.434	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.960 \\
MNIST2-6 	 &	 \underline{\textbf{0.9999}}	 &	 \underline{\textbf{0.9999}}	 &	 0.994	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.999	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.991	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.999\\
Sensorless  &	 0.887	 &	 0.803	 &	 \underline{\textbf{0.9111}}	 &	 0.980	 &	 0.934	 &	 \underline{\textbf{0.9982}}	 &	 \underline{\textbf{0.9709}}	 &	 0.939	 &	 0.887	 &	 0.997	 &	 0.987	 &	 \underline{\textbf{0.9984}}\\
webspam &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.253	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.985	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.354	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.990\\
electricity 	 &	 0.751	 &	 \underline{\textbf{0.9763}}	 &	 0.129	 &	 0.955	 &	 \underline{\textbf{0.997}}	 &	 0.883	 &	 0.829	 &	 \underline{\textbf{0.9661}}	 &	 0.300	 &	 0.970	 &	 \underline{\textbf{0.9968}}	 &	 0.901\\
drybean 	 &	 0.942	 &	 \underline{\textbf{0.9617}}	 &	 0.705	 &	 0.975	 &	 \underline{\textbf{0.9862}}	 &	 0.974	 &	 \underline{\textbf{0.9585}}	 &	 0.914	 &	 0.796	 &	 \underline{\textbf{0.9868}}	 &	 0.955	 &	 0.967\\
adult 	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.109	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.813	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.128	 &	 \underline{\textbf{1.0}}	 &	 \underline{\textbf{1.0}}	 &	 0.817\\
banknote 	 &	 0.968	 &	 \underline{\textbf{0.99}}	 &	 0.768	 &	 0.970	 &	 \underline{\textbf{0.9918}}	 &	 0.961	 &	 \underline{\textbf{0.9699}}	 &	 0.961	 &	 0.798	 &	 \underline{\textbf{0.9822}}	 &	 0.982	 &	 0.957 \\
gender-by-voice  &	 \underline{\textbf{0.9854}}	 &	 0.983	 &	 0.887	 &	 \underline{\textbf{0.9897}}	 &	 0.989	 &	 0.978	 &	 0.982	 &	 \underline{\textbf{0.9964}}	 &	 0.960	 &	 0.990	 &	 \underline{\textbf{0.9975}}	 &	 0.993\\
waveform 	 &	 0.540	 &	 \underline{\textbf{0.5538}}	 &	 0.380	 &	 0.803	 &	 0.801	 &	 \underline{\textbf{0.8628}}	 &	 0.467	 &	 \underline{\textbf{0.5575}}	 &	 0.461	 &	 0.717	 &	 0.779	 &	 \underline{\textbf{0.8665}}\\
wind 	 &	 0.695	 &	 \underline{\textbf{0.8821}}	 &	 0.183	 &	 0.858	 &	 \underline{\textbf{0.9414}}	 &	 0.730	 &	 0.526	 &	 \underline{\textbf{0.7558}}	 &	 0.205	 &	 0.819	 &	 \underline{\textbf{0.8812}}	 &	 0.742\\
speech 	|	 0.990	 |	 0.915	 |	<u>1.0</u> 	|	 0.999	 |	 0.995	 |	 <u>1.0</u>	 |	 <u>0.9943</u>	 |	 0.965	 |	 0.967	|	 <u>0.9987</u>	 | 0.990	 |	 0.998  |
