---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
type: activiti
layout: list
user: user
datalist: []
datatypelist: []
dataformatlist: []
buttonlist: []
testdatalist: []
columnidlist: []
identifiers: []
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