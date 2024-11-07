我們這裡採用的是Northwind資料集，Northwind資料集是一個廣泛使用的樣本資料庫，通常用於教學、練習和展示SQL查詢、資料庫設計和其他資料管理技巧。 ） Traders）的營運數據，主要涉及產品、客戶、訂單、供應商等方面。

主要包含以下表數據
+ Category：類別表，儲存產品類別的詳細信息
+ Region：地區表，儲存地區的詳細信息
+ Territory：銷售區域表，儲存銷售區域的詳細信息，並與區域表關聯
+ CustomerDemographics：儲存客戶類型及其描述
+ Customer：客戶表，儲存客戶的詳細信息
+ CustCustDemographics：客戶人口統計關聯表，建立客戶與客戶人口統計表之間的多對多關聯，一個客戶可能屬於多個人口統計類型
+ Employee：員工表，儲存員工的詳細信息
+ EmployeeTerritory：區域員工關聯表，建立員工與區域表之間的多對多關聯
+ Supplier：供應商表，儲存供應商的詳細信息
+ Product：產品表，儲存產品的詳細信息，並與 Supplier 和 Category 表關聯
+ Shipper：發貨商，倉庫發貨商的詳細信息
+ SalesOrder：訂單表，儲存訂單的詳細信息，並與 Customer, Employee 和 Shipper 表關聯
+ OrderDetail：訂單詳情表，訂單存儲中每個產品的詳細信息，並與 SalesOrder 和 Product 表關聯

資料集的ER圖如下：




