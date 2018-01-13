<Type Name="BatchAccount" FullName="Microsoft.Azure.Management.Batch.Models.BatchAccount">
  <TypeSignature Language="C#" Value="public class BatchAccount : Microsoft.Azure.Management.Batch.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchAccount extends Microsoft.Azure.Management.Batch.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.BatchAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchAccount&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type BatchAccount = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Batch.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="70b55-101">Enthält Informationen zu einem Azure Batch-Konto an.</span><span class="sxs-lookup"><span data-stu-id="70b55-101">Contains information about an Azure Batch account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="70b55-102">Initialisiert eine neue Instanz der BatchAccount-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70b55-102">Initializes a new instance of the BatchAccount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccount (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string accountEndpoint = null, Microsoft.Azure.Management.Batch.Models.ProvisioningState provisioningState = Microsoft.Azure.Management.Batch.Models.ProvisioningState.Invalid, Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; poolAllocationMode = null, Microsoft.Azure.Management.Batch.Models.KeyVaultReference keyVaultReference = null, Microsoft.Azure.Management.Batch.Models.AutoStorageProperties autoStorage = null, int dedicatedCoreQuota = 0, int lowPriorityCoreQuota = 0, int poolQuota = 0, int activeJobAndJobScheduleQuota = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string accountEndpoint, valuetype Microsoft.Azure.Management.Batch.Models.ProvisioningState provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; poolAllocationMode, class Microsoft.Azure.Management.Batch.Models.KeyVaultReference keyVaultReference, class Microsoft.Azure.Management.Batch.Models.AutoStorageProperties autoStorage, int32 dedicatedCoreQuota, int32 lowPriorityCoreQuota, int32 poolQuota, int32 activeJobAndJobScheduleQuota) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccount.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.Batch.Models.ProvisioningState,System.Nullable{Microsoft.Azure.Management.Batch.Models.PoolAllocationMode},Microsoft.Azure.Management.Batch.Models.KeyVaultReference,Microsoft.Azure.Management.Batch.Models.AutoStorageProperties,System.Int32,System.Int32,System.Int32,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.BatchAccount : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.Batch.Models.ProvisioningState * Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; * Microsoft.Azure.Management.Batch.Models.KeyVaultReference * Microsoft.Azure.Management.Batch.Models.AutoStorageProperties * int * int * int * int -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccount" Usage="new Microsoft.Azure.Management.Batch.Models.BatchAccount (id, name, type, location, tags, accountEndpoint, provisioningState, poolAllocationMode, keyVaultReference, autoStorage, dedicatedCoreQuota, lowPriorityCoreQuota, poolQuota, activeJobAndJobScheduleQuota)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accountEndpoint" Type="System.String" />
        <Parameter Name="provisioningState" Type="Microsoft.Azure.Management.Batch.Models.ProvisioningState" />
        <Parameter Name="poolAllocationMode" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt;" />
        <Parameter Name="keyVaultReference" Type="Microsoft.Azure.Management.Batch.Models.KeyVaultReference" />
        <Parameter Name="autoStorage" Type="Microsoft.Azure.Management.Batch.Models.AutoStorageProperties" />
        <Parameter Name="dedicatedCoreQuota" Type="System.Int32" />
        <Parameter Name="lowPriorityCoreQuota" Type="System.Int32" />
        <Parameter Name="poolQuota" Type="System.Int32" />
        <Parameter Name="activeJobAndJobScheduleQuota" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="70b55-103">Die ID der Ressource.</span><span class="sxs-lookup"><span data-stu-id="70b55-103">The ID of the resource.</span></span></param>
        <param name="name"><span data-ttu-id="70b55-104">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="70b55-104">The name of the resource.</span></span></param>
        <param name="type"><span data-ttu-id="70b55-105">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="70b55-105">The type of the resource.</span></span></param>
        <param name="location"><span data-ttu-id="70b55-106">Der Speicherort der Ressource.</span><span class="sxs-lookup"><span data-stu-id="70b55-106">The location of the resource.</span></span></param>
        <param name="tags"><span data-ttu-id="70b55-107">Die Tags der Ressource.</span><span class="sxs-lookup"><span data-stu-id="70b55-107">The tags of the resource.</span></span></param>
        <param name="accountEndpoint"><span data-ttu-id="70b55-108">Der Konto-Endpunkt für die Interaktion mit der Batch-Dienst verwendet.</span><span class="sxs-lookup"><span data-stu-id="70b55-108">The account endpoint used to interact with the Batch service.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="70b55-109">Der Bereitstellungsstatus der Ressource.</span><span class="sxs-lookup"><span data-stu-id="70b55-109">The provisioned state of the resource.</span></span> <span data-ttu-id="70b55-110">Folgende Werte sind möglich: "Ungültig", "erstellen", "Löschen", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="70b55-110">Possible values include: 'Invalid', 'Creating', 'Deleting', 'Succeeded', 'Failed', 'Cancelled'</span></span></param>
        <param name="poolAllocationMode"><span data-ttu-id="70b55-111">Der Modus der Zuordnung zum Erstellen von Pools im Batch-Konto verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="70b55-111">The allocation mode to use for creating pools in the Batch account.</span></span></param>
        <param name="keyVaultReference"><span data-ttu-id="70b55-112">Ein Verweis auf das Azure-schlüsseltresor das Batch-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="70b55-112">A reference to the Azure key vault associated with the Batch account.</span></span></param>
        <param name="autoStorage"><span data-ttu-id="70b55-113">Die Eigenschaften und den Status jedes Auto-Storage-Kontos das Batch-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="70b55-113">The properties and status of any auto-storage account associated with the Batch account.</span></span></param>
        <param name="dedicatedCoreQuota"><span data-ttu-id="70b55-114">Das Kontingent des dedizierten Kern für dieses Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="70b55-114">The dedicated core quota for this Batch account.</span></span></param>
        <param name="lowPriorityCoreQuota"><span data-ttu-id="70b55-115">Die mit niedriger Priorität kernkontingent für dieses Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="70b55-115">The low-priority core quota for this Batch account.</span></span></param>
        <param name="poolQuota"><span data-ttu-id="70b55-116">Das poolkontingent für dieses Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="70b55-116">The pool quota for this Batch account.</span></span></param>
        <param name="activeJobAndJobScheduleQuota"><span data-ttu-id="70b55-117">Die aktiven Auftrag und die Auftrag-Zeitplan-Kontingent für dieses Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="70b55-117">The active job and job schedule quota for this Batch account.</span></span></param>
        <summary>
            <span data-ttu-id="70b55-118">Initialisiert eine neue Instanz der BatchAccount-Klasse.</span><span class="sxs-lookup"><span data-stu-id="70b55-118">Initializes a new instance of the BatchAccount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountEndpoint">
      <MemberSignature Language="C#" Value="public string AccountEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.AccountEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.AccountEndpoint : string" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.AccountEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70b55-119">Ruft die Interaktion mit der Batch-Dienst-Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="70b55-119">Gets the account endpoint used to interact with the Batch service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveJobAndJobScheduleQuota">
      <MemberSignature Language="C#" Value="public int ActiveJobAndJobScheduleQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ActiveJobAndJobScheduleQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.ActiveJobAndJobScheduleQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveJobAndJobScheduleQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.ActiveJobAndJobScheduleQuota : int" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.ActiveJobAndJobScheduleQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activeJobAndJobScheduleQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70b55-120">Ruft den aktiven Auftrag und den Auftrag-Zeitplan-Kontingent für dieses Batch-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="70b55-120">Gets the active job and job schedule quota for this Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoStorage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AutoStorageProperties AutoStorage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.AutoStorageProperties AutoStorage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.AutoStorage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoStorage As AutoStorageProperties" />
      <MemberSignature Language="F#" Value="member this.AutoStorage : Microsoft.Azure.Management.Batch.Models.AutoStorageProperties" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.AutoStorage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoStorage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AutoStorageProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70b55-121">Ruft die Eigenschaften und den Status jedes Auto-Storage-Kontos das Batch-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="70b55-121">Gets the properties and status of any auto-storage account associated with the Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DedicatedCoreQuota">
      <MemberSignature Language="C#" Value="public int DedicatedCoreQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DedicatedCoreQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.DedicatedCoreQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DedicatedCoreQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.DedicatedCoreQuota : int" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.DedicatedCoreQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dedicatedCoreQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70b55-122">Ruft die dedizierten kernkontingent für dieses Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="70b55-122">Gets the dedicated core quota for this Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.KeyVaultReference KeyVaultReference { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.KeyVaultReference KeyVaultReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.KeyVaultReference" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyVaultReference As KeyVaultReference" />
      <MemberSignature Language="F#" Value="member this.KeyVaultReference : Microsoft.Azure.Management.Batch.Models.KeyVaultReference" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.KeyVaultReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keyVaultReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.KeyVaultReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70b55-123">Ruft einen Verweis auf das Azure-schlüsseltresor das Batch-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="70b55-123">Gets a reference to the Azure key vault associated with the Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LowPriorityCoreQuota">
      <MemberSignature Language="C#" Value="public int LowPriorityCoreQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LowPriorityCoreQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.LowPriorityCoreQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LowPriorityCoreQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.LowPriorityCoreQuota : int" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.LowPriorityCoreQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lowPriorityCoreQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70b55-124">Ruft das Kontingent der Kerne mit niedriger Priorität für dieses Batch-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="70b55-124">Gets the low-priority core quota for this Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolAllocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; PoolAllocationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; PoolAllocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.PoolAllocationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolAllocationMode As Nullable(Of PoolAllocationMode)" />
      <MemberSignature Language="F#" Value="member this.PoolAllocationMode : Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt;" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.PoolAllocationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.poolAllocationMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70b55-125">Ruft den Allocation-Modus zum Erstellen von Pools im Batch-Konto verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="70b55-125">Gets the allocation mode to use for creating pools in the Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="70b55-126">Folgende Werte sind möglich: "BatchService", "UserSubscription"</span><span class="sxs-lookup"><span data-stu-id="70b55-126">Possible values include: 'BatchService', 'UserSubscription'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolQuota">
      <MemberSignature Language="C#" Value="public int PoolQuota { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PoolQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.PoolQuota" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolQuota As Integer" />
      <MemberSignature Language="F#" Value="member this.PoolQuota : int" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.PoolQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.poolQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70b55-127">Ruft das poolkontingent für dieses Batch-Konto ab.</span><span class="sxs-lookup"><span data-stu-id="70b55-127">Gets the pool quota for this Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.ProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.ProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccount.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As ProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.Batch.Models.ProvisioningState" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccount.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70b55-128">Ruft den Bereitstellungsstatus der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="70b55-128">Gets the provisioned state of the resource.</span></span> <span data-ttu-id="70b55-129">Folgende Werte sind möglich: "Ungültig", "erstellen", "Löschen", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="70b55-129">Possible values include: 'Invalid', 'Creating', 'Deleting', 'Succeeded', 'Failed', 'Cancelled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccount.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="batchAccount.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="70b55-130">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="70b55-130">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="70b55-131">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="70b55-131">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>