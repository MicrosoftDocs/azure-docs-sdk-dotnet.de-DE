<Type Name="TableOperation" FullName="Microsoft.Azure.CosmosDB.Table.TableOperation">
  <TypeSignature Language="C#" Value="public class TableOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableOperation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />
  <TypeSignature Language="VB.NET" Value="Public Class TableOperation" />
  <TypeSignature Language="F#" Value="type TableOperation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="82cc9-101">Stellt einen einzelnen tabellenvorgang dar.</span><span class="sxs-lookup"><span data-stu-id="82cc9-101">Represents a single table operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Delete (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Delete(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Delete(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Delete entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="82cc9-102">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> Objekt aus der Tabelle gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="82cc9-102">The <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> object to be deleted from the table.</span></span></param>
        <summary>
            <span data-ttu-id="82cc9-103">Erstellt einen neuen tabellenvorgang, der die angegebene Entität aus einer Tabelle löscht.</span><span class="sxs-lookup"><span data-stu-id="82cc9-103">Creates a new table operation that deletes the given entity from a table.</span></span>
            </summary>
        <returns><span data-ttu-id="82cc9-104">Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-104">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Entity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.ITableEntity Entity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.ITableEntity Entity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableOperation.Entity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Entity As ITableEntity" />
      <MemberSignature Language="F#" Value="member this.Entity : Microsoft.Azure.CosmosDB.Table.ITableEntity" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Entity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.ITableEntity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82cc9-105">Ruft die Entität, die nach bearbeiteten ab.</span><span class="sxs-lookup"><span data-stu-id="82cc9-105">Gets the entity that is being operated upon.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Insert (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Insert(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Insert(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Insert (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Insert : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Insert entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="82cc9-106">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> in die Tabelle einzufügende Objekt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-106">The <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> object to be inserted into the table.</span></span></param>
        <summary>
            <span data-ttu-id="82cc9-107">Erstellt einen neuen tabellenvorgang, der die angegebene Entität in eine Tabelle einfügt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-107">Creates a new table operation that inserts the given entity into a table.</span></span>
            </summary>
        <returns><span data-ttu-id="82cc9-108">Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-108">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Insert (Microsoft.Azure.CosmosDB.Table.ITableEntity entity, bool echoContent);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Insert(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity, bool echoContent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Insert(Microsoft.Azure.CosmosDB.Table.ITableEntity,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Insert (entity As ITableEntity, echoContent As Boolean) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Insert : Microsoft.Azure.CosmosDB.Table.ITableEntity * bool -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Insert (entity, echoContent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
        <Parameter Name="echoContent" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="82cc9-109">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> in die Tabelle einzufügende Objekt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-109">The <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> object to be inserted into the table.</span></span></param>
        <param name="echoContent">
          <span data-ttu-id="82cc9-110"><c>"true"</c> , wenn die Nachrichtennutzlast in der Antwort zum Einfügevorgang zurückgegeben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="82cc9-110"><c>true</c> if the message payload should be returned in the response to the insert operation.</span></span> <span data-ttu-id="82cc9-111"><c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="82cc9-111"><c>false</c> otherwise.</span></span></param>
        <summary>
            <span data-ttu-id="82cc9-112">Erstellt einen neuen tabellenvorgang, der die angegebene Entität in eine Tabelle einfügt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-112">Creates a new table operation that inserts the given entity into a table.</span></span>
            </summary>
        <returns><span data-ttu-id="82cc9-113">Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-113">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertOrMerge">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation InsertOrMerge (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation InsertOrMerge(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.InsertOrMerge(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function InsertOrMerge (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member InsertOrMerge : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.InsertOrMerge entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="82cc9-114">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> Objekt eingefügt oder zusammengeführt werden.</span><span class="sxs-lookup"><span data-stu-id="82cc9-114">The <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> object to be inserted or merged.</span></span></param>
        <summary>
            <span data-ttu-id="82cc9-115">Erstellt einen neuen tabellenvorgang, der die angegebene Entität in eine Tabelle einfügt, wenn die Entität nicht vorhanden ist. Wenn die Entität vorhanden ist, werden dessen Inhalt mit der angegebenen Entität zusammengeführt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-115">Creates a new table operation that inserts the given entity into a table if the entity does not exist; if the entity does exist then its contents are merged with the provided entity.</span></span>
            </summary>
        <returns><span data-ttu-id="82cc9-116">Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-116">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation InsertOrReplace (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation InsertOrReplace(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.InsertOrReplace(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function InsertOrReplace (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member InsertOrReplace : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.InsertOrReplace entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="82cc9-117">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> Objekt eingefügt oder ersetzt werden.</span><span class="sxs-lookup"><span data-stu-id="82cc9-117">The <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> object to be inserted or replaced.</span></span></param>
        <summary>
            <span data-ttu-id="82cc9-118">Erstellt einen neuen tabellenvorgang, der die angegebene Entität in eine Tabelle einfügt, wenn die Entität nicht vorhanden ist. Wenn die Entität vorhanden ist, werden dessen Inhalt durch die angegebene Entität ersetzt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-118">Creates a new table operation that inserts the given entity into a table if the entity does not exist; if the entity does exist then its contents are replaced with the provided entity.</span></span>
            </summary>
        <returns><span data-ttu-id="82cc9-119">Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-119">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Merge (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Merge(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Merge(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Merge (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Merge : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Merge entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="82cc9-120">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> Objekt zusammengeführt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="82cc9-120">The <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> object to be merged.</span></span></param>
        <summary>
            <span data-ttu-id="82cc9-121">Erstellt einen neuen tabellenvorgang, der den Inhalt der angegebenen Entität mit der vorhandenen Entität in einer Tabelle zusammenführt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-121">Creates a new table operation that merges the contents of the given entity with the existing entity in a table.</span></span>
            </summary>
        <returns><span data-ttu-id="82cc9-122">Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-122">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableOperationType OperationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.CosmosDB.Table.TableOperationType OperationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableOperation.OperationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationType As TableOperationType" />
      <MemberSignature Language="F#" Value="member this.OperationType : Microsoft.Azure.CosmosDB.Table.TableOperationType" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.OperationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82cc9-123">Ruft den Typ des Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="82cc9-123">Gets the type of operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Replace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Replace (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Replace(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Replace(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Replace (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Replace : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Replace entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="82cc9-124">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> Objekt ersetzt werden.</span><span class="sxs-lookup"><span data-stu-id="82cc9-124">The <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> object to be replaced.</span></span></param>
        <summary>
            <span data-ttu-id="82cc9-125">Erstellt einen neuen tabellenvorgang, der den Inhalt der angegebenen Entität in einer Tabelle ersetzt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-125">Creates a new table operation that replaces the contents of the given entity in a table.</span></span>
            </summary>
        <returns><span data-ttu-id="82cc9-126">Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-126">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Retrieve (string partitionKey, string rowkey, System.Collections.Generic.List&lt;string&gt; selectedColumns = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Retrieve(string partitionKey, string rowkey, class System.Collections.Generic.List`1&lt;string&gt; selectedColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Retrieve(System.String,System.String,System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Retrieve (partitionKey As String, rowkey As String, Optional selectedColumns As List(Of String) = null) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Retrieve : string * string * System.Collections.Generic.List&lt;string&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Retrieve (partitionKey, rowkey, selectedColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowkey" Type="System.String" />
        <Parameter Name="selectedColumns" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKey"><span data-ttu-id="82cc9-127">Eine Zeichenfolge mit dem Partitionsschlüssel der Entität abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="82cc9-127">A string containing the partition key of the entity to be retrieved.</span></span></param>
        <param name="rowkey"><span data-ttu-id="82cc9-128">Eine Zeichenfolge mit dem Zeilenschlüssel der Entität abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="82cc9-128">A string containing the row key of the entity to be retrieved.</span></span></param>
        <param name="selectedColumns"><span data-ttu-id="82cc9-129">Liste der Spaltennamen für die Projektion.</span><span class="sxs-lookup"><span data-stu-id="82cc9-129">List of column names for projection.</span></span></param>
        <summary>
            <span data-ttu-id="82cc9-130">Erstellt einen neuen tabellenvorgang, der den Inhalt der angegebenen Entität in einer Tabelle abruft.</span><span class="sxs-lookup"><span data-stu-id="82cc9-130">Creates a new table operation that retrieves the contents of the given entity in a table.</span></span>
            </summary>
        <returns><span data-ttu-id="82cc9-131">Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-131">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Retrieve&lt;TElement&gt; (string partitionKey, string rowkey, System.Collections.Generic.List&lt;string&gt; selectColumns = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntity;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Retrieve&lt;(class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(string partitionKey, string rowkey, class System.Collections.Generic.List`1&lt;string&gt; selectColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Retrieve``1(System.String,System.String,System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Retrieve(Of TElement As ITableEntity) (partitionKey As String, rowkey As String, Optional selectColumns As List(Of String) = null) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Retrieve : string * string * System.Collections.Generic.List&lt;string&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity)" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Retrieve (partitionKey, rowkey, selectColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowkey" Type="System.String" />
        <Parameter Name="selectColumns" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="82cc9-132">Die Klasse der abzurufende Typ für die Entität.</span><span class="sxs-lookup"><span data-stu-id="82cc9-132">The class of type for the entity to retrieve.</span></span></typeparam>
        <param name="partitionKey"><span data-ttu-id="82cc9-133">Eine Zeichenfolge, die den Partitionsschlüssel der abzurufenden Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="82cc9-133">A string containing the partition key of the entity to retrieve.</span></span></param>
        <param name="rowkey"><span data-ttu-id="82cc9-134">Eine Zeichenfolge, die den Zeilenschlüssel der abzurufenden Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="82cc9-134">A string containing the row key of the entity to retrieve.</span></span></param>
        <param name="selectColumns"><span data-ttu-id="82cc9-135">Liste der Spaltennamen für die Projektion.</span><span class="sxs-lookup"><span data-stu-id="82cc9-135">List of column names for projection.</span></span></param>
        <summary>
            <span data-ttu-id="82cc9-136">Erstellt einen neuen tabellenvorgang, der den Inhalt der angegebenen Entität in einer Tabelle abruft.</span><span class="sxs-lookup"><span data-stu-id="82cc9-136">Creates a new table operation that retrieves the contents of the given entity in a table.</span></span>
            </summary>
        <returns><span data-ttu-id="82cc9-137">Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-137">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Retrieve&lt;TResult&gt; (string partitionKey, string rowkey, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, System.Collections.Generic.List&lt;string&gt; selectedColumns = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Retrieve&lt;TResult&gt;(string partitionKey, string rowkey, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class System.Collections.Generic.List`1&lt;string&gt; selectedColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Retrieve``1(System.String,System.String,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Retrieve(Of TResult) (partitionKey As String, rowkey As String, resolver As EntityResolver(Of TResult), Optional selectedColumns As List(Of String) = null) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Retrieve : string * string * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * System.Collections.Generic.List&lt;string&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Retrieve (partitionKey, rowkey, resolver, selectedColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowkey" Type="System.String" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="selectedColumns" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="82cc9-138">Der Rückgabetyp der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> die angegebene Entität aufgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="82cc9-138">The return type which the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will resolve the given entity to.</span></span></typeparam>
        <param name="partitionKey"><span data-ttu-id="82cc9-139">Eine Zeichenfolge, die den Partitionsschlüssel der abzurufenden Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="82cc9-139">A string containing the partition key of the entity to retrieve.</span></span></param>
        <param name="rowkey"><span data-ttu-id="82cc9-140">Eine Zeichenfolge, die den Zeilenschlüssel der abzurufenden Entität enthält.</span><span class="sxs-lookup"><span data-stu-id="82cc9-140">A string containing the row key of the entity to retrieve.</span></span></param>
        <param name="resolver"><span data-ttu-id="82cc9-141">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Implementierung zum projizieren der Entität als einen bestimmten Typ im Ergebnis abrufen.</span><span class="sxs-lookup"><span data-stu-id="82cc9-141">The <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> implementation to project the entity to retrieve as a particular type in the result.</span></span></param>
        <param name="selectedColumns"><span data-ttu-id="82cc9-142">Liste der Spaltennamen für die Projektion.</span><span class="sxs-lookup"><span data-stu-id="82cc9-142">List of column names for projection.</span></span></param>
        <summary>
            <span data-ttu-id="82cc9-143">Erstellt einen neuen tabellenvorgang, der den Inhalt der angegebenen Entität in einer Tabelle abruft.</span><span class="sxs-lookup"><span data-stu-id="82cc9-143">Creates a new table operation that retrieves the contents of the given entity in a table.</span></span>
            </summary>
        <returns><span data-ttu-id="82cc9-144">Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-144">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RotateEncryptionKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation RotateEncryptionKey (Microsoft.Azure.CosmosDB.Table.KeyRotationEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation RotateEncryptionKey(class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.RotateEncryptionKey(Microsoft.Azure.CosmosDB.Table.KeyRotationEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RotateEncryptionKey (entity As KeyRotationEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member RotateEncryptionKey : Microsoft.Azure.CosmosDB.Table.KeyRotationEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.RotateEncryptionKey entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="82cc9-145">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> Entität über seine gedreht Schlüssel zu verfügen.</span><span class="sxs-lookup"><span data-stu-id="82cc9-145">The <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> entity to have its key rotated.</span></span>  <span data-ttu-id="82cc9-146">Die Ausgabe eines Aufrufs zu einem Aufruf von "ExecuteQueryForKeyRotation()" muss sein.</span><span class="sxs-lookup"><span data-stu-id="82cc9-146">Must be the output of a call to an "ExecuteQueryForKeyRotation()" call.</span></span></param>
        <summary>
            <span data-ttu-id="82cc9-147">Erstellt einen neuen tabellenvorgang, der der angegebenen Entität in einer Tabelle der Inhaltsverschlüsselungsschlüssel dreht.</span><span class="sxs-lookup"><span data-stu-id="82cc9-147">Creates a new table operation that rotates the content encryption key of the given entity in a table.</span></span>
            </summary>
        <returns><span data-ttu-id="82cc9-148">Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="82cc9-148">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>