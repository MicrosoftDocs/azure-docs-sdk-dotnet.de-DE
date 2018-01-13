<Type Name="SharedSecretElement" FullName="Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement">
  <TypeSignature Language="C#" Value="public class SharedSecretElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedSecretElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedSecretElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type SharedSecretElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="77274-101">Ein Konfigurationselement, das die Anmeldeinformationen für einen Dienst oder Client-Endpunkt angibt, die für die Verwendung konfiguriert ist die <see cref="F:Microsoft.Azure.NotificationHubs.TransportClientCredentialType.SharedSecret" /> Anmeldeinformationstyp.</span><span class="sxs-lookup"><span data-stu-id="77274-101">A configuration element that specifies the credentials for a service or client endpoint that is configured to use the <see cref="F:Microsoft.Azure.NotificationHubs.TransportClientCredentialType.SharedSecret" /> credential type.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public void CopyFrom (Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyFrom(class Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement.CopyFrom(Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyFrom (source As SharedSecretElement)" />
      <MemberSignature Language="F#" Value="member this.CopyFrom : Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement -&gt; unit" Usage="sharedSecretElement.CopyFrom source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="77274-102">Der freigegebene geheime Konfigurationselement kopiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="77274-102">The shared secret configuration element to be copied.</span></span></param>
        <summary><span data-ttu-id="77274-103">Kopiert den Inhalt des angegebenen freigegebenen geheimen Konfigurationselements in dieses Konfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="77274-103">Copies the contents of the specified shared secret configuration element to this configuration element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerName">
      <MemberSignature Language="C#" Value="public string IssuerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IssuerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement.IssuerName" />
      <MemberSignature Language="VB.NET" Value="Public Property IssuerName As String" />
      <MemberSignature Language="F#" Value="member this.IssuerName : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement.IssuerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("issuerName", IsRequired=true)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.StringValidator(MaxLength=128, MinLength=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="77274-104">Ruft ab oder legt den Namen des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="77274-104">Gets or sets the issuer name.</span></span></summary>
        <value><span data-ttu-id="77274-105">Der Ausstellername.</span><span class="sxs-lookup"><span data-stu-id="77274-105">The issuer name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerSecret">
      <MemberSignature Language="C#" Value="public string IssuerSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IssuerSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement.IssuerSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property IssuerSecret As String" />
      <MemberSignature Language="F#" Value="member this.IssuerSecret : string with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement.IssuerSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("issuerSecret", IsRequired=true)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.StringValidator(MaxLength=128, MinLength=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="77274-106">Ruft ab oder legt den für den geheimen Schlüssel des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="77274-106">Gets or sets the issuer secret key.</span></span></summary>
        <value><span data-ttu-id="77274-107">Der geheime Schlüssel des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="77274-107">The issuer secret key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="77274-108">Ruft die Eigenschaften dieses Konfigurationselements an, die den Ausstellernamen und den geheimen Schlüssel des Ausstellers enthalten.</span><span class="sxs-lookup"><span data-stu-id="77274-108">Gets the properties of this configuration element that contain the issuer name and the issuer secret key.</span></span></summary>
        <value><span data-ttu-id="77274-109">Die Eigenschaften dieses Konfigurationselements, die den Ausstellernamen und den geheimen Schlüssel des Ausstellers enthalten.</span><span class="sxs-lookup"><span data-stu-id="77274-109">The properties of this configuration element that contain the issuer name and the issuer secret key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenScope">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.TokenScope TokenScope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.NotificationHubs.TokenScope TokenScope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement.TokenScope" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenScope As TokenScope" />
      <MemberSignature Language="F#" Value="member this.TokenScope : Microsoft.Azure.NotificationHubs.TokenScope with get, set" Usage="Microsoft.Azure.NotificationHubs.Configuration.SharedSecretElement.TokenScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("tokenScope", DefaultValue=Mono.Cecil.CustomAttributeArgument, IsRequired=false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.TokenScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="77274-110">Ermittelt oder definiert das token Bereich.</span><span class="sxs-lookup"><span data-stu-id="77274-110">Gets or sets the token scope.</span></span></summary>
        <value><span data-ttu-id="77274-111">Der Bereich, auf das token.</span><span class="sxs-lookup"><span data-stu-id="77274-111">The token scope.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>