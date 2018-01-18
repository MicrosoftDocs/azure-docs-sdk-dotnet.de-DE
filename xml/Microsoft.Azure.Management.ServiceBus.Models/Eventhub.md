<Type Name="Eventhub" FullName="Microsoft.Azure.Management.ServiceBus.Models.Eventhub">
  <TypeSignature Language="C#" Value="public class Eventhub : Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Eventhub extends Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.Eventhub" />
  <TypeSignature Language="VB.NET" Value="Public Class Eventhub&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Eventhub = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ServiceBus.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0fd1d-101">Einzelnes Element in der Liste oder Abrufen eines Event Hubs-Vorgang</span><span class="sxs-lookup"><span data-stu-id="0fd1d-101">Single item in List or Get Event Hub operation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Eventhub ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.Eventhub.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0fd1d-102">Initialisiert eine neue Instanz der Eventhub-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0fd1d-102">Initializes a new instance of the Eventhub class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Eventhub (string id = null, string name = null, string type = null, System.Collections.Generic.IList&lt;string&gt; partitionIds = null, Nullable&lt;DateTime&gt; createdAt = null, Nullable&lt;DateTime&gt; updatedAt = null, Nullable&lt;long&gt; messageRetentionInDays = null, Nullable&lt;long&gt; partitionCount = null, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; status = null, Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription captureDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class System.Collections.Generic.IList`1&lt;string&gt; partitionIds, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt, valuetype System.Nullable`1&lt;int64&gt; messageRetentionInDays, valuetype System.Nullable`1&lt;int64&gt; partitionCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; status, class Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription captureDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.Eventhub.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.ServiceBus.Models.EntityStatus},Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.Eventhub : string * string * string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; * Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription -&gt; Microsoft.Azure.Management.ServiceBus.Models.Eventhub" Usage="new Microsoft.Azure.Management.ServiceBus.Models.Eventhub (id, name, type, partitionIds, createdAt, updatedAt, messageRetentionInDays, partitionCount, status, captureDescription)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="partitionIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="messageRetentionInDays" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="partitionCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt;" />
        <Parameter Name="captureDescription" Type="Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="0fd1d-103">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="0fd1d-103">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="0fd1d-104">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="0fd1d-104">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="0fd1d-105">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="0fd1d-105">Resource type</span></span></param>
        <param name="partitionIds"><span data-ttu-id="0fd1d-106">Aktuelle Anzahl der Shards auf dem Event Hub.</span><span class="sxs-lookup"><span data-stu-id="0fd1d-106">Current number of shards on the Event Hub.</span></span></param>
        <param name="createdAt"><span data-ttu-id="0fd1d-107">Genaue Uhrzeit der Erstellung des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="0fd1d-107">Exact time the Event Hub was created.</span></span></param>
        <param name="updatedAt"><span data-ttu-id="0fd1d-108">Die genaue Uhrzeit wurde die Nachricht aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="0fd1d-108">The exact time the message was updated.</span></span></param>
        <param name="messageRetentionInDays"><span data-ttu-id="0fd1d-109">Anzahl der Tage, die Ereignisse für dieses Ereignis-Hub Wert beibehalten muss 1 bis 7 Tage</span><span class="sxs-lookup"><span data-stu-id="0fd1d-109">Number of days to retain the events for this Event Hub, value should be 1 to 7 days</span></span></param>
        <param name="partitionCount"><span data-ttu-id="0fd1d-110">Anzahl der Partitionen, die für den Event Hub, zulässige Werte sind 1 bis 32 Partitionen.</span><span class="sxs-lookup"><span data-stu-id="0fd1d-110">Number of partitions created for the Event Hub, allowed values are from 1 to 32 partitions.</span></span></param>
        <param name="status"><span data-ttu-id="0fd1d-111">Listet die möglichen Werte für den Status des Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="0fd1d-111">Enumerates the possible values for the status of the Event Hub.</span></span> <span data-ttu-id="0fd1d-112">Folgende Werte sind möglich: 'Active', 'Deaktiviert', 'Wiederherstellen', "SendDisabled", "ReceiveDisabled", "Erstellen", "Löschen", "Umbenennen", "Unknown"</span><span class="sxs-lookup"><span data-stu-id="0fd1d-112">Possible values include: 'Active', 'Disabled', 'Restoring', 'SendDisabled', 'ReceiveDisabled', 'Creating', 'Deleting', 'Renaming', 'Unknown'</span></span></param>
        <param name="captureDescription"><span data-ttu-id="0fd1d-113">Eigenschaften von Capture-Beschreibung</span><span class="sxs-lookup"><span data-stu-id="0fd1d-113">Properties of capture description</span></span></param>
        <summary>
            <span data-ttu-id="0fd1d-114">Initialisiert eine neue Instanz der Eventhub-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0fd1d-114">Initializes a new instance of the Eventhub class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CaptureDescription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription CaptureDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription CaptureDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Eventhub.CaptureDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property CaptureDescription As CaptureDescription" />
      <MemberSignature Language="F#" Value="member this.CaptureDescription : Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Eventhub.CaptureDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.captureDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd1d-115">Ruft ab oder legt die Eigenschaften des Capture-Beschreibung</span><span class="sxs-lookup"><span data-stu-id="0fd1d-115">Gets or sets properties of capture description</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Eventhub.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.Eventhub.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd1d-116">Ruft die genaue Uhrzeit der Erstellung der Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="0fd1d-116">Gets exact time the Event Hub was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageRetentionInDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MessageRetentionInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MessageRetentionInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Eventhub.MessageRetentionInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageRetentionInDays As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MessageRetentionInDays : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Eventhub.MessageRetentionInDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.messageRetentionInDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd1d-117">Ruft ab oder legt die Anzahl der Tage, die für dieses Ereignis-Hub aufbewahrt Wert muss 1 bis 7 Tage</span><span class="sxs-lookup"><span data-stu-id="0fd1d-117">Gets or sets number of days to retain the events for this Event Hub, value should be 1 to 7 days</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PartitionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Eventhub.PartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PartitionCount : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Eventhub.PartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partitionCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd1d-118">Ruft ab oder legt die Anzahl der Partitionen, die für den Event Hub erstellt Werte reichen von 1 bis 32 Partitionen zulässig.</span><span class="sxs-lookup"><span data-stu-id="0fd1d-118">Gets or sets number of partitions created for the Event Hub, allowed values are from 1 to 32 partitions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PartitionIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PartitionIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Eventhub.PartitionIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PartitionIds : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.Eventhub.PartitionIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partitionIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd1d-119">Ruft die aktuelle Anzahl von Shards auf den Event Hub ab.</span><span class="sxs-lookup"><span data-stu-id="0fd1d-119">Gets current number of shards on the Event Hub.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Eventhub.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of EntityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Eventhub.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd1d-120">Listet die möglichen Werte für den Status des Event Hubs auf Ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="0fd1d-120">Gets or sets enumerates the possible values for the status of the Event Hub.</span></span> <span data-ttu-id="0fd1d-121">Folgende Werte sind möglich: 'Active', 'Deaktiviert', 'Wiederherstellen', "SendDisabled", "ReceiveDisabled", "Erstellen", "Löschen", "Umbenennen", "Unknown"</span><span class="sxs-lookup"><span data-stu-id="0fd1d-121">Possible values include: 'Active', 'Disabled', 'Restoring', 'SendDisabled', 'ReceiveDisabled', 'Creating', 'Deleting', 'Renaming', 'Unknown'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Eventhub.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.Eventhub.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.updatedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd1d-122">Ruft die genaue Uhrzeit, an die Nachricht aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="0fd1d-122">Gets the exact time the message was updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.Eventhub.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="eventhub.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0fd1d-123">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="0fd1d-123">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0fd1d-124">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="0fd1d-124">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>