<Type Name="BatchAccountCreateParameters" FullName="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters">
  <TypeSignature Language="C#" Value="public class BatchAccountCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchAccountCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchAccountCreateParameters" />
  <TypeSignature Language="F#" Value="type BatchAccountCreateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0069b-101">Parameter, die auf den Erstellungsvorgang angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="0069b-101">Parameters supplied to the Create operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters.#ctor" />
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
            <span data-ttu-id="0069b-102">Initialisiert eine neue Instanz der BatchAccountCreateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0069b-102">Initializes a new instance of the BatchAccountCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountCreateParameters (string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Batch.Models.AutoStorageBaseProperties autoStorage = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; poolAllocationMode = null, Microsoft.Azure.Management.Batch.Models.KeyVaultReference keyVaultReference = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Batch.Models.AutoStorageBaseProperties autoStorage, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; poolAllocationMode, class Microsoft.Azure.Management.Batch.Models.KeyVaultReference keyVaultReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Batch.Models.AutoStorageBaseProperties,System.Nullable{Microsoft.Azure.Management.Batch.Models.PoolAllocationMode},Microsoft.Azure.Management.Batch.Models.KeyVaultReference)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters : string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Batch.Models.AutoStorageBaseProperties * Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; * Microsoft.Azure.Management.Batch.Models.KeyVaultReference -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters" Usage="new Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters (location, tags, autoStorage, poolAllocationMode, keyVaultReference)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="autoStorage" Type="Microsoft.Azure.Management.Batch.Models.AutoStorageBaseProperties" />
        <Parameter Name="poolAllocationMode" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt;" />
        <Parameter Name="keyVaultReference" Type="Microsoft.Azure.Management.Batch.Models.KeyVaultReference" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="0069b-103">Die Region, in dem das Konto erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="0069b-103">The region in which to create the account.</span></span></param>
        <param name="tags"><span data-ttu-id="0069b-104">Die benutzerdefinierte Tags dem Konto zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="0069b-104">The user-specified tags associated with the account.</span></span></param>
        <param name="autoStorage"><span data-ttu-id="0069b-105">Die Eigenschaften im Zusammenhang mit dem Auto-Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="0069b-105">The properties related to the auto-storage account.</span></span></param>
        <param name="poolAllocationMode"><span data-ttu-id="0069b-106">Der Modus der Zuordnung zum Erstellen von Pools im Batch-Konto verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="0069b-106">The allocation mode to use for creating pools in the Batch account.</span></span></param>
        <param name="keyVaultReference"><span data-ttu-id="0069b-107">Ein Verweis auf das Azure-schlüsseltresor das Batch-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="0069b-107">A reference to the Azure key vault associated with the Batch account.</span></span></param>
        <summary>
            <span data-ttu-id="0069b-108">Initialisiert eine neue Instanz der BatchAccountCreateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0069b-108">Initializes a new instance of the BatchAccountCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoStorage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AutoStorageBaseProperties AutoStorage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.AutoStorageBaseProperties AutoStorage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters.AutoStorage" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoStorage As AutoStorageBaseProperties" />
      <MemberSignature Language="F#" Value="member this.AutoStorage : Microsoft.Azure.Management.Batch.Models.AutoStorageBaseProperties with get, set" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters.AutoStorage" />
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
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AutoStorageBaseProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0069b-109">Ruft ab oder legt die Eigenschaften im Zusammenhang mit dem Auto-Storage-Konto fest.</span><span class="sxs-lookup"><span data-stu-id="0069b-109">Gets or sets the properties related to the auto-storage account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.KeyVaultReference KeyVaultReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.KeyVaultReference KeyVaultReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters.KeyVaultReference" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultReference As KeyVaultReference" />
      <MemberSignature Language="F#" Value="member this.KeyVaultReference : Microsoft.Azure.Management.Batch.Models.KeyVaultReference with get, set" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters.KeyVaultReference" />
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
            <span data-ttu-id="0069b-110">Ruft ab oder legt einen Verweis auf das Azure-schlüsseltresor das Batch-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="0069b-110">Gets or sets a reference to the Azure key vault associated with the Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0069b-111">Ruft ab oder legt die Region, in der zum Erstellen des Kontos.</span><span class="sxs-lookup"><span data-stu-id="0069b-111">Gets or sets the region in which to create the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolAllocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; PoolAllocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; PoolAllocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters.PoolAllocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolAllocationMode As Nullable(Of PoolAllocationMode)" />
      <MemberSignature Language="F#" Value="member this.PoolAllocationMode : Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolAllocationMode&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters.PoolAllocationMode" />
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
            <span data-ttu-id="0069b-112">Abrufen oder festlegen den Zuordnung Modus zum Erstellen von Pools im Batch-Konto verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="0069b-112">Gets or sets the allocation mode to use for creating pools in the Batch account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0069b-113">Der Pool-Allocation-Modus wirkt sich auch wie Clients auf die Batch-Dienst-API authentifizieren können.</span><span class="sxs-lookup"><span data-stu-id="0069b-113">The pool allocation mode also affects how clients may authenticate to the Batch Service API.</span></span> <span data-ttu-id="0069b-114">Wenn der Modus BatchService ist, können Clients mithilfe von Zugriffsschlüsseln oder Azure Active Directory authentifizieren.</span><span class="sxs-lookup"><span data-stu-id="0069b-114">If the mode is BatchService, clients may authenticate using access keys or Azure Active Directory.</span></span> <span data-ttu-id="0069b-115">Wenn der Modus UserSubscription ist, müssen Clients mit Azure Active Directory verwenden.</span><span class="sxs-lookup"><span data-stu-id="0069b-115">If the mode is UserSubscription, clients must use Azure Active Directory.</span></span>
            <span data-ttu-id="0069b-116">Der Standardwert ist BatchService.</span><span class="sxs-lookup"><span data-stu-id="0069b-116">The default is BatchService.</span></span> <span data-ttu-id="0069b-117">Folgende Werte sind möglich: "BatchService", "UserSubscription"</span><span class="sxs-lookup"><span data-stu-id="0069b-117">Possible values include: 'BatchService', 'UserSubscription'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0069b-118">Ruft ab oder legt die benutzerdefinierte Tags, die dem Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="0069b-118">Gets or sets the user-specified tags associated with the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccountCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="batchAccountCreateParameters.Validate " />
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
            <span data-ttu-id="0069b-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="0069b-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0069b-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="0069b-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>