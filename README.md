# WPFThreads

# Consegna

Bisogna visualizzare un conteggio utilizzando le istruzioni multithread

Si devono avere  quindi tre oggetti TextBlock WPF che visualizzano l'andamento dei tre contatori a velocità diverse.

Il primo scatta ogni ms e conta fino a 5000 (durata totale 5 secondi).
Il secondo scatta ogni 10ms e conta fino a 500 (durata totale 5 secondi).
Il terzo scatta ogni 100ms e conta fino a 50 (durata totale 5 secondi).

Si preveda un quarto TextBlock che visualizzi il totale dei tre contatori (alla fine visualizzerà 5.550)

Come ultima cosa abbiamo bisogno di un pulsante "Start" per far partire i conteggi e che rimanga disattivato durante il conteggio e  che si riattivi alla fine

#Introduzione

Come prima cosa dobbiamo creare un nuovo progetto

![Screenshot 2023-04-16 002455](https://user-images.githubusercontent.com/116788494/234233686-d4239a24-e1c4-4120-ad67-88cd0d17b411.png)

Dopo aver scelto il tipo di applicazione che vogliamo fare bisogna anche scegliere la versione di dotnet più adatta alle nostre esigenze

![image](https://user-images.githubusercontent.com/116788494/234234142-a861b746-4ed6-4d08-b112-ecf9db810f27.png)

Dopo aver creato il file utilizzeremo delle linee di codice per creare  delle righe,colonne e i 2 button neccessari per svolgere il lavoro richiesto

![image](https://user-images.githubusercontent.com/116788494/234235484-043a09a8-5720-4a18-8c86-7e1bf8760ab0.png)


 <Grid>
 <Grid.RowDefinitions>
 <RowDefinition></RowDefinition>
 <RowDefinition></RowDefinition>
 <RowDefinition></RowDefinition>
 </Grid.RowDefinitions>
 <Grid.ColumnDefinitions>
 <ColumnDefinition></ColumnDefinition>
 <ColumnDefinition></ColumnDefinition>
 <ColumnDefinition></ColumnDefinition>
 </Grid.ColumnDefinitions>
 <Button Height="100" Grid.Row="1" Grid.Column="1" Width="200" > </Button>
 <Button Height="50" Width="100">
 </Button>
 </Grid>
 
 
 
 
 
 





