# LINQDb
programma per accedere e usare le informazioni di un database

Innanzitutto bisogna creare un progetto .NET che utilizzi la libreria <span style="color:red">sqlite-net-plc</span>

Dopo aver aperto un nuovo terminale si scrive:
![Cattura](https://github.com/AgoRoss/LINQDb/assets/116869835/ab772f90-32b8-4641-8aa6-e876a9cd030e)
senza specificare la versione; verrà automaticamente installata la versione più recente

In questo programma viene usato chinook.db, che è un database SQL che provvede numerose tabelle
esempio:
![cdb](https://github.com/AgoRoss/LINQDb/assets/116869835/4d915a8d-e1a9-4c8e-a65d-6de76df5919e)
chinook.db è facilmente manipolabile e viene spesso usato come tutorial per esercizi di questo tipo

fortunatamente LINQ permette di accedere alle query usando il C#
```csharp
foreach (var Artist in ArtistId)
{
    Console.WriteLine(ArtistId.Name);
}
```
