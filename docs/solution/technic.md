
=== "Development"

    |  ID   | Category | Description |
    | :---: | :------- | :---------- |
    | 1 | Architecture | The system must be developed in a microservices model |
    | 2 | Architecture | The system must support multiple instances of their microservices |
    | 3 | Architecture | The system modules must comunicate themselves through STREAM service |
    | 4 | Architecture | The system must have a Mutual Exclusion Lock (MUTEX) supporting distributed locks |
    | 5 | Performance | The system must support more then one milion request per second |
    | 6 | Performance | The system must support more then a hundred milions wallets |
    | 7 | Performance | No transaction can take more the 650ms to execute |
    | 8 | Wallet | The wallet must to use a distributed mutex to guarantee the unitary execution of operations for each one. It is important to highlight that unitary execution must be per wallet, so it allows two different wallet to be operated at the same time |
    | 9 | Wallet | All transaction in the wallet must be executed synchronously at the user point of view. So for each request the user will receive the final response |
    | 10 | Wallet | As MUTEX will be implemented to grant the unitary and synchronously transacional execution, the sequentiality must be desconsidered |
    | 11 | Wallet | In the case of a centralized wallet, the MUTEX must act at the level of the main wallet |
    | 12 | Wallet | After each transaction the system must make available a way to send asynchronous notifications about the wallet transaction to others modules as needed |

=== "Infrastructure"

    | ID | Category | Description |
    | :---: | :--- | :--- |
    | 1 | Cloud | The Infrastructure as Code (IaC) must work at AWS, GCP, and Azure |
    | 2 | Cloud | The unique modification acceptable at the code to execute in different cloud are the provider selection and the cloud parameters |
    | 3 | Cloud | The IaC must use Terraform to configure the cloud |
    | 4 | Cloud | The IaC status must be stocked at the previously created cloud bucket |
    | 5 | Docker Compose | A docker compose file must be provided to enable a way to execute the solution without the cloud |
    | 6 | Docker Compose | Docker Compose execution model just is recommended for a solution understanding |
    | 7 | All In One | A docker image containing all solution most be provided. Once execute, it must disponibilize all solution that can be accessed by a provided URL |
    | 8 | All In One | All In One execution model just is recommended for an initial solution understanding |

=== "Security"

    | ID | Category | Description |
    | :---: | :--- | :--- |
    | 1 | Architecture | The solution must use the zero trust security model, also known as zero trust architecture (ZTA), must be implemented with focus on never trust, always verify, which means that users and devices should not be trusted by default |

