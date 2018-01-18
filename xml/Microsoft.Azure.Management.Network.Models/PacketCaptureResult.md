<Type Name="PacketCaptureResult" FullName="Microsoft.Azure.Management.Network.Models.PacketCaptureResult">
  <TypeSignature Language="C#" Value="public class PacketCaptureResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PacketCaptureResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.PacketCaptureResult" />
  <TypeSignature Language="VB.NET" Value="Public Class PacketCaptureResult" />
  <TypeSignature Language="F#" Value="type PacketCaptureResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5386a-101">Informationen zum Paket erfassungssitzung.</span><span class="sxs-lookup"><span data-stu-id="5386a-101">Information about packet capture session.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5386a-102">Initialisiert eine neue Instanz der PacketCaptureResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5386a-102">Initializes a new instance of the PacketCaptureResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureResult (string target, Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation storageLocation, string name = null, string id = null, string etag = null, Nullable&lt;int&gt; bytesToCapturePerPacket = null, Nullable&lt;int&gt; totalBytesPerSession = null, Nullable&lt;int&gt; timeLimitInSeconds = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; filters = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string target, class Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation storageLocation, string name, string id, string etag, valuetype System.Nullable`1&lt;int32&gt; bytesToCapturePerPacket, valuetype System.Nullable`1&lt;int32&gt; totalBytesPerSession, valuetype System.Nullable`1&lt;int32&gt; timeLimitInSeconds, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; filters, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.#ctor(System.String,Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.PacketCaptureFilter},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (target As String, storageLocation As PacketCaptureStorageLocation, Optional name As String = null, Optional id As String = null, Optional etag As String = null, Optional bytesToCapturePerPacket As Nullable(Of Integer) = null, Optional totalBytesPerSession As Nullable(Of Integer) = null, Optional timeLimitInSeconds As Nullable(Of Integer) = null, Optional filters As IList(Of PacketCaptureFilter) = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.PacketCaptureResult : string * Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.PacketCaptureResult" Usage="new Microsoft.Azure.Management.Network.Models.PacketCaptureResult (target, storageLocation, name, id, etag, bytesToCapturePerPacket, totalBytesPerSession, timeLimitInSeconds, filters, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="storageLocation" Type="Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="bytesToCapturePerPacket" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="totalBytesPerSession" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="timeLimitInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="filters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="target"><span data-ttu-id="5386a-103">Die Zielressource nur VM-ID wird derzeit unterstützt.</span><span class="sxs-lookup"><span data-stu-id="5386a-103">The ID of the targeted resource, only VM is currently supported.</span></span></param>
        <param name="storageLocation">To be added.</param>
        <param name="name"><span data-ttu-id="5386a-104">Der Name der aufzeichnungssitzung Paket.</span><span class="sxs-lookup"><span data-stu-id="5386a-104">Name of the packet capture session.</span></span></param>
        <param name="id"><span data-ttu-id="5386a-105">ID des Pakets Capture-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="5386a-105">ID of the packet capture operation.</span></span></param>
        <param name="etag">To be added.</param>
        <param name="bytesToCapturePerPacket"><span data-ttu-id="5386a-106">Anzahl von Bytes pro Paket erfasst, werden die restlichen Bytes abgeschnitten.</span><span class="sxs-lookup"><span data-stu-id="5386a-106">Number of bytes captured per packet, the remaining bytes are truncated.</span></span></param>
        <param name="totalBytesPerSession"><span data-ttu-id="5386a-107">Maximale Größe der Capture-Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="5386a-107">Maximum size of the capture output.</span></span></param>
        <param name="timeLimitInSeconds"><span data-ttu-id="5386a-108">Maximale Dauer der aufzeichnungssitzung in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="5386a-108">Maximum duration of the capture session in seconds.</span></span></param>
        <param name="filters">To be added.</param>
        <param name="provisioningState"><span data-ttu-id="5386a-109">Der Bereitstellungsstatus der aufzeichnungssitzung Paket.</span><span class="sxs-lookup"><span data-stu-id="5386a-109">The provisioning state of the packet capture session.</span></span> <span data-ttu-id="5386a-110">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Aktualisieren", "Löschen", "fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="5386a-110">Possible values include: 'Succeeded', 'Updating', 'Deleting', 'Failed'</span></span></param>
        <summary>
            <span data-ttu-id="5386a-111">Initialisiert eine neue Instanz der PacketCaptureResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5386a-111">Initializes a new instance of the PacketCaptureResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BytesToCapturePerPacket">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BytesToCapturePerPacket { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BytesToCapturePerPacket" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.BytesToCapturePerPacket" />
      <MemberSignature Language="VB.NET" Value="Public Property BytesToCapturePerPacket As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BytesToCapturePerPacket : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.BytesToCapturePerPacket" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.bytesToCapturePerPacket")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5386a-112">Ruft ab oder legt die Anzahl von Bytes pro Paket, erfasst die restlichen Bytes abgeschnitten werden.</span><span class="sxs-lookup"><span data-stu-id="5386a-112">Gets or sets number of bytes captured per packet, the remaining bytes are truncated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; Filters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; Filters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Filters" />
      <MemberSignature Language="VB.NET" Value="Public Property Filters As IList(Of PacketCaptureFilter)" />
      <MemberSignature Language="F#" Value="member this.Filters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Filters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.filters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5386a-113">Ruft die ID des Pakets Capture-Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="5386a-113">Gets ID of the packet capture operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="5386a-114">Ruft die Namen der aufzeichnungssitzung Paket ab.</span><span class="sxs-lookup"><span data-stu-id="5386a-114">Gets name of the packet capture session.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5386a-115">Ruft ab oder legt den Bereitstellungsstatus der aufzeichnungssitzung Paket.</span><span class="sxs-lookup"><span data-stu-id="5386a-115">Gets or sets the provisioning state of the packet capture session.</span></span>
            <span data-ttu-id="5386a-116">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Aktualisieren", "Löschen", "fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="5386a-116">Possible values include: 'Succeeded', 'Updating', 'Deleting', 'Failed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation StorageLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation StorageLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.StorageLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageLocation As PacketCaptureStorageLocation" />
      <MemberSignature Language="F#" Value="member this.StorageLocation : Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.StorageLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.target")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5386a-117">Ruft ab oder legt fest, die die Zielressource nur VM-ID derzeit unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="5386a-117">Gets or sets the ID of the targeted resource, only VM is currently supported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeLimitInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TimeLimitInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TimeLimitInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.TimeLimitInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeLimitInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TimeLimitInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.TimeLimitInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeLimitInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5386a-118">Ruft ab oder legt die maximale Dauer der aufzeichnungssitzung in Sekunden fest.</span><span class="sxs-lookup"><span data-stu-id="5386a-118">Gets or sets maximum duration of the capture session in seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalBytesPerSession">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalBytesPerSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalBytesPerSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.TotalBytesPerSession" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalBytesPerSession As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalBytesPerSession : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.TotalBytesPerSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.totalBytesPerSession")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5386a-119">Ruft ab oder legt die maximale Größe der Capture-Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="5386a-119">Gets or sets maximum size of the capture output.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="packetCaptureResult.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5386a-120">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="5386a-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5386a-121">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="5386a-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>