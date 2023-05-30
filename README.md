# Adversarial Evasion Attacks Detection for Tree-Based Ensembles: A Representation Learning Approach - Full Experiments Results

# XGBoost Full Experiments Results

In Tables \ref{tab:xgboost_signopt_exp_table}, \ref{tab:xgboost_opt_exp_table} \ref{tab:xgboost_hsja_exp_table}, \ref{tab:xgboost_cube_exp_table}, and \ref{tab:xgboost_lt_exp_table} we can see the raw metrics of the experiments for each dataset, attack method, and norm for the XGBoost target experiments. In bold is the method or methods that achieved the highest value. Rows that fill in hyphens are cases where the adversarial sample creation process failed.

<details>
<summary>Sign-OPT XGBoost Experiments Results</summary>

<table>
  <thead>
    <tr>
      <th rowspan="2"></th>
      <th colspan="6">Sign-OPT $L_2$</th>
      <th colspan="6">Sign-OPT $L_\infty$</th>
    </tr>
    <tr>
      <th colspan="3">PRC-AUC</th>
      <th colspan="3">ROC-AUC</th>
      <th colspan="3">PRC-AUC</th>
      <th colspan="3">ROC-AUC</th>
    </tr>
    <tr>
      <th>Dataset</th>
      <th>New</th>
      <th>Original</th>
      <th>OC-score</th>
      <th>New</th>
      <th>Original</th>
      <th>OC-score</th>
      <th>New</th>
      <th>Original</th>
      <th>OC-score</th>
      <th>New</th>
      <th>Original</th>
      <th>OC-score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>breast-cancer</td>
      <td>0.988</td>
      <td><strong><u>0.9919</u></strong></td>
      <td>0.958</td>
      <td>0.987</td>
      <td><strong><u>0.9919</u></strong></td>
      <td>0.965</td>
      <td><strong><u>0.9971</u></strong></td>
      <td>0.997</td>
      <td>0.960</td>
      <td><strong><u>0.997</u></strong></td>
      <td><strong><u>0.997</u></strong></td>
      <td>0.970</td>
    </tr>
    <tr>
      <td>covtype</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.049</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.843</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.053</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.833</td>
    </tr>
    <tr>
      <td>cod-rna</td>
      <td>0.743</td>
      <td><strong><u>0.7655</u></strong></td>
      <td>0.161</td>
      <td><strong><u>0.9795</u></strong></td>
      <td>0.955</td>
      <td>0.880</td>
      <td><strong><u>0.7773</u></strong></td>
      <td>0.599</td>
      <td>0.238</td>
      <td><strong><u>0.9808</u></strong></td>
      <td>0.936</td>
      <td>0.889</td>
    </tr>
    <tr>
      <td>diabetes</td>
      <td>0.672</td>
      <td><strong><u>0.855</u></strong></td>
      <td>0.730</td>
      <td>0.707</td>
      <td><strong><u>0.8432</u></strong></td>
      <td>0.772</td>
      <td>0.580</td>
      <td><strong><u>0.8668</u></strong></td>
      <td>0.445</td>
      <td>0.702</td>
      <td><strong><u>0.8678</u></strong></td>
      <td>0.615</td>
    </tr>
    <tr>
      <td>Fashion-MNIST</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.157</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.839</td>
      <td><strong><u>0.9999</u></strong></td>
      <td><strong><u>0.9999</u></strong></td>
      <td>0.237</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.908</td>
    </tr>
    <tr>
      <td>ijcnn1</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.181</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.907</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.276</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.935</td>
    </tr>
    <tr>
      <td>MNIST</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.327</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.945</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.434</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.960</td>
    </tr>
    <tr>
      <td>MNIST2-6</td>
      <td><strong><u>0.9999</u></strong></td>
      <td><strong><u>0.9999</u></strong></td>
      <td>0.994</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.999</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.991</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.999</td>
    </tr>
    <tr>
      <td>Sensorless</td>
      <td>0.887</td>
      <td>0.803</td>
      <td><strong><u>0.9111</u></strong></td>
      <td>0.980</td>
      <td>0.934</td>
      <td><strong><u>0.9982</u></strong></td>
      <td><strong><u>0.9709</u></strong></td>
      <td>0.939</td>
      <td>0.887</td>
      <td>0.997</td>
      <td>0.987</td>
      <td><strong><u>0.9984</u></strong></td>
    </tr>
    <tr>
      <td>webspam</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.253</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.985</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.354</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.990</td>
    </tr>
    <tr>
      <td>electricity</td>
      <td>0.751</td>
      <td><strong><u>0.9763</u></strong></td>
      <td>0.129</td>
      <td>0.955</td>
      <td><strong><u>0.997</u></strong></td>
      <td>0.883</td>
      <td>0.829</td>
      <td><strong><u>0.9661</u></strong></td>
      <td>0.300</td>
      <td>0.970</td>
      <td><strong><u>0.9968</u></strong></td>
      <td>0.901</td>
    </tr>
    <tr>
      <td>drybean</td>
      <td>0.942</td>
      <td><strong><u>0.9617</u></strong></td>
      <td>0.705</td>
      <td>0.975</td>
      <td><strong><u>0.9862</u></strong></td>
      <td>0.974</td>
      <td><strong><u>0.9585</u></strong></td>
      <td>0.914</td>
      <td>0.796</td>
      <td><strong><u>0.9868</u></strong></td>
      <td>0.955</td>
      <td>0.967</td>
    </tr>
    <tr>
      <td>adult</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.109</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.813</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.128</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.817</td>
    </tr>
    <tr>
      <td>banknote</td>
      <td>0.968</td>
      <td><strong><u>0.99</u></strong></td>
      <td>0.768</td>
      <td>0.970</td>
      <td><strong><u>0.9918</u></strong></td>
      <td>0.961</td>
      <td><strong><u>0.9699</u></strong></td>
      <td>0.961</td>
      <td>0.798</td>
      <td><strong><u>0.9822</u></strong></td>
      <td>0.982</td>
      <td>0.957</td>
    </tr>
    <tr>
      <td>gender-by-voice</td>
      <td><strong><u>0.9854</u></strong></td>
      <td>0.983</td>
      <td>0.887</td>
      <td><strong><u>0.9897</u></strong></td>
      <td>0.989</td>
      <td>0.978</td>
      <td>0.982</td>
      <td><strong><u>0.9964</u></strong></td>
      <td>0.960</td>
      <td>0.990</td>
      <td><strong><u>0.9975</u></strong></td>
      <td>0.993</td>
    </tr>
    <tr>
      <td>waveform</td>
      <td>0.540</td>
      <td><strong><u>0.5538</u></strong></td>
      <td>0.380</td>
      <td>0.803</td>
      <td>0.801</td>
      <td><strong><u>0.8628</u></strong></td>
      <td>0.467</td>
      <td><strong><u>0.5575</u></strong></td>
      <td>0.461</td>
      <td>0.717</td>
      <td>0.779</td>
      <td><strong><u>0.8665</u></strong></td>
    </tr>
    <tr>
      <td>wind</td>
      <td>0.695</td>
      <td><strong><u>0.8821</u></strong></td>
      <td>0.183</td>
      <td>0.858</td>
      <td><strong><u>0.9414</u></strong></td>
      <td>0.730</td>
      <td>0.526</td>
      <td><strong><u>0.7558</u></strong></td>
      <td>0.205</td>
      <td>0.819</td>
      <td><strong><u>0.8812</u></strong></td>
      <td>0.742</td>
    </tr>
    <tr>
      <td>speech</td>
      <td>0.990</td>
      <td>0.915</td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.999</td>
      <td>0.995</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>0.9943</u></strong></td>
      <td>0.965</td>
      <td>0.967</td>
      <td><strong><u>0.9987</u></strong></td>
      <td>0.990</td>
      <td>0.998</td>
    </tr>
  </tbody>
</table>
</details>

<details>
<summary>OPT XGBoost Experiments Results</summary>

| Dataset          | New    |  Original  | OC-score  |  New   | Original | OC-score  | New    |  Original  | OC-score |  New   | Original | OC-score |
|------|------|---------|----|------|-------|-----|------|--------|---|----|----|------|
| breast-cancer   |	 0.992	 |	 **<u>0.9956</u>**	 |	 0.867	 |	 0.992	 |	 **<u>0.9952</u>**	 |	 0.925	 |	 0.973	 |	 **<u>0.9737</u>**	 |	 0.920	 |	 **<u>0.9788</u>**	 |	 0.978	 |	 0.968 |
| covtype   		 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.056	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.768	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.072	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.856|
| cod-rna 	 |	 **<u>0.804</u>**	 |	 0.716	 |	 0.183	 |	 **<u>0.9808</u>**	 |	 0.958	 |	 0.892	 |	 **<u>0.8035</u>**	 |	 0.647	 |	 0.234	 |	 **<u>0.9774</u>**	 |	 0.953	 |	 0.907 |
| diabetes   	 |	 0.652	 |	 **<u>0.8434</u>**	 |	 0.594	 |	 0.675	 |	 **<u>0.8612</u>**	 |	 0.741	 |	 **<u>0.8455</u>**	 |	 0.751	 |	 0.699	 |	 **<u>0.8174</u>**	 |	 0.745	 |	 0.736 |
| Fashion-MNIST 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.370	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.923	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.445	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.936 |
| ijcnn1	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.273	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.926	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.246	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.941 |
| MNIST   		 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.476	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.971	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.566	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.975 |
| MNIST2-6 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.996	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	  **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.986	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.999 |
| sensorless 	 |	 **<u>0.9929</u>**	 |	 0.974	 |	 0.883	 |	 **<u>0.9998</u>**	 |	 0.999	 |	 0.999	 |	 **<u>0.9871</u>**	 |	 0.965	 |	 0.877	 |	 **<u>0.999</u>**	 |	 0.993	 |	 0.998 |
| webspam 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.399	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.992	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.387	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.991 |
| electricity 	 |	 0.774	 |	 **<u>0.8818</u>**	 |	 0.248	 |	 0.948	 |	 **<u>0.982</u>**	 |	 0.887	 |	 0.852	 |	 **<u>0.891</u>**	 |	 0.286	 |	 **<u>0.9731</u>**	 |	 0.960	 |	 0.904 |
| drybean |	 **<u>0.9536</u>**	 |	 0.935	 |	 0.848	 |	 **<u>0.9861</u>**	 |	 0.969	 |	 0.984	 |	 **<u>0.9396</u>**	 |	 0.934	 |	 0.877	 |	 0.964	 |	 0.970	 |	 **<u>0.9869</u>** |
| adult 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.076	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.791	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.058	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.702 |
| banknote  		 |	 **<u>0.9893</u>**	 |	 0.950	 |	 0.911	 |	 **<u>0.9906</u>**	 |	 0.984	 |	 0.976	 |	 **<u>0.956</u>**	 |	 0.942	 |	 0.876	 |	 0.974	 |	 0.967	 |	 **<u>0.9767</u>** |
| gender-by-voice 	 |	 0.964	 |	 **<u>0.9943</u>**	 |	 0.812	 |	 0.981	 |	 **<u>0.9964</u>**	 |	 0.964	 |	 0.976	 |	 **<u>0.9926</u>**	 |	 0.842	 |	 0.987	 |	 **<u>0.9951</u>**	 |	 0.974 |
| waveform  	 |	 0.538	 |	 **<u>0.6195</u>**	 |	 0.392	 |	 0.784	 |	 0.777	 |	 **<u>0.8524</u>**	 |	 0.590	 |	 **<u>0.6673</u>**	 |	 0.395	 |	 0.819	 |	 0.800	 |	 **<u>0.8813</u>** |
| wind |	 0.476	 |	 **<u>0.7908</u>**	 |	 0.210	 |	 0.777	 |	 **<u>0.9054</u>**	 |	 0.785	 |	 0.423	 |	 **<u>0.7694</u>**	 |	 0.176	 |	 0.755	 |	 **<u>0.8653</u>**	 |	 0.729 |
| speech 	 |	 **<u>0.9917</u>**	 |	 0.983	 |	 0.973	 |	 **<u>0.9986</u>**	 |	 0.997	 |	 0.998	 |	 **<u>0.9957</u>**	 |	 0.799	 |	 0.984	 |	 0.9996	 |	 0.977	 |	 **<u>1.0</u>** |

</details>
