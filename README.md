# fdo
## SCHEMAS

CUSTOMER
- Id : string
- Code : string | null
- Naming : string
- zipCode : string
- Address : string
- City : string

PRODUCT
- Id : string
- Code : string
- Label : string

PRODUCT_ORDER
- Product : object
- Amount : number
- unitPrice : number

ORDER
- Id : string
- Code : string
- Customer : Object
- ProductOrder[] : Array of objects
- billingDate : date
- dueDate : date


