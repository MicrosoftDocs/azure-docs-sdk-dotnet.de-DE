<Type Name="TcpClientTransportTokenAssertionProviderBindingElement" FullName="Microsoft.ServiceBus.TcpClientTransportTokenAssertionProviderBindingElement">
  <TypeSignature Language="C#" Value="public class TcpClientTransportTokenAssertionProviderBindingElement : System.ServiceModel.Channels.BindingElement, System.ServiceModel.Channels.ITransportTokenAssertionProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TcpClientTransportTokenAssertionProviderBindingElement extends System.ServiceModel.Channels.BindingElement implements class System.ServiceModel.Channels.ITransportTokenAssertionProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.TcpClientTransportTokenAssertionProviderBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class TcpClientTransportTokenAssertionProviderBindingElement&#xA;Inherits BindingElement&#xA;Implements ITransportTokenAssertionProvider" />
  <TypeSignature Language="F#" Value="type TcpClientTransportTokenAssertionProviderBindingElement = class&#xA;    inherit BindingElement&#xA;    interface ITransportTokenAssertionProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.BindingElement</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.ITransportTokenAssertionProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="9805d-101">Stellt das Transportbindungselement, das Sicherheit für Kanal über einen SSL-Datenstroms für die Verwendung in richtlinienexporten unterstützt.</span><span class="sxs-lookup"><span data-stu-id="9805d-101">Represents the transport binding element that supports channel security over an SSL stream for use in policy exports.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TcpClientTransportTokenAssertionProviderBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpClientTransportTokenAssertionProviderBindingElement.#ctor" />
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
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElement Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElement Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpClientTransportTokenAssertionProviderBindingElement.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As BindingElement" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; System.ServiceModel.Channels.BindingElement" Usage="tcpClientTransportTokenAssertionProviderBindingElement.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="9805d-102">Gibt eine Kopie dieser Instanz des Bindungselements zurück.</span><span class="sxs-lookup"><span data-stu-id="9805d-102">Returns a copy of this binding element instance.</span></span></summary>
        <returns><span data-ttu-id="9805d-103">Eine Kopie dieser Instanz des Bindungselements.</span><span class="sxs-lookup"><span data-stu-id="9805d-103">A copy of this binding element instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T GetProperty&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T GetProperty&lt;class T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpClientTransportTokenAssertionProviderBindingElement.GetProperty``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetProperty(Of T As Class) (context As BindingContext) As T" />
      <MemberSignature Language="F#" Value="override this.GetProperty : System.ServiceModel.Channels.BindingContext -&gt; 'T (requires 'T : null)" Usage="tcpClientTransportTokenAssertionProviderBindingElement.GetProperty context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="context"> <span data-ttu-id="9805d-104">Der Bindungskontext, der Kontext für das Bindungselement bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="9805d-104">The binding context that provides context for this binding element.</span></span></param>
        <summary><span data-ttu-id="9805d-105">Ein Objekt des angeforderten Typs, sofern vorhanden, von der entsprechenden Ebene im bindungsstapel zurück.</span><span class="sxs-lookup"><span data-stu-id="9805d-105">Returns an object of the requested type, if present, from the appropriate layer in the binding stack.</span></span></summary>
        <returns><span data-ttu-id="9805d-106">Das Objekt des angeforderten Typs Wenn gefunden; Andernfalls wird null zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="9805d-106">The object of the requested type if found; otherwise, returns null.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTransportTokenAssertion">
      <MemberSignature Language="C#" Value="public System.Xml.XmlElement GetTransportTokenAssertion ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Xml.XmlElement GetTransportTokenAssertion() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpClientTransportTokenAssertionProviderBindingElement.GetTransportTokenAssertion" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTransportTokenAssertion () As XmlElement" />
      <MemberSignature Language="F#" Value="abstract member GetTransportTokenAssertion : unit -&gt; System.Xml.XmlElement&#xA;override this.GetTransportTokenAssertion : unit -&gt; System.Xml.XmlElement" Usage="tcpClientTransportTokenAssertionProviderBindingElement.GetTransportTokenAssertion " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Channels.ITransportTokenAssertionProvider.GetTransportTokenAssertion</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="9805d-107">Ruft das <see cref="T:System.Xml.XmlElement" /> ab, das das Transporttoken darstellt, das in der Sicherheitsbindung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="9805d-107">Gets the <see cref="T:System.Xml.XmlElement" /> that represents the transport token used in the security binding.</span></span></summary>
        <returns><span data-ttu-id="9805d-108">Ein <see cref="T:System.Xml.XmlElement" />, das das Transporttoken darstellt, das in der Sicherheitsbindung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="9805d-108">An <see cref="T:System.Xml.XmlElement" /> that represents the transport token used in the security binding.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>