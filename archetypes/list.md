---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
type: activiti
layout: list
user: user
datalist: []
rowbuttonlist: []
testdatalist: []
buttonlist: []
---

** create a form to list data **

## user
. user
. manager
. senior_manager
. system_manager
## datalist
input the column name of your data,sample data like this
```
[
    {id: "id",name: "ID",formatter: "run",identifier: "true",type: "numeric"},
    {id: "name",name: "Name",formatter: "",identifier: "",type: ""},
    {id: "category",name: "Category",formatter: "",identifier: "",type: ""},
    {id: "unit",name: "Unit",formatter: "",identifier: "",type: ""},
    {id: "price",name: "Price",formatter: "run",identifier: "true",type: "numeric"},
    {id: "comment",name: "Comment",formatter: "",identifier: "",type: ""}
]
```
## rowbuttonlist
input the button you want to operate the data,sample data like this
```
[
    {name: "Update",url: "/user/product/update"},
    {name: "Delete",url: "#"},
]
```

## testdatalist
input your test data,sample data like this
```
[
    "1",
    "product",
    "category",
    "unit",
    "100",
    "comment"
]
```
## buttonlist
input the button you want to operate all data,sample data like this
```
[
    {name: "Create",url: "/user/product/update"},
    {name: "Search",url: "#"},
]
```
