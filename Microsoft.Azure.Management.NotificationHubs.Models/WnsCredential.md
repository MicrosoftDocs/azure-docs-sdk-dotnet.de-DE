<Type Name="WnsCredential" FullName="Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential">
  <TypeSignature Language="C#" Value="public class WnsCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WnsCredential extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class WnsCredential" />
  <TypeSignature Language="F#" Value="type WnsCredential = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            Beschreibung des eine NotificationHub-WnsCredential.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WnsCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der WnsCredential-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WnsCredential (string packageSid = null, string secretKey = null, string windowsLiveEndpoint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string packageSid, string secretKey, string windowsLiveEndpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional packageSid As String = null, Optional secretKey As String = null, Optional windowsLiveEndpoint As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential : string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential (packageSid, secretKey, windowsLiveEndpoint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="packageSid" Type="System.String" />
        <Parameter Name="secretKey" Type="System.String" />
        <Parameter Name="windowsLiveEndpoint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageSid">Die Paket-ID für diese Anmeldeinformation.</param>
        <param name="secretKey">Der geheime Schlüssel.</param>
        <param name="windowsLiveEndpoint">Der Windows Live-Endpunkt.</param>
        <summary>
            Initialisiert eine neue Instanz der WnsCredential-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PackageSid">
      <MemberSignature Language="C#" Value="public string PackageSid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PackageSid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.PackageSid" />
      <MemberSignature Language="VB.NET" Value="Public Property PackageSid As String" />
      <MemberSignature Language="F#" Value="member this.PackageSid : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.PackageSid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.packageSid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Paket-ID für diese Anmeldeinformation.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretKey">
      <MemberSignature Language="C#" Value="public string SecretKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.SecretKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretKey As String" />
      <MemberSignature Language="F#" Value="member this.SecretKey : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.SecretKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.secretKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den für den geheimen Schlüssel fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsLiveEndpoint">
      <MemberSignature Language="C#" Value="public string WindowsLiveEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsLiveEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.WindowsLiveEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsLiveEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.WindowsLiveEndpoint : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.WindowsLiveEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.windowsLiveEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Windows Live-Endpunkt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>