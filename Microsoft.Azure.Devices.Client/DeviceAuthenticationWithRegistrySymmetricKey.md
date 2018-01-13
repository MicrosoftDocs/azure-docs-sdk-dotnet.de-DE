<Type Name="DeviceAuthenticationWithRegistrySymmetricKey" FullName="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey">
  <TypeSignature Language="C#" Value="public sealed class DeviceAuthenticationWithRegistrySymmetricKey : Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeviceAuthenticationWithRegistrySymmetricKey extends System.Object implements class Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeviceAuthenticationWithRegistrySymmetricKey&#xA;Implements IAuthenticationMethod" />
  <TypeSignature Language="F#" Value="type DeviceAuthenticationWithRegistrySymmetricKey = class&#xA;    interface IAuthenticationMethod" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Devices.Client.IAuthenticationMethod</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Die Authentifizierungsmethode, die den symmetrischen Schlüssel zugeordnete Gerät in die Registrierung des Geräts verwendet. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceAuthenticationWithRegistrySymmetricKey (string deviceId, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceId, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceId As String, key As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey : string * string -&gt; Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey" Usage="new Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey (deviceId, key)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">Gerätebezeichner.</param>
        <param name="key">Symmetrische Schlüssel, die dem Gerät zugeordnet werden.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceId">
      <MemberSignature Language="C#" Value="public string DeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey.DeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceId As String" />
      <MemberSignature Language="F#" Value="member this.DeviceId : string with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey.DeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt Sie die Geräte-ID fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public byte[] Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As Byte()" />
      <MemberSignature Language="F#" Value="member this.Key : byte[] with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Schlüssel, der dem Gerät zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyAsBase64String">
      <MemberSignature Language="C#" Value="public string KeyAsBase64String { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyAsBase64String" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey.KeyAsBase64String" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyAsBase64String As String" />
      <MemberSignature Language="F#" Value="member this.KeyAsBase64String : string with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey.KeyAsBase64String" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den formatierten Base64-Schlüssel, die dem Gerät zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Populate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder Populate (Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder iotHubConnectionStringBuilder);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder Populate(class Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder iotHubConnectionStringBuilder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithRegistrySymmetricKey.Populate(Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder)" />
      <MemberSignature Language="F#" Value="abstract member Populate : Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder -&gt; Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder&#xA;override this.Populate : Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder -&gt; Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" Usage="deviceAuthenticationWithRegistrySymmetricKey.Populate iotHubConnectionStringBuilder" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Devices.Client.IAuthenticationMethod.Populate(Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="iotHubConnectionStringBuilder" Type="Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" />
      </Parameters>
      <Docs>
        <param name="iotHubConnectionStringBuilder">Die Instanz zum Auffüllen.</param>
        <summary>
            Füllt ein <see cref="T:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" /> -Instanz auf Grundlage der Eigenschaften der aktuellen Instanz.
            </summary>
        <returns>Die aufgefüllte <see cref="T:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" /> Instanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>