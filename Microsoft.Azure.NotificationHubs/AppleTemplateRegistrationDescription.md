<Type Name="AppleTemplateRegistrationDescription" FullName="Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription">
  <TypeSignature Language="C#" Value="public class AppleTemplateRegistrationDescription : Microsoft.Azure.NotificationHubs.AppleRegistrationDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppleTemplateRegistrationDescription extends Microsoft.Azure.NotificationHubs.AppleRegistrationDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class AppleTemplateRegistrationDescription&#xA;Inherits AppleRegistrationDescription" />
  <TypeSignature Language="F#" Value="type AppleTemplateRegistrationDescription = class&#xA;    inherit AppleRegistrationDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.AppleRegistrationDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="AppleTemplateRegistrationDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Stellt die Beschreibung des Apple-vorlagenregistrierung.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppleTemplateRegistrationDescription (Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription sourceRegistration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription sourceRegistration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription.#ctor(Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sourceRegistration As AppleTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription : Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription -&gt; Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription sourceRegistration" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceRegistration" Type="Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription" />
      </Parameters>
      <Docs>
        <param name="sourceRegistration">Die Quelle der Registrierung.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppleTemplateRegistrationDescription (string deviceToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceToken As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription : string -&gt; Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription deviceToken" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceToken">Das gerätetoken.</param>
        <summary>Initialisiert neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription" /> Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppleTemplateRegistrationDescription (string deviceToken, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceToken, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceToken As String, jsonPayload As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription : string * string -&gt; Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription (deviceToken, jsonPayload)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceToken">Das gerätetoken.</param>
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppleTemplateRegistrationDescription (string deviceToken, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deviceToken, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription.#ctor(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deviceToken As String, jsonPayload As String, tags As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription : string * string * seq&lt;string&gt; -&gt; Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription (deviceToken, jsonPayload, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="deviceToken">Das gerätetoken.</param>
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <param name="tags">Die Beschreibung-Tags.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BodyTemplate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.CDataMember BodyTemplate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.CDataMember BodyTemplate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription.BodyTemplate" />
      <MemberSignature Language="VB.NET" Value="Public Property BodyTemplate As CDataMember" />
      <MemberSignature Language="F#" Value="member this.BodyTemplate : Microsoft.Azure.NotificationHubs.CDataMember with get, set" Usage="Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription.BodyTemplate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=true, Name="BodyTemplate", Order=3001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.CDataMember</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Textvorlage.</summary>
        <value>Die Textvorlage.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expiry">
      <MemberSignature Language="C#" Value="public string Expiry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Expiry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription.Expiry" />
      <MemberSignature Language="VB.NET" Value="Public Property Expiry As String" />
      <MemberSignature Language="F#" Value="member this.Expiry : string with get, set" Usage="Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription.Expiry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=false, Name="Expiry", Order=3002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt sie fest, das Ablaufdatum und die Uhrzeit der Eintragung.</summary>
        <value>Das Ablaufdatum und die Uhrzeit der Eintragung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TemplateName">
      <MemberSignature Language="C#" Value="public string TemplateName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TemplateName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription.TemplateName" />
      <MemberSignature Language="VB.NET" Value="Public Property TemplateName As String" />
      <MemberSignature Language="F#" Value="member this.TemplateName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription.TemplateName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=false, Name="TemplateName", Order=3003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Namen der Vorlage.</summary>
        <value>Der Name der Vorlage.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>