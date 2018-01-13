<Type Name="WnsCredential" FullName="Microsoft.Azure.NotificationHubs.WnsCredential">
  <TypeSignature Language="C#" Value="public class WnsCredential : Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WnsCredential extends Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.WnsCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class WnsCredential&#xA;Inherits PnsCredential" />
  <TypeSignature Language="F#" Value="type WnsCredential = class&#xA;    inherit PnsCredential" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.PnsCredential</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="WnsCredential", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Stellt eine WNS-Anmeldeinformationen dar.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WnsCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WnsCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.WnsCredential" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WnsCredential (string packageSid, string secretKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string packageSid, string secretKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WnsCredential.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (packageSid As String, secretKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.WnsCredential : string * string -&gt; Microsoft.Azure.NotificationHubs.WnsCredential" Usage="new Microsoft.Azure.NotificationHubs.WnsCredential (packageSid, secretKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="packageSid" Type="System.String" />
        <Parameter Name="secretKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageSid">Die Paket-ID</param>
        <param name="secretKey">Der geheime Schlüssel.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.WnsCredential" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WnsCredential.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (other As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="wnsCredential.Equals other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="other">Die andere zu vergleichende Objekt.</param>
        <summary>Gibt an, ob diese Instanz os identisch mit dem angegebenen Objekt.</summary>
        <returns>Gibt <see cref="T:System.Boolean" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WnsCredential.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="wnsCredential.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft den Hashcode für die Anmeldeinformationen ab.</summary>
        <returns>Der Hashcode für die Anmeldeinformationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidate">
      <MemberSignature Language="C#" Value="protected override void OnValidate (bool allowLocalMockPns);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidate(bool allowLocalMockPns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WnsCredential.OnValidate(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidate (allowLocalMockPns As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnValidate : bool -&gt; unit" Usage="wnsCredential.OnValidate allowLocalMockPns" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="allowLocalMockPns" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="allowLocalMockPns">"true", um lokale simulierten PNS zu ermöglichen; andernfalls "false".</param>
        <summary>Überprüft die Anmeldeinformationen an.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PackageSid">
      <MemberSignature Language="C#" Value="public string PackageSid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PackageSid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.WnsCredential.PackageSid" />
      <MemberSignature Language="VB.NET" Value="Public Property PackageSid As String" />
      <MemberSignature Language="F#" Value="member this.PackageSid : string with get, set" Usage="Microsoft.Azure.NotificationHubs.WnsCredential.PackageSid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Paket-ID für diese Anmeldeinformation.</summary>
        <value>Die Paket-ID für diese Anmeldeinformation.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretKey">
      <MemberSignature Language="C#" Value="public string SecretKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.WnsCredential.SecretKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretKey As String" />
      <MemberSignature Language="F#" Value="member this.SecretKey : string with get, set" Usage="Microsoft.Azure.NotificationHubs.WnsCredential.SecretKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den für den geheimen Schlüssel fest.</summary>
        <value>Der geheime Schlüssel.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsLiveEndpoint">
      <MemberSignature Language="C#" Value="public string WindowsLiveEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsLiveEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.WnsCredential.WindowsLiveEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsLiveEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.WindowsLiveEndpoint : string with get, set" Usage="Microsoft.Azure.NotificationHubs.WnsCredential.WindowsLiveEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Windows Live-Endpunkt.</summary>
        <value>Der Windows Live-Endpunkt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>