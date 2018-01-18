<Type Name="ClusterUpgradeDeltaHealthPolicy" FullName="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy">
  <TypeSignature Language="C#" Value="public class ClusterUpgradeDeltaHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterUpgradeDeltaHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterUpgradeDeltaHealthPolicy" />
  <TypeSignature Language="F#" Value="type ClusterUpgradeDeltaHealthPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ac3d7-101">Delta-Integritätsrichtlinie für den cluster</span><span class="sxs-lookup"><span data-stu-id="ac3d7-101">Delta health policy for the cluster</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterUpgradeDeltaHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ac3d7-102">Initialisiert eine neue Instanz der ClusterUpgradeDeltaHealthPolicy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ac3d7-102">Initializes a new instance of the ClusterUpgradeDeltaHealthPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterUpgradeDeltaHealthPolicy (int maxPercentDeltaUnhealthyNodes, int maxPercentUpgradeDomainDeltaUnhealthyNodes, int maxPercentDeltaUnhealthyApplications);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 maxPercentDeltaUnhealthyNodes, int32 maxPercentUpgradeDomainDeltaUnhealthyNodes, int32 maxPercentDeltaUnhealthyApplications) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.#ctor(System.Int32,System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxPercentDeltaUnhealthyNodes As Integer, maxPercentUpgradeDomainDeltaUnhealthyNodes As Integer, maxPercentDeltaUnhealthyApplications As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy : int * int * int -&gt; Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy (maxPercentDeltaUnhealthyNodes, maxPercentUpgradeDomainDeltaUnhealthyNodes, maxPercentDeltaUnhealthyApplications)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxPercentDeltaUnhealthyNodes" Type="System.Int32" />
        <Parameter Name="maxPercentUpgradeDomainDeltaUnhealthyNodes" Type="System.Int32" />
        <Parameter Name="maxPercentDeltaUnhealthyApplications" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxPercentDeltaUnhealthyNodes"><span data-ttu-id="ac3d7-103">Zusätzliche fehlerhaften Knoten in Prozent</span><span class="sxs-lookup"><span data-stu-id="ac3d7-103">Additional unhealthy nodes percentage</span></span></param>
        <param name="maxPercentUpgradeDomainDeltaUnhealthyNodes"><span data-ttu-id="ac3d7-104">Zusätzliche fehlerhaften Knoten Prozentsatz pro upgradedomäne</span><span class="sxs-lookup"><span data-stu-id="ac3d7-104">Additional unhealthy nodes percentage per upgrade domain</span></span> </param>
        <param name="maxPercentDeltaUnhealthyApplications"><span data-ttu-id="ac3d7-105">Zusätzliche "fehlerhaft" Anwendungen-Prozentsatz</span><span class="sxs-lookup"><span data-stu-id="ac3d7-105">Additional unhealthy applications percentage</span></span></param>
        <summary>
            <span data-ttu-id="ac3d7-106">Initialisiert eine neue Instanz der ClusterUpgradeDeltaHealthPolicy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ac3d7-106">Initializes a new instance of the ClusterUpgradeDeltaHealthPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentDeltaUnhealthyApplications">
      <MemberSignature Language="C#" Value="public int MaxPercentDeltaUnhealthyApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPercentDeltaUnhealthyApplications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.MaxPercentDeltaUnhealthyApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentDeltaUnhealthyApplications As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPercentDeltaUnhealthyApplications : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.MaxPercentDeltaUnhealthyApplications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxPercentDeltaUnhealthyApplications")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ac3d7-107">Ruft ab oder legt ihn fest zusätzliche "fehlerhaft" Anwendungen-Prozentsatz</span><span class="sxs-lookup"><span data-stu-id="ac3d7-107">Gets or sets additional unhealthy applications percentage</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public int MaxPercentDeltaUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentDeltaUnhealthyNodes As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPercentDeltaUnhealthyNodes : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.MaxPercentDeltaUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxPercentDeltaUnhealthyNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ac3d7-108">Ruft ab oder legt ihn fest zusätzliche fehlerhaften Knoten in Prozent</span><span class="sxs-lookup"><span data-stu-id="ac3d7-108">Gets or sets additional unhealthy nodes percentage</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUpgradeDomainDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public int MaxPercentUpgradeDomainDeltaUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUpgradeDomainDeltaUnhealthyNodes As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUpgradeDomainDeltaUnhealthyNodes : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxPercentUpgradeDomainDeltaUnhealthyNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ac3d7-109">Ruft ab oder legt zusätzliche fehlerhaften Knoten Prozentsatz pro upgradedomäne</span><span class="sxs-lookup"><span data-stu-id="ac3d7-109">Gets or sets additional unhealthy nodes percentage per upgrade domain</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradeDeltaHealthPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="clusterUpgradeDeltaHealthPolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ac3d7-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="ac3d7-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ac3d7-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="ac3d7-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>