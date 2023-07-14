### Gold recovery prediction ###

It was a final training project of the second module from Yandex Practicum Data Science course. It's a regression task. The performance of gold recovery on two stages of production should be predicted

This project is from pre- gradient boosting part of the course, so only simple classic models from Scikit-learn are used. I try a series of them and end up with voting regressor

As for evaluation metric we were given a sMAPE formula with weighted scores for the two recovery stages (25% for rougher and 75% for final)