<Type Name="ContainerServiceMasterProfile" FullName="Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile">
  <TypeSignature Language="C#" Value="public class ContainerServiceMasterProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceMasterProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceMasterProfile" />
  <TypeSignature Language="F#" Value="type ContainerServiceMasterProfile = class" />
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
            <span data-ttu-id="8f9a2-101">Profil für den Container Service Master.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-101">Profile for the container service master.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceMasterProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile.#ctor" />
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
            <span data-ttu-id="8f9a2-102">Initialisiert eine neue Instanz der ContainerServiceMasterProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-102">Initializes a new instance of the ContainerServiceMasterProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceMasterProfile (string dnsPrefix, Nullable&lt;int&gt; count = null, string fqdn = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string dnsPrefix, valuetype System.Nullable`1&lt;int32&gt; count, string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile.#ctor(System.String,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dnsPrefix As String, Optional count As Nullable(Of Integer) = null, Optional fqdn As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile : string * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile" Usage="new Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile (dnsPrefix, count, fqdn)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dnsPrefix" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dnsPrefix"><span data-ttu-id="8f9a2-103">DNS-Präfix verwendet werden, um den FQDN für Master zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-103">DNS prefix to be used to create the FQDN for master.</span></span></param>
        <param name="count"><span data-ttu-id="8f9a2-104">Anzahl der Master-Shapes (VMs) im Cluster Service Container.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-104">Number of masters (VMs) in the container service cluster.</span></span> <span data-ttu-id="8f9a2-105">Zulässige Werte sind 1, 3 und 5.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-105">Allowed values are 1, 3, and 5.</span></span> <span data-ttu-id="8f9a2-106">Der Standardwert ist 1.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-106">The default value is 1.</span></span></param>
        <param name="fqdn"><span data-ttu-id="8f9a2-107">FQDN für den Master.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-107">FDQN for the master.</span></span></param>
        <summary>
            <span data-ttu-id="8f9a2-108">Initialisiert eine neue Instanz der ContainerServiceMasterProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-108">Initializes a new instance of the ContainerServiceMasterProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f9a2-109">Ruft ab oder legt Anzahl der Master-Shapes (VMs) im Cluster Service Container fest.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-109">Gets or sets number of masters (VMs) in the container service cluster.</span></span> <span data-ttu-id="8f9a2-110">Zulässige Werte sind 1, 3 und 5.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-110">Allowed values are 1, 3, and 5.</span></span> <span data-ttu-id="8f9a2-111">Der Standardwert ist 1.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-111">The default value is 1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsPrefix">
      <MemberSignature Language="C#" Value="public string DnsPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile.DnsPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsPrefix As String" />
      <MemberSignature Language="F#" Value="member this.DnsPrefix : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile.DnsPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dnsPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f9a2-112">Abrufen oder Festlegen der DNS-Präfix verwendet werden, um den FQDN für Master zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-112">Gets or sets DNS prefix to be used to create the FQDN for master.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fqdn">
      <MemberSignature Language="C#" Value="public string Fqdn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile.Fqdn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Fqdn As String" />
      <MemberSignature Language="F#" Value="member this.Fqdn : string" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile.Fqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fqdn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f9a2-113">Ruft den FQDN für den Master ab.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-113">Gets FDQN for the master.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceMasterProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceMasterProfile.Validate " />
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
            <span data-ttu-id="8f9a2-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="8f9a2-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8f9a2-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="8f9a2-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>