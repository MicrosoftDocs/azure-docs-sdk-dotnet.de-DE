<Type Name="WSHttpRelayBinding" FullName="Microsoft.ServiceBus.WSHttpRelayBinding">
  <TypeSignature Language="C#" Value="public abstract class WSHttpRelayBinding : Microsoft.ServiceBus.WSHttpRelayBindingBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit WSHttpRelayBinding extends Microsoft.ServiceBus.WSHttpRelayBindingBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WSHttpRelayBinding" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class WSHttpRelayBinding&#xA;Inherits WSHttpRelayBindingBase" />
  <TypeSignature Language="F#" Value="type WSHttpRelayBinding = class&#xA;    inherit WSHttpRelayBindingBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.WSHttpRelayBindingBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="79cd6-101">Stellt eine interoperable Bindung, die verteilte Transaktionen und sichere, zuverlässige Sitzungen über die Cloud unterstützt.</span><span class="sxs-lookup"><span data-stu-id="79cd6-101">Represents an interoperable binding that supports distributed transactions and secure, reliable sessions through the cloud.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBinding.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBinding.AllowCookies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="79cd6-102">Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Client Cookies akzeptiert und bei zukünftigen Anfragen weiterleitet.</span><span class="sxs-lookup"><span data-stu-id="79cd6-102">Gets or sets a value that indicates whether the client accepts cookies and propagates them on future requests.</span></span> </summary>
        <value><span data-ttu-id="79cd6-103">Gibt <see cref="T:System.Boolean" />.True zurück, wenn die Bindung Cookies zulässt, andernfalls false.</span><span class="sxs-lookup"><span data-stu-id="79cd6-103">Returns <see cref="T:System.Boolean" />.true if the binding allows cookies; otherwise, false.</span></span> <span data-ttu-id="79cd6-104">Der Standardwert ist false.</span><span class="sxs-lookup"><span data-stu-id="79cd6-104">The default is false.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSecurity">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBinding.CreateMessageSecurity" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateMessageSecurity () As SecurityBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateMessageSecurity : unit -&gt; System.ServiceModel.Channels.SecurityBindingElement" Usage="wSHttpRelayBinding.CreateMessageSecurity " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.SecurityBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="79cd6-105">Gibt das Sicherheitsbindungselement von der aktuellen Bindung zurück.</span><span class="sxs-lookup"><span data-stu-id="79cd6-105">Returns the security binding element from the current binding.</span></span></summary>
        <returns><span data-ttu-id="79cd6-106">Gibt eine <see cref="T:System.ServiceModel.Channels.SecurityBindingElement" /> , die die aktuelle Bindung enthält.</span><span class="sxs-lookup"><span data-stu-id="79cd6-106">Returns a <see cref="T:System.ServiceModel.Channels.SecurityBindingElement" /> that contains the current binding.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTransport">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.TransportBindingElement GetTransport ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.TransportBindingElement GetTransport() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBinding.GetTransport" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function GetTransport () As TransportBindingElement" />
      <MemberSignature Language="F#" Value="override this.GetTransport : unit -&gt; System.ServiceModel.Channels.TransportBindingElement" Usage="wSHttpRelayBinding.GetTransport " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.TransportBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="79cd6-107">Gibt das Transportbindungselement von der aktuellen Bindung zurück.</span><span class="sxs-lookup"><span data-stu-id="79cd6-107">Returns the transport binding element from the current binding.</span></span> </summary>
        <returns><span data-ttu-id="79cd6-108">Gibt <see cref="T:System.ServiceModel.Channels.TransportBindingElement" />. Enthält das Transportbindungselement von der aktuellen Bindung.</span><span class="sxs-lookup"><span data-stu-id="79cd6-108">Returns <see cref="T:System.ServiceModel.Channels.TransportBindingElement" />.Contains the transport binding element from the current binding.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.WSHttpRelaySecurity Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.WSHttpRelaySecurity Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBinding.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As WSHttpRelaySecurity" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.WSHttpRelaySecurity" Usage="Microsoft.ServiceBus.WSHttpRelayBinding.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.WSHttpRelaySecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="79cd6-109">Ruft die Sicherheitseinstellungen ab, die mit dieser Bindung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="79cd6-109">Gets the security settings used with this binding.</span></span> </summary>
        <value><span data-ttu-id="79cd6-110">Gibt eine <see cref="T:Microsoft.ServiceBus.WSHttpRelaySecurity" /> , die mit dieser Bindung verwendeten Sicherheitstypen enthält.</span><span class="sxs-lookup"><span data-stu-id="79cd6-110">Returns a <see cref="T:Microsoft.ServiceBus.WSHttpRelaySecurity" /> that contains the security used with this binding.</span></span> <span data-ttu-id="79cd6-111">Der Standardwert Mode-Eigenschaft wird die Nachricht.</span><span class="sxs-lookup"><span data-stu-id="79cd6-111">The default value Mode property is Message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>