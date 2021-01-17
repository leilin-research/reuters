# Multi-label Multi-class Classification based on Reuters-21578

- We take the ApteMod subset of the Reuters-21578 corpus

- For feature engineering, TF-IDF and Word2Vec are implemented

- For classificiation model, Linear SVC, Feedforward Neural Network and Bi-LSTM are applied

- The classification accuracy, Macro F1 and Weighted F1 are shown below:


<table>
    <thead>
        <tr>
            <th>Feature Extraction</th>
            <th>Model</th>
            <th>Accuracy</th>
            <th>Macro F1</th>
            <th>Weighted F1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=2>TF-IDF</td>
            <td >SVC</td>
            <td>0.81</td>
            <td>0.47</td>
            <td>0.84</td>
        </tr>
        <tr>
            <td >Feedforward</td>
            <td>0.78</td>
            <td>0.46</td>
            <td>0.83</td>
        </tr>
        <tr>
            <td rowspan=3>Word2Vec (Pre-trained)</td>
            <td >SVC</td>
            <td>0.73</td>
            <td>0.29</td>
            <td>0.75</td>
        </tr>
        <tr>
            <td >Feedforward</td>
            <td>0.76</td>
            <td>0.43</td>
            <td>0.80</td>
        </tr>
        <tr>
            <td >Bi-LSTM</td>
            <td>0.80</td>
            <td>0.39</td>
            <td>0.82</td>
        </tr>
        <tr>
            <td rowspan=3>Word2Vec (Re-trained)</td>
            <td >SVC</td>
            <td>0.79</td>
            <td>0.40</td>
            <td>0.81</td>
        </tr>
        <tr>
            <td >Feedforward</td>
            <td>0.80</td>
            <td>0.45</td>
            <td>0.83</td>
        </tr>
        <tr>
            <td >Bi-LSTM</td>
            <td><th>0.81</th></td>
            <td><th>0.50</th></td>
            <td><th>0.84</th></td>
        </tr>
    </tbody>
</table>

