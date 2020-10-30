# CNF Conformance
The CNF Conformance program enables interoperability of Cloud native Network Functions (CNFs) from multiple vendors running on top of Kubernetes. The goal is to provide an open source test suite to demonstrate conformance and implementation of best practices for both open and closed source Cloud native Network Functions. 

The conformance program is a living thing. The CNCF community, through the [Cloud Native Network Function Working Group](cnf-wg/README.md), oversees and maintains what it means to be a cloud native conformant telco application (including those applications called network functions). It also develops the process and policy around the certification program. Work on the mechanics of the conformance tests occurs in the [CNF Conformance Test Suite](README-testsuite.md).

## Why Conformance Matters
With such a wide array applications being developed today, workload conformance tests help ensure that developers can follow cloud native best practices when building greenfield applications and/or modernizing existing applications. A conformance passing application provides the following guarantees:

Best practices: Your application follows cloud native best practices. This is useful to know whether you are building upon the work of the community or handling your own custom setup.

Predictability: Your application acts in a predictable manner when running on cloud native infrastructure like Kubernetes. Unexpected behavior should be rare, because application specific issues are weeded out during the conformance tests.

Interoperability: Workloads can be ported across various cloud native infrastructures. This standardization is a key advantage of open source software, and allows you to avoid vendor lock-in.

Running applications in a cloud native manner will allow you more fully utilize the advantages of cloud native infrastructure.

## CNF Conformance Program

- Instructions - TBD
- FAQ - TBD

## Working Group Information

To participate and contribute to the program itself (including discussion of
issues affecting conformance and certification), join the mailing list and
slack channel. Details: [Conformance WG](cnf-wg/README.md).

## Test Suite Information

To contribute to or use the test suite you can join the slack channel, weekly meetings, and interact in github. Details: [Test suite](README-testsuite.md).
