改了下三个代理的模板，
{
    "Precision": 0.75,
    "Recall": 0.75,
    "Accuracy": 0.7,
    "F1": 0.75,
    "Micro-F1": 0.7,
    "Macro-F1": 0.6875,
    "Weighted-F1": 0.7
}
没有用这个            if '0' in result or '[0]' in result:
                pred = 0
            else:
                pred = 1
