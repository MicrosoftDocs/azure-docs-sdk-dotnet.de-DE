<Type Name="DataLakeStoreTransferClient" FullName="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient">
  <TypeSignature Language="C#" Value="public sealed class DataLakeStoreTransferClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DataLakeStoreTransferClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DataLakeStoreTransferClient" />
  <TypeSignature Language="F#" Value="type DataLakeStoreTransferClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt ein allgemeines Datei übertragungsclients in ein Data Lake-Speicher dar. Die effiziente Übertragung großer Dateien unterstützt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreTransferClient (Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontEnd, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker = null, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; folderProgressTracker = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, class Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontEnd, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; folderProgressTracker) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.#ctor(Microsoft.Azure.Management.DataLake.Store.TransferParameters,Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferProgress},System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient : Microsoft.Azure.Management.DataLake.Store.TransferParameters * Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient" Usage="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient (transferParameters, frontEnd, progressTracker, folderProgressTracker)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transferParameters" Type="Microsoft.Azure.Management.DataLake.Store.TransferParameters" />
        <Parameter Name="frontEnd" Type="Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt;" />
        <Parameter Name="folderProgressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt;" />
      </Parameters>
      <Docs>
        <param name="transferParameters">Die Übertragung-Parameter verwendet werden soll.</param>
        <param name="frontEnd">Ein Zeiger auf die Front-End-Schnittstelle, die für die Übertragung verwendet werden soll.</param>
        <param name="progressTracker">(Optional) Ein Tracker, die auf die Übertragung Fortschrittsberichte.</param>
        <param name="folderProgressTracker">(Optional) Der Ordner-Status-nachverfolgung.</param>
        <summary>
            Erstellt eine neue Instanz der Klasse DataLakeStoreTransferClient, indem ein Zeiger auf das Front-End für die Übertragung verwenden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreTransferClient (Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontEnd, System.Threading.CancellationToken token, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker = null, IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; folderProgressTracker = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataLake.Store.TransferParameters transferParameters, class Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter frontEnd, valuetype System.Threading.CancellationToken token, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; progressTracker, class System.IProgress`1&lt;class Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; folderProgressTracker) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.#ctor(Microsoft.Azure.Management.DataLake.Store.TransferParameters,Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter,System.Threading.CancellationToken,System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferProgress},System.IProgress{Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient : Microsoft.Azure.Management.DataLake.Store.TransferParameters * Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter * System.Threading.CancellationToken * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt; * IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient" Usage="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient (transferParameters, frontEnd, token, progressTracker, folderProgressTracker)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transferParameters" Type="Microsoft.Azure.Management.DataLake.Store.TransferParameters" />
        <Parameter Name="frontEnd" Type="Microsoft.Azure.Management.DataLake.Store.IFrontEndAdapter" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
        <Parameter Name="progressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferProgress&gt;" />
        <Parameter Name="folderProgressTracker" Type="System.IProgress&lt;Microsoft.Azure.Management.DataLake.Store.TransferFolderProgress&gt;" />
      </Parameters>
      <Docs>
        <param name="transferParameters">Die Übertragung zu verwendenden Parameter.</param>
        <param name="frontEnd">Ein Zeiger auf die Front-End-Schnittstelle, die für die Übertragung verwendet werden soll.</param>
        <param name="token">Das Token.</param>
        <param name="progressTracker">(Optional) Ein Tracker, die auf die Übertragung Fortschrittsberichte.</param>
        <param name="folderProgressTracker">(Optional) Der Ordner-Status-nachverfolgung.</param>
        <summary>
            Erstellt eine neue Instanz der Klasse DataLakeStoreTransferClient, indem ein Zeiger auf das Front-End für die Übertragung verwenden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public void Execute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Execute() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.Execute" />
      <MemberSignature Language="VB.NET" Value="Public Sub Execute ()" />
      <MemberSignature Language="F#" Value="member this.Execute : unit -&gt; unit" Usage="dataLakeStoreTransferClient.Execute " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Führt die Übertragung an, gemäß den Eingabeparametern.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAllowedThreadsPerFile">
      <MemberSignature Language="C#" Value="public const int MaxAllowedThreadsPerFile = 1024;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int32 MaxAllowedThreadsPerFile = (1024)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.MaxAllowedThreadsPerFile" />
      <MemberSignature Language="VB.NET" Value="Public Const MaxAllowedThreadsPerFile As Integer  = 1024" />
      <MemberSignature Language="F#" Value="val mutable MaxAllowedThreadsPerFile : int" Usage="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.MaxAllowedThreadsPerFile" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <MemberValue>1024</MemberValue>
      <Docs>
        <summary>
            Die maximale Anzahl von parallelen Threads zu ermöglichen. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnFileTransferThreadFailProgressUpdate">
      <MemberSignature Language="C#" Value="public event Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate OnFileTransferThreadFailProgressUpdate;" />
      <MemberSignature Language="ILAsm" Value=".event class Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate OnFileTransferThreadFailProgressUpdate" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.OnFileTransferThreadFailProgressUpdate" />
      <MemberSignature Language="VB.NET" Value="Public Event OnFileTransferThreadFailProgressUpdate As FileTransferThreadFailProgressUpdate " />
      <MemberSignature Language="F#" Value="member this.OnFileTransferThreadFailProgressUpdate : Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate " Usage="member this.OnFileTransferThreadFailProgressUpdate : Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             Ein Ereignis, das registriert wird, um den Fortschritt nachverfolgen, um sicherzustellen, dass ein unerwarteter Übertragungsfehler Fortschritt ordnungsgemäß aktualisiert wird.
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.TransferParameters Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.TransferParameters Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As TransferParameters" />
      <MemberSignature Language="F#" Value="member this.Parameters : Microsoft.Azure.Management.DataLake.Store.TransferParameters" Usage="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreTransferClient.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.TransferParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Parameter für diese Übertragung verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>