# Adversarial Evasion Attacks Detection for Tree-Based Ensembles: A Representation Learning Approach - Full Experiments Results

# XGBoost Full Experiments Results

In Tables 1,2,3,4 and 5 we can see the raw metrics of the experiments for each dataset, attack method, and norm for the XGBoost target experiments. In bold is the method or methods that achieved the highest value. Rows that fill in hyphens are cases where the adversarial sample creation process failed.

### Table 1: Sign-OPT XGBoost Experiments Results

<table>
  <thead>
    <tr>
      <th rowspan="2"></th>
      <th colspan="6">Sign-OPT $L_2$ </th>
      <th colspan="6">Sign-OPT $L_\infty$ </th>
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
  

### Table 2: OPT XGBoost Experiments Results

<table>
  <thead>
    <tr>
      <th rowspan="2"></th>
      <th colspan="6">OPT $L_2$ </th>
      <th colspan="6">OPT $L_\infty$ </th>
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
      <td>0.992</td>
      <td><strong><u>0.9956</u></strong></td>
      <td>0.867</td>
      <td>0.992</td>
      <td><strong><u>0.9952</u></strong></td>
      <td>0.925</td>
      <td>0.973</td>
      <td><strong><u>0.9737</u></strong></td>
      <td>0.920</td>
      <td><strong><u>0.9788</u></strong></td>
      <td>0.978</td>
      <td>0.968</td>
    </tr>
    <tr>
      <td>covtype</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.056</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.768</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.072</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.856</td>
    </tr>
    <tr>
      <td>cod-rna</td>
      <td><strong><u>0.804</u></strong></td>
      <td>0.716</td>
      <td>0.183</td>
      <td><strong><u>0.9808</u></strong></td>
      <td>0.958</td>
      <td>0.892</td>
      <td><strong><u>0.8035</u></strong></td>
      <td>0.647</td>
      <td>0.234</td>
      <td><strong><u>0.9774</u></strong></td>
      <td>0.953</td>
      <td>0.907</td>
    </tr>
    <tr>
      <td>diabetes</td>
      <td>0.652</td>
      <td><strong><u>0.8434</u></strong></td>
      <td>0.594</td>
      <td>0.675</td>
      <td><strong><u>0.8612</u></strong></td>
      <td>0.741</td>
      <td><strong><u>0.8455</u></strong></td>
      <td>0.751</td>
      <td>0.699</td>
      <td><strong><u>0.8174</u></strong></td>
      <td>0.745</td>
      <td>0.736</td>
    </tr>
    <tr>
      <td>Fashion-MNIST</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.370</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.923</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.445</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.936</td>
    </tr>
    <tr>
      <td>ijcnn1</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.273</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.926</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.246</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.941</td>
    </tr>
    <tr>
      <td>MNIST</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.476</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.971</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.566</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.975</td>
    </tr>
    <tr>
      <td>MNIST2-6</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.996</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.986</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.999</td>
    </tr>
    <tr>
      <td>sensorless</td>
      <td><strong><u>0.9929</u></strong></td>
      <td>0.974</td>
      <td>0.883</td>
      <td><strong><u>0.9998</u></strong></td>
      <td>0.999</td>
      <td>0.999</td>
      <td><strong><u>0.9871</u></strong></td>
      <td>0.965</td>
      <td>0.877</td>
      <td><strong><u>0.999</u></strong></td>
      <td>0.993</td>
      <td>0.998</td>
    </tr>
    <tr>
      <td>webspam</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.399</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.992</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.387</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.991</td>
    </tr>
    <tr>
      <td>electricity</td>
      <td>0.774</td>
      <td><strong><u>0.8818</u></strong></td>
      <td>0.248</td>
      <td>0.948</td>
      <td><strong><u>0.982</u></strong></td>
      <td>0.887</td>
      <td>0.852</td>
      <td><strong><u>0.891</u></strong></td>
      <td>0.286</td>
      <td><strong><u>0.9731</u></strong></td>
      <td>0.960</td>
      <td>0.904</td>
    </tr>
    <tr>
      <td>drybean</td>
      <td><strong><u>0.9536</u></strong></td>
      <td>0.935</td>
      <td>0.848</td>
      <td><strong><u>0.9861</u></strong></td>
      <td>0.969</td>
      <td>0.984</td>
      <td><strong><u>0.9396</u></strong></td>
      <td>0.934</td>
      <td>0.877</td>
      <td>0.964</td>
      <td>0.970</td>
      <td><strong><u>0.9869</u></strong></td>
    </tr>
    <tr>
      <td>adult</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.076</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.791</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.058</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.702</td>
    </tr>
    <tr>
      <td>banknote</td>
      <td><strong><u>0.9893</u></strong></td>
      <td>0.950</td>
      <td>0.911</td>
      <td><strong><u>0.9906</u></strong></td>
      <td>0.984</td>
      <td>0.976</td>
      <td><strong><u>0.956</u></strong></td>
      <td>0.942</td>
      <td>0.876</td>
      <td>0.974</td>
      <td>0.967</td>
      <td><strong><u>0.9767</u></strong></td>
    </tr>
    <tr>
      <td>gender-by-voice</td>
      <td>0.964</td>
      <td><strong><u>0.9943</u></strong></td>
      <td>0.812</td>
      <td>0.981</td>
      <td><strong><u>0.9964</u></strong></td>
      <td>0.964</td>
      <td>0.976</td>
      <td><strong><u>0.9926</u></strong></td>
      <td>0.842</td>
      <td>0.987</td>
      <td><strong><u>0.9951</u></strong></td>
      <td>0.974</td>
    </tr>
    <tr>
      <td>waveform</td>
      <td>0.538</td>
      <td><strong><u>0.6195</u></strong></td>
      <td>0.392</td>
      <td>0.784</td>
      <td>0.777</td>
      <td><strong><u>0.8524</u></strong></td>
      <td>0.590</td>
      <td><strong><u>0.6673</u></strong></td>
      <td>0.395</td>
      <td>0.819</td>
      <td>0.800</td>
      <td><strong><u>0.8813</u></strong></td>
    </tr>
    <tr>
      <td>wind</td>
      <td>0.476</td>
      <td><strong><u>0.7908</u></strong></td>
      <td>0.210</td>
      <td>0.777</td>
      <td><strong><u>0.9054</u></strong></td>
      <td>0.785</td>
      <td>0.423</td>
      <td><strong><u>0.7694</u></strong></td>
      <td>0.176</td>
      <td>0.755</td>
      <td><strong><u>0.8653</u></strong></td>
      <td>0.729</td>
    </tr>
    <tr>
      <td>speech</td>
      <td><strong><u>0.9917</u></strong></td>
      <td>0.983</td>
      <td>0.973</td>
      <td><strong><u>0.9986</u></strong></td>
      <td>0.997</td>
      <td>0.998</td>
      <td><strong><u>0.9957</u></strong></td>
      <td>0.799</td>
      <td>0.984</td>
      <td>0.9996</td>
      <td>0.977</td>
      <td><strong><u>1.0</u></strong></td>
    </tr>
  </tbody>
</table>

### Table 3: HSJA XGBoost Experiments Results

|Dataset          | New    |  Original  | OC-score  |  New   | Original | OC-score  | New    |  Original  | OC-score |  New   | Original | OC-score |
|----|----|----|----|----|----|----|----|----|----|----|----|----|
breast-cancer    	 |	 **<u>0.9909</u>**	 |	 0.988	 |	 0.799	 |	 **<u>0.9905</u>**	 |	 0.988	 |	 0.923	 |	 0.982	 |	 **<u>0.9956</u>**	 |	 0.934	 |	 0.987	 |	 **<u>0.9958</u>**	 |	 0.954|
covtype |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.159	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.832	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.230	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.811|
cod-rna 	 |	 **<u>0.8193</u>**	 |	 0.669	 |	 0.107	 |	 **<u>0.9879</u>**	 |	 0.926	 |	 0.817	 |	 **<u>0.8389</u>**	 |	 0.594	 |	 0.185	 |	 **<u>0.9891</u>**	 |	 0.944	 |	 0.847|
diabetes    	 |	 **<u>0.7947</u>**	 |	 0.786	 |	 0.522	 |	 **<u>0.834</u>**	 |	 0.830	 |	 0.708	 |	 0.787	 |	 **<u>0.8219</u>**	 |	 0.516	 |	 0.790	 |	 **<u>0.8325</u>**	 |	 0.710|
Fashion-MNIST 	 |	 0.994	 |	 **<u>0.998</u>**	 |	 0.235	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.881	 |	**<u>1.0</u>**  |	 0.9997	 |	 0.266	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.868|
ijcnn1 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.089	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.846	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.132	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.893|
MNIST |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.493	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.954	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.420	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.945|
MNIST2-6 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.965	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.998	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.972	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.998|
sensorless |	 **<u>0.8562</u>**	 |	 0.729	 |	 0.839	 |	 0.972	 |	 0.920	 |	 **<u>0.9973</u>**	 |	 **<u>0.9175</u>**	 |	 0.782	 |	 0.893	 |	 0.990	 |	 0.934	 |	 **<u>0.9984</u>**|
 webspam |	 **<u>0.9859</u>**	 |	 0.986	 |	 0.232	 |	 0.9999	 |	 **<u>1.0</u>**	 |	 0.986	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.212	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.984|
electricity 	 |	 0.795	 |	 **<u>0.9084</u>**	 |	 0.098	 |	 0.962	 |	 **<u>0.9789</u>**	 |	 0.824	 |	 **<u>0.8877</u>**	 |	 0.853	 |	 0.189	 |	 **<u>0.9841</u>**	 |	 0.953	 |	 0.852|
drybean 	 |	 **<u>0.9568</u>**	 |	 0.943	 |	 0.872	 |	 **<u>0.9826</u>**	 |	 0.974	 |	 0.977	 |	 **<u>0.9561</u>**	 |	 0.953	 |	 0.846	 |	 **<u>0.9795</u>**	 |	 0.979	 |	 0.978|
adult 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.458	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.905	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.366	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.883|
banknote  		 |	 **<u>0.8879</u>**	 |	 0.851	 |	 0.742	 |	 0.889	 |	 **<u>0.9017</u>**	 |	 0.901	 |	 0.895	 |	 **<u>0.901</u>**	 |	 0.658	 |	 **<u>0.9265</u>**	 |	 0.907	 |	 0.869|
gender-by-voice 	 |	 0.920	 |	 **<u>0.9668</u>**	 |	 0.787	 |	 0.952	 |	 **<u>0.9758</u>**	 |	 0.962	 |	 0.961	 |	 **<u>0.9882</u>**	 |	 0.721	 |	 0.975	 |	 **<u>0.9927</u>**	 |	 0.947|
waveform  	 |	 **<u>0.6012</u>**	 |	 0.592	 |	 0.493	 |	 0.774	 |	 0.768	 |	 **<u>0.883</u>**	 |	 0.680	 |	 **<u>0.692</u>**	 |	 0.372	 |	 **<u>0.8323</u>**	 |	 0.815	 |	 0.831|
wind |	 0.763	 |	 **<u>0.7846</u>**	 |	 0.309	 |	 0.881	 |	 **<u>0.8814</u>**	 |	 0.824	 |	 0.712	 |	 **<u>0.8311</u>**	 |	 0.328	 |	 0.870	 |	 **<u>0.9151</u>**	 |	 0.789|
speech 	 |	 **<u>0.9965</u>**	 |	 0.994	 |	 0.989	 |	 **<u>0.9993</u>**	 |	 0.999	 |	 0.999	 |	 0.996	 |	 0.994	 |	 **<u>0.9995</u>**	 |	 0.999	 |	 0.998	 |	 **<u>1.0</u>**|
