![peasy](https://www.dropbox.com/s/2yajr2x9yevvzbm/peasy3.png?dl=0&raw=1)

### Peasy.DataProxy.InMemory

Peasy.DataProxy.InMemory provides the [InMemoryDataProxyBase](https://github.com/ahanusa/Peasy.DataProxy.InMemory/blob/master/Peasy.DataProxy.InMemory/InMemoryDataProxyBase.cs) class.  InMemoryDataProxyBase is an abstract class that implements [IDataProxy](), and can be used to provide an in-memory implementation of your data layer.

Creating an in-memory implementation of your data layer can help facilitate state-based unit tests as well as serving as a fake repository for rapid development of your [service classes]().

