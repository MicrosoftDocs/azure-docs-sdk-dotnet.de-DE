<Type Name="TokenProviderElement" FullName="Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement">
  <TypeSignature Language="C#" Value="public class TokenProviderElement : System.ServiceModel.Configuration.ClientCredentialsElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TokenProviderElement extends System.ServiceModel.Configuration.ClientCredentialsElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement" />
  <TypeSignature Language="VB.NET" Value="Public Class TokenProviderElement&#xA;Inherits ClientCredentialsElement" />
  <TypeSignature Language="F#" Value="type TokenProviderElement = class&#xA;    inherit ClientCredentialsElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.ClientCredentialsElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt das Konfigurationselement dar, das den Tokenanbieter für Service Bus angibt.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="tokenProviderElement.CopyFrom from" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.ServiceModel.Configuration.ServiceModelExtensionElement" />
      </Parameters>
      <Docs>
        <param name="from">Das Konfigurationselement zum Kopieren der Inhalte aus.</param>
        <summary>Kopiert den Inhalt des angegebenen Konfigurationselements in dieses Konfigurationselement.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("name", IsKey=true, IsRequired=false)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.StringValidator(InvalidCharacters=" ", MinLength=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Namen des angegebenen <see cref="T:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement" /> Objekt.</summary>
        <value>Das angegebene <see cref="T:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement" /> Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Auflistung von Eigenschaften, die in der Konfigurationselement enthalten.</summary>
        <value>Die Auflistung von Eigenschaften, die in der Konfigurationselement enthalten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement SharedAccessSignature { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SharedAccessSignature As SharedAccessSignatureElement" />
      <MemberSignature Language="F#" Value="member this.SharedAccessSignature : Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement" Usage="Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement.SharedAccessSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("sharedAccessSignature")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Configuration.SharedAccessSignatureElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das SAS-Signatur-Element ab.</summary>
        <value>Das SAS-Signatur-Element.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedSecret">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement SharedSecret { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement SharedSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement.SharedSecret" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SharedSecret As SharedSecretElement" />
      <MemberSignature Language="F#" Value="member this.SharedSecret : Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement" Usage="Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement.SharedSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("sharedSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das freigegebene geheime Element in der Tokenanbieter-Element enthalten.</summary>
        <value>Das freigegebene geheime-Element in der Tokenanbieter-Element enthalten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsAuthentication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Configuration.WindowsElement WindowsAuthentication { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.Configuration.WindowsElement WindowsAuthentication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement.WindowsAuthentication" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WindowsAuthentication As WindowsElement" />
      <MemberSignature Language="F#" Value="member this.WindowsAuthentication : Microsoft.Azure.NotificationHubs.Configuration.WindowsElement" Usage="Microsoft.Azure.NotificationHubs.Configuration.TokenProviderElement.WindowsAuthentication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("windowsAuthentication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Configuration.WindowsElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Windows-Authentifizierungseinstellungen für dieses Element ab.</summary>
        <value>Die Windows-Authentifizierungseinstellungen für dieses Element.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>