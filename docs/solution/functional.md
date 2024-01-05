
=== "Digital Wallet"

    | ID | Category | Description |
    | :---: | :--- | :--- |
    | 1 | Identification | Every wallet must be identified by an automatically generated non-numeric and non-sequential ID. Once assigned, this value can no longer be changed |
    | 2 | Anonymization | It is extremely important that the wallet does not contain data that uniquely identifies the user |
    | 3 | Operation | It must make it possible to carry out financial transactions involving the entry and exit of capital in which every operation is the addition of a value. To withdraw capital, you must add a negative value |
    | 4 | Operation | In the moment of operation the statement and balance must be actualized transactionally. No matter how many transaction it can be made concurrently, the balance must be consistent |
    | 5 | Operation | The wallet must not accept operations that leave it with a negative balance, except in the case of a over limit associated with it |
    | 6 | Over Limit | The wallets must have an over limit feature, which allows operations to be carried out that could lead to a negative balance |
    | 7 | Over Limit | The over limit must be configured separately per wallet, thus allowing the maximum extra limit to be changed when necessary without changing the other wallets |
    | 8 | Type | There must be three kind of wallets: __Single__, __Shared__, and __Centralized__ |
    | 9 | Single | In a single Wallet, the wallet serves only the user who carries out the transaction without affecting any other user |
    | 10 | Shared | In a shared Wallet, the wallet serves all users who share it. This way, a user can use any value on the card at any time, as long as it has an available balance |
    | 11 | Shared | In a shared transaction, all users who share it have the ability to view all transactions carried out in the wallet. These operations identify the user who performed them |
    | 12 | Centralized | In a centralized wallet, there is a main wallet and secondary wallets. Each user who shares the main wallet has their own secondary wallet, which in turn is managed by the main wallet |
    | 13 | Centralized | In a centralized wallet, the secondary wallet must always have its balance equal to zero; as every operation must occur at the level of the main wallet |
    | 14 | Centralized | Each user of a centralized wallet can only see the operations carried out by himself. Therefore, they cannot have access to operations carried out by other users holding a secondary wallet linked to the main wallet |
    | 15 | Centralized | In a secondary wallet, all operations must be replicated to the main wallet, however the balance of the secondary wallet must not be affected. This replication must be synchronous and must only happen if it is possible to do in the main wallet |
    | 16 | Centralized | Operations carried out through a secondary wallet in a centralized model must only be visible to the user who carried it out and the owner of the main wallet |
    | 17 | Centralized | The main wallet owner must be able to view the operations with identification of which user performed them |
    | 18 | Block and Unblock | Existem duas maneiras de bloquear e desbloquear uma carteira. O primeiro é o institucional, que só a instituição financeira pode executar. A segunda é a do cliente, que pode ser executada conforme sua necessidade |
    | 19 | Block and Unblock | In a wallet blocked by the financial institution, only add value operations can be carried out. Capital withdrawals must be blocked |
    | 20 | Block and Unblock | In a wallet blocked by the client, no operations can be carried out, except special operations originating from the financial institution. e.g. Maintenance fee |
    | 21 | Block and Unblock | The most important rule of the block and unblock feature is their precedence of blocking before unlocking, that means no matter if the user or institution says unblock, if the client says block the wallet cannot be operated. The same is valid if the institution say block |
    | 22 | Block and Unblock | Is crucial that client and institution does not interfere in the block and unblock action of other. The blocks and unblock of these player must be independent |

=== "Client"

    | ID | Category | Description |
    | :---: | :--- | :--- |
    |       |      |      |

=== "Product"

    | ID | Category | Description |
    | :---: | :--- | :--- |
    |       |      |      |

=== "Monitoring"

    | ID | Category | Description |
    | :---: | :--- | :--- |
    |       |      |      |

=== "Insight"

    | ID | Category | Description |
    | :---: | :--- | :--- |
    |       |      |      |

=== "Integration" 

    | ID | Category | Description |
    | :---: | :--- | :--- |
    |       |      |      |

=== "User Interface"

    | ID | Category | Description |
    | :---: | :--- | :--- |
    |       |      |      |