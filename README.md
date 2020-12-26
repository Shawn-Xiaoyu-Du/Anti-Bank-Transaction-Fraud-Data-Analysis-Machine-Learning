# Anti-Fraud-Transaction-Data-analysis
Based on 574256 Transaction lines to detect the Fraud Transaction automatically with model


Variables Names:
step: The number 1-24 represents24 hours.
Transaction type. 
Transation amount.
nameOrig, The name of account who pay	and transfer from
oldbalanceOrg, the payment account	balance before transaction.
newbalanceOrig,the payment account	balance after transaction.
nameDest, the account	receive payment balance name.
oldbalanceDest, the account	receive payment balance before transaction.
newbalanceDest, the account	receive payment balance after transaction.
isFraud, Key label, the prediction output

该数据基于真实的金融交易记录生成的数据集，各列含义如下：
step: 时间范围，1表示凌晨12:00-1:00
type: 交易类型，Cash-in, Cash-out,Debit,Payment and Transfer五种
amount: 交易金额
NameOrig: 交易者
OldbalanceOrig: 交易之前的账户余额
NewbalanceOrig: 交易之后的账户余额
nameDest:交易的接收方
OldbalanceDest 交易之前交易接收方账户余额，商家则无信息
newbalanceDest 交易之后接收方账户余额，商家则无信息
isFraud 如果是欺诈交易取值为1，否则为0

整个数据挖掘建模如下：
1. 问题分析与模型选择
2. 数据分析与可视化
3. 数据预处理与特征购机
4. 模型训练与验证
5. 总结与分析
