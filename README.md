改了下三个代理的模板，
{
    "Precision": 0.7377049180327869,
    "Recall": 0.75,
    "Accuracy": 0.69,
    "F1": 0.743801652892562,
    "Micro-F1": 0.69,
    "Macro-F1": 0.6756982948007113,
    "Weighted-F1": 0.6893189664190814
}
没有用这个            if '0' in result or '[0]' in result:
                pred = 0
            else:
                pred = 1
