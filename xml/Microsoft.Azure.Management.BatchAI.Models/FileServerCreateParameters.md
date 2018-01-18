<Type Name="FileServerCreateParameters" FullName="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters">
  <TypeSignature Language="C#" Value="public class FileServerCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileServerCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class FileServerCreateParameters" />
  <TypeSignature Language="F#" Value="type FileServerCreateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
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
            <span data-ttu-id="43f79-101">Parameter, die auf den Erstellungsvorgang angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="43f79-101">Parameters supplied to the Create operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileServerCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="43f79-102">Initialisiert eine neue Instanz der FileServerCreateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="43f79-102">Initializes a new instance of the FileServerCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileServerCreateParameters (string location, string vmSize, Microsoft.Azure.Management.BatchAI.Models.SshConfiguration sshConfiguration, Microsoft.Azure.Management.BatchAI.Models.DataDisks dataDisks, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string vmSize, class Microsoft.Azure.Management.BatchAI.Models.SshConfiguration sshConfiguration, class Microsoft.Azure.Management.BatchAI.Models.DataDisks dataDisks, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.#ctor(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.SshConfiguration,Microsoft.Azure.Management.BatchAI.Models.DataDisks,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.BatchAI.Models.ResourceId)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters : string * string * Microsoft.Azure.Management.BatchAI.Models.SshConfiguration * Microsoft.Azure.Management.BatchAI.Models.DataDisks * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.BatchAI.Models.ResourceId -&gt; Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" Usage="new Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters (location, vmSize, sshConfiguration, dataDisks, tags, subnet)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="sshConfiguration" Type="Microsoft.Azure.Management.BatchAI.Models.SshConfiguration" />
        <Parameter Name="dataDisks" Type="Microsoft.Azure.Management.BatchAI.Models.DataDisks" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="43f79-103">Die Region, in dem der Dateiserver erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="43f79-103">The region in which to create the File Server.</span></span></param>
        <param name="vmSize"><span data-ttu-id="43f79-104">Die Größe des virtuellen Computers des Dateiservers.</span><span class="sxs-lookup"><span data-stu-id="43f79-104">The size of the virtual machine of the file server.</span></span></param>
        <param name="sshConfiguration"><span data-ttu-id="43f79-105">SSH-Einstellungen für den Dateiserver.</span><span class="sxs-lookup"><span data-stu-id="43f79-105">SSH settings for the file server.</span></span></param>
        <param name="dataDisks"><span data-ttu-id="43f79-106">Einstellungen für den Datenträger, der für den Dateiserver erstellt würde.</span><span class="sxs-lookup"><span data-stu-id="43f79-106">Settings for the data disk which would be created for the file server.</span></span></param>
        <param name="tags"><span data-ttu-id="43f79-107">Der benutzerdefinierte Tags, die Dateiserver zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="43f79-107">The user specified tags associated with the File Server.</span></span></param>
        <param name="subnet"><span data-ttu-id="43f79-108">Gibt den Bezeichner des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="43f79-108">Specifies the identifier of the subnet.</span></span></param>
        <summary>
            <span data-ttu-id="43f79-109">Initialisiert eine neue Instanz der FileServerCreateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="43f79-109">Initializes a new instance of the FileServerCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.DataDisks DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.DataDisks DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As DataDisks" />
      <MemberSignature Language="F#" Value="member this.DataDisks : Microsoft.Azure.Management.BatchAI.Models.DataDisks with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.DataDisks</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="43f79-110">Ruft ab oder legt Einstellungen für den Datenträger, der erstellt wird, für den Dateiserver.</span><span class="sxs-lookup"><span data-stu-id="43f79-110">Gets or sets settings for the data disk which would be created for the file server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="43f79-111">Ruft ab oder legt die Region, in dem der Dateiserver erstellt.</span><span class="sxs-lookup"><span data-stu-id="43f79-111">Gets or sets the region in which to create the File Server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SshConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.SshConfiguration SshConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.SshConfiguration SshConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.SshConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property SshConfiguration As SshConfiguration" />
      <MemberSignature Language="F#" Value="member this.SshConfiguration : Microsoft.Azure.Management.BatchAI.Models.SshConfiguration with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.SshConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sshConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.SshConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="43f79-112">Ruft ab, oder legt ihn fest SSH-Einstellungen für den Dateiserver.</span><span class="sxs-lookup"><span data-stu-id="43f79-112">Gets or sets SSH settings for the file server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As ResourceId" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="43f79-113">Ruft ab oder legt gibt den Bezeichner des Subnetzes an.</span><span class="sxs-lookup"><span data-stu-id="43f79-113">Gets or sets specifies the identifier of the subnet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="43f79-114">Ruft ab oder legt angegebene Benutzer die Dateiserver zugeordneten Tags.</span><span class="sxs-lookup"><span data-stu-id="43f79-114">Gets or sets the user specified tags associated with the File Server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fileServerCreateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="43f79-115">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="43f79-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="43f79-116">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="43f79-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="43f79-117">Ruft ab oder legt die Größe des virtuellen Computers des Dateiservers.</span><span class="sxs-lookup"><span data-stu-id="43f79-117">Gets or sets the size of the virtual machine of the file server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="43f79-118">Informationen zu den verfügbaren VM-Größen für Dateiserver aus dem Marketplace für virtuelle Maschinen finden Sie unter Größen für virtuelle Maschinen (Linux).</span><span class="sxs-lookup"><span data-stu-id="43f79-118">For information about available VM sizes for fileservers from the Virtual Machines Marketplace, see Sizes for Virtual Machines (Linux).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>