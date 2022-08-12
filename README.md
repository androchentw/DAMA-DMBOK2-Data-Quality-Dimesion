# DAMA-DMBOK2-Data-Quality-Dimesion
DAMA-DMBOK2-Data-Quality-Dimesion is a quick reference and implementation of the DAMA Guide to the Data Management Body of Knowledge, focued on the dimension of data quality.


# Data Quality Dimesions

## A. [DMBoK2] Table 29, page 462 ~ 464.

1. Accuracy
2. Completeness
3. Consistency
4. Integrity
5. Reasonability
6. Timeliness
7. Uniqueness
8. Validity

## B. [CloverDX] 6 Data Quality Metrics

1. Completeness
    * This measures whether all the necessary data is present in a specific dataset. You can think about completeness in one of two ways: at the record level or at the attribute level. Measuring completeness at the attribute level is a little more complex however, as not all fields will be mandatory.
    * An example metric for completeness is the percent of data fields that have values entered into them.

2. Accuracy
    * How accurately does your data reflect the real-world object? 
    * An example metric for accuracy is finding the percentage of values that are correct compared to the actual value.

3. Consistency
    * Maintaining synchronicity between different databases is essential. To ensure data remains consistent on a daily basis, software systems are often the answer.
    * For example, transaction consistency helps you detect incomplete financial transactions. Once found, you can roll back those errors meaning both balances remain in check.

4. Validity
    * Validity is a measure of how well data conforms to required value attributes
    * For example, ensuring dates conform to the same format, i.e., date/month/year or month/date/year.

5. Timeliness
    * Timeliness reflects the accuracy of data at a specific point in time. 
    * An example of this is when a customer moves to a new house, how timely are they in informing their bank of their new address?

6. Integrity
    * To ensure data integrity, it’s important to maintain all the data quality metrics we’ve mentioned above as your data moves between different systems. Typically, data stored in multiple systems breaks data integrity.
    * An example metric for integrity is the percent of data that is the same across multiple systems.


# Ref
* [DAMA DMBoK2 - Body of Knowledge (edition 2)](https://www.dama.org/cpages/body-of-knowledge)
* [6 Data Quality Metrics You Can't Afford To Ignore](https://www.cloverdx.com/blog/6-data-quality-metrics-you-cant-ignore)
* [深度解读数据管理葵花宝典-《DAMA-DMBOK2数据管理知识体系指南（第2版）》](https://blog.csdn.net/fuyipingwml1976124/article/details/106233428)


<!-- Links -->
[DMBoK2]: https://www.dama.org/cpages/body-of-knowledge
[CloverDX]: https://www.cloverdx.com/blog/6-data-quality-metrics-you-cant-ignore
