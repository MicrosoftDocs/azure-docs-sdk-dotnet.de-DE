<Type Name="IssuerElement" FullName="Microsoft.Azure.NotificationHubs.Configuration.IssuerElement">
  <TypeSignature Language="C#" Value="public class IssuerElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IssuerElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Configuration.IssuerElement" />
  <TypeSignature Language="VB.NET" Value="Public Class IssuerElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type IssuerElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Ein Konfigurationselement, das einen Aussteller eines Tokens für den Windows Azure-Servicebus beschreibt.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.IssuerElement.Address" />
      <MemberSignature Language="VB.NET" Value="Public Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.IssuerElement.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("issuerAddress", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.StringValidator(MaxLength=2048, MinLength=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die URI-Adresse des Tokenausstellers.</summary>
        <value>Die URI-Adresse des Tokenausstellers.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public void CopyFrom (System.Configuration.ConfigurationElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyFrom(class System.Configuration.ConfigurationElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.IssuerElement.CopyFrom(System.Configuration.ConfigurationElement)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyFrom (from As ConfigurationElement)" />
      <MemberSignature Language="F#" Value="member this.CopyFrom : System.Configuration.ConfigurationElement -&gt; unit" Usage="issuerElement.CopyFrom from" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.Configuration.ConfigurationElement" />
      </Parameters>
      <Docs>
        <param name="from">Das Konfigurationselement zum Kopieren der Inhalte aus.</param>
        <summary>Kopiert den Inhalt des angegebenen Konfigurationselements in dieses Konfigurationselement.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.IssuerElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.Azure.NotificationHubs.Configuration.IssuerElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Auflistung der in diesem Konfigurationselement enthaltenen Eigenschaften ab.</summary>
        <value>Die Auflistung der in diesem Konfigurationselement enthaltenen Eigenschaften.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>