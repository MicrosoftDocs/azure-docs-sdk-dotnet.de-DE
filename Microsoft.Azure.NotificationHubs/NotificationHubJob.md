<Type Name="NotificationHubJob" FullName="Microsoft.Azure.NotificationHubs.NotificationHubJob">
  <TypeSignature Language="C#" Value="public sealed class NotificationHubJob : Microsoft.Azure.NotificationHubs.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NotificationHubJob extends Microsoft.Azure.NotificationHubs.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NotificationHubJob&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type NotificationHubJob = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.EntityDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="NotificationHubJob", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="77607-101">Metadaten des NotificationHub-Auftrags</span><span class="sxs-lookup"><span data-stu-id="77607-101">Metadata of the NotificationHub Job</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotificationHubJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubJob.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionName">
      <MemberSignature Language="C#" Value="public string CollectionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CollectionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.CollectionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionName As String" />
      <MemberSignature Language="F#" Value="member this.CollectionName : string" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.CollectionName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.NotificationHubs.Messaging.IResourceDescription.CollectionName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-102">Ruft den Namen der Auflistung ab.</span><span class="sxs-lookup"><span data-stu-id="77607-102">Gets the name of the collection.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-103">Der Name der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="77607-103">The name of the collection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="CreatedAt", Order=1010)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-104">Ruft die Uhrzeit der Erstellung.</span><span class="sxs-lookup"><span data-stu-id="77607-104">Gets the created time.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-105">Die Uhrzeit der Erstellung.</span><span class="sxs-lookup"><span data-stu-id="77607-105">The created time.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failure">
      <MemberSignature Language="C#" Value="public string Failure { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Failure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.Failure" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Failure As String" />
      <MemberSignature Language="F#" Value="member this.Failure : string" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.Failure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Failure", Order=1008)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-106">Ruft den Fehler ab.</span><span class="sxs-lookup"><span data-stu-id="77607-106">Gets the failure.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-107">Der Fehler.</span><span class="sxs-lookup"><span data-stu-id="77607-107">The failure.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailuresFileName">
      <MemberSignature Language="C#" Value="public string FailuresFileName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailuresFileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.FailuresFileName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailuresFileName As String" />
      <MemberSignature Language="F#" Value="member this.FailuresFileName : string" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.FailuresFileName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-108">Ruft den Namen der Datei Fehler ab.</span><span class="sxs-lookup"><span data-stu-id="77607-108">Gets the name of the failures file.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-109">Der Name der Datei Fehlern.</span><span class="sxs-lookup"><span data-stu-id="77607-109">The name of the failures file.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportFileUri">
      <MemberSignature Language="C#" Value="public Uri ImportFileUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ImportFileUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.ImportFileUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ImportFileUri As Uri" />
      <MemberSignature Language="F#" Value="member this.ImportFileUri : Uri with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.ImportFileUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="ImportFileUri", Order=1006)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-110">Ruft ab oder legt die Importdatei URI.</span><span class="sxs-lookup"><span data-stu-id="77607-110">Gets or sets the import file URI.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-111">Die Importdatei URI.</span><span class="sxs-lookup"><span data-stu-id="77607-111">The import file URI.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.Dictionary&lt;string,string&gt; InputProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.Dictionary`2&lt;string, string&gt; InputProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.InputProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property InputProperties As Dictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.InputProperties : System.Collections.Generic.Dictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.InputProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="InputProperties", Order=1007)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-112">Ruft ab oder legt die Eingabeeigenschaften.</span><span class="sxs-lookup"><span data-stu-id="77607-112">Gets or sets the input properties.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-113">Die Eingabeeigenschaften.</span><span class="sxs-lookup"><span data-stu-id="77607-113">The input properties.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.JobId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="JobId", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-114">Ruft die Auftrags-ID ab.</span><span class="sxs-lookup"><span data-stu-id="77607-114">Gets the job identifier.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-115">Der Auftragsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="77607-115">The job identifier.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubJobType JobType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.NotificationHubs.NotificationHubJobType JobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.JobType" />
      <MemberSignature Language="VB.NET" Value="Public Property JobType As NotificationHubJobType" />
      <MemberSignature Language="F#" Value="member this.JobType : Microsoft.Azure.NotificationHubs.NotificationHubJobType with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.JobType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=true, IsRequired=true, Name="Type", Order=1003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubJobType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-116">Ruft ab oder legt den Typ des Auftrags fest.</span><span class="sxs-lookup"><span data-stu-id="77607-116">Gets or sets the type of the job.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-117">Der Typ des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="77607-117">The type of the job.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputContainerUri">
      <MemberSignature Language="C#" Value="public Uri OutputContainerUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri OutputContainerUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.OutputContainerUri" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputContainerUri As Uri" />
      <MemberSignature Language="F#" Value="member this.OutputContainerUri : Uri with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.OutputContainerUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=true, Name="OutputContainerUri", Order=1005)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-118">Abrufen oder Festlegen der Ausgabecontainer URI.</span><span class="sxs-lookup"><span data-stu-id="77607-118">Gets or sets the output container URI.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-119">Die Ausgabecontainer-URI.</span><span class="sxs-lookup"><span data-stu-id="77607-119">The output container URI.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputFileName">
      <MemberSignature Language="C#" Value="public string OutputFileName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputFileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.OutputFileName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutputFileName As String" />
      <MemberSignature Language="F#" Value="member this.OutputFileName : string" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.OutputFileName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-120">Ruft den Namen der Ausgabedatei ab.</span><span class="sxs-lookup"><span data-stu-id="77607-120">Gets the name of the output file.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-121">Der Name der Ausgabedatei.</span><span class="sxs-lookup"><span data-stu-id="77607-121">The name of the output file.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.Dictionary&lt;string,string&gt; OutputProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.Dictionary`2&lt;string, string&gt; OutputProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.OutputProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutputProperties As Dictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.OutputProperties : System.Collections.Generic.Dictionary&lt;string, string&gt;" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.OutputProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="OutputProperties", Order=1009)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-122">Ruft die Ausgabeeigenschaften ab.</span><span class="sxs-lookup"><span data-stu-id="77607-122">Gets the output properties.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-123">Die Ausgabeeigenschaften.</span><span class="sxs-lookup"><span data-stu-id="77607-123">The output properties.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Progress">
      <MemberSignature Language="C#" Value="public decimal Progress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Decimal Progress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.Progress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Progress As Decimal" />
      <MemberSignature Language="F#" Value="member this.Progress : decimal" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.Progress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Progress", Order=1002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Decimal</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-124">Ruft den Status ab.</span><span class="sxs-lookup"><span data-stu-id="77607-124">Gets the progress.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-125">Der Status.</span><span class="sxs-lookup"><span data-stu-id="77607-125">The progress.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubJobStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.NotificationHubs.NotificationHubJobStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As NotificationHubJobStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.NotificationHubs.NotificationHubJobStatus" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Status", Order=1004)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubJobStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-126">Ruft den Status ab.</span><span class="sxs-lookup"><span data-stu-id="77607-126">Gets the status.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-127">Der Status.</span><span class="sxs-lookup"><span data-stu-id="77607-127">The status.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubJob.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.Azure.NotificationHubs.NotificationHubJob.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="UpdatedAt", Order=1011)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77607-128">Ruft die aktualisierte Zeit ab.</span><span class="sxs-lookup"><span data-stu-id="77607-128">Gets the updated time.</span></span>
            </summary>
        <value>
            <span data-ttu-id="77607-129">Die aktualisierte Uhrzeit.</span><span class="sxs-lookup"><span data-stu-id="77607-129">The updated time.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>