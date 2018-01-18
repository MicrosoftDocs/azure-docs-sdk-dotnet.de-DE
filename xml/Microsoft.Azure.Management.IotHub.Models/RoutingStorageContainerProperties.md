<Type Name="RoutingStorageContainerProperties" FullName="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties">
  <TypeSignature Language="C#" Value="public class RoutingStorageContainerProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RoutingStorageContainerProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RoutingStorageContainerProperties" />
  <TypeSignature Language="F#" Value="type RoutingStorageContainerProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ae44d-101">Die Eigenschaften im Zusammenhang mit einem speicherendpunkt für den Container.</span><span class="sxs-lookup"><span data-stu-id="ae44d-101">The properties related to a storage container endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingStorageContainerProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ae44d-102">Initialisiert eine neue Instanz der RoutingStorageContainerProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ae44d-102">Initializes a new instance of the RoutingStorageContainerProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingStorageContainerProperties (string connectionString, string name, string containerName, string subscriptionId = null, string resourceGroup = null, string fileNameFormat = null, Nullable&lt;int&gt; batchFrequencyInSeconds = null, Nullable&lt;int&gt; maxChunkSizeInBytes = null, string encoding = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string name, string containerName, string subscriptionId, string resourceGroup, string fileNameFormat, valuetype System.Nullable`1&lt;int32&gt; batchFrequencyInSeconds, valuetype System.Nullable`1&lt;int32&gt; maxChunkSizeInBytes, string encoding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String, name As String, containerName As String, Optional subscriptionId As String = null, Optional resourceGroup As String = null, Optional fileNameFormat As String = null, Optional batchFrequencyInSeconds As Nullable(Of Integer) = null, Optional maxChunkSizeInBytes As Nullable(Of Integer) = null, Optional encoding As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties : string * string * string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties (connectionString, name, containerName, subscriptionId, resourceGroup, fileNameFormat, batchFrequencyInSeconds, maxChunkSizeInBytes, encoding)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="fileNameFormat" Type="System.String" />
        <Parameter Name="batchFrequencyInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxChunkSizeInBytes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="encoding" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="ae44d-103">Die Verbindungszeichenfolge des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="ae44d-103">The connection string of the storage account.</span></span></param>
        <param name="name"><span data-ttu-id="ae44d-104">Der Name zum Identifizieren von diesem Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="ae44d-104">The name that identifies this endpoint.</span></span> <span data-ttu-id="ae44d-105">Der Name kann nur alphanumerische Zeichen, Punkte, Unterstriche, Bindestriche enthalten und besitzt eine maximale Länge von 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="ae44d-105">The name can only include alphanumeric characters, periods, underscores, hyphens and has a maximum length of 64 characters.</span></span> <span data-ttu-id="ae44d-106">Die folgenden Namen sind reserviert: Ereignisse, OperationsMonitoringEvents, FileNotifications, $default.</span><span class="sxs-lookup"><span data-stu-id="ae44d-106">The following names are reserved:  events, operationsMonitoringEvents, fileNotifications, $default.</span></span> <span data-ttu-id="ae44d-107">Endpunktnamen müssen über Endpunkttypen eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="ae44d-107">Endpoint names must be unique across endpoint types.</span></span></param>
        <param name="containerName"><span data-ttu-id="ae44d-108">Der Name des Speichercontainer im Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="ae44d-108">The name of storage container in the storage account.</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="ae44d-109">Die Abonnement-ID des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="ae44d-109">The subscription identifier of the storage account.</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="ae44d-110">Der Name der Ressourcengruppe des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="ae44d-110">The name of the resource group of the storage account.</span></span></param>
        <param name="fileNameFormat"><span data-ttu-id="ae44d-111">Name-Dateiformat für das Blob.</span><span class="sxs-lookup"><span data-stu-id="ae44d-111">File name format for the blob.</span></span> <span data-ttu-id="ae44d-112">Standardformat lautet {Iothub} / {partition} / {JJJJ} / {MM} / {TT} / {"hh"} / {mm}.</span><span class="sxs-lookup"><span data-stu-id="ae44d-112">Default format is {iothub}/{partition}/{YYYY}/{MM}/{DD}/{HH}/{mm}.</span></span> <span data-ttu-id="ae44d-113">Alle Parameter müssen angegeben werden, jedoch neu angeordnet werden können.</span><span class="sxs-lookup"><span data-stu-id="ae44d-113">All parameters are mandatory but can be reordered.</span></span></param>
        <param name="batchFrequencyInSeconds"><span data-ttu-id="ae44d-114">Das Zeitintervall mit der Blobs in den Speicher geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="ae44d-114">Time interval at which blobs are written to storage.</span></span> <span data-ttu-id="ae44d-115">Wert muss zwischen 60 und 720 Sekunden liegen.</span><span class="sxs-lookup"><span data-stu-id="ae44d-115">Value should be between 60 and 720 seconds.</span></span>
            <span data-ttu-id="ae44d-116">Standardwert ist 300 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="ae44d-116">Default value is 300 seconds.</span></span></param>
        <param name="maxChunkSizeInBytes"><span data-ttu-id="ae44d-117">Maximale Anzahl von Bytes für jedes Blob in den Speicher geschrieben.</span><span class="sxs-lookup"><span data-stu-id="ae44d-117">Maximum number of bytes for each blob written to storage.</span></span> <span data-ttu-id="ae44d-118">Wert muss zwischen 10485760(10MB) und 524288000(500MB) liegen.</span><span class="sxs-lookup"><span data-stu-id="ae44d-118">Value should be between 10485760(10MB) and 524288000(500MB).</span></span> <span data-ttu-id="ae44d-119">Standardwert ist 314572800(300MB).</span><span class="sxs-lookup"><span data-stu-id="ae44d-119">Default value is 314572800(300MB).</span></span></param>
        <param name="encoding"><span data-ttu-id="ae44d-120">Codierung, dient zum Serialisieren von Nachrichten auf Blobs.</span><span class="sxs-lookup"><span data-stu-id="ae44d-120">Encoding that is used to serialize messages to blobs.</span></span> <span data-ttu-id="ae44d-121">Unterstützte Werte sind "Avro" und "Avrodeflate".</span><span class="sxs-lookup"><span data-stu-id="ae44d-121">Supported values are 'avro' and 'avrodeflate'.</span></span> <span data-ttu-id="ae44d-122">Standardwert ist "Avro".</span><span class="sxs-lookup"><span data-stu-id="ae44d-122">Default value is 'avro'.</span></span></param>
        <summary>
            <span data-ttu-id="ae44d-123">Initialisiert eine neue Instanz der RoutingStorageContainerProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ae44d-123">Initializes a new instance of the RoutingStorageContainerProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchFrequencyInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BatchFrequencyInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BatchFrequencyInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.BatchFrequencyInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchFrequencyInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BatchFrequencyInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.BatchFrequencyInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="batchFrequencyInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ae44d-124">Ruft ab, oder legt ihn fest Zeitintervall, die mit der Blobs in den Speicher geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="ae44d-124">Gets or sets time interval at which blobs are written to storage.</span></span>
            <span data-ttu-id="ae44d-125">Wert muss zwischen 60 und 720 Sekunden liegen.</span><span class="sxs-lookup"><span data-stu-id="ae44d-125">Value should be between 60 and 720 seconds.</span></span> <span data-ttu-id="ae44d-126">Standardwert ist 300 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="ae44d-126">Default value is 300 seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ae44d-127">Ruft ab oder legt die Verbindungszeichenfolge des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="ae44d-127">Gets or sets the connection string of the storage account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerName">
      <MemberSignature Language="C#" Value="public string ContainerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.ContainerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerName As String" />
      <MemberSignature Language="F#" Value="member this.ContainerName : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.ContainerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ae44d-128">Ruft ab oder legt den Namen des Speichercontainers im Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="ae44d-128">Gets or sets the name of storage container in the storage account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encoding">
      <MemberSignature Language="C#" Value="public string Encoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Encoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.Encoding" />
      <MemberSignature Language="VB.NET" Value="Public Property Encoding As String" />
      <MemberSignature Language="F#" Value="member this.Encoding : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.Encoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encoding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ae44d-129">Ruft ab, oder legt sie fest, Codierung, die zum Serialisieren von Nachrichten in Blobs verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="ae44d-129">Gets or sets encoding that is used to serialize messages to blobs.</span></span>
            <span data-ttu-id="ae44d-130">Unterstützte Werte sind "Avro" und "Avrodeflate".</span><span class="sxs-lookup"><span data-stu-id="ae44d-130">Supported values are 'avro' and 'avrodeflate'.</span></span> <span data-ttu-id="ae44d-131">Standardwert ist "Avro".</span><span class="sxs-lookup"><span data-stu-id="ae44d-131">Default value is 'avro'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileNameFormat">
      <MemberSignature Language="C#" Value="public string FileNameFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileNameFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.FileNameFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property FileNameFormat As String" />
      <MemberSignature Language="F#" Value="member this.FileNameFormat : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.FileNameFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileNameFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ae44d-132">Ruft ab, oder legt ihn fest-Dateiformat für das Blob.</span><span class="sxs-lookup"><span data-stu-id="ae44d-132">Gets or sets file name format for the blob.</span></span> <span data-ttu-id="ae44d-133">Standardformat lautet {Iothub} / {partition} / {JJJJ} / {MM} / {TT} / {"hh"} / {mm}.</span><span class="sxs-lookup"><span data-stu-id="ae44d-133">Default format is {iothub}/{partition}/{YYYY}/{MM}/{DD}/{HH}/{mm}.</span></span> <span data-ttu-id="ae44d-134">Alle Parameter müssen angegeben werden, jedoch neu angeordnet werden können.</span><span class="sxs-lookup"><span data-stu-id="ae44d-134">All parameters are mandatory but can be reordered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxChunkSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxChunkSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxChunkSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.MaxChunkSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxChunkSizeInBytes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxChunkSizeInBytes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.MaxChunkSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxChunkSizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ae44d-135">Ruft ab oder legt die maximale Anzahl von Bytes für jedes Blob in den Speicher geschrieben.</span><span class="sxs-lookup"><span data-stu-id="ae44d-135">Gets or sets maximum number of bytes for each blob written to storage.</span></span> <span data-ttu-id="ae44d-136">Wert muss zwischen 10485760(10MB) und 524288000(500MB) liegen.</span><span class="sxs-lookup"><span data-stu-id="ae44d-136">Value should be between 10485760(10MB) and 524288000(500MB).</span></span> <span data-ttu-id="ae44d-137">Standardwert ist 314572800(300MB).</span><span class="sxs-lookup"><span data-stu-id="ae44d-137">Default value is 314572800(300MB).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ae44d-138">Ruft ab oder legt den Namen, der diesen Endpunkt identifiziert.</span><span class="sxs-lookup"><span data-stu-id="ae44d-138">Gets or sets the name that identifies this endpoint.</span></span> <span data-ttu-id="ae44d-139">Der Name kann nur alphanumerische Zeichen, Punkte, Unterstriche, Bindestriche enthalten und besitzt eine maximale Länge von 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="ae44d-139">The name can only include alphanumeric characters, periods, underscores, hyphens and has a maximum length of 64 characters.</span></span> <span data-ttu-id="ae44d-140">Die folgenden Namen sind reserviert: Ereignisse, OperationsMonitoringEvents, FileNotifications, $default.</span><span class="sxs-lookup"><span data-stu-id="ae44d-140">The following names are reserved:  events, operationsMonitoringEvents, fileNotifications, $default.</span></span> <span data-ttu-id="ae44d-141">Endpunktnamen müssen über Endpunkttypen eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="ae44d-141">Endpoint names must be unique across endpoint types.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ae44d-142">Ruft ab oder legt den Namen der Ressourcengruppe des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="ae44d-142">Gets or sets the name of the resource group of the storage account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ae44d-143">Ruft ab oder legt die Abonnement-ID des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="ae44d-143">Gets or sets the subscription identifier of the storage account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="routingStorageContainerProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ae44d-144">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="ae44d-144">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ae44d-145">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="ae44d-145">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>