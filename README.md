# NET Performance Series

Repository to accompany my .NET Performance Series Articles on medium.com

## How to run

To run Benchmarks in a certain namespace or by name, simply run:

```
dotnet run -c Release --framework net6.0 net7.0 --filter *<filter>*
```

and replace '<filter>' with a part of the name or namespace. If applicable, you might need to remove **net6.0** from this line.

# References

.NET Performance Analysis: Newtonsoft.Json vs System.Text.Json in .NET 8

https://trevormccubbin.medium.com/net-performance-analysis-newtonsoft-json-vs-system-text-json-in-net-8-34520c21d054

https://github.com/gtechsltn/DotnetBenchmarks

.NET Performance #2: Newtonsoft vs. System.Text.Json

https://medium.com/@tobias.streng/net-performance-series-2-newtonsoft-vs-system-text-json-2bf43e037db0

https://github.com/gtechsltn/NET7-Performance
