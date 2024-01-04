
=== "Development"

    |  ID   | Category | Description |
    | :---: | :------- | :---------- |
    | 1 | Architecture | The system must be developed in a microservices model |
    | 2 | Performance | The system must support more then one milion request per second |
    | 3 | Performance | The system must support more then a hundred milions users |
    | 3 | Transaction | The wallet must to use a distributed mutex to guarantee the unitary execution of operations for each portfolio. It is important to highlight that unitary execution must be per portfolio, which allows two different portfolios to be operated at the same time |
    | 4 | Transaction | In the case of a centralized wallet, the mutex must act at the level of the main wallet |
    | 1 | Transactions | After each transaction the system must make available a way to send asynchronous notifications about the wallet health to others modules as needed. |

=== "IaC"

    | ID | Category | Description |
    | :---: | :--- | :--- |
    |       |      |      |

=== "Security"

    | ID | Category | Description |
    | :---: | :--- | :--- |
    |       |      |      |
