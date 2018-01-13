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
    <summary>Stellt eine interoperable Bindung, die verteilte Transaktionen und sichere, zuverlässige Sitzungen über die Cloud unterstützt. </summary>
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
        <summary>Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Client Cookies akzeptiert und bei zukünftigen Anfragen weiterleitet. </summary>
        <value>Gibt <see cref="T:System.Boolean" />.True zurück, wenn die Bindung Cookies zulässt, andernfalls false. Der Standardwert ist false. </value>
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
        <summary>Gibt das Sicherheitsbindungselement von der aktuellen Bindung zurück.</summary>
        <returns>Gibt eine <see cref="T:System.ServiceModel.Channels.SecurityBindingElement" /> , die die aktuelle Bindung enthält. </returns>
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
        <summary>Gibt das Transportbindungselement von der aktuellen Bindung zurück. </summary>
        <returns>Gibt <see cref="T:System.ServiceModel.Channels.TransportBindingElement" />. Enthält das Transportbindungselement von der aktuellen Bindung.</returns>
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
        <summary>Ruft die Sicherheitseinstellungen ab, die mit dieser Bindung verwendet werden. </summary>
        <value>Gibt eine <see cref="T:Microsoft.ServiceBus.WSHttpRelaySecurity" /> , die mit dieser Bindung verwendeten Sicherheitstypen enthält. Der Standardwert Mode-Eigenschaft wird die Nachricht.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>