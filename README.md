Phone for You is a company that sells smartphones through several stores. The company has
several partners at national level who are responsible for the company's sales. Phone for You not only
sends the equipment that is sold in each of the stores, but also supports the service
of product returns.
As a result of considerable growth in recent years, Phone for You aims for every
one of its partners to present a monthly sales report for its
products/smartphones, as well as the returns that were made. To do this, each partner will have
to implement a module in your computer system that exports information essentially about
sales and returns.
To support the sending of each partner's sales and returns report, it was decided to provide a
XML vocabulary in order to facilitate the integration of data from each partner. In this way, each
partner will have to implement in their IT systems a module that supports the generation of
XML documents (sales and returns) according to the established vocabulary.

# 1 - General information: The NIF, name and address of the partner, tax year and the month to which the
document (and which corresponds to the partner).

# 2 - The list of all customers involved in the sales, which includes: First and last name, email
(if the customer did not provide the email address, it should appear: “unknown”), the address (country, city and
postal code) and also the type of customer based on the time they have been registered in the system:
                  . Minus one year: “new”
                  . 1 and 5 years: “regular”
                  . More than 5 years: “premium”
It must also contain information on the number of purchases made by each customer in the
last 3 years, as well as the total value of purchases.

# 3 - The list of products involved in sales, which includes: the code, brand, model and current price.
Furthermore, each product must be categorized based on 5 perspectives:
                  . Price range: Budget, Mid-Range and High-End
                  . Performance: Basic, Standard, High and Gaming
                  . Front camera quality: Basic, Good and Pro
                  . Screen size: Small, Medium and Large
                  . Battery capacity: Short, Average and Long
                  . Storage capacity: Low, Medium and High

# 4 - For each sale it is necessary to register: the invoice code, the date of sale, the customer code
and the total value of the sale. For each sales line, it is necessary to record: The sales line number
sale, product code, product quantity and total value of the line.


# 5 - Summary information must be presented about the set of sales included in the
document, which includes: Number of different products, total sales, number of customers
different, number of sales by product category (Price Game, Performance,
Front Camera Quality, Screen Size, Battery Capacity and Power Capacity
storage).
