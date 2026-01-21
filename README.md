# Msc-Data-Science-Disseration
Forecasting Household Energy Demand Using Machine Learning and Deep Learning Models


Forecasting household electricity demand has become an indispensable part of modern energy
management due to the electrification of everything, the behavioural complexity, and the
integration of intermittent renewable energy sources. Linear statistical models cannot
effectively capture nonlinear and irregular consumption patterns of residential datasets; hence,
more complex computational models are in demand. This thesis develops and evaluates a
comprehensive electricity demand forecasting framework by considering several state-of-the-
art machines learning models, including linear regression, k-nearest neighbours, Support
Vector Regression, Random Forests, XGBoost, and LightGBM, as well as deep learning
architectures based on Gated Recurrent Units and a Seq2Seq encoder-decoder model. Based
on a multi-year hourly dataset comprising 103,776 observations of electricity demand and
temperature, extensive exploratory data analysis showed evident daily, weekly, and seasonal
cycles, strong autocorrelation structures, and nonlinear temperature-load relationships.
The different machine learning models showed a quite reasonable performance, although tree-
based ensembles significantly outperformed kernel-based and linear models. The deep learning
architectures, however, reached the highest predictive accuracy because their ability to
internalize sequential patterns without heavy feature engineering was the best. The single-step
forecasting was best performed by the GRU model among all ML methods. Although Seq2Seq
showed very strong performance, some limitations were revealed during those rare behavioural
anomalies, pointing to potential future attention-enhanced architectures. The results prove
advanced deep learning techniques better suited for modelling the increasingly complex
temporal dynamics of household energy consumption and highlight their potential for real-time
smart-grid optimization, demand response, and sustainability-driven energy planning.
