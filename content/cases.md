---
title: Cases Overview
menus:
 - main
tables:
  cases:
    cols:
      - id: benchmark
        name: "Benchmark"
        tip: "the Name and link to the benchmark"
      - id: year
        name: Year
        tip: "The year in which the benchmark was originally published"
      - id: domain
        name: Domain
        tip: 'The domain of the benchmark'
      - id: topics
        name: Topic
        tip: "The technical discipline executed by the benchmark"
      - id: evaluation
        name: "Evaluation Criteria"
        tip: "The evaluation criteria"
    rows:
      - benchmark: '[FIXML to Java, C# and C++](2014/solutions_fixml.html)'
        year: '2014'
        domain: finance
        topics:
          - transformation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
      - benchmark: '[Train Benchmark](2015/solutions_train.html)'
        year: '2015'
        domain: railway
        topics:
          - incremental change propagation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - initial runtime
          - change propagation time
          - scalability
      - benchmark: '[Class Responsibility Assignment](2016/solutions_cra.html)'
        year: '2016'
        domain: software engineering
        topics:
          - search-based optimization
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - quality of results
          - runtime
      - benchmark: '[Dataflow](2016/livecontest.html)'
        year: '2016'
        domain: software engineering
        topics:
          - transformation
          - incremental change propagation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - initial runtime
          - change propagation time
          - scalability
      - benchmark: '[Smart Grids](2017/solutions_smartGrid.html)'
        year: '2017'
        domain: smart grids
        topics:
          - transformation
          - incremental change propagation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - initial runtime
          - change propagation time
          - scalability
      - benchmark: '[Families to Persons](2017/solutions_familiesToPersons.html)'
        year: '2017'
        domain: example
        topics:
          - bidirectional transformation
          - incremental change propagation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - initial runtime
          - change propagation time
          - scalability
      - benchmark: '[State Elimination](2017/solutions_stateElimination.html)'
        year: '2017'
        domain: software engineering
        topics:
          - destructive transformation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - runtime
          - scalability
      - benchmark: '[Transformation Reuse](2017/solutions_livecontest.html)'
        year: '2017'
        domain: software engineering
        topics:
          - reuse
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - runtime
          - reuse
      - benchmark: '[Quality-based Software Selection and Hardware-Mapping](2018/solutions_qualityBased.html)'
        year: '2018'
        domain: systems engineering
        topics:
          - search-based optimization
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - runtime
          - quality of results
          - scalability
      - benchmark: '[Social Media](2018/solutions_liveContest.html)'
        year: '2018'
        domain: social media
        topics:
          - incremental change propagation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - initial runtime
          - change propagation time
      - benchmark: '[Truth tables to BDD](2019/solutions_tt2bdd.html)'
        year: '2019'
        domain: example
        topics:
          - open to any research direction
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
      - benchmark: '[BibtexXML to Docbook](2019/solutions_liveContest.html)'
        year: '2019'
        domain: example
        topics:
          - bidirectional transformation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
      - benchmark: '[Roundtrip](2020/solutions_roundtrip.html)'
        year: '2020'
        domain: versioning
        topics:
          - bidirectional transformation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - reuse
      - benchmark: '[Incremental Workflows](2021/solutions_iworkflows.html)'
        year: '2021'
        domain: lab automation
        topics:
          - incremental change propagation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - initial runtime
          - change propagation time
          - scalability
      - benchmark: '[OCL2PSQL](2021/solutions_ocl2psql.html)'
        year: '2021'
        domain: database queries
        topics:
          - transformation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - runtime
          - quality of results
      - benchmark: '[Containers to MiniYAML](2023/solutions_containers.html)'
        year: '2023'
        domain: deployment
        topics:
          - bidirectional transformation
          - incremental change propagation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - scalability
          - initial runtime
          - change propagation time
      - benchmark: '[KMEHR to FHIR](2023/solutions_kmehr.html)'
        year: '2023'
        domain: healthcare
        topics:
          - bidirectional transformation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - runtime
          - scalability
      - benchmark: '[Incremental Class into Relational](2023/solutions_class2rel.html)'
        year: '2023'
        domain: example
        topics:
          - incremental change propagation
        evaluation:
          - understandability
          - maintainability
          - correctness
          - conciseness
          - initial runtime
          - change propagation time

---

Over the past years, many authors have contributed case studies for the
TTC, creating a set of community-established benchmarks for model
transformation tools. The following table provides an overview.

{{< table "cases" >}}
