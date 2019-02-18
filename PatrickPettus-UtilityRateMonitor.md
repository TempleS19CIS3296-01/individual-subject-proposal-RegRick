# Project Description

Utility rates can fluctuate wildly throughtout a given day. During peak hours (dusk/evening), rates can be more than 25% higher than the daily average. By simply reducing consumption during peak hours, consumers can save substantial amounts on power bills. The Utility Rate Monitor application will provide a simple interface with which users can compare their power consumption to their utility's rate in (near)real time, analyze how other company's rates may affect their power-bill, and review statistics of historic power consumption. The application's primary goal is provide as much information to the consumer as possible to enable an informed decision regarding power consumption.

Rate/Consumption "comparisons" will be a simple multi-line plot, where the utility rate is superimposed over power consumption. Other lines for differing rates can be included for cross-utility comparisons. Historic data will be retained and used to provide running statistics on power consumption and rate behavior. This data will be exportable as either .pdf or .xls.

Ultimately, the app will agregate data across multiple utilities (gas, electric, etc.), and will present/export statistics generated from all data sources.

# Adherence to Course Objectives

Because this application will need to be highly modular to accomodate different utility providers, the architecture will have a highly object-oriented focus. Furthermore, if the application is to provide (near) real-time rates, multiple threads will be needed. As progression towards the projects objectives lends itself well to iterative development, a TDD approach will be taken to ensure that all requirements are met.
