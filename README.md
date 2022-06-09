<samp>

# sentiment-analysis-dataset [Swahili]

Swahili sentiment analysis dataset is the dataset training binary (positive or negative) sentiment analysis model.

This data you see in ```swahili.csv`` is but results of cleaning of data found on an opensource repository titled [**Swahili-sentiment-analysis**](https://github.com/Jinamizi/Swahili-sentiment-analysis) by [jinamizi](https://github.com/Jinamizi/).

## Here a preview of the data

```python
>>> import pandas as pd
>>> dataset = pd.read_csv('swahili.csv', usecols=['text', 'labels'])
>>> dataset.head()
                                 text    labels
0  team 2019merimera alikuwa takataka  negative
1                      sijafurahishwa  negative
2                       kubuni dosari  negative
3   bila kusema nilipoteza pesa zangu  negative
4        sema kupoteza pesa na wakati  negative
>>>
```

This is data that has been used to [Swahili-Sentiment-Analysis](https://huggingface.co/spaces/neurotech/Swahili-sentiment-analysis) model.

## Issues

In case you're facing any difficulty when trying to use the data, please raise an issue so as we can assist you.

## Contributions

Please Feel free to contribute to this repository, whether its code, docs or data processing pipeline.

## Give it star

Did you find this repository useful, please give it a star so as more people can know about it

## Credits

All the credits  to

1. [Jinamizi](https://github.com/Jinamizi/)
2. [Kalebu](https://github.com/kalebu/)

</samp>
