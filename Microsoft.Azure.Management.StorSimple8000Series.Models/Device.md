<Type Name="Device" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Device">
  <TypeSignature Language="C#" Value="public class Device : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Device extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Device" />
  <TypeSignature Language="VB.NET" Value="Public Class Device&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type Device = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Das StorSimple-Gerät.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Device ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse Gerät an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Device (string friendlyName, DateTime activationTime, string culture, string deviceDescription, string deviceSoftwareVersion, Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus deviceConfigurationStatus, string targetIqn, string modelDescription, Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus status, string serialNumber, Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType deviceType, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId activeController, string friendlySoftwareVersion, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, string friendlySoftwareName = null, Nullable&lt;long&gt; availableLocalStorageInBytes = null, Nullable&lt;long&gt; availableTieredStorageInBytes = null, Nullable&lt;long&gt; provisionedTieredStorageInBytes = null, Nullable&lt;long&gt; provisionedLocalStorageInBytes = null, Nullable&lt;long&gt; provisionedVolumeSizeInBytes = null, Nullable&lt;long&gt; usingStorageInBytes = null, Nullable&lt;long&gt; totalTieredStorageInBytes = null, Nullable&lt;int&gt; agentGroupVersion = null, Nullable&lt;int&gt; networkInterfaceCardCount = null, string deviceLocation = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt; virtualMachineApiType = null, Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails details = null, Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails rolloverDetails = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, valuetype System.DateTime activationTime, string culture, string deviceDescription, string deviceSoftwareVersion, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus deviceConfigurationStatus, string targetIqn, string modelDescription, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus status, string serialNumber, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType deviceType, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId activeController, string friendlySoftwareVersion, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, string friendlySoftwareName, valuetype System.Nullable`1&lt;int64&gt; availableLocalStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; availableTieredStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; provisionedTieredStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; provisionedLocalStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; provisionedVolumeSizeInBytes, valuetype System.Nullable`1&lt;int64&gt; usingStorageInBytes, valuetype System.Nullable`1&lt;int64&gt; totalTieredStorageInBytes, valuetype System.Nullable`1&lt;int32&gt; agentGroupVersion, valuetype System.Nullable`1&lt;int32&gt; networkInterfaceCardCount, string deviceLocation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt; virtualMachineApiType, class Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails details, class Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails rolloverDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.#ctor(System.String,System.DateTime,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType},Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails,Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Device : string * DateTime * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus * string * Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails * Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Device" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Device (friendlyName, activationTime, culture, deviceDescription, deviceSoftwareVersion, deviceConfigurationStatus, targetIqn, modelDescription, status, serialNumber, deviceType, activeController, friendlySoftwareVersion, id, name, type, kind, friendlySoftwareName, availableLocalStorageInBytes, availableTieredStorageInBytes, provisionedTieredStorageInBytes, provisionedLocalStorageInBytes, provisionedVolumeSizeInBytes, usingStorageInBytes, totalTieredStorageInBytes, agentGroupVersion, networkInterfaceCardCount, deviceLocation, virtualMachineApiType, details, rolloverDetails)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="activationTime" Type="System.DateTime" />
        <Parameter Name="culture" Type="System.String" />
        <Parameter Name="deviceDescription" Type="System.String" />
        <Parameter Name="deviceSoftwareVersion" Type="System.String" />
        <Parameter Name="deviceConfigurationStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus" />
        <Parameter Name="targetIqn" Type="System.String" />
        <Parameter Name="modelDescription" Type="System.String" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus" />
        <Parameter Name="serialNumber" Type="System.String" />
        <Parameter Name="deviceType" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType" />
        <Parameter Name="activeController" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId" />
        <Parameter Name="friendlySoftwareVersion" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="friendlySoftwareName" Type="System.String" />
        <Parameter Name="availableLocalStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="availableTieredStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="provisionedTieredStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="provisionedLocalStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="provisionedVolumeSizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="usingStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="totalTieredStorageInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="agentGroupVersion" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="networkInterfaceCardCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="deviceLocation" Type="System.String" />
        <Parameter Name="virtualMachineApiType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt;" />
        <Parameter Name="details" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails" />
        <Parameter Name="rolloverDetails" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails" />
      </Parameters>
      <Docs>
        <param name="friendlyName">Der Anzeigename des Geräts.</param>
        <param name="activationTime">Die UTC-Zeit, zu der das Gerät aktiviert wurde.</param>
        <param name="culture">Die Sprache-Kultur-Einstellung auf dem Gerät.
            Für z. B.: "En-US"</param>
        <param name="deviceDescription">Die gerätebeschreibung.</param>
        <param name="deviceSoftwareVersion">Die Versionsnummer der Software auf dem Gerät ausgeführt werden soll.</param>
        <param name="deviceConfigurationStatus">Den aktuellen Konfigurationsstatus des Geräts. Folgende Werte sind möglich: "Abgeschlossen", "Ausstehend"</param>
        <param name="targetIqn">Das Ziel-IQN.</param>
        <param name="modelDescription">Das Gerätemodell.</param>
        <param name="status">Der aktuelle Status des Geräts. Folgende Werte sind möglich: "Unknown", "Online", "Offline", "Deaktiviert", "RequiresAttention", "MaintenanceMode", "Erstellen", "Bereitstellung", "Deaktivieren", "Deleted", "ReadyToSetup"</param>
        <param name="serialNumber">Die Seriennummer.</param>
        <param name="deviceType">Der Typ des Geräts. Folgende Werte sind möglich: "Ungültig", "Series8000VirtualAppliance", "Series8000PhysicalAppliance"</param>
        <param name="activeController">Der Bezeichner für den aktiven Controller des Geräts. Folgende Werte sind möglich: "Unknown", "None", "Controller0", "Controller1"</param>
        <param name="friendlySoftwareVersion">Die benutzerfreundliche Version der Gerätesoftware.</param>
        <param name="id">Die Pfad-ID, die das Objekt eindeutig identifiziert.</param>
        <param name="name">Der Name des Objekts.</param>
        <param name="type">Der hierarchische Typ des Objekts.</param>
        <param name="kind">Die Art des Objekts. Derzeit wird nur Series8000 wird unterstützt. Folgende Werte sind möglich: "Series8000"</param>
        <param name="friendlySoftwareName">Der angezeigte Name der Software auf dem Gerät ausgeführt werden soll.</param>
        <param name="availableLocalStorageInBytes">Der Speicher in Bytes, der lokal auf dem Gerät verfügbar ist.</param>
        <param name="availableTieredStorageInBytes">Der Speicher in Bytes, der auf dem Gerät bei mehrstufigen Volumes verfügbar ist.</param>
        <param name="provisionedTieredStorageInBytes">Der Speicher in Bytes, der auf dem Gerät bei mehrstufigen Volumes bereitgestellt wurde.</param>
        <param name="provisionedLocalStorageInBytes">Der Speicher in Bytes, die bei lokalen Volumes auf dem Gerät (einschließlich zusätzliche lokale Reservierung) verwendet werden soll.</param>
        <param name="provisionedVolumeSizeInBytes">Gesamtkapazität des mehrstufigen und lokale Volumes auf dem Gerät in bytes</param>
        <param name="usingStorageInBytes">Der Speicher in Bytes, die zurzeit auf dem Gerät, einschließlich sowohl lokale Pipes verwendet wird und der Cloud.</param>
        <param name="totalTieredStorageInBytes">Mehrstufigen verfügbaren Gesamtspeicher auf dem Gerät in Bytes.</param>
        <param name="agentGroupVersion">Die Version der Geräte-Agent-Gruppe.</param>
        <param name="networkInterfaceCardCount">Die Anzahl der Netzwerkkarten</param>
        <param name="deviceLocation">Der Speicherort des virtuellen Geräts.</param>
        <param name="virtualMachineApiType">Der Typ des virtuellen Computers API.
            Folgende Werte sind möglich: "Klassisch", "Arm"</param>
        <param name="details">Die Gerätedetails in Bezug auf die Endpunkt-Anzahl und die Anzahl der Volume-Container zusätzliche.</param>
        <param name="rolloverDetails">Der zusätzliche Gerätedetails für den Dienst Rollover des datenverschlüsselungsschlüssels.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Gerät an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivationTime">
      <MemberSignature Language="C#" Value="public DateTime ActivationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ActivationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ActivationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ActivationTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.ActivationTime : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ActivationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die UTC-Zeit, zu der das Gerät aktiviert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveController">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId ActiveController { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId ActiveController" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ActiveController" />
      <MemberSignature Language="VB.NET" Value="Public Property ActiveController As ControllerId" />
      <MemberSignature Language="F#" Value="member this.ActiveController : Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ActiveController" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activeController")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Bezeichner der dem aktiven Controller des Geräts.
            Folgende Werte sind möglich: "Unknown", "None", "Controller0", "Controller1"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AgentGroupVersion">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AgentGroupVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AgentGroupVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.AgentGroupVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property AgentGroupVersion As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AgentGroupVersion : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.AgentGroupVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.agentGroupVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Geräte-Agent-Gruppe-Version.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableLocalStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; AvailableLocalStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; AvailableLocalStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.AvailableLocalStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableLocalStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.AvailableLocalStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.AvailableLocalStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availableLocalStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Speicher in Bytes, die lokal auf dem Gerät verfügbar ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableTieredStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; AvailableTieredStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; AvailableTieredStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.AvailableTieredStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableTieredStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.AvailableTieredStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.AvailableTieredStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availableTieredStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Speicher in Bytes, die auf dem Gerät bei mehrstufigen Volumes verfügbar ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Culture">
      <MemberSignature Language="C#" Value="public string Culture { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Culture" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Culture" />
      <MemberSignature Language="VB.NET" Value="Public Property Culture As String" />
      <MemberSignature Language="F#" Value="member this.Culture : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Culture" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.culture")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Spracheinstellung für die Kultur auf dem Gerät. Für z. B.: "En-US"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As DeviceDetails" />
      <MemberSignature Language="F#" Value="member this.Details : Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der zusätzlichen Gerätedetails in Bezug auf die Endpunkt-Anzahl und die Anzahl der Volume-Container.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceConfigurationStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus DeviceConfigurationStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus DeviceConfigurationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceConfigurationStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceConfigurationStatus As DeviceConfigurationStatus" />
      <MemberSignature Language="F#" Value="member this.DeviceConfigurationStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceConfigurationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceConfigurationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceConfigurationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den aktuellen Konfigurationsstatus des Geräts.
            Folgende Werte sind möglich: "Abgeschlossen", "Ausstehend"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceDescription">
      <MemberSignature Language="C#" Value="public string DeviceDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceDescription As String" />
      <MemberSignature Language="F#" Value="member this.DeviceDescription : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die gerätebeschreibung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceLocation">
      <MemberSignature Language="C#" Value="public string DeviceLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceLocation As String" />
      <MemberSignature Language="F#" Value="member this.DeviceLocation : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Speicherort des virtuellen Geräts fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceSoftwareVersion">
      <MemberSignature Language="C#" Value="public string DeviceSoftwareVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceSoftwareVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceSoftwareVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceSoftwareVersion As String" />
      <MemberSignature Language="F#" Value="member this.DeviceSoftwareVersion : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceSoftwareVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceSoftwareVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Versionsnummer der Software auf dem Gerät ausgeführt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType DeviceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType DeviceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceType" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceType As DeviceType" />
      <MemberSignature Language="F#" Value="member this.DeviceType : Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.DeviceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ des Geräts fest. Folgende Werte sind möglich: "Ungültig", "Series8000VirtualAppliance", "Series8000PhysicalAppliance"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.FriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.friendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Anzeigenamen des Geräts.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlySoftwareName">
      <MemberSignature Language="C#" Value="public string FriendlySoftwareName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlySoftwareName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.FriendlySoftwareName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlySoftwareName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlySoftwareName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.FriendlySoftwareName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.friendlySoftwareName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Anzeigenamen der Software auf dem Gerät ausgeführt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlySoftwareVersion">
      <MemberSignature Language="C#" Value="public string FriendlySoftwareVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlySoftwareVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.FriendlySoftwareVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlySoftwareVersion As String" />
      <MemberSignature Language="F#" Value="member this.FriendlySoftwareVersion : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.FriendlySoftwareVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.friendlySoftwareVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die benutzerfreundliche Version der Gerätesoftware.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModelDescription">
      <MemberSignature Language="C#" Value="public string ModelDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ModelDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ModelDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property ModelDescription As String" />
      <MemberSignature Language="F#" Value="member this.ModelDescription : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ModelDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.modelDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Gerätemodell.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceCardCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NetworkInterfaceCardCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NetworkInterfaceCardCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.NetworkInterfaceCardCount" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterfaceCardCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceCardCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.NetworkInterfaceCardCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkInterfaceCardCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Netzwerkkarten
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisionedLocalStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProvisionedLocalStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProvisionedLocalStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ProvisionedLocalStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisionedLocalStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProvisionedLocalStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ProvisionedLocalStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisionedLocalStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Speicher in Bytes, die bei lokalen Volumes auf dem Gerät (einschließlich zusätzliche lokale Reservierung) verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisionedTieredStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProvisionedTieredStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProvisionedTieredStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ProvisionedTieredStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisionedTieredStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProvisionedTieredStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ProvisionedTieredStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisionedTieredStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Speicher in Bytes, der auf dem Gerät bei mehrstufigen Volumes bereitgestellt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisionedVolumeSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProvisionedVolumeSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProvisionedVolumeSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ProvisionedVolumeSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisionedVolumeSizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProvisionedVolumeSizeInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.ProvisionedVolumeSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisionedVolumeSizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Gesamtkapazität in Byte mehrstufigen und lokale Volumes auf dem Gerät
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RolloverDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails RolloverDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails RolloverDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.RolloverDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property RolloverDetails As DeviceRolloverDetails" />
      <MemberSignature Language="F#" Value="member this.RolloverDetails : Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.RolloverDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.rolloverDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceRolloverDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die zusätzlichen Gerätedetails für den Dienst Rollover des datenverschlüsselungsschlüssels.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerialNumber">
      <MemberSignature Language="C#" Value="public string SerialNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SerialNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.SerialNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SerialNumber As String" />
      <MemberSignature Language="F#" Value="member this.SerialNumber : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.SerialNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serialNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Seriennummer.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As DeviceStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DeviceStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den aktuellen Status des Geräts. Folgende Werte sind möglich: "Unknown", "Online", "Offline", "Deaktiviert", "RequiresAttention", "MaintenanceMode", "Erstellen", "Bereitstellung", "Deaktivieren", "Deleted", "ReadyToSetup"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetIqn">
      <MemberSignature Language="C#" Value="public string TargetIqn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetIqn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.TargetIqn" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetIqn As String" />
      <MemberSignature Language="F#" Value="member this.TargetIqn : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.TargetIqn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetIqn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Ziel-IQN.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTieredStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TotalTieredStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TotalTieredStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.TotalTieredStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalTieredStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TotalTieredStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.TotalTieredStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.totalTieredStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt mehrstufigen verfügbaren Gesamtspeicher auf dem Gerät in Bytes.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsingStorageInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; UsingStorageInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; UsingStorageInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.UsingStorageInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property UsingStorageInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.UsingStorageInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.UsingStorageInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usingStorageInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Sie den Speicher in Bytes, die zurzeit auf dem Gerät, einschließlich sowohl lokale Pipes verwendet wird und der Cloud.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="device.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineApiType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt; VirtualMachineApiType { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt; VirtualMachineApiType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Device.VirtualMachineApiType" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineApiType As Nullable(Of VirtualMachineApiType)" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineApiType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Device.VirtualMachineApiType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachineApiType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VirtualMachineApiType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den virtuellen Computer API ab. Folgende Werte sind möglich: "Klassisch", "Arm"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>