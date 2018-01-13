<Type Name="ContainerServiceOrchestratorProfile" FullName="Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile">
  <TypeSignature Language="C#" Value="public class ContainerServiceOrchestratorProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceOrchestratorProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceOrchestratorProfile" />
  <TypeSignature Language="F#" Value="type ContainerServiceOrchestratorProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2594a-101">Profil für den Container-Orchestrator-Dienst.</span><span class="sxs-lookup"><span data-stu-id="2594a-101">Profile for the container service orchestrator.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceOrchestratorProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2594a-102">Initialisiert eine neue Instanz der ContainerServiceOrchestratorProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2594a-102">Initializes a new instance of the ContainerServiceOrchestratorProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceOrchestratorProfile (Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorTypes orchestratorType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorTypes orchestratorType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile.#ctor(Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (orchestratorType As ContainerServiceOrchestratorTypes)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile : Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorTypes -&gt; Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile" Usage="new Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile orchestratorType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="orchestratorType" Type="Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorTypes" />
      </Parameters>
      <Docs>
        <param name="orchestratorType"><span data-ttu-id="2594a-103">Die Orchestrator zum Verwalten von Clusterressourcen für Container-Dienst.</span><span class="sxs-lookup"><span data-stu-id="2594a-103">The orchestrator to use to manage container service cluster resources.</span></span> <span data-ttu-id="2594a-104">Gültige Werte sind Punktschwarms, DCOS und Benutzerdefiniert.</span><span class="sxs-lookup"><span data-stu-id="2594a-104">Valid values are Swarm, DCOS, and Custom.</span></span> <span data-ttu-id="2594a-105">Folgende Werte sind möglich: "Containerhostclustern", "DCOS", "Benutzerdefiniert", "Kubernetes"</span><span class="sxs-lookup"><span data-stu-id="2594a-105">Possible values include: 'Swarm', 'DCOS', 'Custom', 'Kubernetes'</span></span></param>
        <summary>
            <span data-ttu-id="2594a-106">Initialisiert eine neue Instanz der ContainerServiceOrchestratorProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2594a-106">Initializes a new instance of the ContainerServiceOrchestratorProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrchestratorType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorTypes OrchestratorType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorTypes OrchestratorType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile.OrchestratorType" />
      <MemberSignature Language="VB.NET" Value="Public Property OrchestratorType As ContainerServiceOrchestratorTypes" />
      <MemberSignature Language="F#" Value="member this.OrchestratorType : Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile.OrchestratorType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="orchestratorType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2594a-107">Abrufen oder Festlegen der Orchestrator zum Verwalten von Clusterressourcen für Container-Dienst.</span><span class="sxs-lookup"><span data-stu-id="2594a-107">Gets or sets the orchestrator to use to manage container service cluster resources.</span></span> <span data-ttu-id="2594a-108">Gültige Werte sind Punktschwarms, DCOS und Benutzerdefiniert.</span><span class="sxs-lookup"><span data-stu-id="2594a-108">Valid values are Swarm, DCOS, and Custom.</span></span>
            <span data-ttu-id="2594a-109">Folgende Werte sind möglich: "Containerhostclustern", "DCOS", "Benutzerdefiniert", "Kubernetes"</span><span class="sxs-lookup"><span data-stu-id="2594a-109">Possible values include: 'Swarm', 'DCOS', 'Custom', 'Kubernetes'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceOrchestratorProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceOrchestratorProfile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2594a-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="2594a-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2594a-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="2594a-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>