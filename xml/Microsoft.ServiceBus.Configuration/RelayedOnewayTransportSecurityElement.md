<Type Name="RelayedOnewayTransportSecurityElement" FullName="Microsoft.ServiceBus.Configuration.RelayedOnewayTransportSecurityElement">
  <TypeSignature Language="C#" Value="public sealed class RelayedOnewayTransportSecurityElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RelayedOnewayTransportSecurityElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportSecurityElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RelayedOnewayTransportSecurityElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type RelayedOnewayTransportSecurityElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="92aea-101">Ein Konfigurationselement, steuert die transportsicherheitseinstellungen für die <see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" /> und <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> Typen.</span><span class="sxs-lookup"><span data-stu-id="92aea-101">A configuration element that controls transport security settings for the <see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" /> and <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> types.</span></span> <span data-ttu-id="92aea-102">Diese Klasse kann nicht vererbt werden.</span><span class="sxs-lookup"><span data-stu-id="92aea-102">This class cannot be inherited.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayedOnewayTransportSecurityElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportSecurityElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportSecurityElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.RelayedOnewayTransportSecurityElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92aea-103">Ruft die Auflistung von Eigenschaften ab.</span><span class="sxs-lookup"><span data-stu-id="92aea-103">Gets the collection of properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionLevel">
      <MemberSignature Language="C#" Value="public System.Net.Security.ProtectionLevel ProtectionLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.Security.ProtectionLevel ProtectionLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.RelayedOnewayTransportSecurityElement.ProtectionLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionLevel As ProtectionLevel" />
      <MemberSignature Language="F#" Value="member this.ProtectionLevel : System.Net.Security.ProtectionLevel with get, set" Usage="Microsoft.ServiceBus.Configuration.RelayedOnewayTransportSecurityElement.ProtectionLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("protectionLevel", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Security.ProtectionLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="92aea-104">Abrufen oder Festlegen der Schutzebene für den Transport, die für Nachrichten verwendet, die durch Bindungen, die mit diesem Konfigurationselement konfiguriert übertragen angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="92aea-104">Gets or sets the transport security protection level that is applied to messages transmitted through bindings configured with this configuration element.</span></span></summary>
        <value><span data-ttu-id="92aea-105">Gibt eine <see cref="T:System.Net.Security.ProtectionLevel" /> , die in diesem Konfigurationselement angegebene Transport Sicherheit Schutzebene enthält.</span><span class="sxs-lookup"><span data-stu-id="92aea-105">Returns a <see cref="T:System.Net.Security.ProtectionLevel" /> that contains the transport security protection level specified in this configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>