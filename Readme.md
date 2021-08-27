<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128569240/14.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T172081)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/SplineAreaChart/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/SplineAreaChart/MainWindow.xaml))
<!-- default file list end -->
# How to create a 2D Spline Area Chart

The following example demonstrates how to create a [2D Spline Area](https://docs.devexpress.com/WPF/17679/controls-and-libraries/charts-suite/chart-control/fundamentals/series-fundamentals/2d-series-types/area-series/spline-area?p=netframework) chart. To do this, it is necessary to assign the [ChartControl.Diagram](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.ChartControl.Diagram?p=netframework) property to [XYDiagram2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.XYDiagram2D?p=netframework), and then add two [SplineAreaSeries2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.SplineAreaSeries2D?p=netframework) objects with points to the diagram's [Series](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.Diagram.Series?p=netframework) collection.
Also, this example shows how to specify [AreaSeries2D.Transparency](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.AreaSeries2D.Transparency?p=netframework) and [SplineAreaSeries2D.LineTension](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.SplineAreaSeries2D.LineTension?p=netframework) properties and add a title to a chart.
