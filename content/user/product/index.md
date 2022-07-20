---
title: "Product"
date: 2022-07-20T13:26:35+09:00
draft: true
type: activiti
layout: list
user: user
datalist: [
    {id: "id",name: "ID",formatter: "run",identifier: "true",type: "numeric"},
    {id: "name",name: "Name",formatter: "",identifier: "",type: ""},
    {id: "category",name: "Category",formatter: "",identifier: "",type: ""},
    {id: "unit",name: "Unit",formatter: "",identifier: "",type: ""},
    {id: "price",name: "Price",formatter: "run",identifier: "true",type: "numeric"},
    {id: "comment",name: "Comment",formatter: "",identifier: "",type: ""}
    ]
buttonlist: [
    {name: "Update",url: "/user/product/update"},
    {name: "Delete",url: "/user/product/insert"},
]
testdatalist: [
    "1",
    "product",
    "category",
    "unit",
    "100",
    "comment"
]
---

** create a form to list data **

## user
. user
. manager
. senior_manager
. system_manager
## datalist
input the column name of your data
## datatypelist
input the column dataType of your data
. int
. float
. string
. boolean
. date
. datetime
## buttonlist
input the button you want to operate the data
. create
. update
. confirm
. cancel
. delete
. linkto
. custom operator