# EchoFramework-GO

### URL
* Customers
```
    http://localhost:3000/customers/add
    http://localhost:3000/customers/list
    http://localhost:3000/customers/update
    http://localhost:3000/customers/delete
```
    
    
* Employees
```
    http://localhost:3000/employee/list
```
    
* Suppliers
```
    http://localhost:3000/suppliers/add
    http://localhost:3000/suppliers/list
    http://localhost:3000/suppliers/update
    http://localhost:3000/suppliers/delete
``` 
    
### Request JSON
* List Supplier
```
tidak harus diisi / request dapat berjalan hanya dengan url
```

* Adding Supplier
```
{
    "companyName" : "Beni Store",
    "contactName" : "Beni",
    "contactTitle" : "Purchasing Manager",
    "address" : "Surau Gadang",
    "city" : "Padank",
    "postalCode" : "25176",
    "country" : "Indon",
    "phone" :  "(171) 555-2222",
    "fax" : "55175",
    "homePage" : "www.drsync.id"
}
```

* Updating Supplier
```
{
    "companyName" : "Beni Store",
    "contactName" : "Beni Fajri",
    "contactTitle" : "Purchasing Manager",
    "supplierID" : 30
}
```


* Deleting Supplier
```
{
    "supplierID": "33"
}
```

### Hasil
* List Supplier
```
{
    "status": 200,
    "message": "succses",
    "data": [
        {
            "supplierID": "",
            "companyName": "Exotic Liquids",
            "contactName": "Charlotte Cooper",
            "contactTitle": "Purchasing Manager",
            "address": "49 Gilbert St.",
            "city": "London",
            "postalCode": "EC1 4SD",
            "country": "UK",
            "phone": "",
            "fax": "",
            "homePage": ""
        },
         ...
    ]
}
```

* Adding Supplier
```
{
    "status": 200,
    "message": "succes"
}
```

* Updating Supplier
```
{
    "status": 200,
    "message": "succes"
}
```


* Deleting Supplier
```
{
    "status": 200,
    "message": "succes"
}
```




