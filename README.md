# Cross-Selling_Project:  How to increase cross selling of Banking Products
Final Project for Data Glacier virtual internship


Problem Statement:  XYZ credit union in Latin America is performing very well in selling the Banking products (eg: Credit card, deposit account, retirement account, safe deposit box etc) but their existing customer is not not buying more than 1 product which means bank is not performing good in cross selling (Bank is not able to sell their other offerings to existing customer). XYZ Credit Union decided to approach ABC analytics to solve their problem.

ML Problem statement:

ABC company came up with a framework which will be utilizing machine learning algorithm in the core to increase cross selling.

But As a data analyst you need to inspect the data and suggest what action bank can take to increase cross selling (without using ML)

Task:

1. Business understanding

2. Data Understanding

3. Data Cleansing and Transformation

4. Exploratory data analysis

5. EDA Recommendation (ppt)

6. Dashboard which should capture type of customer their count, segment wise (VIP,student etc) customer average age and other KPIs which gives better business insight in taking decision.

7. Prepare a final presentation


Data Set:  https://drive.google.com/file/d/16-nzZR91-ijrfjUcI2PniTpOgrvFAykA/view


|Column Name |	Description |
| ----------------------- | -----------------------------|
|fecha_dato	|The table is partitioned for this column |
|ncodpers	|Customer code |
|ind_empleado	 |Employee index: A active, B ex employed, F filial, N not employee, P pasive |
|pais_residencia |Customer's Country residence |
|sexo	|Customer's sex|
|age|	Age|
|fecha_alta	|The date in which the customer became as the first holder of a contract in the bank|
|ind_nuevo	|New customer Index. 1 if the customer registered in the last 6 months.|
|antiguedad	|Customer seniority (in months)|
|indrel	|1 (First/Primary), 99 (Primary customer during the month but not at the end of the month)|
|ult_fec_cli_1t	|Last date as primary customer (if he isn't at the end of the month)|
|indrel_1mes	|Customer type at the beginning of the month ,1 (First/Primary customer), 2 (co-owner ),P (Potential),3 (former primary), 4(former co-owner)|
|tiprel_1mes	|Customer relation type at the beginning of the month, A (active), I (inactive), P (former customer),R (Potential)|
|indresi	|Residence index (S (Yes) or N (No) if the residence country is the same than the bank country)|
|indext	|Foreigner index (S (Yes) or N (No) if the customer's birth country is different than the bank country)|
|conyuemp|	Spouse index. 1 if the customer is spouse of an employee|
|canal_entrada|	channel used by the customer to join|
|indfall	|Deceased index. N/S|
|tipodom	|Addres type. 1, primary address|
|cod_prov	|Province code (customer's address)|
|nomprov	|Province name|
|ind_actividad_cliente	|Activity index (1, active customer; 0, inactive customer)|
|renta	|Gross income of the household|
|segmento	|segmentation: 01 - VIP, 02 - Individuals 03 - college graduated|
|ind_ahor_fin_ult1|	Saving Account|
|ind_aval_fin_ult1	|Guarantees|
|ind_cco_fin_ult1	|Current Accounts |
|ind_cder_fin_ult1	|Derivada Account|
|ind_cno_fin_ult1	|Payroll Account|
|ind_ctju_fin_ult1	|Junior Account|
|ind_ctma_fin_ult1|	Más particular Account|
|ind_ctop_fin_ult1	|particular Account|
|ind_ctpp_fin_ult1	|particular Plus Account |
|ind_deco_fin_ult1	|Short-term deposits |
|ind_deme_fin_ult1	|Medium-term deposits |
|ind_dela_fin_ult1	|Long-term deposits |
|ind_ecue_fin_ult1	|e-account |
|ind_fond_fin_ult1	|Funds|
|ind_hip_fin_ult1	|Mortgage |
|ind_plan_fin_ult1	|Pensions |
|ind_pres_fin_ult1	|Loans |
|ind_reca_fin_ult1	|Taxes |
|ind_tjcr_fin_ult1	|Credit Card |
|ind_valo_fin_ult1	|Securities |
|ind_viv_fin_ult1	| Home Account|
|ind_nomina_ult1	|    Payroll |
|ind_nom_pens_ult1	| Pensions |
|ind_recibo_ult1	 |   Direct Debit|
