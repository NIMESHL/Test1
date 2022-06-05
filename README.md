#  the below SQL query shows how to fetch all the details from the Customers table #


CustomerID	| CustomerName | 	ContactName	 | Address	     | City	  | PostalCode | Country
1           |Alfreds       |  Maria Anders | Obere Str. 57 | Berlin | 12209	     | Germany
             Futterkiste		 
2	          |Ana Trujillo  |	Ana Trujillo | Avda. de la   | México |	05021      | Mexico
             Emparedados y                   Constitución     D.F.
              helados                          2222	
              

SELECT * FROM Customers
WHERE Country='Mexico';
