<Type Name="RollingUpgradeStatusInfo" FullName="Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo">
  <TypeSignature Language="C#" Value="public class RollingUpgradeStatusInfo : Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RollingUpgradeStatusInfo extends Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class RollingUpgradeStatusInfo&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type RollingUpgradeStatusInfo = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="61991-101">Der Status des die aktuelle VM-Skalierungsgruppe paralleles Upgrade.</span><span class="sxs-lookup"><span data-stu-id="61991-101">The status of the latest virtual machine scale set rolling upgrade.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradeStatusInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="61991-102">Initialisiert eine neue Instanz der RollingUpgradeStatusInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="61991-102">Initializes a new instance of the RollingUpgradeStatusInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradeStatusInfo (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy policy = null, Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus runningStatus = null, Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo progress = null, Microsoft.Azure.Management.Compute.Models.ApiError error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy policy, class Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus runningStatus, class Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo progress, class Microsoft.Azure.Management.Compute.Models.ApiError error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy,Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus,Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo,Microsoft.Azure.Management.Compute.Models.ApiError)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional policy As RollingUpgradePolicy = null, Optional runningStatus As RollingUpgradeRunningStatus = null, Optional progress As RollingUpgradeProgressInfo = null, Optional error As ApiError = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy * Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus * Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo * Microsoft.Azure.Management.Compute.Models.ApiError -&gt; Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo" Usage="new Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo (location, id, name, type, tags, policy, runningStatus, progress, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy" />
        <Parameter Name="runningStatus" Type="Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus" />
        <Parameter Name="progress" Type="Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.Compute.Models.ApiError" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="61991-103">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="61991-103">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="61991-104">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="61991-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="61991-105">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="61991-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="61991-106">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="61991-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="61991-107">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="61991-107">Resource tags</span></span></param>
        <param name="policy"><span data-ttu-id="61991-108">Parallelen Upgrade Richtlinien für dieses Upgrade.</span><span class="sxs-lookup"><span data-stu-id="61991-108">The rolling upgrade policies applied for this upgrade.</span></span></param>
        <param name="runningStatus"><span data-ttu-id="61991-109">Informationen zu den aktuellen Ausführungsstatus des gesamten Upgrades.</span><span class="sxs-lookup"><span data-stu-id="61991-109">Information about the current running state of the overall upgrade.</span></span></param>
        <param name="progress"><span data-ttu-id="61991-110">Informationen über die Anzahl der Instanzen virtueller Computer in jeder Upgradestatus.</span><span class="sxs-lookup"><span data-stu-id="61991-110">Information about the number of virtual machine instances in each upgrade state.</span></span></param>
        <param name="error"><span data-ttu-id="61991-111">Fehlerdetails für dieses Upgrade, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="61991-111">Error details for this upgrade, if there are any.</span></span></param>
        <summary>
            <span data-ttu-id="61991-112">Initialisiert eine neue Instanz der RollingUpgradeStatusInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="61991-112">Initializes a new instance of the RollingUpgradeStatusInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ApiError Error { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ApiError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo.Error" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Error As ApiError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.Compute.Models.ApiError" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ApiError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61991-113">Ruft Details zum Systemfehler für das Upgrade ab, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="61991-113">Gets error details for this upgrade, if there are any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Policy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy Policy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy Policy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo.Policy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Policy As RollingUpgradePolicy" />
      <MemberSignature Language="F#" Value="member this.Policy : Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo.Policy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.policy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61991-114">Ruft das parallele Upgrade Richtlinien für das Upgrade ab.</span><span class="sxs-lookup"><span data-stu-id="61991-114">Gets the rolling upgrade policies applied for this upgrade.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Progress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo Progress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo Progress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo.Progress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Progress As RollingUpgradeProgressInfo" />
      <MemberSignature Language="F#" Value="member this.Progress : Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo.Progress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.progress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.RollingUpgradeProgressInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61991-115">Ruft Informationen über die Anzahl der Instanzen virtueller Computer in jeder Upgradestatus ab.</span><span class="sxs-lookup"><span data-stu-id="61991-115">Gets information about the number of virtual machine instances in each upgrade state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunningStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus RunningStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus RunningStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo.RunningStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RunningStatus As RollingUpgradeRunningStatus" />
      <MemberSignature Language="F#" Value="member this.RunningStatus : Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo.RunningStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.runningStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.RollingUpgradeRunningStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61991-116">Ruft Informationen zu den aktuellen Ausführungsstatus des gesamten Upgrades.</span><span class="sxs-lookup"><span data-stu-id="61991-116">Gets information about the current running state of the overall upgrade.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RollingUpgradeStatusInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="rollingUpgradeStatusInfo.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="61991-117">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="61991-117">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61991-118">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="61991-118">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>