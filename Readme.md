<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128572094/15.2.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T308588)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* **[MainWindow.xaml](./CS/TreeMapFlatDataAdapterSample/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/TreeMapFlatDataAdapterSample/MainWindow.xaml))**
<!-- default file list end -->
# How to provide flat data to the TreeMap


This example demonstrates how to provide flat data to the TreeMap. To accomplish this task, use the <strong>Flat Data Adapter</strong>.


<h3>Description</h3>

To provide data using the Flat&nbsp;Data Adapter, do the following.<br />Assign a newly created <strong>TreeMapFlatDataAdapter</strong> object to the <strong>TreeMapControl.DataAdapter</strong> property. Then, specify the <strong>DataSource</strong>, <strong>LabelDataMember</strong> and&nbsp;<strong>ValueDataMember</strong> properties of the adapter.<br />In addition, it is possible to specify how to group automatically generated items. For this add a new <strong>GroupDefinition </strong>object to the adapter's&nbsp;<strong>Groups </strong>collection. Specify the <strong>GroupDataMember</strong> and <strong>HeaderContentTemplate</strong> properies of the definition.

<br/>


