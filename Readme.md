# How to repeat the Detail report band multiple times (a data-bound report)


If your report's data source is empty or not defined, you can <strong>specify</strong> how many times the Detail band content is printed through the <strong><a href="https://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUIReportPrintOptions_DetailCountOnEmptyDataSourcetopic">XtraReport.PrintOptions.DetailCountOnEmptyDataSource</a></strong> property.<br><br>If a report is<strong> data bound</strong>, you can <strong>limit </strong>the number of times the Detail band is printed by using the <a href="https://documentation.devexpress.com/XtraReports/DevExpressXtraReportsUIReportPrintOptions_DetailCounttopic.aspx">DetailCount</a> property.<br><br>Please note that the <a href="https://documentation.devexpress.com/XtraReports/DevExpressXtraReportsUIReportPrintOptions_DetailCounttopic.aspx">DetailCount</a> property is designed to specify the maximum number (i.e., the limit) of times the Detail band is printed. In other words, if a data source contains one record, we cannot print it more than one time by using the <a href="https://documentation.devexpress.com/XtraReports/DevExpressXtraReportsUIReportPrintOptions_DetailCounttopic.aspx">DetailCount</a> property. <br>We need to use the solution illustrated by this example. It demonstrates how to repeat a data source record depending on a value taken from another field. To achieve this, add an unbound <a href="https://documentation.devexpress.com/#XtraReports/clsDevExpressXtraReportsUIDetailReportBandtopic">DetailReportBand</a> and control the number of copies using its <strong><a href="https://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUIReportPrintOptions_DetailCountOnEmptyDataSourcetopic">ReportPrintOptions.DetailCountOnEmptyDataSource</a></strong> property.<br><br>See also: <br><strong><a href="https://www.devexpress.com/Support/Center/p/E3740">How to print DetailBand a particular amount of times irregardless of the number of records in a report datasource</a></strong>

<br/>


