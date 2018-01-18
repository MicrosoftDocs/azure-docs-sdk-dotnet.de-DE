<Type Name="HDInsightOnDemandLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService">
  <TypeSignature Language="C#" Value="public class HDInsightOnDemandLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HDInsightOnDemandLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class HDInsightOnDemandLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type HDInsightOnDemandLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("HDInsightOnDemand")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b5cea-101">Die Eigenschaften für den HDInsight-LinkedService.</span><span class="sxs-lookup"><span data-stu-id="b5cea-101">The properties for the HDInsight linkedService.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightOnDemandLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-102">Initialisiert eine neue Instanz der HDInsightOnDemandLinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b5cea-102">Initializes a new instance of the HDInsightOnDemandLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightOnDemandLinkedService (int clusterSize, TimeSpan timeToLive, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 clusterSize, valuetype System.TimeSpan timeToLive, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.#ctor(System.Int32,System.TimeSpan,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clusterSize As Integer, timeToLive As TimeSpan, linkedServiceName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService : int * TimeSpan * string -&gt; Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService (clusterSize, timeToLive, linkedServiceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clusterSize" Type="System.Int32" />
        <Parameter Name="timeToLive" Type="System.TimeSpan" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clusterSize">To be added.</param>
        <param name="timeToLive">To be added.</param>
        <param name="linkedServiceName">To be added.</param>
        <summary>
            <span data-ttu-id="b5cea-103">Initialisiert eine neue Instanz der HDInsightOnDemandLinkedService-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="b5cea-103">Initializes a new instance of the HDInsightOnDemandLinkedService class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalLinkedServiceNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AdditionalLinkedServiceNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AdditionalLinkedServiceNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.AdditionalLinkedServiceNames" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalLinkedServiceNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AdditionalLinkedServiceNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.AdditionalLinkedServiceNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="b5cea-104">Optional.</span></span> <span data-ttu-id="b5cea-105">Geben Sie zusätzliche Azure-Speicherkonten, die vom Cluster zugänglich sein müssen.</span><span class="sxs-lookup"><span data-stu-id="b5cea-105">Specify additional Azure storage accounts that need to be accessible from the cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterSize">
      <MemberSignature Language="C#" Value="public int ClusterSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ClusterSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.ClusterSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ClusterSize : int with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.ClusterSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b5cea-106">Required.</span></span> <span data-ttu-id="b5cea-107">Größe der HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="b5cea-107">HDInsight cluster size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterType">
      <MemberSignature Language="C#" Value="public string ClusterType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.ClusterType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterType As String" />
      <MemberSignature Language="F#" Value="member this.ClusterType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.ClusterType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-108">Ruft ab oder legt die Konfiguration für den HDInsight-Cluster.</span><span class="sxs-lookup"><span data-stu-id="b5cea-108">Gets or sets the flavor for the HDInsight cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CoreConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; CoreConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; CoreConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.CoreConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CoreConfiguration As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.CoreConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.CoreConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-109">Optional.</span><span class="sxs-lookup"><span data-stu-id="b5cea-109">Optional.</span></span> <span data-ttu-id="b5cea-110">Ermöglicht Benutzer die Standardwerte für die zentrale Konfiguration überschrieben.</span><span class="sxs-lookup"><span data-stu-id="b5cea-110">Allows user to override default values for core configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataNodeSize">
      <MemberSignature Language="C#" Value="public string DataNodeSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataNodeSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.DataNodeSize" />
      <MemberSignature Language="VB.NET" Value="Public Property DataNodeSize As String" />
      <MemberSignature Language="F#" Value="member this.DataNodeSize : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.DataNodeSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-111">Ruft ab oder legt die Größe des vom Datenknoten.</span><span class="sxs-lookup"><span data-stu-id="b5cea-111">Gets or sets the size of the Data Node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HBaseConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; HBaseConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; HBaseConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.HBaseConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property HBaseConfiguration As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.HBaseConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.HBaseConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-112">Optional.</span><span class="sxs-lookup"><span data-stu-id="b5cea-112">Optional.</span></span> <span data-ttu-id="b5cea-113">Ermöglicht Benutzer, die Standardwerte für die HBase-Konfiguration zu überschreiben.</span><span class="sxs-lookup"><span data-stu-id="b5cea-113">Allows user to override default values for HBase configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HcatalogLinkedServiceName">
      <MemberSignature Language="C#" Value="public string HcatalogLinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HcatalogLinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.HcatalogLinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property HcatalogLinkedServiceName As String" />
      <MemberSignature Language="F#" Value="member this.HcatalogLinkedServiceName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.HcatalogLinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-114">Der Name des mit Azure SQL verknüpften Diensts, der auf die HCatalog-Datenbank verweist.</span><span class="sxs-lookup"><span data-stu-id="b5cea-114">The name of Azure SQL linked service that point to the HCatalog database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HdfsConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; HdfsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; HdfsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.HdfsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property HdfsConfiguration As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.HdfsConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.HdfsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-115">Optional.</span><span class="sxs-lookup"><span data-stu-id="b5cea-115">Optional.</span></span> <span data-ttu-id="b5cea-116">Ermöglicht Benutzer, die Standardwerte für die Konfiguration von HDFS zu überschreiben.</span><span class="sxs-lookup"><span data-stu-id="b5cea-116">Allows user to override default values for HDFS configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HeadNodeSize">
      <MemberSignature Language="C#" Value="public string HeadNodeSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HeadNodeSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.HeadNodeSize" />
      <MemberSignature Language="VB.NET" Value="Public Property HeadNodeSize As String" />
      <MemberSignature Language="F#" Value="member this.HeadNodeSize : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.HeadNodeSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-117">Ruft ab oder legt die Größe des Hauptknotens fest.</span><span class="sxs-lookup"><span data-stu-id="b5cea-117">Gets or sets the size of the Head Node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HiveConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; HiveConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; HiveConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.HiveConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property HiveConfiguration As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.HiveConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.HiveConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-118">Optional.</span><span class="sxs-lookup"><span data-stu-id="b5cea-118">Optional.</span></span> <span data-ttu-id="b5cea-119">Ermöglicht Benutzer, die Standardwerte für die HIVE-Konfiguration zu überschreiben.</span><span class="sxs-lookup"><span data-stu-id="b5cea-119">Allows user to override default values for HIVE configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HiveCustomLibrariesContainer">
      <MemberSignature Language="C#" Value="public string HiveCustomLibrariesContainer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HiveCustomLibrariesContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.HiveCustomLibrariesContainer" />
      <MemberSignature Language="VB.NET" Value="Public Property HiveCustomLibrariesContainer As String" />
      <MemberSignature Language="F#" Value="member this.HiveCustomLibrariesContainer : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.HiveCustomLibrariesContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-120">Optional.</span><span class="sxs-lookup"><span data-stu-id="b5cea-120">Optional.</span></span> <span data-ttu-id="b5cea-121">Der Name des Blob-Containers, die benutzerdefinierte Jar-Dateien für die Nutzung der Struktur enthält.</span><span class="sxs-lookup"><span data-stu-id="b5cea-121">The name of the blob container that contains custom jar files for HIVE consumption.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServiceName">
      <MemberSignature Language="C#" Value="public string LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServiceName As String" />
      <MemberSignature Language="F#" Value="member this.LinkedServiceName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.LinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b5cea-122">Required.</span></span> <span data-ttu-id="b5cea-123">Name des Speicher-Diensts.</span><span class="sxs-lookup"><span data-stu-id="b5cea-123">Storage service name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MapReduceConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; MapReduceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; MapReduceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.MapReduceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property MapReduceConfiguration As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.MapReduceConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.MapReduceConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-124">Optional.</span><span class="sxs-lookup"><span data-stu-id="b5cea-124">Optional.</span></span> <span data-ttu-id="b5cea-125">Ermöglicht Benutzer, die Standardwerte für die MapReduce-Konfiguration zu überschreiben.</span><span class="sxs-lookup"><span data-stu-id="b5cea-125">Allows user to override default values for MapReduce configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OozieConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; OozieConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; OozieConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.OozieConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property OozieConfiguration As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.OozieConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.OozieConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-126">Optional.</span><span class="sxs-lookup"><span data-stu-id="b5cea-126">Optional.</span></span> <span data-ttu-id="b5cea-127">Ermöglicht Benutzer, die Standardwerte für Oozie-Konfiguration zu überschreiben.</span><span class="sxs-lookup"><span data-stu-id="b5cea-127">Allows user to override default values for Oozie configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public string OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As String" />
      <MemberSignature Language="F#" Value="member this.OsType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-128">Ruft ab oder legt den Typ des Betriebssystems auf Clusterknoten installiert.</span><span class="sxs-lookup"><span data-stu-id="b5cea-128">Gets or sets the type of operating system installed on cluster nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaGeneration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.HDInsightSchemaGenerationProperties SchemaGeneration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.HDInsightSchemaGenerationProperties SchemaGeneration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.SchemaGeneration" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaGeneration As HDInsightSchemaGenerationProperties" />
      <MemberSignature Language="F#" Value="member this.SchemaGeneration : Microsoft.Azure.Management.DataFactories.Models.HDInsightSchemaGenerationProperties with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.SchemaGeneration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.HDInsightSchemaGenerationProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-129">Definieren Sie, welche Optionen für Erstellen/Ändern der Tabelle für eine Eingabe und Ausgabe von Datasets für eine HDInsight-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="b5cea-129">Define what options to use for generating/altering table for an input and output Datasets for an HDInsight activity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SparkConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; SparkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; SparkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.SparkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property SparkConfiguration As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.SparkConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.SparkConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-130">Die von diesem HDInsight-Cluster Spark-Dienstkonfiguration.</span><span class="sxs-lookup"><span data-stu-id="b5cea-130">The Spark service configuration of this HDInsight cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SshPassword">
      <MemberSignature Language="C#" Value="public string SshPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SshPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.SshPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property SshPassword As String" />
      <MemberSignature Language="F#" Value="member this.SshPassword : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.SshPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-131">Ruft ab oder legt die SSH-Kennwort fest.</span><span class="sxs-lookup"><span data-stu-id="b5cea-131">Gets or sets SSH password.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SshPublicKey">
      <MemberSignature Language="C#" Value="public string SshPublicKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SshPublicKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.SshPublicKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SshPublicKey As String" />
      <MemberSignature Language="F#" Value="member this.SshPublicKey : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.SshPublicKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-132">Ruft ab oder legt den öffentlichen Schlüssel für SSH verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="b5cea-132">Gets or sets the public key to be used for SSH.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SshUserName">
      <MemberSignature Language="C#" Value="public string SshUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SshUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.SshUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property SshUserName As String" />
      <MemberSignature Language="F#" Value="member this.SshUserName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.SshUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-133">Ruft ab oder legt die SSH-Benutzername.</span><span class="sxs-lookup"><span data-stu-id="b5cea-133">Gets or sets SSH user name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StormConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; StormConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; StormConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.StormConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property StormConfiguration As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.StormConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.StormConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-134">Optional.</span><span class="sxs-lookup"><span data-stu-id="b5cea-134">Optional.</span></span> <span data-ttu-id="b5cea-135">Ermöglicht Benutzer, die Standardwerte für die Storm-Konfiguration zu überschreiben.</span><span class="sxs-lookup"><span data-stu-id="b5cea-135">Allows user to override default values for Storm configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b5cea-136">Required.</span></span> <span data-ttu-id="b5cea-137">Die Gültigkeitsdauer (Time To Live, TTL).</span><span class="sxs-lookup"><span data-stu-id="b5cea-137">Time to live.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-138">Optional.</span><span class="sxs-lookup"><span data-stu-id="b5cea-138">Optional.</span></span> <span data-ttu-id="b5cea-139">HDInsight-Version.</span><span class="sxs-lookup"><span data-stu-id="b5cea-139">HDInsight version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="YarnConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; YarnConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; YarnConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.YarnConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property YarnConfiguration As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.YarnConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.YarnConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-140">Optional.</span><span class="sxs-lookup"><span data-stu-id="b5cea-140">Optional.</span></span> <span data-ttu-id="b5cea-141">Ermöglicht Benutzer, die Standardwerte für die YARN-Konfiguration zu überschreiben.</span><span class="sxs-lookup"><span data-stu-id="b5cea-141">Allows user to override default values for YARN configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ZookeeperNodeSize">
      <MemberSignature Language="C#" Value="public string ZookeeperNodeSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ZookeeperNodeSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.ZookeeperNodeSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ZookeeperNodeSize As String" />
      <MemberSignature Language="F#" Value="member this.ZookeeperNodeSize : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightOnDemandLinkedService.ZookeeperNodeSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5cea-142">Ruft ab oder legt die Größe des Knotens Zookeeper fest.</span><span class="sxs-lookup"><span data-stu-id="b5cea-142">Gets or sets the size of the Zookeeper Node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>