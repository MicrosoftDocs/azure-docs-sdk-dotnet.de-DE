<Type Name="Device" FullName="Microsoft.Azure.Devices.Device">
  <TypeSignature Language="C#" Value="public class Device : Microsoft.Azure.Devices.Shared.IETagHolder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Device extends System.Object implements class Microsoft.Azure.Devices.Shared.IETagHolder" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Device" />
  <TypeSignature Language="VB.NET" Value="Public Class Device&#xA;Implements IETagHolder" />
  <TypeSignature Language="F#" Value="type Device = class&#xA;    interface IETagHolder" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Devices.Shared.IETagHolder</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="0320a-101">Enthält Eigenschaften des Geräts und ihre Accessoren.</span><span class="sxs-lookup"><span data-stu-id="0320a-101">Contains Device properties and their accessors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Device ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Device.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0320a-102">Erstellt eine neue Instanz von<see cref="T:Microsoft.Azure.Devices.Device" /></span><span class="sxs-lookup"><span data-stu-id="0320a-102">Creates a new instance of <see cref="T:Microsoft.Azure.Devices.Device" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Device (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Device.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Device : string -&gt; Microsoft.Azure.Devices.Device" Usage="new Microsoft.Azure.Devices.Device id" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="0320a-103">Geräte-ID</span><span class="sxs-lookup"><span data-stu-id="0320a-103">Device ID</span></span></param>
        <summary>
            <span data-ttu-id="0320a-104">Erstellt eine neue Instanz von<see cref="T:Microsoft.Azure.Devices.Device" /></span><span class="sxs-lookup"><span data-stu-id="0320a-104">Creates a new instance of <see cref="T:Microsoft.Azure.Devices.Device" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authentication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.AuthenticationMechanism Authentication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.AuthenticationMechanism Authentication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Device.Authentication" />
      <MemberSignature Language="VB.NET" Value="Public Property Authentication As AuthenticationMechanism" />
      <MemberSignature Language="F#" Value="member this.Authentication : Microsoft.Azure.Devices.AuthenticationMechanism with get, set" Usage="Microsoft.Azure.Devices.Device.Authentication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authentication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.AuthenticationMechanism</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0320a-105">Authentifizierungsmechanismus des Geräts</span><span class="sxs-lookup"><span data-stu-id="0320a-105">Device's authentication mechanism</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudToDeviceMessageCount">
      <MemberSignature Language="C#" Value="public int CloudToDeviceMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CloudToDeviceMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Device.CloudToDeviceMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CloudToDeviceMessageCount As Integer" />
      <MemberSignature Language="F#" Value="member this.CloudToDeviceMessageCount : int" Usage="Microsoft.Azure.Devices.Device.CloudToDeviceMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloudToDeviceMessageCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0320a-106">Anzahl der Nachrichten, die an das Gerät gesendet, aus der Cloud</span><span class="sxs-lookup"><span data-stu-id="0320a-106">Number of messages sent to the Device from the Cloud</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.DeviceConnectionState ConnectionState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.DeviceConnectionState ConnectionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Device.ConnectionState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionState As DeviceConnectionState" />
      <MemberSignature Language="F#" Value="member this.ConnectionState : Microsoft.Azure.Devices.DeviceConnectionState" Usage="Microsoft.Azure.Devices.Device.ConnectionState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeviceConnectionState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0320a-107">ConnectionState des Geräts</span><span class="sxs-lookup"><span data-stu-id="0320a-107">Device's ConnectionState</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionStateUpdatedTime">
      <MemberSignature Language="C#" Value="public DateTime ConnectionStateUpdatedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ConnectionStateUpdatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Device.ConnectionStateUpdatedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionStateUpdatedTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.ConnectionStateUpdatedTime : DateTime" Usage="Microsoft.Azure.Devices.Device.ConnectionStateUpdatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionStateUpdatedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0320a-108">Uhrzeit der Erstellung der <see cref="P:Microsoft.Azure.Devices.Device.ConnectionState" /> zuletzt aktualisiert wurde</span><span class="sxs-lookup"><span data-stu-id="0320a-108">Time when the <see cref="P:Microsoft.Azure.Devices.Device.ConnectionState" /> was last updated</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Device.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Devices.Device.ETag" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Devices.Shared.IETagHolder.ETag</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
        <summary>
            <span data-ttu-id="0320a-109">ETag des Geräts</span><span class="sxs-lookup"><span data-stu-id="0320a-109">Device's ETag</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerationId">
      <MemberSignature Language="C#" Value="public string GenerationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GenerationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Device.GenerationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GenerationId As String" />
      <MemberSignature Language="F#" Value="member this.GenerationId : string" Usage="Microsoft.Azure.Devices.Device.GenerationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="generationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0320a-110">Generations-ID des Geräts</span><span class="sxs-lookup"><span data-stu-id="0320a-110">Device's Generation ID</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Device.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Devices.Device.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deviceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0320a-111">Geräte-ID</span><span class="sxs-lookup"><span data-stu-id="0320a-111">Device ID</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastActivityTime">
      <MemberSignature Language="C#" Value="public DateTime LastActivityTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastActivityTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Device.LastActivityTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastActivityTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastActivityTime : DateTime" Usage="Microsoft.Azure.Devices.Device.LastActivityTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastActivityTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0320a-112">Uhrzeit der Erstellung der <see cref="T:Microsoft.Azure.Devices.Device" /> zuletzt aktiv war</span><span class="sxs-lookup"><span data-stu-id="0320a-112">Time when the <see cref="T:Microsoft.Azure.Devices.Device" /> was last active</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.DeviceStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.DeviceStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Device.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As DeviceStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Devices.DeviceStatus with get, set" Usage="Microsoft.Azure.Devices.Device.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeviceStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0320a-113">Der Gerätestatus</span><span class="sxs-lookup"><span data-stu-id="0320a-113">Device's Status</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusReason">
      <MemberSignature Language="C#" Value="public string StatusReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Device.StatusReason" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusReason As String" />
      <MemberSignature Language="F#" Value="member this.StatusReason : string with get, set" Usage="Microsoft.Azure.Devices.Device.StatusReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0320a-114">Deshalb ggf. für das Gerät in angegeben werden<see cref="P:Microsoft.Azure.Devices.Device.Status" /></span><span class="sxs-lookup"><span data-stu-id="0320a-114">Reason, if any, for the Device to be in specified <see cref="P:Microsoft.Azure.Devices.Device.Status" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusUpdatedTime">
      <MemberSignature Language="C#" Value="public DateTime StatusUpdatedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StatusUpdatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Device.StatusUpdatedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusUpdatedTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StatusUpdatedTime : DateTime" Usage="Microsoft.Azure.Devices.Device.StatusUpdatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusUpdatedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0320a-115">Uhrzeit der Erstellung der <see cref="P:Microsoft.Azure.Devices.Device.Status" /> zuletzt aktualisiert wurde</span><span class="sxs-lookup"><span data-stu-id="0320a-115">Time when the <see cref="P:Microsoft.Azure.Devices.Device.Status" /> was last updated</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>