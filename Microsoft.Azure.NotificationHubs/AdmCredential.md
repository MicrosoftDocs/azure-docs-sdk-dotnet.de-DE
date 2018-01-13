<Type Name="AdmCredential" FullName="Microsoft.Azure.NotificationHubs.AdmCredential">
  <TypeSignature Language="C#" Value="public class AdmCredential : Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdmCredential extends Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.AdmCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class AdmCredential&#xA;Inherits PnsCredential" />
  <TypeSignature Language="F#" Value="type AdmCredential = class&#xA;    inherit PnsCredential" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="AdmCredential", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Gibt die Anmeldeinformationen Amazon Device Messaging (ADM).</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdmCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AdmCredential" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdmCredential (string clientId, string clientSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string clientSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmCredential.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String, clientSecret As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AdmCredential : string * string -&gt; Microsoft.Azure.NotificationHubs.AdmCredential" Usage="new Microsoft.Azure.NotificationHubs.AdmCredential (clientId, clientSecret)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="clientSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId">The client identifier. (Der Clientbezeichner.)</param>
        <param name="clientSecret">Die Anmeldeinformationen für den geheimen Tastenkombination.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AdmCredential" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthTokenUrl">
      <MemberSignature Language="C#" Value="public string AuthTokenUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthTokenUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AdmCredential.AuthTokenUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthTokenUrl As String" />
      <MemberSignature Language="F#" Value="member this.AuthTokenUrl : string with get, set" Usage="Microsoft.Azure.NotificationHubs.AdmCredential.AuthTokenUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die URL des autorisierungstokens fest.</summary>
        <value>Die URL der das Autorisierungstoken.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AdmCredential.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string with get, set" Usage="Microsoft.Azure.NotificationHubs.AdmCredential.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Clientbezeichner.</summary>
        <value>The client identifier. (Der Clientbezeichner.)</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientSecret">
      <MemberSignature Language="C#" Value="public string ClientSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AdmCredential.ClientSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientSecret As String" />
      <MemberSignature Language="F#" Value="member this.ClientSecret : string with get, set" Usage="Microsoft.Azure.NotificationHubs.AdmCredential.ClientSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Anmeldeinformationen Zugriff für den geheimen Schlüssel fest.</summary>
        <value>Die Anmeldeinformationen für den geheimen Tastenkombination.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmCredential.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (other As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="admCredential.Equals other" />
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
        <param name="other">Das zu vergleichende Objekt.</param>
        <summary>Gibt an, ob die Anmeldeinformationen mit dem angegebenen Objekt identisch ist.</summary>
        <returns>"true", wenn diese Anmeldeinformationen mit dem bestimmten Objekt gleich sind; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmCredential.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="admCredential.GetHashCode " />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmCredential.OnValidate(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidate (allowLocalMockPns As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnValidate : bool -&gt; unit" Usage="admCredential.OnValidate allowLocalMockPns" />
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
        <summary>Überprüft die Amazon Device Messaging-Anmeldeinformationen an.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Runtime.Serialization.InvalidDataContractException" />
      </Docs>
    </Member>
    <Member MemberName="SendUrlTemplate">
      <MemberSignature Language="C#" Value="public string SendUrlTemplate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SendUrlTemplate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AdmCredential.SendUrlTemplate" />
      <MemberSignature Language="VB.NET" Value="Public Property SendUrlTemplate As String" />
      <MemberSignature Language="F#" Value="member this.SendUrlTemplate : string with get, set" Usage="Microsoft.Azure.NotificationHubs.AdmCredential.SendUrlTemplate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Abrufen oder Festlegen der sendende URL-Vorlage.</summary>
        <value>Die sendende URL-Vorlage.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>