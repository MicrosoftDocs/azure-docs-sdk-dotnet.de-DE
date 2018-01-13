<Type Name="WSHttpRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement">
  <TypeSignature Language="C#" Value="public abstract class WSHttpRelayBindingElement : Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit WSHttpRelayBindingElement extends Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class WSHttpRelayBindingElement&#xA;Inherits WSHttpRelayBindingBaseElement" />
  <TypeSignature Language="F#" Value="type WSHttpRelayBindingElement = class&#xA;    inherit WSHttpRelayBindingBaseElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="0d915-101">Ein Konfigurationselement, das eine interoperable Bindung darstellt, die verteilte Transaktionen und sichere, zuverlässige Sitzungen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="0d915-101">A configuration element that represents an interoperable binding that supports distributed transactions and secure, reliable sessions.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.AllowCookies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("allowCookies", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="0d915-102">Ruft ab oder legt einen Wert, der angibt, ob der Dienst oder Client Cookies akzeptiert und für zukünftige Anfragen propagiert.</span><span class="sxs-lookup"><span data-stu-id="0d915-102">Gets or sets a value that indicates whether the service or client accepts cookies and propagates them on future requests.</span></span></summary>
        <value><span data-ttu-id="0d915-103">"true", wenn der Dienst oder Client Cookies akzeptiert und für zukünftige Anfragen propagiert; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="0d915-103">true if the service or client accepts cookies and propagates them on future requests; otherwise, false.</span></span> <span data-ttu-id="0d915-104">Der Standardwert ist false.</span><span class="sxs-lookup"><span data-stu-id="0d915-104">The default is false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="0d915-105">Ruft den Typ des der <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</span><span class="sxs-lookup"><span data-stu-id="0d915-105">Gets the type of the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></summary>
        <value><span data-ttu-id="0d915-106">Der Typ des der <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</span><span class="sxs-lookup"><span data-stu-id="0d915-106">The type of the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="wSHttpRelayBindingElement.InitializeFrom binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> <span data-ttu-id="0d915-107">Die Bindung zum Initialisieren dieses Konfigurationselements aus.</span><span class="sxs-lookup"><span data-stu-id="0d915-107">The binding to initialize this configuration element from.</span></span></param>
        <summary><span data-ttu-id="0d915-108">Initialisiert dieses bindungskonfigurationselement mit dem Inhalt der angegebenen Bindung.</span><span class="sxs-lookup"><span data-stu-id="0d915-108">Initializes this binding configuration element with the content of the specfied binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="wSHttpRelayBindingElement.OnApplyConfiguration binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> <span data-ttu-id="0d915-109">Die Bindung, die Einstellungen zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="0d915-109">The binding to update the settings of.</span></span></param>
        <summary><span data-ttu-id="0d915-110">Wendet die Einstellungen dieses Konfigurationselements auf die angegebene Bindung.</span><span class="sxs-lookup"><span data-stu-id="0d915-110">Applies the settings of this configuration element to the specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="0d915-111">Ruft eine Auflistung von Eigenschaften für dieses bindungskonfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="0d915-111">Gets a collection of properties of this binding configuration element.</span></span></summary>
        <value><span data-ttu-id="0d915-112">Eine Auflistung von Eigenschaften für dieses bindungskonfigurationselement.</span><span class="sxs-lookup"><span data-stu-id="0d915-112">A collection of properties of this binding configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As WSHttpRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("security")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="0d915-113">Ruft die <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" /> Konfigurationselement, die Sicherheitseinstellungen für enthält, die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</span><span class="sxs-lookup"><span data-stu-id="0d915-113">Gets the <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" /> configuration element that contains the security settings for the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></summary>
        <value><span data-ttu-id="0d915-114">Die <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" /> Konfigurationselement, die Sicherheitseinstellungen für enthält, die <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> Bindung.</span><span class="sxs-lookup"><span data-stu-id="0d915-114">The <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" /> configuration element that contains the security settings for the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>