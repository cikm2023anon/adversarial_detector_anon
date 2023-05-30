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

<table>
  <thead>
    <tr>
      <th rowspan="2"></th>
      <th colspan="6">HSJA $L_2$ </th>
      <th colspan="6">HSJA $L_\infty$ </th>
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
      <td><strong><u>0.9909</u></strong></td>
      <td>0.988</td>
      <td>0.799</td>
      <td><strong><u>0.9905</u></strong></td>
      <td>0.988</td>
      <td>0.923</td>
      <td>0.982</td>
      <td><strong><u>0.9956</u></strong></td>
      <td>0.934</td>
      <td>0.987</td>
      <td><strong><u>0.9958</u></strong></td>
      <td>0.954</td>
    </tr>
    <tr>
      <td>covtype</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.159</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.832</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.230</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.811</td>
    </tr>
    <tr>
      <td>cod-rna</td>
      <td><strong><u>0.8193</u></strong></td>
      <td>0.669</td>
      <td>0.107</td>
      <td><strong><u>0.9879</u></strong></td>
      <td>0.926</td>
      <td>0.817</td>
      <td><strong><u>0.8389</u></strong></td>
      <td>0.594</td>
      <td>0.185</td>
      <td><strong><u>0.9891</u></strong></td>
      <td>0.944</td>
      <td>0.847</td>
    </tr>
    <tr>
      <td>diabetes</td>
      <td><strong><u>0.7947</u></strong></td>
      <td>0.786</td>
      <td>0.522</td>
      <td><strong><u>0.834</u></strong></td>
      <td>0.830</td>
      <td>0.708</td>
      <td>0.787</td>
      <td><strong><u>0.8219</u></strong></td>
      <td>0.516</td>
      <td>0.790</td>
      <td><strong><u>0.8325</u></strong></td>
      <td>0.710</td>
    </tr>
    <tr>
      <td>Fashion-MNIST</td>
      <td>0.994</td>
      <td><strong><u>0.998</u></strong></td>
      <td>0.235</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.881</td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.9997</td>
      <td>0.266</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.868</td>
    </tr>
    <tr>
      <td>ijcnn1</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.089</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.846</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.132</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.893</td>
    </tr>
    <tr>
      <td>MNIST</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.493</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.954</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.420</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.945</td>
    </tr>
    <tr>
      <td>MNIST2-6</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.965</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.998</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.972</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.998</td>
    </tr>
    <tr>
      <td>sensorless</td>
      <td><strong><u>0.8562</u></strong></td>
      <td>0.729</td>
      <td>0.839</td>
      <td>0.972</td>
      <td>0.920</td>
      <td><strong><u>0.9973</u></strong></td>
      <td><strong><u>0.9175</u></strong></td>
      <td>0.782</td>
      <td>0.893</td>
      <td>0.990</td>
      <td>0.934</td>
      <td><strong><u>0.9984</u></strong></td>
    </tr>
    <tr>
      <td>webspam</td>
      <td><strong><u>0.9859</u></strong></td>
      <td>0.986</td>
      <td>0.232</td>
      <td>0.9999</td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.986</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.212</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.984</td>
    </tr>
    <tr>
      <td>electricity</td>
      <td>0.795</td>
      <td><strong><u>0.9084</u></strong></td>
      <td>0.098</td>
      <td>0.962</td>
      <td><strong><u>0.9789</u></strong></td>
      <td>0.824</td>
      <td><strong><u>0.8877</u></strong></td>
      <td>0.853</td>
      <td>0.189</td>
      <td><strong><u>0.9841</u></strong></td>
      <td>0.953</td>
      <td>0.852</td>
    </tr>
    <tr>
      <td>drybean</td>
      <td><strong><u>0.9568</u></strong></td>
      <td>0.943</td>
      <td>0.872</td>
      <td><strong><u>0.9826</u></strong></td>
      <td>0.974</td>
      <td>0.977</td>
      <td><strong><u>0.9561</u></strong></td>
      <td>0.953</td>
      <td>0.846</td>
      <td><strong><u>0.9795</u></strong></td>
      <td>0.979</td>
      <td>0.978</td>
    </tr>
    <tr>
      <td>adult</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.458</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.905</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.366</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.883</td>
    </tr>
    <tr>
      <td>banknote</td>
      <td><strong><u>0.8879</u></strong></td>
      <td>0.851</td>
      <td>0.742</td>
      <td>0.889</td>
      <td><strong><u>0.9017</u></strong></td>
      <td>0.901</td>
      <td>0.895</td>
      <td><strong><u>0.901</u></strong></td>
      <td>0.658</td>
      <td><strong><u>0.9265</u></strong></td>
      <td>0.907</td>
      <td>0.869</td>
    </tr>
    <tr>
      <td>gender-by-voice</td>
      <td>0.920</td>
      <td><strong><u>0.9668</u></strong></td>
      <td>0.787</td>
      <td>0.952</td>
      <td><strong><u>0.9758</u></strong></td>
      <td>0.962</td>
      <td>0.961</td>
      <td><strong><u>0.9882</u></strong></td>
      <td>0.721</td>
      <td>0.975</td>
      <td><strong><u>0.9927</u></strong></td>
      <td>0.947</td>
    </tr>
    <tr>
      <td>waveform</td>
      <td><strong><u>0.6012</u></strong></td>
      <td>0.592</td>
      <td>0.493</td>
      <td>0.774</td>
      <td>0.768</td>
      <td><strong><u>0.883</u></strong></td>
      <td>0.680</td>
      <td><strong><u>0.692</u></strong></td>
      <td>0.372</td>
      <td><strong><u>0.8323</u></strong></td>
      <td>0.815</td>
      <td>0.831</td>
    </tr>
    <tr>
      <td>wind</td>
      <td>0.763</td>
      <td><strong><u>0.7846</u></strong></td>
      <td>0.309</td>
      <td>0.881</td>
      <td><strong><u>0.8814</u></strong></td>
      <td>0.824</td>
      <td>0.712</td>
      <td><strong><u>0.8311</u></strong></td>
      <td>0.328</td>
      <td>0.870</td>
      <td><strong><u>0.9151</u></strong></td>
      <td>0.789</td>
    </tr>
    <tr>
      <td>speech</td>
      <td><strong><u>0.9965</u></strong></td>
      <td>0.994</td>
      <td>0.989</td>
      <td><strong><u>0.9993</u></strong></td>
      <td>0.999</td>
      <td>0.999</td>
      <td>0.996</td>
      <td>0.994</td>
      <td><strong><u>0.9995</u></strong></td>
      <td>0.999</td>
      <td>0.998</td>
      <td><strong><u>1.0</u></strong></td>
    </tr>
  </tbody>
</table>

### Table 4: Cube XGBoost Experiments Results

<table>
  <thead>
    <tr>
      <th rowspan="2"></th>
      <th colspan="6">Cube $L_2$ </th>
      <th colspan="6">Cube $L_\infty$ </th>
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
      <td>0.537</td>
      <td>0.212</td>
      <td><strong><u>0.7413</u></strong></td>
      <td>0.756</td>
      <td>0.591</td>
      <td><strong><u>0.8878</u></strong></td>
      <td>0.869</td>
      <td><strong><u>0.9257</u></strong></td>
      <td>0.303</td>
      <td>0.931</td>
      <td><strong><u>0.9665</u></strong></td>
      <td>0.575</td>
    </tr>
    <tr>
      <td>covtype</td>
      <td><strong><u>0.9823</u></strong></td>
      <td>0.020</td>
      <td>0.045</td>
      <td><strong><u>0.9998</u></strong></td>
      <td>0.649</td>
      <td>0.838</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.043</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.893</td>
    </tr>
    <tr>
      <td>cod-rna</td>
      <td><strong><u>0.7678</u></strong></td>
      <td>0.212</td>
      <td>0.183</td>
      <td><strong><u>0.985</u></strong></td>
      <td>0.800</td>
      <td>0.873</td>
      <td><strong><u>0.8643</u></strong></td>
      <td>0.732</td>
      <td>0.343</td>
      <td><strong><u>0.9841</u></strong></td>
      <td>0.944</td>
      <td>0.915</td>
    </tr>
    <tr>
      <td>diabetes</td>
      <td><strong><u>0.5437</u></strong></td>
      <td>0.458</td>
      <td>0.258</td>
      <td><strong><u>0.7935</u></strong></td>
      <td>0.717</td>
      <td>0.724</td>
      <td>0.567</td>
      <td><strong><u>0.6097</u></strong></td>
      <td>0.532</td>
      <td><strong><u>0.7316</u></strong></td>
      <td>0.667</td>
      <td>0.710</td>
    </tr>
    <tr>
      <td>Fashion-MNIST</td>
      <td><strong><u>0.9094</u></strong></td>
      <td>0.538</td>
      <td>0.098</td>
      <td><strong><u>0.9951</u></strong></td>
      <td>0.798</td>
      <td>0.850</td>
      <td><strong><u>0.8929</u></strong></td>
      <td>0.750</td>
      <td>0.014</td>
      <td><strong><u>0.9996</u></strong></td>
      <td>0.999</td>
      <td>0.903</td>
    </tr>
    <tr>
      <td>ijcnn1</td>
      <td><strong><u>0.773</u></strong></td>
      <td>0.310</td>
      <td>0.246</td>
      <td><strong><u>0.987</u></strong></td>
      <td>0.915</td>
      <td>0.905</td>
      <td>0.998</td>
      <td><strong><u>0.9998</u></strong></td>
      <td>0.216</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.912</td>
    </tr>
    <tr>
      <td>MNIST</td>
      <td><strong><u>0.7755</u></strong></td>
      <td>0.263</td>
      <td>0.202</td>
      <td><strong><u>0.9846</u></strong></td>
      <td>0.735</td>
      <td>0.926</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.028</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.917</td>
    </tr>
    <tr>
      <td>MNIST2-6</td>
      <td>0.968</td>
      <td><strong><u>0.9853</u></strong></td>
      <td>0.977</td>
      <td>0.990</td>
      <td>0.995</td>
      <td><strong><u>0.9979</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.987</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.999</td>
    </tr>
    <tr>
      <td>sensorless</td>
      <td><strong><u>0.8793</u></strong></td>
      <td>0.650</td>
      <td>0.595</td>
      <td>0.994</td>
      <td>0.916</td>
      <td><strong><u>0.9961</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.770</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.996</td>
    </tr>
    <tr>
      <td>webspam</td>
      <td><strong><u>0.9185</u></strong></td>
      <td>0.843</td>
      <td>0.297</td>
      <td><strong><u>0.9987</u></strong></td>
      <td>0.984</td>
      <td>0.990</td>
      <td><strong><u>0.9994</u></strong></td>
      <td><strong><u>0.9994</u></strong></td>
      <td>0.390</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.990</td>
    </tr>
    <tr>
      <td>electricity</td>
      <td><strong><u>0.7746</u></strong></td>
      <td>0.671</td>
      <td>0.312</td>
      <td><strong><u>0.9666</u></strong></td>
      <td>0.887</td>
      <td>0.904</td>
      <td><strong><u>0.9931</u></strong></td>
      <td>0.986</td>
      <td>0.652</td>
      <td><strong><u>0.9996</u></strong></td>
      <td>0.995</td>
      <td>0.969</td>
    </tr>
    <tr>
      <td>drybean</td>
      <td><strong><u>0.9954</u></strong></td>
      <td>0.987</td>
      <td>0.720</td>
      <td><strong><u>0.9996</u></strong></td>
      <td>0.999</td>
      <td>0.975</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.610</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.937</td>
    </tr>
    <tr>
      <td>adult</td>
      <td>0.944</td>
      <td><strong><u>0.9454</u></strong></td>
      <td>0.315</td>
      <td><strong><u>0.993</u></strong></td>
      <td>0.985</td>
      <td>0.941</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.551</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.998</td>
    </tr>
    <tr>
      <td>banknote</td>
      <td><strong><u>0.6201</u></strong></td>
      <td>0.538</td>
      <td>0.469</td>
      <td>0.971</td>
      <td>0.862</td>
      <td><strong><u>0.9893</u></strong></td>
      <td><strong><u>0.9973</u></strong></td>
      <td><strong><u>0.9973</u></strong></td>
      <td>0.364</td>
      <td><strong><u>0.9992</u></strong></td>
      <td><strong><u>0.9992</u></strong></td>
      <td>0.923</td>
    </tr>
    <tr>
      <td>gender-by-voice</td>
      <td>0.811</td>
      <td><strong><u>0.866</u></strong></td>
      <td>0.663</td>
      <td>0.915</td>
      <td>0.943</td>
      <td><strong><u>0.9439</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.117</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.671</td>
    </tr>
    <tr>
      <td>waveform</td>
      <td><strong><u>0.9614</u></strong></td>
      <td>0.959</td>
      <td>0.426</td>
      <td><strong><u>0.9754</u></strong></td>
      <td>0.969</td>
      <td>0.838</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.188</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.705</td>
    </tr>
    <tr>
      <td>wind</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.754</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.966</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.017</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.119</td>
    </tr>
    <tr>
      <td>speech</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
  </tbody>
</table>

### Table 5: Leaf-Tuple XGBoost Experiments Results


<table>
  <thead>
    <tr>
      <th rowspan="2"></th>
      <th colspan="6">Leaf-Tuple $L_2$ </th>
      <th colspan="6">Leaf-Tuple $L_\infty$ </th>
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
      <td><strong><u>0.9954</u></strong></td>
      <td>0.989</td>
      <td>0.921</td>
      <td><strong><u>0.9954</u></strong></td>
      <td>0.988</td>
      <td>0.915</td>
      <td>0.871</td>
      <td>0.835</td>
      <td><strong><u>0.9399</u></strong></td>
      <td>0.893</td>
      <td>0.854</td>
      <td><strong><u>0.9356</u></strong></td>
    </tr>
    <tr>
      <td>covtype</td>
      <td><strong><u>0.9962</u></strong></td>
      <td>0.723</td>
      <td>0.118</td>
      <td><strong><u>0.9995</u></strong></td>
      <td>0.934</td>
      <td>0.761</td>
      <td><strong><u>0.9969</u></strong></td>
      <td>0.783</td>
      <td>0.110</td>
      <td><strong><u>0.9999</u></strong></td>
      <td>0.950</td>
      <td>0.782</td>
    </tr>
    <tr>
      <td>cod-rna</td>
      <td>0.932</td>
      <td><strong><u>0.9477</u></strong></td>
      <td>0.540</td>
      <td>0.981</td>
      <td><strong><u>0.9822</u></strong></td>
      <td>0.861</td>
      <td>0.951</td>
      <td><strong><u>0.97</u></strong></td>
      <td>0.614</td>
      <td>0.986</td>
      <td><strong><u>0.9891</u></strong></td>
      <td>0.891</td>
    </tr>
    <tr>
      <td>diabetes</td>
      <td><strong><u>0.7227</u></strong></td>
      <td>0.653</td>
      <td>0.557</td>
      <td><strong><u>0.7826</u></strong></td>
      <td>0.688</td>
      <td>0.685</td>
      <td>0.561</td>
      <td><strong><u>0.5782</u></strong></td>
      <td>0.419</td>
      <td>0.643</td>
      <td><strong><u>0.6522</u></strong></td>
      <td>0.611</td>
    </tr>
    <tr>
      <td>Fashion-MNIST</td>
      <td><strong><u>0.9627</u></strong></td>
      <td>0.948</td>
      <td>0.367</td>
      <td><strong><u>0.9891</u></strong></td>
      <td>0.973</td>
      <td>0.759</td>
      <td><strong><u>0.9544</u></strong></td>
      <td>0.951</td>
      <td>0.393</td>
      <td><strong><u>0.9868</u></strong></td>
      <td>0.978</td>
      <td>0.786</td>
    </tr>
    <tr>
      <td>ijcnn1</td>
      <td>0.946</td>
      <td><strong><u>0.9584</u></strong></td>
      <td>0.668</td>
      <td>0.984</td>
      <td><strong><u>0.9867</u></strong></td>
      <td>0.906</td>
      <td>0.960</td>
      <td><strong><u>0.9711</u></strong></td>
      <td>0.744</td>
      <td>0.988</td>
      <td><strong><u>0.9899</u></strong></td>
      <td>0.935</td>
    </tr>
    <tr>
      <td>MNIST</td>
      <td>0.995</td>
      <td><strong><u>0.9953</u></strong></td>
      <td>0.410</td>
      <td><strong><u>0.9982</u></strong></td>
      <td>0.997</td>
      <td>0.773</td>
      <td><strong><u>0.9972</u></strong></td>
      <td>0.997</td>
      <td>0.435</td>
      <td><strong><u>0.9993</u></strong></td>
      <td>0.999</td>
      <td>0.800</td>
    </tr>
    <tr>
      <td>MNIST2-6</td>
      <td>0.999</td>
      <td><strong><u>0.9997</u></strong></td>
      <td>0.981</td>
      <td>0.999</td>
      <td><strong><u>0.9997</u></strong></td>
      <td>0.989</td>
      <td>0.999</td>
      <td><strong><u>0.9995</u></strong></td>
      <td>0.983</td>
      <td>0.999</td>
      <td><strong><u>0.9995</u></strong></td>
      <td>0.988</td>
    </tr>
    <tr>
      <td>Sensorless</td>
      <td><strong><u>0.9657</u></strong></td>
      <td>0.965</td>
      <td>0.889</td>
      <td><strong><u>0.9855</u></strong></td>
      <td>0.985</td>
      <td>0.969</td>
      <td><strong><u>0.9712</u></strong></td>
      <td>0.969</td>
      <td>0.891</td>
      <td><strong><u>0.9886</u></strong></td>
      <td>0.986</td>
      <td>0.956</td>
    </tr>
    <tr>
      <td>webspam</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.322</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.946</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.318</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.942</td>
    </tr>
    <tr>
      <td>electricity</td>
      <td>0.987</td>
      <td><strong><u>0.987</u></strong></td>
      <td>0.712</td>
      <td><strong><u>0.9955</u></strong></td>
      <td>0.995</td>
      <td>0.925</td>
      <td><strong><u>0.9935</u></strong></td>
      <td>0.992</td>
      <td>0.700</td>
      <td><strong><u>0.9976</u></strong></td>
      <td>0.997</td>
      <td>0.933</td>
    </tr>
    <tr>
      <td>drybean</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.836</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.963</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.807</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.952</td>
    </tr>
    <tr>
      <td>adult</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.982</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.999</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
    </tr>
    <tr>
      <td>banknote</td>
      <td>0.997</td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.728</td>
      <td>0.998</td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.920</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.756</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.953</td>
    </tr>
    <tr>
      <td>gender-by-voice</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.947</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.986</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.922</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.974</td>
    </tr>
    <tr>
      <td>waveform</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.164</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.757</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.172</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.776</td>
    </tr>
    <tr>
      <td>wind</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.995</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.999</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.834</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.999</td>
    </tr>
    <tr>
      <td>speech</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.976</td>
      <td><strong><u>1.0</u></strong></td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.995</td>
      <td><strong><u>1.0</u></strong></td>
      <td>0.9999</td>
      <td>0.992</td>
      <td><strong><u>0.9999</u></strong></td>
      <td><strong><u>0.9999</u></strong></td>
      <td>0.998</td>
    </tr>
  </tbody>
</table>

# RandomForest Full Experiments Results

In Tables 6,7,8,9 and 10 we can see the raw metrics of the experiments for each dataset, attack method, and norm for the RandomForest target experiments. In bold is the method or methods that achieved the highest value. Rows that fill in hyphens are cases where the adversarial sample creation process failed.

### Table 6: Sign-OPT RandomForest Experiments Results

|Dataset          | New    |  Original  | OC-score  |  New   | Original | OC-score  | New    |  Original  | OC-score |  New   | Original | OC-score |
|----|----|----|----|----|----|----|----|----|----|----|----|----|
breast-cancer    	 |	 0.992	 |	 0.983	 |	 **<u>0.9952</u>**	 |	 0.992	 |	 0.986	 |	 **<u>0.9962</u>**	 |	 0.965	 |	 **<u>0.997</u>**	 |	 0.997	 |	 0.961	 |	 0.997	 |	 **<u>0.9974</u>**|
covtype 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.097	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.859	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.080	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.731|
cod-rna |	 **<u>0.9572</u>**	 |	 0.918	 |	 0.248	 |	 **<u>0.9982</u>**	 |	 0.995	 |	 0.925	 |	 **<u>0.9266</u>**	 |	 0.749	 |	 0.178	 |	 **<u>0.996</u>**	 |	 0.979	 |	 0.898|
diabetes  	 |	 0.840	 |	 **<u>0.8485</u>**	 |	 0.593	 |	 **<u>0.8593</u>**	 |	 0.854	 |	 0.764	 |	 0.738	 |	 **<u>0.8493</u>**	 |	 0.669	 |	 0.815	 |	 **<u>0.8735</u>**	 |	 0.809|
Fashion-MNIST |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.147	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.919	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.223	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.943|
ijcnn1 |	**<u>1.0</u>**  |	 **<u>1.0</u>**	 |	 0.375	 |	 1.000	 |	 **<u>1.0</u>**	 |	 0.972	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.390	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.958|
MNIST |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.238	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.929	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.553	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.967|
MNIST2-6 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.869	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.990	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.872	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.990|
sensorless  	 |	 **<u>0.8165</u>**	 |	 0.735	 |	 0.637	 |	 **<u>0.9842</u>**	 |	 0.942	 |	 0.981	 |	 **<u>0.973</u>**	 |	 0.968	 |	 0.641	 |	 **<u>0.9982</u>**	 |	 0.994	 |	 0.975|
webspam	 |	 **<u>1.0</u>**	 |	**<u>1.0</u>**	 |	 0.161	 |	 **<u>1.0</u>**	 |	**<u>1.0</u>**	 |	 0.981	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.138	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.979|
electricity 	 |	 0.939	 |	 **<u>0.9644</u>**	 |	 0.295	 |	 0.995	 |	 **<u>0.9975</u>**	 |	 0.892	 |	 0.968	 |	 **<u>0.9696</u>**	 |	 0.406	 |	 **<u>0.9981</u>**	 |	 0.993	 |	 0.917|
drybean 	 |	 **<u>0.9808</u>**	 |	 0.914	 |	 0.810	 |	 **<u>0.9897</u>**	 |	 0.946	 |	 0.987	 |	 **<u>0.9739</u>**	 |	 0.948	 |	 0.866	 |	 **<u>0.9945</u>**	 |	 0.977	 |	 0.991|
adult   	 |	 **<u>1.0</u>**	 |	 0.9998	 |	 0.227	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.863	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.300	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.910|
banknote |	 0.886	 |	 **<u>0.9614</u>**	 |	 0.875	 |	 0.941	 |	 0.969	 |	 **<u>0.9809</u>**	 |	 **<u>0.9847</u>**	 |	 0.982	 |	 0.920	 |	 **<u>0.9888</u>**	 |	 0.985	 |	 0.981|
gender-by-voice  	 |	 0.969	 |	 **<u>0.9988</u>**	 |	 0.751	 |	 0.986	 |	 **<u>0.9992</u>**	 |	 0.946	 |	 **<u>0.9957</u>**	 |	 0.989	 |	 0.942	 |	 **<u>0.9976</u>**	 |	 0.995	 |	 0.989|
waveform  	 |	 **<u>0.8227</u>**	 |	 0.756	 |	 0.447	 |	 **<u>0.9182</u>**	 |	 0.868	 |	 0.897	 |	 0.787	 |	 **<u>0.9148</u>**	 |	 0.516	 |	 0.914	 |	 **<u>0.9552</u>**	 |	 0.918|
wind 	 |	 0.784	 |	 **<u>0.9087</u>**	 |	 0.309	 |	 0.943	 |	 **<u>0.9661</u>**	 |	 0.897	 |	 0.745	 |	 **<u>0.8765</u>**	 |	 0.379	 |	 0.934	 |	 **<u>0.9551</u>**	 |	 0.894|
speech |  -	 |	- |  -	 |	-	| -	 |	-	| 	- 	| 	-	 |	-	| 	-	 |	-	| 	-	|

### Table 7: OPT RandomForest Experiments Results

|Dataset          | New    |  Original  | OC-score  |  New   | Original | OC-score  | New    |  Original  | OC-score |  New   | Original | OC-score |
|----|----|----|----|----|----|----|----|----|----|----|----|----|
breast-cancer    	 |	 0.975	 |	 **<u>0.9926</u>**	 |	 0.947	 |	 0.982	 |	 **<u>0.9935</u>**	 |	 0.973	 |	 0.980	 |	 **<u>0.9932</u>**	 |	 0.834	 |	 0.978	 |	 **<u>0.9937</u>**	 |	 0.909|
covtype 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.127	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.868	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.114	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.807|
cod-rna 	 |	 **<u>0.9316</u>**	 |	 0.927	 |	 0.163	 |	 **<u>0.9977</u>**	 |	 0.994	 |	 0.878	 |	 **<u>0.9069</u>**	 |	 0.747	 |	 0.148	 |	 **<u>0.9948</u>**	 |	 0.973	 |	 0.915|
diabetes 	 |	 0.747	 |	 **<u>0.7514</u>**	 |	 0.509	 |	 0.784	 |	 **<u>0.8161</u>**	 |	 0.719	 |	 **<u>0.8889</u>**	 |	 0.842	 |	 0.545	 |	 **<u>0.913</u>**	 |	 0.878	 |	 0.701|
Fashion-MNIST 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.236	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.938	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.220	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.932|
ijcnn1 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.366	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.947	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.379	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.945|
MNIST 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.555	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.971	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.484	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.961|
MNIST2-6 	 |	 **<u>1.0</u>**	 |	 **<u>0.9997</u>**	 |	 0.859	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.989	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.800	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.977|
Sensorless 	 |	 **<u>0.9705</u>**	 |	 0.911	 |	 0.704	 |	 **<u>0.9978</u>**	 |	 0.967	 |	 0.977	 |	 **<u>0.9772</u>**	 |	 0.938	 |	 0.694	 |	 **<u>0.9984</u>**	 |	 0.973	 |	 0.967|
webspam 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.187	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.984	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.217	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.985|
electricity |	 0.936	 |	 **<u>0.9646</u>**	 |	 0.429	 |	 0.991	 |	 **<u>0.9964</u>**	 |	 0.956	 |	 0.975	 |	 **<u>0.992</u>**	 |	 0.529	 |	 0.997	 |	 **<u>0.9995</u>**	 |	 0.976|
drybean 	 |	 **<u>0.983</u>**	 |	 0.917	 |	 0.902	 |	 **<u>0.996</u>**	 |	 0.958	 |	 0.993	 |	 **<u>0.9779</u>**	 |	 0.951	 |	 0.806	 |	 **<u>0.9937</u>**	 |	 0.971	 |	 0.984|
adult 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.398	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.918	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.278	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.864|
banknote  		 |	 0.954	 |	 **<u>0.9975</u>**	 |	 0.908	 |	 0.968	 |	 **<u>0.9982</u>**	 |	 0.982	 |	 0.942	 |	 **<u>0.9504</u>**	 |	 0.815	 |	 0.949	 |	 0.964	 |	 **<u>0.9672</u>**|
gender-by-voice 	 |	 0.973	 |	 **<u>0.995</u>**	 |	 0.812	 |	 0.984	 |	 **<u>0.9968</u>**	 |	 0.968	 |	 0.985	 |	 **<u>0.9947</u>**	 |	 0.950	 |	 0.991	 |	 **<u>0.9967</u>**	 |	 0.991|
waveform  	 |	 **<u>0.8013</u>**	 |	 0.799	 |	 0.447	 |	 0.899	 |	 0.893	 |	 **<u>0.9103</u>**	 |	 0.659	 |	 **<u>0.6708</u>**	 |	 0.481	 |	 0.826	 |	 0.824	 |	 **<u>0.8952</u>**|
wind 	 |	 0.752	 |	 **<u>0.8612</u>**	 |	 0.236	 |	 0.922	 |	 **<u>0.9273</u>**	 |	 0.810	 |	 0.740	 |	 **<u>0.8563</u>**	 |	 0.354	 |	 0.923	 |	 **<u>0.9465</u>**	 |	 0.870|
speech |  -	 |	- |  -	 |	-	| -	 |	-	| 	- 	| 	-	 |	-	| 	-	 |	-	| 	-	|



### Table 8: HSJA RandomForest Experiments Results

|Dataset          | New    |  Original  | OC-score  |  New   | Original | OC-score  | New    |  Original  | OC-score |  New   | Original | OC-score |
|----|----|----|----|----|----|----|----|----|----|----|----|----|
breast-cancer 	 |	 **<u>0.986</u>**	 |	 0.983	 |	 0.962	 |	 **<u>0.9875</u>**	 |	 0.986	 |	 0.984	 |	 0.980	 |	 **<u>0.9974</u>**	 |	 0.774	 |	 0.986	 |	 **<u>0.9982</u>**	 |	 0.936|
covtype 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.230	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.835	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.245	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.853|
cod-rna 	|  -	 |	- |  - |	-	| -	 |	-	| 	- 	| 	-	 |	-	| 	-	 |	-	| 	- |
diabetes    |  -	 |	- |  - |	-	| -	 |	-	| 	- 	| 	-	 |	-	| 	-	 |	-	| 	- |
Fashion-MNIST 	 |	 **<u>0.9999</u>**	 |	 **<u>0.9999</u>**	 |	 0.248	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.943	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.240	 |	 **<u>1.0</u>**	 |	**<u>1.0</u>**	 |	 0.943|
ijcnn1 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.224	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.902	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.237	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.887|
MNIST 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.321	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.931	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.385	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.953|
MNIST2-6 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.775	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.985	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.700	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.975|
sensorless 	 |	 **<u>0.9235</u>**	 |	 0.777	 |	 0.550	 |	 **<u>0.9934</u>**	 |	 0.931	 |	 0.948	 |	 **<u>0.8885</u>**	 |	 0.737	 |	 0.430	 |	 **<u>0.9913</u>**	 |	 0.919	 |	 0.951|
webspam 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.094	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.959	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.041	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.900|
electricity 	 |	 **<u>0.9381</u>**	 |	 0.931	 |	 0.297	 |	 **<u>0.9935</u>**	 |	 0.991	 |	 0.920	 |	 0.947	 |	 **<u>0.9544</u>**	 |	 0.290	 |	 **<u>0.9973</u>**	 |	 0.989	 |	 0.882|
drybean 	 |	 **<u>0.9676</u>**	 |	 0.948	 |	 0.874	 |	 **<u>0.991</u>**	 |	 0.978	 |	 0.989	 |	 **<u>0.9847</u>**	 |	 0.984	 |	 0.828	 |	 **<u>0.9974</u>**	 |	 0.997	 |	 0.985|
adult 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.538	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.931	 |	**<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.480	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.877|
banknote 	 |	 **<u>0.9632</u>**	 |	 0.874	 |	 0.747	 |	 **<u>0.9642</u>**	 |	 0.916	 |	 0.909	 |	 0.943	 |	 **<u>0.9496</u>**	 |	 0.774	 |	 **<u>0.9579</u>**	 |	 0.955	 |	 0.921|
gender-by-voice 	 |	 0.955	 |	 **<u>0.985</u>**	 |	 0.724	 |	 0.973	 |	 **<u>0.9882</u>**	 |	 0.944	 |	 0.960	 |	 **<u>0.9684</u>**	 |	 0.726	 |	 0.975	 |	 **<u>0.9765</u>**	 |	 0.930|
waveform 	 |	 **<u>0.736</u>**	 |	 0.704	 |	 0.308	 |	 **<u>0.8824</u>**	 |	 0.836	 |	 0.848	 |	 **<u>0.7729</u>**	 |	 0.636	 |	 0.397	 |	 **<u>0.8893</u>**	 |	 0.821	 |	 0.849|
wind 	 |	 **<u>0.8744</u>**	 |	 0.860	 |	 0.425	 |	 **<u>0.9495</u>**	 |	 0.916	 |	 0.852	 |	 0.843	 |	 **<u>0.8597</u>**	 |	 0.311	 |	 **<u>0.9519</u>**	 |	 0.941	 |	 0.858|
speech   |  -	 |	- |  - |	-	| -	 |	-	| 	- 	| 	-	 |	-	| 	-	 |	-	| 	-|

### Table 9: Cube RandomForest Experiments Results

|Dataset          | New    |  Original  | OC-score  |  New   | Original | OC-score  | New    |  Original  | OC-score |  New   | Original | OC-score |
|----|----|----|----|----|----|----|----|----|----|----|----|----|
breast-cancer 	 |	 0.435	 |	 0.139	 |	 **<u>0.6983</u>**	 |	 0.738	 |	 0.283	 |	 **<u>0.9391</u>**	 |	 **<u>1.0</u>**	 |	 0.932	 |	 0.173	 |	 **<u>1.0</u>**	 |	 0.979	 |	 0.695|
covtype   		 |	 **<u>0.7853</u>**	 |	 0.123	 |	 0.106	 |	 **<u>0.9911</u>**	 |	 0.710	 |	 0.752	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.070	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.831|
cod-rna 	 |	 **<u>0.7844</u>**	 |	 0.299	 |	 0.111	 |	 **<u>0.9871</u>**	 |	 0.876	 |	 0.815	 |	 **<u>0.9158</u>**	 |	 0.833	 |	 0.164	 |	 **<u>0.9955</u>**	 |	 0.974	 |	 0.872|
diabetes 	 |	 **<u>0.6343</u>**	 |	 0.248	 |	 0.307	 |	 **<u>0.9185</u>**	 |	 0.620	 |	 0.750	 |	 0.384	 |	 **<u>0.4718</u>**	 |	 0.307	 |	 0.562	 |	 **<u>0.6139</u>**	 |	 0.597|
Fashion-MNIST |	 **<u>0.864</u>**	 |	 0.687	 |	 0.149	 |	 **<u>0.9939</u>**	 |	 0.898	 |	 0.912	 |	 **<u>0.9947</u>**	 |	 0.991	 |	 0.374	 |	 0.9999	 |	 **<u>1.0</u>**	 |	 0.954|
ijcnn1 	 |	 **<u>0.8503</u>**	 |	 0.612	 |	 0.280	 |	 **<u>0.9949</u>**	 |	 0.967	 |	 0.883	 |	 0.984	 |	 **<u>1.0</u>**	 |	 0.120	 |	**<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.870|
MNIST 	 |	 **<u>0.9337</u>**	 |	 0.894	 |	 0.335	 |	 **<u>0.9978</u>**	 |	 0.972	 |	 0.957	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.852	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.994|
MNIST2-6   |	 **<u>0.9399</u>**	 |	 0.933	 |	 0.858	 |	 0.990	 |	 0.971	 |	 **<u>0.9914</u>**	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.910	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.991|
sensorless 	 |	 **<u>0.9066</u>**	 |	 0.666	 |	 0.425	 |	 **<u>0.9924</u>**	 |	 0.882	 |	 0.947	 |	 **<u>0.9945</u>**	 |	 0.988	 |	 0.767	 |	 0.9998	 |	 **<u>1.0</u>**	 |	 0.984|
webspam 	 |	 **<u>0.9345</u>**	 |	 0.735	 |	 0.311	 |	 **<u>0.9984</u>**	 |	 0.952	 |	 0.979	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.127	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.913|
electricity 	 |	 **<u>0.9726</u>**	 |	 0.914	 |	 0.445	 |	 **<u>0.9978</u>**	 |	 0.975	 |	 0.852	 |	 **<u>0.9988</u>**	 |	 0.998	 |	 0.095	 |	 0.9999	 |	**<u>1.0</u>**	 |	 0.877|
drybean |	 0.938	 |	 **<u>0.964</u>**	 |	 0.797	 |	 **<u>0.9862</u>**	 |	 0.980	 |	 0.964	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.838	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.990|
adult 	 |	 **<u>0.9977</u>**	 |	 0.995	 |	 0.151	 |	 0.9999	 |	 **<u>1.0</u>**	 |	 0.791	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.010	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.472|
banknote |	 **<u>0.9316</u>**	 |	 0.865	 |	 0.504	 |	 **<u>0.9853</u>**	 |	 0.964	 |	 0.957	 |	 0.944	 |	 **<u>1.0</u>**	 |	 0.176	 |	 0.996	 |	 **<u>1.0</u>**	 |	 0.927|
gender-by-voice 	 |	 **<u>0.8822</u>**	 |	 0.839	 |	 0.481	 |	 **<u>0.9799</u>**	 |	 0.965	 |	 0.941	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.347	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.869|
waveform |	 0.954	 |	 **<u>0.9535</u>**	 |	 0.226	 |	 **<u>0.9739</u>**	 |	 0.973	 |	 0.799	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.083	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.542|
wind |  -	 |	- |  -	 |	-	| -	 |	-	| 	- 	| 	-	 |	-	| 	-	 |	-	| 	-|
speech |  -	 |	- |  -	 |	-	| -	 |	-	| 	- 	| 	-	 |	-	| 	-	 |	-	| 	-|

### Table 10: Leaf-Tuple RandomForest Experiments Results

|Dataset          | New    |  Original  | OC-score  |  New   | Original | OC-score  | New    |  Original  | OC-score |  New   | Original | OC-score |
|----|----|----|----|----|----|----|----|----|----|----|----|----|
breast-cancer 	 |	 0.971	 |	 **<u>0.9964</u>**	 |	 0.939	 |	 0.972	 |	 **<u>0.9964</u>**	 |	 0.947	 |	 0.995	 |	 **<u>0.9964</u>**	 |	 0.872	 |	 0.995	 |	 **<u>0.9965</u>**	 |	 0.922|
covtype      |  -	 |	- |  - |	-	| -	 |	-	| 	- 	| 	-	 |	-	| 	-	 |	-	| 	-|
cod-rna 		 |	 0.988	 |	 **<u>0.9895</u>**	 |	 0.581	 |	 **<u>0.997</u>**	 |	 0.997	 |	 0.891	 |	 0.993	 |	 **<u>0.9953</u>**	 |	 0.693	 |	 0.998	 |	 **<u>0.9987</u>**	 |	 0.940|
diabetes      |  -	 |	- |  - |	-	| -	 |	-	| 	- 	| 	-	 |	-	| 	-	 |	-	| 	-|
Fashion-MNIST 	 |	 **<u>0.8023</u>**	 |	 0.578	 |	 0.033	 |	 **<u>0.9918</u>**	 |	 0.878	 |	 0.688	 |	 **<u>0.8884</u>**	 |	 0.693	 |	 0.021	 |	 **<u>0.9916</u>**	 |	 0.849	 |	 0.602|
ijcnn1  			 |	 **<u>0.9939</u>**	 |	 0.994	 |	 0.912	 |	 **<u>0.9983</u>**	 |	 0.998	 |	 0.982	 |	 0.990	 |	 **<u>0.9929</u>**	 |	 0.931	 |	 0.997	 |	 **<u>0.998</u>**	 |	 0.988|
MNIST 	 |	 **<u>0.7772</u>**	 |	 0.423	 |	 0.023	 |	 **<u>0.986</u>**	 |	 0.885	 |	 0.625	 |	 **<u>0.8996</u>**	 |	 0.840	 |	 0.108	 |	 **<u>0.9883</u>**	 |	 0.934	 |	 0.860|
MNIST2-6 	 |	 0.996	 |	 **<u>0.999</u>**	 |	 0.962	 |	 0.996	 |	 **<u>0.999</u>**	 |	 0.973	 |	 0.998	 |	 **<u>0.9989</u>**	 |	 0.976	 |	 0.998	 |	 **<u>0.9989</u>**	 |	 0.987|
Sensorless 	 |	 **<u>0.6531</u>**	 |	 0.171	 |	 0.030	 |	 **<u>0.9801</u>**	 |	 0.709	 |	 0.772	 |	 **<u>0.9427</u>**	 |	 0.799	 |	 0.042	 |	 **<u>0.9938</u>**	 |	 0.931	 |	 0.677|
webspam 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.731	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.978	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.602	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.978|
electricity 	 |	 0.999	 |	 **<u>0.9997</u>**	 |	 0.822	 |	 **<u>1.0</u>**	 |	 0.9999	 |	 0.976	 |	 0.996	 |	 **<u>0.999</u>**	 |	 0.828	 |	 0.999	 |	 **<u>0.9997</u>**	 |	 0.947|
drybean 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.503	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.946	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.636	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.946|
adult 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.469	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.991	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.812	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.995|
banknote  	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.805	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.977	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.544	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.893|
gender-by-voice 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.892	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.981	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.867	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.968|
waveform 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.298	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.869	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.347	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.922|
wind 	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.366	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.950	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.451	 |	 **<u>1.0</u>**	 |	 **<u>1.0</u>**	 |	 0.986|
speech  |  -	 |	- |  - |	-	| -	 |	-	| 	- 	| 	-	 |	-	| 	-	 |	-	| 	-|
