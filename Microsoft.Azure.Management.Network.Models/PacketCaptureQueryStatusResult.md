<Type Name="PacketCaptureQueryStatusResult" FullName="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult">
  <TypeSignature Language="C#" Value="public class PacketCaptureQueryStatusResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PacketCaptureQueryStatusResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult" />
  <TypeSignature Language="VB.NET" Value="Public Class PacketCaptureQueryStatusResult" />
  <TypeSignature Language="F#" Value="type PacketCaptureQueryStatusResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="86ea7-101">Status der erfassungssitzung Paket.</span><span class="sxs-lookup"><span data-stu-id="86ea7-101">Status of packet capture session.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureQueryStatusResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.#ctor" />
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
            <span data-ttu-id="86ea7-102">Initialisiert eine neue Instanz der PacketCaptureQueryStatusResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="86ea7-102">Initializes a new instance of the PacketCaptureQueryStatusResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureQueryStatusResult (string name = null, string id = null, Nullable&lt;DateTime&gt; captureStartTime = null, string packetCaptureStatus = null, string stopReason = null, System.Collections.Generic.IList&lt;string&gt; packetCaptureError = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; captureStartTime, string packetCaptureStatus, string stopReason, class System.Collections.Generic.IList`1&lt;string&gt; packetCaptureError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.#ctor(System.String,System.String,System.Nullable{System.DateTime},System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional id As String = null, Optional captureStartTime As Nullable(Of DateTime) = null, Optional packetCaptureStatus As String = null, Optional stopReason As String = null, Optional packetCaptureError As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult : string * string * Nullable&lt;DateTime&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult" Usage="new Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult (name, id, captureStartTime, packetCaptureStatus, stopReason, packetCaptureError)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="captureStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="packetCaptureStatus" Type="System.String" />
        <Parameter Name="stopReason" Type="System.String" />
        <Parameter Name="packetCaptureError" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="86ea7-103">Der Name der Ressource Capture Paket.</span><span class="sxs-lookup"><span data-stu-id="86ea7-103">The name of the packet capture resource.</span></span></param>
        <param name="id"><span data-ttu-id="86ea7-104">Die ID des Pakets erfassen Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="86ea7-104">The ID of the packet capture resource.</span></span></param>
        <param name="captureStartTime"><span data-ttu-id="86ea7-105">Die Startzeit der aufzeichnungssitzung Paket.</span><span class="sxs-lookup"><span data-stu-id="86ea7-105">The start time of the packet capture session.</span></span></param>
        <param name="packetCaptureStatus"><span data-ttu-id="86ea7-106">Der Status der aufzeichnungssitzung Paket.</span><span class="sxs-lookup"><span data-stu-id="86ea7-106">The status of the packet capture session.</span></span> <span data-ttu-id="86ea7-107">Folgende Werte sind möglich: 'Wurde nicht gestartet', 'Running', 'Beendet', 'Fehler', 'Unbekannt'</span><span class="sxs-lookup"><span data-stu-id="86ea7-107">Possible values include: 'NotStarted', 'Running', 'Stopped', 'Error', 'Unknown'</span></span></param>
        <param name="stopReason"><span data-ttu-id="86ea7-108">Der Grund wurde der aktuelle Paket erfassungssitzung beendet.</span><span class="sxs-lookup"><span data-stu-id="86ea7-108">The reason the current packet capture session was stopped.</span></span></param>
        <param name="packetCaptureError"><span data-ttu-id="86ea7-109">Liste von Fehlern in der Paket-erfassungssitzung.</span><span class="sxs-lookup"><span data-stu-id="86ea7-109">List of errors of packet capture session.</span></span></param>
        <summary>
            <span data-ttu-id="86ea7-110">Initialisiert eine neue Instanz der PacketCaptureQueryStatusResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="86ea7-110">Initializes a new instance of the PacketCaptureQueryStatusResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CaptureStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CaptureStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CaptureStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.CaptureStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CaptureStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CaptureStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.CaptureStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="captureStartTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86ea7-111">Ruft ab oder legt die Startzeit der aufzeichnungssitzung Paket fest.</span><span class="sxs-lookup"><span data-stu-id="86ea7-111">Gets or sets the start time of the packet capture session.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.Id" />
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
            <span data-ttu-id="86ea7-112">Ruft ab oder legt die ID der Ressource Capture Paket fest.</span><span class="sxs-lookup"><span data-stu-id="86ea7-112">Gets or sets the ID of the packet capture resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.Name" />
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
            <span data-ttu-id="86ea7-113">Ruft ab oder legt den Namen der Ressource Capture Paket fest.</span><span class="sxs-lookup"><span data-stu-id="86ea7-113">Gets or sets the name of the packet capture resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PacketCaptureError">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PacketCaptureError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PacketCaptureError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.PacketCaptureError" />
      <MemberSignature Language="VB.NET" Value="Public Property PacketCaptureError As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PacketCaptureError : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.PacketCaptureError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="packetCaptureError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86ea7-114">Ruft ab, oder legt die Liste von Fehlern in der Paket-erfassungssitzung fest.</span><span class="sxs-lookup"><span data-stu-id="86ea7-114">Gets or sets list of errors of packet capture session.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PacketCaptureStatus">
      <MemberSignature Language="C#" Value="public string PacketCaptureStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PacketCaptureStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.PacketCaptureStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property PacketCaptureStatus As String" />
      <MemberSignature Language="F#" Value="member this.PacketCaptureStatus : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.PacketCaptureStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="packetCaptureStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86ea7-115">Ruft ab oder legt den Status der aufzeichnungssitzung Paket fest.</span><span class="sxs-lookup"><span data-stu-id="86ea7-115">Gets or sets the status of the packet capture session.</span></span> <span data-ttu-id="86ea7-116">Folgende Werte sind möglich: 'Wurde nicht gestartet', 'Running', 'Beendet', 'Fehler', 'Unbekannt'</span><span class="sxs-lookup"><span data-stu-id="86ea7-116">Possible values include: 'NotStarted', 'Running', 'Stopped', 'Error', 'Unknown'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopReason">
      <MemberSignature Language="C#" Value="public string StopReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StopReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.StopReason" />
      <MemberSignature Language="VB.NET" Value="Public Property StopReason As String" />
      <MemberSignature Language="F#" Value="member this.StopReason : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.StopReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stopReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86ea7-117">Ruft ab oder legt fest, die die Ursache der aktuellen Paket Capture Sitzung beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="86ea7-117">Gets or sets the reason the current packet capture session was stopped.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>