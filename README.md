# ABC_Blockchain
An implementation of  ABC: Proof-of-Stake without Consensus



### 使用

使用前要pip install cryptography

process相当于是主函数，会生成两个可以互发交易的进程，然后互相转10个coins

ledger是账本

transaction是控制每一个单笔交易，包括input，output，sign，还有validate