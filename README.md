# class-mediator-database-paging
This simple class mediator can be used in a database paging requirement related use case. Along with the class mediator, there are synapse configurations which can be used to implement an end to end use case where data is pulled from a database and delivered to a backend service in a guaranteed and in-order manner.

![](https://github.com/chanakaudaya/class-mediator-database-paging/blob/master/WSO2%20EI%20Process%20large%20data%20set.png)

# sample database structure

+-----------+--------+---------------+-------------+---------+--------------+

| AccountID | Branch | AccountNumber | AccountType | Balance | ModifiedDate |

+-----------+--------+---------------+-------------+---------+--------------+

|         1 | AOB    | A00012        | CURRENT     |  231221 | 2014-12-02   |

|         2 | AOB    | A00012        | CURRENT     |  231221 | 2014-12-02   |

|         3 | AOB    | A00012        | CURRENT     |  231221 | 2014-12-02   |

|         4 | AOB    | A00012        | CURRENT     |  231221 | 2014-12-02   |

|         5 | AOB    | A00012        | CURRENT     |  231221 | 2014-12-02   |

|         6 | AOB    | A00012        | CURRENT     |  231221 | 2014-12-02   |

|         7 | AOB    | A00012        | CURRENT     |  231221 | 2014-12-02   |

|         8 | AOB    | A00012        | CURRENT     |  231221 | 2014-12-02   |

|         9 | AOB    | A00012        | CURRENT     |  231221 | 2014-12-02   |

|        10 | AOB    | A00012        | CURRENT     |  231221 | 2014-12-02   |

+-----------+--------+---------------+-------------+---------+--------------+

