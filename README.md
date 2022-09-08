<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/534186274/22.1.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1114320)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Dashboard for ASP.NET Core - How to Color the Dashboard Item's Elements on the Client

The following example shows how to color a dashboard item's elements on the client. To do this, handle the [ViewerApiExtensionOptions.onItemElementCustomColor](https://docs.devexpress.com/Dashboard/js-DevExpress.Dashboard.ViewerApiExtensionOptions?p=netframework#js_devexpress_dashboard_viewerapiextensionoptions_onitemelementcustomcolor) event, get the item's [multidimensional data](https://docs.devexpress.com/Dashboard/403003/web-dashboard/dashboard-control-for-javascript-applications-jquery-knockout-etc/obtain-underlying-and-displayed-data#client-data-structure), and apply the color to the dashboard item's element based on the condition.

The image below displays dashboard items whose values are colored based on their values:

- [Chart item](https://docs.devexpress.com/Dashboard/117159/web-dashboard/create-dashboards-on-the-web/dashboard-item-settings/chart): For 2014, values that exceed 30k are colored green, values below 17k are red, and values between 170k and 30k are gray.
- [Pie item](https://docs.devexpress.com/Dashboard/117162/web-dashboard/create-dashboards-on-the-web/dashboard-item-settings/pies): Values below 80k are colored yellow.

![](dashboard-color-elements.png)

## Files to Look At

* [elementCustomColor.js](./CS/AspNetCoreDashboardColoring/wwwroot/js/elementCustomColor.js)
* [Index.cshtml](./CS/AspNetCoreDashboardColoring/Pages/Index.cshtml)


## Documentation

- [Coloring Basics](https://docs.devexpress.com/Dashboard/116915)
- [Coloring in the Web Dashboard](https://docs.devexpress.com/Dashboard/117152)

## More Examples

- [Dashboard for ASP.NET Core - How to Customize the Color Palette](https://github.com/DevExpress-Examples/asp-net-core-dashboard-customize-color-palettes)
- [Dashboard for Web Forms - How to Color the Dashboard Item's Elements on the Client](https://github.com/DevExpress-Examples/web-forms-dashboard-color-dashboard-item-elements)
