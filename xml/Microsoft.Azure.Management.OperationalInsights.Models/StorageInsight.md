<Type Name="StorageInsight" FullName="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight">
  <TypeSignature Language="C#" Value="public class StorageInsight : Microsoft.Azure.Management.OperationalInsights.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageInsight extends Microsoft.Azure.Management.OperationalInsights.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageInsight&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type StorageInsight = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.OperationalInsights.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="24db4-101">Die oberste Ebene Insight Ressource Speichercontainer.</span><span class="sxs-lookup"><span data-stu-id="24db4-101">The top level storage insight resource container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageInsight ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="24db4-102">Initialisiert eine neue Instanz der StorageInsight-Klasse.</span><span class="sxs-lookup"><span data-stu-id="24db4-102">Initializes a new instance of the StorageInsight class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageInsight (Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount storageAccount, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;string&gt; containers = null, System.Collections.Generic.IList&lt;string&gt; tables = null, Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus status = null, string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount storageAccount, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;string&gt; containers, class System.Collections.Generic.IList`1&lt;string&gt; tables, class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus status, string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.#ctor(Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight : Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight (storageAccount, id, name, type, tags, containers, tables, status, eTag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="containers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="tables" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus" />
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="24db4-103">Die Verbindungsdetails für Storage-Konto</span><span class="sxs-lookup"><span data-stu-id="24db4-103">The storage account connection details</span></span></param>
        <param name="id"><span data-ttu-id="24db4-104">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="24db4-104">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="24db4-105">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="24db4-105">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="24db4-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="24db4-106">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="24db4-107">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="24db4-107">Resource tags</span></span></param>
        <param name="containers"><span data-ttu-id="24db4-108">Die Namen der Blob-Container, die der Arbeitsbereich gelesen werden soll</span><span class="sxs-lookup"><span data-stu-id="24db4-108">The names of the blob containers that the workspace should read</span></span></param>
        <param name="tables"><span data-ttu-id="24db4-109">Die Namen der Azure-Tabellen, die der Arbeitsbereich gelesen werden soll</span><span class="sxs-lookup"><span data-stu-id="24db4-109">The names of the Azure tables that the workspace should read</span></span></param>
        <param name="status"><span data-ttu-id="24db4-110">Der Status der Speicher und die Erkenntnisse</span><span class="sxs-lookup"><span data-stu-id="24db4-110">The status of the storage insight</span></span></param>
        <param name="eTag"><span data-ttu-id="24db4-111">Das ETag der Speicher und die Erkenntnisse.</span><span class="sxs-lookup"><span data-stu-id="24db4-111">The ETag of the storage insight.</span></span></param>
        <summary>
            <span data-ttu-id="24db4-112">Initialisiert eine neue Instanz der StorageInsight-Klasse.</span><span class="sxs-lookup"><span data-stu-id="24db4-112">Initializes a new instance of the StorageInsight class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Containers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Containers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Containers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Containers" />
      <MemberSignature Language="VB.NET" Value="Public Property Containers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Containers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Containers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.containers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24db4-113">Ruft ab oder legt die Namen der Blob-Container, die der Arbeitsbereich gelesen werden soll</span><span class="sxs-lookup"><span data-stu-id="24db4-113">Gets or sets the names of the blob containers that the workspace should read</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24db4-114">Ruft ab oder legt das ETag der Speicher und die Erkenntnisse.</span><span class="sxs-lookup"><span data-stu-id="24db4-114">Gets or sets the ETag of the storage insight.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As StorageInsightStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus" Usage="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.StorageInsightStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24db4-115">Ruft den Status und die Erkenntnisse Speicher ab</span><span class="sxs-lookup"><span data-stu-id="24db4-115">Gets the status of the storage insight</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount StorageAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount StorageAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.StorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccount As StorageAccount" />
      <MemberSignature Language="F#" Value="member this.StorageAccount : Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.StorageAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24db4-116">Ruft ab oder legt das Speicherkonto Verbindungsdetails</span><span class="sxs-lookup"><span data-stu-id="24db4-116">Gets or sets the storage account connection details</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tables">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Tables { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Tables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Tables" />
      <MemberSignature Language="VB.NET" Value="Public Property Tables As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Tables : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Tables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tables")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24db4-117">Ruft ab oder legt die Namen der Azure-Tabellen, die der Arbeitsbereich gelesen werden soll</span><span class="sxs-lookup"><span data-stu-id="24db4-117">Gets or sets the names of the Azure tables that the workspace should read</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageInsight.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="24db4-118">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="24db4-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="24db4-119">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="24db4-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>