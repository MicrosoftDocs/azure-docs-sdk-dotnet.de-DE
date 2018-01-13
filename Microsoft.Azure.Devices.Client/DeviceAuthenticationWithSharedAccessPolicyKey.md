<Type Name="DeviceAuthenticationWithSharedAccessPolicyKey" FullName="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey">
  <TypeSignature Language="C#" Value="public sealed class DeviceAuthenticationWithSharedAccessPolicyKey : Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeviceAuthenticationWithSharedAccessPolicyKey extends System.Object implements class Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeviceAuthenticationWithSharedAccessPolicyKey&#xA;Implements IAuthenticationMethod" />
  <TypeSignature Language="F#" Value="type DeviceAuthenticationWithSharedAccessPolicyKey = class&#xA;    interface IAuthenticationMethod" />
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
            Die Authentifizierungsmethode, die einen SAS-Richtlinienschlüssel verwendet. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceAuthenticationWithSharedAccessPolicyKey (string deviceId, string policyName, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceId, string policyName, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceId As String, policyName As String, key As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey : string * string * string -&gt; Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey" Usage="new Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey (deviceId, policyName, key)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">Gerätebezeichner.</param>
        <param name="policyName">Name der Richtlinie für freigegebenen Zugriff zu verwenden.</param>
        <param name="key">Schlüssel, die die SAS-Richtlinie zugeordnet werden.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceId">
      <MemberSignature Language="C#" Value="public string DeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey.DeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceId As String" />
      <MemberSignature Language="F#" Value="member this.DeviceId : string with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey.DeviceId" />
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
      <MemberSignature Language="C#" Value="public string Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey.Key" />
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
            Ruft ab oder legt den Schlüssel, der freigegebene Richtlinie zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyName">
      <MemberSignature Language="C#" Value="public string PolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey.PolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyName As String" />
      <MemberSignature Language="F#" Value="member this.PolicyName : string with get, set" Usage="Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey.PolicyName" />
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
            Der Name der Richtlinie für freigegebenen Zugriff.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Populate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder Populate (Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder iotHubConnectionStringBuilder);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder Populate(class Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder iotHubConnectionStringBuilder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.DeviceAuthenticationWithSharedAccessPolicyKey.Populate(Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder)" />
      <MemberSignature Language="F#" Value="abstract member Populate : Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder -&gt; Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder&#xA;override this.Populate : Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder -&gt; Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" Usage="deviceAuthenticationWithSharedAccessPolicyKey.Populate iotHubConnectionStringBuilder" />
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