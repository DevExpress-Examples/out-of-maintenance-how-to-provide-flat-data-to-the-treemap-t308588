# How to provide flat data to the TreeMap


This example demonstrates how to provide flat data to the TreeMap. To accomplish this task, use the <strong>Flat Data Adapter</strong>.


<h3>Description</h3>

To provide data using the Flat&nbsp;Data Adapter, do the following.<br />Assign a newly created <strong>TreeMapFlatDataAdapter</strong> object to the <strong>TreeMapControl.DataAdapter</strong> property. Then, specify the <strong>DataSource</strong>, <strong>LabelDataMember</strong> and&nbsp;<strong>ValueDataMember</strong> properties of the adapter.<br />In addition, it is possible to specify how to group automatically generated items. For this add a new <strong>GroupDefinition </strong>object to the adapter's&nbsp;<strong>Groups </strong>collection. Specify the <strong>GroupDataMember</strong> and <strong>HeaderContentTemplate</strong> properies of the definition.

<br/>


