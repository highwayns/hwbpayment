---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
type: activiti
layout: form
user: user
datalist: []
buttonlist: []
---

** create a form to input data **

## user
. user
. manager
. senior_manager
. system_manager
## datalist
input the column name of your data,sample data just like this
```
[
    {id: "id",name: "ID",caption: "ID",type: "numeric",option: []},
    {id: "name",name: "Name",caption: "Name",type: "text",option: []},
    {id: "category",name: "Category",caption: "Category",type: "option",option: [{value: "b",text: "Watch"},{value: "p",text: "Picture"}]},
    {id: "unit",name: "Unit",caption: "Unit",type: "option",option: [{value: "k",text: "KG"},{value: "b",text: "Box"}]},
    {id: "price",name: "Price",caption: "Price",type: "numeric",option: []},
    {id: "comment",name: "Comment",caption: "Comment",type: "textarea",option: []}
]
```
## buttonlist
input the button you want to operate the data,sample data like this
```
[
    {name: "Confirm",url: "/user/product/"},
    {name: "Reset",url: "#"},
]
```
