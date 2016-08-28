
# [JIOWA Test Data Generation Tool](http://www.jiowa.de/download.html)

A simple test data generation tool to create tons of realistic personalized data items for test environments.
The test data generation tool can produce trillions of data items for realistic performance testing.

Other approaches often rely on numerated test names ("Thomas001 Muller058", ... "Thomas789 Muller910", ...) or even automatically generated cryptic names like "asdfljsdf kklhhjj", ... , "uzqwzurk iouwerhh". While this kind of test data is sufficient to test the base functionality of a system, this does not apply at all for testing the performance of realistic search queries, like finding all data items for a specific name. In particular, performance tests for phonetic search with cryptic names are obviously impossible if you want to find all similar sounding but differently written names. This is especially unfavorable, because a large amount of performance in software systems is spent on search queries. Thus, extensive performance testing for this use case is crucial.

This tool is able to create millions of different realistic names to address this problem.

Some statistics:

Around 100 million international different female & male name combinations.
Trillions of different name and city/street combinations.
Many cities from all US states and all German states (Bundesländer) in test data.
Countless name & address combinations for US and German addresses.
The software is written in Java and can be imported into any IDE as simple Maven project. In order to support various kinds of data formats, it is pre-configured to make use of the template engine of the JIOWA Code Generation Framework. Using simple code templates it is very easy to automatically generate project specific code enriched with random test data (classes, SQL scripts, configuration files, unit and integration tests, ...). 
