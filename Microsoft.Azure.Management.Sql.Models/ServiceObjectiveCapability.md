<Type Name="ServiceObjectiveCapability" FullName="Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability">
  <TypeSignature Language="C#" Value="public class ServiceObjectiveCapability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceObjectiveCapability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceObjectiveCapability" />
  <TypeSignature Language="F#" Value="type ServiceObjectiveCapability = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="9dbe4-101">Die Funktion für den Dienst-Ziele.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-101">The service objectives capability.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceObjectiveCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9dbe4-102">Initialisiert eine neue Instanz der ServiceObjectiveCapability-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-102">Initializes a new instance of the ServiceObjectiveCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceObjectiveCapability (string name = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.PerformanceLevelUnit&gt; unit = null, Nullable&lt;int&gt; value = null, Guid id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; supportedMaxSizes = null, Microsoft.Azure.Management.Sql.Models.MaxSizeCapability includedMaxSize = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.PerformanceLevelUnit&gt; unit, valuetype System.Nullable`1&lt;int32&gt; value, valuetype System.Guid id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; supportedMaxSizes, class Microsoft.Azure.Management.Sql.Models.MaxSizeCapability includedMaxSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.CapabilityStatus},System.Nullable{Microsoft.Azure.Management.Sql.Models.PerformanceLevelUnit},System.Nullable{System.Int32},System.Guid,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.MaxSizeCapability},Microsoft.Azure.Management.Sql.Models.MaxSizeCapability)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional status As Nullable(Of CapabilityStatus) = null, Optional unit As Nullable(Of PerformanceLevelUnit) = null, Optional value As Nullable(Of Integer) = null, Optional id As Guid = null, Optional supportedMaxSizes As IList(Of MaxSizeCapability) = null, Optional includedMaxSize As MaxSizeCapability = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability : string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Models.PerformanceLevelUnit&gt; * Nullable&lt;int&gt; * Guid * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; * Microsoft.Azure.Management.Sql.Models.MaxSizeCapability -&gt; Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability" Usage="new Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability (name, status, unit, value, id, supportedMaxSizes, includedMaxSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" />
        <Parameter Name="unit" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.PerformanceLevelUnit&gt;" />
        <Parameter Name="value" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="id" Type="System.Guid" />
        <Parameter Name="supportedMaxSizes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt;" />
        <Parameter Name="includedMaxSize" Type="Microsoft.Azure.Management.Sql.Models.MaxSizeCapability" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="9dbe4-103">Die Dienst-SLO-Name.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-103">The service objective name.</span></span></param>
        <param name="status"><span data-ttu-id="9dbe4-104">Der Status des dienstziels.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-104">The status of the service objective.</span></span> <span data-ttu-id="9dbe4-105">Folgende Werte sind möglich: "Sichtbar", "Verfügbar", "Default", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="9dbe4-105">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span></param>
        <param name="unit"><span data-ttu-id="9dbe4-106">Unit-Typ verwendet, um Servicelevel-Ziel Leistung zu messen.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-106">Unit type used to measure service objective performance level.</span></span> <span data-ttu-id="9dbe4-107">Folgende Werte sind möglich: "DTU"</span><span class="sxs-lookup"><span data-stu-id="9dbe4-107">Possible values include: 'DTU'</span></span></param>
        <param name="value"><span data-ttu-id="9dbe4-108">Leistung-Level-Wert.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-108">Performance level value.</span></span></param>
        <param name="id"><span data-ttu-id="9dbe4-109">Die eindeutige ID des dienstziels.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-109">The unique ID of the service objective.</span></span></param>
        <param name="supportedMaxSizes"><span data-ttu-id="9dbe4-110">Die Liste der unterstützten maximale Datenbankgröße für dieses dienstziel.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-110">The list of supported maximum database sizes for this service objective.</span></span></param>
        <param name="includedMaxSize"><span data-ttu-id="9dbe4-111">Die enthalten (free) maximale Größe für diese SLO.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-111">The included (free) max size for this service level objective.</span></span></param>
        <summary>
            <span data-ttu-id="9dbe4-112">Initialisiert eine neue Instanz der ServiceObjectiveCapability-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-112">Initializes a new instance of the ServiceObjectiveCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public Guid Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Guid" />
      <MemberSignature Language="F#" Value="member this.Id : Guid" Usage="Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dbe4-113">Ruft die eindeutige ID des dienstziels.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-113">Gets the unique ID of the service objective.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludedMaxSize">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.MaxSizeCapability IncludedMaxSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Models.MaxSizeCapability IncludedMaxSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.IncludedMaxSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IncludedMaxSize As MaxSizeCapability" />
      <MemberSignature Language="F#" Value="member this.IncludedMaxSize : Microsoft.Azure.Management.Sql.Models.MaxSizeCapability" Usage="Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.IncludedMaxSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="includedMaxSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.MaxSizeCapability</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dbe4-114">Ruft die enthalten (free), maximale Größe für dieses SLO ab.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-114">Gets the included (free) max size for this service level objective.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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
            <span data-ttu-id="9dbe4-115">Ruft den Dienstnamen für den objektiven ab.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-115">Gets the service objective name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CapabilityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dbe4-116">Ruft den Status des dienstziels ab.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-116">Gets the status of the service objective.</span></span> <span data-ttu-id="9dbe4-117">Folgende Werte sind möglich: "Sichtbar", "Verfügbar", "Default", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="9dbe4-117">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedMaxSizes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; SupportedMaxSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; SupportedMaxSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.SupportedMaxSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportedMaxSizes As IList(Of MaxSizeCapability)" />
      <MemberSignature Language="F#" Value="member this.SupportedMaxSizes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.SupportedMaxSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedMaxSizes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dbe4-118">Ruft die Liste der unterstützten maximale Datenbankgröße für dieses dienstziel.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-118">Gets the list of supported maximum database sizes for this service objective.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.PerformanceLevelUnit&gt; Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.PerformanceLevelUnit&gt; Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As Nullable(Of PerformanceLevelUnit)" />
      <MemberSignature Language="F#" Value="member this.Unit : Nullable&lt;Microsoft.Azure.Management.Sql.Models.PerformanceLevelUnit&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="performanceLevel.unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.PerformanceLevelUnit&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dbe4-119">Ruft Unit-Typ verwendet, um Servicelevel-Ziel Leistung zu messen.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-119">Gets unit type used to measure service objective performance level.</span></span>
            <span data-ttu-id="9dbe4-120">Folgende Werte sind möglich: "DTU"</span><span class="sxs-lookup"><span data-stu-id="9dbe4-120">Possible values include: 'DTU'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Value : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ServiceObjectiveCapability.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="performanceLevel.value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9dbe4-121">Ruft die Ebene Leistungswert ab.</span><span class="sxs-lookup"><span data-stu-id="9dbe4-121">Gets performance level value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>